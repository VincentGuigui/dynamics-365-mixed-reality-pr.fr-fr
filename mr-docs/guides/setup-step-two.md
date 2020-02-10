---
author: Mamaylya
description: Étape 2 de la configuration de Dynamics 365 Guides, qui comprend la création d'un environnement Common Data Service et l'installation de la solution Dynamics 365 Guides
ms.author: mamaylya
ms.date: 01/28/2020
ms.service: crm-online
ms.topic: article
title: Créer un environnement Common Data Service et installer la solution Dynamics 365 Guides dans le cadre du processus de configuration
ms.reviewer: v-brycho
ms.openlocfilehash: e4c86eac56b562358c8383cf21c2f01175b3b65d
ms.sourcegitcommit: 217d31bb34e67a6b8823d5ddac7ef8d56d054139
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/29/2020
ms.locfileid: "2995247"
---
# <a name="dynamics-365-guides-setup-step-2-install-the-solution"></a>Étape 2 de la configuration de Dynamics 365 Guides : Installer la solution

>[!NOTE]
>Avant d'effectuer les procédures de cette étape, vous devez passer par l'étape 1 du processus de configuration : [Acheter un abonnement ou s'inscrire pour un essai gratuit](setup-step-one.md)

Après avoir acheté un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et avoir affecté les licences, vous devez créer un environnement où vous pouvez installer la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Le type d'environnement que vous créez dépend de la création d'un environnement d'évaluation ou de production. Si vous avez acheté une licence pour [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous devez configurer un environnement de production. Un environnement de production offre des capacités de sauvegarde et de restauration. 

>[!NOTE]
>Si vous disposez déjà d'un environnement à utiliser (par exemple, une instance de l'abonnement Dynamics 365 de votre entreprise), vous pouvez passer directement à [Modifier la taille maximale de fichier pour le téléchargement](#upload).

## <a name="set-up-a-trial-environment"></a>Configurer un environnement d'évaluation
    
1.  Accédez au [Centre d'administration Power Platform](https://admin.powerplatform.microsoft.com/environments) et connectez-vous avec les informations d'identification de l'administrateur pour la version d’évaluation.

2.  Dans le Centre d'administration Power Platform, sélectionnez **Environnements**.

    ![Environnements Power Platform](media/powerapps-environments.PNG "Environnements Power Platform")
    
3.  Sélectionnez le bouton **Autres actions d'environnement** (...) en regard de l'instance par défaut, puis sélectionnez **Gérer l'environnement**.

    ![Gérer l'environnement](media/powerapps-manage-environment.PNG "Gérer l'environnement")    
     
4. Modifiez le nom de l'environnement (par exemple, Guides_*un nom quelconque*), puis sélectionnez **Créer ma base de données**.

    ![Créer une base de données](media/powerapps-create-database.PNG "Créer une base de données")
    
5. Dans la boîte de dialogue **Créer une base de données pour cet environnement**, choisissez votre devise et votre langue.

    ![Paramètres de devise et de langue](media/currency-language-settings.PNG "Paramètres de devise et de langue")
  
6.  Sélectionnez **Créer une base de données.**

    La page suivante s'affiche alors que la base de données est créée et mise en service :
    
     ![Page Approvisionnement de la base de données](media/provisioning-database.PNG "Page Approvisionnement de la base de données")
 
     > [!NOTE]
     > La création de la base de données prend généralement quelques minutes. Si, au bout de cinq minutes, le message « Approvisionnement de la base de données » apparaît toujours, essayez d'actualiser la page.

7.  Une fois que la base de données a été créée, revenez à la page **Environnements** et allez à la procédure [Modifier la taille maximale de fichier pour le téléchargement](#upload).

## <a name="set-up-a-production-environment"></a>Configurer un environnement de production

1.  Accédez au [Centre d'administration de Power Platform](https://admin.powerplatform.microsoft.com/environments), sélectionnez **Environnements** s'il n'est pas déjà sélectionné, puis sélectionnez **Nouveau**.

    ![Ajouter un nouvel environnement](media/add-new-environment.PNG "Ajouter un nouvel environnement") 

    Le volet **Nouvel environnement** apparaît sur le côté droit de l'écran.

    ![Volet Nouvel environnement](media/new-environment-pane.PNG "Volet Nouvel environnement") 

3.  Dans le volet **Nouvel environnement** :

    a.  Entrez un nom pour l'environnement.

    b.  Dans la liste **Type**, sélectionnez **Production**.

    c.  Conservez les paramètres par défaut dans le champ **Région**.  

    d.  Dans le champ **Créer une base de données pour cet environnement ?**, déplacez le curseur sur **Oui**.

    e.  Cliquez sur **Suivant** en bas de l'écran. 

3. Dans le volet **Ajouter une base de données** qui s'affiche, choisissez votre langue et votre devise, laissez les autres paramètres par défaut, puis sélectionnez **Enregistrer**.

   ![Volet Ajouter une base de données](media/add-database-pane.PNG "Volet Ajouter une base de données") 

   >[!NOTE]
   > Pour en savoir plus sur les groupes de sécurité, voir [Contrôler l'accès des utilisateurs aux instances](https://docs.microsoft.com/dynamics365/admin/add-instance-subscription#BKMK_man_sec_group).

   La page suivante apparaît pendant la préparation de l'environnement de production. 
   
    ![Message L'environnement est en cours de préparation](media/environment-message.PNG "Message L'environnement est en cours de préparation") 

4.  Une fois le nouvel environnement actif (signalé comme **Prêt** dans la colonne **État**), passez à la procédure suivante pour modifier la taille maximale du fichier de téléchargement.

>[!NOTE]
>Si vous configurez un environnement de production au lieu d'un environnement d'évaluation, dans les procédures suivantes de cette rubrique, utilisez l'environnement de production au lieu de l'environnement par défaut indiqué dans les captures d'écran.

## Modifier la taille maximale de fichier pour le téléchargement<a name="upload"></a>

Dans l'application du PC [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous pouvez télécharger vos propres fichiers 3D, ainsi que des vidéos et des images 2D. La taille de plusieurs de ces fichiers sera supérieure à 5 Mo, vous devrez donc modifier la taille maximale des fichiers qui seront chargés. Pour ce faire, vous devrez remplacer le paramètre de la taille de pièce jointe.

1. Dans la page **Environnements** du Centre d'administration Power Platform, sélectionnez l'environnement nouvellement créé, puis sélectionnez le bouton **Autres actions d'environnement** (...), puis **Paramètres**. 

    ![Bouton Autres actions d'environnement](media/environment-settings.PNG "Bouton Autres actions d'environnement")
       
2. Sous **E-mail**, sélectionnez **Paramètres d'e-mail**. 

    ![Paramètres d'e-mail](media/email-settings.png "Paramètres d'e-mail")

3. Faites défiler l'écran vers le bas de la page, puis sous **Documents joints**, définissez le champ **Taille maximale de fichier pour les pièces jointes** sur 131072. Sélectionnez **Enregistrer** une fois terminé.

    ![Taille du fichier](media/edit-file-size.png "Taille du fichier")

4. Revenez sur la page **Environnements** pour préparer l'étape suivante. 

## Installer et configurer la solution<a name="configure"></a>

1. Dans le [Centre d'administration Power Platform](https://admin.powerplatform.microsoft.com/environments), sélectionnez le bouton **Autres actions d'environnement** (...) en regard de l'environnement configuré, puis sélectionnez **Gérer les solutions**.

    ![Gérer les solutions](media/manage-solutions.PNG "Gérer les solutions")
     
    >[!NOTE]
    > Vous pouvez également accéder au Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)] à partir du portail Power Apps.
    
2. Sélectionnez la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] dans la liste, puis sélectionnez **Installer**.

    ![Bouton Installer](media/solutions-install-button.png "Bouton Installer")
    
3. Dans la boîte de dialogue **Conditions d'utilisation**, examinez les conditions, puis sélectionnez **Installer**.

    Dans la page Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)], le message suivant apparaît en surbrillance jaune pour indiquer que la solution est sur le point d'être installée : « Veuillez patienter pendant que l'installation démarre. » 
        
     ![Message d'installation](media/installing-solution.png "Message d'installation")
     
    Le champ **Statut** à gauche du message installation indique **Installation en attente** lorsque la solution est en cours d'installation. Lorsque la solution est installée, le contenu du champ **Statut** est remplacé par **Installé**.
    
    > [!NOTE]
    > Le processus d'installation peut prendre jusqu'à une heure et est variable en fonction du jour et de la région. Si le statut n'a pas changé au bout d'une heure, essayez d'actualiser la page. Si l'installation échoue, vous verrez ce message : « L'installation de la solution a échoué. Réessayez plus tard. Si le problème persiste, contactez le service clientèle. »<br>![Échec de l'installation](media/failed-install.PNG "Échec de l'installation")

## Paramétrer des rôles d'utilisateur pour la solution<a name="user-roles"></a>

> [!NOTE]
> L'affichage d'un utilisateur dans le Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)] peut prendre jusqu'à une heure, une fois les licences ajoutées dans le Centre d'administration [!include[cc-microsoft](../includes/cc-microsoft.md)] 365.

1. Une fois la solution installée, accédez au [Centre d'administration Power Platform](https://admin.powerplatform.microsoft.com/). 

2. Dans la page **Environnements**, sélectionnez l'environnement nouvellement créé, puis sélectionnez le bouton **Autres actions d'environnement** (...), puis **Paramètres**. 

    ![Paramètres d'environnement](media/environment-settings.PNG "Paramètres d'environnement")

3. Sur la page **Paramètres**, développez **Utilisateurs + Autorisations**, puis sélectionnez **Utilisateurs**.

    ![Utilisateurs et autorisations](media/settings-page.png "Utilisateurs et autorisations")
    
    > [!IMPORTANT]
    > Vous pouvez accéder aux données [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] via la vignette **Guides Hub** de la page précédente, mais nous déconseillons d'effectuer des modifications dans Guides Hub. Toute modification apportée peut avoir des conséquences imprévues pour les applications [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].
 
4. Dans la page **Utilisateurs activés**, sélectionnez l'utilisateur, puis sélectionnez **Gérer les rôles**. 

    ![Gérer les rôles](media/manage-roles.png "Gérer les rôles")
 
5. Dans la boîte de dialogue **Gérer les rôles d'utilisateurs**, assurez-vous que la case à cocher **Utilisateur Common Data Service** est cochée.
         
    ![Case à cocher Utilisateur Common Data Service](media/common-data-service-user.PNG "Case à cocher Utilisateur Common Data Service")
    
6. Sélectionnez la case à cocher **D[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] Auteur** ou **[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] Opérateur**, selon les privilèges à accorder à l'utilisateur.

    ![Cases à cocher des rôles Auteur et opérateur](media/select-role.PNG "Cases à cocher des rôles Auteur et opérateur")
    
    Le tableau suivant décrit les privilèges accordés à chaque rôle :
    
    |Rôle|Description|
    |-----------------------|----------------------------------------------------------------------|
    |**Auteur**|Les utilisateurs disposant de ce rôle peuvent utiliser l'application du PC et l'application HoloLens pour créer, modifier et utiliser des guides. Ils peuvent également renommer et désactiver les guides existants.|
    |**Opérateur**|Les utilisateurs avec ce rôle peuvent utiliser l'application HoloLens pour afficher/utiliser un guide. Si le rôle **Opérateur** est définir, les opérateurs peuvent également gagner du temps en ignorant la boîte de dialogue **Sélectionner un mode** lorsqu'ils ouvrent un guide.|
      
7. Si vous souhaitez que ces utilisateurs disposent de privilèges d'administrateur, sélectionnez la case à cocher **Administrateur système**. 
     
## <a name="whats-next"></a>Étapes suivantes

Lorsque vous avez terminé cette étape, passez à l'étape 2 du processus de configuration : [Télécharger et installer les applications](setup-step-three.md)<br>

Si vous rencontrez des problèmes avec l'une des procédures de cette étape :

- Posez des questions sur notre site communautaire à l'adresse https://community.dynamics.com/365/guides.

- Contactez le service clientèle à l'adresse https://dynamics.microsoft.com/support/.

