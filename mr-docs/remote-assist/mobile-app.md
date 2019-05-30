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
# <a name="dynamics-365-remote-assist-mobile-user-guide-in-preview"></a>Guide de l'utilisateur de Dynamics 365 Remote Assist Mobile (en version préliminaire)

[Cette rubrique fait partie de la documentation en version préliminaire et peut faire l'objet de modifications.]

L'application Microsoft Dynamics 365 Remote Assist Mobile étend les capacités de Dynamics 365 Remote Assist à l'utilisation de téléphones compatibles Android ARCore (en plus de Microsoft HoloLens). Les techniciens peuvent utiliser leurs téléphones pour se connecter et collaborer avec un expert dans Microsoft Teams. En utilisant l'appel vidéo en direct et les annotations de réalité mixte, ils peuvent partager ce qu'ils voient avec l'expert pour résoudre les problèmes ensemble, plus rapidement. 

## <a name="what-youll-need"></a>Ce dont vous aurez besoin

Vous aurez besoin des éléments suivants pour utiliser l'application Remote Assist Mobile :

- Un téléphone compatible Android ARCore (les tablettes ne sont actuellement pas prises en charge), avec ARCore installé. [Consultez la liste complète des appareils pris en charge.](https://developers.google.com/ar/discover/supported-devices) 

- Un compte Google Play.

- L'application Remote Assist Mobile.

- Un compte Microsoft Teams (disponible gratuitement).

- Un client pour ordinateur de bureau Microsoft Teams exécutant Windows 10 (pour l'expert distant qui reçoit l'appel).

- Une connexion Internet. Au moins 1,5 Mo de bande passante est recommandé pour optimiser l'expérience.

Si vous souhaitez utiliser Remote Assist avec Dynamics 365 for Field Service, vous pouvez enregistrer automatiquement les informations d'un appel dans un ordre de travail Field Service. Vous avez également besoin de l'un ou des deux éléments suivants :

- Application web Dynamics 365 for Field Service

- Application mobile Dynamics 365 for Field Service 

## <a name="get-started"></a>Mise en route

### <a name="step-1-sign-up-for-a-microsoft-teams-account-free"></a>Étape 1 : s'inscrire à un nouveau compte Microsoft Teams (gratuit)

Un compte Microsoft Teams est requis pour utiliser l'application Remote Assist Mobile. Si vous n'avez pas encore de compte Teams, vous pouvez [créer un compte Teams gratuitement](https://businessstore.microsoft.com/en-us/create-account/signup?products=CFQ7TTC0K8P5:0001&lm=deeplink&lmsrc=freePageWeb&cmpid=FreemiumSignUpHeader). 

### <a name="step-2-download-the-app"></a>Étape 2 : télécharger l'application

1.  Accédez au Google Play Store : https://play.google.com/store/apps/details?id=com.microsoft.ramobile.

2.  Sélectionnez **Télécharger**. 
 
### <a name="step-3-sign-in-to-the-app-for-the-first-time"></a>Étape 3 : se connecter à l'application pour la première fois

1.  Après avoir téléchargé l'application, ouvrez-la sur votre téléphone Android. 

2.  Connectez-vous avec votre compte Microsoft Teams.

    ![Écran de connexion](media/sign-in.png "Écran de connexion")
  
    > [!TIP]
    > L'adresse de connexion sera au format suivant : nomutilisateur@société.
    
3.  Dans la boîte de dialogue qui s'affiche, sélectionnez **Activer la fonctionnalité** pour lier Remote Assist à Dynamics 365 for Field Service, ou sélectionnez **Ignorer** si vous ne souhaitez pas lier l'application à ce stade. Vous pouvez toujours les lier ultérieurement via **Paramètres**. Pour en savoir plus sur la manière dont les applications fonctionnent ensemble, sélectionnez **En savoir plus**.

    ![Écran Field Service](media/field-service.PNG "Écran Field Service")
  
## <a name="make-a-call"></a>Effectuer un appel
Après vous être connecté, vous verrez la page **Contacts**, qui est la page principale de l'application Remote Assist Mobile. Dans la page **Contacts**, vos contacts sont organisés par les appels les plus récents.

![Écran contacts](media/contacts.PNG "Écran contacts")


Pour effectuer un appel :

1.  Sélectionnez ![bouton Rechercher](media/search-icon.PNG "bouton Rechercher"), entrez le nom du contact à rechercher, puis sélectionnez ce contact dans la liste résultante.
       
    ![Recherche d'un contact](media/search-contact.PNG "Recherche d'un contact")
    
2.  Dans la carte de contact, sélectionnez **Lancer l'appel**.

    ![Écran Lancer l'appel](media/launch-call.PNG "Écran Lancer l'appel")
  
    Utilisez les boutons de la barre en bas de l'écran pour mettre en sourdine l'appel, suspendre le flux vidéo, activer l'écoute amplifiée ou terminer l'appel.
    
    ![Commandes d'appel](media/call-controls.PNG "Commandes d'appel")
  
 
## <a name="add-annotations"></a>Ajouter des annotations
Vous pouvez ajouter des annotations à votre écran pour les partage avec un expert participant à l'appel. Pour créer des annotations, votre téléphone a besoin d'identifier au moins un plan (vertical ou horizontal) dans votre zone de travail. Pour ce faire, analysez votre zone de travail avec le téléphone. Lorsqu'un plan a été reconnu, vous obtenez une visualisation de confirmation et la barre d'outils d'annotation s'affiche en haut de l'écran :

![Ajouter des annotations](media/annotation-bar-full-screen.PNG "Ajouter des annotations")
  
> [!NOTE] 
> Si vous verrouillez votre téléphone ou réduisez Remote Assist, les plans identifiés réapparaîtront automatiquement dès que votre téléphone reconnaît l'environnement.

### <a name="add-an-annotation"></a>Ajouter une annotation
Vous pouvez ajouter une annotation à l'aide des boutons de la barre d'outils d'annotation :

![Barre d'annotation](media/annotation-bar.PNG "Barre d'annotation")
  
Par exemple, pour ajouter une flèche, cliquez sur l'outil de flèche et glissez votre doigt jusqu'à l'emplacement où vous souhaitez placer la flèche.

### <a name="minimize-or-restore-the-toolbar"></a>Réduire ou restaurer la barre d'outils

Pour réduire la barre d'outils si vous souhaitez afficher une plus grande zone de l'écran :

- Sélectionnez la flèche à droite de la barre d'outils. 

  ![Réduire la barre](media/minimize-bar.PNG "Réduire la barre")
 
Pour restaurer la barre d'outils à sa taille initiale :

- Sélectionnez le bouton **Stylo**. 

  ![Bouton Stylo](media/pen-button.PNG "Bouton Stylo")

### <a name="make-the-experts-video-feed-bigger"></a>Agrandir le flux vidéo de l'expert

Lorsque vous appelez un expert, son flux vidéo s'affiche dans le coin inférieur droit de l'écran de votre téléphone. Pour agrandir le flux vidéo de l'expert, appuyez sur le flux. Appuyez à nouveau sur le flux pour revenir à la taille d'origine.

![Flux vidéo de l'expert](media/expert-annotating.PNG "Flux vidéo de l'expert")
  
Si l'expert annote, une icône de notification s'affiche sur le flux de l'expert.  

## <a name="switch-the-camera-view-from-portrait-to-landscape"></a>Basculer la vue de l'appareil-photo de portrait à paysage

Vous pouvez changer l'orientation de la vue de l'appareil-photo de portrait à paysage en cours d'appel en modifiant l'orientation de votre téléphone. L'utilisation de la vue Paysage offre un champ de vision plus étendu, ce qui peut améliorer l'expérience pour l'expert distant participant à l'appel.
   
## <a name="use-remote-assist-together-with-dynamics-365-for-field-service"></a>Utiliser Remote Assist avec Dynamics 365 for Field Service

Vous pouvez utiliser Remote Assist avec Dynamics 365 for Field Service si vous souhaitez enregistrer automatiquement les informations d'un appel dans un ordre de travail Field Service lorsque vous terminez l'appel. 

Lorsque vous vous connectez à l'application Remote Assist Mobile pour la première fois, vous êtes invité à lier Remote Assist à Dynamics 365 for Field Service. Vous pouvez lier les applications via Paramètres si vous avez choisi de ne pas les lier lors de la première connexion.

### <a name="link-the-remote-assist-mobile-app-to-dynamics-365-for-field-service"></a>Lier l'application mobile Remote Assist à Dynamics 365 for Field Service

1.  Sélectionnez le bouton **Menu principal** ![Bouton Menu principal](media/main-menu-button.PNG "Bouton Menu principal").

2.  Sélectionnez le bouton **Paramètres**.  

3.  Dans la boîte de dialogue **Paramètres**, déplacez le curseur sur actif.

    ![Écran Paramètres](media/settings.PNG "Écran Paramètres")
  
### <a name="save-call-data-to-a-field-service-work-order"></a>Sauvegardez les données d'appel dans un ordre de travail Field Service

1.  Lorsque vous mettez un terme à l'appel, la boîte de dialogue suivante s'affiche :

    ![Écran Publier dans l'ordre de travail](media/post-to-work-order.PNG "Écran Publier dans l'ordre de travail")
  
2.  Sélectionnez **Publier**.


3.  Dans l'écran **Sélectionner une réservation**, sélectionnez la réservation appropriée pour publier les données d'appels.

    ![Écran Sélectionner une réservation](media/bookings-today.PNG "Écran Sélectionner une réservation")
  
    > [!NOTE]
    > Si vous ne voyez pas la réservation recherchée, cela peut être dû au fait que vous avez accès aux instances multiples (organisations). Pour basculer vers une instance différente, sélectionnez le bouton représentant des points de suspension (...), puis sélectionnez l'instance que vous voulez.<br>![Sélectionnez l'instance](media/select-instance.PNG "Sélectionnez l'instance")
    
## <a name="sign-out-of-the-app"></a>Se déconnecter de l'application

1.  Sélectionnez le bouton **Menu principal** ![Bouton Menu principal](media/main-menu-button.PNG "Bouton Menu principal").

2.  Sélectionnez **Se déconnecter**.

## <a name="get-help"></a>Obtenir de l'aide

1.  Sélectionnez le bouton **Menu principal** ![Bouton Menu principal](media/main-menu-button.PNG "Bouton Menu principal").

2.  Sélectionnez **?**.

## <a name="get-support-or-provide-feedback"></a>Obtenir un support ou fournir des commentaires

Si vous souhaitez obtenir un accès direct au forum de l'équipe du produit et fournir des commentaires sur l'aperçu de l'application mobile :

1.  Inscrivez-vous au programme Insiders de préversion publique de Dynamics 365 Remote Assist Mobile à l'adresse suivante : https://experience.dynamics.com. 


2.  Cochez la case **Programme Insider**, ce qui vous conduira à l'application du programme Insider.

    ![Bouton Programme Insider](media/insiders-program.PNG "Bouton Programme Insider")
 
Vous pouvez également fournir des commentaires directement depuis l'application en procédant comme suit :

1.  Sélectionnez le bouton **Menu principal** ![Bouton Menu principal](media/main-menu-button.PNG "Bouton Menu principal").

2.  Sélectionnez **Commentaires**.
