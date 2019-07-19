---
author: jevertt
description: Lancer Dynamics 365 Remote Assist à partir d'une autre application (activation de protocole)
ms.author: jevertt
ms.date: 09/21/2018
ms.service: crm-online
ms.topic: article
title: Lancer Dynamics 365 Remote Assist à partir d'une autre application
ms.reviewer: v-brycho
ms.openlocfilehash: 3c11f917f9d948dab2c8f06a70e8b363801c5167
ms.sourcegitcommit: 0cb918a4505c43abfb65ca9aab9e5b3cd71211a0
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/22/2019
ms.locfileid: "1594115"
---
# <a name="launch-dynamics-365-remote-assist-from-another-app-protocol-activation"></a>Lancer Dynamics 365 Remote Assist à partir d'une autre application (activation de protocole)

Vous pouvez incorporer le code dans votre application [!include[pn-hololens](../includes/pn-hololens.md)] pour basculer vers [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] et commencer un appel à l'aide d'un Uniform Resource Identifier (URI).
Par exemple, supposons que vous créez une application pour la maintenance d'hélicoptères. Vous pouvez ajouter un bouton qu'un ingénieur de maintenance pourra utiliser pour appeler un expert s'il est bloqué. Ce bouton lancera [!include[pn-remote-assist](../includes/pn-remote-assist.md)] et appellera l'expert désigné.

[!include[pn-remote-assist](../includes/pn-remote-assist.md)] prend en charge deux méthodes pour l'activation du protocole : 

-   “ms-voip-video” concerne l'appel vidéo.

-   “ms-voip-call” concerne l'appel audio.

Ces deux méthodes utilisent le même schéma d'argument qui accepte un champ « contactID ».
L'URI ressemblerait à ceci :

`
ms-voip-video:?contactids=\<contactID\>
`

L'ID contact est l'ID objet [!include[pn-azure-active-directory](../includes/pn-azure-active-directory.md)] ([!include[pn-azure](../includes/pn-azure.md)] AD) de l'utilisateur.

## <a name="code-sample"></a>Exemple de code

Vous devez incorporer le code dans votre application [!include[pn-hololens](../includes/pn-hololens.md)]. L'exemple de code suivant est écrit dans C++, mais peut être facilement adapté à une autre langue.

```
Platform::String\^ id = objectId-\>Text;
auto uri = ref new Windows::Foundation::Uri("ms-voip-video:?contactids=" + id);
resultText-\>Text = uri-\>AbsoluteUri; 

concurrency::task\<bool\> launchUriOperation(Windows::System::Launcher::LaunchUriAsync(uri));
launchUriOperation.then([this](bool success)   
{         
    if (success)         
    {             
        // URI launched  
        resultText-\>Text += " (URI Launched)"; 
    } 
    else         
    {             
        // URI launch failed             
        resultText-\>Text += " (FAILED)";
    }     
});  
```

Pour passer un appel audio uniquement au lieu de vidéo, utilisez l'URI : “ms-voip-call:?contactids=”

## <a name="place-a-call-to-test-your-code"></a>Passez un appel pour tester votre code

1.  Exécutez votre application sur l'[!include[pn-hololens](../includes/pn-hololens.md)].

2.  Initialisez l'appel depuis votre application.

3.  L'[!include[pn-hololens](../includes/pn-hololens.md)] s'affiche pour fermer l'application, ouvrez [!include[pn-remote-assist](../includes/pn-remote-assist.md)] s'il n'est pas déjà ouvert et connectez-vous.

4.  Une fois le panneau de contacts chargé, [!include[pn-remote-assist](../includes/pn-remote-assist.md)] passe un appel au contact spécifié.

### <a name="see-also"></a>Voir aussi

Pour plus de détails sur le lancement d'une application avec un URI, voir[Lancer une application avec un URI](<https://docs.microsoft.com/en-us/windows/uwp/launch-resume/launch-app-with-uri>).
