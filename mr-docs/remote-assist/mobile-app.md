---
author: MatthewJonPaul
description: Guide de l'utilisateur de Dynamics 365 Remote Assist Mobile
ms.author: mapau
ms.date: 04/02/2019
ms.service: crm-online
ms.topic: article
title: Guide de l'utilisateur de Dynamics 365 Remote Assist Mobile
ms.reviewer: v-brycho
ms.openlocfilehash: 12a63de66e562630ea4501fec0531ee9717379d1
ms.sourcegitcommit: 157b70ec12e7cc459231aa5e32d311ebc09727d8
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/25/2019
ms.locfileid: "1575482"
---
# <a name="dynamics-365-remote-assist-mobile-user-guide-in-preview"></a><span data-ttu-id="00949-103">Guide de l'utilisateur de Dynamics 365 Remote Assist Mobile (en version préliminaire)</span><span class="sxs-lookup"><span data-stu-id="00949-103">Dynamics 365 Remote Assist Mobile User Guide (in preview)</span></span>

<span data-ttu-id="00949-104">[Cette rubrique fait partie de la documentation en version préliminaire et peut faire l'objet de modifications.]</span><span class="sxs-lookup"><span data-stu-id="00949-104">[This topic is pre-release documentation and is subject to change.]</span></span>

<span data-ttu-id="00949-105">L'application Microsoft Dynamics 365 Remote Assist Mobile étend les capacités de Dynamics 365 Remote Assist à l'utilisation de téléphones compatibles Android ARCore (en plus de Microsoft HoloLens).</span><span class="sxs-lookup"><span data-stu-id="00949-105">The Microsoft Dynamics 365 Remote Assist mobile app extends the capabilities of Dynamics 365 Remote Assist to work with Android ARCore-capable phones (in addition to Microsoft HoloLens).</span></span> <span data-ttu-id="00949-106">Les techniciens peuvent utiliser leurs téléphones pour se connecter et collaborer avec un expert dans Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="00949-106">Technicians can use their phones to connect and collaborate with an expert on Microsoft Teams.</span></span> <span data-ttu-id="00949-107">En utilisant l'appel vidéo en direct et les annotations de réalité mixte, ils peuvent partager ce qu'ils voient avec l'expert pour résoudre les problèmes ensemble, plus rapidement.</span><span class="sxs-lookup"><span data-stu-id="00949-107">Using live video calling and mixed reality annotations, they can share what they see with the expert to troubleshoot problems together, faster.</span></span> 

## <a name="what-youll-need"></a><span data-ttu-id="00949-108">Ce dont vous aurez besoin</span><span class="sxs-lookup"><span data-stu-id="00949-108">What you’ll need</span></span>

<span data-ttu-id="00949-109">Vous aurez besoin des éléments suivants pour utiliser l'application Remote Assist Mobile :</span><span class="sxs-lookup"><span data-stu-id="00949-109">You’ll need the following to use the Remote Assist mobile app:</span></span>

- <span data-ttu-id="00949-110">Un téléphone compatible Android ARCore (les tablettes ne sont actuellement pas prises en charge), avec ARCore installé.</span><span class="sxs-lookup"><span data-stu-id="00949-110">An Android ARCore-capable phone (tablets are not currently supported), with ARCore installed.</span></span> [<span data-ttu-id="00949-111">Consultez la liste complète des appareils pris en charge.</span><span class="sxs-lookup"><span data-stu-id="00949-111">View the full list of supported devices.</span></span>](https://developers.google.com/ar/discover/supported-devices) 

- <span data-ttu-id="00949-112">Un compte Google Play.</span><span class="sxs-lookup"><span data-stu-id="00949-112">A Google Play account.</span></span>

- <span data-ttu-id="00949-113">L'application Remote Assist Mobile.</span><span class="sxs-lookup"><span data-stu-id="00949-113">The Remote Assist mobile app.</span></span>

- <span data-ttu-id="00949-114">Un compte Microsoft Teams (disponible gratuitement).</span><span class="sxs-lookup"><span data-stu-id="00949-114">A Microsoft Teams account (available for free).</span></span>

- <span data-ttu-id="00949-115">Un client pour ordinateur de bureau Microsoft Teams exécutant Windows 10 (pour l'expert distant qui reçoit l'appel).</span><span class="sxs-lookup"><span data-stu-id="00949-115">A Microsoft Teams desktop client running Windows 10 (for the remote expert receiving the call).</span></span>

- <span data-ttu-id="00949-116">Une connexion Internet.</span><span class="sxs-lookup"><span data-stu-id="00949-116">An internet connection.</span></span> <span data-ttu-id="00949-117">Au moins 1,5 Mo de bande passante est recommandé pour optimiser l'expérience.</span><span class="sxs-lookup"><span data-stu-id="00949-117">At least 1.5 MB of bandwidth is recommended for the best experience.</span></span>

<span data-ttu-id="00949-118">Si vous souhaitez utiliser Remote Assist avec Dynamics 365 for Field Service, vous pouvez enregistrer automatiquement les informations d'un appel dans un ordre de travail Field Service. Vous avez également besoin de l'un ou des deux éléments suivants :</span><span class="sxs-lookup"><span data-stu-id="00949-118">If you want to use Remote Assist together with Dynamics 365 for Field Service so you can automatically log call information to a Field Service work order, you’ll also need one or both of the following:</span></span>

- <span data-ttu-id="00949-119">Application web Dynamics 365 for Field Service</span><span class="sxs-lookup"><span data-stu-id="00949-119">Dynamics 365 for Field Service web application</span></span>

- <span data-ttu-id="00949-120">Application mobile Dynamics 365 for Field Service</span><span class="sxs-lookup"><span data-stu-id="00949-120">Dynamics 365 for Field Service mobile app</span></span> 

## <a name="get-started"></a><span data-ttu-id="00949-121">Mise en route</span><span class="sxs-lookup"><span data-stu-id="00949-121">Get started</span></span>

### <a name="step-1-sign-up-for-a-microsoft-teams-account-free"></a><span data-ttu-id="00949-122">Étape 1 : s'inscrire à un nouveau compte Microsoft Teams (gratuit)</span><span class="sxs-lookup"><span data-stu-id="00949-122">Step 1: Sign up for a Microsoft Teams account (free)</span></span>

<span data-ttu-id="00949-123">Un compte Microsoft Teams est requis pour utiliser l'application Remote Assist Mobile.</span><span class="sxs-lookup"><span data-stu-id="00949-123">A Microsoft Teams account is required to use Remote Assist mobile.</span></span> <span data-ttu-id="00949-124">Si vous n'avez pas encore de compte Teams, vous pouvez [créer un compte Teams gratuitement](https://businessstore.microsoft.com/en-us/create-account/signup?products=CFQ7TTC0K8P5:0001&lm=deeplink&lmsrc=freePageWeb&cmpid=FreemiumSignUpHeader).</span><span class="sxs-lookup"><span data-stu-id="00949-124">If you don’t already have a Teams account, you can [create a Teams account for free](https://businessstore.microsoft.com/en-us/create-account/signup?products=CFQ7TTC0K8P5:0001&lm=deeplink&lmsrc=freePageWeb&cmpid=FreemiumSignUpHeader).</span></span> 

### <a name="step-2-download-the-app"></a><span data-ttu-id="00949-125">Étape 2 : télécharger l'application</span><span class="sxs-lookup"><span data-stu-id="00949-125">Step 2: Download the app</span></span>

1.  <span data-ttu-id="00949-126">Accédez au Google Play Store : https://play.google.com/store/apps/details?id=com.microsoft.ramobile.</span><span class="sxs-lookup"><span data-stu-id="00949-126">Go to the Google Play Store: https://play.google.com/store/apps/details?id=com.microsoft.ramobile.</span></span>

2.  <span data-ttu-id="00949-127">Sélectionnez **Télécharger**.</span><span class="sxs-lookup"><span data-stu-id="00949-127">Select **Download**.</span></span> 
 
### <a name="step-3-sign-in-to-the-app-for-the-first-time"></a><span data-ttu-id="00949-128">Étape 3 : se connecter à l'application pour la première fois</span><span class="sxs-lookup"><span data-stu-id="00949-128">Step 3: Sign in to the app for the first time</span></span>

1.  <span data-ttu-id="00949-129">Après avoir téléchargé l'application, ouvrez-la sur votre téléphone Android.</span><span class="sxs-lookup"><span data-stu-id="00949-129">After you’ve downloaded the app, open it on your Android phone.</span></span> 

2.  <span data-ttu-id="00949-130">Connectez-vous avec votre compte Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="00949-130">Sign in with your Microsoft Teams account.</span></span>

    <span data-ttu-id="00949-131">![Écran de connexion](media/sign-in.png "Écran de connexion")</span><span class="sxs-lookup"><span data-stu-id="00949-131">![Sign-in screen](media/sign-in.png "Sign-in screen")</span></span>
  
    > [!TIP]
    > <span data-ttu-id="00949-132">L'adresse de connexion sera au format suivant : nomutilisateur@société.</span><span class="sxs-lookup"><span data-stu-id="00949-132">The sign-in address will be in the form: username@company.</span></span>
    
3.  <span data-ttu-id="00949-133">Dans la boîte de dialogue qui s'affiche, sélectionnez **Activer la fonctionnalité** pour lier Remote Assist à Dynamics 365 for Field Service, ou sélectionnez **Ignorer** si vous ne souhaitez pas lier l'application à ce stade.</span><span class="sxs-lookup"><span data-stu-id="00949-133">In the dialog box that appears, select **Enable Feature** to link Remote Assist to Dynamics 365 for Field Service, or select **Skip** if you don’t want to link the apps at this time.</span></span> <span data-ttu-id="00949-134">Vous pouvez toujours les lier ultérieurement via **Paramètres**.</span><span class="sxs-lookup"><span data-stu-id="00949-134">You can always link them later through **Settings**.</span></span> <span data-ttu-id="00949-135">Pour en savoir plus sur la manière dont les applications fonctionnent ensemble, sélectionnez **En savoir plus**.</span><span class="sxs-lookup"><span data-stu-id="00949-135">To learn more about how the apps work together, select **Learn More**.</span></span>

    <span data-ttu-id="00949-136">![Écran Field Service](media/field-service.PNG "Écran Field Service")</span><span class="sxs-lookup"><span data-stu-id="00949-136">![Field Service screen](media/field-service.PNG "Field Service screen")</span></span>
  
## <a name="make-a-call"></a><span data-ttu-id="00949-137">Effectuer un appel</span><span class="sxs-lookup"><span data-stu-id="00949-137">Make a call</span></span>
<span data-ttu-id="00949-138">Après vous être connecté, vous verrez la page **Contacts**, qui est la page principale de l'application Remote Assist Mobile.</span><span class="sxs-lookup"><span data-stu-id="00949-138">After signing in, you’ll see the **Contacts** page, which is the main page in the Remote Assist mobile app.</span></span> <span data-ttu-id="00949-139">Dans la page **Contacts**, vos contacts sont organisés par les appels les plus récents.</span><span class="sxs-lookup"><span data-stu-id="00949-139">On the **Contacts** page, your contacts are organized by the most recent calls.</span></span>

<span data-ttu-id="00949-140">![Écran contacts](media/contacts.PNG "Écran contacts")</span><span class="sxs-lookup"><span data-stu-id="00949-140">![Contacts screen](media/contacts.PNG "Contacts screen")</span></span>


<span data-ttu-id="00949-141">Pour effectuer un appel :</span><span class="sxs-lookup"><span data-stu-id="00949-141">To make a call:</span></span>

1.  <span data-ttu-id="00949-142">Sélectionnez ![bouton Rechercher](media/search-icon.PNG "bouton Rechercher"), entrez le nom du contact à rechercher, puis sélectionnez ce contact dans la liste résultante.</span><span class="sxs-lookup"><span data-stu-id="00949-142">Select ![Search button](media/search-icon.PNG "Search button"), enter the name of the contact to search for, and then select the contact from the resulting list.</span></span>
       
    <span data-ttu-id="00949-143">![Recherche d'un contact](media/search-contact.PNG "Recherche d'un contact")</span><span class="sxs-lookup"><span data-stu-id="00949-143">![Search for a contact](media/search-contact.PNG "Search for a contact")</span></span>
    
2.  <span data-ttu-id="00949-144">Dans la carte de contact, sélectionnez **Lancer l'appel**.</span><span class="sxs-lookup"><span data-stu-id="00949-144">In the contact card, select **Launch Call**.</span></span>

    <span data-ttu-id="00949-145">![Écran Lancer l'appel](media/launch-call.PNG "Écran Lancer l'appel")</span><span class="sxs-lookup"><span data-stu-id="00949-145">![Launch Call screen](media/launch-call.PNG "Launch Call screen")</span></span>
  
    <span data-ttu-id="00949-146">Utilisez les boutons de la barre en bas de l'écran pour mettre en sourdine l'appel, suspendre le flux vidéo, activer l'écoute amplifiée ou terminer l'appel.</span><span class="sxs-lookup"><span data-stu-id="00949-146">Use the buttons in the bar at the bottom of the screen to mute the call, pause the video feed, turn on the speaker phone, or end the call.</span></span>
    
    <span data-ttu-id="00949-147">![Commandes d'appel](media/call-controls.PNG "Commandes d'appel")</span><span class="sxs-lookup"><span data-stu-id="00949-147">![Call controls](media/call-controls.PNG "Call controls")</span></span>
  
 
## <a name="add-annotations"></a><span data-ttu-id="00949-148">Ajouter des annotations</span><span class="sxs-lookup"><span data-stu-id="00949-148">Add annotations</span></span>
<span data-ttu-id="00949-149">Vous pouvez ajouter des annotations à votre écran pour les partage avec un expert participant à l'appel.</span><span class="sxs-lookup"><span data-stu-id="00949-149">You can add annotations to your screen to share with an expert on the call.</span></span> <span data-ttu-id="00949-150">Pour créer des annotations, votre téléphone a besoin d'identifier au moins un plan (vertical ou horizontal) dans votre zone de travail.</span><span class="sxs-lookup"><span data-stu-id="00949-150">To create annotations, your phone needs to recognize at least one plane (vertical or horizontal) in your work area.</span></span> <span data-ttu-id="00949-151">Pour ce faire, analysez votre zone de travail avec le téléphone.</span><span class="sxs-lookup"><span data-stu-id="00949-151">You do this by scanning your work area with the phone.</span></span> <span data-ttu-id="00949-152">Lorsqu'un plan a été reconnu, vous obtenez une visualisation de confirmation et la barre d'outils d'annotation s'affiche en haut de l'écran :</span><span class="sxs-lookup"><span data-stu-id="00949-152">When a plane has been recognized, you’ll see a confirmation visualization and the annotation toolbar will appear at the top of the screen:</span></span>

<span data-ttu-id="00949-153">![Ajouter des annotations](media/annotation-bar-full-screen.PNG "Ajouter des annotations")</span><span class="sxs-lookup"><span data-stu-id="00949-153">![Add annotations](media/annotation-bar-full-screen.PNG "Add annotations")</span></span>
  
> [!NOTE] 
> <span data-ttu-id="00949-154">Si vous verrouillez votre téléphone ou réduisez Remote Assist, les plans identifiés réapparaîtront automatiquement dès que votre téléphone reconnaît l'environnement.</span><span class="sxs-lookup"><span data-stu-id="00949-154">If you lock your phone or minimize Remote Assist, the recognized planes will reappear automatically as soon as your phone recognizes the environment.</span></span>

### <a name="add-an-annotation"></a><span data-ttu-id="00949-155">Ajouter une annotation</span><span class="sxs-lookup"><span data-stu-id="00949-155">Add an annotation</span></span>
<span data-ttu-id="00949-156">Vous pouvez ajouter une annotation à l'aide des boutons de la barre d'outils d'annotation :</span><span class="sxs-lookup"><span data-stu-id="00949-156">You can add an annotation by using the buttons on the annotation toolbar:</span></span>

<span data-ttu-id="00949-157">![Barre d'annotation](media/annotation-bar.PNG "Barre d'annotation")</span><span class="sxs-lookup"><span data-stu-id="00949-157">![Annotation bar](media/annotation-bar.PNG "Annotation bar")</span></span>
  
<span data-ttu-id="00949-158">Par exemple, pour ajouter une flèche, cliquez sur l'outil de flèche et glissez votre doigt jusqu'à l'emplacement où vous souhaitez placer la flèche.</span><span class="sxs-lookup"><span data-stu-id="00949-158">For example, to add an arrow, tap the arrow tool and drag your finger to the spot where you want to place the arrow.</span></span>

### <a name="minimize-or-restore-the-toolbar"></a><span data-ttu-id="00949-159">Réduire ou restaurer la barre d'outils</span><span class="sxs-lookup"><span data-stu-id="00949-159">Minimize or restore the toolbar</span></span>

<span data-ttu-id="00949-160">Pour réduire la barre d'outils si vous souhaitez afficher une plus grande zone de l'écran :</span><span class="sxs-lookup"><span data-stu-id="00949-160">To minimize the toolbar if you want to see more of the screen:</span></span>

- <span data-ttu-id="00949-161">Sélectionnez la flèche à droite de la barre d'outils.</span><span class="sxs-lookup"><span data-stu-id="00949-161">Select the arrow on the right side of the toolbar.</span></span> 

  <span data-ttu-id="00949-162">![Réduire la barre](media/minimize-bar.PNG "Réduire la barre")</span><span class="sxs-lookup"><span data-stu-id="00949-162">![Minimize bar](media/minimize-bar.PNG "Minimize bar")</span></span>
 
<span data-ttu-id="00949-163">Pour restaurer la barre d'outils à sa taille initiale :</span><span class="sxs-lookup"><span data-stu-id="00949-163">To restore the toolbar to its original size:</span></span>

- <span data-ttu-id="00949-164">Sélectionnez le bouton **Stylo**.</span><span class="sxs-lookup"><span data-stu-id="00949-164">Select the **Pen** button.</span></span> 

  <span data-ttu-id="00949-165">![Bouton Stylo](media/pen-button.PNG "Bouton Stylo")</span><span class="sxs-lookup"><span data-stu-id="00949-165">![Pen button](media/pen-button.PNG "Pen button")</span></span>

### <a name="make-the-experts-video-feed-bigger"></a><span data-ttu-id="00949-166">Agrandir le flux vidéo de l'expert</span><span class="sxs-lookup"><span data-stu-id="00949-166">Make the expert’s video feed bigger</span></span>

<span data-ttu-id="00949-167">Lorsque vous appelez un expert, son flux vidéo s'affiche dans le coin inférieur droit de l'écran de votre téléphone.</span><span class="sxs-lookup"><span data-stu-id="00949-167">When you call an expert, the expert’s video feed appears in the lower-right corner of your phone screen.</span></span> <span data-ttu-id="00949-168">Pour agrandir le flux vidéo de l'expert, appuyez sur le flux.</span><span class="sxs-lookup"><span data-stu-id="00949-168">To make the expert’s video feed bigger, tap the feed.</span></span> <span data-ttu-id="00949-169">Appuyez à nouveau sur le flux pour revenir à la taille d'origine.</span><span class="sxs-lookup"><span data-stu-id="00949-169">Tap the feed again to return to the original size.</span></span>

<span data-ttu-id="00949-170">![Flux vidéo de l'expert](media/expert-annotating.PNG "Flux vidéo de l'expert")</span><span class="sxs-lookup"><span data-stu-id="00949-170">![Expert video feed](media/expert-annotating.PNG "Expert video feed")</span></span>
  
<span data-ttu-id="00949-171">Si l'expert annote, une icône de notification s'affiche sur le flux de l'expert.</span><span class="sxs-lookup"><span data-stu-id="00949-171">If the expert is annotating, a notification icon will appear on the expert's feed.</span></span>  

## <a name="switch-the-camera-view-from-portrait-to-landscape"></a><span data-ttu-id="00949-172">Basculer la vue de l'appareil-photo de portrait à paysage</span><span class="sxs-lookup"><span data-stu-id="00949-172">Switch the camera view from portrait to landscape</span></span>

<span data-ttu-id="00949-173">Vous pouvez changer l'orientation de la vue de l'appareil-photo de portrait à paysage en cours d'appel en modifiant l'orientation de votre téléphone.</span><span class="sxs-lookup"><span data-stu-id="00949-173">You can switch the orientation of the camera view from portrait to landscape while in a call by changing the orientation of your phone.</span></span> <span data-ttu-id="00949-174">L'utilisation de la vue Paysage offre un champ de vision plus étendu, ce qui peut améliorer l'expérience pour l'expert distant participant à l'appel.</span><span class="sxs-lookup"><span data-stu-id="00949-174">Using landscape view provides a wider field of view, which may improve the experience for the remote expert on the call.</span></span>
   
## <a name="use-remote-assist-together-with-dynamics-365-for-field-service"></a><span data-ttu-id="00949-175">Utiliser Remote Assist avec Dynamics 365 for Field Service</span><span class="sxs-lookup"><span data-stu-id="00949-175">Use Remote Assist together with Dynamics 365 for Field Service</span></span>

<span data-ttu-id="00949-176">Vous pouvez utiliser Remote Assist avec Dynamics 365 for Field Service si vous souhaitez enregistrer automatiquement les informations d'un appel dans un ordre de travail Field Service lorsque vous terminez l'appel.</span><span class="sxs-lookup"><span data-stu-id="00949-176">You can use Remote Assist together with Dynamics 365 for Field Service if you want to automatically log call information to a Field Service work order when you end the call.</span></span> 

<span data-ttu-id="00949-177">Lorsque vous vous connectez à l'application Remote Assist Mobile pour la première fois, vous êtes invité à lier Remote Assist à Dynamics 365 for Field Service.</span><span class="sxs-lookup"><span data-stu-id="00949-177">When you sign in to the Remote Assist mobile app for the first time, you’re prompted to link Remote Assist to Dynamics 365 for Field Service.</span></span> <span data-ttu-id="00949-178">Vous pouvez lier les applications via Paramètres si vous avez choisi de ne pas les lier lors de la première connexion.</span><span class="sxs-lookup"><span data-stu-id="00949-178">You can link the apps through Settings if you chose not to link them at first sign-in.</span></span>

### <a name="link-the-remote-assist-mobile-app-to-dynamics-365-for-field-service"></a><span data-ttu-id="00949-179">Lier l'application mobile Remote Assist à Dynamics 365 for Field Service</span><span class="sxs-lookup"><span data-stu-id="00949-179">Link the Remote Assist mobile app to Dynamics 365 for Field Service</span></span>

1.  <span data-ttu-id="00949-180">Sélectionnez le bouton **Menu principal** ![Bouton Menu principal](media/main-menu-button.PNG "Bouton Menu principal").</span><span class="sxs-lookup"><span data-stu-id="00949-180">Select the **Main menu** ![Main menu button](media/main-menu-button.PNG "Main menu button") button.</span></span>

2.  <span data-ttu-id="00949-181">Sélectionnez le bouton **Paramètres**.</span><span class="sxs-lookup"><span data-stu-id="00949-181">Select the **Settings** button.</span></span>  

3.  <span data-ttu-id="00949-182">Dans la boîte de dialogue **Paramètres**, déplacez le curseur sur actif.</span><span class="sxs-lookup"><span data-stu-id="00949-182">In the **Settings** dialog box, move the slider to on.</span></span>

    <span data-ttu-id="00949-183">![Écran Paramètres](media/settings.PNG "Écran Paramètres")</span><span class="sxs-lookup"><span data-stu-id="00949-183">![Settings screen](media/settings.PNG "Settings screen")</span></span>
  
### <a name="save-call-data-to-a-field-service-work-order"></a><span data-ttu-id="00949-184">Sauvegardez les données d'appel dans un ordre de travail Field Service</span><span class="sxs-lookup"><span data-stu-id="00949-184">Save call data to a Field Service work order</span></span>

1.  <span data-ttu-id="00949-185">Lorsque vous mettez un terme à l'appel, la boîte de dialogue suivante s'affiche :</span><span class="sxs-lookup"><span data-stu-id="00949-185">When you end the call, the following dialog box will appear:</span></span>

    <span data-ttu-id="00949-186">![Écran Publier dans l'ordre de travail](media/post-to-work-order.PNG "Écran Publier dans l'ordre de travail")</span><span class="sxs-lookup"><span data-stu-id="00949-186">![Post to Work Order screen](media/post-to-work-order.PNG "Post to Work Order screen")</span></span>
  
2.  <span data-ttu-id="00949-187">Sélectionnez **Publier**.</span><span class="sxs-lookup"><span data-stu-id="00949-187">Select **Post**.</span></span>


3.  <span data-ttu-id="00949-188">Dans l'écran **Sélectionner une réservation**, sélectionnez la réservation appropriée pour publier les données d'appels.</span><span class="sxs-lookup"><span data-stu-id="00949-188">In the **Select a Booking** screen, select the appropriate booking to post the call data to.</span></span>

    <span data-ttu-id="00949-189">![Écran Sélectionner une réservation](media/bookings-today.PNG "Écran Sélectionner une réservation")</span><span class="sxs-lookup"><span data-stu-id="00949-189">![Select a Booking screen](media/bookings-today.PNG "Select a Booking screen")</span></span>
  
    > [!NOTE]
    > <span data-ttu-id="00949-190">Si vous ne voyez pas la réservation recherchée, cela peut être dû au fait que vous avez accès aux instances multiples (organisations).</span><span class="sxs-lookup"><span data-stu-id="00949-190">If you don’t see the booking you’re looking for, it might be because you have access to multiple instances (organizations).</span></span> <span data-ttu-id="00949-191">Pour basculer vers une instance différente, sélectionnez le bouton représentant des points de suspension (...), puis sélectionnez l'instance que vous voulez.</span><span class="sxs-lookup"><span data-stu-id="00949-191">To switch to a different instance, select the ellipsis button (...), and then select the instance you want.</span></span><br><span data-ttu-id="00949-192">![Sélectionnez l'instance](media/select-instance.PNG "Sélectionnez l'instance")</span><span class="sxs-lookup"><span data-stu-id="00949-192">![Select instance](media/select-instance.PNG "Select instance")</span></span>
    
## <a name="sign-out-of-the-app"></a><span data-ttu-id="00949-193">Se déconnecter de l'application</span><span class="sxs-lookup"><span data-stu-id="00949-193">Sign out of the app</span></span>

1.  <span data-ttu-id="00949-194">Sélectionnez le bouton **Menu principal** ![Bouton Menu principal](media/main-menu-button.PNG "Bouton Menu principal").</span><span class="sxs-lookup"><span data-stu-id="00949-194">Select the **Main menu** ![Main menu button](media/main-menu-button.PNG "Main menu button") button.</span></span>

2.  <span data-ttu-id="00949-195">Sélectionnez **Se déconnecter**.</span><span class="sxs-lookup"><span data-stu-id="00949-195">Select **Sign Out**.</span></span>

## <a name="get-help"></a><span data-ttu-id="00949-196">Obtenir de l'aide</span><span class="sxs-lookup"><span data-stu-id="00949-196">Get Help</span></span>

1.  <span data-ttu-id="00949-197">Sélectionnez le bouton **Menu principal** ![Bouton Menu principal](media/main-menu-button.PNG "Bouton Menu principal").</span><span class="sxs-lookup"><span data-stu-id="00949-197">Select the **Main menu** ![Main menu button](media/main-menu-button.PNG "Main menu button") button.</span></span>

2.  <span data-ttu-id="00949-198">Sélectionnez **?**.</span><span class="sxs-lookup"><span data-stu-id="00949-198">Select **Help**.</span></span>

## <a name="get-support-or-provide-feedback"></a><span data-ttu-id="00949-199">Obtenir un support ou fournir des commentaires</span><span class="sxs-lookup"><span data-stu-id="00949-199">Get support or provide feedback</span></span>

<span data-ttu-id="00949-200">Si vous souhaitez obtenir un accès direct au forum de l'équipe du produit et fournir des commentaires sur l'aperçu de l'application mobile :</span><span class="sxs-lookup"><span data-stu-id="00949-200">If you’d like to get direct access to the product team forum and provide feedback on the mobile app preview:</span></span>

1.  <span data-ttu-id="00949-201">Inscrivez-vous au programme Insiders de préversion publique de Dynamics 365 Remote Assist Mobile à l'adresse suivante : https://experience.dynamics.com.</span><span class="sxs-lookup"><span data-stu-id="00949-201">Sign up for the Dynamics 365 Remote Assist Mobile Public Preview Insiders Program at https://experience.dynamics.com.</span></span> 


2.  <span data-ttu-id="00949-202">Cochez la case **Programme Insider**, ce qui vous conduira à l'application du programme Insider.</span><span class="sxs-lookup"><span data-stu-id="00949-202">Select the **Insider Program** box, which will lead you to the Insider Program application.</span></span>

    <span data-ttu-id="00949-203">![Bouton Programme Insider](media/insiders-program.PNG "Bouton Programme Insider")</span><span class="sxs-lookup"><span data-stu-id="00949-203">![Insider Program button](media/insiders-program.PNG "Insider Program button")</span></span>
 
<span data-ttu-id="00949-204">Vous pouvez également fournir des commentaires directement depuis l'application en procédant comme suit :</span><span class="sxs-lookup"><span data-stu-id="00949-204">You can also provide feedback directly from the app by using the following procedure:</span></span>

1.  <span data-ttu-id="00949-205">Sélectionnez le bouton **Menu principal** ![Bouton Menu principal](media/main-menu-button.PNG "Bouton Menu principal").</span><span class="sxs-lookup"><span data-stu-id="00949-205">Select the **Main menu** ![Main menu button](media/main-menu-button.PNG "Main menu button") button.</span></span>

2.  <span data-ttu-id="00949-206">Sélectionnez **Commentaires**.</span><span class="sxs-lookup"><span data-stu-id="00949-206">Select **Feedback**.</span></span>
