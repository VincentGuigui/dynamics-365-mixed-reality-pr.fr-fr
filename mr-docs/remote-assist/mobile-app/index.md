---
author: drpusey
description: Guide de l'utilisateur de l'application mobile Dynamics 365 Remote Assist
ms.author: drpusey
ms.date: 06/07/2019
ms.service: crm-online
ms.topic: article
title: Guide de l'utilisateur de l'application mobile Dynamics 365 Remote Assist
ms.reviewer: v-brycho
ms.openlocfilehash: 378d40c1d4722943e9b47fcb83c88851cb8b0115
ms.sourcegitcommit: 36509aebf3b012fa3ee0e9c5af0366b0186bfcd7
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 08/29/2019
ms.locfileid: "1968121"
---
# <a name="dynamics-365-remote-assist-mobile-user-guide-in-preview"></a><span data-ttu-id="66518-103">Guide de l'utilisateur de l'application Dynamics 365 Remote Assist Mobile (en version préliminaire)</span><span class="sxs-lookup"><span data-stu-id="66518-103">Dynamics 365 Remote Assist Mobile user guide (in preview)</span></span>

<span data-ttu-id="66518-104">[Cette rubrique fait partie de la documentation en version préliminaire et peut faire l'objet de modifications.]</span><span class="sxs-lookup"><span data-stu-id="66518-104">[This topic is pre-release documentation and is subject to change.]</span></span>

<span data-ttu-id="66518-105">L'application mobile [!include[cc-microsoft](../../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../../includes/pn-dyn-365-remote-assist.md)] étend les capacités de [!include[pn-dyn-365-remote-assist](../../includes/pn-dyn-365-remote-assist.md)] à l'utilisation de téléphones compatibles [!include[tn-android](../../includes/tn-android.md)] ARCore (en plus de [!include[cc-microsoft](../../includes/cc-microsoft.md)] [!include[pn-HoloLens](../../includes/pn-HoloLens.md)]).</span><span class="sxs-lookup"><span data-stu-id="66518-105">The [!include[cc-microsoft](../../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../../includes/pn-dyn-365-remote-assist.md)] mobile app extends the capabilities of [!include[pn-dyn-365-remote-assist](../../includes/pn-dyn-365-remote-assist.md)] to work with [!include[tn-android](../../includes/tn-android.md)] ARCore-capable phones (in addition to [!include[cc-microsoft](../../includes/cc-microsoft.md)]  [!include[pn-HoloLens](../../includes/pn-HoloLens.md)]).</span></span> <span data-ttu-id="66518-106">Les techniciens peuvent utiliser leurs téléphones pour se connecter et collaborer avec un expert dans [!include[pn-microsoft-teams](../../includes/pn-microsoft-teams.md)].</span><span class="sxs-lookup"><span data-stu-id="66518-106">Technicians can use their phones to connect and collaborate with an expert on [!include[pn-microsoft-teams](../../includes/pn-microsoft-teams.md)].</span></span> <span data-ttu-id="66518-107">En utilisant l'appel vidéo en direct et les annotations de réalité mixte, ils peuvent partager ce qu'ils voient avec le spécialiste pour résoudre les problèmes ensemble, plus rapidement.</span><span class="sxs-lookup"><span data-stu-id="66518-107">Using live video calling and mixed reality annotations, they can share what they see with the expert to troubleshoot problems together, faster.</span></span> 

## <a name="what-youll-need"></a><span data-ttu-id="66518-108">Ce dont vous aurez besoin</span><span class="sxs-lookup"><span data-stu-id="66518-108">What you’ll need</span></span>

<span data-ttu-id="66518-109">Vous aurez besoin des éléments suivants pour utiliser l'application mobile [!include[pn-remote-assist](../../includes/pn-remote-assist.md)] :</span><span class="sxs-lookup"><span data-stu-id="66518-109">You’ll need the following to use the [!include[pn-remote-assist](../../includes/pn-remote-assist.md)] mobile app:</span></span>

- <span data-ttu-id="66518-110">Un téléphone compatible [!include[tn-android](../../includes/tn-android.md)] ARCore (les tablettes ne sont actuellement pas prises en charge), avec ARCore installé.</span><span class="sxs-lookup"><span data-stu-id="66518-110">An [!include[tn-android](../../includes/tn-android.md)] ARCore-capable phone (tablets are not currently supported), with ARCore installed.</span></span> [<span data-ttu-id="66518-111">Consultez la liste complète des appareils pris en charge.</span><span class="sxs-lookup"><span data-stu-id="66518-111">View the full list of supported devices.</span></span>](https://developers.google.com/ar/discover/supported-devices) 

- <span data-ttu-id="66518-112">Un compte [!include[tn-google](../../includes/tn-google.md)] Play.</span><span class="sxs-lookup"><span data-stu-id="66518-112">A [!include[tn-google](../../includes/tn-google.md)] Play account.</span></span>

- <span data-ttu-id="66518-113">L'application mobile [!include[pn-remote-assist](../../includes/pn-remote-assist.md)].</span><span class="sxs-lookup"><span data-stu-id="66518-113">The [!include[pn-remote-assist](../../includes/pn-remote-assist.md)] mobile app.</span></span>

- <span data-ttu-id="66518-114">Un compte [!include[pn-microsoft-teams](../../includes/pn-microsoft-teams.md)] (disponible gratuitement).</span><span class="sxs-lookup"><span data-stu-id="66518-114">A [!include[pn-microsoft-teams](../../includes/pn-microsoft-teams.md)] account (available for free).</span></span>

- <span data-ttu-id="66518-115">Un client pour ordinateur de bureau [!include[pn-microsoft-teams](../../includes/pn-microsoft-teams.md)] exécutant [!include[pn-ms-windows-short](../../includes/pn-ms-windows-short.md)] 10 (pour l'expert distant qui reçoit l'appel).</span><span class="sxs-lookup"><span data-stu-id="66518-115">A [!include[pn-microsoft-teams](../../includes/pn-microsoft-teams.md)] desktop client running [!include[pn-ms-windows-short](../../includes/pn-ms-windows-short.md)] 10 (for the remote expert receiving the call).</span></span>

- <span data-ttu-id="66518-116">Une connexion Internet.</span><span class="sxs-lookup"><span data-stu-id="66518-116">An internet connection.</span></span> <span data-ttu-id="66518-117">Au moins 1,5 Mo de bande passante est recommandé pour optimiser l'expérience.</span><span class="sxs-lookup"><span data-stu-id="66518-117">At least 1.5 MB of bandwidth is recommended for the best experience.</span></span>

<span data-ttu-id="66518-118">Si vous souhaitez utiliser [!include[pn-remote-assist](../../includes/pn-remote-assist.md)] avec [!include[pn-dyn-365-field-service](../../includes/pn-dyn-365-field-service.md)], vous pouvez enregistrer automatiquement les informations d'un appel dans un ordre de travail [!include[pn-field-service](../../includes/pn-field-service.md)]. Vous avez également besoin de l'un ou des deux éléments suivants :</span><span class="sxs-lookup"><span data-stu-id="66518-118">If you want to use [!include[pn-remote-assist](../../includes/pn-remote-assist.md)] together with [!include[pn-dyn-365-field-service](../../includes/pn-dyn-365-field-service.md)] so you can automatically log call information to a [!include[pn-field-service](../../includes/pn-field-service.md)] work order, you’ll also need one or both of the following:</span></span>

- <span data-ttu-id="66518-119">Application web [!include[pn-dyn-365-field-service](../../includes/pn-dyn-365-field-service.md)]</span><span class="sxs-lookup"><span data-stu-id="66518-119">[!include[pn-dyn-365-field-service](../../includes/pn-dyn-365-field-service.md)] web application</span></span>

- <span data-ttu-id="66518-120">Application mobile [!include[pn-dyn-365-field-service](../../includes/pn-dyn-365-field-service.md)]</span><span class="sxs-lookup"><span data-stu-id="66518-120">[!include[pn-dyn-365-field-service](../../includes/pn-dyn-365-field-service.md)] mobile app</span></span> 

## <a name="get-started"></a><span data-ttu-id="66518-121">Mise en route</span><span class="sxs-lookup"><span data-stu-id="66518-121">Get started</span></span>

### <a name="step-1-sign-up-for-a-microsoft-teams-account-free"></a><span data-ttu-id="66518-122">Étape 1 : Inscrivez-vous à un compte Microsoft Teams (gratuit)</span><span class="sxs-lookup"><span data-stu-id="66518-122">Step 1: Sign up for a Microsoft Teams account (free)</span></span>

<span data-ttu-id="66518-123">Un compte [!include[pn-microsoft-teams](../../includes/pn-microsoft-teams.md)] est requis pour utiliser l'application mobile [!include[pn-remote-assist](../../includes/pn-remote-assist.md)].</span><span class="sxs-lookup"><span data-stu-id="66518-123">A [!include[pn-microsoft-teams](../../includes/pn-microsoft-teams.md)] account is required to use [!include[pn-remote-assist](../../includes/pn-remote-assist.md)] mobile.</span></span> <span data-ttu-id="66518-124">Si vous n'avez pas encore de compte [!include[pn-teams](../../includes/pn-teams.md)], vous pouvez [créer un compte Teams gratuitement.](https://businessstore.microsoft.com/en-us/create-account/signup?products=CFQ7TTC0K8P5:0001&lm=deeplink&lmsrc=freePageWeb&cmpid=FreemiumSignUpHeader)</span><span class="sxs-lookup"><span data-stu-id="66518-124">If you don’t already have a [!include[pn-teams](../../includes/pn-teams.md)] account, you can [create a Teams account for free](https://businessstore.microsoft.com/en-us/create-account/signup?products=CFQ7TTC0K8P5:0001&lm=deeplink&lmsrc=freePageWeb&cmpid=FreemiumSignUpHeader).</span></span> 

### <a name="step-2-download-the-app"></a><span data-ttu-id="66518-125">Étape 2 : Télécharger l'application</span><span class="sxs-lookup"><span data-stu-id="66518-125">Step 2: Download the app</span></span>

1.  <span data-ttu-id="66518-126">Accédez à [!include[tn-google](../../includes/tn-google.md)] Play Store : https://play.google.com/store/apps/details?id=com.microsoft.ramobile.</span><span class="sxs-lookup"><span data-stu-id="66518-126">Go to the [!include[tn-google](../../includes/tn-google.md)] Play Store: https://play.google.com/store/apps/details?id=com.microsoft.ramobile.</span></span>

2.  <span data-ttu-id="66518-127">Sélectionnez **Télécharger**.</span><span class="sxs-lookup"><span data-stu-id="66518-127">Select **Download**.</span></span> 
 
### <a name="step-3-sign-in-to-the-app-for-the-first-time"></a><span data-ttu-id="66518-128">Étape 3 : Se connecter à l'application pour la première fois</span><span class="sxs-lookup"><span data-stu-id="66518-128">Step 3: Sign in to the app for the first time</span></span>

1.  <span data-ttu-id="66518-129">Après avoir téléchargé l'application, ouvrez-la sur votre téléphone [!include[tn-android](../../includes/tn-android.md)].</span><span class="sxs-lookup"><span data-stu-id="66518-129">After you’ve downloaded the app, open it on your [!include[tn-android](../../includes/tn-android.md)] phone.</span></span> 

2.  <span data-ttu-id="66518-130">Connectez-vous avec votre compte [!include[pn-microsoft-teams](../../includes/pn-microsoft-teams.md)].</span><span class="sxs-lookup"><span data-stu-id="66518-130">Sign in with your [!include[pn-microsoft-teams](../../includes/pn-microsoft-teams.md)] account.</span></span>

    <span data-ttu-id="66518-131">![Écran de connexion](../media/sign-in.png "Écran de connexion")</span><span class="sxs-lookup"><span data-stu-id="66518-131">![Sign-in screen](../media/sign-in.png "Sign-in screen")</span></span>
  
    > [!TIP]
    > <span data-ttu-id="66518-132">L'adresse de connexion sera au format suivant : nomutilisateur@société.</span><span class="sxs-lookup"><span data-stu-id="66518-132">The sign-in address will be in the form: username@company.</span></span>
    
3.  <span data-ttu-id="66518-133">Dans la boîte de dialogue qui s'affiche, sélectionnez **Activer la fonctionnalité** pour lier [!include[pn-remote-assist](../../includes/pn-remote-assist.md)] à [!include[pn-dyn-365-field-service](../../includes/pn-dyn-365-field-service.md)], ou sélectionnez **Ignorer** si vous ne souhaitez pas lier l'application à ce stade.</span><span class="sxs-lookup"><span data-stu-id="66518-133">In the dialog box that appears, select **Enable Feature** to link [!include[pn-remote-assist](../../includes/pn-remote-assist.md)] to [!include[pn-dyn-365-field-service](../../includes/pn-dyn-365-field-service.md)], or select **Skip** if you don’t want to link the apps at this time.</span></span> <span data-ttu-id="66518-134">Vous pouvez toujours les lier ultérieurement via **Paramètres**.</span><span class="sxs-lookup"><span data-stu-id="66518-134">You can always link them later through **Settings**.</span></span> <span data-ttu-id="66518-135">Pour en savoir plus sur la manière dont les applications fonctionnent ensemble, sélectionnez **En savoir plus**.</span><span class="sxs-lookup"><span data-stu-id="66518-135">To learn more about how the apps work together, select **Learn More**.</span></span>

    <span data-ttu-id="66518-136">![Écran Field Service](../media/field-service.PNG "Écran Field Service")</span><span class="sxs-lookup"><span data-stu-id="66518-136">![Field Service screen](../media/field-service.PNG "Field Service screen")</span></span>
  
## <a name="make-a-call"></a><span data-ttu-id="66518-137">Effectuer un appel</span><span class="sxs-lookup"><span data-stu-id="66518-137">Make a call</span></span>
<span data-ttu-id="66518-138">Après vous être connecté, vous verrez la page **Contacts**, qui est la page principale de l'application mobile [!include[pn-remote-assist](../../includes/pn-remote-assist.md)].</span><span class="sxs-lookup"><span data-stu-id="66518-138">After signing in, you’ll see the **Contacts** page, which is the main page in the [!include[pn-remote-assist](../../includes/pn-remote-assist.md)] mobile app.</span></span> <span data-ttu-id="66518-139">Dans la page **Contacts**, vos contacts sont organisés par les appels les plus récents.</span><span class="sxs-lookup"><span data-stu-id="66518-139">On the **Contacts** page, your contacts are organized by the most recent calls.</span></span>

<span data-ttu-id="66518-140">![Écran contacts](../media/contacts.PNG "Écran contacts")</span><span class="sxs-lookup"><span data-stu-id="66518-140">![Contacts screen](../media/contacts.PNG "Contacts screen")</span></span>


<span data-ttu-id="66518-141">Pour effectuer un appel :</span><span class="sxs-lookup"><span data-stu-id="66518-141">To make a call:</span></span>

1.  <span data-ttu-id="66518-142">Sélectionnez ![bouton Rechercher](../media/search-icon.PNG "bouton Rechercher"), entrez le nom du contact à rechercher, puis sélectionnez ce contact dans la liste résultante.</span><span class="sxs-lookup"><span data-stu-id="66518-142">Select ![Search button](../media/search-icon.PNG "Search button"), enter the name of the contact to search for, and then select the contact from the resulting list.</span></span>
       
    <span data-ttu-id="66518-143">![Recherche d'un contact](../media/search-contact.PNG "Recherche d'un contact")</span><span class="sxs-lookup"><span data-stu-id="66518-143">![Search for a contact](../media/search-contact.PNG "Search for a contact")</span></span>
    
2.  <span data-ttu-id="66518-144">Dans la carte de contact, sélectionnez **Lancer l'appel**.</span><span class="sxs-lookup"><span data-stu-id="66518-144">In the contact card, select **Launch Call**.</span></span>

    <span data-ttu-id="66518-145">![Écran Lancer l'appel](../media/launch-call.PNG "Écran Lancer l'appel")</span><span class="sxs-lookup"><span data-stu-id="66518-145">![Launch Call screen](../media/launch-call.PNG "Launch Call screen")</span></span>
  
    <span data-ttu-id="66518-146">Utilisez les boutons de la barre en bas de l'écran pour mettre en sourdine l'appel, suspendre le flux vidéo, activer l'écoute amplifiée ou terminer l'appel.</span><span class="sxs-lookup"><span data-stu-id="66518-146">Use the buttons in the bar at the bottom of the screen to mute the call, pause the video feed, turn on the speaker phone, or end the call.</span></span>
    
    <span data-ttu-id="66518-147">![Commandes d'appel](../media/call-controls.PNG "Commandes d'appel")</span><span class="sxs-lookup"><span data-stu-id="66518-147">![Call controls](../media/call-controls.PNG "Call controls")</span></span>
  
 
## <a name="add-annotations"></a><span data-ttu-id="66518-148">Ajouter des annotations</span><span class="sxs-lookup"><span data-stu-id="66518-148">Add annotations</span></span>
<span data-ttu-id="66518-149">Vous pouvez ajouter des annotations à votre écran pour les partage avec un expert participant à l'appel.</span><span class="sxs-lookup"><span data-stu-id="66518-149">You can add annotations to your screen to share with an expert on the call.</span></span> <span data-ttu-id="66518-150">Pour créer des annotations, votre téléphone a besoin d'identifier au moins un plan (vertical ou horizontal) dans votre zone de travail.</span><span class="sxs-lookup"><span data-stu-id="66518-150">To create annotations, your phone needs to recognize at least one plane (vertical or horizontal) in your work area.</span></span> <span data-ttu-id="66518-151">Pour ce faire, analysez votre zone de travail avec le téléphone.</span><span class="sxs-lookup"><span data-stu-id="66518-151">You do this by scanning your work area with the phone.</span></span> <span data-ttu-id="66518-152">Lorsqu'un plan a été reconnu, vous obtenez une visualisation de confirmation et la barre d'outils d'annotation s'affiche en haut de l'écran :</span><span class="sxs-lookup"><span data-stu-id="66518-152">When a plane has been recognized, you’ll see a confirmation visualization and the annotation toolbar will appear at the top of the screen:</span></span>

<span data-ttu-id="66518-153">![Ajouter des annotations](../media/annotation-bar-full-screen.PNG "Ajouter des annotations")</span><span class="sxs-lookup"><span data-stu-id="66518-153">![Add annotations](../media/annotation-bar-full-screen.PNG "Add annotations")</span></span>
  
> [!NOTE] 
> <span data-ttu-id="66518-154">Si vous verrouillez votre téléphone ou réduisez [!include[pn-remote-assist](../../includes/pn-remote-assist.md)], les plans identifiés réapparaîtront automatiquement dès que votre téléphone reconnaît l'environnement.</span><span class="sxs-lookup"><span data-stu-id="66518-154">If you lock your phone or minimize [!include[pn-remote-assist](../../includes/pn-remote-assist.md)], the recognized planes will reappear automatically as soon as your phone recognizes the environment.</span></span>

### <a name="add-an-annotation"></a><span data-ttu-id="66518-155">Ajouter une annotation</span><span class="sxs-lookup"><span data-stu-id="66518-155">Add an annotation</span></span>
<span data-ttu-id="66518-156">Vous pouvez ajouter une annotation à l'aide des boutons de la barre d'outils d'annotation :</span><span class="sxs-lookup"><span data-stu-id="66518-156">You can add an annotation by using the buttons on the annotation toolbar:</span></span>

<span data-ttu-id="66518-157">![Barre d'annotation](../media/annotation-bar.PNG "Barre d'annotation")</span><span class="sxs-lookup"><span data-stu-id="66518-157">![Annotation bar](../media/annotation-bar.PNG "Annotation bar")</span></span>
  
<span data-ttu-id="66518-158">Par exemple, pour ajouter une flèche, cliquez sur l'outil de flèche et glissez votre doigt jusqu'à l'emplacement où vous souhaitez placer la flèche.</span><span class="sxs-lookup"><span data-stu-id="66518-158">For example, to add an arrow, tap the arrow tool and drag your finger to the spot where you want to place the arrow.</span></span>

### <a name="minimize-or-restore-the-toolbar"></a><span data-ttu-id="66518-159">Réduire ou restaurer la barre d'outils</span><span class="sxs-lookup"><span data-stu-id="66518-159">Minimize or restore the toolbar</span></span>

<span data-ttu-id="66518-160">Pour réduire la barre d'outils si vous souhaitez afficher une plus grande zone de l'écran :</span><span class="sxs-lookup"><span data-stu-id="66518-160">To minimize the toolbar if you want to see more of the screen:</span></span>

- <span data-ttu-id="66518-161">Sélectionnez la flèche à droite de la barre d'outils.</span><span class="sxs-lookup"><span data-stu-id="66518-161">Select the arrow on the right side of the toolbar.</span></span> 

  <span data-ttu-id="66518-162">![Réduire la barre](../media/minimize-bar.PNG "Réduire la barre")</span><span class="sxs-lookup"><span data-stu-id="66518-162">![Minimize bar](../media/minimize-bar.PNG "Minimize bar")</span></span>
 
<span data-ttu-id="66518-163">Pour restaurer la barre d'outils à sa taille initiale :</span><span class="sxs-lookup"><span data-stu-id="66518-163">To restore the toolbar to its original size:</span></span>

- <span data-ttu-id="66518-164">Sélectionnez le bouton **Stylo**.</span><span class="sxs-lookup"><span data-stu-id="66518-164">Select the **Pen** button.</span></span> 

  <span data-ttu-id="66518-165">![Bouton Stylo](../media/pen-button.PNG "Bouton Stylo")</span><span class="sxs-lookup"><span data-stu-id="66518-165">![Pen button](../media/pen-button.PNG "Pen button")</span></span>

### <a name="make-the-experts-video-feed-bigger"></a><span data-ttu-id="66518-166">Agrandir le flux vidéo de l'expert</span><span class="sxs-lookup"><span data-stu-id="66518-166">Make the expert’s video feed bigger</span></span>

<span data-ttu-id="66518-167">Lorsque vous appelez un expert, son flux vidéo s'affiche dans le coin inférieur droit de l'écran de votre téléphone.</span><span class="sxs-lookup"><span data-stu-id="66518-167">When you call an expert, the expert’s video feed appears in the lower-right corner of your phone screen.</span></span> <span data-ttu-id="66518-168">Pour agrandir le flux vidéo de l'expert, appuyez sur le flux.</span><span class="sxs-lookup"><span data-stu-id="66518-168">To make the expert’s video feed bigger, tap the feed.</span></span> <span data-ttu-id="66518-169">Appuyez à nouveau sur le flux pour revenir à la taille d'origine.</span><span class="sxs-lookup"><span data-stu-id="66518-169">Tap the feed again to return to the original size.</span></span>

<span data-ttu-id="66518-170">![Flux vidéo de l'expert](../media/expert-annotating.PNG "Flux vidéo de l'expert")</span><span class="sxs-lookup"><span data-stu-id="66518-170">![Expert video feed](../media/expert-annotating.PNG "Expert video feed")</span></span>
  
<span data-ttu-id="66518-171">Si l'expert annote, une icône de notification s'affiche sur le flux de l'expert.</span><span class="sxs-lookup"><span data-stu-id="66518-171">If the expert is annotating, a notification icon will appear on the expert's feed.</span></span>  

## <a name="switch-the-camera-view-from-portrait-to-landscape"></a><span data-ttu-id="66518-172">Basculer la vue de l'appareil-photo de portrait à paysage</span><span class="sxs-lookup"><span data-stu-id="66518-172">Switch the camera view from portrait to landscape</span></span>

<span data-ttu-id="66518-173">Vous pouvez changer l'orientation de la vue de l'appareil-photo de portrait à paysage en cours d'appel en modifiant l'orientation de votre téléphone.</span><span class="sxs-lookup"><span data-stu-id="66518-173">You can switch the orientation of the camera view from portrait to landscape while in a call by changing the orientation of your phone.</span></span> <span data-ttu-id="66518-174">L'utilisation de la vue Paysage offre un champ de vision plus étendu, ce qui peut améliorer l'expérience pour le spécialiste distant participant à l'appel.</span><span class="sxs-lookup"><span data-stu-id="66518-174">Using landscape view provides a wider field of view, which may improve the experience for the remote expert on the call.</span></span>
   
## <a name="use-remote-assist-together-with-dynamics-365-for-field-service"></a><span data-ttu-id="66518-175">Utiliser Remote Assist avec Dynamics 365 for Field Service</span><span class="sxs-lookup"><span data-stu-id="66518-175">Use Remote Assist together with Dynamics 365 for Field Service</span></span>

<span data-ttu-id="66518-176">Vous pouvez utiliser [!include[pn-remote-assist](../../includes/pn-remote-assist.md)] avec [!include[pn-dyn-365-field-service](../../includes/pn-dyn-365-field-service.md)] si vous souhaitez enregistrer automatiquement les informations d'un appel dans un ordre de travail [!include[pn-field-service](../../includes/pn-field-service.md)] lorsque vous terminez l'appel.</span><span class="sxs-lookup"><span data-stu-id="66518-176">You can use [!include[pn-remote-assist](../../includes/pn-remote-assist.md)] together with [!include[pn-dyn-365-field-service](../../includes/pn-dyn-365-field-service.md)] if you want to automatically log call information to a [!include[pn-field-service](../../includes/pn-field-service.md)] work order when you end the call.</span></span> 

<span data-ttu-id="66518-177">Lorsque vous vous connectez à l'application mobile [!include[pn-remote-assist](../../includes/pn-remote-assist.md)] pour la première fois, vous êtes invité à lier [!include[pn-remote-assist](../../includes/pn-remote-assist.md)] à [!include[pn-dyn-365-field-service](../../includes/pn-dyn-365-field-service.md)].</span><span class="sxs-lookup"><span data-stu-id="66518-177">When you sign in to the [!include[pn-remote-assist](../../includes/pn-remote-assist.md)] mobile app for the first time, you’re prompted to link [!include[pn-remote-assist](../../includes/pn-remote-assist.md)] to [!include[pn-dyn-365-field-service](../../includes/pn-dyn-365-field-service.md)].</span></span> <span data-ttu-id="66518-178">Vous pouvez lier les applications via **Paramètres** si vous avez choisi de ne pas les lier lors de la première connexion.</span><span class="sxs-lookup"><span data-stu-id="66518-178">You can link the apps through **Settings** if you chose not to link them at first sign-in.</span></span>

### <a name="link-the-remote-assist-mobile-app-to-dynamics-365-for-field-service"></a><span data-ttu-id="66518-179">Lier l'application mobile Remote Assist à Dynamics 365 for Field Service</span><span class="sxs-lookup"><span data-stu-id="66518-179">Link the Remote Assist mobile app to Dynamics 365 for Field Service</span></span>

1.  <span data-ttu-id="66518-180">Sélectionnez le bouton **Menu principal** ![Bouton Menu principal](../media/main-menu-button.PNG "Bouton Menu principal").</span><span class="sxs-lookup"><span data-stu-id="66518-180">Select the **Main menu** ![Main menu button](../media/main-menu-button.PNG "Main menu button") button.</span></span>

2.  <span data-ttu-id="66518-181">Sélectionnez le bouton **Paramètres**.</span><span class="sxs-lookup"><span data-stu-id="66518-181">Select the **Settings** button.</span></span>  

3.  <span data-ttu-id="66518-182">Dans la boîte de dialogue **Paramètres**, déplacez le curseur sur actif.</span><span class="sxs-lookup"><span data-stu-id="66518-182">In the **Settings** dialog box, move the slider to on.</span></span>

    <span data-ttu-id="66518-183">![Écran Paramètres](../media/settings.PNG "Écran Paramètres")</span><span class="sxs-lookup"><span data-stu-id="66518-183">![Settings screen](../media/settings.PNG "Settings screen")</span></span>
  
### <a name="save-call-data-to-a-field-service-work-order"></a><span data-ttu-id="66518-184">Sauvegardez les données d'appel dans un ordre de travail Field Service</span><span class="sxs-lookup"><span data-stu-id="66518-184">Save call data to a Field Service work order</span></span>

1.  <span data-ttu-id="66518-185">Lorsque vous mettez un terme à l'appel, la boîte de dialogue suivante s'affiche :</span><span class="sxs-lookup"><span data-stu-id="66518-185">When you end the call, the following dialog box will appear:</span></span>

    <span data-ttu-id="66518-186">![Écran Publier dans l'ordre de travail](../media/post-to-work-order.PNG "Écran Publier dans l'ordre de travail")</span><span class="sxs-lookup"><span data-stu-id="66518-186">![Post to Work Order screen](../media/post-to-work-order.PNG "Post to Work Order screen")</span></span>
  
2.  <span data-ttu-id="66518-187">Sélectionnez **Publier**.</span><span class="sxs-lookup"><span data-stu-id="66518-187">Select **Post**.</span></span>

3.  <span data-ttu-id="66518-188">Dans l'écran **Sélectionner une réservation**, sélectionnez la réservation appropriée pour publier les données d'appels.</span><span class="sxs-lookup"><span data-stu-id="66518-188">In the **Select a Booking** screen, select the appropriate booking to post the call data to.</span></span>

    <span data-ttu-id="66518-189">![Écran Sélectionner une réservation](../media/bookings-today.PNG "Écran Sélectionner une réservation")</span><span class="sxs-lookup"><span data-stu-id="66518-189">![Select a Booking screen](../media/bookings-today.PNG "Select a Booking screen")</span></span>
  
    > [!NOTE]
    > <span data-ttu-id="66518-190">Si vous ne voyez pas la réservation recherchée, cela peut être dû au fait que vous avez accès aux instances multiples (organisations).</span><span class="sxs-lookup"><span data-stu-id="66518-190">If you don’t see the booking you’re looking for, it might be because you have access to multiple instances (organizations).</span></span> <span data-ttu-id="66518-191">Pour basculer vers une instance différente, sélectionnez le bouton représentant des points de suspension (...), puis sélectionnez l'instance que vous voulez.</span><span class="sxs-lookup"><span data-stu-id="66518-191">To switch to a different instance, select the ellipsis button (...), and then select the instance you want.</span></span><br><span data-ttu-id="66518-192">![Sélectionnez l'instance](../media/select-instance.PNG "Sélectionnez l'instance")</span><span class="sxs-lookup"><span data-stu-id="66518-192">![Select instance](../media/select-instance.PNG "Select instance")</span></span>
    
## <a name="sign-out-of-the-app"></a><span data-ttu-id="66518-193">Se déconnecter de l'application</span><span class="sxs-lookup"><span data-stu-id="66518-193">Sign out of the app</span></span>

1.  <span data-ttu-id="66518-194">Sélectionnez le bouton **Menu principal** ![Bouton Menu principal](../media/main-menu-button.PNG "Bouton Menu principal").</span><span class="sxs-lookup"><span data-stu-id="66518-194">Select the **Main menu** ![Main menu button](../media/main-menu-button.PNG "Main menu button") button.</span></span>

2.  <span data-ttu-id="66518-195">Sélectionnez **Se déconnecter**.</span><span class="sxs-lookup"><span data-stu-id="66518-195">Select **Sign Out**.</span></span>

## <a name="get-help"></a><span data-ttu-id="66518-196">Obtenir de l'aide</span><span class="sxs-lookup"><span data-stu-id="66518-196">Get Help</span></span>

1.  <span data-ttu-id="66518-197">Sélectionnez le bouton **Menu principal** ![Bouton Menu principal](../media/main-menu-button.PNG "Bouton Menu principal").</span><span class="sxs-lookup"><span data-stu-id="66518-197">Select the **Main menu** ![Main menu button](../media/main-menu-button.PNG "Main menu button") button.</span></span>

2.  <span data-ttu-id="66518-198">Sélectionnez **?**.</span><span class="sxs-lookup"><span data-stu-id="66518-198">Select **Help**.</span></span>

## <a name="get-support-or-provide-feedback"></a><span data-ttu-id="66518-199">Obtenir un support ou fournir des commentaires</span><span class="sxs-lookup"><span data-stu-id="66518-199">Get support or provide feedback</span></span>

<span data-ttu-id="66518-200">Si vous souhaitez obtenir un accès direct au forum de l'équipe du produit et fournir des commentaires sur la version préliminaire de l'application mobile :</span><span class="sxs-lookup"><span data-stu-id="66518-200">If you’d like to get direct access to the product team forum and provide feedback on the mobile app preview:</span></span>

1.  <span data-ttu-id="66518-201">Inscrivez-vous au Programme Insider de version préliminaire publique de [!include[pn-dyn-365-remote-assist](../../includes/pn-dyn-365-remote-assist.md)] Mobile à l'adresse suivante : https://experience.dynamics.com.</span><span class="sxs-lookup"><span data-stu-id="66518-201">Sign up for the [!include[pn-dyn-365-remote-assist](../../includes/pn-dyn-365-remote-assist.md)] Mobile Public Preview Insiders Program at https://experience.dynamics.com.</span></span> 


2.  <span data-ttu-id="66518-202">Cochez la case **Programme Insider**, ce qui vous conduira à l'application du programme Insider.</span><span class="sxs-lookup"><span data-stu-id="66518-202">Select the **Insider Program** box, which will lead you to the Insider Program application.</span></span>

    <span data-ttu-id="66518-203">![Bouton Programme Insider](../media/insiders-program.PNG "Bouton Programme Insider")</span><span class="sxs-lookup"><span data-stu-id="66518-203">![Insider Program button](../media/insiders-program.PNG "Insider Program button")</span></span>
 
<span data-ttu-id="66518-204">Vous pouvez également fournir des commentaires directement depuis l'application en procédant comme suit :</span><span class="sxs-lookup"><span data-stu-id="66518-204">You can also provide feedback directly from the app by using the following procedure:</span></span>

1.  <span data-ttu-id="66518-205">Sélectionnez le bouton **Menu principal** ![Bouton Menu principal](../media/main-menu-button.PNG "Bouton Menu principal").</span><span class="sxs-lookup"><span data-stu-id="66518-205">Select the **Main menu** ![Main menu button](../media/main-menu-button.PNG "Main menu button") button.</span></span>

2.  <span data-ttu-id="66518-206">Sélectionnez **Commentaires**.</span><span class="sxs-lookup"><span data-stu-id="66518-206">Select **Feedback**.</span></span>

### <a name="see-also"></a><span data-ttu-id="66518-207">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="66518-207">See also</span></span>

[<span data-ttu-id="66518-208">Détecter les problèmes d'intégration de Dynamics 365 for Field Service dans Remote Assist</span><span class="sxs-lookup"><span data-stu-id="66518-208">Troubleshoot Dynamics 365 for Field Service integration with Remote Assist</span></span>](../troubleshoot-field-service.md)
