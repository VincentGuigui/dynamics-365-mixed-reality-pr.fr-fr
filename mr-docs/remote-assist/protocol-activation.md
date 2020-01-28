---
author: bencorn
description: Lancer Dynamics 365 Remote Assist à partir d'une autre application (activation de protocole)
ms.author: bencorn
ms.date: 10/01/2019
ms.service: crm-online
ms.topic: article
title: Lancer Dynamics 365 Remote Assist à partir d'une autre application
ms.reviewer: v-brycho
ms.openlocfilehash: 0165c27c7148fb1ef2f5d4057230724d859900b4
ms.sourcegitcommit: 56579384c418edd4f37cd750751fc8e4d8883a65
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 12/20/2019
ms.locfileid: "2921066"
---
# <a name="launch-dynamics-365-remote-assist-from-another-app-protocol-activation"></a>Lancer Dynamics 365 Remote Assist à partir d'une autre application (activation de protocole)

Vous pouvez incorporer le code dans votre application [!include[pn-hololens](../includes/pn-hololens.md)] pour basculer vers [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] et commencer un appel à l'aide d'un Uniform Resource Identifier (URI).

Par exemple, supposons que vous créez une application pour la maintenance d'hélicoptères. Vous pouvez ajouter un bouton qu'un ingénieur de maintenance pourra utiliser pour appeler un expert s'il est bloqué. Ce bouton lancera [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] et appellera l'expert désigné.

[!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] prend en charge deux méthodes pour l'activation du protocole : 

-   “ms-voip-video” concerne l'appel vidéo.

-   “ms-voip-call” concerne l'appel audio.

Ces deux méthodes utilisent le même schéma d'argument qui accepte un champ « contactID ».
L'URI ressemblerait à ceci :

`
ms-voip-video:?contactids=\<contactID\>
`

L'ID contact est l'ID objet [!include[pn-azure-active-directory](../includes/pn-azure-active-directory.md)] ([!include[pn-azure](../includes/pn-azure.md)] AD) de l'utilisateur.

## <a name="code-example"></a>Exemple de code

Vous devez incorporer le code dans votre application [!include[pn-hololens](../includes/pn-hololens.md)]. L'exemple de code suivant est écrit en C++, mais peut être facilement adapté à un autre langage.

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

## <a name="return-to-your-app-at-the-end-of-a-call"></a>Revenir à votre application à la fin d'un appel

Un champ supplémentaire « returnto » peut être inclus pour que Dynamics 365 Remote Assist puisse revenir à votre application à la fin d'un appel. Les utilisateurs peuvent ainsi commencer et mettre fin à leur expérience dans votre application sans avoir à basculer manuellement de l'une à l'autre.

Pour prendre en charge le champ « returnto », vous devez enregistrer votre application avec un URI personnalisé (voir [Enregistrer une application avec un URI personnalisé](<https://docs.microsoft.com/windows/uwp/launch-resume/handle-uri-activation#step-1-specify-the-extension-point-in-the-package-manifest>)).

Ajoutez ensuite le champ facultatif « returnto » ainsi que le nom de l'application enregistrée que vous avez renseigné à l'étape précédente. Dans l'exemple ci-dessous, « helicoptor-maintenance-app » est l'URI enregistré :

`
ms-voip-call:?contactids=<CONTACT_ID>&returnto=helicoptor-maintenance-app");
`

### <a name="example-of-launching-dynamics-365-remote-assist-from-your-app-with-optional-returnto-field"></a>Exemple de lancement de Dynamics 365 Remote Assist à partir de votre application avec le champ facultatif « returnto »

L'exemple de code suivant est écrit en C++, mais peut être facilement adapté à un autre langage.

```
Platform::String^ id = objectId->Text;
auto uri = ref new Windows::Foundation::Uri("ms-voip-video:?contactids=" + id + &returnto=helicoptor-maintenance-app");
resultText->Text = uri->AbsoluteUri; 

concurrency::task<bool> launchUriOperation(Windows::System::Launcher::LaunchUriAsync(uri));
launchUriOperation.then([this](bool success)   
{         
    if (success)         
    {             
        // URI launched  
        resultText->Text += " (URI Launched)"; 
    } 
    else         
    {             
        // URI launch failed             
        resultText->Text += " (FAILED)";
    }     
});  
```

## <a name="place-a-call-to-test-your-code"></a>Passer un appel pour tester votre code

1.  Exécutez votre application sur l'[!include[pn-hololens](../includes/pn-hololens.md)].

2.  Initialisez l'appel depuis votre application.

3.  L'[!include[pn-hololens](../includes/pn-hololens.md)] s'affiche pour fermer l'application, ouvrez [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] s'il n'est pas déjà ouvert et connectez-vous.

4.  Une fois le panneau de contacts chargé, [!include[pn-remote-assist](../includes/pn-remote-assist.md)] passe un appel au contact spécifié.

### <a name="see-also"></a>Voir aussi

Pour plus de détails sur le lancement d'une application avec un URI, voir[Lancer une application avec un URI](<https://docs.microsoft.com/windows/uwp/launch-resume/launch-app-with-uri>).
