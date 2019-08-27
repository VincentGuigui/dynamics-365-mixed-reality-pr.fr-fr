---
author: Mamaylya
description: Tout ce que vous devez savoir sur l'inscription à Dynamics 365 Guides (version préliminaire), la configuration de la solution, et l'installation des applications.
ms.author: mamaylya
ms.date: 04/30/2019
ms.service: crm-online
ms.topic: article
title: S'inscrire à Dynamics 365 Guides (version préliminaire)
ms.reviewer: v-brycho
ms.openlocfilehash: 8e464d99ecd30a39634d1304764b8040d96f6d97
ms.sourcegitcommit: 8770ec043776563f3f9e87ee89f241c68015f576
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/31/2019
ms.locfileid: "1797431"
---
# <a name="sign-up-for-dynamics-365-guides-preview"></a>S'inscrire à Dynamics 365 Guides (version préliminaire)

[!INCLUDE [cc-beta-prerelease-disclaimer](../includes/cc-beta-prerelease-disclaimer.md)]
 
Nous sommes heureux d'annoncer l'arrivée de [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)] ! [En savoir plus sur les fonctionnalités de Guides](index.md).

Pour démarrer avec [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous devez :

1.  Vous inscrire à la version préliminaire.

2.  Créer un environnement Common Data Service, si vous n'en avez pas encore.

3. Installer la solution [!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)].

4.  Télécharger et installer les applications [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] sur un [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC et [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-hololens](../includes/pn-hololens.md)].

5. Ajouter des comptes d'utilisateur supplémentaires (facultatif).

6. Paramétrer les états d'Analyses de Guides.

Cette rubrique fournit des instructions détaillées pour tout ce qui précède.

## <a name="step-1-sign-up-for-the-preview"></a>Étape 1 : S'inscrire à la version préliminaire

- Accédez à la page [Mise en route](http://aka.ms/GetGuides), puis suivez les instructions pour créer vos informations d'identification utilisateur pour la version préliminaire. Une fois que vous avez vos informations d'identification, revenez sur cette page et cliquez sur [Étape 2 : Créer un environnement Common Data Service](#cds).

    > [!IMPORTANT] 
    > Nous vous recommandons de créer des informations d'identification utilisateur pour la version préliminaire même si vous avez déjà un compte professionnel. Si vous n'êtes pas administrateur de l'organisation, vous ne pourrez pas effectuer les étapes 2 et 3. En outre, une fois invité à entrer un nom de domaine, n'utilisez pas votre domaine professionnel. Créez un nouveau domaine dans l'écran : **guides*YourCompanyName***.
 
## Étape 2 : Créer un environnement Common Data Service<a name="cds"></a>

Une fois l'inscription à la version préliminaire effectuée, vous devez créer un environnement dans lequel installer la solution [!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)]. Si vous avez déjà un environnement Common Data Service, vous pouvez passer à l'[Étape 3 : Installation et configuration de la solution Dynamics 365 Guides](#configure).

1.   Accédez à [Centre d'administration Microsoft 365](https://admin.microsoft.com/AdminPortal/Home).


2.  Assurez-vous que la licence Dynamics 365 Guides est affectée à un utilisateur. Pour cela, dans le volet gauche, sélectionnez **Utilisateurs**, **Utilisateurs actifs**, puis activez la case à cocher en regard de l'utilisateur à ajouter. 

    ![Écran Utilisateurs > Utilisateurs actifs](media/users-active-users.PNG "Écran Utilisateurs > Utilisateurs actifs")
    
3.  Dans l'écran **Compte Guides**, cliquez sur le bouton **Modifier** en regard de **Licences de produit**.

     ![Modifier le plan PowerApps](media/edit-powerapps-plan.PNG "Modifier le plan PowerApps")


4.  Dans l'écran **Licences de produit**, déplacez le curseur **Dynamics 365 Guides** sur **Activé**, puis sélectionnez **Enregistrer**.
  
    ![Ajouter des licences utilisateur](media/guides-license.PNG "Ajouter des licences utilisateur")
    
5.  Accédez à [Centre d'administration PowerApps](https://preview.admin.powerapps.com/environments), puis connectez-vous avec les informations d'identification utilisateur fournies lorsque vous vous êtes inscrit à la version préliminaire.

6.  Sélectionnez **Nouvel environnement** dans le centre d'administration PowerApps.

    ![Centre d'administration PowerApps](media/powerapps-environment.PNG "Centre d'administration PowerApps")
 
7.  Renseignez les détails suivants pour l'environnement :

    -   **Nom de l'environnement :** Guides_*anyname*
    -   **Région :** Ne pas modifier - **conserver les paramètres par défaut**
    -   **Type d'environnement :** Définissez-le sur **Production**
  
        ![Boîte de dialogue Nouvel environnement](media/new-environment-dialog.PNG "Boîte de dialogue Nouvel environnement")
        
    > [!NOTE]
    > Définissez **Type d'environnement** sur **Production**. Ne le définissez pas sur **Essai**.
    
8.  Cliquez sur le bouton **Créer un environnement**. 

9.  Dans la boîte de dialogue qui apparaît, sélectionnez **Créer une base de données**.

    ![Boîte de dialogue de création de l'environnement](media/environment-created.PNG "Boîte de dialogue de création de l'environnement")   
    
10. Dans la boîte de dialogue suivante, sélectionnez la devise et la langue.

    ![Paramètres de devise et de langue](media/currency-language-settings.PNG "Paramètres de devise et de langue")
  
11. Sélectionnez **Créer une base de données.**

12. Dans l'écran **Centre d'administration PowerApps** > **Environnements**, sélectionnez l'environnement qui vient d'être créé (un environnement de production, pas un environnement par défaut). 

    ![Sélectionner l'environnement](media/select-environment.PNG "Sélectionner l'environnement")
 
    L'écran suivant s'affiche alors que la base de données est créée et mise en service :
    
    ![Écran d'approvisionnement de la base de données](media/provisioning-database.PNG "Écran d'approvisionnement de la base de données")
 
    > [!NOTE]
    > La création de la base de données prend généralement quelques minutes. Si, au bout de 5 minutes, le message « Approvisionnement de la base de données » apparaît toujours, essayez d'actualiser la page.
    

13. Une fois que la base de données est créée, un lien vers le Centre d'administration Dynamics 365 apparaît. Sélectionnez ce lien, puis connectez-vous à nouveau avec les informations d'identification que vous avez créées pour la version préliminaire. Vous devrez peut-être fermer votre navigateur avant de vous connecter. 

    ![Lien Centre d'administration](media/admin-center-link.PNG "Lien Centre d'administration")

Le centre d'administration Dynamics apparaît. Il s'agit de l'emplacement où vous pouvez installer la solution et effectuer d'autres configurations.

## Étape 3 : Installer et configurer la solution Dynamics 365 Guides (version préliminaire)<a name="configure"></a>

Dans l'application du PC [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous pouvez télécharger vos propres fichiers 3D, ainsi que des vidéos et des images 2D. La taille de plusieurs de ces fichiers sera supérieure à 5 Mo, vous devrez donc modifier la taille maximale des fichiers qui seront chargés. Pour ce faire, vous devrez remplacer le paramètre de la taille de pièce jointe par 128 Mo (131072 Ko). 

1.  Accédez au [Centre d'administration Dynamics 365](https://port.crm.dynamics.com/G/Instances/InstancePicker.aspx), puis connectez-vous avec les informations d'identification utilisateur créées lorsque vous vous êtes inscrit pour [!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)]. 
    
2.  Sélectionnez l'instance [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] qui vient d'être créée dans la liste d'instances, puis sélectionnez **Ouvrir** comme indiqué ici : 
    
    ![Centre d'administration avec le bouton Ouvrir sélectionné](media/admin-center-open-button.PNG "Centre d'administration avec le bouton Ouvrir sélectionné")
    
    Cela ouvre l'écran **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]**.
    
3.  Dans l'écran **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]**, sélectionnez **Paramètres**, puis sélectionnez **Paramètres avancés**. 

    ![Paramètres avancés](media/advanced-settings.PNG "Paramètres avancés")
    
4.  Dans l'écran **[!include[pn-dyn-365](../includes/pn-dyn-365.md)] Gestion d'entreprise**, sélectionnez la liste déroulante **Paramètres**.

     ![Écran2 Gestion d'entreprise](media/business-management.PNG "Écran Gestion d'entreprise")
    
5.  Sous **Système**, sélectionnez **Administration**.

    ![Bouton Administration dans Dynamics 365](media/administration-button.PNG "Bouton Administration dans Dynamics 365")
 
6.  Dans la page **[!include[pn-dyn-365](../includes/pn-dyn-365.md)] Paramètres > Administration**, sélectionnez **Paramètres système**.

    ![Paramètres système dans Dynamics 365](media/system-settings.PNG "Paramètres système dans Dynamics 365")
  
7.  Dans la boîte de dialogue **Paramètres système**, sélectionnez l'onglet **E-mail**, faites défiler l'écran vers le bas de la boîte de dialogue, puis dans le champ **Définir la limite de la taille de fichier pour les pièces jointes**, entrez **131072**. Cliquez sur **OK** lorsque vous avez terminé.

    ![Boîte de dialogue Paramètres système](media/system-settings-dialog-box.PNG "Boîte de dialogue Paramètres système")
 
8.  Revenez dans le [Centre d'administration Dynamics 365](https://port.crm.dynamics.com/G/Instances/InstancePicker.aspx), puis sélectionnez le petit bouton Modifier en regard de **Solutions**.

    ![Bouton Modifier Solutions](media/solutions-edit-button.PNG "Bouton Modifier Solutions")
 
    > [!NOTE]
    > Vous pouvez également accéder au Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)] à partir du portail PowerApps.
    
8.  Sélectionnez la solution [!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)] dans la liste, puis sélectionnez **Installer**. 

    ![Bouton Solutions Installer](media/solutions-install-button.PNG "Bouton Solutions Installer")
    
9. Dans la boîte de dialogue **Conditions d'utilisation**, examinez les conditions, puis sélectionnez **Installer** lorsque vous êtes prêt.

   Dans l'écran **Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)]**, le message suivant apparaît en surbrillance jaune pour indiquer que la solution est sur le point d'être installée :

   ![Message d'installation de la solution](media/installing-solution.PNG "Message d'installation de la solution")
   
   Le champ **Statut** à gauche du message jaune indique **Installation en attente** lorsque la solution est en cours d'installation. Lorsque la solution est installée, le contenu du champ **Statut** est remplacé par **Installé**.
 
    > [!NOTE]
    > Le processus d'installation peut prendre jusqu'à une heure et est variable en fonction du jour et de la région. Si le statut n'a pas changé au bout d'une heure, essayez d'actualiser l'écran. Si l'installation échoue, vous verrez ce message :<br>![Échec de l'installation](media/failed-install.PNG "Échec de l'installation")

### Paramétrer des rôles d'utilisateur pour la solution<a name="user-roles"></a>

> [!NOTE]
> L'affichage d'un utilisateur dans le Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)] peut prendre jusqu'à une heure, une fois les licences ajoutées dans le Centre d'administration [!include[cc-microsoft](../includes/cc-microsoft.md)] 365. 

1.  Une fois la solution installée, accédez au [Centre d'administration Dynamics 365](https://port.crm.dynamics.com/G/Instances/InstancePicker.aspx), sélectionnez l'instance [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] qui vient d'être créée dans la liste des instances, puis sélectionnez **Ouvrir**.

2. Sur la page **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]**, sélectionnez **Paramètres**, puis sélectionnez **Paramètres avancés**.

    ![Paramètres avancés Dynamics 365](media/roles-advanced-settings.PNG "Paramètres avancés Dynamics 365")
    
    > [!IMPORTANT]
    > Vous pouvez accéder aux données [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] via la vignette Guides Hub (version préliminaire) de l'écran précédent, mais nous déconseillons d'effectuer des modifications dans Guides Hub. Toute modification apportée peut avoir des conséquences imprévues pour les applications [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].
 
3.   Dans l'écran **[!include[pn-dyn-365](../includes/pn-dyn-365.md)] > Gestion d'entreprise**, sélectionnez la liste déroulante **Paramètres**.
    
     ![Écran2 Gestion d'entreprise](media/business-management.PNG "Écran Gestion d'entreprise")

4.  Sur la page **[!include[pn-dyn-365](../includes/pn-dyn-365.md)] Paramètres** > **Administration**, sous **Système**, sélectionnez **Sécurité**. 

    ![Paramètre de sécurité Dynamics 365](media/security-setting.PNG "Paramètre de sécurité Dynamics 365")
 
4.  Dans la page **Sécurité**, sélectionnez **Utilisateurs**.

    ![Paramètre Utilisateurs Dynamics 365](media/select-users.PNG "Paramètre Utilisateurs Dynamics 365")
 
5.  Sélectionnez l'utilisateur, puis sélectionnez **Gérer les rôles**. 

    ![Commande Gérer les rôles](media/manage-roles-command.PNG "Commande Gérer les rôles")
 
6.  Dans la boîte de dialogue **Gérer les rôles d'utilisateurs**, sélectionnez les rôles suivants : 

    - Utilisateur Common Data Service
    
    - Auteur [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]
    
    - Administrateur système 
       
      ![Boîte de dialogue Gérer les rôles renseignée](media/manage-roles-dialog-box.PNG "Boîte de dialogue Gérer les rôles renseignée")
      
      > [!NOTE]
      > Sélectionnez le rôle Administrateur système s'il s'agit de l'utilisateur principal/de l'administrateur. Sinon, ne sélectionnez pas ce rôle.
 
     
## <a name="step-4-install-the-applications"></a>Étape 4 : Installer les applications

Il y a deux applications [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] : 

- Application de création du PC

- Application [!include[pn-hololens](../includes/pn-hololens.md)], avec un mode Créer et un mode Opérateur

Vous pouvez installer les applications à partir de [!include[cc-microsoft](../includes/cc-microsoft.md)] Store tel que décrit dans la section suivante.

> [!NOTE]
> Si vous ne pouvez pas accéder à [!include[cc-microsoft](../includes/cc-microsoft.md)] Store en raison de politiques d'entreprise, contactez votre administrateur pour qu'il distribue l'application.

Si vous utilisez [!include[cc-microsoft](../includes/cc-microsoft.md)] Store pour Entreprises pour distribuer vos applications, les utilisateurs peuvent les installer à partir du magasin privé de votre organisation ou d'un lien que vous leur envoyez par e-mail. Les instructions sont fournies plus loin dans cette rubrique.

### <a name="install-the-apps-from-microsoft-store"></a>Installer les applications à partir de Microsoft Store

#### <a name="install-the-pc-authoring-app"></a>Installer l'application de création sur PC 
1.  Assurez-vous que votre [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC exécute la dernière version de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] (10.0.16299 ou ultérieure).

2.  Sur votre PC, allez dans **Démarrer** ![Bouton Démarrer](media/windows-button.png "Bouton Démarrer") > **[!include[cc-microsoft](../includes/cc-microsoft.md)] Store** ![Bouton Store](media/store-button.png "Bouton Store"), puis recherchez [!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)].

3.  Dans [!include[cc-microsoft](../includes/cc-microsoft.md)] Store, sélectionnez **Obtenir** en regard de l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] pour la télécharger et l'installer.

    ![Application préliminaire dans Microsoft Store](media/preview-app.PNG "Application préliminaire dans Microsoft Store")

    > [!NOTE]
    > Pour obtenir des instructions sur l'ouverture et la connexion à l'application, voir [Création de guide](authoring-overview.md).

#### <a name="install-the-hololens-app"></a>Installer l'application HoloLens

1.  Assurez-vous qu'[!include[pn-hololens](../includes/pn-hololens.md)] exécute la version 10.0.14393.0 ou ultérieure. Nous vous recommandons de mettre à jour [!include[pn-hololens](../includes/pn-hololens.md)] vers des versions plus récentes quand elles sont disponibles. Voir [Gérer les mises à jour vers HoloLens](https://docs.microsoft.com/en-us/HoloLens/hololens-updates) pour obtenir des instructions sur l'utilisation de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Update pour Entreprise.

2.  Dans [!include[pn-hololens](../includes/pn-hololens.md)], utilisez l'écartement des doigts paume vers le haut pour ouvrir le menu **Accueil**, puis ouvrez l'application [!include[cc-microsoft](../includes/cc-microsoft.md)] Store et recherchez [!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)].

3.  Sélectionnez **Installer** pour télécharger et installer l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

> [!NOTE] 
> Pour obtenir des instructions sur l'ouverture et la connexion à l'application, si vous êtes un auteur, consultez la [rubrique de création HoloLens](hololens-authoring.md). Les opérateurs peuvent utiliser le [manuel de l'opérateur Dynamics 365 Guides](operator-guide.md).

### <a name="distribute-the-apps-through-the-microsoft-store-for-business"></a>Distribuer les applications via Microsoft Store pour Entreprises

1.  Accédez à [Microsoft Store pour Entreprises](https://businessstore.microsoft.com/en-us/store).

2.  [Faites l'acquisition de la ou des applications](https://docs.microsoft.com/en-us/microsoft-store/acquire-apps-microsoft-store-for-business).

3.  Choisissez l'une des méthodes de distribution suivantes :

    - [Magasin privé](https://docs.microsoft.com/en-us/microsoft-store/distribute-apps-from-your-private-store)
    
    - [Lien de courrier électronique](https://docs.microsoft.com/en-us/microsoft-store/assign-apps-to-employees)
    
    - [Gestion des périphériques mobiles](https://docs.microsoft.com/en-us/microsoft-store/configure-mdm-provider-microsoft-store-for-business)

Pour plus d'informations sur l'ouverture et la connexion à l'application du PC après l'avoir installée, voir [Création de guide](authoring-overview.md).

Pour plus d'informations sur l'ouverture et la connexion à l'application [!include[pn-hololens](../includes/pn-hololens.md)], accédez à l'une des options suivantes, selon que vous êtes auteur ou opérateur :

   - [Création HoloLens](hololens-authoring.md)
   
   - [Manuel de l'opérateur](operator-guide.md)
   
## Étape 5 : Ajouter des comptes d'utilisateur supplémentaires (facultatif)<a name="user-accounts"></a>

Vous devrez créer un compte d'utilisateur pour toutes les personnes à que vous affectez une licence. Créez un compte d'utilisateur pour toutes les personnes de votre équipe qui vont utiliser [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Vous devez créer des comptes d'utilisateur dans le Centre d'administration Microsoft 365 [!include[cc-microsoft](../includes/cc-microsoft.md)], puis affecter des licences à ces utilisateurs.

### <a name="add-a-user-account"></a>Ajouter un compte d'utilisateur

1.  Accédez à [Centre d'administration Microsoft 365](https://admin.microsoft.com/AdminPortal/Home).

2.  Sélectionnez **Ajouter un utilisateur**.

    ![Ajouter un utilisateur](media/add-user.PNG "Ajouter un utilisateur")
 
    La boîte de dialogue **Nouvel utilisateur** s'affiche :
    
    ![Boîte de dialogue Nouvel utilisateur](media/new-user-dialog-box.PNG "Boîte de dialogue Nouvel utilisateur")
 
3.  Dans la boîte de dialogue **Nouvel utilisateur**, renseignez les informations utilisateur suivantes :

    - Ajoutez le prénom, le nom, le nom complet et le nom d'utilisateur.

    - **Domaine.** Laissez le domaine tel quel. Il est automatiquement renseigné en fonction de la société que vous avez entrée lorsque vous vous êtes inscrit pour la version préliminaire. 

    - **Mot de passe.** Le système génère un ID utilisateur et un mot de passe temporaires pour l'utilisateur. Nous vous recommandons d'envoyer les informations d'identification temporaires à l'utilisateur via e-mail et d'inviter l'utilisateur à changer de mot de passe à la première connexion. Pour appliquer cela, sélectionnez la flèche vers le bas, puis activez la case à cocher **Demander à cet utilisateur de modifier son mot de passe lorsqu'il se connecte pour la première fois**. 
    
      ![Case à cocher pour l'application du mot de passe](media/password-enforcement.PNG "Case à cocher pour l'application du mot de passe")

    - **Rôles.** Développez cette section et sélectionnez l'option **Utilisateur (aucun accès Administrateur)**. 
    
      ![Modifier les rôles d'utilisateur](media/user-roles.PNG "Modifier les rôles d'utilisateur")
 

    - **Licences de produits**. Développez cette section, puis déplacez le curseur sur **Dynamics 365 Guides** **Activé**. Vous pouvez affecter jusqu'à 25 utilisateurs.
    
      ![Boîte de dialogue Licences de produits](media/new-user-plans.PNG "Boîte de dialogue Licences de produits")
 
4.  Sélectionnez **Ajouter** lorsque vous avez terminé.

    Lorsque vous ajoutez un utilisateur, celui-ci reçoit une notification par e-mail de l'équipe en ligne de services [!include[cc-microsoft](../includes/cc-microsoft.md)] qui inclut leur ID utilisateur et leur mot de passe temporaire. Il doit utiliser ces informations pour se connecter à [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

5. Si ce n'est déjà fait, [paramétrez des rôles d'utilisateur pour la solution](#user-roles) comme décrit précédemment dans cette rubrique.

## <a name="step-6-set-up-guides-analytics-reports"></a>Étape 6 : Paramétrer les états d'Analyses de Guides 

[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] inclut des états [!include[pn-power-bi](../includes/pn-power-bi.md)] (appelés Analyses de Guides) qui permettent d'analyser les processus des guides. Vous pouvez partager ces états au sein de votre organisation en les publiant dans le service [!include[pn-power-bi](../includes/pn-power-bi.md)]. Cela permet à toute personne de votre organisation ayant une licence Pro [!include[pn-power-bi](../includes/pn-power-bi.md)] d'accéder à l'état via l'interface Web du service [!include[pn-power-bi](../includes/pn-power-bi.md)] accessible sur [https://powerbi.microsoft.com](https://powerbi.microsoft.com).  

[!include[pn-power-bi](../includes/pn-power-bi.md)] fournit plusieurs systèmes pour partager des états avec d'autres personnes de votre organisation. Nous vous recommandons de lire [Comment partager votre travail dans Power BI](https://docs.microsoft.com/en-us/power-bi/service-how-to-collaborate-distribute-dashboards-reports) pour obtenir une vue d'ensemble. Pour partager facilement vos états dans votre organisation en lecture seule, publiez-les sous forme d'application [!include[pn-power-bi](../includes/pn-power-bi.md)]. Cela implique de suivre les étapes bien documentées suivantes : 

1.  [Créer un espace de travail dans le service Power BI](https://docs.microsoft.com/en-us/power-bi/service-create-workspaces). 

2.  [Publier les états d'Analyses de Guides dans cet espace de travail via Power BI Desktop](https://docs.microsoft.com/en-us/power-bi/desktop-upload-desktop-files). 

3.  [Publier le contenu de l'espace de travail en tant qu'application dans le service Power BI](https://docs.microsoft.com/en-us/power-bi/service-create-distribute-apps).  

### <a name="see-also"></a>Voir aussi

[Mise en route de Dynamics 365 Guides en version préliminaire](get-started.md)<br>
[Créer un guide](authoring-overview.md)<br>
[Manuel de l'opérateur](operator-guide.md)<br>
[Analyser les guides pour rendre les processus plus efficaces](analytics-guide.md)<br>
[FAQ](faq.md)






