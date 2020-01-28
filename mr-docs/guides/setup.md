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
# <a name="buy-and-deploy-dynamics-365-guides"></a><span data-ttu-id="b0038-103">Acheter et déployer Dynamics 365 Guides</span><span class="sxs-lookup"><span data-stu-id="b0038-103">Buy and deploy Dynamics 365 Guides</span></span>

<span data-ttu-id="b0038-104">Nous sommes ravis de vous présenter [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] pour la disponibilité générale !</span><span class="sxs-lookup"><span data-stu-id="b0038-104">We're thrilled to introduce [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] for general availability!</span></span> <span data-ttu-id="b0038-105">[En savoir plus sur les fonctionnalités de Guides](index.md).</span><span class="sxs-lookup"><span data-stu-id="b0038-105">[Learn about Guides capabilities](index.md).</span></span>

<span data-ttu-id="b0038-106">Pour démarrer avec [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous devez :</span><span class="sxs-lookup"><span data-stu-id="b0038-106">To get started with [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], you need to:</span></span>

1. <span data-ttu-id="b0038-107">Acheter un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] ou vous inscrire pour un essai gratuit de 30 jours.</span><span class="sxs-lookup"><span data-stu-id="b0038-107">Buy a [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] subscription or sign up for a free, 30-day trial subscription.</span></span>

2. <span data-ttu-id="b0038-108">Créer un environnement Common Data Service (si vous n'en avez pas déjà un) et installer la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] dans l'environnement (instance).</span><span class="sxs-lookup"><span data-stu-id="b0038-108">Create a Common Data Service environment (if you don't already have one) and install the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] solution in the environment (instance).</span></span>

3.  <span data-ttu-id="b0038-109">Télécharger et installer les applications [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] sur un [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC et [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-hololens](../includes/pn-hololens.md)].</span><span class="sxs-lookup"><span data-stu-id="b0038-109">Download and install the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] apps on a [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC and [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-hololens](../includes/pn-hololens.md)].</span></span>

4. <span data-ttu-id="b0038-110">Paramétrer les états d'Analyses de Guides.</span><span class="sxs-lookup"><span data-stu-id="b0038-110">Set up Guides Analytics reports.</span></span>

5. <span data-ttu-id="b0038-111">Ajouter des comptes d'utilisateur supplémentaires (facultatif).</span><span class="sxs-lookup"><span data-stu-id="b0038-111">Add additional user accounts (optional).</span></span>

<span data-ttu-id="b0038-112">Cette rubrique fournit des instructions détaillées pour tout ce qui précède.</span><span class="sxs-lookup"><span data-stu-id="b0038-112">This topic provides step-by-step instructions for all of the above.</span></span>

## <a name="step-1-buy-a-dynamics-365-guides-subscription-or-sign-up-for-a-free-trial-subscription"></a><span data-ttu-id="b0038-113">Étape 1 : Acheter un abonnement Dynamics 365 Guides ou s'inscrire pour un essai gratuit.</span><span class="sxs-lookup"><span data-stu-id="b0038-113">Step 1: Buy a Dynamics 365 Guides subscription or sign up for a free trial subscription</span></span>

<span data-ttu-id="b0038-114">Il existe plusieurs moyens d'obtenir un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] :</span><span class="sxs-lookup"><span data-stu-id="b0038-114">There are multiple ways to get a [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] subscription:</span></span>

- <span data-ttu-id="b0038-115">Si vous avez un compte professionnel Microsoft, vous pouvez accéder directement au Centre d'administration Microsoft 365 et rechercher un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] ici.</span><span class="sxs-lookup"><span data-stu-id="b0038-115">If you have a Microsoft work account, you can go directly to the Microsoft 365 admin center and search for a [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] subscription there.</span></span>

- <span data-ttu-id="b0038-116">Accédez à la page [Mise en route](https://aka.ms/GetGuides).</span><span class="sxs-lookup"><span data-stu-id="b0038-116">Go to the [Getting started](https://aka.ms/GetGuides) page.</span></span> <span data-ttu-id="b0038-117">Vous pouvez utiliser cette page pour acheter un abonnement ou vous inscrire pour un essai gratuit de 30 jours.</span><span class="sxs-lookup"><span data-stu-id="b0038-117">You can use this page to buy a subscription or to sign up for a free, 30-day trial subscription.</span></span> <span data-ttu-id="b0038-118">Si vous vous inscrivez pour un essai gratuit, vous pouvez utiliser les informations d'identification d'un compte Dynamics 365 existant ou en créer de nouvelles.</span><span class="sxs-lookup"><span data-stu-id="b0038-118">If you sign up for a trial, you can use credentials for an existing Dynamics 365 account or you can create new credentials.</span></span> 

    > [!IMPORTANT] 
    > <span data-ttu-id="b0038-119">Si vous ne disposez pas des autorisations d'administrateur associées à votre compte de travail, vous ne pourrez pas effectuer l'étape 2 du processus de configuration.</span><span class="sxs-lookup"><span data-stu-id="b0038-119">If you don't have administrator permissions associated with your work account, you won't be able to complete step 2 of the Setup process.</span></span> <span data-ttu-id="b0038-120">Veuillez coordonner la configuration avec votre administrateur.</span><span class="sxs-lookup"><span data-stu-id="b0038-120">Please coordinate setup with your administrator.</span></span> <span data-ttu-id="b0038-121">S'il n'est pas possible de coordonner la configuration avec votre administrateur, vous pouvez choisir de créer des informations d'identification d'utilisateur pour essayer [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] en suivant les étapes décrites sur la page [Mise en route](https://aka.ms/GetGuides).</span><span class="sxs-lookup"><span data-stu-id="b0038-121">If it's not possible to coordinate setup with your administrator, you can choose to create user credentials to try out [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] by following the steps on the [Getting started](https://aka.ms/GetGuides) page.</span></span> <span data-ttu-id="b0038-122">Dans ce cas, le nouvel abonné est créé et le compte du nouvel utilisateur créé bénéficie des autorisations d'administrateur.</span><span class="sxs-lookup"><span data-stu-id="b0038-122">In this case, the new tenant will be created and the newly created user account will have administrator permissions.</span></span> <span data-ttu-id="b0038-123">Notez que vous devez fournir le nom de domaine dans l'écran : *guidesYourCompanyName*.</span><span class="sxs-lookup"><span data-stu-id="b0038-123">Note that you'll need to provide the domain name in the form: *guidesYourCompanyName*</span></span>
    
<span data-ttu-id="b0038-124">Après vous être inscrit(e) pour un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous devez affecter la licence [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] aux comptes d'utilisateur.</span><span class="sxs-lookup"><span data-stu-id="b0038-124">After you sign up for a [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] subscription, you need to assign the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] license to user accounts.</span></span> <span data-ttu-id="b0038-125">Pour ce faire :</span><span class="sxs-lookup"><span data-stu-id="b0038-125">To do this:</span></span>

1. <span data-ttu-id="b0038-126">Accédez au [Centre d'administration Microsoft 365](https://admin.microsoft.com/AdminPortal/Home) et assurez-vous que le curseur de l'option **Nouveau Centre d'administration** dans le coin supérieur droit de la page est bien défini sur **activé**.</span><span class="sxs-lookup"><span data-stu-id="b0038-126">Go to the [Microsoft 365 admin center](https://admin.microsoft.com/AdminPortal/Home) and make sure that the slider for **The new admin center** option in the top right of the page is set to **on**.</span></span>

    <span data-ttu-id="b0038-127">![Curseur Nouveau Centre d'administration](media/new-admin-center-slider.PNG "Curseur Nouveau Centre d'administration")</span><span class="sxs-lookup"><span data-stu-id="b0038-127">![The new admin center slider](media/new-admin-center-slider.PNG "The new admin center slider")</span></span>

2.  <span data-ttu-id="b0038-128">Assurez-vous que la licence [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] est affectée à un utilisateur.</span><span class="sxs-lookup"><span data-stu-id="b0038-128">Make sure that the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] license is assigned to a user.</span></span> <span data-ttu-id="b0038-129">Pour cela, dans le volet gauche, sélectionnez **Utilisateurs**, **Utilisateurs actifs**, puis activez la case à cocher en regard de l'utilisateur à ajouter.</span><span class="sxs-lookup"><span data-stu-id="b0038-129">To do this, in the left pane, select **Users**, select **Active users**, and then select the check box for the user you want to add.</span></span> 

    <span data-ttu-id="b0038-130">![Page Utilisateurs > Utilisateurs actifs](media/users-active-users.PNG "Page Utilisateurs > Utilisateurs actifs")</span><span class="sxs-lookup"><span data-stu-id="b0038-130">![Users > Active Users page](media/users-active-users.PNG "Users > Active Users page")</span></span>
    
3.  <span data-ttu-id="b0038-131">Sélectionnez **Gérer les licences de produit**.</span><span class="sxs-lookup"><span data-stu-id="b0038-131">Select **Manage product licenses**.</span></span>

     <span data-ttu-id="b0038-132">![Gérer les licences de produit](media/manage-product-licenses.PNG "Gérer les licences de produit")</span><span class="sxs-lookup"><span data-stu-id="b0038-132">![Manage product licenses](media/manage-product-licenses.PNG "Manage product licenses")</span></span>

4.  <span data-ttu-id="b0038-133">Sur la page **Licences de produit**, activez la case à cocher pour **[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]**.</span><span class="sxs-lookup"><span data-stu-id="b0038-133">On the **Product licenses** page, select the check box for **[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]**.</span></span>
  
    <span data-ttu-id="b0038-134">![Ajouter une licence utilisateur](media/guides-license.PNG "Ajouter une licence utilisateur")</span><span class="sxs-lookup"><span data-stu-id="b0038-134">![Add user license](media/guides-license.PNG "Add user license")</span></span> 
 
## <span data-ttu-id="b0038-135">Étape 2 : Créer un environnement Common Data Service et installer la solution Dynamics 365 Guides<a name="cds"></a></span><span class="sxs-lookup"><span data-stu-id="b0038-135">Step 2: Create a Common Data Service environment and install the Dynamics 365 Guides solution<a name="cds"></a></span></span>

<span data-ttu-id="b0038-136">Après avoir acquis un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et avoir affecté les licences, vous devez créer un environnement où vous pouvez installer la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="b0038-136">After acquiring a [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] subscription and assigning licenses, you'll need to create an environment where you can install the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] solution.</span></span> <span data-ttu-id="b0038-137">Le type d'environnement que vous créez dépend de la création d'un environnement d'évaluation ou de production.</span><span class="sxs-lookup"><span data-stu-id="b0038-137">The type of environment you create depends on whether you're creating a trial or production environment.</span></span>

>[!NOTE]
><span data-ttu-id="b0038-138">Si vous disposez déjà d'un environnement Common Data Service (par exemple, une instance de l'abonnement Dynamics 365 de votre entreprise), vous pouvez passer directement à [Modifier la taille maximale de fichier pour le téléchargement](#upload).</span><span class="sxs-lookup"><span data-stu-id="b0038-138">If you already have a Common Data Service environment (for example, an instance in your company's Dynamics 365 tenant), you can skip to [Change maximum upload file size](#upload).</span></span>

### <a name="set-up-a-trial-environment-on-the-default-instance"></a><span data-ttu-id="b0038-139">Configurer un environnement d'évaluation sur l'instance par défaut</span><span class="sxs-lookup"><span data-stu-id="b0038-139">Set up a trial environment on the default instance</span></span>

<span data-ttu-id="b0038-140">Notez que l'instance par défaut ne fournit pas de capacités de sauvegarde et de restauration.</span><span class="sxs-lookup"><span data-stu-id="b0038-140">Note that the default instance does not provide backup and restore capabilities.</span></span> <span data-ttu-id="b0038-141">Si vous avez besoin de ces fonctionnalités, vous devez acheter une licence et configurer un environnement de production comme décrit dans la procédure suivante.</span><span class="sxs-lookup"><span data-stu-id="b0038-141">If you need these capabilities, you need to buy a license and set up a production environment as described in the next procedure.</span></span>
    
1.  <span data-ttu-id="b0038-142">Accédez au [Centre d'administration Power Platform](https://admin.powerplatform.microsoft.com/environments) et connectez-vous avec les informations d'identification de l'utilisateur Administrateur (celles liées aux licences [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] affectées).</span><span class="sxs-lookup"><span data-stu-id="b0038-142">Go to the [Power Platform Admin center](https://admin.powerplatform.microsoft.com/environments) and sign in with the admin user credentials (where the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] licenses are assigned).</span></span>

2.  <span data-ttu-id="b0038-143">Dans le Centre d'administration Power Platform, sélectionnez **Environnements**.</span><span class="sxs-lookup"><span data-stu-id="b0038-143">In the Power Platform Admin center, select **Environments**.</span></span>

    <span data-ttu-id="b0038-144">![Environnements Power Platform](media/powerapps-environments.PNG "Environnements Power Platform")</span><span class="sxs-lookup"><span data-stu-id="b0038-144">![Power Platform Environments](media/powerapps-environments.PNG "Power Platform Environments")</span></span>
    
3.  <span data-ttu-id="b0038-145">Sélectionnez le bouton **Autres actions d'environnement** (...) en regard de l'instance par défaut, puis sélectionnez **Gérer l'environnement**.</span><span class="sxs-lookup"><span data-stu-id="b0038-145">Select the **More environment actions** button (...) next to the default instance, and then select **Manage environment**.</span></span>

    <span data-ttu-id="b0038-146">![Gérer l'environnement](media/powerapps-manage-environment.PNG "Gérer l'environnement")</span><span class="sxs-lookup"><span data-stu-id="b0038-146">![Manage Environment](media/powerapps-manage-environment.PNG "Manage Environment")</span></span>    
     
4. <span data-ttu-id="b0038-147">Modifiez le nom de l'environnement (par exemple, Guides_*un nom quelconque*), puis sélectionnez **Créer ma base de données**.</span><span class="sxs-lookup"><span data-stu-id="b0038-147">Change the name of the environment (for example, Guides_*anyname*), and then select **Create my database**.</span></span>

    <span data-ttu-id="b0038-148">![Créer une base de données](media/powerapps-create-database.PNG "Créer une base de données")</span><span class="sxs-lookup"><span data-stu-id="b0038-148">![Create database](media/powerapps-create-database.PNG "Create database")</span></span>
    
5. <span data-ttu-id="b0038-149">Dans la boîte de dialogue **Créer une base de données pour cet environnement**, choisissez votre devise et votre langue.</span><span class="sxs-lookup"><span data-stu-id="b0038-149">In the **Create a database for this environment** dialog box, choose your currency and language.</span></span>

    <span data-ttu-id="b0038-150">![Paramètres de devise et de langue](media/currency-language-settings.PNG "Paramètres de devise et de langue")</span><span class="sxs-lookup"><span data-stu-id="b0038-150">![Currency and language settings](media/currency-language-settings.PNG "Currency and language settings")</span></span>
  
6.  <span data-ttu-id="b0038-151">Sélectionnez **Créer une base de données.**</span><span class="sxs-lookup"><span data-stu-id="b0038-151">Select **Create database.**</span></span>

    <span data-ttu-id="b0038-152">La page suivante s'affiche alors que la base de données est créée et mise en service :</span><span class="sxs-lookup"><span data-stu-id="b0038-152">The following page appears while the database is being created and provisioned:</span></span>
    
     <span data-ttu-id="b0038-153">![Page Approvisionnement de la base de données](media/provisioning-database.PNG "Page Approvisionnement de la base de données")</span><span class="sxs-lookup"><span data-stu-id="b0038-153">![Provisioning database page](media/provisioning-database.PNG "Provisioning database page")</span></span>
 
     > [!NOTE]
     > <span data-ttu-id="b0038-154">La création de la base de données prend généralement quelques minutes.</span><span class="sxs-lookup"><span data-stu-id="b0038-154">Database creation usually takes several minutes.</span></span> <span data-ttu-id="b0038-155">Si, au bout de cinq minutes, le message « Approvisionnement de la base de données » apparaît toujours, essayez d'actualiser la page.</span><span class="sxs-lookup"><span data-stu-id="b0038-155">If, after five minutes, the "Provisioning database" message still appears, try refreshing the page.</span></span>

7.  <span data-ttu-id="b0038-156">Une fois que la base de données a été créée, revenez à la page **Environnements** et allez à la procédure [Modifier la taille maximale de fichier pour le téléchargement](#upload) décrite plus loin dans cette rubrique.</span><span class="sxs-lookup"><span data-stu-id="b0038-156">After you've successfully created the database, return to the **Environments** page and go to the [Change maximum upload file size](#upload) procedure later in this topic.</span></span>

### <a name="set-up-a-production-environment"></a><span data-ttu-id="b0038-157">Configurer un environnement de production</span><span class="sxs-lookup"><span data-stu-id="b0038-157">Set up a production environment</span></span>

<span data-ttu-id="b0038-158">Si vous avez acheté une licence pour [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous devez configurer un environnement de production.</span><span class="sxs-lookup"><span data-stu-id="b0038-158">If you bought a license for [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], you need to set up a production environment.</span></span> <span data-ttu-id="b0038-159">Un environnement de production offre des capacités de sauvegarde et de restauration.</span><span class="sxs-lookup"><span data-stu-id="b0038-159">A production environment provides backup and restore capabilities.</span></span>

1.  <span data-ttu-id="b0038-160">Accédez au [Centre d'administration de Power Platform](https://admin.powerplatform.microsoft.com/environments), sélectionnez **Environnements** s'il n'est pas déjà sélectionné, puis sélectionnez **Nouveau**.</span><span class="sxs-lookup"><span data-stu-id="b0038-160">Go to the [Power Platform Admin center](https://admin.powerplatform.microsoft.com/environments), select **Environments** if it's not already selected, and then select **New**.</span></span>

    <span data-ttu-id="b0038-161">![Ajouter un nouvel environnement](media/add-new-environment.PNG "Ajouter un nouvel environnement")</span><span class="sxs-lookup"><span data-stu-id="b0038-161">![Add new environment](media/add-new-environment.PNG "Add new environment")</span></span> 

    <span data-ttu-id="b0038-162">Le volet **Nouvel environnement** apparaît sur le côté droit de l'écran.</span><span class="sxs-lookup"><span data-stu-id="b0038-162">The **New environment** pane appears on the right side of the screen.</span></span>

    <span data-ttu-id="b0038-163">![Volet Nouvel environnement](media/new-environment-pane.PNG "Volet Nouvel environnement")</span><span class="sxs-lookup"><span data-stu-id="b0038-163">![New environment pane](media/new-environment-pane.PNG "New environment pane")</span></span> 

3.  <span data-ttu-id="b0038-164">Dans le volet **Nouvel environnement** :</span><span class="sxs-lookup"><span data-stu-id="b0038-164">In the **New environment** pane:</span></span>

    <span data-ttu-id="b0038-165">a.</span><span class="sxs-lookup"><span data-stu-id="b0038-165">a.</span></span>  <span data-ttu-id="b0038-166">Entrez un nom pour l'environnement.</span><span class="sxs-lookup"><span data-stu-id="b0038-166">Enter a name for the environment.</span></span>

    <span data-ttu-id="b0038-167">b.</span><span class="sxs-lookup"><span data-stu-id="b0038-167">b.</span></span>  <span data-ttu-id="b0038-168">Dans la liste **Type**, sélectionnez **Production**.</span><span class="sxs-lookup"><span data-stu-id="b0038-168">In the **Type** list, select **Production**.</span></span>

    <span data-ttu-id="b0038-169">c.</span><span class="sxs-lookup"><span data-stu-id="b0038-169">c.</span></span>  <span data-ttu-id="b0038-170">Conservez les paramètres par défaut dans le champ **Région**.</span><span class="sxs-lookup"><span data-stu-id="b0038-170">In the **Region** field, keep the default setting.</span></span>  

    <span data-ttu-id="b0038-171">d.</span><span class="sxs-lookup"><span data-stu-id="b0038-171">d.</span></span>  <span data-ttu-id="b0038-172">Dans le champ **Créer une base de données pour cet environnement ?**, déplacez le curseur sur **Oui**.</span><span class="sxs-lookup"><span data-stu-id="b0038-172">In the **Create a database for this environment?** field, move the slider to **Yes**.</span></span>

    <span data-ttu-id="b0038-173">e.</span><span class="sxs-lookup"><span data-stu-id="b0038-173">e.</span></span>  <span data-ttu-id="b0038-174">Cliquez sur **Suivant** en bas de l'écran.</span><span class="sxs-lookup"><span data-stu-id="b0038-174">Select **Next** at the bottom of the screen.</span></span> 

3. <span data-ttu-id="b0038-175">Dans le volet **Ajouter une base de données** qui s'affiche, choisissez votre langue et votre devise, laissez les autres paramètres par défaut, puis sélectionnez **Enregistrer**.</span><span class="sxs-lookup"><span data-stu-id="b0038-175">In the **Add database** pane that appears, choose your language and currency, leave the other default settings, and then select **Save**.</span></span>

   <span data-ttu-id="b0038-176">![Volet Ajouter une base de données](media/add-database-pane.PNG "Volet Ajouter une base de données")</span><span class="sxs-lookup"><span data-stu-id="b0038-176">![Add database pane](media/add-database-pane.PNG "Add database pane")</span></span> 

   >[!NOTE]
   > <span data-ttu-id="b0038-177">Pour en savoir plus sur les groupes de sécurité, voir [Contrôler l'accès des utilisateurs aux instances](https://docs.microsoft.com/dynamics365/admin/add-instance-subscription#BKMK_man_sec_group).</span><span class="sxs-lookup"><span data-stu-id="b0038-177">To learn about security groups, see [Control user access to instances](https://docs.microsoft.com/dynamics365/admin/add-instance-subscription#BKMK_man_sec_group).</span></span>

   <span data-ttu-id="b0038-178">La page suivante apparaît pendant la préparation de l'environnement de production.</span><span class="sxs-lookup"><span data-stu-id="b0038-178">The following page appears while the production environment is being prepared.</span></span> 
   
    <span data-ttu-id="b0038-179">![Message L'environnement est en cours de préparation](media/environment-message.PNG "Message L'environnement est en cours de préparation")</span><span class="sxs-lookup"><span data-stu-id="b0038-179">![Environment getting prepared message](media/environment-message.PNG "Environment getting prepared message")</span></span> 

4.  <span data-ttu-id="b0038-180">Une fois le nouvel environnement actif (signalé comme **Prêt** dans la colonne **État**), passez à la procédure suivante pour modifier la taille maximale du fichier de téléchargement.</span><span class="sxs-lookup"><span data-stu-id="b0038-180">After the new environment is active (listed as **Ready** in the **State** column), go to the next procedure for changing the maximum upload file size.</span></span>

>[!NOTE]
><span data-ttu-id="b0038-181">Dans les procédures suivantes de cette rubrique, utilisez l'environnement de production au lieu de l'environnement par défaut indiqué dans les captures d'écran.</span><span class="sxs-lookup"><span data-stu-id="b0038-181">In subsequent procedures throughout this topic, use the production environment instead of the default environment shown in the screenshots.</span></span>

<a name="upload"></a>

### <a name="change-maximum-upload-file-size"></a><span data-ttu-id="b0038-182">Modifier la taille maximale de fichier pour le téléchargement</span><span class="sxs-lookup"><span data-stu-id="b0038-182">Change maximum upload file size</span></span>

<span data-ttu-id="b0038-183">Dans l'application du PC [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous pouvez télécharger vos propres fichiers 3D, ainsi que des vidéos et des images 2D.</span><span class="sxs-lookup"><span data-stu-id="b0038-183">In the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] PC application, you can upload your own 3D files in addition to videos and 2D images.</span></span> <span data-ttu-id="b0038-184">La taille de plusieurs de ces fichiers sera supérieure à 5 Mo, vous devrez donc modifier la taille maximale des fichiers qui seront chargés.</span><span class="sxs-lookup"><span data-stu-id="b0038-184">Many of these files will be larger than 5 MB, so you need to change the maximum file size for files that are uploaded.</span></span> <span data-ttu-id="b0038-185">Pour ce faire, vous devrez remplacer le paramètre de la taille de pièce jointe par 128 Mo (131072 Ko).</span><span class="sxs-lookup"><span data-stu-id="b0038-185">To do this, you'll change the setting for the email attachment size to 128 MB (131072 KB).</span></span>

1. <span data-ttu-id="b0038-186">Dans la page **Environnements** du Centre d'administration Power Platform, sélectionnez l'environnement nouvellement créé, puis sélectionnez le bouton **Autres actions d'environnement** (...), puis **Paramètres**.</span><span class="sxs-lookup"><span data-stu-id="b0038-186">On the Power Platform Admin center **Environments** page, select the newly created environment, select the **More environment actions** (...) button, and then select **Settings**.</span></span> 

    <span data-ttu-id="b0038-187">![Bouton Autres actions d'environnement](media/environment-settings.PNG "Bouton Autres actions d'environnement")</span><span class="sxs-lookup"><span data-stu-id="b0038-187">![More environment actions button](media/environment-settings.PNG "More environment actions button")</span></span>
       
2. <span data-ttu-id="b0038-188">Sous **E-mail**, sélectionnez **Paramètres d'e-mail**.</span><span class="sxs-lookup"><span data-stu-id="b0038-188">Under **Email**, select **Email settings**.</span></span> 

    <span data-ttu-id="b0038-189">![Paramètres d'e-mail](media/email-settings.png "Paramètres d'e-mail")</span><span class="sxs-lookup"><span data-stu-id="b0038-189">![Email settings](media/email-settings.png "Email settings")</span></span>

3. <span data-ttu-id="b0038-190">Faites défiler l'écran vers le bas de la page, puis sous **Documents joints**, définissez le champ **Taille maximale de fichier pour les pièces jointes** sur 131072.</span><span class="sxs-lookup"><span data-stu-id="b0038-190">Scroll down to the bottom of the page, and then under **Attachments**, set the **Maximum file size for attachments** field to 131072.</span></span> <span data-ttu-id="b0038-191">Sélectionnez **Enregistrer** une fois terminé.</span><span class="sxs-lookup"><span data-stu-id="b0038-191">Select **Save** when you're done.</span></span>

    <span data-ttu-id="b0038-192">![Taille du fichier](media/edit-file-size.png "Taille du fichier")</span><span class="sxs-lookup"><span data-stu-id="b0038-192">![File size](media/edit-file-size.png "File size")</span></span>

4. <span data-ttu-id="b0038-193">Revenez sur la page **Environnements** pour préparer l'étape suivante.</span><span class="sxs-lookup"><span data-stu-id="b0038-193">Go back to the **Environments** page to prepare for the next step.</span></span> 

### <span data-ttu-id="b0038-194">Installer et configurer la solution Dynamics 365 Guides<a name="configure"></a></span><span class="sxs-lookup"><span data-stu-id="b0038-194">Install and configure the Dynamics 365 Guides solution<a name="configure"></a></span></span>

1. <span data-ttu-id="b0038-195">Dans le [Centre d'administration Power Platform](https://admin.powerplatform.microsoft.com/environments), sélectionnez le bouton **Autres actions d'environnement** (...) en regard de l'environnement configuré, puis sélectionnez **Gérer les solutions**.</span><span class="sxs-lookup"><span data-stu-id="b0038-195">In the [Power Platform Admin center](https://admin.powerplatform.microsoft.com/environments), select the **More environment actions** (...) button next to the configured environment, and then select **Manage Solutions**.</span></span>

    <span data-ttu-id="b0038-196">![Gérer les solutions](media/manage-solutions.PNG "Gérer les solutions")</span><span class="sxs-lookup"><span data-stu-id="b0038-196">![Manage solutions](media/manage-solutions.PNG "Manage solutions")</span></span>
     
    >[!NOTE]
    > <span data-ttu-id="b0038-197">Vous pouvez également accéder au Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)] à partir du portail PowerApps.</span><span class="sxs-lookup"><span data-stu-id="b0038-197">You can also get to the [!include[pn-dyn-365](../includes/pn-dyn-365.md)] Administration Center from the PowerApps portal.</span></span>
    
2. <span data-ttu-id="b0038-198">Sélectionnez la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] dans la liste, puis sélectionnez **Installer**.</span><span class="sxs-lookup"><span data-stu-id="b0038-198">Select the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] solution in the list, and then select **Install**.</span></span>

    <span data-ttu-id="b0038-199">![Bouton Installer](media/solutions-install-button.png "Bouton Installer")</span><span class="sxs-lookup"><span data-stu-id="b0038-199">![Install button](media/solutions-install-button.png "Install button")</span></span>
    
3. <span data-ttu-id="b0038-200">Dans la boîte de dialogue **Conditions d'utilisation**, examinez les conditions, puis sélectionnez **Installer**.</span><span class="sxs-lookup"><span data-stu-id="b0038-200">In the **Terms of Service** dialog box, review the terms, and then select **Install**.</span></span>

    <span data-ttu-id="b0038-201">Dans la page Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)], le message suivant apparaît en surbrillance jaune pour indiquer que la solution est sur le point d'être installée : « Veuillez patienter pendant que l'installation démarre. »</span><span class="sxs-lookup"><span data-stu-id="b0038-201">On the [!include[pn-dyn-365](../includes/pn-dyn-365.md)] Administration Center page, you'll see the following message highlighted in yellow showing that the solution is about to be installed: "Please wait while installation starts."</span></span> 
        
     <span data-ttu-id="b0038-202">![Message d'installation](media/installing-solution.png "Message d'installation")</span><span class="sxs-lookup"><span data-stu-id="b0038-202">![Installing message](media/installing-solution.png "Installing message")</span></span>
     
    <span data-ttu-id="b0038-203">Le champ **Statut** à gauche du message installation indique **Installation en attente** lorsque la solution est en cours d'installation.</span><span class="sxs-lookup"><span data-stu-id="b0038-203">The **Status** field to the left of the installation message will say **Installation pending** while the solution is being installed.</span></span> <span data-ttu-id="b0038-204">Lorsque la solution est installée, le contenu du champ **Statut** est remplacé par **Installé**.</span><span class="sxs-lookup"><span data-stu-id="b0038-204">When the solution has finished installing, the **Status** field changes to **Installed**.</span></span>
    
    > [!NOTE]
    > <span data-ttu-id="b0038-205">Le processus d'installation peut prendre jusqu'à une heure et est variable en fonction du jour et de la région.</span><span class="sxs-lookup"><span data-stu-id="b0038-205">The installation process can take up to one hour and is variable based on the time of day and region.</span></span> <span data-ttu-id="b0038-206">Si le statut n'a pas changé au bout d'une heure, essayez d'actualiser la page.</span><span class="sxs-lookup"><span data-stu-id="b0038-206">If the status hasn't changed after an hour, try refreshing the page.</span></span> <span data-ttu-id="b0038-207">Si l'installation échoue, vous verrez ce message : « L'installation de la solution a échoué.</span><span class="sxs-lookup"><span data-stu-id="b0038-207">If the installation fails, you'll see this message: "Solution installation failed.</span></span> <span data-ttu-id="b0038-208">Réessayez plus tard.</span><span class="sxs-lookup"><span data-stu-id="b0038-208">Please try again later.</span></span> <span data-ttu-id="b0038-209">Si le problème persiste, contactez le service clientèle. »</span><span class="sxs-lookup"><span data-stu-id="b0038-209">If the problem persists, please contact customer support."</span></span><br><span data-ttu-id="b0038-210">![Échec de l'installation](media/failed-install.PNG "Échec de l'installation")</span><span class="sxs-lookup"><span data-stu-id="b0038-210">![Failed installation](media/failed-install.PNG "Failed installation")</span></span>

### <span data-ttu-id="b0038-211">Paramétrer des rôles d'utilisateur pour la solution<a name="user-roles"></a></span><span class="sxs-lookup"><span data-stu-id="b0038-211">Set up user roles for the solution<a name="user-roles"></a></span></span>

> [!NOTE]
> <span data-ttu-id="b0038-212">L'affichage d'un utilisateur dans le Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)] peut prendre jusqu'à une heure, une fois les licences ajoutées dans le Centre d'administration [!include[cc-microsoft](../includes/cc-microsoft.md)] 365.</span><span class="sxs-lookup"><span data-stu-id="b0038-212">It can take up to one hour for a user to appear in the [!include[pn-dyn-365](../includes/pn-dyn-365.md)] admin center after the licenses are added in the [!include[cc-microsoft](../includes/cc-microsoft.md)] 365 admin center.</span></span>

1. <span data-ttu-id="b0038-213">Une fois la solution installée, accédez au [Centre d'administration Power Platform](https://admin.powerplatform.microsoft.com/).</span><span class="sxs-lookup"><span data-stu-id="b0038-213">After the solution has finished installing, go to the [Power Platform admin center](https://admin.powerplatform.microsoft.com/).</span></span> 

2. <span data-ttu-id="b0038-214">Dans la page **Environnements**, sélectionnez l'environnement nouvellement créé, puis sélectionnez le bouton **Paramètres** dans la barre de titre.</span><span class="sxs-lookup"><span data-stu-id="b0038-214">On the **Environments** page, select the environment you created, and then select the **Settings** button in the title bar.</span></span> 

3. <span data-ttu-id="b0038-215">Sur la page **Paramètres**, sous **Utilisateurs + Autorisations**, sélectionnez **Utilisateurs**.</span><span class="sxs-lookup"><span data-stu-id="b0038-215">On the **Settings** page, under **Users + permissions**, select **Users**.</span></span>

    <span data-ttu-id="b0038-216">![Utilisateurs et autorisations](media/settings-page.png "Utilisateurs et autorisations")</span><span class="sxs-lookup"><span data-stu-id="b0038-216">![Users and permissions](media/settings-page.png "Users and permissions")</span></span>
    
    > [!IMPORTANT]
    > <span data-ttu-id="b0038-217">Vous pouvez accéder aux données [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] via la vignette Guides Hub de la page précédente, mais nous déconseillons d'effectuer des modifications dans Guides Hub.</span><span class="sxs-lookup"><span data-stu-id="b0038-217">You can access [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] data through the Guides Hub tile on the preceding page, but we recommend that you not make any changes in the Guides Hub.</span></span> <span data-ttu-id="b0038-218">Toute modification apportée peut avoir des conséquences imprévues pour les applications [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="b0038-218">Any changes you make can have unintended consequences for the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] apps.</span></span>
 
4.  <span data-ttu-id="b0038-219">Dans la page **Utilisateurs activés**, sélectionnez l'utilisateur, puis sélectionnez **Gérer les rôles**.</span><span class="sxs-lookup"><span data-stu-id="b0038-219">On the **Enabled Users** page, select the user, and then select **Manage Roles**.</span></span> 

    <span data-ttu-id="b0038-220">![Gérer les rôles](media/manage-roles.png "Gérer les rôles")</span><span class="sxs-lookup"><span data-stu-id="b0038-220">![Manage roles](media/manage-roles.png "Manage roles")</span></span>
 
5.  <span data-ttu-id="b0038-221">Dans la boîte de dialogue **Gérer les rôles d'utilisateurs**, sélectionnez les rôles suivants :</span><span class="sxs-lookup"><span data-stu-id="b0038-221">In the **Manage User Roles** dialog box, select the following roles:</span></span> 

    - <span data-ttu-id="b0038-222">Utilisateur Common Data Service</span><span class="sxs-lookup"><span data-stu-id="b0038-222">Common Data Service User</span></span>    

    - <span data-ttu-id="b0038-223">Auteur [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]</span><span class="sxs-lookup"><span data-stu-id="b0038-223">[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] Author</span></span>    
         
      <span data-ttu-id="b0038-224">![Boîte de dialogue Gérer les rôles renseignée](media/manage-roles-dialog-box.PNG "Boîte de dialogue Gérer les rôles renseignée")</span><span class="sxs-lookup"><span data-stu-id="b0038-224">![Manage Roles dialog box filled in](media/manage-roles-dialog-box.PNG "Manage Roles dialog box filled in")</span></span>
      
      > [!NOTE]
      > <span data-ttu-id="b0038-225">Sélectionnez également le rôle Administrateur système s'il s'agit de l'utilisateur principal/de l'administrateur. Sinon, ne sélectionnez pas ce rôle.</span><span class="sxs-lookup"><span data-stu-id="b0038-225">Also select the System Administrator role if this is the main user/admin. Otherwise, do not select that role.</span></span> 
     
## <a name="step-3-download-and-install-the-apps"></a><span data-ttu-id="b0038-226">Étape 3 : Télécharger et installer les applications.</span><span class="sxs-lookup"><span data-stu-id="b0038-226">Step 3: Download and install the apps</span></span>

<span data-ttu-id="b0038-227">Il y a deux applications [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] :</span><span class="sxs-lookup"><span data-stu-id="b0038-227">There are two [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] applications:</span></span> 

- <span data-ttu-id="b0038-228">Application de création du PC</span><span class="sxs-lookup"><span data-stu-id="b0038-228">PC authoring application</span></span>

- <span data-ttu-id="b0038-229">Application [!include[pn-hololens](../includes/pn-hololens.md)], avec un mode Créer et un mode Opérateur</span><span class="sxs-lookup"><span data-stu-id="b0038-229">[!include[pn-hololens](../includes/pn-hololens.md)] application, which has an Author mode and an Operator mode</span></span>

<span data-ttu-id="b0038-230">Vous pouvez installer les deux applications à partir de [!include[cc-microsoft](../includes/cc-microsoft.md)] Store tel que décrit dans la section suivante.</span><span class="sxs-lookup"><span data-stu-id="b0038-230">You can install both apps from [!include[cc-microsoft](../includes/cc-microsoft.md)] Store as described in the next section.</span></span>

> [!NOTE]
> <span data-ttu-id="b0038-231">Si vous ne pouvez pas accéder à [!include[cc-microsoft](../includes/cc-microsoft.md)] Store en raison de politiques d'entreprise, contactez votre administrateur pour qu'il distribue l'application.</span><span class="sxs-lookup"><span data-stu-id="b0038-231">If you can't access [!include[cc-microsoft](../includes/cc-microsoft.md)] Store due to company policies, please contact your administrator to distribute the app.</span></span>

<span data-ttu-id="b0038-232">Si vous utilisez [!include[cc-microsoft](../includes/cc-microsoft.md)] Store pour Entreprises pour distribuer vos applications, les utilisateurs peuvent les installer à partir du magasin privé de votre organisation ou d'un lien que vous leur envoyez par e-mail.</span><span class="sxs-lookup"><span data-stu-id="b0038-232">If you use [!include[cc-microsoft](../includes/cc-microsoft.md)] Store for Business to distribute your apps, you can have users install the apps from your organization's private store or from an email link that you send.</span></span> <span data-ttu-id="b0038-233">Les instructions sont fournies plus loin dans cette rubrique.</span><span class="sxs-lookup"><span data-stu-id="b0038-233">Instructions are provided later in this topic.</span></span>

### <a name="install-the-apps-from-microsoft-store"></a><span data-ttu-id="b0038-234">Installer les applications à partir de Microsoft Store</span><span class="sxs-lookup"><span data-stu-id="b0038-234">Install the apps from Microsoft Store</span></span>

#### <a name="install-the-pc-authoring-app"></a><span data-ttu-id="b0038-235">Installer l'application de création sur PC</span><span class="sxs-lookup"><span data-stu-id="b0038-235">Install the PC authoring app</span></span> 
1.  <span data-ttu-id="b0038-236">Assurez-vous que votre [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC exécute la dernière version de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] (doit correspondre à la version 10.0.17134, mise à jour d’avril 2018 ou ultérieure).</span><span class="sxs-lookup"><span data-stu-id="b0038-236">Check to make sure your [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC is running the latest [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] build (must be build 10.0.17134, April 2018 update, or later).</span></span>

2.  <span data-ttu-id="b0038-237">Sur votre PC, allez dans **Démarrer** ![Bouton Démarrer](media/windows-button.png "Bouton Démarrer") > **[!include[cc-microsoft](../includes/cc-microsoft.md)] Store** ![bouton Store](media/store-button.png "Bouton Store"), puis recherchez [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="b0038-237">On your PC, go to **Start** ![Start button](media/windows-button.png "Start button") > **[!include[cc-microsoft](../includes/cc-microsoft.md)] Store** ![Store button](media/store-button.png "Store button"), and then search for "[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]".</span></span>

3.  <span data-ttu-id="b0038-238">Dans [!include[cc-microsoft](../includes/cc-microsoft.md)] Store, sélectionnez **Installer** pour télécharger et installer l'application.</span><span class="sxs-lookup"><span data-stu-id="b0038-238">In [!include[cc-microsoft](../includes/cc-microsoft.md)] Store, select **Install** to download and install the application.</span></span>

    > [!NOTE]
    > <span data-ttu-id="b0038-239">Pour obtenir des instructions sur l'ouverture et la connexion à l'application, voir [Guide Création sur PC](pc-authoring.md).</span><span class="sxs-lookup"><span data-stu-id="b0038-239">For instructions on opening and signing in to the app, see the [PC authoring guide](pc-authoring.md).</span></span>

#### <a name="install-the-hololens-app"></a><span data-ttu-id="b0038-240">Installer l'application HoloLens</span><span class="sxs-lookup"><span data-stu-id="b0038-240">Install the HoloLens app</span></span>

1.  <span data-ttu-id="b0038-241">Assurez-vous qu'[!include[pn-hololens](../includes/pn-hololens.md)] exécute la version 10.0.17134 ou ultérieure.</span><span class="sxs-lookup"><span data-stu-id="b0038-241">Make sure [!include[pn-hololens](../includes/pn-hololens.md)] is running build 10.0.17134 or later.</span></span> <span data-ttu-id="b0038-242">Nous vous recommandons de mettre à jour [!include[pn-hololens](../includes/pn-hololens.md)] vers des versions plus récentes quand elles sont disponibles.</span><span class="sxs-lookup"><span data-stu-id="b0038-242">We recommend updating [!include[pn-hololens](../includes/pn-hololens.md)] to newer versions when available.</span></span> <span data-ttu-id="b0038-243">Pour obtenir des instructions sur l'utilisation de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Update pour Entreprise, voir [Gérer les mises à jour vers HoloLens](https://docs.microsoft.com/HoloLens/hololens-updates).</span><span class="sxs-lookup"><span data-stu-id="b0038-243">For instructions on using [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Update for Business, see [Manage updates to HoloLens](https://docs.microsoft.com/HoloLens/hololens-updates).</span></span>

2.  <span data-ttu-id="b0038-244">Dans [!include[pn-hololens](../includes/pn-hololens.md)], utilisez l'écartement des doigts paume vers le haut pour ouvrir le menu **Accueil**, puis ouvrez l'application [!include[cc-microsoft](../includes/cc-microsoft.md)] Store et recherchez [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="b0038-244">On your [!include[pn-hololens](../includes/pn-hololens.md)], use the bloom gesture to open the **Home** menu, and then open the [!include[cc-microsoft](../includes/cc-microsoft.md)] Store app and search for "[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]".</span></span>

3.  <span data-ttu-id="b0038-245">Pour télécharger et installer l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], sélectionnez **Installer**.</span><span class="sxs-lookup"><span data-stu-id="b0038-245">To download and install the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] application, select **Install**.</span></span>

> [!NOTE] 
> <span data-ttu-id="b0038-246">Si vous êtes un auteur, consultez la rubrique de création [HoloLens](hololens-authoring.md) pour obtenir des instructions sur l'ouverture et la connexion à l'application.</span><span class="sxs-lookup"><span data-stu-id="b0038-246">If you're an author, see the [HoloLens authoring topic](hololens-authoring.md) for instructions on opening and signing in to the app.</span></span> <span data-ttu-id="b0038-247">Les opérateurs peuvent utiliser le [manuel de l'opérateur Dynamics 365 Guides](operator-guide.md).</span><span class="sxs-lookup"><span data-stu-id="b0038-247">Operators can use the [Dynamics 365 Guides Operator's manual](operator-guide.md).</span></span>

### <a name="distribute-the-apps-through-microsoft-store-for-business"></a><span data-ttu-id="b0038-248">Répartir les applications par le biais de Microsoft Store pour Entreprises</span><span class="sxs-lookup"><span data-stu-id="b0038-248">Distribute the apps through Microsoft Store for Business</span></span>

1.  <span data-ttu-id="b0038-249">Allez à [Microsoft Store pour Entreprises](https://businessstore.microsoft.com/store).</span><span class="sxs-lookup"><span data-stu-id="b0038-249">Go to [Microsoft Store for Business](https://businessstore.microsoft.com/store).</span></span>

2.  <span data-ttu-id="b0038-250">[Faites l'acquisition de la ou des applications](https://docs.microsoft.com/microsoft-store/acquire-apps-microsoft-store-for-business).</span><span class="sxs-lookup"><span data-stu-id="b0038-250">[Acquire the app(s)](https://docs.microsoft.com/microsoft-store/acquire-apps-microsoft-store-for-business).</span></span>

3.  <span data-ttu-id="b0038-251">Choisissez l'une des méthodes de distribution suivantes :</span><span class="sxs-lookup"><span data-stu-id="b0038-251">Choose one of the following distribution methods:</span></span>

    - [<span data-ttu-id="b0038-252">Magasin privé</span><span class="sxs-lookup"><span data-stu-id="b0038-252">Private store</span></span>](https://docs.microsoft.com/microsoft-store/distribute-apps-from-your-private-store)
    
    - [<span data-ttu-id="b0038-253">Lien de courrier électronique</span><span class="sxs-lookup"><span data-stu-id="b0038-253">Email link</span></span>](https://docs.microsoft.com/microsoft-store/assign-apps-to-employees)
    
    - [<span data-ttu-id="b0038-254">Gestion des périphériques mobiles</span><span class="sxs-lookup"><span data-stu-id="b0038-254">Mobile device management</span></span>](https://docs.microsoft.com/microsoft-store/configure-mdm-provider-microsoft-store-for-business)

<span data-ttu-id="b0038-255">Pour plus d'informations sur l'ouverture et la connexion à l'application du PC après l'avoir installée, voir [Création de guide](authoring-overview.md).</span><span class="sxs-lookup"><span data-stu-id="b0038-255">For information about opening and signing in to the PC application after installing it, see the [authoring guide](authoring-overview.md).</span></span>

<span data-ttu-id="b0038-256">Pour plus d'informations sur l'ouverture et la connexion à l'application [!include[pn-hololens](../includes/pn-hololens.md)], accédez à l'une des options suivantes, selon que vous êtes auteur ou opérateur :</span><span class="sxs-lookup"><span data-stu-id="b0038-256">For information about opening and signing in to the [!include[pn-hololens](../includes/pn-hololens.md)] application, go to one of the following, depending on whether you're an author or an operator:</span></span>

   - [<span data-ttu-id="b0038-257">Création HoloLens</span><span class="sxs-lookup"><span data-stu-id="b0038-257">HoloLens authoring</span></span>](hololens-authoring.md)
   
   - [<span data-ttu-id="b0038-258">Manuel de l'opérateur</span><span class="sxs-lookup"><span data-stu-id="b0038-258">Operator's manual</span></span>](operator-guide.md)

## <a name="step-4-set-up-guides-analytics-reports"></a><span data-ttu-id="b0038-259">Étape 4 : Paramétrer les états d'Analyses de Guides</span><span class="sxs-lookup"><span data-stu-id="b0038-259">Step 4: Set up Guides Analytics reports</span></span> 

[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] <span data-ttu-id="b0038-260">inclut des états [!include[pn-power-bi](../includes/pn-power-bi.md)] (appelés Analyses de Guides) qui permettent d'analyser les processus des guides [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="b0038-260">includes [!include[pn-power-bi](../includes/pn-power-bi.md)] reports (called Guides Analytics) that you can use to analyze [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] processes.</span></span> <span data-ttu-id="b0038-261">Suivez les instructions pour savoir comment [ouvrir Analyses de Guides](https://docs.microsoft.com/dynamics365/mixed-reality/guides/analytics-guide#open-guides-analytics) en utilisant l'[application Power BI Desktop](https://powerbi.microsoft.com/get-started/) disponible gratuitement.</span><span class="sxs-lookup"><span data-stu-id="b0038-261">Follow the instructions for how to [Open Guides Analytics](https://docs.microsoft.com/dynamics365/mixed-reality/guides/analytics-guide#open-guides-analytics) using the free [Power BI Desktop application](https://powerbi.microsoft.com/get-started/).</span></span>

<span data-ttu-id="b0038-262">Si vous disposez d'une licence [!include[pn-power-bi](../includes/pn-power-bi.md)] Pro, vous pouvez partager vos états d'Analyses de Guides [!include[pn-power-bi](../includes/pn-power-bi.md)] au sein de votre organisation en les publiant dans le service [!include[pn-power-bi](../includes/pn-power-bi.md)].</span><span class="sxs-lookup"><span data-stu-id="b0038-262">If you have a [!include[pn-power-bi](../includes/pn-power-bi.md)] Pro license, you can share your Guides Analytics [!include[pn-power-bi](../includes/pn-power-bi.md)] reports within your organization by publishing them to the [!include[pn-power-bi](../includes/pn-power-bi.md)] Service.</span></span> <span data-ttu-id="b0038-263">Cela permet à toute personne de votre organisation ayant une licence Pro [!include[pn-power-bi](../includes/pn-power-bi.md)] d'accéder à l'état via l'interface Web du service [!include[pn-power-bi](../includes/pn-power-bi.md)] accessible sur [https://powerbi.microsoft.com](https://powerbi.microsoft.com).</span><span class="sxs-lookup"><span data-stu-id="b0038-263">This allows anyone in your organization with a [!include[pn-power-bi](../includes/pn-power-bi.md)] Pro license to access the report through the [!include[pn-power-bi](../includes/pn-power-bi.md)] Service web interface accessible at [https://powerbi.microsoft.com](https://powerbi.microsoft.com).</span></span> <span data-ttu-id="b0038-264">Pour en savoir plus sur la collaboration sur le cloud de [!include[pn-power-bi](../includes/pn-power-bi.md)] et le partage, ainsi que l'inscription à une version d'essai gratuit de [!include[pn-power-bi](../includes/pn-power-bi.md)] Pro, consultez [Getting Started with Power BI Desktop](https://powerbi.microsoft.com/get-started/) et [Ways to share your work in Power BI](https://docs.microsoft.com/power-bi/service-how-to-collaborate-distribute-dashboards-reports).</span><span class="sxs-lookup"><span data-stu-id="b0038-264">To learn about [!include[pn-power-bi](../includes/pn-power-bi.md)] cloud collaboration and sharing and to sign up for a free trial of [!include[pn-power-bi](../includes/pn-power-bi.md)] Pro, visit [Getting Started with Power BI Desktop](https://powerbi.microsoft.com/get-started/) and [Ways to share your work in Power BI](https://docs.microsoft.com/power-bi/service-how-to-collaborate-distribute-dashboards-reports).</span></span>

## <span data-ttu-id="b0038-265">Étape 5 : Ajouter des comptes d'utilisateur supplémentaires (facultatif)<a name="user-accounts"></a></span><span class="sxs-lookup"><span data-stu-id="b0038-265">Step 5: Add additional user accounts (optional)<a name="user-accounts"></a></span></span>

<span data-ttu-id="b0038-266">Pour ajouter des utilisateurs supplémentaires, vous devez leur affecter la licence [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et configurer les rôles auxquels ils auront accès dans le Centre d'administration Dynamics 365.</span><span class="sxs-lookup"><span data-stu-id="b0038-266">If you want to add additional users, you need to assign the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] license to them and configure the roles they will have access to in the Dynamics 365 admin center.</span></span>

### <a name="add-a-user-account"></a><span data-ttu-id="b0038-267">Ajouter un compte d'utilisateur</span><span class="sxs-lookup"><span data-stu-id="b0038-267">Add a user account</span></span>

1. <span data-ttu-id="b0038-268">Accédez à [Centre d'administration Microsoft 365](https://admin.microsoft.com/AdminPortal/Home).</span><span class="sxs-lookup"><span data-stu-id="b0038-268">Go to the [Microsoft 365 admin center](https://admin.microsoft.com/AdminPortal/Home).</span></span>

2. <span data-ttu-id="b0038-269">Dans le volet gauche, sélectionnez **Utilisateurs**, puis **Utilisateurs actifs**.</span><span class="sxs-lookup"><span data-stu-id="b0038-269">In the left pane, select **Users**, and then select **Active users**.</span></span> 

3. <span data-ttu-id="b0038-270">Sur la page **Utilisateurs actifs**, sélectionnez **Ajouter un utilisateur**.</span><span class="sxs-lookup"><span data-stu-id="b0038-270">On the **Active users** page, select **Add a user**.</span></span>

   <span data-ttu-id="b0038-271">![Commande Ajouter un utilisateur](media/add-additional-user.png "Commande Ajouter un utilisateur")</span><span class="sxs-lookup"><span data-stu-id="b0038-271">![Add a user command](media/add-additional-user.png "Add a user command")</span></span> 

4. <span data-ttu-id="b0038-272">Sur la page **Configurer les bases**, renseignez les informations pour le nouvel utilisateur.</span><span class="sxs-lookup"><span data-stu-id="b0038-272">On the **Set up the basics** page, fill in the information for the new user.</span></span> <span data-ttu-id="b0038-273">Sélectionnez **Suivant** une fois terminé.</span><span class="sxs-lookup"><span data-stu-id="b0038-273">Select **Next** when you're done.</span></span>

   <span data-ttu-id="b0038-274">![Page Configurer les bases](media/setup-basics.png "Page Configurer les bases")</span><span class="sxs-lookup"><span data-stu-id="b0038-274">![Set up the basics page](media/setup-basics.png "Set up the basics page")</span></span>

   > [!NOTE]
   > <span data-ttu-id="b0038-275">Par défaut, un mot de passe sera généré automatiquement pour l'utilisateur.</span><span class="sxs-lookup"><span data-stu-id="b0038-275">By default, an auto-generated password will be generated for the user.</span></span> <span data-ttu-id="b0038-276">L'utilisateur doit modifier le mot de passe la première fois qu'il se connecte à ce compte.</span><span class="sxs-lookup"><span data-stu-id="b0038-276">The user is required to change the password the first time they sign in with this account.</span></span> <span data-ttu-id="b0038-277">Pour remplacer le mot de passe par un mot de passe permanent au lieu d'utiliser celui généré automatiquement, cochez l'option **Mot de passe généré automatiquement** et désactivez l'option **Demander à cet utilisateur de modifier son mot de passe lorsqu'il se connecte pour la première fois.**</span><span class="sxs-lookup"><span data-stu-id="b0038-277">If you want to change the password to a permanent password instead of using the auto-generated password, select the **Let me create the password** option, and then clear the **Require this user to change their password when they first sign in** check box.</span></span> 
 
5. <span data-ttu-id="b0038-278">Sélectionnez l'emplacement de cet utilisateur, puis sous **Licences**, activez la case à cocher **Dynamics 365 Guides**.</span><span class="sxs-lookup"><span data-stu-id="b0038-278">Select the location for this user, and then under **Licenses**, select the **Dynamics 365 Guides** check box.</span></span> 

    <span data-ttu-id="b0038-279">![Case à cocher Dynamics 365 Guides](media/assign-license-user.png "Case à cocher Dynamics 365 Guides")</span><span class="sxs-lookup"><span data-stu-id="b0038-279">![Dynamics 365 Guides check box](media/assign-license-user.png "Dynamics 365 Guides check box")</span></span> 

     <span data-ttu-id="b0038-280">Sélectionnez **Suivant** une fois terminé.</span><span class="sxs-lookup"><span data-stu-id="b0038-280">Select **Next** when you're done.</span></span>
   
7. <span data-ttu-id="b0038-281">Sur la page **Paramètres facultatifs**, laissez la zone **Utilisateur (aucun accès Administrateur)** sélectionnée à moins que ce nouvel utilisateur soit un administrateur.</span><span class="sxs-lookup"><span data-stu-id="b0038-281">On the **Optional settings** page, leave the **User (no administrator access)** box selected unless this new user will be an administrator.</span></span> <span data-ttu-id="b0038-282">Dans ce cas, activez la case à cocher **Administrateur global**.</span><span class="sxs-lookup"><span data-stu-id="b0038-282">In that case, select the **Global administrator** check box.</span></span> 

   <span data-ttu-id="b0038-283">![Page Paramètres facultatifs](media/user-optional-settings.png "Page Paramètres facultatifs")</span><span class="sxs-lookup"><span data-stu-id="b0038-283">![Optional settings page](media/user-optional-settings.png "Optional settings page")</span></span> 
   
8. <span data-ttu-id="b0038-284">Pour renseigner les informations de profil du nouvel utilisateur, faites défiler et développez **Informations de profil**.</span><span class="sxs-lookup"><span data-stu-id="b0038-284">To fill out the new user's profile info, scroll down, and then expand **Profile info**.</span></span> <span data-ttu-id="b0038-285">Sélectionnez **Suivant** une fois terminé.</span><span class="sxs-lookup"><span data-stu-id="b0038-285">Select **Next** when you're done.</span></span>
   
   <span data-ttu-id="b0038-286">![Informations de profil développées](media/expanded-profile-info.png "Informations de profil développées")</span><span class="sxs-lookup"><span data-stu-id="b0038-286">![Expanded Profile info](media/expanded-profile-info.png "Expanded Profile info")</span></span>
   
8. <span data-ttu-id="b0038-287">Vérifiez les informations de cette dernière page.</span><span class="sxs-lookup"><span data-stu-id="b0038-287">Review the information on the last page.</span></span> <span data-ttu-id="b0038-288">Pour apporter des modifications, sélectionnez le bouton **Modifier** en dessous de chaque section.</span><span class="sxs-lookup"><span data-stu-id="b0038-288">To make changes, select the **Edit** button below each section.</span></span> <span data-ttu-id="b0038-289">Sélectionnez **Terminé l'ajout** une fois terminé.</span><span class="sxs-lookup"><span data-stu-id="b0038-289">Select **Finish Adding** when you're done.</span></span>

   <span data-ttu-id="b0038-290">![Page de vérification avec les boutons Modifier](media/review-page.png "Page de vérification avec les boutons Modifier")</span><span class="sxs-lookup"><span data-stu-id="b0038-290">![Review page with Edit buttons](media/review-page.png "Review page with Edit buttons")</span></span>

9. <span data-ttu-id="b0038-291">Si vous avez sélectionné **Mot de passe généré automatiquement** à l'étape 4, notez le mot de passe.</span><span class="sxs-lookup"><span data-stu-id="b0038-291">If you selected **Auto-generate password** in step 4, make note of the password.</span></span> <span data-ttu-id="b0038-292">L'utilisateur a besoin de ce mot de passe pour se connecter.</span><span class="sxs-lookup"><span data-stu-id="b0038-292">The user will need this password to sign in.</span></span>

   <span data-ttu-id="b0038-293">![Mot de passé généré automatiquement](media/review-user-settings.png "Mot de passe généré automatiquement")</span><span class="sxs-lookup"><span data-stu-id="b0038-293">![Auto-generated password](media/review-user-settings.png "Auto-generated password")</span></span> 
   
10. <span data-ttu-id="b0038-294">Sélectionnez **Fermer**.</span><span class="sxs-lookup"><span data-stu-id="b0038-294">Select **Close**.</span></span>

11. <span data-ttu-id="b0038-295">[Paramétrez des rôles d'utilisateur pour la solution](#user-roles) comme décrit précédemment dans cette rubrique.</span><span class="sxs-lookup"><span data-stu-id="b0038-295">[Set up user roles for the solution](#user-roles) as described earlier in this topic.</span></span>

### <a name="see-also"></a><span data-ttu-id="b0038-296">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="b0038-296">See also</span></span>

[<span data-ttu-id="b0038-297">Mise en route d'Dynamics 365 Guides</span><span class="sxs-lookup"><span data-stu-id="b0038-297">Get started with Dynamics 365 Guides</span></span>](get-started.md)<br>
[<span data-ttu-id="b0038-298">Créer un guide</span><span class="sxs-lookup"><span data-stu-id="b0038-298">Author a guide</span></span>](authoring-overview.md)<br>
[<span data-ttu-id="b0038-299">Manuel de l'opérateur</span><span class="sxs-lookup"><span data-stu-id="b0038-299">Operator's manual</span></span>](operator-guide.md)<br>
[<span data-ttu-id="b0038-300">Analyser les guides pour rendre les processus plus efficaces</span><span class="sxs-lookup"><span data-stu-id="b0038-300">Analyze your guides to improve process efficiencies</span></span>](analytics-guide.md)<br>
[<span data-ttu-id="b0038-301">FAQ</span><span class="sxs-lookup"><span data-stu-id="b0038-301">FAQ</span></span>](faq.md)