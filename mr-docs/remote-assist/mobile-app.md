---
author: drpusey
description: Guide de l'utilisateur de l'application mobile Dynamics 365 Remote Assist
ms.author: drpusey
ms.date: 06/07/2019
ms.service: crm-online
ms.topic: article
title: Guide de l'utilisateur de l'application mobile Dynamics 365 Remote Assist
ms.reviewer: v-brycho
ms.openlocfilehash: 8004747d1811543b7ad6f40a31303fce531d2400
ms.sourcegitcommit: 21c2ba57557afc0090b7b5f1f5e8f8c9d0f7def5
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 06/14/2019
ms.locfileid: "1631941"
---
# <a name="dynamics-365-remote-assist-mobile-user-guide-in-preview"></a>Guide de l'utilisateur de l'application mobile Dynamics 365 Remote Assist (en version préliminaire)

[Cette rubrique fait partie de la documentation en version préliminaire et peut faire l'objet de modifications.]

L'application mobile [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] étend les capacités de [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] à l'utilisation de téléphones compatibles [!include[tn-android](../includes/tn-android.md)] ARCore (en plus de [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-HoloLens](../includes/pn-HoloLens.md)]. Les techniciens peuvent utiliser leurs téléphones pour se connecter et collaborer avec un expert dans [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)]. En utilisant l'appel vidéo en direct et les annotations de réalité mixte, ils peuvent partager ce qu'ils voient avec le spécialiste pour résoudre les problèmes ensemble, plus rapidement. 

## <a name="what-youll-need"></a>Ce dont vous aurez besoin

Vous aurez besoin des éléments suivants pour utiliser l'application mobile [!include[pn-remote-assist](../includes/pn-remote-assist.md)] :

- Un téléphone compatible [!include[tn-android](../includes/tn-android.md)] ARCore (les tablettes ne sont actuellement pas prises en charge), avec ARCore installé. [Consultez la liste complète des appareils pris en charge.](https://developers.google.com/ar/discover/supported-devices) 

- Un compte [!include[tn-google](../includes/tn-google.md)] Play.

- L'application mobile [!include[pn-remote-assist](../includes/pn-remote-assist.md)].

- Un compte [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] (disponible gratuitement).

- Un client pour ordinateur de bureau [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] exécutant [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 (pour l'expert distant qui reçoit l'appel).

- Une connexion Internet. Au moins 1,5 Mo de bande passante est recommandé pour optimiser l'expérience.

Si vous souhaitez utiliser [!include[pn-remote-assist](../includes/pn-remote-assist.md)] avec [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)], vous pouvez enregistrer automatiquement les informations d'un appel dans un ordre de travail [!include[pn-field-service](../includes/pn-field-service.md)]. Vous avez également besoin de l'un ou des deux éléments suivants :

- Application web [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)]

- Application mobile [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)] 

## <a name="get-started"></a>Mise en route

### <a name="step-1-sign-up-for-a-microsoft-teams-account-free"></a>Étape 1 : Inscrivez-vous à un compte Microsoft Teams (gratuit)

Un compte [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] est requis pour utiliser l'application mobile [!include[pn-remote-assist](../includes/pn-remote-assist.md)]. Si vous n'avez pas encore de compte [!include[pn-teams](../includes/pn-teams.md)], vous pouvez [créer un compte Teams gratuitement.](https://businessstore.microsoft.com/en-us/create-account/signup?products=CFQ7TTC0K8P5:0001&lm=deeplink&lmsrc=freePageWeb&cmpid=FreemiumSignUpHeader) 

### <a name="step-2-download-the-app"></a>Étape 2 : Télécharger l'application

1.  Accédez à [!include[tn-google](../includes/tn-google.md)] Play Store : https://play.google.com/store/apps/details?id=com.microsoft.ramobile.

2.  Sélectionnez **Télécharger**. 
 
### <a name="step-3-sign-in-to-the-app-for-the-first-time"></a>Étape 3 : Se connecter à l'application pour la première fois

1.  Après avoir téléchargé l'application, ouvrez-la sur votre téléphone [!include[tn-android](../includes/tn-android.md)]. 

2.  Connectez-vous avec votre compte [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)].

    ![Écran de connexion](media/sign-in.png "Écran de connexion")
  
    > [!TIP]
    > L'adresse de connexion sera au format suivant : nomutilisateur@société.
    
3.  Dans la boîte de dialogue qui s'affiche, sélectionnez **Activer la fonctionnalité** pour lier [!include[pn-remote-assist](../includes/pn-remote-assist.md)] à [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)], ou sélectionnez **Ignorer** si vous ne souhaitez pas lier l'application à ce stade. Vous pouvez toujours les lier ultérieurement via **Paramètres**. Pour en savoir plus sur la manière dont les applications fonctionnent ensemble, sélectionnez **En savoir plus**.

    ![Écran Field Service](media/field-service.PNG "Écran Field Service")
  
## <a name="make-a-call"></a>Effectuer un appel
Après vous être connecté, vous verrez la page **Contacts**, qui est la page principale de l'application mobile [!include[pn-remote-assist](../includes/pn-remote-assist.md)]. Dans la page **Contacts**, vos contacts sont organisés par les appels les plus récents.

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
> Si vous verrouillez votre téléphone ou réduisez [!include[pn-remote-assist](../includes/pn-remote-assist.md)], les plans identifiés réapparaîtront automatiquement dès que votre téléphone reconnaît l'environnement.

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

Vous pouvez changer l'orientation de la vue de l'appareil-photo de portrait à paysage en cours d'appel en modifiant l'orientation de votre téléphone. L'utilisation de la vue Paysage offre un champ de vision plus étendu, ce qui peut améliorer l'expérience pour le spécialiste distant participant à l'appel.
   
## <a name="use-remote-assist-together-with-dynamics-365-for-field-service"></a>Utiliser Remote Assist avec Dynamics 365 for Field Service

Vous pouvez utiliser [!include[pn-remote-assist](../includes/pn-remote-assist.md)] avec [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)] si vous souhaitez enregistrer automatiquement les informations d'un appel dans un ordre de travail [!include[pn-field-service](../includes/pn-field-service.md)] lorsque vous terminez l'appel. 

Lorsque vous vous connectez à l'application mobile [!include[pn-remote-assist](../includes/pn-remote-assist.md)] pour la première fois, vous êtes invité à lier [!include[pn-remote-assist](../includes/pn-remote-assist.md)] à [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)]. Vous pouvez lier les applications via **Paramètres** si vous avez choisi de ne pas les lier lors de la première connexion.

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

Si vous souhaitez obtenir un accès direct au forum de l'équipe du produit et fournir des commentaires sur la version préliminaire de l'application mobile :

1.  Inscrivez-vous au programme Insiders de version préliminaire publique de [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] Mobile à l'adresse suivante : https://experience.dynamics.com. 


2.  Cochez la case **Programme Insider**, ce qui vous conduira à l'application du programme Insider.

    ![Bouton Programme Insider](media/insiders-program.PNG "Bouton Programme Insider")
 
Vous pouvez également fournir des commentaires directement depuis l'application en procédant comme suit :

1.  Sélectionnez le bouton **Menu principal** ![Bouton Menu principal](media/main-menu-button.PNG "Bouton Menu principal").

2.  Sélectionnez **Commentaires**.

### <a name="see-also"></a>Voir aussi

[Détecter les problèmes d'intégration de Dynamics 365 for Field Service dans Remote Assist](troubleshoot-field-service.md)
