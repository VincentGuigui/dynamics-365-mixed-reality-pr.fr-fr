---
author: Mamaylya
description: Tout ce que vous devez savoir sur l'achat de Dynamics 365 Guides, la configuration de la solution, et l'installation des applications.
ms.author: mamaylya
ms.date: 10/29/2019
ms.service: crm-online
ms.topic: article
title: Acheter et déployer Dynamics 365 Guides
ms.reviewer: v-brycho
ms.openlocfilehash: ff4d58749fad8209e6476a259dc6c039a1f6b67a
ms.sourcegitcommit: 5d57bc15af21d18e21b1ec8db0ec046aea997917
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/30/2019
ms.locfileid: "2692120"
---
# <a name="buy-and-deploy-dynamics-365-guides"></a><span data-ttu-id="e5983-103">Acheter et déployer Dynamics 365 Guides</span><span class="sxs-lookup"><span data-stu-id="e5983-103">Buy and deploy Dynamics 365 Guides</span></span>

<span data-ttu-id="e5983-104">Nous sommes ravis de vous présenter [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] pour la disponibilité générale !</span><span class="sxs-lookup"><span data-stu-id="e5983-104">We're thrilled to introduce [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] for general availability!</span></span> <span data-ttu-id="e5983-105">[En savoir plus sur les fonctionnalités de Guides](index.md).</span><span class="sxs-lookup"><span data-stu-id="e5983-105">[Learn about Guides capabilities](index.md).</span></span>

<span data-ttu-id="e5983-106">Pour démarrer avec [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous devez :</span><span class="sxs-lookup"><span data-stu-id="e5983-106">To get started with [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], you need to:</span></span>

1. <span data-ttu-id="e5983-107">Achetez un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] ou inscrivez-vous pour un essai gratuit de 30 jours.</span><span class="sxs-lookup"><span data-stu-id="e5983-107">Buy a [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] subscription or sign up for a free 30-day trial subscription.</span></span>

2. <span data-ttu-id="e5983-108">Créez un environnement Common Data Service (si vous n'en avez pas déjà un) et installez la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] dans l'environnement (instance).</span><span class="sxs-lookup"><span data-stu-id="e5983-108">Create a Common Data Service environment (if you don't already have one) and install the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] solution in the environment (instance).</span></span>

3.  <span data-ttu-id="e5983-109">Télécharger et installer les applications [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] sur un [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC et [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-hololens](../includes/pn-hololens.md)].</span><span class="sxs-lookup"><span data-stu-id="e5983-109">Download and install the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] apps on a [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC and [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-hololens](../includes/pn-hololens.md)].</span></span>

4. <span data-ttu-id="e5983-110">Paramétrer les états d'Analyses de Guides.</span><span class="sxs-lookup"><span data-stu-id="e5983-110">Set up Guides Analytics reports.</span></span>

5. <span data-ttu-id="e5983-111">Ajouter des comptes d'utilisateur supplémentaires (facultatif).</span><span class="sxs-lookup"><span data-stu-id="e5983-111">Add additional user accounts (optional).</span></span>

<span data-ttu-id="e5983-112">Cette rubrique fournit des instructions détaillées pour tout ce qui précède.</span><span class="sxs-lookup"><span data-stu-id="e5983-112">This topic provides step-by-step instructions for all of the above.</span></span>

## <a name="step-1-buy-a-dynamics-365-guides-subscription-or-sign-up-for-a-free-trial-subscription"></a><span data-ttu-id="e5983-113">Étape 1 : Acheter un abonnement Dynamics 365 Guides ou s'inscrire pour un essai gratuit.</span><span class="sxs-lookup"><span data-stu-id="e5983-113">Step 1: Buy a Dynamics 365 Guides subscription or sign up for a free trial subscription</span></span>

<span data-ttu-id="e5983-114">Il existe plusieurs moyens d'obtenir un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] :</span><span class="sxs-lookup"><span data-stu-id="e5983-114">There are multiple ways to get a [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] subscription:</span></span>

- <span data-ttu-id="e5983-115">Si vous avez un compte professionnel Microsoft, vous pouvez accéder directement au Centre d'administration Microsoft 365 et rechercher un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] ici.</span><span class="sxs-lookup"><span data-stu-id="e5983-115">If you have a Microsoft work account, you can go directly to the Microsoft 365 Admin Center and search for a [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] subscription there.</span></span>

- <span data-ttu-id="e5983-116">Accédez à la [page Mise en route](http://aka.ms/GetGuides).</span><span class="sxs-lookup"><span data-stu-id="e5983-116">Go to [the Getting started page](http://aka.ms/GetGuides).</span></span> <span data-ttu-id="e5983-117">Vous pouvez utiliser cette page pour acheter un abonnement ou vous inscrire pour un essai gratuit de 30 jours.</span><span class="sxs-lookup"><span data-stu-id="e5983-117">You can use this page to buy a subscription or to sign up for a free 30-day trial subscription.</span></span> <span data-ttu-id="e5983-118">Si vous vous inscrivez pour un essai gratuit, vous pouvez utiliser les informations d'identification d'un compte Dynamics 365 existant ou en créer de nouvelles.</span><span class="sxs-lookup"><span data-stu-id="e5983-118">If you sign up for a trial, you can use credentials for an existing Dynamics 365 account or you can create new credentials.</span></span> 

    > [!IMPORTANT] 
    > <span data-ttu-id="e5983-119">Si vous ne disposez pas des autorisations d'administrateur associées à votre compte de travail, vous ne pourrez pas effectuer l'étape 2 du processus de paramétrage.</span><span class="sxs-lookup"><span data-stu-id="e5983-119">If you don't have administrator permissions associated with your work account, you won't be able to complete Step 2 of the Setup process.</span></span> <span data-ttu-id="e5983-120">Veuillez coordonner la configuration avec votre administrateur.</span><span class="sxs-lookup"><span data-stu-id="e5983-120">Please coordinate setup with your administrator.</span></span> <span data-ttu-id="e5983-121">S'il n'est pas possible de coordonner la configuration avec votre administrateur, vous pouvez choisir de créer des informations d'identification d'utilisateur pour essayer [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] en suivant les étapes décrites sur la page [Mise en route](http://aka.ms/GetGuides).</span><span class="sxs-lookup"><span data-stu-id="e5983-121">If it's not possible to coordinate setup with your administrator, you can choose to create user credentials to try out [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] by following the steps on [the Getting started page](http://aka.ms/GetGuides).</span></span> <span data-ttu-id="e5983-122">Dans ce cas, le nouvel abonné est créé et le compte du nouvel utilisateur créé bénéficie des autorisations d'administrateur.</span><span class="sxs-lookup"><span data-stu-id="e5983-122">In this case, the new tenant will be created and the newly created user account will have administrator permissions.</span></span> <span data-ttu-id="e5983-123">Notez que vous devez fournir le nom de domaine dans l'écran : *guidesYourCompanyName*.</span><span class="sxs-lookup"><span data-stu-id="e5983-123">Note that you'll need to provide the domain name in the form: *guidesYourCompanyName*.</span></span>
    
<span data-ttu-id="e5983-124">Après vous être inscrit(e) pour un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous devez affecter la licence [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] aux comptes d'utilisateur.</span><span class="sxs-lookup"><span data-stu-id="e5983-124">After you sign up for a [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] subscription, you need to assign the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] license to user accounts.</span></span> <span data-ttu-id="e5983-125">Pour ce faire :</span><span class="sxs-lookup"><span data-stu-id="e5983-125">To do this:</span></span>

1. <span data-ttu-id="e5983-126">Accédez à [Centre d'administration Microsoft 365](https://admin.microsoft.com/AdminPortal/Home) et assurez-vous que le curseur de l'option **Nouveau Centre d'administration** dans le coin supérieur droit de la page est bien défini sur **activé**.</span><span class="sxs-lookup"><span data-stu-id="e5983-126">Go to the [Microsoft 365 Admin Center](https://admin.microsoft.com/AdminPortal/Home) and make sure that the slider for **The new admin center** option in the top right of the page is set to **on**.</span></span>

    <span data-ttu-id="e5983-127">![Curseur Nouveau Centre d'administration](media/new-admin-center-slider.png "Curseur Nouveau Centre d'administration")</span><span class="sxs-lookup"><span data-stu-id="e5983-127">![The new admin center slider](media/new-admin-center-slider.png "The new admin center slider")</span></span>

2.  <span data-ttu-id="e5983-128">Assurez-vous que la licence [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] est affectée à un utilisateur.</span><span class="sxs-lookup"><span data-stu-id="e5983-128">Make sure that the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] license is assigned to a user.</span></span> <span data-ttu-id="e5983-129">Pour cela, dans le volet gauche, sélectionnez **Utilisateurs**, **Utilisateurs actifs**, puis activez la case à cocher en regard de l'utilisateur à ajouter.</span><span class="sxs-lookup"><span data-stu-id="e5983-129">To do this, in the left pane, select **Users**, select **Active users**, and then select the check box for the user you want to add.</span></span> 

    <span data-ttu-id="e5983-130">![Écran Utilisateurs > Utilisateurs actifs](media/users-active-users.png "Écran Utilisateurs > Utilisateurs actifs")</span><span class="sxs-lookup"><span data-stu-id="e5983-130">![Users > Active Users screen](media/users-active-users.png "Users > Active Users screen")</span></span>
    
3.  <span data-ttu-id="e5983-131">Sélectionnez **Gérer les licences de produit**.</span><span class="sxs-lookup"><span data-stu-id="e5983-131">Select **Manage product licenses**.</span></span>

     <span data-ttu-id="e5983-132">![Gérer les licences de produit](media/manage-product-licenses.png "Gérer les licences de produit")</span><span class="sxs-lookup"><span data-stu-id="e5983-132">![Manage product licenses](media/manage-product-licenses.png "Manage product licenses")</span></span>

4.  <span data-ttu-id="e5983-133">Dans l'écran **Licences de produit**, activez la case à cocher pour **[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]**.</span><span class="sxs-lookup"><span data-stu-id="e5983-133">In the **Product licenses** screen, select the check box for **[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]**.</span></span>
  
    <span data-ttu-id="e5983-134">![Ajouter une licence utilisateur](media/guides-license.PNG "Ajouter une licence utilisateur")</span><span class="sxs-lookup"><span data-stu-id="e5983-134">![Add user license](media/guides-license.PNG "Add user license")</span></span> 
 
## <span data-ttu-id="e5983-135">Étape 2 : Créer un environnement Common Data Service et installer la solution Dynamics 365 Guides<a name="cds"></a></span><span class="sxs-lookup"><span data-stu-id="e5983-135">Step 2: Create a Common Data Service environment and install the Dynamics 365 Guides solution<a name="cds"></a></span></span>

<span data-ttu-id="e5983-136">Après avoir acquis un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et avoir affecté les licences, vous devez créer une base de données dans un environnement implicite dans lequel vous pouvez installer la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="e5983-136">After acquiring a [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] subscription and assigning licenses, you’ll need to create a database on a default environment where you can install the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] solution.</span></span> <span data-ttu-id="e5983-137">Si vous disposez déjà d'un environnement Common Data Service (par exemple, une instance de l'abonnement Dynamics 365 de votre entreprise), vous pouvez passer directement à [Modifier la taille maximale de téléchargement](#upload).</span><span class="sxs-lookup"><span data-stu-id="e5983-137">If you already have a Common Data Service environment (for example, an instance in your company's Dynamics 365 tenant), you can skip to [Change maxiumum upload size](#upload).</span></span>
    
1.  <span data-ttu-id="e5983-138">Accédez au [Centre d'administration Power Platform](https://admin.powerplatform.microsoft.com/environments) et connectez-vous avec les informations d'identification de l'utilisateur Administrateur (celles liées aux licences [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] affectées).</span><span class="sxs-lookup"><span data-stu-id="e5983-138">Go to the [Power Platform Admin Center](https://admin.powerplatform.microsoft.com/environments) and sign in with the admin user credentials (where the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] licenses are assigned).</span></span>

2.  <span data-ttu-id="e5983-139">Dans le Centre d'administration Power Platform, sélectionnez **Environnements**.</span><span class="sxs-lookup"><span data-stu-id="e5983-139">In the Power Platform Admin Center, select **Environments**.</span></span>

    <span data-ttu-id="e5983-140">![Environnements Power Platform](media/powerapps-environments.PNG "Environnements Power Platform")</span><span class="sxs-lookup"><span data-stu-id="e5983-140">![Power Platform Environments](media/powerapps-environments.PNG "Power Platform Environments")</span></span>
    
3.  <span data-ttu-id="e5983-141">Sélectionnez le bouton **Autres actions d'environnement** (...) en regard de l'instance par défaut, puis sélectionnez **Gérer l'environnement**.</span><span class="sxs-lookup"><span data-stu-id="e5983-141">Select the **More environment actions** button (...) next to the default instance, and then select **Manage environment**.</span></span>

    <span data-ttu-id="e5983-142">![Gérer l'environnement](media/powerapps-manage-environment.PNG "Gérer l'environnement")</span><span class="sxs-lookup"><span data-stu-id="e5983-142">![Manage Environment](media/powerapps-manage-environment.PNG "Manage Environment")</span></span>
    
4. <span data-ttu-id="e5983-143">Modifiez le nom de l'environnement (par exemple, Guides_*un nom quelconque*), puis sélectionnez **Créer ma base de données**.</span><span class="sxs-lookup"><span data-stu-id="e5983-143">Change the name of the environment (for example, Guides_*anyname*), and then select **Create my database**.</span></span>

    <span data-ttu-id="e5983-144">![Créer une base de données](media/powerapps-create-database.PNG "Créer une base de données")</span><span class="sxs-lookup"><span data-stu-id="e5983-144">![Create database](media/powerapps-create-database.PNG "Create database")</span></span>
    
5. <span data-ttu-id="e5983-145">Dans la boîte de dialogue suivante, sélectionnez la devise et la langue.</span><span class="sxs-lookup"><span data-stu-id="e5983-145">In the next dialog box, choose your currency and language.</span></span>

    <span data-ttu-id="e5983-146">![Paramètres de devise et de langue](media/currency-language-settings.PNG "Paramètres de devise et de langue")</span><span class="sxs-lookup"><span data-stu-id="e5983-146">![Currency and language settings](media/currency-language-settings.PNG "Currency and language settings")</span></span>
  
6.  <span data-ttu-id="e5983-147">Sélectionnez **Créer une base de données.**</span><span class="sxs-lookup"><span data-stu-id="e5983-147">Select **Create database.**</span></span>

<span data-ttu-id="e5983-148">L'écran suivant s'affiche alors que la base de données est créée et mise en service :</span><span class="sxs-lookup"><span data-stu-id="e5983-148">The following screen appears while the database is being created and provisioned:</span></span>
    
   <span data-ttu-id="e5983-149">![Écran Approvisionnement de la base de données](media/provisioning-database.PNG "Écran Approvisionnement de la base de données")</span><span class="sxs-lookup"><span data-stu-id="e5983-149">![Provisioning database screen](media/provisioning-database.PNG "Provisioning database screen")</span></span>
 
   > [!NOTE]
   > <span data-ttu-id="e5983-150">La création de la base de données prend généralement quelques minutes.</span><span class="sxs-lookup"><span data-stu-id="e5983-150">Database creation usually takes several minutes.</span></span> <span data-ttu-id="e5983-151">Si, au bout de 5 minutes, le message « Approvisionnement de la base de données » apparaît toujours, essayez d'actualiser la page.</span><span class="sxs-lookup"><span data-stu-id="e5983-151">If, after 5 minutes, the “Provisioning database” message still appears, try refreshing the page.</span></span>    

7.  <span data-ttu-id="e5983-152">Une fois que la base de données a été créée, revenez à la page **Environnements**.</span><span class="sxs-lookup"><span data-stu-id="e5983-152">After the database has been successfully created, return to the **Environments** page.</span></span>

### <span data-ttu-id="e5983-153">Modifier la taille maximale de fichier pour le téléchargement<a name="upload"></a></span><span class="sxs-lookup"><span data-stu-id="e5983-153">Change maximum upload file size<a name="upload"></a></span></span>

<span data-ttu-id="e5983-154">Dans l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] PC, vous pouvez télécharger vos propres fichiers 3D, ainsi que des vidéos et des images 2D.</span><span class="sxs-lookup"><span data-stu-id="e5983-154">In the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] PC application, you can upload your own 3D files, as well as videos and 2D images.</span></span> <span data-ttu-id="e5983-155">La taille de plusieurs de ces fichiers sera supérieure à 5 Mo, vous devrez donc modifier la taille maximale des fichiers qui seront chargés.</span><span class="sxs-lookup"><span data-stu-id="e5983-155">Many of these files will be larger than 5 MB, so you need to change the maximum file size for files that are uploaded.</span></span> <span data-ttu-id="e5983-156">Pour ce faire, vous devrez remplacer le paramètre de la taille de pièce jointe par 128 Mo (131072 Ko).</span><span class="sxs-lookup"><span data-stu-id="e5983-156">To do this, you'll change the setting for the email attachment size to 128 MB (131072 KB).</span></span>

1. <span data-ttu-id="e5983-157">Dans la page Environnements du Centre d'administration Power Platform, sélectionnez l'environnement nouvellement créé, puis sélectionnez le bouton **Paramètres** dans la barre de titre.</span><span class="sxs-lookup"><span data-stu-id="e5983-157">On the Power Platform Admin Center Environments page, select the newly created environment, and then select the **Settings** button in the title bar.</span></span> 

    <span data-ttu-id="e5983-158">![Sélectionner un environnement et des paramètres](media/admin-center-settings.png "Sélectionner un environnement et des paramètres")</span><span class="sxs-lookup"><span data-stu-id="e5983-158">![Select environment and Settings](media/admin-center-settings.png "Select environment and settings")</span></span>
   
2. <span data-ttu-id="e5983-159">Sous **E-mail**, sélectionnez **Paramètres d'e-mail**.</span><span class="sxs-lookup"><span data-stu-id="e5983-159">Under **Email**, select **Email settings**.</span></span> 

    <span data-ttu-id="e5983-160">![Paramètres d'e-mail](media/email-settings.png "Paramètres d'e-mail")</span><span class="sxs-lookup"><span data-stu-id="e5983-160">![Email settings](media/email-settings.png "Email settings")</span></span>

3. <span data-ttu-id="e5983-161">Faites défiler l'écran vers le bas de la page, puis sous **Documents joints**, définissez le champ **Taille maximale de fichier pour les pièces jointes** sur 131072.</span><span class="sxs-lookup"><span data-stu-id="e5983-161">Scroll down to the bottom of the page, and then under **Attachments**, set the **Maximum file size for attachments** field to 131072.</span></span> <span data-ttu-id="e5983-162">Sélectionnez **Enregistrer** une fois terminé.</span><span class="sxs-lookup"><span data-stu-id="e5983-162">Select **Save** when you’re done.</span></span>

    <span data-ttu-id="e5983-163">![Taille du fichier](media/edit-file-size.png "Taille du fichier")</span><span class="sxs-lookup"><span data-stu-id="e5983-163">![File size](media/edit-file-size.png "File size")</span></span>

4. <span data-ttu-id="e5983-164">Revenez sur la page **Environnements** pour préparer l'étape suivante.</span><span class="sxs-lookup"><span data-stu-id="e5983-164">Go back to the **Environments** page to prepare for the next step.</span></span> 

### <span data-ttu-id="e5983-165">Installer et configurer la solution Dynamics 365 Guides<a name="configure"></a></span><span class="sxs-lookup"><span data-stu-id="e5983-165">Install and configure the Dynamics 365 Guides solution<a name="configure"></a></span></span>

1. <span data-ttu-id="e5983-166">Dans le [Centre d'administration Power Platform](https://admin.powerplatform.microsoft.com/environments), sélectionnez le bouton **Autres actions d'environnement** (les trois points) en regard de l'environnement configuré, puis sélectionnez **Gérer les solutions**.</span><span class="sxs-lookup"><span data-stu-id="e5983-166">In the [Power Platform Admin center](https://admin.powerplatform.microsoft.com/environments), select the **More environment actions** (three dots) button next to the configured environment, and then select **Manage Solutions**.</span></span>

    <span data-ttu-id="e5983-167">![Gérer les solutions](media/manage-solutions.PNG "Gérer les solutions")</span><span class="sxs-lookup"><span data-stu-id="e5983-167">![Manage solutions](media/manage-solutions.PNG "Manage solutions")</span></span>
     
    >[!NOTE]
    > <span data-ttu-id="e5983-168">Vous pouvez également accéder au Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)] à partir du portail PowerApps.</span><span class="sxs-lookup"><span data-stu-id="e5983-168">You can also get to the [!include[pn-dyn-365](../includes/pn-dyn-365.md)] Administration Center from the PowerApps portal.</span></span>
    
2. <span data-ttu-id="e5983-169">Sélectionnez la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] dans la liste, puis sélectionnez **Installer**.</span><span class="sxs-lookup"><span data-stu-id="e5983-169">Select the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] solution in the list, and then select **Install**.</span></span>

    <span data-ttu-id="e5983-170">![Bouton Installer](media/solutions-install-button.png "Bouton Installer")</span><span class="sxs-lookup"><span data-stu-id="e5983-170">![Install button](media/solutions-install-button.png "Install button")</span></span>
    
3. <span data-ttu-id="e5983-171">Dans la boîte de dialogue **Conditions d'utilisation**, examinez les conditions, puis sélectionnez **Installer** lorsque vous êtes prêt.</span><span class="sxs-lookup"><span data-stu-id="e5983-171">In the **Terms of Service** dialog box, review the terms, and then select **Install** when you're ready.</span></span>

    <span data-ttu-id="e5983-172">Dans l'écran Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)], le message suivant apparaît en surbrillance jaune pour indiquer que la solution est sur le point d'être installée :</span><span class="sxs-lookup"><span data-stu-id="e5983-172">In the [!include[pn-dyn-365](../includes/pn-dyn-365.md)] Administration Center screen, you'll see the following message highlighted in yellow showing that the solution is about to be installed:</span></span>
    
     <span data-ttu-id="e5983-173">![Message d'installation](media/installing-solution.png "Message d'installation")</span><span class="sxs-lookup"><span data-stu-id="e5983-173">![Installing message](media/installing-solution.png "Installing message")</span></span>
     
    <span data-ttu-id="e5983-174">Le champ **Statut** à gauche du message jaune indique **Installation en attente** lorsque la solution est en cours d'installation.</span><span class="sxs-lookup"><span data-stu-id="e5983-174">The **Status** field to the left of the yellow message will say **Installation pending** while the solution is being installed.</span></span> <span data-ttu-id="e5983-175">Lorsque la solution est installée, le contenu du champ **Statut** est remplacé par **Installé**.</span><span class="sxs-lookup"><span data-stu-id="e5983-175">When the solution has finished installing, the **Status** field changes to **Installed**.</span></span>
    
    > [!NOTE]
    > <span data-ttu-id="e5983-176">Le processus d'installation peut prendre jusqu'à une heure et est variable en fonction du jour et de la région.</span><span class="sxs-lookup"><span data-stu-id="e5983-176">The installation process can take up to one hour and is variable based on the time of day and region.</span></span> <span data-ttu-id="e5983-177">Si le statut n'a pas changé au bout d'une heure, essayez d'actualiser l'écran.</span><span class="sxs-lookup"><span data-stu-id="e5983-177">If the status hasn't changed after an hour, try refreshing your screen.</span></span> <span data-ttu-id="e5983-178">Si l'installation échoue, vous verrez ce message :</span><span class="sxs-lookup"><span data-stu-id="e5983-178">If the installation fails, you'll see this message:</span></span><br><span data-ttu-id="e5983-179">![Échec de l'installation](media/failed-install.PNG "Échec de l'installation")</span><span class="sxs-lookup"><span data-stu-id="e5983-179">![Failed installation](media/failed-install.PNG "Failed installation")</span></span>

### <span data-ttu-id="e5983-180">Paramétrer des rôles d'utilisateur pour la solution<a name="user-roles"></a></span><span class="sxs-lookup"><span data-stu-id="e5983-180">Set up user roles for the solution<a name="user-roles"></a></span></span>

> [!NOTE]
> <span data-ttu-id="e5983-181">L'affichage d'un utilisateur dans le Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)] peut prendre jusqu'à une heure, une fois les licences ajoutées dans le Centre d'administration [!include[cc-microsoft](../includes/cc-microsoft.md)] 365.</span><span class="sxs-lookup"><span data-stu-id="e5983-181">It can take up to one hour for a user to appear in the [!include[pn-dyn-365](../includes/pn-dyn-365.md)] admin center after the licenses are added in the [!include[cc-microsoft](../includes/cc-microsoft.md)] 365 admin center.</span></span> 

1. <span data-ttu-id="e5983-182">Une fois la solution installée, accédez au [Centre d'administration Power Platform](https://admin.powerplatform.microsoft.com/).</span><span class="sxs-lookup"><span data-stu-id="e5983-182">After the solution has finished installing, go to the [Power Platform admin center](https://admin.powerplatform.microsoft.com/).</span></span> 

2. <span data-ttu-id="e5983-183">Dans la page **Environnements**, sélectionnez l'environnement nouvellement créé, puis sélectionnez le bouton **Paramètres** dans la barre de titre.</span><span class="sxs-lookup"><span data-stu-id="e5983-183">On the **Environments** page, select the environment you created, and then select the **Settings** button in the title bar.</span></span> 

3. <span data-ttu-id="e5983-184">Dans la page **Paramètres**, sous **Utilisateurs + Autorisations**, sélectionnez **Utilisateurs**.</span><span class="sxs-lookup"><span data-stu-id="e5983-184">In the **Settings** page, under **Users + permissions**, select **Users**.</span></span>

    <span data-ttu-id="e5983-185">![Utilisateurs et autorisations](media/settings-page.png "Utilisateurs et autorisations")</span><span class="sxs-lookup"><span data-stu-id="e5983-185">![Users and permissions](media/settings-page.png "Users and permissions")</span></span>
    
    > [!IMPORTANT]
    > <span data-ttu-id="e5983-186">Vous pouvez accéder aux données [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] via la vignette Guides Hub de l'écran précédent, mais nous déconseillons d'effectuer des modifications dans Guides Hub.</span><span class="sxs-lookup"><span data-stu-id="e5983-186">You can access [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] data through the Guides Hub tile in the preceding screen, but we recommend that you not make any changes in the Guides Hub.</span></span> <span data-ttu-id="e5983-187">Toute modification apportée peut avoir des conséquences imprévues pour les applications [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="e5983-187">Any changes you make can have unintended consequences for the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] apps.</span></span>
 
4.  <span data-ttu-id="e5983-188">Dans la page **Utilisateurs activés**, sélectionnez l'utilisateur, puis sélectionnez **Gérer les rôles**.</span><span class="sxs-lookup"><span data-stu-id="e5983-188">On the **Enabled Users** page, select the user, and then select **Manage Roles**.</span></span> 

    <span data-ttu-id="e5983-189">![Gérer les rôles](media/manage-roles.png "Gérer les rôles")</span><span class="sxs-lookup"><span data-stu-id="e5983-189">![Manage roles](media/manage-roles.png "Manage roles")</span></span>
 
5.  <span data-ttu-id="e5983-190">Dans la boîte de dialogue **Gérer les rôles d'utilisateurs**, sélectionnez les rôles suivants :</span><span class="sxs-lookup"><span data-stu-id="e5983-190">In the **Manage User Roles** dialog box, select the following roles:</span></span> 

    - <span data-ttu-id="e5983-191">Utilisateur Common Data Service</span><span class="sxs-lookup"><span data-stu-id="e5983-191">Common Data Service User</span></span>
    
    - <span data-ttu-id="e5983-192">Auteur [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]</span><span class="sxs-lookup"><span data-stu-id="e5983-192">[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] Author</span></span>
    
    - <span data-ttu-id="e5983-193">Administrateur système</span><span class="sxs-lookup"><span data-stu-id="e5983-193">System Administrator</span></span> 
       
      <span data-ttu-id="e5983-194">![Boîte de dialogue Gérer les rôles renseignée](media/manage-roles-dialog-box.PNG "Boîte de dialogue Gérer les rôles renseignée")</span><span class="sxs-lookup"><span data-stu-id="e5983-194">![Manage Roles dialog box filled in](media/manage-roles-dialog-box.PNG "Manage Roles dialog box filled in")</span></span>
      
      > [!NOTE]
      > <span data-ttu-id="e5983-195">Sélectionnez le rôle Administrateur système s'il s'agit de l'utilisateur principal/de l'administrateur. Sinon, ne sélectionnez pas ce rôle.</span><span class="sxs-lookup"><span data-stu-id="e5983-195">Select the System Administrator role if this is the main user/admin. Otherwise, do not select that role.</span></span> 
     
## <a name="step-3-download-and-install-the-apps"></a><span data-ttu-id="e5983-196">Étape 3 : Télécharger et installer les applications.</span><span class="sxs-lookup"><span data-stu-id="e5983-196">Step 3: Download and install the apps</span></span>

<span data-ttu-id="e5983-197">Il y a deux applications [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] :</span><span class="sxs-lookup"><span data-stu-id="e5983-197">There are two [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] applications:</span></span> 

- <span data-ttu-id="e5983-198">Application de création de l'ordinateur de bureau</span><span class="sxs-lookup"><span data-stu-id="e5983-198">Desktop authoring application</span></span>

- <span data-ttu-id="e5983-199">Application [!include[pn-hololens](../includes/pn-hololens.md)], avec un mode Créer et un mode Opérateur</span><span class="sxs-lookup"><span data-stu-id="e5983-199">[!include[pn-hololens](../includes/pn-hololens.md)] application, which has an Author mode and an Operator mode</span></span>

<span data-ttu-id="e5983-200">Vous pouvez installer les deux applications à partir de [!include[cc-microsoft](../includes/cc-microsoft.md)] Store tel que décrit dans la section suivante.</span><span class="sxs-lookup"><span data-stu-id="e5983-200">You can install both apps from [!include[cc-microsoft](../includes/cc-microsoft.md)] Store as described in the next section.</span></span>

> [!NOTE]
> <span data-ttu-id="e5983-201">Si vous ne pouvez pas accéder à [!include[cc-microsoft](../includes/cc-microsoft.md)] Store en raison de politiques d'entreprise, contactez votre administrateur pour qu'il distribue l'application.</span><span class="sxs-lookup"><span data-stu-id="e5983-201">If you can’t access [!include[cc-microsoft](../includes/cc-microsoft.md)] Store due to company policies, please contact your administrator to distribute the app.</span></span>

<span data-ttu-id="e5983-202">Si vous utilisez [!include[cc-microsoft](../includes/cc-microsoft.md)] Store pour Entreprises pour distribuer vos applications, les utilisateurs peuvent les installer à partir du magasin privé de votre organisation ou d'un lien que vous leur envoyez par e-mail.</span><span class="sxs-lookup"><span data-stu-id="e5983-202">If you use [!include[cc-microsoft](../includes/cc-microsoft.md)] Store for Business to distribute your apps, you can have users install the apps from your organization’s private store or from an email link that you send.</span></span> <span data-ttu-id="e5983-203">Les instructions sont fournies plus loin dans cette rubrique.</span><span class="sxs-lookup"><span data-stu-id="e5983-203">Instructions are provided later in this topic.</span></span>

### <a name="install-the-apps-from-microsoft-store"></a><span data-ttu-id="e5983-204">Installer les applications à partir de Microsoft Store</span><span class="sxs-lookup"><span data-stu-id="e5983-204">Install the apps from Microsoft Store</span></span>

#### <a name="install-the-pc-authoring-app"></a><span data-ttu-id="e5983-205">Installer l'application de création sur PC</span><span class="sxs-lookup"><span data-stu-id="e5983-205">Install the PC authoring app</span></span> 
1.  <span data-ttu-id="e5983-206">Assurez-vous que votre [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC exécute la dernière version de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] (doit correspondre à la version 10.0.17134, mise à jour d’avril 2018 ou ultérieure).</span><span class="sxs-lookup"><span data-stu-id="e5983-206">Check to make sure your [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC is running the latest [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] build (must be build 10.0.17134, April 2018 update, or later).</span></span>

2.  <span data-ttu-id="e5983-207">Sur votre PC, allez dans **Démarrer** ![Bouton Démarrer](media/windows-button.png "Bouton Démarrer") > **[!include[cc-microsoft](../includes/cc-microsoft.md)] Store** ![bouton Store](media/store-button.png "Bouton Store"), puis recherchez [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="e5983-207">On your PC, go to **Start** ![Start button](media/windows-button.png "Start button") > **[!include[cc-microsoft](../includes/cc-microsoft.md)] Store** ![Store button](media/store-button.png "Store button"), and then search for “[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].”</span></span>

3.  <span data-ttu-id="e5983-208">Dans [!include[cc-microsoft](../includes/cc-microsoft.md)] Store, sélectionnez **Obtenir** en regard de l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] pour la télécharger et l'installer.</span><span class="sxs-lookup"><span data-stu-id="e5983-208">In [!include[cc-microsoft](../includes/cc-microsoft.md)] Store, select **Get** for the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] app to download, and install the application.</span></span>

    > [!NOTE]
    > <span data-ttu-id="e5983-209">Pour obtenir des instructions sur l'ouverture et la connexion à l'application, voir [Création de guide](authoring-overview.md).</span><span class="sxs-lookup"><span data-stu-id="e5983-209">For instructions on opening and signing in to the app, see the [authoring guide](authoring-overview.md).</span></span>

#### <a name="install-the-hololens-app"></a><span data-ttu-id="e5983-210">Installer l'application HoloLens</span><span class="sxs-lookup"><span data-stu-id="e5983-210">Install the HoloLens app</span></span>

1.  <span data-ttu-id="e5983-211">Assurez-vous qu'[!include[pn-hololens](../includes/pn-hololens.md)] exécute la version 10.0.17134 ou ultérieure.</span><span class="sxs-lookup"><span data-stu-id="e5983-211">Make sure [!include[pn-hololens](../includes/pn-hololens.md)] is running build 10.0.17134 or later.</span></span> <span data-ttu-id="e5983-212">Nous vous recommandons de mettre à jour [!include[pn-hololens](../includes/pn-hololens.md)] vers des versions plus récentes quand elles sont disponibles.</span><span class="sxs-lookup"><span data-stu-id="e5983-212">We recommend updating [!include[pn-hololens](../includes/pn-hololens.md)] to newer versions when available.</span></span> <span data-ttu-id="e5983-213">Voir [Gérer les mises à jour vers HoloLens](https://docs.microsoft.com/HoloLens/hololens-updates) pour obtenir des instructions sur l'utilisation de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Update pour Entreprise.</span><span class="sxs-lookup"><span data-stu-id="e5983-213">See [Manage updates to HoloLens](https://docs.microsoft.com/HoloLens/hololens-updates) for instructions on using [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Update for Business.</span></span>

2.  <span data-ttu-id="e5983-214">Dans [!include[pn-hololens](../includes/pn-hololens.md)], utilisez l'écartement des doigts paume vers le haut pour ouvrir le menu **Accueil**, puis ouvrez l'application [!include[cc-microsoft](../includes/cc-microsoft.md)] Store et recherchez [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="e5983-214">On your [!include[pn-hololens](../includes/pn-hololens.md)], use the bloom gesture to open the **Home** menu, and then open the [!include[cc-microsoft](../includes/cc-microsoft.md)] Store app and search for “[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]”.</span></span>

3.  <span data-ttu-id="e5983-215">Sélectionnez **Installer** pour télécharger et installer l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="e5983-215">Select **Install** to download and install the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] application.</span></span>

> [!NOTE] 
> <span data-ttu-id="e5983-216">Pour obtenir des instructions sur l'ouverture et la connexion à l'application, si vous êtes un auteur, consultez la [rubrique de création HoloLens](hololens-authoring.md).</span><span class="sxs-lookup"><span data-stu-id="e5983-216">For instructions on opening and signing in to the app, if you're an author, see the [HoloLens authoring topic](hololens-authoring.md).</span></span> <span data-ttu-id="e5983-217">Les opérateurs peuvent utiliser le [manuel de l'opérateur Dynamics 365 Guides](operator-guide.md).</span><span class="sxs-lookup"><span data-stu-id="e5983-217">Operators can use the [Dynamics 365 Guides Operator's manual](operator-guide.md).</span></span>

### <a name="distribute-the-apps-through-microsoft-store-for-business"></a><span data-ttu-id="e5983-218">Répartir les applications par le biais de Microsoft Store pour Entreprises</span><span class="sxs-lookup"><span data-stu-id="e5983-218">Distribute the apps through Microsoft Store for Business</span></span>

1.  <span data-ttu-id="e5983-219">Allez à [Microsoft Store pour Entreprises](https://businessstore.microsoft.com/store).</span><span class="sxs-lookup"><span data-stu-id="e5983-219">Go to [Microsoft Store for Business](https://businessstore.microsoft.com/store).</span></span>

2.  <span data-ttu-id="e5983-220">[Faites l'acquisition de la ou des applications](https://docs.microsoft.com/microsoft-store/acquire-apps-microsoft-store-for-business).</span><span class="sxs-lookup"><span data-stu-id="e5983-220">[Acquire the app(s)](https://docs.microsoft.com/microsoft-store/acquire-apps-microsoft-store-for-business).</span></span>

3.  <span data-ttu-id="e5983-221">Choisissez l'une des méthodes de distribution suivantes :</span><span class="sxs-lookup"><span data-stu-id="e5983-221">Choose one of the following distribution methods:</span></span>

    - [<span data-ttu-id="e5983-222">Magasin privé</span><span class="sxs-lookup"><span data-stu-id="e5983-222">Private store</span></span>](https://docs.microsoft.com/microsoft-store/distribute-apps-from-your-private-store)
    
    - [<span data-ttu-id="e5983-223">Lien de courrier électronique</span><span class="sxs-lookup"><span data-stu-id="e5983-223">Email link</span></span>](https://docs.microsoft.com/microsoft-store/assign-apps-to-employees)
    
    - [<span data-ttu-id="e5983-224">Gestion des périphériques mobiles</span><span class="sxs-lookup"><span data-stu-id="e5983-224">Mobile device management</span></span>](https://docs.microsoft.com/microsoft-store/configure-mdm-provider-microsoft-store-for-business)

<span data-ttu-id="e5983-225">Pour plus d'informations sur l'ouverture et la connexion à l'application du PC après l'avoir installée, voir [Création de guide](authoring-overview.md).</span><span class="sxs-lookup"><span data-stu-id="e5983-225">For information on opening and signing in to the PC application after installing it, see the [authoring guide](authoring-overview.md).</span></span>

<span data-ttu-id="e5983-226">Pour plus d'informations sur l'ouverture et la connexion à l'application [!include[pn-hololens](../includes/pn-hololens.md)], accédez à l'une des options suivantes, selon que vous êtes auteur ou opérateur :</span><span class="sxs-lookup"><span data-stu-id="e5983-226">For information on opening and signing in to the [!include[pn-hololens](../includes/pn-hololens.md)] application, go to one of the following, depending on whether you're an author or an operator:</span></span>

   - [<span data-ttu-id="e5983-227">Création HoloLens</span><span class="sxs-lookup"><span data-stu-id="e5983-227">HoloLens authoring</span></span>](hololens-authoring.md)
   
   - [<span data-ttu-id="e5983-228">Manuel de l'opérateur</span><span class="sxs-lookup"><span data-stu-id="e5983-228">Operator's manual</span></span>](operator-guide.md)

## <a name="step-4-set-up-guides-analytics-reports"></a><span data-ttu-id="e5983-229">Étape 4 : Paramétrer les états d'Analyses de Guides</span><span class="sxs-lookup"><span data-stu-id="e5983-229">Step 4: Set up Guides Analytics reports</span></span> 

[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] <span data-ttu-id="e5983-230">inclut des états [!include[pn-power-bi](../includes/pn-power-bi.md)] (appelés Analyses de Guides) qui permettent d'analyser les processus des guides [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="e5983-230">includes [!include[pn-power-bi](../includes/pn-power-bi.md)] reports (called Guides Analytics) that you can use to analyze [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] processes.</span></span> <span data-ttu-id="e5983-231">Suivez les instructions pour savoir comment [ouvrir Analyses de Guides](https://docs.microsoft.com/dynamics365/mixed-reality/guides/analytics-guide#open-guides-analytics) en utilisant l'[application Power BI Desktop](https://powerbi.microsoft.com/get-started/) disponible gratuitement.</span><span class="sxs-lookup"><span data-stu-id="e5983-231">Follow the instructions for how to [Open Guides Analytics](https://docs.microsoft.com/dynamics365/mixed-reality/guides/analytics-guide#open-guides-analytics) using the freely available [Power BI Desktop application](https://powerbi.microsoft.com/get-started/).</span></span>

<span data-ttu-id="e5983-232">Si vous disposez d'une licence [!include[pn-power-bi](../includes/pn-power-bi.md)] Pro, vous pouvez partager vos états d'Analyses de Guides [!include[pn-power-bi](../includes/pn-power-bi.md)] au sein de votre organisation en les publiant dans le service [!include[pn-power-bi](../includes/pn-power-bi.md)].</span><span class="sxs-lookup"><span data-stu-id="e5983-232">If you have a [!include[pn-power-bi](../includes/pn-power-bi.md)] Pro license, you can share your Guides Analytics [!include[pn-power-bi](../includes/pn-power-bi.md)] reports within your organization by publishing them to the [!include[pn-power-bi](../includes/pn-power-bi.md)] Service.</span></span> <span data-ttu-id="e5983-233">Cela permet à toute personne de votre organisation ayant une licence Pro [!include[pn-power-bi](../includes/pn-power-bi.md)] d'accéder à l'état via l'interface Web du service [!include[pn-power-bi](../includes/pn-power-bi.md)] accessible sur [https://powerbi.microsoft.com](https://powerbi.microsoft.com).</span><span class="sxs-lookup"><span data-stu-id="e5983-233">This allows anyone in your organization with a [!include[pn-power-bi](../includes/pn-power-bi.md)] Pro license to access the report through the [!include[pn-power-bi](../includes/pn-power-bi.md)] Service web interface accessible at [https://powerbi.microsoft.com](https://powerbi.microsoft.com).</span></span> <span data-ttu-id="e5983-234">Pour en savoir plus sur la collaboration sur le cloud de [!include[pn-power-bi](../includes/pn-power-bi.md)] et le partage, ainsi que l'inscription à une version d'essai gratuit de [!include[pn-power-bi](../includes/pn-power-bi.md)] Pro, consultez [Getting Started with Power BI Desktop](https://powerbi.microsoft.com/get-started/) et [Ways to share your work in Power BI](https://docs.microsoft.com/power-bi/service-how-to-collaborate-distribute-dashboards-reports).</span><span class="sxs-lookup"><span data-stu-id="e5983-234">To learn about [!include[pn-power-bi](../includes/pn-power-bi.md)] cloud collaboration and sharing and to sign up for a free trial of [!include[pn-power-bi](../includes/pn-power-bi.md)] Pro, visit [Getting Started with Power BI Desktop](https://powerbi.microsoft.com/get-started/) and [Ways to share your work in Power BI](https://docs.microsoft.com/power-bi/service-how-to-collaborate-distribute-dashboards-reports).</span></span>

## <span data-ttu-id="e5983-235">Étape 5 : Ajouter des comptes d'utilisateur supplémentaires (facultatif)<a name="user-accounts"></a></span><span class="sxs-lookup"><span data-stu-id="e5983-235">Step 5: Add additional user accounts (optional)<a name="user-accounts"></a></span></span>

<span data-ttu-id="e5983-236">Pour ajouter des utilisateurs supplémentaires, vous devez leur affecter la licence [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et configurer les rôles auxquels ils auront accès dans le Centre d'administration Dynamics 365.</span><span class="sxs-lookup"><span data-stu-id="e5983-236">If you want to add additional users, you need to assign the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] license to them and configure the roles they will have access to in the Dynamics 365 admin center.</span></span>

### <a name="add-a-user-account"></a><span data-ttu-id="e5983-237">Ajouter un compte d'utilisateur</span><span class="sxs-lookup"><span data-stu-id="e5983-237">Add a user account</span></span>

1. <span data-ttu-id="e5983-238">Accédez à [Centre d'administration Microsoft 365](https://admin.microsoft.com/AdminPortal/Home).</span><span class="sxs-lookup"><span data-stu-id="e5983-238">Go to the [Microsoft 365 admin center](https://admin.microsoft.com/AdminPortal/Home).</span></span>

2. <span data-ttu-id="e5983-239">Dans le volet gauche de navigation, sélectionnez **Utilisateurs**, puis **Utilisateurs actifs**.</span><span class="sxs-lookup"><span data-stu-id="e5983-239">In the left navigation, select **Users**, and then select **Active users**.</span></span> 

3. <span data-ttu-id="e5983-240">Sélectionnez **Ajouter un utilisateur**.</span><span class="sxs-lookup"><span data-stu-id="e5983-240">Select **Add a user**.</span></span>

   <span data-ttu-id="e5983-241">![Ajouter un utilisateur](media/add-additional-user.png "Ajouter un utilisateur")</span><span class="sxs-lookup"><span data-stu-id="e5983-241">![Add user](media/add-additional-user.png "Add user")</span></span> 

4. <span data-ttu-id="e5983-242">Renseignez les informations pour le nouvel utilisateur.</span><span class="sxs-lookup"><span data-stu-id="e5983-242">Fill in the information for the new user.</span></span> <span data-ttu-id="e5983-243">Sélectionnez **Suivant** une fois terminé.</span><span class="sxs-lookup"><span data-stu-id="e5983-243">Select **Next** when you're done.</span></span>

   > [!NOTE]
   > <span data-ttu-id="e5983-244">Par défaut, un mot de passe sera généré automatiquement pour l'utilisateur.</span><span class="sxs-lookup"><span data-stu-id="e5983-244">By default, an auto-generated password will be generated for the user.</span></span> <span data-ttu-id="e5983-245">L'utilisateur doit modifier le mot de passe la première fois qu'il se connecte à ce compte.</span><span class="sxs-lookup"><span data-stu-id="e5983-245">The user is required to change the password the first time they sign in with this account.</span></span> <span data-ttu-id="e5983-246">Si vous souhaitez remplacer le mot de passe à ce moment-là par un mot de passe permanent au lieu d'utiliser le mot de passe généré automatiquement, remplacez **Mot de passe généré automatiquement** par **Laissez-moi créer le mot de passe**, puis désactivez la case à cocher **Demander à cet utilisateur de modifier son mot de passe lorsqu'il se connecte pour la première fois**.</span><span class="sxs-lookup"><span data-stu-id="e5983-246">If you want to change the password at this time to a permanent password instead of using the auto-generated password, change **Auto-generate password** to **Let me create the password**, and then clear the **Require this user to change their password when they first sign in** check box.</span></span> 
 
5. <span data-ttu-id="e5983-247">Sélectionnez l'emplacement de cet utilisateur, puis sous **Licences**, activez la case à cocher en regard de **Dynamics 365 Guides**.</span><span class="sxs-lookup"><span data-stu-id="e5983-247">Select the location for this user, and then under **Licenses**, select the check box next to **Dynamics 365 Guides**.</span></span> 

    <span data-ttu-id="e5983-248">![Attribuer une licence](media/assign-license-user.png "Attribuer une licence")</span><span class="sxs-lookup"><span data-stu-id="e5983-248">![Assign license](media/assign-license-user.png "Assign license")</span></span> 

     <span data-ttu-id="e5983-249">Sélectionnez **Suivant** une fois terminé.</span><span class="sxs-lookup"><span data-stu-id="e5983-249">Select **Next** when you're done.</span></span>
   
7. <span data-ttu-id="e5983-250">Dans l'écran **Paramètres facultatifs**, laissez la zone **Utilisateur (aucun accès Administrateur)** sélectionnée à moins que ce nouvel utilisateur soit un administrateur.</span><span class="sxs-lookup"><span data-stu-id="e5983-250">In the **Optional settings** screen, leave the **User (no administrator access)** box selected unless this new user will be an administrator.</span></span> <span data-ttu-id="e5983-251">Dans ce cas, activez la case à cocher **Administrateur global**.</span><span class="sxs-lookup"><span data-stu-id="e5983-251">In that case, select the **Global administrator** check box.</span></span> <span data-ttu-id="e5983-252">Pour renseigner les informations de profil du nouvel utilisateur, développez **Informations de profil**.</span><span class="sxs-lookup"><span data-stu-id="e5983-252">To fill out the new user's profile info, expand the **Profile info**.</span></span> <span data-ttu-id="e5983-253">Sélectionnez **Suivant** une fois terminé.</span><span class="sxs-lookup"><span data-stu-id="e5983-253">Select **Next** when you're done.</span></span>

   <span data-ttu-id="e5983-254">![Paramètres utilisateur facultatifs](media/user-optional-settings.png "Paramètres utilisateur facultatifs")</span><span class="sxs-lookup"><span data-stu-id="e5983-254">![Optional user settings](media/user-optional-settings.png "Optional user settings")</span></span> 
   
8. <span data-ttu-id="e5983-255">Vérifiez les informations de cette dernière page.</span><span class="sxs-lookup"><span data-stu-id="e5983-255">Review the info in this last page.</span></span> <span data-ttu-id="e5983-256">Pour apporter des modifications, sélectionnez le bouton **Modifier** en dessous de chaque section.</span><span class="sxs-lookup"><span data-stu-id="e5983-256">To make changes, select the **Edit** button below each section.</span></span> <span data-ttu-id="e5983-257">Sélectionnez **Terminé l'ajout** une fois terminé.</span><span class="sxs-lookup"><span data-stu-id="e5983-257">When you're done, select **Finish Adding**.</span></span>

9. <span data-ttu-id="e5983-258">Si vous avez sélectionné **Générez le mot de passe** à l'étape 4, notez le mot de passe.</span><span class="sxs-lookup"><span data-stu-id="e5983-258">If you selected **Generate password** in step 4, make note of the password.</span></span> <span data-ttu-id="e5983-259">L'utilisateur a besoin de ce mot de passe pour se connecter.</span><span class="sxs-lookup"><span data-stu-id="e5983-259">The user will need this password to sign in.</span></span>

   <span data-ttu-id="e5983-260">![Vérifier les paramètres utilisateur](media/review-user-settings.png "Vérifier les paramètres utilisateur")</span><span class="sxs-lookup"><span data-stu-id="e5983-260">![Review user settings](media/review-user-settings.png "Review user settings")</span></span> 
   
10. <span data-ttu-id="e5983-261">Sélectionnez **Fermer**.</span><span class="sxs-lookup"><span data-stu-id="e5983-261">Select **Close**.</span></span>

11. <span data-ttu-id="e5983-262">[Paramétrez des rôles d'utilisateur pour la solution](#user-roles) comme décrit précédemment dans cette rubrique.</span><span class="sxs-lookup"><span data-stu-id="e5983-262">[Set up user roles for the solution](#user-roles) as described earlier in this topic.</span></span>

### <a name="see-also"></a><span data-ttu-id="e5983-263">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="e5983-263">See also</span></span>

[<span data-ttu-id="e5983-264">Mise en route d'Dynamics 365 Guides</span><span class="sxs-lookup"><span data-stu-id="e5983-264">Get started with Dynamics 365 Guides</span></span>](get-started.md)<br>
[<span data-ttu-id="e5983-265">Créer un guide</span><span class="sxs-lookup"><span data-stu-id="e5983-265">Author a guide</span></span>](authoring-overview.md)<br>
[<span data-ttu-id="e5983-266">Manuel de l'opérateur</span><span class="sxs-lookup"><span data-stu-id="e5983-266">Operator's manual</span></span>](operator-guide.md)<br>
[<span data-ttu-id="e5983-267">Analyser les guides pour rendre les processus plus efficaces</span><span class="sxs-lookup"><span data-stu-id="e5983-267">Analyze your guides to improve process efficiencies</span></span>](analytics-guide.md)<br>
[<span data-ttu-id="e5983-268">FAQ</span><span class="sxs-lookup"><span data-stu-id="e5983-268">FAQ</span></span>](faq.md)






