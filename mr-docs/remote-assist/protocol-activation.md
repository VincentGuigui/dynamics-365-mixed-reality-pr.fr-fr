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
# <a name="launch-dynamics-365-remote-assist-from-another-app-protocol-activation"></a><span data-ttu-id="10b90-103">Lancer Dynamics 365 Remote Assist à partir d'une autre application (activation de protocole)</span><span class="sxs-lookup"><span data-stu-id="10b90-103">Launch Dynamics 365 Remote Assist from another app (protocol activation)</span></span>

<span data-ttu-id="10b90-104">Vous pouvez incorporer le code dans votre application [!include[pn-hololens](../includes/pn-hololens.md)] pour basculer vers [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] et commencer un appel à l'aide d'un Uniform Resource Identifier (URI).</span><span class="sxs-lookup"><span data-stu-id="10b90-104">You can embed code in your [!include[pn-hololens](../includes/pn-hololens.md)] application to switch to [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] and begin a call using a Uniform Resource Identifier (URI).</span></span>
<span data-ttu-id="10b90-105">Par exemple, supposons que vous créez une application pour la maintenance d'hélicoptères.</span><span class="sxs-lookup"><span data-stu-id="10b90-105">For example, let’s say you’re creating a helicopter maintenance app.</span></span> <span data-ttu-id="10b90-106">Vous pouvez ajouter un bouton qu'un ingénieur de maintenance pourra utiliser pour appeler un expert s'il est bloqué.</span><span class="sxs-lookup"><span data-stu-id="10b90-106">You can add a button that a maintenance engineer can use to call an expert if they get stuck.</span></span> <span data-ttu-id="10b90-107">Ce bouton lancera [!include[pn-remote-assist](../includes/pn-remote-assist.md)] et appellera l'expert désigné.</span><span class="sxs-lookup"><span data-stu-id="10b90-107">The button will launch [!include[pn-remote-assist](../includes/pn-remote-assist.md)] and call the designated expert.</span></span>

[!include[pn-remote-assist](../includes/pn-remote-assist.md)] <span data-ttu-id="10b90-108">prend en charge deux méthodes pour l'activation du protocole :</span><span class="sxs-lookup"><span data-stu-id="10b90-108">supports two methods for protocol activation:</span></span> 

-   <span data-ttu-id="10b90-109">“ms-voip-video” concerne l'appel vidéo.</span><span class="sxs-lookup"><span data-stu-id="10b90-109">“ms-voip-video” is for video-enabled calling.</span></span>

-   <span data-ttu-id="10b90-110">“ms-voip-call” concerne l'appel audio.</span><span class="sxs-lookup"><span data-stu-id="10b90-110">“ms-voip-call” is for audio-only calling.</span></span>

<span data-ttu-id="10b90-111">Ces deux méthodes utilisent le même schéma d'argument qui accepte un champ « contactID ».</span><span class="sxs-lookup"><span data-stu-id="10b90-111">Both methods use the same argument schema, which accepts a “contactID” field.</span></span>
<span data-ttu-id="10b90-112">L'URI ressemblerait à ceci :</span><span class="sxs-lookup"><span data-stu-id="10b90-112">The URI would look something like this:</span></span>

`
ms-voip-video:?contactids=\<contactID\>
`

<span data-ttu-id="10b90-113">L'ID contact est l'ID objet [!include[pn-azure-active-directory](../includes/pn-azure-active-directory.md)] ([!include[pn-azure](../includes/pn-azure.md)] AD) de l'utilisateur.</span><span class="sxs-lookup"><span data-stu-id="10b90-113">The contact ID is the user’s [!include[pn-azure-active-directory](../includes/pn-azure-active-directory.md)] ([!include[pn-azure](../includes/pn-azure.md)] AD) object ID.</span></span>

## <a name="code-sample"></a><span data-ttu-id="10b90-114">Exemple de code</span><span class="sxs-lookup"><span data-stu-id="10b90-114">Code sample</span></span>

<span data-ttu-id="10b90-115">Vous devez incorporer le code dans votre application [!include[pn-hololens](../includes/pn-hololens.md)].</span><span class="sxs-lookup"><span data-stu-id="10b90-115">You’ll need to embed the code in your [!include[pn-hololens](../includes/pn-hololens.md)] app.</span></span> <span data-ttu-id="10b90-116">L'exemple de code suivant est écrit dans C++, mais peut être facilement adapté à une autre langue.</span><span class="sxs-lookup"><span data-stu-id="10b90-116">The following code sample is written in C++, but can be easily adapted to another language.</span></span>

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

<span data-ttu-id="10b90-117">Pour passer un appel audio uniquement au lieu de vidéo, utilisez l'URI : “ms-voip-call:?contactids=”</span><span class="sxs-lookup"><span data-stu-id="10b90-117">To place an audio-only call instead of video, use URI: “ms-voip-call:?contactids=”</span></span>

## <a name="place-a-call-to-test-your-code"></a><span data-ttu-id="10b90-118">Passez un appel pour tester votre code</span><span class="sxs-lookup"><span data-stu-id="10b90-118">Place a call to test your code</span></span>

1.  <span data-ttu-id="10b90-119">Exécutez votre application sur l'[!include[pn-hololens](../includes/pn-hololens.md)].</span><span class="sxs-lookup"><span data-stu-id="10b90-119">Run your app on the [!include[pn-hololens](../includes/pn-hololens.md)].</span></span>

2.  <span data-ttu-id="10b90-120">Initialisez l'appel depuis votre application.</span><span class="sxs-lookup"><span data-stu-id="10b90-120">Initiate the call from your app.</span></span>

3.  <span data-ttu-id="10b90-121">L'[!include[pn-hololens](../includes/pn-hololens.md)] s'affiche pour fermer l'application, ouvrez [!include[pn-remote-assist](../includes/pn-remote-assist.md)] s'il n'est pas déjà ouvert et connectez-vous.</span><span class="sxs-lookup"><span data-stu-id="10b90-121">The [!include[pn-hololens](../includes/pn-hololens.md)] will appear to close the app, open [!include[pn-remote-assist](../includes/pn-remote-assist.md)] if it isn’t already open, and sign in.</span></span>

4.  <span data-ttu-id="10b90-122">Une fois le panneau de contacts chargé, [!include[pn-remote-assist](../includes/pn-remote-assist.md)] passe un appel au contact spécifié.</span><span class="sxs-lookup"><span data-stu-id="10b90-122">After the contacts panel is loaded, [!include[pn-remote-assist](../includes/pn-remote-assist.md)] will place a call to the specified contact.</span></span>

### <a name="see-also"></a><span data-ttu-id="10b90-123">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="10b90-123">See also</span></span>

<span data-ttu-id="10b90-124">Pour plus de détails sur le lancement d'une application avec un URI, voir[Lancer une application avec un URI](<https://docs.microsoft.com/en-us/windows/uwp/launch-resume/launch-app-with-uri>).</span><span class="sxs-lookup"><span data-stu-id="10b90-124">For more details on launching an app with a URI, see [Launch an app with a URI](<https://docs.microsoft.com/en-us/windows/uwp/launch-resume/launch-app-with-uri>).</span></span>
