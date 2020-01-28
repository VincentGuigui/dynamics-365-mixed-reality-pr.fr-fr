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
# <a name="launch-dynamics-365-remote-assist-from-another-app-protocol-activation"></a><span data-ttu-id="8cce1-103">Lancer Dynamics 365 Remote Assist à partir d'une autre application (activation de protocole)</span><span class="sxs-lookup"><span data-stu-id="8cce1-103">Launch Dynamics 365 Remote Assist from another app (protocol activation)</span></span>

<span data-ttu-id="8cce1-104">Vous pouvez incorporer le code dans votre application [!include[pn-hololens](../includes/pn-hololens.md)] pour basculer vers [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] et commencer un appel à l'aide d'un Uniform Resource Identifier (URI).</span><span class="sxs-lookup"><span data-stu-id="8cce1-104">You can embed code in your [!include[pn-hololens](../includes/pn-hololens.md)] application to switch to [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] and begin a call using a Uniform Resource Identifier (URI).</span></span>

<span data-ttu-id="8cce1-105">Par exemple, supposons que vous créez une application pour la maintenance d'hélicoptères.</span><span class="sxs-lookup"><span data-stu-id="8cce1-105">For example, let’s say you’re creating a helicopter maintenance app.</span></span> <span data-ttu-id="8cce1-106">Vous pouvez ajouter un bouton qu'un ingénieur de maintenance pourra utiliser pour appeler un expert s'il est bloqué.</span><span class="sxs-lookup"><span data-stu-id="8cce1-106">You can add a button that a maintenance engineer can use to call an expert if they get stuck.</span></span> <span data-ttu-id="8cce1-107">Ce bouton lancera [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] et appellera l'expert désigné.</span><span class="sxs-lookup"><span data-stu-id="8cce1-107">The button will launch [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] and call the designated expert.</span></span>

[!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] <span data-ttu-id="8cce1-108">prend en charge deux méthodes pour l'activation du protocole :</span><span class="sxs-lookup"><span data-stu-id="8cce1-108">supports two methods for protocol activation:</span></span> 

-   <span data-ttu-id="8cce1-109">“ms-voip-video” concerne l'appel vidéo.</span><span class="sxs-lookup"><span data-stu-id="8cce1-109">“ms-voip-video” is for video-enabled calling.</span></span>

-   <span data-ttu-id="8cce1-110">“ms-voip-call” concerne l'appel audio.</span><span class="sxs-lookup"><span data-stu-id="8cce1-110">“ms-voip-call” is for audio-only calling.</span></span>

<span data-ttu-id="8cce1-111">Ces deux méthodes utilisent le même schéma d'argument qui accepte un champ « contactID ».</span><span class="sxs-lookup"><span data-stu-id="8cce1-111">Both methods use the same argument schema, which accepts a “contactID” field.</span></span>
<span data-ttu-id="8cce1-112">L'URI ressemblerait à ceci :</span><span class="sxs-lookup"><span data-stu-id="8cce1-112">The URI would look something like this:</span></span>

`
ms-voip-video:?contactids=\<contactID\>
`

<span data-ttu-id="8cce1-113">L'ID contact est l'ID objet [!include[pn-azure-active-directory](../includes/pn-azure-active-directory.md)] ([!include[pn-azure](../includes/pn-azure.md)] AD) de l'utilisateur.</span><span class="sxs-lookup"><span data-stu-id="8cce1-113">The contact ID is the user’s [!include[pn-azure-active-directory](../includes/pn-azure-active-directory.md)] ([!include[pn-azure](../includes/pn-azure.md)] AD) object ID.</span></span>

## <a name="code-example"></a><span data-ttu-id="8cce1-114">Exemple de code</span><span class="sxs-lookup"><span data-stu-id="8cce1-114">Code example</span></span>

<span data-ttu-id="8cce1-115">Vous devez incorporer le code dans votre application [!include[pn-hololens](../includes/pn-hololens.md)].</span><span class="sxs-lookup"><span data-stu-id="8cce1-115">You’ll need to embed the code in your [!include[pn-hololens](../includes/pn-hololens.md)] app.</span></span> <span data-ttu-id="8cce1-116">L'exemple de code suivant est écrit en C++, mais peut être facilement adapté à un autre langage.</span><span class="sxs-lookup"><span data-stu-id="8cce1-116">The following code example is written in C++, but can be easily adapted to another language.</span></span>

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

<span data-ttu-id="8cce1-117">Pour passer un appel audio uniquement au lieu de vidéo, utilisez l'URI : “ms-voip-call:?contactids=”</span><span class="sxs-lookup"><span data-stu-id="8cce1-117">To place an audio-only call instead of video, use URI: “ms-voip-call:?contactids=”</span></span>

## <a name="return-to-your-app-at-the-end-of-a-call"></a><span data-ttu-id="8cce1-118">Revenir à votre application à la fin d'un appel</span><span class="sxs-lookup"><span data-stu-id="8cce1-118">Return to your app at the end of a call</span></span>

<span data-ttu-id="8cce1-119">Un champ supplémentaire « returnto » peut être inclus pour que Dynamics 365 Remote Assist puisse revenir à votre application à la fin d'un appel.</span><span class="sxs-lookup"><span data-stu-id="8cce1-119">An additional "returnto" field can be included to have Dynamics 365 Remote Assist return to your application when a call ends.</span></span> <span data-ttu-id="8cce1-120">Les utilisateurs peuvent ainsi commencer et mettre fin à leur expérience dans votre application sans avoir à basculer manuellement de l'une à l'autre.</span><span class="sxs-lookup"><span data-stu-id="8cce1-120">This enables users to both start and end their experience in your app without having to manually switch between them.</span></span>

<span data-ttu-id="8cce1-121">Pour prendre en charge le champ « returnto », vous devez enregistrer votre application avec un URI personnalisé (voir [Enregistrer une application avec un URI personnalisé](<https://docs.microsoft.com/windows/uwp/launch-resume/handle-uri-activation#step-1-specify-the-extension-point-in-the-package-manifest>)).</span><span class="sxs-lookup"><span data-stu-id="8cce1-121">To support the "returnto" field, you need to register your app with a custom URI (see [Register an app with a custom URI](<https://docs.microsoft.com/windows/uwp/launch-resume/handle-uri-activation#step-1-specify-the-extension-point-in-the-package-manifest>)).</span></span>

<span data-ttu-id="8cce1-122">Ajoutez ensuite le champ facultatif « returnto » ainsi que le nom de l'application enregistrée que vous avez renseigné à l'étape précédente.</span><span class="sxs-lookup"><span data-stu-id="8cce1-122">Then include the optional "returnto" field along with the registered app name you completed in the previous step.</span></span> <span data-ttu-id="8cce1-123">Dans l'exemple ci-dessous, « helicoptor-maintenance-app » est l'URI enregistré :</span><span class="sxs-lookup"><span data-stu-id="8cce1-123">In the example below, "helicoptor-maintenance-app" is the registered URI:</span></span>

`
ms-voip-call:?contactids=<CONTACT_ID>&returnto=helicoptor-maintenance-app");
`

### <a name="example-of-launching-dynamics-365-remote-assist-from-your-app-with-optional-returnto-field"></a><span data-ttu-id="8cce1-124">Exemple de lancement de Dynamics 365 Remote Assist à partir de votre application avec le champ facultatif « returnto »</span><span class="sxs-lookup"><span data-stu-id="8cce1-124">Example of launching Dynamics 365 Remote Assist from your app with optional returnto field</span></span>

<span data-ttu-id="8cce1-125">L'exemple de code suivant est écrit en C++, mais peut être facilement adapté à un autre langage.</span><span class="sxs-lookup"><span data-stu-id="8cce1-125">The following code example is written in C++, but can be easily adapted to another language.</span></span>

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

## <a name="place-a-call-to-test-your-code"></a><span data-ttu-id="8cce1-126">Passer un appel pour tester votre code</span><span class="sxs-lookup"><span data-stu-id="8cce1-126">Place a call to test your code</span></span>

1.  <span data-ttu-id="8cce1-127">Exécutez votre application sur l'[!include[pn-hololens](../includes/pn-hololens.md)].</span><span class="sxs-lookup"><span data-stu-id="8cce1-127">Run your app on the [!include[pn-hololens](../includes/pn-hololens.md)].</span></span>

2.  <span data-ttu-id="8cce1-128">Initialisez l'appel depuis votre application.</span><span class="sxs-lookup"><span data-stu-id="8cce1-128">Initiate the call from your app.</span></span>

3.  <span data-ttu-id="8cce1-129">L'[!include[pn-hololens](../includes/pn-hololens.md)] s'affiche pour fermer l'application, ouvrez [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] s'il n'est pas déjà ouvert et connectez-vous.</span><span class="sxs-lookup"><span data-stu-id="8cce1-129">The [!include[pn-hololens](../includes/pn-hololens.md)] will appear to close the app, open [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] if it isn’t already open, and sign in.</span></span>

4.  <span data-ttu-id="8cce1-130">Une fois le panneau de contacts chargé, [!include[pn-remote-assist](../includes/pn-remote-assist.md)] passe un appel au contact spécifié.</span><span class="sxs-lookup"><span data-stu-id="8cce1-130">After the contacts panel is loaded, [!include[pn-remote-assist](../includes/pn-remote-assist.md)] will place a call to the specified contact.</span></span>

### <a name="see-also"></a><span data-ttu-id="8cce1-131">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="8cce1-131">See also</span></span>

<span data-ttu-id="8cce1-132">Pour plus de détails sur le lancement d'une application avec un URI, voir[Lancer une application avec un URI](<https://docs.microsoft.com/windows/uwp/launch-resume/launch-app-with-uri>).</span><span class="sxs-lookup"><span data-stu-id="8cce1-132">For more details on launching an app with a URI, see [Launch an app with a URI](<https://docs.microsoft.com/windows/uwp/launch-resume/launch-app-with-uri>).</span></span>
