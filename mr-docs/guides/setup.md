---
author: Mamaylya
description: Tout ce que vous devez savoir sur l'achat de Dynamics 365 Guides, la configuration de la solution, et l'installation des applications.
ms.author: mamaylya
ms.date: 10/01/2019
ms.service: crm-online
ms.topic: article
title: Acheter et déployer Dynamics 365 Guides
ms.reviewer: v-brycho
ms.openlocfilehash: 1ee96bf6bf2423cf1a33df8a78d253eb48456c3c
ms.sourcegitcommit: 40992f99110d02b2120a930679c5f681b0a6227a
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/25/2019
ms.locfileid: "2049992"
---
# <a name="buy-and-deploy-dynamics-365-guides"></a><span data-ttu-id="edf84-103">Acheter et déployer Dynamics 365 Guides</span><span class="sxs-lookup"><span data-stu-id="edf84-103">Buy and deploy Dynamics 365 Guides</span></span>

<span data-ttu-id="edf84-104">Nous sommes ravis de vous présenter [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] pour la disponibilité générale !</span><span class="sxs-lookup"><span data-stu-id="edf84-104">We're thrilled to introduce [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] for general availability!</span></span> <span data-ttu-id="edf84-105">[En savoir plus sur les fonctionnalités de Guides](index.md).</span><span class="sxs-lookup"><span data-stu-id="edf84-105">[Learn about Guides capabilities](index.md).</span></span>

<span data-ttu-id="edf84-106">Pour démarrer avec [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous devez :</span><span class="sxs-lookup"><span data-stu-id="edf84-106">To get started with [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], you need to:</span></span>

1. <span data-ttu-id="edf84-107">Achetez un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] ou inscrivez-vous pour un essai gratuit de 30 jours.</span><span class="sxs-lookup"><span data-stu-id="edf84-107">Buy a [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] subscription or sign up for a free 30-day trial subscription.</span></span>

2. <span data-ttu-id="edf84-108">Créez un environnement Common Data Service (si vous n'en avez pas déjà un) et installez la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] dans l'environnement (instance).</span><span class="sxs-lookup"><span data-stu-id="edf84-108">Create a Common Data Service environment (if you don't already have one) and install the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] solution in the environment (instance).</span></span>

3.  <span data-ttu-id="edf84-109">Télécharger et installer les applications [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] sur un [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC et [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-hololens](../includes/pn-hololens.md)].</span><span class="sxs-lookup"><span data-stu-id="edf84-109">Download and install the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] apps on a [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC and [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-hololens](../includes/pn-hololens.md)].</span></span>

4. <span data-ttu-id="edf84-110">Paramétrer les états d'Analyses de Guides.</span><span class="sxs-lookup"><span data-stu-id="edf84-110">Set up Guides Analytics reports.</span></span>

5. <span data-ttu-id="edf84-111">Ajouter des comptes d'utilisateur supplémentaires (facultatif).</span><span class="sxs-lookup"><span data-stu-id="edf84-111">Add additional user accounts (optional).</span></span>

<span data-ttu-id="edf84-112">Cette rubrique fournit des instructions détaillées pour tout ce qui précède.</span><span class="sxs-lookup"><span data-stu-id="edf84-112">This topic provides step-by-step instructions for all of the above.</span></span>

## <a name="step-1-buy-a-dynamics-365-guides-subscription-or-sign-up-for-a-free-trial-subscription"></a><span data-ttu-id="edf84-113">Étape 1 : Acheter un abonnement Dynamics 365 Guides ou s'inscrire pour un essai gratuit.</span><span class="sxs-lookup"><span data-stu-id="edf84-113">Step 1: Buy a Dynamics 365 Guides subscription or sign up for a free trial subscription</span></span>

<span data-ttu-id="edf84-114">Il existe plusieurs moyens d'obtenir un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] :</span><span class="sxs-lookup"><span data-stu-id="edf84-114">There are multiple ways to get a [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] subscription:</span></span>

- <span data-ttu-id="edf84-115">Si vous avez un compte professionnel Microsoft, vous pouvez accéder directement au Centre d'administration Microsoft 365 et rechercher un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] ici.</span><span class="sxs-lookup"><span data-stu-id="edf84-115">If you have a Microsoft work account, you can go directly to the Microsoft 365 Admin Center and search for a [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] subscription there.</span></span>

- <span data-ttu-id="edf84-116">Accédez à la [page Mise en route](http://aka.ms/GetGuides).</span><span class="sxs-lookup"><span data-stu-id="edf84-116">Go to [the Getting started page](http://aka.ms/GetGuides).</span></span> <span data-ttu-id="edf84-117">Vous pouvez utiliser cette page pour acheter un abonnement ou vous inscrire pour un essai gratuit de 30 jours.</span><span class="sxs-lookup"><span data-stu-id="edf84-117">You can use this page to buy a subscription or to sign up for a free 30-day trial subscription.</span></span> <span data-ttu-id="edf84-118">Si vous vous inscrivez pour un essai gratuit, vous pouvez utiliser les informations d'identification d'un compte Dynamics 365 existant ou en créer de nouvelles.</span><span class="sxs-lookup"><span data-stu-id="edf84-118">If you sign up for a trial, you can use credentials for an existing Dynamics 365 account or you can create new credentials.</span></span> 

    > [!IMPORTANT] 
    > <span data-ttu-id="edf84-119">Si vous ne disposez pas des autorisations d'administrateur associées à votre compte de travail, vous ne pourrez pas effectuer l'étape 2 du processus de paramétrage.</span><span class="sxs-lookup"><span data-stu-id="edf84-119">If you don't have administrator permissions associated with your work account, you won't be able to complete Step 2 of the Setup process.</span></span> <span data-ttu-id="edf84-120">Veuillez coordonner la configuration avec votre administrateur.</span><span class="sxs-lookup"><span data-stu-id="edf84-120">Please coordinate setup with your administrator.</span></span> <span data-ttu-id="edf84-121">S'il n'est pas possible de coordonner la configuration avec votre administrateur, vous pouvez choisir de créer des informations d'identification d'utilisateur pour essayer [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] en suivant les étapes décrites sur la page Mise en route.</span><span class="sxs-lookup"><span data-stu-id="edf84-121">If it's not possible to coordinate setup with your administrator, you can choose to create user credentials to try out [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] by following the steps on the Getting started page.</span></span> <span data-ttu-id="edf84-122">Dans ce cas, le nouvel abonné est créé et le compte du nouvel utilisateur créé bénéficie des autorisations d'administrateur.</span><span class="sxs-lookup"><span data-stu-id="edf84-122">In this case, the new tenant will be created and the newly created user account will have administrator permissions.</span></span> <span data-ttu-id="edf84-123">Notez que vous devez fournir le nom de domaine dans l'écran : *guidesYourCompanyName*.</span><span class="sxs-lookup"><span data-stu-id="edf84-123">Note that you'll need to provide the domain name in the form: *guidesYourCompanyName*.</span></span>
    
<span data-ttu-id="edf84-124">Après vous être inscrit(e) pour un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous devez affecter la licence [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] aux comptes d'utilisateur.</span><span class="sxs-lookup"><span data-stu-id="edf84-124">After you sign up for a [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] subscription, you need to assign the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] license to user accounts.</span></span> <span data-ttu-id="edf84-125">Pour ce faire :</span><span class="sxs-lookup"><span data-stu-id="edf84-125">To do this:</span></span>

1. <span data-ttu-id="edf84-126">Accédez à [Centre d'administration Microsoft 365](https://admin.microsoft.com/AdminPortal/Home).</span><span class="sxs-lookup"><span data-stu-id="edf84-126">Go to the [Microsoft 365 Admin Center](https://admin.microsoft.com/AdminPortal/Home).</span></span>

2.  <span data-ttu-id="edf84-127">Assurez-vous que la licence [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] est affectée à un utilisateur.</span><span class="sxs-lookup"><span data-stu-id="edf84-127">Make sure that the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] license is assigned to a user.</span></span> <span data-ttu-id="edf84-128">Pour cela, dans le volet gauche, sélectionnez **Utilisateurs**, **Utilisateurs actifs**, puis activez la case à cocher en regard de l'utilisateur à ajouter.</span><span class="sxs-lookup"><span data-stu-id="edf84-128">To do that, in the left pane, select **Users**, select **Active users**, and then select the check box for the user you want to add.</span></span> 

    <span data-ttu-id="edf84-129">![Écran Utilisateurs > Utilisateurs actifs](media/users-active-users.PNG "Écran Utilisateurs > Utilisateurs actifs")</span><span class="sxs-lookup"><span data-stu-id="edf84-129">![Users > Active Users screen](media/users-active-users.PNG "Users > Active Users screen")</span></span>
    
3.  <span data-ttu-id="edf84-130">Dans l'écran **Compte Guides**, cliquez sur le bouton **Modifier** en regard de **Licences de produit**.</span><span class="sxs-lookup"><span data-stu-id="edf84-130">In the **Guides Account** screen, select the **Edit** button next to **Product licenses**.</span></span>

     <span data-ttu-id="edf84-131">![Modifier le plan PowerApps](media/edit-powerapps-plan.PNG "Modifier le plan PowerApps")</span><span class="sxs-lookup"><span data-stu-id="edf84-131">![Edit PowerApps plan](media/edit-powerapps-plan.PNG "Edit PowerApps plan")</span></span>

4.  <span data-ttu-id="edf84-132">Dans l'écran **Licences de produit**, déplacez le curseur **[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]** sur **Activé**, puis sélectionnez **Enregistrer**.</span><span class="sxs-lookup"><span data-stu-id="edf84-132">In the **Product licenses** screen, turn the **[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]** slider to **On**, and then select **Save**.</span></span>
  
    <span data-ttu-id="edf84-133">![Ajouter des licences utilisateur](media/guides-license.PNG "Ajouter des licences utilisateur")</span><span class="sxs-lookup"><span data-stu-id="edf84-133">![Add user license](media/guides-license.PNG "Add user license")</span></span> 
 
## <span data-ttu-id="edf84-134">Étape 2 : Créer un environnement Common Data Service et installer la solution Dynamics 365 Guides<a name="cds"></a></span><span class="sxs-lookup"><span data-stu-id="edf84-134">Step 2: Create a Common Data Service environment and install the Dynamics 365 Guides solution<a name="cds"></a></span></span>

<span data-ttu-id="edf84-135">Après avoir acquis un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et avoir affecté les licences, vous devez créer une base de données dans un environnement implicite dans lequel vous pouvez installer la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="edf84-135">After acquiring a [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] subscription and assigning licenses, you’ll need to create a database on a default environment where you can install the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] solution.</span></span> <span data-ttu-id="edf84-136">Si vous disposez déjà d'un environnement Common Data Service (par exemple, une instance de l'abonnement Dynamics 365 de votre entreprise), vous pouvez passer directement à l'étape [Installation et configuration de la solution Dynamics 365 Guides](#configure).</span><span class="sxs-lookup"><span data-stu-id="edf84-136">If you already have a Common Data Service environment (for example, an instance in your company's Dynamics 365 tenant), you can skip to [Install and configure the Dynamics 365 Guides solution](#configure).</span></span>
    
1.  <span data-ttu-id="edf84-137">Accédez au [Power Platform Centre d'administration](https://admin.powerplatform.microsoft.com/environments) et connectez-vous avec les informations d'identification de l'utilisateur Administrateur (celles liées aux licences [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] affectées).</span><span class="sxs-lookup"><span data-stu-id="edf84-137">Go to the [Power Platform Admin Center](https://admin.powerplatform.microsoft.com/environments) and sign in with the admin user credentials (the one where the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] licenses are assigned).</span></span>

2.  <span data-ttu-id="edf84-138">Dans le Centre d'administration Power Platform, sélectionnez **Environnements**.</span><span class="sxs-lookup"><span data-stu-id="edf84-138">In the Power Platform Admin Center, select **Environments**.</span></span>

    <span data-ttu-id="edf84-139">![Environnements Power Platform](media/powerapps-environments.PNG "Environnements Power Platform ")</span><span class="sxs-lookup"><span data-stu-id="edf84-139">![Power Platform Environments](media/powerapps-environments.PNG "Power Platform Environments")</span></span>
    
3.  <span data-ttu-id="edf84-140">Sélectionnez le bouton **Informations supplémentaires** (...) en regard de l'instance par défaut, puis sélectionnez **Gérer l'environnement**.</span><span class="sxs-lookup"><span data-stu-id="edf84-140">Select the **More information** button (...) next to the default instance, and then select **Manage environment**.</span></span>

    <span data-ttu-id="edf84-141">![Gérer l'environnement](media/powerapps-manage-environment.PNG "Gérer l'environnement")</span><span class="sxs-lookup"><span data-stu-id="edf84-141">![Manage Environment](media/powerapps-manage-environment.PNG "Manage Environment")</span></span>
    
4. <span data-ttu-id="edf84-142">Modifiez le nom de l'environnement (par exemple, Guides_*un nom quelconque*), puis sélectionnez **Créer ma base de données**.</span><span class="sxs-lookup"><span data-stu-id="edf84-142">Change the name of the environment (for example, Guides_*anyname*), and then select **Create my database**.</span></span>

    <span data-ttu-id="edf84-143">![Créer une base de données](media/powerapps-create-database.PNG "Créer une base de données")</span><span class="sxs-lookup"><span data-stu-id="edf84-143">![Create database](media/powerapps-create-database.PNG "Create database")</span></span>
    
5. <span data-ttu-id="edf84-144">Dans la boîte de dialogue suivante, sélectionnez la devise et la langue.</span><span class="sxs-lookup"><span data-stu-id="edf84-144">In the next dialog box, choose your currency and language.</span></span>

    <span data-ttu-id="edf84-145">![Paramètres de devise et de langue](media/currency-language-settings.PNG "Paramètres de devise et de langue")</span><span class="sxs-lookup"><span data-stu-id="edf84-145">![Currency and language settings](media/currency-language-settings.PNG "Currency and language settings")</span></span>
  
6.  <span data-ttu-id="edf84-146">Sélectionnez **Créer une base de données.**</span><span class="sxs-lookup"><span data-stu-id="edf84-146">Select **Create database.**</span></span>

<span data-ttu-id="edf84-147">L'écran suivant s'affiche alors que la base de données est créée et mise en service :</span><span class="sxs-lookup"><span data-stu-id="edf84-147">The following screen appears while the database is being created and provisioned:</span></span>
    
   <span data-ttu-id="edf84-148">![Écran d'approvisionnement de la base de données](media/provisioning-database.PNG "Écran d'approvisionnement de la base de données")</span><span class="sxs-lookup"><span data-stu-id="edf84-148">![Provisioning database screen](media/provisioning-database.PNG "Provisioning database screen")</span></span>
 
   > [!NOTE]
   > <span data-ttu-id="edf84-149">La création de la base de données prend généralement quelques minutes.</span><span class="sxs-lookup"><span data-stu-id="edf84-149">Database creation usually takes several minutes.</span></span> <span data-ttu-id="edf84-150">Si, au bout de 5 minutes, le message « Approvisionnement de la base de données » apparaît toujours, essayez d'actualiser la page.</span><span class="sxs-lookup"><span data-stu-id="edf84-150">If, after 5 minutes, the “Provisioning database” message still appears, try refreshing the page.</span></span>    

7.  <span data-ttu-id="edf84-151">Une fois que la base de données est créée, un lien vers le Centre d'administration Dynamics 365 apparaît.</span><span class="sxs-lookup"><span data-stu-id="edf84-151">After the database is created, a link to the Dynamics 365 Administration Center appears.</span></span> <span data-ttu-id="edf84-152">Sélectionnez ce lien, puis connectez-vous à nouveau avec les informations d'identification que vous avez utilisées lors des étapes précédentes.</span><span class="sxs-lookup"><span data-stu-id="edf84-152">Select this link, and then sign in again with the credentials you used in previous steps.</span></span> <span data-ttu-id="edf84-153">Vous devrez peut-être fermer votre navigateur avant de vous connecter.</span><span class="sxs-lookup"><span data-stu-id="edf84-153">You might need to close your browser before signing in.</span></span> 

    <span data-ttu-id="edf84-154">![Lien Centre d'administration](media/admin-center-link.PNG "Lien Centre d'administration")</span><span class="sxs-lookup"><span data-stu-id="edf84-154">![Admin Center link](media/admin-center-link.PNG "Admin Center link")</span></span>

<span data-ttu-id="edf84-155">Le Centre d'administration Dynamics apparaît.</span><span class="sxs-lookup"><span data-stu-id="edf84-155">The Dynamics Admin Center appears.</span></span> <span data-ttu-id="edf84-156">Il s'agit de l'emplacement où vous pouvez installer la solution et effectuer d'autres configurations.</span><span class="sxs-lookup"><span data-stu-id="edf84-156">This is where you can install the solution and make other configurations.</span></span>

### <span data-ttu-id="edf84-157">Installer et configurer la solution Dynamics 365 Guides<a name="configure"></a></span><span class="sxs-lookup"><span data-stu-id="edf84-157">Install and configure the Dynamics 365 Guides solution<a name="configure"></a></span></span>

<span data-ttu-id="edf84-158">Dans l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] PC, vous pouvez télécharger vos propres fichiers 3D, ainsi que des vidéos et des images 2D.</span><span class="sxs-lookup"><span data-stu-id="edf84-158">In the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] PC application, you can upload your own 3D files, as well as videos and 2D images.</span></span> <span data-ttu-id="edf84-159">La taille de plusieurs de ces fichiers sera supérieure à 5 Mo, vous devrez donc modifier la taille maximale des fichiers qui seront chargés.</span><span class="sxs-lookup"><span data-stu-id="edf84-159">Many of these files will be larger than 5 MB, so you need to change the maximum file size for files that are uploaded.</span></span> <span data-ttu-id="edf84-160">Pour ce faire, vous devrez remplacer le paramètre de la taille de pièce jointe par 128 Mo (131072 Ko).</span><span class="sxs-lookup"><span data-stu-id="edf84-160">To do this, you'll change the setting for the email attachment size to 128 MB (131072 KB).</span></span> 

1.  <span data-ttu-id="edf84-161">Accédez au [Centre d'administration Dynamics 365](https://port.crm.dynamics.com/G/Instances/InstancePicker.aspx), puis connectez-vous avec les informations d'identification disposant des autorisations de l'administrateur pour [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="edf84-161">Go to the [Dynamics 365 Administration Center](https://port.crm.dynamics.com/G/Instances/InstancePicker.aspx) and sign in with the user credentials that have admin permissions for [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span></span> 
    
2.  <span data-ttu-id="edf84-162">Sélectionnez l'instance [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] qui vient d'être créée dans la liste d'instances, puis sélectionnez **Ouvrir** comme indiqué ici :</span><span class="sxs-lookup"><span data-stu-id="edf84-162">Select the newly created [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] instance from the list of instances, and then select **Open** as shown here:</span></span> 
    
    <span data-ttu-id="edf84-163">![Centre d'administration avec le bouton Ouvrir sélectionné](media/admin-center-open-button.PNG "Centre d'administration avec le bouton Ouvrir sélectionné")</span><span class="sxs-lookup"><span data-stu-id="edf84-163">![Admin Center with Open button selected](media/admin-center-open-button.PNG "Admin Center with Open button selected")</span></span>
    
    <span data-ttu-id="edf84-164">Cela ouvre l'écran **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]**.</span><span class="sxs-lookup"><span data-stu-id="edf84-164">This opens the **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]** screen.</span></span>
    
3.  <span data-ttu-id="edf84-165">Dans l'écran **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]**, sélectionnez **Paramètres**, puis sélectionnez **Paramètres avancés**.</span><span class="sxs-lookup"><span data-stu-id="edf84-165">In the **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]** screen, select **Settings**, and then select **Advanced Settings**.</span></span> 

    <span data-ttu-id="edf84-166">![Paramètres avancés](media/advanced-settings.PNG "Paramètres avancés")</span><span class="sxs-lookup"><span data-stu-id="edf84-166">![Advanced Settings](media/advanced-settings.PNG "Advanced Settings")</span></span>
    
4.  <span data-ttu-id="edf84-167">Dans l'écran **[!include[pn-dyn-365](../includes/pn-dyn-365.md)] Gestion d'entreprise**, sélectionnez la liste déroulante **Paramètres**.</span><span class="sxs-lookup"><span data-stu-id="edf84-167">In the **[!include[pn-dyn-365](../includes/pn-dyn-365.md)] Business Management** screen, select the **Settings** drop-down list.</span></span>

     <span data-ttu-id="edf84-168">![Écran2 Gestion d'entreprise](media/business-management.PNG "Écran Gestion d'entreprise")</span><span class="sxs-lookup"><span data-stu-id="edf84-168">![Business Management screen2](media/business-management.PNG "Business Management screen")</span></span>
    
5.  <span data-ttu-id="edf84-169">Sous **Système**, sélectionnez **Administration**.</span><span class="sxs-lookup"><span data-stu-id="edf84-169">Under **System**, select **Administration**.</span></span>

    <span data-ttu-id="edf84-170">![Bouton Administration dans Dynamics 365](media/administration-button.PNG "Bouton Administration dans Dynamics 365")</span><span class="sxs-lookup"><span data-stu-id="edf84-170">![Administration button in Dynamics 365](media/administration-button.PNG "Administration button in Dynamics 365")</span></span>
 
6.  <span data-ttu-id="edf84-171">Dans la page **[!include[pn-dyn-365](../includes/pn-dyn-365.md)] Paramètres > Administration**, sélectionnez **Paramètres système**.</span><span class="sxs-lookup"><span data-stu-id="edf84-171">In the **[!include[pn-dyn-365](../includes/pn-dyn-365.md)] Settings > Administration** page, select **System Settings**.</span></span>

    <span data-ttu-id="edf84-172">![Paramètres système dans Dynamics 365](media/system-settings.PNG "Paramètres système dans Dynamics 365")</span><span class="sxs-lookup"><span data-stu-id="edf84-172">![System settings in Dynamics 365](media/system-settings.PNG "System settings in Dynamics 365")</span></span>
  
7.  <span data-ttu-id="edf84-173">Dans la boîte de dialogue **Paramètres système**, sélectionnez l'onglet **E-mail**, faites défiler l'écran vers le bas de la boîte de dialogue, puis dans le champ **Définir la limite de la taille de fichier pour les pièces jointes**, entrez **131072**.</span><span class="sxs-lookup"><span data-stu-id="edf84-173">In the **System Settings** dialog box, select the **Email** tab, scroll down to the bottom of the dialog box, and then in the **Set file size limits for attachments** field, enter **131072**.</span></span> <span data-ttu-id="edf84-174">Cliquez sur **OK** lorsque vous avez terminé.</span><span class="sxs-lookup"><span data-stu-id="edf84-174">Select **OK** when you’re done.</span></span>

    <span data-ttu-id="edf84-175">![Boîte de dialogue Paramètres système](media/system-settings-dialog-box.PNG "Boîte de dialogue Paramètres système")</span><span class="sxs-lookup"><span data-stu-id="edf84-175">![System settings dialog box](media/system-settings-dialog-box.PNG "System settings dialog box")</span></span>
 
8.  <span data-ttu-id="edf84-176">Revenez dans le [Centre d'administration Dynamics 365](https://port.crm.dynamics.com/G/Instances/InstancePicker.aspx), puis sélectionnez le petit bouton Modifier en regard de **Solutions**.</span><span class="sxs-lookup"><span data-stu-id="edf84-176">Go back to the [Dynamics 365 Administration Center](https://port.crm.dynamics.com/G/Instances/InstancePicker.aspx) and select the small edit button next to **Solutions**.</span></span>

    <span data-ttu-id="edf84-177">![Bouton Modifier Solutions](media/solutions-edit-button.PNG "Bouton Modifier Solutions")</span><span class="sxs-lookup"><span data-stu-id="edf84-177">![Solutions Edit button](media/solutions-edit-button.PNG "Solutions Edit button")</span></span>
 
    > [!NOTE]
    > <span data-ttu-id="edf84-178">Vous pouvez également accéder au Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)] à partir du portail PowerApps.</span><span class="sxs-lookup"><span data-stu-id="edf84-178">You can also get to the [!include[pn-dyn-365](../includes/pn-dyn-365.md)] Administration Center from the PowerApps portal.</span></span>
    
8.  <span data-ttu-id="edf84-179">Sélectionnez la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] dans la liste, puis sélectionnez **Installer**.</span><span class="sxs-lookup"><span data-stu-id="edf84-179">Select the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] solution in the list, and then select **Install**.</span></span> 

    <span data-ttu-id="edf84-180">![Bouton Solutions Installer](media/solutions-install-button.PNG "Bouton Solutions Installer")</span><span class="sxs-lookup"><span data-stu-id="edf84-180">![Solutions Install button](media/solutions-install-button.PNG "Solutions Install button")</span></span>
    
9. <span data-ttu-id="edf84-181">Dans la boîte de dialogue **Conditions d'utilisation**, examinez les conditions, puis sélectionnez **Installer** lorsque vous êtes prêt.</span><span class="sxs-lookup"><span data-stu-id="edf84-181">In the **Terms of Service** dialog box, review the terms, and then select **install** when you're ready.</span></span>

   <span data-ttu-id="edf84-182">Dans l'écran **Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)]**, le message suivant apparaît en surbrillance jaune pour indiquer que la solution est sur le point d'être installée :</span><span class="sxs-lookup"><span data-stu-id="edf84-182">In the **[!include[pn-dyn-365](../includes/pn-dyn-365.md)] Administration Center** screen, you'll see the following message highlighted in yellow showing that the solution is about to be installed:</span></span>

   <span data-ttu-id="edf84-183">![Message d'installation de la solution](media/installing-solution.PNG "Message d'installation de la solution")</span><span class="sxs-lookup"><span data-stu-id="edf84-183">![Solution installing message](media/installing-solution.PNG "Solution installing message")</span></span>
   
   <span data-ttu-id="edf84-184">Le champ **Statut** à gauche du message jaune indique **Installation en attente** lorsque la solution est en cours d'installation.</span><span class="sxs-lookup"><span data-stu-id="edf84-184">The **Status** field to the left of the yellow message will say **Installation pending** while the solution is being installed.</span></span> <span data-ttu-id="edf84-185">Lorsque la solution est installée, le contenu du champ **Statut** est remplacé par **Installé**.</span><span class="sxs-lookup"><span data-stu-id="edf84-185">When the solution has finished installing, the **Status** field changes to **Installed**.</span></span>
 
    > [!NOTE]
    > <span data-ttu-id="edf84-186">Le processus d'installation peut prendre jusqu'à une heure et est variable en fonction du jour et de la région.</span><span class="sxs-lookup"><span data-stu-id="edf84-186">The installation process can take up to one hour and is variable based on the time of day and region.</span></span> <span data-ttu-id="edf84-187">Si le statut n'a pas changé au bout d'une heure, essayez d'actualiser l'écran.</span><span class="sxs-lookup"><span data-stu-id="edf84-187">If the status hasn't changed after an hour, try refreshing your screen.</span></span> <span data-ttu-id="edf84-188">Si l'installation échoue, vous verrez ce message :</span><span class="sxs-lookup"><span data-stu-id="edf84-188">If the installation fails, you'll see this message:</span></span><br><span data-ttu-id="edf84-189">![Échec de l'installation](media/failed-install.PNG "Échec de l'installation")</span><span class="sxs-lookup"><span data-stu-id="edf84-189">![Failed installation](media/failed-install.PNG "Failed installation")</span></span>

### <span data-ttu-id="edf84-190">Paramétrer des rôles d'utilisateur pour la solution<a name="user-roles"></a></span><span class="sxs-lookup"><span data-stu-id="edf84-190">Set up user roles for the solution<a name="user-roles"></a></span></span>

> [!NOTE]
> <span data-ttu-id="edf84-191">L'affichage d'un utilisateur dans le Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)] peut prendre jusqu'à une heure, une fois les licences ajoutées dans le Centre d'administration [!include[cc-microsoft](../includes/cc-microsoft.md)] 365.</span><span class="sxs-lookup"><span data-stu-id="edf84-191">It can take up to one hour for a user to appear in the [!include[pn-dyn-365](../includes/pn-dyn-365.md)] admin center after the licenses are added in the [!include[cc-microsoft](../includes/cc-microsoft.md)] 365 admin center.</span></span> 

1.  <span data-ttu-id="edf84-192">Une fois la solution installée, accédez au [Centre d'administration Dynamics 365](https://port.crm.dynamics.com/G/Instances/InstancePicker.aspx), sélectionnez l'instance [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] qui vient d'être créée dans la liste des instances, puis sélectionnez **Ouvrir**.</span><span class="sxs-lookup"><span data-stu-id="edf84-192">After the solution has finished installing, go to the [Dynamics 365 Administration Center](https://port.crm.dynamics.com/G/Instances/InstancePicker.aspx), select the newly created [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] instance from the list of instances, and then select **Open**.</span></span>

2. <span data-ttu-id="edf84-193">Sur la page **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]**, sélectionnez **Paramètres**, puis sélectionnez **Paramètres avancés**.</span><span class="sxs-lookup"><span data-stu-id="edf84-193">On the **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]** page, select **Settings**, and then select **Advanced Settings**.</span></span>

    <span data-ttu-id="edf84-194">![Paramètres avancés Dynamics 365](media/roles-advanced-settings.PNG "Paramètres avancés Dynamics 365")</span><span class="sxs-lookup"><span data-stu-id="edf84-194">![Dynamics 365 Advanced Settings](media/roles-advanced-settings.PNG "Dynamics 365 Advanced Settings")</span></span>
    
    > [!IMPORTANT]
    > <span data-ttu-id="edf84-195">Vous pouvez accéder aux données [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] via la vignette Guides Hub de l'écran précédent, mais nous déconseillons d'effectuer des modifications dans Guides Hub.</span><span class="sxs-lookup"><span data-stu-id="edf84-195">You can access [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] data through the Guides Hub tile in the preceding screen, but we recommend that you not make any changes in the Guides Hub.</span></span> <span data-ttu-id="edf84-196">Toute modification apportée peut avoir des conséquences imprévues pour les applications [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="edf84-196">Any changes you make can have unintended consequences for the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] apps.</span></span>
 
3.   <span data-ttu-id="edf84-197">Dans l'écran **[!include[pn-dyn-365](../includes/pn-dyn-365.md)] > Gestion d'entreprise**, sélectionnez la liste déroulante **Paramètres**.</span><span class="sxs-lookup"><span data-stu-id="edf84-197">In the **[!include[pn-dyn-365](../includes/pn-dyn-365.md)] > Business Management** screen, select the **Settings** drop-down list.</span></span>
    
     <span data-ttu-id="edf84-198">![Écran2 Gestion d'entreprise](media/business-management.PNG "Écran Gestion d'entreprise")</span><span class="sxs-lookup"><span data-stu-id="edf84-198">![Business Management screen2](media/business-management.PNG "Business Management screen")</span></span>

4.  <span data-ttu-id="edf84-199">Sur la page **[!include[pn-dyn-365](../includes/pn-dyn-365.md)] Paramètres** > **Administration**, sous **Système**, sélectionnez **Sécurité**.</span><span class="sxs-lookup"><span data-stu-id="edf84-199">On the **[!include[pn-dyn-365](../includes/pn-dyn-365.md)] Settings** > **Administration** page, under **System**, select **Security**.</span></span> 

    <span data-ttu-id="edf84-200">![Paramètre de sécurité Dynamics 365](media/security-setting.PNG "Paramètre de sécurité Dynamics 365")</span><span class="sxs-lookup"><span data-stu-id="edf84-200">![Dynamics 365 Security setting](media/security-setting.PNG "Dynamics 365 Security setting")</span></span>
 
5.  <span data-ttu-id="edf84-201">Dans la page **Sécurité**, sélectionnez **Utilisateurs**.</span><span class="sxs-lookup"><span data-stu-id="edf84-201">On the **Security** page, select **Users**.</span></span>

    <span data-ttu-id="edf84-202">![Paramètre Utilisateurs Dynamics 365](media/select-users.PNG "Paramètre Utilisateurs Dynamics 365")</span><span class="sxs-lookup"><span data-stu-id="edf84-202">![Dynamics 365 Users setting](media/select-users.PNG "Dynamics 365 Users setting")</span></span>
 
6.  <span data-ttu-id="edf84-203">Sélectionnez l'utilisateur, puis sélectionnez **Gérer les rôles**.</span><span class="sxs-lookup"><span data-stu-id="edf84-203">Select the user, and then select **Manage** roles.</span></span> 

    <span data-ttu-id="edf84-204">![Commande Gérer les rôles](media/manage-roles-command.PNG "Commande Gérer les rôles")</span><span class="sxs-lookup"><span data-stu-id="edf84-204">![Manage Roles command](media/manage-roles-command.PNG "Manage Roles command")</span></span>
 
7.  <span data-ttu-id="edf84-205">Dans la boîte de dialogue **Gérer les rôles d'utilisateurs**, sélectionnez les rôles suivants :</span><span class="sxs-lookup"><span data-stu-id="edf84-205">In the **Manage User Roles** dialog box, select the following roles:</span></span> 

    - <span data-ttu-id="edf84-206">Utilisateur Common Data Service</span><span class="sxs-lookup"><span data-stu-id="edf84-206">Common Data Service User</span></span>
    
    - <span data-ttu-id="edf84-207">Auteur [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]</span><span class="sxs-lookup"><span data-stu-id="edf84-207">[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] Author</span></span>
    
    - <span data-ttu-id="edf84-208">Administrateur système</span><span class="sxs-lookup"><span data-stu-id="edf84-208">System Administrator</span></span> 
       
      <span data-ttu-id="edf84-209">![Boîte de dialogue Gérer les rôles renseignée](media/manage-roles-dialog-box.PNG "Boîte de dialogue Gérer les rôles renseignée")</span><span class="sxs-lookup"><span data-stu-id="edf84-209">![Manage Roles dialog box filled in](media/manage-roles-dialog-box.PNG "Manage Roles dialog box filled in")</span></span>
      
      > [!NOTE]
      > <span data-ttu-id="edf84-210">Sélectionnez le rôle Administrateur système s'il s'agit de l'utilisateur principal/de l'administrateur. Sinon, ne sélectionnez pas ce rôle.</span><span class="sxs-lookup"><span data-stu-id="edf84-210">Select the System Administrator role if this is the main user/admin. Otherwise, do not select that role.</span></span> 
     
## <a name="step-3-download-and-install-the-apps"></a><span data-ttu-id="edf84-211">Étape 3 : Télécharger et installer les applications.</span><span class="sxs-lookup"><span data-stu-id="edf84-211">Step 3: Download and install the apps</span></span>

<span data-ttu-id="edf84-212">Il y a deux applications [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] :</span><span class="sxs-lookup"><span data-stu-id="edf84-212">There are two [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] applications:</span></span> 

- <span data-ttu-id="edf84-213">Application de création de l'ordinateur de bureau</span><span class="sxs-lookup"><span data-stu-id="edf84-213">Desktop authoring application</span></span>

- <span data-ttu-id="edf84-214">Application [!include[pn-hololens](../includes/pn-hololens.md)], avec un mode Créer et un mode Opérateur</span><span class="sxs-lookup"><span data-stu-id="edf84-214">[!include[pn-hololens](../includes/pn-hololens.md)] application, which has an Author mode and an Operator mode</span></span>

<span data-ttu-id="edf84-215">Vous pouvez installer les deux applications à partir de [!include[cc-microsoft](../includes/cc-microsoft.md)] Store tel que décrit dans la section suivante.</span><span class="sxs-lookup"><span data-stu-id="edf84-215">You can install both apps from [!include[cc-microsoft](../includes/cc-microsoft.md)] Store as described in the next section.</span></span>

> [!NOTE]
> <span data-ttu-id="edf84-216">Si vous ne pouvez pas accéder à [!include[cc-microsoft](../includes/cc-microsoft.md)] Store en raison de politiques d'entreprise, contactez votre administrateur pour qu'il distribue l'application.</span><span class="sxs-lookup"><span data-stu-id="edf84-216">If you can’t access [!include[cc-microsoft](../includes/cc-microsoft.md)] Store due to company policies, please contact your administrator to distribute the app.</span></span>

<span data-ttu-id="edf84-217">Si vous utilisez [!include[cc-microsoft](../includes/cc-microsoft.md)] Store pour Entreprises pour distribuer vos applications, les utilisateurs peuvent les installer à partir du magasin privé de votre organisation ou d'un lien que vous leur envoyez par e-mail.</span><span class="sxs-lookup"><span data-stu-id="edf84-217">If you use [!include[cc-microsoft](../includes/cc-microsoft.md)] Store for Business to distribute your apps, you can have users install the apps from your organization’s private store or from an email link that you send.</span></span> <span data-ttu-id="edf84-218">Les instructions sont fournies plus loin dans cette rubrique.</span><span class="sxs-lookup"><span data-stu-id="edf84-218">Instructions are provided later in this topic.</span></span>

### <a name="install-the-apps-from-microsoft-store"></a><span data-ttu-id="edf84-219">Installer les applications à partir de Microsoft Store</span><span class="sxs-lookup"><span data-stu-id="edf84-219">Install the apps from Microsoft Store</span></span>

#### <a name="install-the-pc-authoring-app"></a><span data-ttu-id="edf84-220">Installer l'application de création sur PC</span><span class="sxs-lookup"><span data-stu-id="edf84-220">Install the PC authoring app</span></span> 
1.  <span data-ttu-id="edf84-221">Assurez-vous que votre [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC exécute la dernière version de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] (doit correspondre à la version 10.0.17134, mise à jour d’avril 2018 ou ultérieure).</span><span class="sxs-lookup"><span data-stu-id="edf84-221">Check to make sure your [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC is running the latest [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] build (must be build 10.0.17134, April 2018 update, or later).</span></span>

2.  <span data-ttu-id="edf84-222">Sur votre PC, allez dans **Démarrer** ![Bouton Démarrer](media/windows-button.png "Bouton Démarrer") > **[!include[cc-microsoft](../includes/cc-microsoft.md)] Store** ![Bouton Store](media/store-button.png "Bouton Store"), puis recherchez [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="edf84-222">On your PC, go to **Start** ![Start button](media/windows-button.png "Start button") > **[!include[cc-microsoft](../includes/cc-microsoft.md)] Store** ![Store button](media/store-button.png "Store button"), and then search for “[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].”</span></span>

3.  <span data-ttu-id="edf84-223">Dans [!include[cc-microsoft](../includes/cc-microsoft.md)] Store, sélectionnez **Obtenir** en regard de l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] pour la télécharger et l'installer.</span><span class="sxs-lookup"><span data-stu-id="edf84-223">In [!include[cc-microsoft](../includes/cc-microsoft.md)] Store, select **Get** for the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] app to download, and install the application.</span></span>

    <span data-ttu-id="edf84-224">![Application dans Microsoft Store](media/app.PNG "Application dans Microsoft Store")</span><span class="sxs-lookup"><span data-stu-id="edf84-224">![App in Microsoft Store](media/app.PNG "App in Microsoft Store")</span></span>

    > [!NOTE]
    > <span data-ttu-id="edf84-225">Pour obtenir des instructions sur l'ouverture et la connexion à l'application, voir [Création de guide](authoring-overview.md).</span><span class="sxs-lookup"><span data-stu-id="edf84-225">For instructions on opening and signing in to the app, see the [authoring guide](authoring-overview.md).</span></span>

#### <a name="install-the-hololens-app"></a><span data-ttu-id="edf84-226">Installer l'application HoloLens</span><span class="sxs-lookup"><span data-stu-id="edf84-226">Install the HoloLens app</span></span>

1.  <span data-ttu-id="edf84-227">Assurez-vous qu'[!include[pn-hololens](../includes/pn-hololens.md)] exécute la version 10.0.17134 ou ultérieure.</span><span class="sxs-lookup"><span data-stu-id="edf84-227">Make sure [!include[pn-hololens](../includes/pn-hololens.md)] is running build 10.0.17134 or later.</span></span> <span data-ttu-id="edf84-228">Nous vous recommandons de mettre à jour [!include[pn-hololens](../includes/pn-hololens.md)] vers des versions plus récentes quand elles sont disponibles.</span><span class="sxs-lookup"><span data-stu-id="edf84-228">We recommend updating [!include[pn-hololens](../includes/pn-hololens.md)] to newer versions when available.</span></span> <span data-ttu-id="edf84-229">Voir [Gérer les mises à jour vers HoloLens](https://docs.microsoft.com/HoloLens/hololens-updates) pour obtenir des instructions sur l'utilisation de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Update pour Entreprise.</span><span class="sxs-lookup"><span data-stu-id="edf84-229">See [Manage updates to HoloLens](https://docs.microsoft.com/HoloLens/hololens-updates) for instructions on using [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Update for Business.</span></span>

2.  <span data-ttu-id="edf84-230">Dans [!include[pn-hololens](../includes/pn-hololens.md)], utilisez l'écartement des doigts paume vers le haut pour ouvrir le menu **Accueil**, puis ouvrez l'application [!include[cc-microsoft](../includes/cc-microsoft.md)] Store et recherchez [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="edf84-230">On your [!include[pn-hololens](../includes/pn-hololens.md)], use the bloom gesture to open the **Home** menu, and then open the [!include[cc-microsoft](../includes/cc-microsoft.md)] Store app and search for “[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]”.</span></span>

3.  <span data-ttu-id="edf84-231">Sélectionnez **Installer** pour télécharger et installer l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="edf84-231">Select **Install** to download and install the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] application.</span></span>

> [!NOTE] 
> <span data-ttu-id="edf84-232">Pour obtenir des instructions sur l'ouverture et la connexion à l'application, si vous êtes un auteur, consultez la [rubrique de création HoloLens](hololens-authoring.md).</span><span class="sxs-lookup"><span data-stu-id="edf84-232">For instructions on opening and signing in to the app, if you're an author, see the [HoloLens authoring topic](hololens-authoring.md).</span></span> <span data-ttu-id="edf84-233">Les opérateurs peuvent utiliser le [manuel de l'opérateur Dynamics 365 Guides](operator-guide.md).</span><span class="sxs-lookup"><span data-stu-id="edf84-233">Operators can use the [Dynamics 365 Guides Operator's manual](operator-guide.md).</span></span>

### <a name="distribute-the-apps-through-the-microsoft-store-for-business"></a><span data-ttu-id="edf84-234">Distribuer les applications via Microsoft Store pour Entreprises</span><span class="sxs-lookup"><span data-stu-id="edf84-234">Distribute the apps through the Microsoft Store for Business</span></span>

1.  <span data-ttu-id="edf84-235">Allez à [Microsoft Store pour Entreprises](https://businessstore.microsoft.com/store).</span><span class="sxs-lookup"><span data-stu-id="edf84-235">Go to [Microsoft Store for Business](https://businessstore.microsoft.com/store).</span></span>

2.  <span data-ttu-id="edf84-236">[Faites l'acquisition de la ou des applications](https://docs.microsoft.com/microsoft-store/acquire-apps-microsoft-store-for-business).</span><span class="sxs-lookup"><span data-stu-id="edf84-236">[Acquire the app(s)](https://docs.microsoft.com/microsoft-store/acquire-apps-microsoft-store-for-business).</span></span>

3.  <span data-ttu-id="edf84-237">Choisissez l'une des méthodes de distribution suivantes :</span><span class="sxs-lookup"><span data-stu-id="edf84-237">Choose one of the following distribution methods:</span></span>

    - [<span data-ttu-id="edf84-238">Magasin privé</span><span class="sxs-lookup"><span data-stu-id="edf84-238">Private store</span></span>](https://docs.microsoft.com/microsoft-store/distribute-apps-from-your-private-store)
    
    - [<span data-ttu-id="edf84-239">Lien de courrier électronique</span><span class="sxs-lookup"><span data-stu-id="edf84-239">Email link</span></span>](https://docs.microsoft.com/microsoft-store/assign-apps-to-employees)
    
    - [<span data-ttu-id="edf84-240">Gestion des périphériques mobiles</span><span class="sxs-lookup"><span data-stu-id="edf84-240">Mobile device management</span></span>](https://docs.microsoft.com/microsoft-store/configure-mdm-provider-microsoft-store-for-business)

<span data-ttu-id="edf84-241">Pour plus d'informations sur l'ouverture et la connexion à l'application du PC après l'avoir installée, voir [Création de guide](authoring-overview.md).</span><span class="sxs-lookup"><span data-stu-id="edf84-241">For information on opening and signing in to the PC application after installing it, see the [authoring guide](authoring-overview.md).</span></span>

<span data-ttu-id="edf84-242">Pour plus d'informations sur l'ouverture et la connexion à l'application [!include[pn-hololens](../includes/pn-hololens.md)], accédez à l'une des options suivantes, selon que vous êtes auteur ou opérateur :</span><span class="sxs-lookup"><span data-stu-id="edf84-242">For information on opening and signing in to the [!include[pn-hololens](../includes/pn-hololens.md)] application, go to one of the following, depending on whether you're an author or an operator:</span></span>

   - [<span data-ttu-id="edf84-243">Création HoloLens</span><span class="sxs-lookup"><span data-stu-id="edf84-243">HoloLens authoring</span></span>](hololens-authoring.md)
   
   - [<span data-ttu-id="edf84-244">Manuel de l'opérateur</span><span class="sxs-lookup"><span data-stu-id="edf84-244">Operator's manual</span></span>](operator-guide.md)

## <a name="step-4-set-up-guides-analytics-reports"></a><span data-ttu-id="edf84-245">Étape 4 : Paramétrer les états d'Analyses de Guides</span><span class="sxs-lookup"><span data-stu-id="edf84-245">Step 4: Set up Guides Analytics reports</span></span> 

[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] <span data-ttu-id="edf84-246">inclut des états [!include[pn-power-bi](../includes/pn-power-bi.md)] (appelés Analyses de Guides) qui permettent d'analyser les processus des guides.</span><span class="sxs-lookup"><span data-stu-id="edf84-246">includes [!include[pn-power-bi](../includes/pn-power-bi.md)] reports (called Guides Analytics) that you can use to analyze guides processes.</span></span> <span data-ttu-id="edf84-247">Suivez les instructions pour savoir comment [ouvrir Analyses de Guides](https://docs.microsoft.com/en-us/dynamics365/mixed-reality/guides/analytics-guide#open-guides-analytics) en utilisant l'[application Power BI Desktop](https://powerbi.microsoft.com/get-started/) disponible gratuitement.</span><span class="sxs-lookup"><span data-stu-id="edf84-247">Follow the instructions for how to [Open Guides Analytics](https://docs.microsoft.com/en-us/dynamics365/mixed-reality/guides/analytics-guide#open-guides-analytics) using the freely available [Power BI Desktop application](https://powerbi.microsoft.com/get-started/).</span></span>

<span data-ttu-id="edf84-248">Si vous disposez d'une licence [!include[pn-power-bi](../includes/pn-power-bi.md)] Pro, vous pouvez partager vos états d'Analyses de Guides [!include[pn-power-bi](../includes/pn-power-bi.md)] au sein de votre organisation en les publiant dans le service [!include[pn-power-bi](../includes/pn-power-bi.md)].</span><span class="sxs-lookup"><span data-stu-id="edf84-248">If you have a [!include[pn-power-bi](../includes/pn-power-bi.md)] Pro license, you can share your Guides Analytics [!include[pn-power-bi](../includes/pn-power-bi.md)] reports within your organization by publishing them to the [!include[pn-power-bi](../includes/pn-power-bi.md)] Service.</span></span> <span data-ttu-id="edf84-249">Cela permet à toute personne de votre organisation ayant une licence Pro [!include[pn-power-bi](../includes/pn-power-bi.md)] d'accéder à l'état via l'interface Web du service [!include[pn-power-bi](../includes/pn-power-bi.md)] accessible sur [https://powerbi.microsoft.com](https://powerbi.microsoft.com).</span><span class="sxs-lookup"><span data-stu-id="edf84-249">This allows anyone in your organization with a [!include[pn-power-bi](../includes/pn-power-bi.md)] Pro license to access the report through the [!include[pn-power-bi](../includes/pn-power-bi.md)] Service web interface accessible at [https://powerbi.microsoft.com](https://powerbi.microsoft.com).</span></span> <span data-ttu-id="edf84-250">Pour en savoir plus sur la collaboration sur le cloud de [!include[pn-power-bi](../includes/pn-power-bi.md)] et le partage, ainsi que l'inscription à une version d'essai gratuit de [!include[pn-power-bi](../includes/pn-power-bi.md)] Pro, consultez [Getting Started with Power BI Desktop](https://powerbi.microsoft.com/en-us/get-started/) et [Ways to share your work in Power BI](https://docs.microsoft.com/en-us/power-bi/service-how-to-collaborate-distribute-dashboards-reports).</span><span class="sxs-lookup"><span data-stu-id="edf84-250">To learn about [!include[pn-power-bi](../includes/pn-power-bi.md)] cloud collaboration and sharing and to sign up for a free trial of [!include[pn-power-bi](../includes/pn-power-bi.md)] Pro, visit [Getting Started with Power BI Desktop](https://powerbi.microsoft.com/en-us/get-started/) and [Ways to share your work in Power BI](https://docs.microsoft.com/en-us/power-bi/service-how-to-collaborate-distribute-dashboards-reports).</span></span>

## <span data-ttu-id="edf84-251">Étape 5 : Ajouter des comptes d'utilisateur supplémentaires (facultatif)<a name="user-accounts"></a></span><span class="sxs-lookup"><span data-stu-id="edf84-251">Step 5: Add additional user accounts (optional)<a name="user-accounts"></a></span></span>

<span data-ttu-id="edf84-252">Pour ajouter des utilisateurs supplémentaires, vous devez leur affecter la licence [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] dans le Centre d'administration Microsoft 365 et configurer les rôles dans le portail d'administrateur Microsoft Dynamics 365.</span><span class="sxs-lookup"><span data-stu-id="edf84-252">If you want to add additional users, you need to assign the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] license to them in the Microsoft 365 Admin Center and configure roles in the Dynamics 365 admin portal.</span></span>

### <a name="add-a-user-account"></a><span data-ttu-id="edf84-253">Ajouter un compte d'utilisateur</span><span class="sxs-lookup"><span data-stu-id="edf84-253">Add a user account</span></span>

1.  <span data-ttu-id="edf84-254">Accédez à [Centre d'administration Microsoft 365](https://admin.microsoft.com/AdminPortal/Home).</span><span class="sxs-lookup"><span data-stu-id="edf84-254">Go to the [Microsoft 365 Admin Center](https://admin.microsoft.com/AdminPortal/Home).</span></span>

2.  <span data-ttu-id="edf84-255">Sélectionnez les comptes d'utilisateur.</span><span class="sxs-lookup"><span data-stu-id="edf84-255">Select user accounts.</span></span>

3. <span data-ttu-id="edf84-256">Affectez-leur la licence [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="edf84-256">Assign the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] license to them.</span></span> 

4. <span data-ttu-id="edf84-257">Développez la section **Licences de produit**, puis déplacez le curseur **[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]** sur **Activé**.</span><span class="sxs-lookup"><span data-stu-id="edf84-257">Expand the **Product licenses** section, and then turn the **[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]** slider to **On**.</span></span> <span data-ttu-id="edf84-258">Vous pouvez affecter jusqu'à 25 utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="edf84-258">You can assign up to 25 users.</span></span>
    
      <span data-ttu-id="edf84-259">![Boîte de dialogue Licences de produits](media/new-user-plans.PNG "Boîte de dialogue Licences de produits")</span><span class="sxs-lookup"><span data-stu-id="edf84-259">![Product Licenses dialog box](media/new-user-plans.PNG "Product Licenses dialog box")</span></span>
 
5.  <span data-ttu-id="edf84-260">Sélectionnez **Enregistrer** une fois terminé.</span><span class="sxs-lookup"><span data-stu-id="edf84-260">Select **Save** when you’re done.</span></span>    

6. <span data-ttu-id="edf84-261">[Paramétrez des rôles d'utilisateur pour la solution](#user-roles) comme décrit précédemment dans cette rubrique.</span><span class="sxs-lookup"><span data-stu-id="edf84-261">[Set up user roles for the solution](#user-roles) as described earlier in this topic.</span></span>

### <a name="see-also"></a><span data-ttu-id="edf84-262">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="edf84-262">See also</span></span>

[<span data-ttu-id="edf84-263">Mise en route d'Dynamics 365 Guides</span><span class="sxs-lookup"><span data-stu-id="edf84-263">Get started with Dynamics 365 Guides</span></span>](get-started.md)<br>
[<span data-ttu-id="edf84-264">Créer un guide</span><span class="sxs-lookup"><span data-stu-id="edf84-264">Author a guide</span></span>](authoring-overview.md)<br>
[<span data-ttu-id="edf84-265">Manuel de l'opérateur</span><span class="sxs-lookup"><span data-stu-id="edf84-265">Operator's manual</span></span>](operator-guide.md)<br>
[<span data-ttu-id="edf84-266">Analyser les guides pour rendre les processus plus efficaces</span><span class="sxs-lookup"><span data-stu-id="edf84-266">Analyze your guides to improve process efficiencies</span></span>](analytics-guide.md)<br>
[<span data-ttu-id="edf84-267">FAQ</span><span class="sxs-lookup"><span data-stu-id="edf84-267">FAQ</span></span>](faq.md)






