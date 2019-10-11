---
author: drpusey
description: Guide de l'utilisateur de Dynamics 365 Remote Assist pour mobile
ms.author: drpusey
ms.date: 10/01/2019
ms.service: crm-online
ms.topic: article
title: Guide de l'utilisateur de Dynamics 365 Remote Assist pour mobile
ms.reviewer: v-brycho
ms.openlocfilehash: 0f53e8f5827a0afe777bd82c9b44b747ff87b1d0
ms.sourcegitcommit: a8de6f8df9f709457e626fd26d6786d4953162a3
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/30/2019
ms.locfileid: "2261613"
---
# <a name="dynamics-365-remote-assist-for-mobile-user-guide"></a>Guide de l'utilisateur de Dynamics 365 Remote Assist pour mobile

[!include[cc-microsoft](../../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../../includes/pn-dyn-365-remote-assist.md)] pour mobile étend les capacités de [!include[pn-dyn-365-remote-assist](../../includes/pn-dyn-365-remote-assist.md)] à l'utilisation de téléphones ou de tablettes [!include[tn-android](../../includes/tn-android.md)] ou iOS (en plus de [!include[cc-microsoft](../../includes/cc-microsoft.md)] [!include[pn-HoloLens](../../includes/pn-HoloLens.md)]). Les techniciens peuvent utiliser leur téléphone ou tablette pour se connecter et collaborer avec un expert dans [!include[pn-microsoft-teams](../../includes/pn-microsoft-teams.md)]. En utilisant l'appel vidéo en direct et les annotations, ils peuvent partager ce qu'ils voient avec le spécialiste pour résoudre les problèmes ensemble, plus rapidement. 


## <a name="what-youll-need"></a>Ce dont vous aurez besoin

Vous aurez besoin des éléments suivants pour utiliser [!include[pn-dyn-365-remote-assist](../../includes/pn-dyn-365-remote-assist.md)] pour mobile :

- Un appareil [!include[tn-android](../../includes/tn-android.md)] ou iOS. Dynamics 365 Remote Assist pour mobile prend en charge les appareils de réalité augmentée et de réalité non augmentée. Avec les appareils de réalité non augmentée, vous pouvez utiliser des annotations 2D pour :
  - [Afficher la liste complète des appareils Android prenant en charge la réalité augmentée](https://developers.google.com/ar/discover/supported-devices)

  - [En savoir plus sur la réalité augmentée sur iOS](https://www.apple.com/ios/augmented-reality/)


- Un compte [!include[tn-google](../../includes/tn-google.md)] Play ou Apple Store.

- [!include[pn-dyn-365-remote-assist](../../includes/pn-dyn-365-remote-assist.md)] pour mobile.


- Une licence [!include[pn-dyn-365-remote-assist](../../includes/pn-dyn-365-remote-assist.md)] (essai gratuit disponible).

- Un compte [!include[pn-microsoft-teams](../../includes/pn-microsoft-teams.md)] (disponible gratuitement).

- Un client pour ordinateur de bureau [!include[pn-microsoft-teams](../../includes/pn-microsoft-teams.md)] exécutant [!include[pn-ms-windows-short](../../includes/pn-ms-windows-short.md)] 10 (pour l'expert distant qui reçoit l'appel).

- Une connexion Internet. Au moins 1,5 Mo de bande passante est recommandé pour optimiser l'expérience.

Si vous souhaitez utiliser [!include[pn-dyn-365-remote-assist](../../includes/pn-dyn-365-remote-assist.md)] avec [!include[pn-dyn-365-field-service](../../includes/pn-dyn-365-field-service.md)], vous pouvez enregistrer automatiquement les informations d'un appel dans un ordre de travail [!include[pn-field-service](../../includes/pn-field-service.md)]. Vous avez également besoin de l'un ou des deux éléments suivants :

- Application web [!include[pn-dyn-365-field-service](../../includes/pn-dyn-365-field-service.md)]

- Application mobile [!include[pn-dyn-365-field-service](../../includes/pn-dyn-365-field-service.md)] 

## <a name="get-started"></a>Mise en route

### <a name="step-1-sign-up-for-a-microsoft-teams-account-free"></a>Étape 1 : S'inscrire à un compte Microsoft Teams (gratuit)

Un compte [!include[pn-microsoft-teams](../../includes/pn-microsoft-teams.md)] est requis pour utiliser [!include[pn-dyn-365-remote-assist](../../includes/pn-dyn-365-remote-assist.md)] pour mobile. Si vous n'avez pas encore de compte [!include[pn-teams](../../includes/pn-teams.md)], vous pouvez [créer un compte Teams gratuitement](https://businessstore.microsoft.com/create-account/signup?products=CFQ7TTC0K8P5:0001&lm=deeplink&lmsrc=freePageWeb&cmpid=FreemiumSignUpHeader). 

### <a name="step-2-download-the-app"></a>Étape 2 : Télécharger l'application

1.  Accédez à [Google Play Store](https://play.google.com/store/apps/details?id=com.microsoft.ramobile) ou [Apple Store](https://go.microsoft.com/fwlink/?linkid=2100645).

2.  Sélectionnez **Télécharger**. 
 
### <a name="step-3-sign-in-to-the-app-for-the-first-time"></a>Étape 3 : Se connecter à l'application pour la première fois

1.  Après avoir téléchargé l'application, ouvrez-la sur votre téléphone ou tablette. 

2.  Connectez-vous avec votre compte [!include[pn-microsoft-teams](../../includes/pn-microsoft-teams.md)].

    ![Écran de connexion](../media/sign-in.png "Écran de connexion")
  
    > [!TIP]
    > L'adresse de connexion sera au format suivant : username@company
    
3.  Dans la boîte de dialogue qui s'affiche, sélectionnez **Activer la fonctionnalité** pour lier [!include[pn-dyn-365-remote-assist](../../includes/pn-dyn-365-remote-assist.md)] à [!include[pn-dyn-365-field-service](../../includes/pn-dyn-365-field-service.md)], ou sélectionnez **Ignorer** si vous ne souhaitez pas lier l'application à ce stade. Vous pouvez toujours les lier ultérieurement via **Paramètres**. Pour en savoir plus sur la manière dont les applications fonctionnent ensemble, sélectionnez **En savoir plus**.

    ![Écran Field Service](../media/field-service.PNG "Écran Field Service")
   
4. Si vous ne disposez pas d'une licence [!include[pn-dyn-365-remote-assist](../../includes/pn-dyn-365-remote-assist.md)], une autre boîte de dialogue vous invite à obtenir une licence ou à vous inscrire pour un essai gratuit.

  
## <a name="view-a-quick-tutorial-to-jumpstart-your-learning-curve"></a>Afficher un didacticiel rapide pour démarrer votre courbe d'apprentissage

Dynamics 365 Remote Assist pour mobile comprend un didacticiel que vous pouvez utiliser pour démarrer votre courbe d'apprentissage. Vous pouvez lancer le didacticiel en sélectionnant le bouton **Essayer** une fois connecté.

![Essayer le didacticiel](media/try-it.png "Essayer le didacticiel")

Vous pouvez également lancer le didacticiel en sélectionnant le bouton Menu principal, puis en sélectionnant **Découvrir les outils**.

![Option Découvrir les outils](media/learn-the-tools.png "Option Découvrir les outils")

## <a name="make-a-call"></a>Effectuer un appel
Après vous être connecté, vous verrez la page **Contacts**, qui est la page principale dans [!include[pn-dyn-365-remote-assist](../../includes/pn-dyn-365-remote-assist.md)] pour mobile. Dans la page **Contacts**, vos contacts sont organisés selon les appels les plus récents.

![Écran contacts](media/contacts.png "Écran contacts")

Pour effectuer un appel :

1.  Sélectionnez ![bouton Rechercher](../media/search-icon.PNG "bouton Rechercher"), entrez le nom du contact à rechercher, puis sélectionnez ce contact dans la liste résultante.
       
    ![Recherche d'un contact](../media/search-contact.PNG "Recherche d'un contact")
    
2.  Dans la carte de contact, sélectionnez **Lancer l'appel**.

    ![Écran Lancer l'appel](media/launch-call.png "Écran Lancer l'appel")
  
    Utilisez les boutons de la barre en bas de l'écran pour mettre en sourdine l'appel, suspendre le flux vidéo, activer l'écoute amplifiée ou terminer l'appel.
    
    ![Commandes d'appel](media/call-controls.PNG "Commandes d'appel")
    
    A. Suspendre le flux vidéo<br>
    B. Mettre en sourdine l'appel<br>
    C. Activer l'écoute amplifiée<br>
    D. Terminer l'appel
  
 
## <a name="add-annotations"></a>Ajouter des annotations
Vous pouvez ajouter des annotations à votre écran pour les partager avec un expert participant à l'appel. Pour créer des annotations, votre téléphone ou tablette a besoin d'identifier au moins un plan (vertical ou horizontal) dans votre zone de travail. Pour ce faire, analysez votre zone de travail avec le téléphone ou la tablette. Lorsqu'un plan a été reconnu, vous obtenez une visualisation de confirmation et la barre d'outils d'annotation s'affiche en haut de l'écran :

![Ajouter des annotations](media/annotation-bar-full-screen.PNG "Ajouter des annotations")
  
> [!NOTE] 
> Si vous verrouillez votre téléphone ou tablette, ou réduisez [!include[pn-dyn-365-remote-assist](../../includes/pn-dyn-365-remote-assist.md)] pour mobile, les plans identifiés réapparaîtront automatiquement dès que votre téléphone ou tablette reconnaîtra l'environnement.

### <a name="add-an-augmented-reality-annotation"></a>Ajouter une annotation de réalité augmentée

Vous pouvez ajouter une annotation de réalité augmentée à l'aide des boutons de la barre d'outils d'annotation :

![Barre d'annotation](media/annotation-bar.PNG "Barre d'annotation")

A. Ajouter une flèche<br>
B. Ajouter de l'encre<br>
C. Modifier la couleur de la flèche ou de l'encre<br>
D. Annuler la dernière action<br>
E. Supprimer tout sur l'écran, y compris les annotations de l'expert
  
Par exemple, pour ajouter une flèche, cliquez sur l'outil de flèche et glissez votre doigt jusqu'à l'emplacement où vous souhaitez placer la flèche.

### <a name="add-a-2d-annotation"></a>Ajouter une annotation 2D

Vous pouvez également annoter en 2D en désactivant la réalité augmentée ou en prenant une photo.

![Bouton Caméra](media/camera-button.PNG "Bouton Caméra")

Lorsque la réalité augmentée est désactivée, le bouton **Caméra** se transforme en coche. 

![Coche 2D](media/2d-checkmark.png "Coche 2D")

Vous pouvez utiliser la 2D :

- Pour améliorer les performances et économiser la batterie.

- Pour améliorer la précision des annotations.

- Si votre appareil ne prend pas en charge la réalité augmentée.

### <a name="make-the-experts-video-feed-bigger"></a>Agrandir le flux vidéo de l'expert

Lorsque vous appelez un expert, son flux vidéo s'affiche dans le coin inférieur droit de l'écran de votre téléphone ou tablette. Pour agrandir le flux vidéo de l'expert, appuyez sur le flux. Appuyez à nouveau sur le flux pour revenir à la taille d'origine.

![Flux vidéo de l'expert](media/expert-annotating.PNG "Flux vidéo de l'expert")
  
Si l'expert annote, une icône de notification s'affiche sur le flux de l'expert.  

## <a name="switch-the-camera-view-from-portrait-to-landscape"></a>Basculer la vue de l'appareil-photo de portrait à paysage

Vous pouvez changer l'orientation de la vue de l'appareil-photo de portrait à paysage en cours d'appel en modifiant l'orientation de votre téléphone ou tablette. L'utilisation de la vue Paysage offre un champ de vision plus étendu, ce qui peut améliorer l'expérience pour le spécialiste distant participant à l'appel.

## <a name="send-a-text-message"></a>Envoyer un message texte

Vous pouvez également communiquer par conversation instantanée Teams avec la personne que vous appelez. Une fenêtre contextuelle s'affiche pour les messages que vous recevez, ou vous pouvez ouvrir la fenêtre de conversation instantanée textuelle pour envoyer un message à l'autre personne. 

![Fenêtre de conversation instantanée](media/chat.png "Fenêtre de conversation instantanée")
   

## <a name="use-dynamics-365-remote-assist-together-with-dynamics-365-field-service"></a>Utiliser Dynamics 365 Remote Assist avec Dynamics 365 Field Service

Vous pouvez utiliser [!include[pn-dyn-365-remote-assist](../../includes/pn-dyn-365-remote-assist.md)] avec [!include[pn-dyn-365-field-service](../../includes/pn-dyn-365-field-service.md)] si vous souhaitez enregistrer automatiquement les informations d'un appel dans un ordre de travail [!include[pn-field-service](../../includes/pn-field-service.md)] lorsque vous terminez l'appel. 

Lorsque vous vous connectez à [!include[pn-dyn-365-remote-assist](../../includes/pn-dyn-365-remote-assist.md)] pour mobile pour la première fois, vous êtes invité à lier [!include[pn-dyn-365-remote-assist](../../includes/pn-dyn-365-remote-assist.md)] à [!include[pn-dyn-365-field-service](../../includes/pn-dyn-365-field-service.md)]. Vous pouvez lier les applications via **Paramètres** si vous avez choisi de ne pas les lier lors de la première connexion.

### <a name="link-dynamics-365-remote-assist-for-mobile-to-dynamics-365-field-service"></a>Lier Dynamics 365 Remote Assist pour mobile à Dynamics 365 Field Service

1.  Sélectionnez le bouton **Menu principal** ![Bouton Menu principal](../media/main-menu-button.PNG "Bouton Menu principal").

2.  Sélectionnez le bouton **Paramètres**.  

3.  Dans la boîte de dialogue **Paramètres**, déplacez le curseur sur actif.

    ![Écran Paramètres](../media/settings.PNG "Écran Paramètres")
  
### <a name="save-call-data-to-a-dynamics-365-field-service-work-order"></a>Sauvegarder les données d'appel dans un ordre de travail Dynamics 365 Field Service

1.  Lorsque vous mettez un terme à l'appel, la boîte de dialogue suivante s'affiche :

    ![Écran Publier dans l'ordre de travail](media/post-to-work-order.jpg "Écran Publier dans l'ordre de travail")
  
2.  Sélectionnez **Publier**.

3.  Dans l'écran **Sélectionner une des réservations du jour**, sélectionnez la réservation appropriée pour publier les données d'appel.

    ![Écran Sélectionner une réservation](media/bookings-today.jpg "Écran Sélectionner une réservation")
  
    > [!NOTE]
    > Si vous ne voyez pas la réservation recherchée, cela peut être dû au fait que vous avez accès aux instances multiples (organisations). Pour basculer vers une instance différente, sélectionnez le bouton représentant des points de suspension (...), puis sélectionnez l'instance que vous voulez.<br>![Sélectionnez l'instance](../media/select-instance.PNG "Sélectionnez l'instance")
    
## <a name="sign-out-of-the-app"></a>Se déconnecter de l'application

1.  Sélectionnez le bouton **Menu principal** ![Bouton Menu principal](../media/main-menu-button.PNG "Bouton Menu principal").

2.  Sélectionnez **Se déconnecter**.

## <a name="get-help"></a>Obtenir de l'aide

1.  Sélectionnez le bouton **Menu principal** ![Bouton Menu principal](../media/main-menu-button.PNG "Bouton Menu principal").

2.  Sélectionnez **?**.

## <a name="get-support-or-provide-feedback"></a>Obtenir un support ou fournir des commentaires

Si vous souhaitez accéder au forum sur le produit ou laisser des commentaires sur l'application, accédez à [Communauté Dynamics 365 Remote Assist](https://community.dynamics.com/365/remoteassist/).

Vous pouvez également fournir des commentaires directement depuis l'application en procédant comme suit :

1.  Sélectionnez le bouton **Menu principal** ![Bouton Menu principal](../media/main-menu-button.PNG "Bouton Menu principal").

2.  Sélectionnez **Commentaires**.

### <a name="see-also"></a>Voir aussi

[Intégrer Dynamics 365 Field Service dans Dynamics 365 Remote Assist](../troubleshoot-field-service.md)


