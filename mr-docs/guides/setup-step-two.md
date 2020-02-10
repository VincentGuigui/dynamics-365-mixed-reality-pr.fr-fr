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
# <a name="dynamics-365-guides-setup-step-2-install-the-solution"></a><span data-ttu-id="51416-103">Étape 2 de la configuration de Dynamics 365 Guides : Installer la solution</span><span class="sxs-lookup"><span data-stu-id="51416-103">Dynamics 365 Guides setup Step 2: Install the solution</span></span>

>[!NOTE]
><span data-ttu-id="51416-104">Avant d'effectuer les procédures de cette étape, vous devez passer par l'étape 1 du processus de configuration : [Acheter un abonnement ou s'inscrire pour un essai gratuit](setup-step-one.md)</span><span class="sxs-lookup"><span data-stu-id="51416-104">Before completing the procedures in this step, make sure to see step 1 in the setup process: [Buy a subscription or sign up for a free trial](setup-step-one.md)</span></span>

<span data-ttu-id="51416-105">Après avoir acheté un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et avoir affecté les licences, vous devez créer un environnement où vous pouvez installer la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="51416-105">After acquiring a [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] subscription and assigning licenses, you need to create an environment where you can install the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] solution.</span></span> <span data-ttu-id="51416-106">Le type d'environnement que vous créez dépend de la création d'un environnement d'évaluation ou de production.</span><span class="sxs-lookup"><span data-stu-id="51416-106">The type of environment you create depends on whether you're creating a trial or production environment.</span></span> <span data-ttu-id="51416-107">Si vous avez acheté une licence pour [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous devez configurer un environnement de production.</span><span class="sxs-lookup"><span data-stu-id="51416-107">If you bought a license for [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], set up a production environment.</span></span> <span data-ttu-id="51416-108">Un environnement de production offre des capacités de sauvegarde et de restauration.</span><span class="sxs-lookup"><span data-stu-id="51416-108">A production environment provides backup and restore capabilities.</span></span> 

>[!NOTE]
><span data-ttu-id="51416-109">Si vous disposez déjà d'un environnement à utiliser (par exemple, une instance de l'abonnement Dynamics 365 de votre entreprise), vous pouvez passer directement à [Modifier la taille maximale de fichier pour le téléchargement](#upload).</span><span class="sxs-lookup"><span data-stu-id="51416-109">If you already have an environment that you want to use (for example, an instance in your company's Dynamics 365 tenant), you can skip to [Change maximum upload file size](#upload).</span></span>

## <a name="set-up-a-trial-environment"></a><span data-ttu-id="51416-110">Configurer un environnement d'évaluation</span><span class="sxs-lookup"><span data-stu-id="51416-110">Set up a trial environment</span></span>
    
1.  <span data-ttu-id="51416-111">Accédez au [Centre d'administration Power Platform](https://admin.powerplatform.microsoft.com/environments) et connectez-vous avec les informations d'identification de l'administrateur pour la version d’évaluation.</span><span class="sxs-lookup"><span data-stu-id="51416-111">Go to the [Power Platform Admin center](https://admin.powerplatform.microsoft.com/environments) and sign in with the admin user credentials for the trial.</span></span>

2.  <span data-ttu-id="51416-112">Dans le Centre d'administration Power Platform, sélectionnez **Environnements**.</span><span class="sxs-lookup"><span data-stu-id="51416-112">In the Power Platform Admin center, select **Environments**.</span></span>

    <span data-ttu-id="51416-113">![Environnements Power Platform](media/powerapps-environments.PNG "Environnements Power Platform")</span><span class="sxs-lookup"><span data-stu-id="51416-113">![Power Platform Environments](media/powerapps-environments.PNG "Power Platform Environments")</span></span>
    
3.  <span data-ttu-id="51416-114">Sélectionnez le bouton **Autres actions d'environnement** (...) en regard de l'instance par défaut, puis sélectionnez **Gérer l'environnement**.</span><span class="sxs-lookup"><span data-stu-id="51416-114">Select the **More environment actions** button (...) next to the default instance, and then select **Manage environment**.</span></span>

    <span data-ttu-id="51416-115">![Gérer l'environnement](media/powerapps-manage-environment.PNG "Gérer l'environnement")</span><span class="sxs-lookup"><span data-stu-id="51416-115">![Manage Environment](media/powerapps-manage-environment.PNG "Manage Environment")</span></span>    
     
4. <span data-ttu-id="51416-116">Modifiez le nom de l'environnement (par exemple, Guides_*un nom quelconque*), puis sélectionnez **Créer ma base de données**.</span><span class="sxs-lookup"><span data-stu-id="51416-116">Change the name of the environment (for example, Guides_*anyname*), and then select **Create my database**.</span></span>

    <span data-ttu-id="51416-117">![Créer une base de données](media/powerapps-create-database.PNG "Créer une base de données")</span><span class="sxs-lookup"><span data-stu-id="51416-117">![Create database](media/powerapps-create-database.PNG "Create database")</span></span>
    
5. <span data-ttu-id="51416-118">Dans la boîte de dialogue **Créer une base de données pour cet environnement**, choisissez votre devise et votre langue.</span><span class="sxs-lookup"><span data-stu-id="51416-118">In the **Create a database for this environment** dialog box, choose your currency and language.</span></span>

    <span data-ttu-id="51416-119">![Paramètres de devise et de langue](media/currency-language-settings.PNG "Paramètres de devise et de langue")</span><span class="sxs-lookup"><span data-stu-id="51416-119">![Currency and language settings](media/currency-language-settings.PNG "Currency and language settings")</span></span>
  
6.  <span data-ttu-id="51416-120">Sélectionnez **Créer une base de données.**</span><span class="sxs-lookup"><span data-stu-id="51416-120">Select **Create database.**</span></span>

    <span data-ttu-id="51416-121">La page suivante s'affiche alors que la base de données est créée et mise en service :</span><span class="sxs-lookup"><span data-stu-id="51416-121">The following page appears while the database is being created and provisioned:</span></span>
    
     <span data-ttu-id="51416-122">![Page Approvisionnement de la base de données](media/provisioning-database.PNG "Page Approvisionnement de la base de données")</span><span class="sxs-lookup"><span data-stu-id="51416-122">![Provisioning database page](media/provisioning-database.PNG "Provisioning database page")</span></span>
 
     > [!NOTE]
     > <span data-ttu-id="51416-123">La création de la base de données prend généralement quelques minutes.</span><span class="sxs-lookup"><span data-stu-id="51416-123">Database creation usually takes several minutes.</span></span> <span data-ttu-id="51416-124">Si, au bout de cinq minutes, le message « Approvisionnement de la base de données » apparaît toujours, essayez d'actualiser la page.</span><span class="sxs-lookup"><span data-stu-id="51416-124">If, after five minutes, the "Provisioning database" message still appears, try refreshing the page.</span></span>

7.  <span data-ttu-id="51416-125">Une fois que la base de données a été créée, revenez à la page **Environnements** et allez à la procédure [Modifier la taille maximale de fichier pour le téléchargement](#upload).</span><span class="sxs-lookup"><span data-stu-id="51416-125">After you've successfully created the database, return to the **Environments** page and go to the [Change maximum upload file size](#upload) procedure.</span></span>

## <a name="set-up-a-production-environment"></a><span data-ttu-id="51416-126">Configurer un environnement de production</span><span class="sxs-lookup"><span data-stu-id="51416-126">Set up a production environment</span></span>

1.  <span data-ttu-id="51416-127">Accédez au [Centre d'administration de Power Platform](https://admin.powerplatform.microsoft.com/environments), sélectionnez **Environnements** s'il n'est pas déjà sélectionné, puis sélectionnez **Nouveau**.</span><span class="sxs-lookup"><span data-stu-id="51416-127">Go to the [Power Platform Admin center](https://admin.powerplatform.microsoft.com/environments), select **Environments** if it's not already selected, and then select **New**.</span></span>

    <span data-ttu-id="51416-128">![Ajouter un nouvel environnement](media/add-new-environment.PNG "Ajouter un nouvel environnement")</span><span class="sxs-lookup"><span data-stu-id="51416-128">![Add new environment](media/add-new-environment.PNG "Add new environment")</span></span> 

    <span data-ttu-id="51416-129">Le volet **Nouvel environnement** apparaît sur le côté droit de l'écran.</span><span class="sxs-lookup"><span data-stu-id="51416-129">The **New environment** pane appears on the right side of the screen.</span></span>

    <span data-ttu-id="51416-130">![Volet Nouvel environnement](media/new-environment-pane.PNG "Volet Nouvel environnement")</span><span class="sxs-lookup"><span data-stu-id="51416-130">![New environment pane](media/new-environment-pane.PNG "New environment pane")</span></span> 

3.  <span data-ttu-id="51416-131">Dans le volet **Nouvel environnement** :</span><span class="sxs-lookup"><span data-stu-id="51416-131">In the **New environment** pane:</span></span>

    <span data-ttu-id="51416-132">a.</span><span class="sxs-lookup"><span data-stu-id="51416-132">a.</span></span>  <span data-ttu-id="51416-133">Entrez un nom pour l'environnement.</span><span class="sxs-lookup"><span data-stu-id="51416-133">Enter a name for the environment.</span></span>

    <span data-ttu-id="51416-134">b.</span><span class="sxs-lookup"><span data-stu-id="51416-134">b.</span></span>  <span data-ttu-id="51416-135">Dans la liste **Type**, sélectionnez **Production**.</span><span class="sxs-lookup"><span data-stu-id="51416-135">In the **Type** list, select **Production**.</span></span>

    <span data-ttu-id="51416-136">c.</span><span class="sxs-lookup"><span data-stu-id="51416-136">c.</span></span>  <span data-ttu-id="51416-137">Conservez les paramètres par défaut dans le champ **Région**.</span><span class="sxs-lookup"><span data-stu-id="51416-137">In the **Region** field, keep the default setting.</span></span>  

    <span data-ttu-id="51416-138">d.</span><span class="sxs-lookup"><span data-stu-id="51416-138">d.</span></span>  <span data-ttu-id="51416-139">Dans le champ **Créer une base de données pour cet environnement ?**, déplacez le curseur sur **Oui**.</span><span class="sxs-lookup"><span data-stu-id="51416-139">In the **Create a database for this environment?** field, move the slider to **Yes**.</span></span>

    <span data-ttu-id="51416-140">e.</span><span class="sxs-lookup"><span data-stu-id="51416-140">e.</span></span>  <span data-ttu-id="51416-141">Cliquez sur **Suivant** en bas de l'écran.</span><span class="sxs-lookup"><span data-stu-id="51416-141">Select **Next** at the bottom of the screen.</span></span> 

3. <span data-ttu-id="51416-142">Dans le volet **Ajouter une base de données** qui s'affiche, choisissez votre langue et votre devise, laissez les autres paramètres par défaut, puis sélectionnez **Enregistrer**.</span><span class="sxs-lookup"><span data-stu-id="51416-142">In the **Add database** pane that appears, choose your language and currency, leave the other default settings, and then select **Save**.</span></span>

   <span data-ttu-id="51416-143">![Volet Ajouter une base de données](media/add-database-pane.PNG "Volet Ajouter une base de données")</span><span class="sxs-lookup"><span data-stu-id="51416-143">![Add database pane](media/add-database-pane.PNG "Add database pane")</span></span> 

   >[!NOTE]
   > <span data-ttu-id="51416-144">Pour en savoir plus sur les groupes de sécurité, voir [Contrôler l'accès des utilisateurs aux instances](https://docs.microsoft.com/dynamics365/admin/add-instance-subscription#BKMK_man_sec_group).</span><span class="sxs-lookup"><span data-stu-id="51416-144">To learn about security groups, see [Control user access to instances](https://docs.microsoft.com/dynamics365/admin/add-instance-subscription#BKMK_man_sec_group).</span></span>

   <span data-ttu-id="51416-145">La page suivante apparaît pendant la préparation de l'environnement de production.</span><span class="sxs-lookup"><span data-stu-id="51416-145">The following page appears while the production environment is being prepared.</span></span> 
   
    <span data-ttu-id="51416-146">![Message L'environnement est en cours de préparation](media/environment-message.PNG "Message L'environnement est en cours de préparation")</span><span class="sxs-lookup"><span data-stu-id="51416-146">![Environment getting prepared message](media/environment-message.PNG "Environment getting prepared message")</span></span> 

4.  <span data-ttu-id="51416-147">Une fois le nouvel environnement actif (signalé comme **Prêt** dans la colonne **État**), passez à la procédure suivante pour modifier la taille maximale du fichier de téléchargement.</span><span class="sxs-lookup"><span data-stu-id="51416-147">After the new environment is active (listed as **Ready** in the **State** column), go to the next procedure for changing the maximum upload file size.</span></span>

>[!NOTE]
><span data-ttu-id="51416-148">Si vous configurez un environnement de production au lieu d'un environnement d'évaluation, dans les procédures suivantes de cette rubrique, utilisez l'environnement de production au lieu de l'environnement par défaut indiqué dans les captures d'écran.</span><span class="sxs-lookup"><span data-stu-id="51416-148">If you set up a production environment instead of a trial environment, in subsequent procedures throughout this topic, use the production environment instead of the default environment shown in the screenshots.</span></span>

## <span data-ttu-id="51416-149">Modifier la taille maximale de fichier pour le téléchargement<a name="upload"></a></span><span class="sxs-lookup"><span data-stu-id="51416-149">Change maximum upload file size<a name="upload"></a></span></span>

<span data-ttu-id="51416-150">Dans l'application du PC [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous pouvez télécharger vos propres fichiers 3D, ainsi que des vidéos et des images 2D.</span><span class="sxs-lookup"><span data-stu-id="51416-150">In the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] PC application, you can upload your own 3D files in addition to videos and 2D images.</span></span> <span data-ttu-id="51416-151">La taille de plusieurs de ces fichiers sera supérieure à 5 Mo, vous devrez donc modifier la taille maximale des fichiers qui seront chargés.</span><span class="sxs-lookup"><span data-stu-id="51416-151">Many of these files will be larger than 5 MB, so you need to change the maximum file size for uploaded files.</span></span> <span data-ttu-id="51416-152">Pour ce faire, vous devrez remplacer le paramètre de la taille de pièce jointe.</span><span class="sxs-lookup"><span data-stu-id="51416-152">To do this, you'll change the setting for the email attachment size.</span></span>

1. <span data-ttu-id="51416-153">Dans la page **Environnements** du Centre d'administration Power Platform, sélectionnez l'environnement nouvellement créé, puis sélectionnez le bouton **Autres actions d'environnement** (...), puis **Paramètres**.</span><span class="sxs-lookup"><span data-stu-id="51416-153">On the Power Platform Admin center **Environments** page, select the newly created environment, select the **More environment actions** (...) button, and then select **Settings**.</span></span> 

    <span data-ttu-id="51416-154">![Bouton Autres actions d'environnement](media/environment-settings.PNG "Bouton Autres actions d'environnement")</span><span class="sxs-lookup"><span data-stu-id="51416-154">![More environment actions button](media/environment-settings.PNG "More environment actions button")</span></span>
       
2. <span data-ttu-id="51416-155">Sous **E-mail**, sélectionnez **Paramètres d'e-mail**.</span><span class="sxs-lookup"><span data-stu-id="51416-155">Under **Email**, select **Email settings**.</span></span> 

    <span data-ttu-id="51416-156">![Paramètres d'e-mail](media/email-settings.png "Paramètres d'e-mail")</span><span class="sxs-lookup"><span data-stu-id="51416-156">![Email settings](media/email-settings.png "Email settings")</span></span>

3. <span data-ttu-id="51416-157">Faites défiler l'écran vers le bas de la page, puis sous **Documents joints**, définissez le champ **Taille maximale de fichier pour les pièces jointes** sur 131072.</span><span class="sxs-lookup"><span data-stu-id="51416-157">Scroll down to the bottom of the page, and then under **Attachments**, set the **Maximum file size for attachments** field to 131072.</span></span> <span data-ttu-id="51416-158">Sélectionnez **Enregistrer** une fois terminé.</span><span class="sxs-lookup"><span data-stu-id="51416-158">Select **Save** when you're done.</span></span>

    <span data-ttu-id="51416-159">![Taille du fichier](media/edit-file-size.png "Taille du fichier")</span><span class="sxs-lookup"><span data-stu-id="51416-159">![File size](media/edit-file-size.png "File size")</span></span>

4. <span data-ttu-id="51416-160">Revenez sur la page **Environnements** pour préparer l'étape suivante.</span><span class="sxs-lookup"><span data-stu-id="51416-160">Go back to the **Environments** page to prepare for the next step.</span></span> 

## <span data-ttu-id="51416-161">Installer et configurer la solution<a name="configure"></a></span><span class="sxs-lookup"><span data-stu-id="51416-161">Install and configure the solution<a name="configure"></a></span></span>

1. <span data-ttu-id="51416-162">Dans le [Centre d'administration Power Platform](https://admin.powerplatform.microsoft.com/environments), sélectionnez le bouton **Autres actions d'environnement** (...) en regard de l'environnement configuré, puis sélectionnez **Gérer les solutions**.</span><span class="sxs-lookup"><span data-stu-id="51416-162">In the [Power Platform Admin center](https://admin.powerplatform.microsoft.com/environments), select the **More environment actions** (...) button next to the configured environment, and then select **Manage Solutions**.</span></span>

    <span data-ttu-id="51416-163">![Gérer les solutions](media/manage-solutions.PNG "Gérer les solutions")</span><span class="sxs-lookup"><span data-stu-id="51416-163">![Manage solutions](media/manage-solutions.PNG "Manage solutions")</span></span>
     
    >[!NOTE]
    > <span data-ttu-id="51416-164">Vous pouvez également accéder au Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)] à partir du portail Power Apps.</span><span class="sxs-lookup"><span data-stu-id="51416-164">You can also get to the [!include[pn-dyn-365](../includes/pn-dyn-365.md)] Administration Center from the Power Apps portal.</span></span>
    
2. <span data-ttu-id="51416-165">Sélectionnez la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] dans la liste, puis sélectionnez **Installer**.</span><span class="sxs-lookup"><span data-stu-id="51416-165">Select the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] solution in the list, and then select **Install**.</span></span>

    <span data-ttu-id="51416-166">![Bouton Installer](media/solutions-install-button.png "Bouton Installer")</span><span class="sxs-lookup"><span data-stu-id="51416-166">![Install button](media/solutions-install-button.png "Install button")</span></span>
    
3. <span data-ttu-id="51416-167">Dans la boîte de dialogue **Conditions d'utilisation**, examinez les conditions, puis sélectionnez **Installer**.</span><span class="sxs-lookup"><span data-stu-id="51416-167">In the **Terms of Service** dialog box, review the terms, and then select **Install**.</span></span>

    <span data-ttu-id="51416-168">Dans la page Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)], le message suivant apparaît en surbrillance jaune pour indiquer que la solution est sur le point d'être installée : « Veuillez patienter pendant que l'installation démarre. »</span><span class="sxs-lookup"><span data-stu-id="51416-168">On the [!include[pn-dyn-365](../includes/pn-dyn-365.md)] Administration Center page, you'll see the following message highlighted in yellow, showing that the solution is about to be installed: "Please wait while installation starts."</span></span> 
        
     <span data-ttu-id="51416-169">![Message d'installation](media/installing-solution.png "Message d'installation")</span><span class="sxs-lookup"><span data-stu-id="51416-169">![Installing message](media/installing-solution.png "Installing message")</span></span>
     
    <span data-ttu-id="51416-170">Le champ **Statut** à gauche du message installation indique **Installation en attente** lorsque la solution est en cours d'installation.</span><span class="sxs-lookup"><span data-stu-id="51416-170">The **Status** field to the left of the installation message will say **Installation pending** while the solution is being installed.</span></span> <span data-ttu-id="51416-171">Lorsque la solution est installée, le contenu du champ **Statut** est remplacé par **Installé**.</span><span class="sxs-lookup"><span data-stu-id="51416-171">When the solution has finished installing, the **Status** field changes to **Installed**.</span></span>
    
    > [!NOTE]
    > <span data-ttu-id="51416-172">Le processus d'installation peut prendre jusqu'à une heure et est variable en fonction du jour et de la région.</span><span class="sxs-lookup"><span data-stu-id="51416-172">The installation process can take up to one hour and is variable based on the time of day and region.</span></span> <span data-ttu-id="51416-173">Si le statut n'a pas changé au bout d'une heure, essayez d'actualiser la page.</span><span class="sxs-lookup"><span data-stu-id="51416-173">If the status hasn't changed after an hour, try refreshing the page.</span></span> <span data-ttu-id="51416-174">Si l'installation échoue, vous verrez ce message : « L'installation de la solution a échoué.</span><span class="sxs-lookup"><span data-stu-id="51416-174">If the installation fails, you'll see this message: "Solution installation failed.</span></span> <span data-ttu-id="51416-175">Réessayez plus tard.</span><span class="sxs-lookup"><span data-stu-id="51416-175">Please try again later.</span></span> <span data-ttu-id="51416-176">Si le problème persiste, contactez le service clientèle. »</span><span class="sxs-lookup"><span data-stu-id="51416-176">If the problem persists, please contact customer support."</span></span><br><span data-ttu-id="51416-177">![Échec de l'installation](media/failed-install.PNG "Échec de l'installation")</span><span class="sxs-lookup"><span data-stu-id="51416-177">![Failed installation](media/failed-install.PNG "Failed installation")</span></span>

## <span data-ttu-id="51416-178">Paramétrer des rôles d'utilisateur pour la solution<a name="user-roles"></a></span><span class="sxs-lookup"><span data-stu-id="51416-178">Set up user roles for the solution<a name="user-roles"></a></span></span>

> [!NOTE]
> <span data-ttu-id="51416-179">L'affichage d'un utilisateur dans le Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)] peut prendre jusqu'à une heure, une fois les licences ajoutées dans le Centre d'administration [!include[cc-microsoft](../includes/cc-microsoft.md)] 365.</span><span class="sxs-lookup"><span data-stu-id="51416-179">It can take up to one hour for a user to appear in the [!include[pn-dyn-365](../includes/pn-dyn-365.md)] admin center after the licenses are added in the [!include[cc-microsoft](../includes/cc-microsoft.md)] 365 admin center.</span></span>

1. <span data-ttu-id="51416-180">Une fois la solution installée, accédez au [Centre d'administration Power Platform](https://admin.powerplatform.microsoft.com/).</span><span class="sxs-lookup"><span data-stu-id="51416-180">After the solution has finished installing, go to the [Power Platform admin center](https://admin.powerplatform.microsoft.com/).</span></span> 

2. <span data-ttu-id="51416-181">Dans la page **Environnements**, sélectionnez l'environnement nouvellement créé, puis sélectionnez le bouton **Autres actions d'environnement** (...), puis **Paramètres**.</span><span class="sxs-lookup"><span data-stu-id="51416-181">On the **Environments** page, select the environment you created, select the **More environment actions** (...) button, and then select **Settings**.</span></span> 

    <span data-ttu-id="51416-182">![Paramètres d'environnement](media/environment-settings.PNG "Paramètres d'environnement")</span><span class="sxs-lookup"><span data-stu-id="51416-182">![Environment settings](media/environment-settings.PNG "Environment settings")</span></span>

3. <span data-ttu-id="51416-183">Sur la page **Paramètres**, développez **Utilisateurs + Autorisations**, puis sélectionnez **Utilisateurs**.</span><span class="sxs-lookup"><span data-stu-id="51416-183">On the **Settings** page, expand **Users + permissions**, and then select **Users**.</span></span>

    <span data-ttu-id="51416-184">![Utilisateurs et autorisations](media/settings-page.png "Utilisateurs et autorisations")</span><span class="sxs-lookup"><span data-stu-id="51416-184">![Users and permissions](media/settings-page.png "Users and permissions")</span></span>
    
    > [!IMPORTANT]
    > <span data-ttu-id="51416-185">Vous pouvez accéder aux données [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] via la vignette **Guides Hub** de la page précédente, mais nous déconseillons d'effectuer des modifications dans Guides Hub.</span><span class="sxs-lookup"><span data-stu-id="51416-185">You can access [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] data through the **Guides Hub** tile on the preceding page, but we recommend that you not make any changes in the Guides Hub.</span></span> <span data-ttu-id="51416-186">Toute modification apportée peut avoir des conséquences imprévues pour les applications [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="51416-186">Any changes you make can have unintended consequences for the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] apps.</span></span>
 
4. <span data-ttu-id="51416-187">Dans la page **Utilisateurs activés**, sélectionnez l'utilisateur, puis sélectionnez **Gérer les rôles**.</span><span class="sxs-lookup"><span data-stu-id="51416-187">On the **Enabled Users** page, select the user, and then select **Manage Roles**.</span></span> 

    <span data-ttu-id="51416-188">![Gérer les rôles](media/manage-roles.png "Gérer les rôles")</span><span class="sxs-lookup"><span data-stu-id="51416-188">![Manage roles](media/manage-roles.png "Manage roles")</span></span>
 
5. <span data-ttu-id="51416-189">Dans la boîte de dialogue **Gérer les rôles d'utilisateurs**, assurez-vous que la case à cocher **Utilisateur Common Data Service** est cochée.</span><span class="sxs-lookup"><span data-stu-id="51416-189">In the **Manage User Roles** dialog box, make sure the **Common Data Service User** check box is selected.</span></span>
         
    <span data-ttu-id="51416-190">![Case à cocher Utilisateur Common Data Service](media/common-data-service-user.PNG "Case à cocher Utilisateur Common Data Service")</span><span class="sxs-lookup"><span data-stu-id="51416-190">![Common Data Service User check box](media/common-data-service-user.PNG "Common Data Service User check box")</span></span>
    
6. <span data-ttu-id="51416-191">Sélectionnez la case à cocher **D[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] Auteur** ou **[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] Opérateur**, selon les privilèges à accorder à l'utilisateur.</span><span class="sxs-lookup"><span data-stu-id="51416-191">Select the **D[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] Author** or **[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] Operator** check box, depending on the privileges you want the user to have.</span></span>

    <span data-ttu-id="51416-192">![Cases à cocher des rôles Auteur et opérateur](media/select-role.PNG "Cases à cocher des rôles Auteur et opérateur")</span><span class="sxs-lookup"><span data-stu-id="51416-192">![Author and Operator role check boxes](media/select-role.PNG "Author and Operator role check boxes")</span></span>
    
    <span data-ttu-id="51416-193">Le tableau suivant décrit les privilèges accordés à chaque rôle :</span><span class="sxs-lookup"><span data-stu-id="51416-193">The following table describes the privileges provided by each role:</span></span>
    
    |<span data-ttu-id="51416-194">Rôle</span><span class="sxs-lookup"><span data-stu-id="51416-194">Role</span></span>|<span data-ttu-id="51416-195">Description</span><span class="sxs-lookup"><span data-stu-id="51416-195">Description</span></span>|
    |-----------------------|----------------------------------------------------------------------|
    |<span data-ttu-id="51416-196">**Auteur**</span><span class="sxs-lookup"><span data-stu-id="51416-196">**Author**</span></span>|<span data-ttu-id="51416-197">Les utilisateurs disposant de ce rôle peuvent utiliser l'application du PC et l'application HoloLens pour créer, modifier et utiliser des guides.</span><span class="sxs-lookup"><span data-stu-id="51416-197">Users with this role can use the PC app and HoloLens app to create, edit, and operate guides.</span></span> <span data-ttu-id="51416-198">Ils peuvent également renommer et désactiver les guides existants.</span><span class="sxs-lookup"><span data-stu-id="51416-198">They can also rename and deactivate existing guides.</span></span>|
    |<span data-ttu-id="51416-199">**Opérateur**</span><span class="sxs-lookup"><span data-stu-id="51416-199">**Operator**</span></span>|<span data-ttu-id="51416-200">Les utilisateurs avec ce rôle peuvent utiliser l'application HoloLens pour afficher/utiliser un guide.</span><span class="sxs-lookup"><span data-stu-id="51416-200">Users with this role can use the HoloLens app to view/operate a guide.</span></span> <span data-ttu-id="51416-201">Si le rôle **Opérateur** est définir, les opérateurs peuvent également gagner du temps en ignorant la boîte de dialogue **Sélectionner un mode** lorsqu'ils ouvrent un guide.</span><span class="sxs-lookup"><span data-stu-id="51416-201">If the **Operator** role is set, operators can also save time when opening a guide by skipping the **Select Mode** dialog box.</span></span>|
      
7. <span data-ttu-id="51416-202">Si vous souhaitez que ces utilisateurs disposent de privilèges d'administrateur, sélectionnez la case à cocher **Administrateur système**.</span><span class="sxs-lookup"><span data-stu-id="51416-202">If you want this user to have administrator privileges, select the **System Administrator** check box.</span></span> 
     
## <a name="whats-next"></a><span data-ttu-id="51416-203">Étapes suivantes</span><span class="sxs-lookup"><span data-stu-id="51416-203">What's next?</span></span>

<span data-ttu-id="51416-204">Lorsque vous avez terminé cette étape, passez à l'étape 2 du processus de configuration : [Télécharger et installer les applications](setup-step-three.md)</span><span class="sxs-lookup"><span data-stu-id="51416-204">When you're done with this step, go to step 2 in the setup process: [Download and install the apps](setup-step-three.md)</span></span><br>

<span data-ttu-id="51416-205">Si vous rencontrez des problèmes avec l'une des procédures de cette étape :</span><span class="sxs-lookup"><span data-stu-id="51416-205">If you have trouble with any of the procedures in this step, please:</span></span>

- <span data-ttu-id="51416-206">Posez des questions sur notre site communautaire à l'adresse https://community.dynamics.com/365/guides.</span><span class="sxs-lookup"><span data-stu-id="51416-206">Ask on our community site at https://community.dynamics.com/365/guides.</span></span>

- <span data-ttu-id="51416-207">Contactez le service clientèle à l'adresse https://dynamics.microsoft.com/support/.</span><span class="sxs-lookup"><span data-stu-id="51416-207">Contact customer service at https://dynamics.microsoft.com/support/.</span></span>

