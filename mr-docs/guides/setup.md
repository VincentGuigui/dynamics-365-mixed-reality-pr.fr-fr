---
author: Mamaylya
description: Tout ce que vous devez savoir sur l'achat de Dynamics 365 Guides, la configuration de la solution, et l'installation des applications.
ms.author: mamaylya
ms.date: 01/07/2020
ms.service: crm-online
ms.topic: article
title: Acheter et déployer Dynamics 365 Guides
ms.reviewer: v-brycho
ms.openlocfilehash: 1aa7f16db5360fca75a2a65f5650f511593163db
ms.sourcegitcommit: de7d5972e721f2f061df6e0cd4cdb057da100bf1
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/08/2020
ms.locfileid: "2935923"
---
# <a name="buy-and-deploy-dynamics-365-guides"></a>Acheter et déployer Dynamics 365 Guides

Nous sommes ravis de vous présenter [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] pour la disponibilité générale ! [En savoir plus sur les fonctionnalités de Guides](index.md).

Pour démarrer avec [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous devez :

1. Acheter un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] ou vous inscrire pour un essai gratuit de 30 jours.

2. Créer un environnement Common Data Service (si vous n'en avez pas déjà un) et installer la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] dans l'environnement (instance).

3.  Télécharger et installer les applications [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] sur un [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC et [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-hololens](../includes/pn-hololens.md)].

4. Paramétrer les états d'Analyses de Guides.

5. Ajouter des comptes d'utilisateur supplémentaires (facultatif).

Cette rubrique fournit des instructions détaillées pour tout ce qui précède.

## <a name="step-1-buy-a-dynamics-365-guides-subscription-or-sign-up-for-a-free-trial-subscription"></a>Étape 1 : Acheter un abonnement Dynamics 365 Guides ou s'inscrire pour un essai gratuit.

Il existe plusieurs moyens d'obtenir un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] :

- Si vous avez un compte professionnel Microsoft, vous pouvez accéder directement au Centre d'administration Microsoft 365 et rechercher un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] ici.

- Accédez à la page [Mise en route](https://aka.ms/GetGuides). Vous pouvez utiliser cette page pour acheter un abonnement ou vous inscrire pour un essai gratuit de 30 jours. Si vous vous inscrivez pour un essai gratuit, vous pouvez utiliser les informations d'identification d'un compte Dynamics 365 existant ou en créer de nouvelles. 

    > [!IMPORTANT] 
    > Si vous ne disposez pas des autorisations d'administrateur associées à votre compte de travail, vous ne pourrez pas effectuer l'étape 2 du processus de configuration. Veuillez coordonner la configuration avec votre administrateur. S'il n'est pas possible de coordonner la configuration avec votre administrateur, vous pouvez choisir de créer des informations d'identification d'utilisateur pour essayer [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] en suivant les étapes décrites sur la page [Mise en route](https://aka.ms/GetGuides). Dans ce cas, le nouvel abonné est créé et le compte du nouvel utilisateur créé bénéficie des autorisations d'administrateur. Notez que vous devez fournir le nom de domaine dans l'écran : *guidesYourCompanyName*.
    
Après vous être inscrit(e) pour un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous devez affecter la licence [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] aux comptes d'utilisateur. Pour ce faire :

1. Accédez au [Centre d'administration Microsoft 365](https://admin.microsoft.com/AdminPortal/Home) et assurez-vous que le curseur de l'option **Nouveau Centre d'administration** dans le coin supérieur droit de la page est bien défini sur **activé**.

    ![Curseur Nouveau Centre d'administration](media/new-admin-center-slider.PNG "Curseur Nouveau Centre d'administration")

2.  Assurez-vous que la licence [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] est affectée à un utilisateur. Pour cela, dans le volet gauche, sélectionnez **Utilisateurs**, **Utilisateurs actifs**, puis activez la case à cocher en regard de l'utilisateur à ajouter. 

    ![Page Utilisateurs > Utilisateurs actifs](media/users-active-users.PNG "Page Utilisateurs > Utilisateurs actifs")
    
3.  Sélectionnez **Gérer les licences de produit**.

     ![Gérer les licences de produit](media/manage-product-licenses.PNG "Gérer les licences de produit")

4.  Sur la page **Licences de produit**, activez la case à cocher pour **[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]**.
  
    ![Ajouter une licence utilisateur](media/guides-license.PNG "Ajouter une licence utilisateur") 
 
## Étape 2 : Créer un environnement Common Data Service et installer la solution Dynamics 365 Guides<a name="cds"></a>

Après avoir acquis un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et avoir affecté les licences, vous devez créer un environnement où vous pouvez installer la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Le type d'environnement que vous créez dépend de la création d'un environnement d'évaluation ou de production.

>[!NOTE]
>Si vous disposez déjà d'un environnement Common Data Service (par exemple, une instance de l'abonnement Dynamics 365 de votre entreprise), vous pouvez passer directement à [Modifier la taille maximale de fichier pour le téléchargement](#upload).

### <a name="set-up-a-trial-environment-on-the-default-instance"></a>Configurer un environnement d'évaluation sur l'instance par défaut

Notez que l'instance par défaut ne fournit pas de capacités de sauvegarde et de restauration. Si vous avez besoin de ces fonctionnalités, vous devez acheter une licence et configurer un environnement de production comme décrit dans la procédure suivante.
    
1.  Accédez au [Centre d'administration Power Platform](https://admin.powerplatform.microsoft.com/environments) et connectez-vous avec les informations d'identification de l'utilisateur Administrateur (celles liées aux licences [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] affectées).

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

7.  Une fois que la base de données a été créée, revenez à la page **Environnements** et allez à la procédure [Modifier la taille maximale de fichier pour le téléchargement](#upload) décrite plus loin dans cette rubrique.

### <a name="set-up-a-production-environment"></a>Configurer un environnement de production

Si vous avez acheté une licence pour [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous devez configurer un environnement de production. Un environnement de production offre des capacités de sauvegarde et de restauration.

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
>Dans les procédures suivantes de cette rubrique, utilisez l'environnement de production au lieu de l'environnement par défaut indiqué dans les captures d'écran.

<a name="upload"></a>

### <a name="change-maximum-upload-file-size"></a>Modifier la taille maximale de fichier pour le téléchargement

Dans l'application du PC [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous pouvez télécharger vos propres fichiers 3D, ainsi que des vidéos et des images 2D. La taille de plusieurs de ces fichiers sera supérieure à 5 Mo, vous devrez donc modifier la taille maximale des fichiers qui seront chargés. Pour ce faire, vous devrez remplacer le paramètre de la taille de pièce jointe par 128 Mo (131072 Ko).

1. Dans la page **Environnements** du Centre d'administration Power Platform, sélectionnez l'environnement nouvellement créé, puis sélectionnez le bouton **Autres actions d'environnement** (...), puis **Paramètres**. 

    ![Bouton Autres actions d'environnement](media/environment-settings.PNG "Bouton Autres actions d'environnement")
       
2. Sous **E-mail**, sélectionnez **Paramètres d'e-mail**. 

    ![Paramètres d'e-mail](media/email-settings.png "Paramètres d'e-mail")

3. Faites défiler l'écran vers le bas de la page, puis sous **Documents joints**, définissez le champ **Taille maximale de fichier pour les pièces jointes** sur 131072. Sélectionnez **Enregistrer** une fois terminé.

    ![Taille du fichier](media/edit-file-size.png "Taille du fichier")

4. Revenez sur la page **Environnements** pour préparer l'étape suivante. 

### Installer et configurer la solution Dynamics 365 Guides<a name="configure"></a>

1. Dans le [Centre d'administration Power Platform](https://admin.powerplatform.microsoft.com/environments), sélectionnez le bouton **Autres actions d'environnement** (...) en regard de l'environnement configuré, puis sélectionnez **Gérer les solutions**.

    ![Gérer les solutions](media/manage-solutions.PNG "Gérer les solutions")
     
    >[!NOTE]
    > Vous pouvez également accéder au Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)] à partir du portail PowerApps.
    
2. Sélectionnez la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] dans la liste, puis sélectionnez **Installer**.

    ![Bouton Installer](media/solutions-install-button.png "Bouton Installer")
    
3. Dans la boîte de dialogue **Conditions d'utilisation**, examinez les conditions, puis sélectionnez **Installer**.

    Dans la page Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)], le message suivant apparaît en surbrillance jaune pour indiquer que la solution est sur le point d'être installée : « Veuillez patienter pendant que l'installation démarre. » 
        
     ![Message d'installation](media/installing-solution.png "Message d'installation")
     
    Le champ **Statut** à gauche du message installation indique **Installation en attente** lorsque la solution est en cours d'installation. Lorsque la solution est installée, le contenu du champ **Statut** est remplacé par **Installé**.
    
    > [!NOTE]
    > Le processus d'installation peut prendre jusqu'à une heure et est variable en fonction du jour et de la région. Si le statut n'a pas changé au bout d'une heure, essayez d'actualiser la page. Si l'installation échoue, vous verrez ce message : « L'installation de la solution a échoué. Réessayez plus tard. Si le problème persiste, contactez le service clientèle. »<br>![Échec de l'installation](media/failed-install.PNG "Échec de l'installation")

### Paramétrer des rôles d'utilisateur pour la solution<a name="user-roles"></a>

> [!NOTE]
> L'affichage d'un utilisateur dans le Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)] peut prendre jusqu'à une heure, une fois les licences ajoutées dans le Centre d'administration [!include[cc-microsoft](../includes/cc-microsoft.md)] 365.

1. Une fois la solution installée, accédez au [Centre d'administration Power Platform](https://admin.powerplatform.microsoft.com/). 

2. Dans la page **Environnements**, sélectionnez l'environnement nouvellement créé, puis sélectionnez le bouton **Paramètres** dans la barre de titre. 

3. Sur la page **Paramètres**, sous **Utilisateurs + Autorisations**, sélectionnez **Utilisateurs**.

    ![Utilisateurs et autorisations](media/settings-page.png "Utilisateurs et autorisations")
    
    > [!IMPORTANT]
    > Vous pouvez accéder aux données [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] via la vignette Guides Hub de la page précédente, mais nous déconseillons d'effectuer des modifications dans Guides Hub. Toute modification apportée peut avoir des conséquences imprévues pour les applications [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].
 
4.  Dans la page **Utilisateurs activés**, sélectionnez l'utilisateur, puis sélectionnez **Gérer les rôles**. 

    ![Gérer les rôles](media/manage-roles.png "Gérer les rôles")
 
5.  Dans la boîte de dialogue **Gérer les rôles d'utilisateurs**, sélectionnez les rôles suivants : 

    - Utilisateur Common Data Service    

    - Auteur [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]    
         
      ![Boîte de dialogue Gérer les rôles renseignée](media/manage-roles-dialog-box.PNG "Boîte de dialogue Gérer les rôles renseignée")
      
      > [!NOTE]
      > Sélectionnez également le rôle Administrateur système s'il s'agit de l'utilisateur principal/de l'administrateur. Sinon, ne sélectionnez pas ce rôle. 
     
## <a name="step-3-download-and-install-the-apps"></a>Étape 3 : Télécharger et installer les applications.

Il y a deux applications [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] : 

- Application de création du PC

- Application [!include[pn-hololens](../includes/pn-hololens.md)], avec un mode Créer et un mode Opérateur

Vous pouvez installer les deux applications à partir de [!include[cc-microsoft](../includes/cc-microsoft.md)] Store tel que décrit dans la section suivante.

> [!NOTE]
> Si vous ne pouvez pas accéder à [!include[cc-microsoft](../includes/cc-microsoft.md)] Store en raison de politiques d'entreprise, contactez votre administrateur pour qu'il distribue l'application.

Si vous utilisez [!include[cc-microsoft](../includes/cc-microsoft.md)] Store pour Entreprises pour distribuer vos applications, les utilisateurs peuvent les installer à partir du magasin privé de votre organisation ou d'un lien que vous leur envoyez par e-mail. Les instructions sont fournies plus loin dans cette rubrique.

### <a name="install-the-apps-from-microsoft-store"></a>Installer les applications à partir de Microsoft Store

#### <a name="install-the-pc-authoring-app"></a>Installer l'application de création sur PC 
1.  Assurez-vous que votre [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC exécute la dernière version de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] (doit correspondre à la version 10.0.17134, mise à jour d’avril 2018 ou ultérieure).

2.  Sur votre PC, allez dans **Démarrer** ![Bouton Démarrer](media/windows-button.png "Bouton Démarrer") > **[!include[cc-microsoft](../includes/cc-microsoft.md)] Store** ![bouton Store](media/store-button.png "Bouton Store"), puis recherchez [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

3.  Dans [!include[cc-microsoft](../includes/cc-microsoft.md)] Store, sélectionnez **Installer** pour télécharger et installer l'application.

    > [!NOTE]
    > Pour obtenir des instructions sur l'ouverture et la connexion à l'application, voir [Guide Création sur PC](pc-authoring.md).

#### <a name="install-the-hololens-app"></a>Installer l'application HoloLens

1.  Assurez-vous qu'[!include[pn-hololens](../includes/pn-hololens.md)] exécute la version 10.0.17134 ou ultérieure. Nous vous recommandons de mettre à jour [!include[pn-hololens](../includes/pn-hololens.md)] vers des versions plus récentes quand elles sont disponibles. Pour obtenir des instructions sur l'utilisation de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Update pour Entreprise, voir [Gérer les mises à jour vers HoloLens](https://docs.microsoft.com/HoloLens/hololens-updates).

2.  Dans [!include[pn-hololens](../includes/pn-hololens.md)], utilisez l'écartement des doigts paume vers le haut pour ouvrir le menu **Accueil**, puis ouvrez l'application [!include[cc-microsoft](../includes/cc-microsoft.md)] Store et recherchez [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

3.  Pour télécharger et installer l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], sélectionnez **Installer**.

> [!NOTE] 
> Si vous êtes un auteur, consultez la rubrique de création [HoloLens](hololens-authoring.md) pour obtenir des instructions sur l'ouverture et la connexion à l'application. Les opérateurs peuvent utiliser le [manuel de l'opérateur Dynamics 365 Guides](operator-guide.md).

### <a name="distribute-the-apps-through-microsoft-store-for-business"></a>Répartir les applications par le biais de Microsoft Store pour Entreprises

1.  Allez à [Microsoft Store pour Entreprises](https://businessstore.microsoft.com/store).

2.  [Faites l'acquisition de la ou des applications](https://docs.microsoft.com/microsoft-store/acquire-apps-microsoft-store-for-business).

3.  Choisissez l'une des méthodes de distribution suivantes :

    - [Magasin privé](https://docs.microsoft.com/microsoft-store/distribute-apps-from-your-private-store)
    
    - [Lien de courrier électronique](https://docs.microsoft.com/microsoft-store/assign-apps-to-employees)
    
    - [Gestion des périphériques mobiles](https://docs.microsoft.com/microsoft-store/configure-mdm-provider-microsoft-store-for-business)

Pour plus d'informations sur l'ouverture et la connexion à l'application du PC après l'avoir installée, voir [Création de guide](authoring-overview.md).

Pour plus d'informations sur l'ouverture et la connexion à l'application [!include[pn-hololens](../includes/pn-hololens.md)], accédez à l'une des options suivantes, selon que vous êtes auteur ou opérateur :

   - [Création HoloLens](hololens-authoring.md)
   
   - [Manuel de l'opérateur](operator-guide.md)

## <a name="step-4-set-up-guides-analytics-reports"></a>Étape 4 : Paramétrer les états d'Analyses de Guides 

[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] inclut des états [!include[pn-power-bi](../includes/pn-power-bi.md)] (appelés Analyses de Guides) qui permettent d'analyser les processus des guides [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Suivez les instructions pour savoir comment [ouvrir Analyses de Guides](https://docs.microsoft.com/dynamics365/mixed-reality/guides/analytics-guide#open-guides-analytics) en utilisant l'[application Power BI Desktop](https://powerbi.microsoft.com/get-started/) disponible gratuitement.

Si vous disposez d'une licence [!include[pn-power-bi](../includes/pn-power-bi.md)] Pro, vous pouvez partager vos états d'Analyses de Guides [!include[pn-power-bi](../includes/pn-power-bi.md)] au sein de votre organisation en les publiant dans le service [!include[pn-power-bi](../includes/pn-power-bi.md)]. Cela permet à toute personne de votre organisation ayant une licence Pro [!include[pn-power-bi](../includes/pn-power-bi.md)] d'accéder à l'état via l'interface Web du service [!include[pn-power-bi](../includes/pn-power-bi.md)] accessible sur [https://powerbi.microsoft.com](https://powerbi.microsoft.com). Pour en savoir plus sur la collaboration sur le cloud de [!include[pn-power-bi](../includes/pn-power-bi.md)] et le partage, ainsi que l'inscription à une version d'essai gratuit de [!include[pn-power-bi](../includes/pn-power-bi.md)] Pro, consultez [Getting Started with Power BI Desktop](https://powerbi.microsoft.com/get-started/) et [Ways to share your work in Power BI](https://docs.microsoft.com/power-bi/service-how-to-collaborate-distribute-dashboards-reports).

## Étape 5 : Ajouter des comptes d'utilisateur supplémentaires (facultatif)<a name="user-accounts"></a>

Pour ajouter des utilisateurs supplémentaires, vous devez leur affecter la licence [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et configurer les rôles auxquels ils auront accès dans le Centre d'administration Dynamics 365.

### <a name="add-a-user-account"></a>Ajouter un compte d'utilisateur

1. Accédez à [Centre d'administration Microsoft 365](https://admin.microsoft.com/AdminPortal/Home).

2. Dans le volet gauche, sélectionnez **Utilisateurs**, puis **Utilisateurs actifs**. 

3. Sur la page **Utilisateurs actifs**, sélectionnez **Ajouter un utilisateur**.

   ![Commande Ajouter un utilisateur](media/add-additional-user.png "Commande Ajouter un utilisateur") 

4. Sur la page **Configurer les bases**, renseignez les informations pour le nouvel utilisateur. Sélectionnez **Suivant** une fois terminé.

   ![Page Configurer les bases](media/setup-basics.png "Page Configurer les bases")

   > [!NOTE]
   > Par défaut, un mot de passe sera généré automatiquement pour l'utilisateur. L'utilisateur doit modifier le mot de passe la première fois qu'il se connecte à ce compte. Pour remplacer le mot de passe par un mot de passe permanent au lieu d'utiliser celui généré automatiquement, cochez l'option **Mot de passe généré automatiquement** et désactivez l'option **Demander à cet utilisateur de modifier son mot de passe lorsqu'il se connecte pour la première fois.** 
 
5. Sélectionnez l'emplacement de cet utilisateur, puis sous **Licences**, activez la case à cocher **Dynamics 365 Guides**. 

    ![Case à cocher Dynamics 365 Guides](media/assign-license-user.png "Case à cocher Dynamics 365 Guides") 

     Sélectionnez **Suivant** une fois terminé.
   
7. Sur la page **Paramètres facultatifs**, laissez la zone **Utilisateur (aucun accès Administrateur)** sélectionnée à moins que ce nouvel utilisateur soit un administrateur. Dans ce cas, activez la case à cocher **Administrateur global**. 

   ![Page Paramètres facultatifs](media/user-optional-settings.png "Page Paramètres facultatifs") 
   
8. Pour renseigner les informations de profil du nouvel utilisateur, faites défiler et développez **Informations de profil**. Sélectionnez **Suivant** une fois terminé.
   
   ![Informations de profil développées](media/expanded-profile-info.png "Informations de profil développées")
   
8. Vérifiez les informations de cette dernière page. Pour apporter des modifications, sélectionnez le bouton **Modifier** en dessous de chaque section. Sélectionnez **Terminé l'ajout** une fois terminé.

   ![Page de vérification avec les boutons Modifier](media/review-page.png "Page de vérification avec les boutons Modifier")

9. Si vous avez sélectionné **Mot de passe généré automatiquement** à l'étape 4, notez le mot de passe. L'utilisateur a besoin de ce mot de passe pour se connecter.

   ![Mot de passé généré automatiquement](media/review-user-settings.png "Mot de passe généré automatiquement") 
   
10. Sélectionnez **Fermer**.

11. [Paramétrez des rôles d'utilisateur pour la solution](#user-roles) comme décrit précédemment dans cette rubrique.

### <a name="see-also"></a>Voir aussi

[Mise en route d'Dynamics 365 Guides](get-started.md)<br>
[Créer un guide](authoring-overview.md)<br>
[Manuel de l'opérateur](operator-guide.md)<br>
[Analyser les guides pour rendre les processus plus efficaces](analytics-guide.md)<br>
[FAQ](faq.md)