---
author: bencorn
description: Paramétrer et utiliser Microsoft Teams avec Dynamics 365 Remote Assist pour collaborer à un appel
ms.author: bencorn
ms.date: 10/01/2019
ms.service: crm-online
ms.topic: article
title: Paramétrer et utiliser Microsoft Teams avec Dynamics 365 Remote Assist
ms.reviewer: v-brycho
ms.openlocfilehash: cb9670cbf6ba650a4b744ecabf14f3efb488a106
ms.sourcegitcommit: 15f2c0f0ac19d9516135d89c44550a2b77cd181e
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/27/2019
ms.locfileid: "2224263"
---
# <a name="set-up-and-use-microsoft-teams-with-dynamics-365-remote-assist-to-collaborate-on-a-call"></a>Paramétrer et utiliser Microsoft Teams avec Dynamics 365 Remote Assist pour collaborer à un appel

Un utilisateur de [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] sur [!include[pn-hololens](../includes/pn-hololens.md)] peut travailler en collaboration avec un collègue (généralement un expert d'un domaine spécifique) lors d'un appel vidéo en utilisant [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)]. L'expert peut consulter tout ce que l'utilisateur de [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] voit et ensemble, ils peuvent dessiner et annoter holographiquement. Par exemple, imaginons qu'un collaborateur de première ligne procède à la maintenance d'une machine très complexe et a des doutes quant à la manière de résoudre un problème. Le collaborateur de première ligne peut appeler un expert n'importe où dans le monde et lui demander son appui pour la maintenance à l'aide d'annotations ou de fichiers.

Le paramétrage de cette collaboration en utilisant [!include[pn-teams](../includes/pn-teams.md)] est simple et gratuit pour l'expert.

Besoin d'aide complémentaire ? [Consultez la FAQ de Dynamics 365 Remote Assist](faq.md) pour obtenir des réponses aux questions fréquentes.

[Consultez des vidéos pratiques](videos.md) concernant [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)].

## <a name="what-youll-need"></a>Ce dont vous aurez besoin

L'utilisateur de [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] (collaborateur de première ligne) sur [!include[pn-HoloLens](../includes/pn-HoloLens.md)] a besoin des éléments suivants :

-   [Un abonnement à Dynamics 365 Remote Assist.](../licensing/buy-and-deploy.md) L'abonnement à [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] inclut un abonnement à [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)].

-   Un [!include[pn-hololens](../includes/pn-hololens.md)] exécutant la [Mise à jour d'avril 2018 de Windows 10](https://support.microsoft.com/help/12643) (ou une version ultérieure).

-   Un compte [!include[pn-azure-active-directory](../includes/pn-azure-active-directory.md)].

Le spécialiste a besoin des éléments suivants :

-   Un PC exécutant [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 avec la dernière version de [Microsoft Teams](https://products.office.com/microsoft-teams/group-chat-software) ou un appareil mobile exécutant [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] Mobile. Le spécialiste utilise [!include[pn-teams](../includes/pn-teams.md)] pour communiquer avec l'utilisateur de [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] dans [!include[pn-HoloLens](../includes/pn-HoloLens.md)]. [!include[pn-teams](../includes/pn-teams.md)] peut être disponible [en téléchargement gratuit](https://teams.microsoft.com/downloads).

-   Un compte [!include[cc-microsoft](../includes/cc-microsoft.md)] gratuit. Le spécialiste peut déjà avoir un compte [!include[cc-microsoft](../includes/cc-microsoft.md)] s'il s'est inscrit pour [!include[cc-microsoft](../includes/cc-microsoft.md)] App Store, Skype, Xbox, Hotmail ou Outlook.com. Si l'expert n'a pas encore de compte [!include[cc-microsoft](../includes/cc-microsoft.md)], il peut s'inscrire sur [https://account.microsoft.com/account](https://account.microsoft.com/account).

## <a name="setup"></a>Configurer

Vous pouvez intégrer un expert pour collaborer en utilisant [!include[pn-teams](../includes/pn-teams.md)] en trois étapes faciles :

| **Étape** | **Description**                                                                  | **Qui effectue cette étape ?**           |
|----------|----------------------------------------------------------------------------------|-----------------------------------|
|    1.      | Activer l'accès invité pour [!include[pn-teams](../includes/pn-teams.md)]                                                    | Administrateur                     |
|    2.      | Inviter l'expert à rejoindre une équipe en tant qu'invité en utilisant le compte [!include[cc-microsoft](../includes/cc-microsoft.md)] de l'expert | Administrateur ou expert et utilisateur [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] (pour télécharger [!include[pn-teams](../includes/pn-teams.md)]) |
|    3.      | Passer un appel                                                                     | Expert ou utilisateur [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)]     |

### <a name="step-1-enable-guest-access-for-teams"></a>Étape 1 : activez l'accès Invité pour les équipes

1.  Si vous êtes l'administrateur du tenant [!include[pn-azure](../includes/pn-azure.md)] principal, allez à <https://admin.microsoft.com/adminportal/> pour ouvrir le portail administrateur d'Office, puis connectez-vous.

2.  Dans le menu sur la gauche, sélectionnez **Afficher plus** \> **Paramètres** \> **Services et compléments**.

    ![Services et compléments](media/bf81ea48e3ccd560b6f44dbc72a73eb5.png "Services et compléments")

1.  Sélectionnez **[!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)]** dans la liste de candidatures.

    ![Microsoft Teams](media/ad846431f181b1c6df362bc2e0e03167.png "Microsoft Teams")

1.  Sélectionnez **Paramètres par type d'utilisateur/de licence**.

2.  Dans la liste déroulante en regard de **Sélectionner le type d'utilisateur/licence à configurer**, sélectionnez **Invité**.

3.  Définissez **Activer/Désactiver [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)] pour tous les utilisateurs de ce type** sur **Activé**, puis sélectionnez **Enregistrer**.

    ![Enregistrer](media/9f095e7553a4af03ff13ea6a29a9343a.png "Enregistrer")

4.  Attendez une heure que les paramètres se propagent.

### <a name="step-2-invite-the-expert-to-join-a-team"></a>Étape 2 : invitez l'expert à rejoindre une équipe

1.  Dans [!include[pn-teams](../includes/pn-teams.md)], sélectionnez **Rejoindre ou créer une équipe** pour créer une équipe si elle n'existe pas déjà. L'expert et l'utilisateur de [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] doivent être dans la même équipe pour communiquer.

    ![Rejoindre ou créer une équipe](media/16e00f809d210dcb3b1e8c8e859b73da.png "Rejoindre ou créer une équipe")

1.  Lorsqu'il vous est demandé d'ajouter des membres, accédez au compte [!include[cc-microsoft](../includes/cc-microsoft.md)] de l'expert.

    ![Compte Microsoft](media/71e9276273f8f47b786f743416a2cb64.png "Compte Microsoft")

    > [!NOTE]
    > Si vous ne voyez pas l'option pour ajouter un invité en tapant une adresse e-mail, il est probable que l'accès Invité ne soit pas activé pour le tenant [!include[pn-azure](../includes/pn-azure.md)] de votre société pour [!include[pn-teams](../includes/pn-teams.md)]. Activez l'accès Invité comme décrit précédemment dans cette rubrique.

1.  L'expert recevra immédiatement un message électronique et peut cliquer sur le lien dans le message pour ouvrir (ou télécharger) [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)]. Cette version de [!include[pn-teams](../includes/pn-teams.md)] est gratuite et n'est pas une version d'essai.

### <a name="step-3-place-a-call"></a>Étape 3. Passer un appel

1.  L'expert lance l'application [!include[pn-teams](../includes/pn-teams.md)] et l'utilisateur de [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] sur [!include[pn-hololens](../includes/pn-hololens.md)] se connecte à son compte comme d'habitude.

    > [!IMPORTANT]
    > Si c'est la première fois que l'expert a lancé [!include[pn-teams](../includes/pn-teams.md)] et qu'il n'a été invité à aucune autre équipe, [!include[pn-teams](../includes/pn-teams.md)] guidera automatiquement l'expert vers l'espace correct. Si l'expert a été invité à d'autres équipes, il pourra devoir basculer vers le tenant approprié.  
    >     
    > Pour changer de tenant, dans le menu déroulant dans le coin supérieur droit de la fenêtre, sélectionnez le tenant invité approprié :
    
    ![Tenant invité](media/55237a5359fb66daf7bbb9413adab6b9.png "Tenant invité")
       
    > [!NOTE]
    > [!include[pn-teams](../includes/pn-teams.md)] peut nécessiter quelques secondes pour recharger.
    
1.  L'une ou l'autre des parties peut être à l'origine de l'appel. Vous devrez peut-être rechercher dans les contacts pour trouver la bonne personne.

    > [!NOTE]
    > L'invité peut appeler n'importe quel membre de la même équipe. Pour étendre cette fonctionnalité, invitez tous les autres membres au sein de votre société qui pourraient tirer profit d'être en mesure d'accéder à ce nouvel expert.

## <a name="working-with-annotations"></a>Utilisation des annotations

Une fois que [!include[pn-teams](../includes/pn-teams.md)] est installé, l'expert peut effectuer des appels vidéo à l'adresse de contacts (et en recevoir de ces derniers) en utilisant [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] sur un [!include[pn-hololens](../includes/pn-hololens.md)].

Au cours d'un appel, l'expert voit l'espace du contact, hologrammes inclus, peut utiliser la barre d'outils de réalité mixte dans la fenêtre de l'appel vidéo pour ajouter des hologrammes.

![Barre d'outils de réalité mixte](media/071f358ab6bbf7c2072b15d9203a1593.png "Barre d'outils de réalité mixte")

## <a name="draw-and-annotate"></a>Dessiner et annoter

### <a name="edit-mode"></a>Mode d'édition

Pour commencer à annoter l'espace d'un contact, effectuez d'abord une des actions suivantes pour interrompre le flux vidéo et entrer en mode d'édition :

-   Sélectionnez n'importe où dans la fenêtre d'appel.

-   Sélectionnez l'un des articles dans la barre d'outils de réalité mixte.

-   Sélectionnez **Commencer l'édition**.

En mode d'édition, l'expert verra toujours un stream en direct de l'appel dans le coin de la fenêtre d'application.

### <a name="add-arrows-ink-and-files"></a>Ajouter des flèches, de l'encre et des fichiers

Utilisez la barre d'outils de réalité mixte pour placer les flèches, dessiner ou ajouter des fichiers :

-   Pour ajouter des flèches, sélectionnez **Insérer une flèche** ![Insérer une flèche](media/6584f4b7932378aa23f6efbf460b304c.png "Insérer une flèche").

-   Pour ajouter de l'encre, sélectionnez **Encre** ![Encre](media/187307e30fd713f5ae67aba854b78bc4.png "Encre").

-   Pour modifier la couleur de flèche ou d'encre, sélectionnez **Choisir une couleur** ![Choisir une couleur](media/5d9d3c70cf19ed175a8dc1ad71a60fc5.png "Choisir une couleur").

-   Pour ajouter un fichier, sélectionnez **Insérer des fichiers** ![Insérer des fichiers](media/41aa538d3be8e163215f7d9374abe90e.png "Insérer des fichiers"), puis ajouter un fichier image ou un fichier PDF.

    > [!NOTE]
    > Une fois ajoutées, les images ne peuvent pas être déplacées, supprimées ou redimensionnées par l'expert.

### <a name="finish-editing"></a>Terminer l'édition

Une fois l'annotation terminée, effectuez l'une des opérations suivantes pour terminer l'édition et revenir au mode réel :

-   Sélectionnez **Arrêter la modification**.

-   Sélectionnez le flux vidéo en direct dans le coin droit de votre écran.

### <a name="make-changes-to-edits"></a>Apporter des modifications aux éditions

Pour apporter des modifications aux éditions, procédez d'une des façons suivantes :

-   En mode d'édition, sélectionnez **Annuler** pour annuler la dernière action.

-   En mode d'édition, sélectionnez **Effacer tout** ![Effacer tout](media/3aab547aa81003ad181eceadc2c83a47.png "Effacer tout") pour effacer toutes les annotations effectuées pendant cette session d'édition.

-   En mode réel, sélectionnez **Effacer tout** ![Effacer tout](media/3aab547aa81003ad181eceadc2c83a47.png "Effacer tout") pour effacer toutes les annotations effectuées pendant cet appel.

> [!NOTE]
> Les dessins ou les flèches spécifiques ne peuvent pas être supprimés. Seul l'utilisateur d'[!include[pn-hololens](../includes/pn-hololens.md)] peut apporter des modifications à des images ajoutées par un expert, ou les supprimer.

## <a name="share-your-desktop-or-a-running-application-with-a-dynamics-365-remote-assist-user"></a>Partager votre ordinateur de bureau ou une application en cours d'exécution avec un utilisateur de Dynamics 365 Remote Assist

Lorsque vous partagez votre bureau ou une application en cours d'exécution avec un utilisateur de [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)], le flux vidéo de l'utilisateur passe à une couleur unie. Tous les outils de la barre d'outils demeureront utilisables, même si le flux vidéo ne sera plus affiché.

Pour partager votre bureau ou une application en cours d'exécution :

1. Dans [!include[pn-teams](../includes/pn-teams.md)], sélectionnez le bouton **Ouvrir le bac de partage**.

   ![Bouton Bac de partage](media/share-tray.PNG "Bouton Bac de partage")
   
2. Sélectionnez l'écran que vous souhaitez partager.

> [!NOTE]
> Vous ne pouvez partager qu'une seule application ou qu'un seul écran à la fois. Si vous souhaitez partager un écran différent, sélectionnez le bouton **Fermer le bac de partage** pour arrêter le partage, sélectionnez un autre écran, puis redémarrez le partage.

### <a name="see-also"></a>Voir aussi
[Guide de l'utilisateur](user-guide.md)<br/>
[Vidéos pratiques](videos.md)<br/>
[FAQ](faq.md)<br/>
