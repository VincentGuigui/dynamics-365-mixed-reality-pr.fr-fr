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
# <a name="sign-up-for-dynamics-365-guides-preview"></a><span data-ttu-id="040c5-103">S'inscrire à Dynamics 365 Guides (version préliminaire)</span><span class="sxs-lookup"><span data-stu-id="040c5-103">Sign up for Dynamics 365 Guides (Preview)</span></span>

[!INCLUDE [cc-beta-prerelease-disclaimer](../includes/cc-beta-prerelease-disclaimer.md)]
 
<span data-ttu-id="040c5-104">Nous sommes heureux d'annoncer l'arrivée de [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)] !</span><span class="sxs-lookup"><span data-stu-id="040c5-104">We're thrilled to introduce [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)]!</span></span> <span data-ttu-id="040c5-105">[En savoir plus sur les fonctionnalités de Guides](index.md).</span><span class="sxs-lookup"><span data-stu-id="040c5-105">[Learn about Guides capabilities](index.md).</span></span>

<span data-ttu-id="040c5-106">Pour démarrer avec [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous devez :</span><span class="sxs-lookup"><span data-stu-id="040c5-106">To get started with [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], you need to:</span></span>

1.  <span data-ttu-id="040c5-107">Vous inscrire à la version préliminaire.</span><span class="sxs-lookup"><span data-stu-id="040c5-107">Sign up for the preview.</span></span>

2.  <span data-ttu-id="040c5-108">Créer un environnement Common Data Service, si vous n'en avez pas encore.</span><span class="sxs-lookup"><span data-stu-id="040c5-108">Create a Common Data Service environment, if you don't already have one.</span></span>

3. <span data-ttu-id="040c5-109">Installer la solution [!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)].</span><span class="sxs-lookup"><span data-stu-id="040c5-109">Install the [!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)] solution.</span></span>

4.  <span data-ttu-id="040c5-110">Télécharger et installer les applications [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] sur un [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC et [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-hololens](../includes/pn-hololens.md)].</span><span class="sxs-lookup"><span data-stu-id="040c5-110">Download and install the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] apps on a [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC and [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-hololens](../includes/pn-hololens.md)].</span></span>

5. <span data-ttu-id="040c5-111">Ajouter des comptes d'utilisateur supplémentaires (facultatif).</span><span class="sxs-lookup"><span data-stu-id="040c5-111">Add additional user accounts (optional).</span></span>

6. <span data-ttu-id="040c5-112">Paramétrer les états d'Analyses de Guides.</span><span class="sxs-lookup"><span data-stu-id="040c5-112">Set up Guides Analytics reports.</span></span>

<span data-ttu-id="040c5-113">Cette rubrique fournit des instructions détaillées pour tout ce qui précède.</span><span class="sxs-lookup"><span data-stu-id="040c5-113">This topic provides step-by-step instructions for all of the above.</span></span>

## <a name="step-1-sign-up-for-the-preview"></a><span data-ttu-id="040c5-114">Étape 1 : S'inscrire à la version préliminaire</span><span class="sxs-lookup"><span data-stu-id="040c5-114">Step 1: Sign up for the preview</span></span>

- <span data-ttu-id="040c5-115">Accédez à la page [Mise en route](http://aka.ms/GetGuides), puis suivez les instructions pour créer vos informations d'identification utilisateur pour la version préliminaire.</span><span class="sxs-lookup"><span data-stu-id="040c5-115">Go to [the Getting started page](http://aka.ms/GetGuides), and then follow the instructions to create your user credentials for the preview.</span></span> <span data-ttu-id="040c5-116">Une fois que vous avez vos informations d'identification, revenez sur cette page et cliquez sur [Étape 2 : Créer un environnement Common Data Service](#cds).</span><span class="sxs-lookup"><span data-stu-id="040c5-116">After you have your credentials, come back to this page and go to [Step 2: Create a Common Data Service environment](#cds).</span></span>

    > [!IMPORTANT] 
    > <span data-ttu-id="040c5-117">Nous vous recommandons de créer des informations d'identification utilisateur pour la version préliminaire même si vous avez déjà un compte professionnel.</span><span class="sxs-lookup"><span data-stu-id="040c5-117">We recommend creating user credentials for the preview even if you have an existing work account.</span></span> <span data-ttu-id="040c5-118">Si vous n'êtes pas administrateur de l'organisation, vous ne pourrez pas effectuer les étapes 2 et 3.</span><span class="sxs-lookup"><span data-stu-id="040c5-118">If you're not an admin in the organization, you won't be able to complete Steps 2 and 3.</span></span> <span data-ttu-id="040c5-119">En outre, une fois invité à entrer un nom de domaine, n'utilisez pas votre domaine professionnel.</span><span class="sxs-lookup"><span data-stu-id="040c5-119">Also, when asked to enter a domain name, don't use your normal work domain.</span></span> <span data-ttu-id="040c5-120">Créez un nouveau domaine dans l'écran : \**guides*YourCompanyName\*\*\*.</span><span class="sxs-lookup"><span data-stu-id="040c5-120">Create a new domain in the form: \**guides*YourCompanyName\*\*\*.</span></span>
 
## <span data-ttu-id="040c5-121">Étape 2 : Créer un environnement Common Data Service<a name="cds"></a></span><span class="sxs-lookup"><span data-stu-id="040c5-121">Step 2: Create a Common Data Service environment<a name="cds"></a></span></span>

<span data-ttu-id="040c5-122">Une fois l'inscription à la version préliminaire effectuée, vous devez créer un environnement dans lequel installer la solution [!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)].</span><span class="sxs-lookup"><span data-stu-id="040c5-122">After signing up for the preview, you’ll need to create an environment where you can install the [!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)] solution.</span></span> <span data-ttu-id="040c5-123">Si vous avez déjà un environnement Common Data Service, vous pouvez passer à l'[Étape 3 : Installation et configuration de la solution Dynamics 365 Guides](#configure).</span><span class="sxs-lookup"><span data-stu-id="040c5-123">If you already have a Common Data Service environment, you can skip to [Step 3: Install and configure the Dynamics 365 Guides solution](#configure).</span></span>

1.   <span data-ttu-id="040c5-124">Accédez à [Centre d'administration Microsoft 365](https://admin.microsoft.com/AdminPortal/Home).</span><span class="sxs-lookup"><span data-stu-id="040c5-124">Go to the [Microsoft 365 Admin Center](https://admin.microsoft.com/AdminPortal/Home).</span></span>


2.  <span data-ttu-id="040c5-125">Assurez-vous que la licence Dynamics 365 Guides est affectée à un utilisateur.</span><span class="sxs-lookup"><span data-stu-id="040c5-125">Make sure that the Dynamics 365 Guides license is assigned to a user.</span></span> <span data-ttu-id="040c5-126">Pour cela, dans le volet gauche, sélectionnez **Utilisateurs**, **Utilisateurs actifs**, puis activez la case à cocher en regard de l'utilisateur à ajouter.</span><span class="sxs-lookup"><span data-stu-id="040c5-126">To do that, in the left pane, select **Users**, select **Active users**, and then select the check box for the user you want to add.</span></span> 

    <span data-ttu-id="040c5-127">![Écran Utilisateurs > Utilisateurs actifs](media/users-active-users.PNG "Écran Utilisateurs > Utilisateurs actifs")</span><span class="sxs-lookup"><span data-stu-id="040c5-127">![Users > Active Users screen](media/users-active-users.PNG "Users > Active Users screen")</span></span>
    
3.  <span data-ttu-id="040c5-128">Dans l'écran **Compte Guides**, cliquez sur le bouton **Modifier** en regard de **Licences de produit**.</span><span class="sxs-lookup"><span data-stu-id="040c5-128">In the **Guides Account** screen, select the **Edit** button next to **Product licenses**.</span></span>

     <span data-ttu-id="040c5-129">![Modifier le plan PowerApps](media/edit-powerapps-plan.PNG "Modifier le plan PowerApps")</span><span class="sxs-lookup"><span data-stu-id="040c5-129">![Edit PowerApps plan](media/edit-powerapps-plan.PNG "Edit PowerApps plan")</span></span>


4.  <span data-ttu-id="040c5-130">Dans l'écran **Licences de produit**, déplacez le curseur **Dynamics 365 Guides** sur **Activé**, puis sélectionnez **Enregistrer**.</span><span class="sxs-lookup"><span data-stu-id="040c5-130">In the **Product licenses** screen, turn the **Dynamics 365 Guides** slider to **On**, and then select **Save**.</span></span>
  
    <span data-ttu-id="040c5-131">![Ajouter des licences utilisateur](media/guides-license.PNG "Ajouter des licences utilisateur")</span><span class="sxs-lookup"><span data-stu-id="040c5-131">![Add user license](media/guides-license.PNG "Add user license")</span></span>
    
5.  <span data-ttu-id="040c5-132">Accédez à [Centre d'administration PowerApps](https://preview.admin.powerapps.com/environments), puis connectez-vous avec les informations d'identification utilisateur fournies lorsque vous vous êtes inscrit à la version préliminaire.</span><span class="sxs-lookup"><span data-stu-id="040c5-132">Go to the [PowerApps Admin Center](https://preview.admin.powerapps.com/environments), and sign in with the user credentials provided when you signed up for the preview.</span></span>

6.  <span data-ttu-id="040c5-133">Sélectionnez **Nouvel environnement** dans le centre d'administration PowerApps.</span><span class="sxs-lookup"><span data-stu-id="040c5-133">In the PowerApps Admin Center, select **New environment**.</span></span>

    <span data-ttu-id="040c5-134">![Centre d'administration PowerApps](media/powerapps-environment.PNG "Centre d'administration PowerApps")</span><span class="sxs-lookup"><span data-stu-id="040c5-134">![PowerApps Admin Center](media/powerapps-environment.PNG "PowerApps Admin Center")</span></span>
 
7.  <span data-ttu-id="040c5-135">Renseignez les détails suivants pour l'environnement :</span><span class="sxs-lookup"><span data-stu-id="040c5-135">Fill in the following details for the environment:</span></span>

    -   <span data-ttu-id="040c5-136">**Nom de l'environnement :** Guides_*anyname*</span><span class="sxs-lookup"><span data-stu-id="040c5-136">**Environment name:** Guides_*anyname*</span></span>
    -   <span data-ttu-id="040c5-137">**Région :** Ne pas modifier - **conserver les paramètres par défaut**</span><span class="sxs-lookup"><span data-stu-id="040c5-137">**Region:** Don't change - **keep the default setting**</span></span>
    -   <span data-ttu-id="040c5-138">**Type d'environnement :** Définissez-le sur **Production**</span><span class="sxs-lookup"><span data-stu-id="040c5-138">**Environment type:** Set it to **Production**</span></span>
  
        <span data-ttu-id="040c5-139">![Boîte de dialogue Nouvel environnement](media/new-environment-dialog.PNG "Boîte de dialogue Nouvel environnement")</span><span class="sxs-lookup"><span data-stu-id="040c5-139">![New Environment dialog box](media/new-environment-dialog.PNG "New Environment dialog box")</span></span>
        
    > [!NOTE]
    > <span data-ttu-id="040c5-140">Définissez **Type d'environnement** sur **Production**.</span><span class="sxs-lookup"><span data-stu-id="040c5-140">Make sure to set **Environment type** to **Production**.</span></span> <span data-ttu-id="040c5-141">Ne le définissez pas sur **Essai**.</span><span class="sxs-lookup"><span data-stu-id="040c5-141">Do not set it to **Trial**.</span></span>
    
8.  <span data-ttu-id="040c5-142">Cliquez sur le bouton **Créer un environnement**.</span><span class="sxs-lookup"><span data-stu-id="040c5-142">Select the **Create environment** button.</span></span> 

9.  <span data-ttu-id="040c5-143">Dans la boîte de dialogue qui apparaît, sélectionnez **Créer une base de données**.</span><span class="sxs-lookup"><span data-stu-id="040c5-143">In the dialog box that appears, select **Create database**.</span></span>

    <span data-ttu-id="040c5-144">![Boîte de dialogue de création de l'environnement](media/environment-created.PNG "Boîte de dialogue de création de l'environnement")</span><span class="sxs-lookup"><span data-stu-id="040c5-144">![Environment created dialog box](media/environment-created.PNG "Environment created dialog box")</span></span>   
    
10. <span data-ttu-id="040c5-145">Dans la boîte de dialogue suivante, sélectionnez la devise et la langue.</span><span class="sxs-lookup"><span data-stu-id="040c5-145">In the next dialog box, choose your currency and language.</span></span>

    <span data-ttu-id="040c5-146">![Paramètres de devise et de langue](media/currency-language-settings.PNG "Paramètres de devise et de langue")</span><span class="sxs-lookup"><span data-stu-id="040c5-146">![Currency and language settings](media/currency-language-settings.PNG "Currency and language settings")</span></span>
  
11. <span data-ttu-id="040c5-147">Sélectionnez **Créer une base de données.**</span><span class="sxs-lookup"><span data-stu-id="040c5-147">Select **Create database.**</span></span>

12. <span data-ttu-id="040c5-148">Dans l'écran **Centre d'administration PowerApps** > **Environnements**, sélectionnez l'environnement qui vient d'être créé (un environnement de production, pas un environnement par défaut).</span><span class="sxs-lookup"><span data-stu-id="040c5-148">In the **PowerApps Admin center** > **Environments** screen, select the environment that was just created (a production environment, not a default environment).</span></span> 

    <span data-ttu-id="040c5-149">![Sélectionner l'environnement](media/select-environment.PNG "Sélectionner l'environnement")</span><span class="sxs-lookup"><span data-stu-id="040c5-149">![Select the environment](media/select-environment.PNG "Select the environment")</span></span>
 
    <span data-ttu-id="040c5-150">L'écran suivant s'affiche alors que la base de données est créée et mise en service :</span><span class="sxs-lookup"><span data-stu-id="040c5-150">The following screen appears while the database is being created and provisioned:</span></span>
    
    <span data-ttu-id="040c5-151">![Écran d'approvisionnement de la base de données](media/provisioning-database.PNG "Écran d'approvisionnement de la base de données")</span><span class="sxs-lookup"><span data-stu-id="040c5-151">![Provisioning database screen](media/provisioning-database.PNG "Provisioning database screen")</span></span>
 
    > [!NOTE]
    > <span data-ttu-id="040c5-152">La création de la base de données prend généralement quelques minutes.</span><span class="sxs-lookup"><span data-stu-id="040c5-152">Database creation usually takes several minutes.</span></span> <span data-ttu-id="040c5-153">Si, au bout de 5 minutes, le message « Approvisionnement de la base de données » apparaît toujours, essayez d'actualiser la page.</span><span class="sxs-lookup"><span data-stu-id="040c5-153">If, after 5 minutes, the “Provisioning database” message still appears, try refreshing the page.</span></span>
    

13. <span data-ttu-id="040c5-154">Une fois que la base de données est créée, un lien vers le Centre d'administration Dynamics 365 apparaît.</span><span class="sxs-lookup"><span data-stu-id="040c5-154">After the database is created, a link to the Dynamics 365 Administration Center appears.</span></span> <span data-ttu-id="040c5-155">Sélectionnez ce lien, puis connectez-vous à nouveau avec les informations d'identification que vous avez créées pour la version préliminaire.</span><span class="sxs-lookup"><span data-stu-id="040c5-155">Select this link, and then sign in again with the credentials you created for the preview.</span></span> <span data-ttu-id="040c5-156">Vous devrez peut-être fermer votre navigateur avant de vous connecter.</span><span class="sxs-lookup"><span data-stu-id="040c5-156">You might need to close your browser before signing in.</span></span> 

    <span data-ttu-id="040c5-157">![Lien Centre d'administration](media/admin-center-link.PNG "Lien Centre d'administration")</span><span class="sxs-lookup"><span data-stu-id="040c5-157">![Admin Center link](media/admin-center-link.PNG "Admin Center link")</span></span>

<span data-ttu-id="040c5-158">Le centre d'administration Dynamics apparaît.</span><span class="sxs-lookup"><span data-stu-id="040c5-158">The Dynamics Admin Center appears.</span></span> <span data-ttu-id="040c5-159">Il s'agit de l'emplacement où vous pouvez installer la solution et effectuer d'autres configurations.</span><span class="sxs-lookup"><span data-stu-id="040c5-159">This is where you can install the solution and make other configurations.</span></span>

## <span data-ttu-id="040c5-160">Étape 3 : Installer et configurer la solution Dynamics 365 Guides (version préliminaire)<a name="configure"></a></span><span class="sxs-lookup"><span data-stu-id="040c5-160">Step 3: Install and configure the Dynamics 365 Guides (Preview) solution<a name="configure"></a></span></span>

<span data-ttu-id="040c5-161">Dans l'application du PC [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous pouvez télécharger vos propres fichiers 3D, ainsi que des vidéos et des images 2D.</span><span class="sxs-lookup"><span data-stu-id="040c5-161">In the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] PC application, you can upload your own 3D files, as well as videos and 2D images.</span></span> <span data-ttu-id="040c5-162">La taille de plusieurs de ces fichiers sera supérieure à 5 Mo, vous devrez donc modifier la taille maximale des fichiers qui seront chargés.</span><span class="sxs-lookup"><span data-stu-id="040c5-162">Many of these files will be larger than 5 MB, so you need to change the maximum file size for files that are uploaded.</span></span> <span data-ttu-id="040c5-163">Pour ce faire, vous devrez remplacer le paramètre de la taille de pièce jointe par 128 Mo (131072 Ko).</span><span class="sxs-lookup"><span data-stu-id="040c5-163">To do this, you'll change the setting for the email attachment size to 128 MB (131072 KB).</span></span> 

1.  <span data-ttu-id="040c5-164">Accédez au [Centre d'administration Dynamics 365](https://port.crm.dynamics.com/G/Instances/InstancePicker.aspx), puis connectez-vous avec les informations d'identification utilisateur créées lorsque vous vous êtes inscrit pour [!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)].</span><span class="sxs-lookup"><span data-stu-id="040c5-164">Go to the [Dynamics 365 Administration Center](https://port.crm.dynamics.com/G/Instances/InstancePicker.aspx), and sign in with the user credentials you created when you signed up for the [!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)].</span></span> 
    
2.  <span data-ttu-id="040c5-165">Sélectionnez l'instance [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] qui vient d'être créée dans la liste d'instances, puis sélectionnez **Ouvrir** comme indiqué ici :</span><span class="sxs-lookup"><span data-stu-id="040c5-165">Select the newly created [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] instance from the list of instances, and then select **Open** as shown here:</span></span> 
    
    <span data-ttu-id="040c5-166">![Centre d'administration avec le bouton Ouvrir sélectionné](media/admin-center-open-button.PNG "Centre d'administration avec le bouton Ouvrir sélectionné")</span><span class="sxs-lookup"><span data-stu-id="040c5-166">![Admin Center with Open button selected](media/admin-center-open-button.PNG "Admin Center with Open button selected")</span></span>
    
    <span data-ttu-id="040c5-167">Cela ouvre l'écran **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]**.</span><span class="sxs-lookup"><span data-stu-id="040c5-167">This opens the **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]** screen.</span></span>
    
3.  <span data-ttu-id="040c5-168">Dans l'écran **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]**, sélectionnez **Paramètres**, puis sélectionnez **Paramètres avancés**.</span><span class="sxs-lookup"><span data-stu-id="040c5-168">In the **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]** screen, select **Settings**, and then select **Advanced Settings**.</span></span> 

    <span data-ttu-id="040c5-169">![Paramètres avancés](media/advanced-settings.PNG "Paramètres avancés")</span><span class="sxs-lookup"><span data-stu-id="040c5-169">![Advanced Settings](media/advanced-settings.PNG "Advanced Settings")</span></span>
    
4.  <span data-ttu-id="040c5-170">Dans l'écran **[!include[pn-dyn-365](../includes/pn-dyn-365.md)] Gestion d'entreprise**, sélectionnez la liste déroulante **Paramètres**.</span><span class="sxs-lookup"><span data-stu-id="040c5-170">In the **[!include[pn-dyn-365](../includes/pn-dyn-365.md)] Business Management** screen, select the **Settings** drop-down list.</span></span>

     <span data-ttu-id="040c5-171">![Écran2 Gestion d'entreprise](media/business-management.PNG "Écran Gestion d'entreprise")</span><span class="sxs-lookup"><span data-stu-id="040c5-171">![Business Management screen2](media/business-management.PNG "Business Management screen")</span></span>
    
5.  <span data-ttu-id="040c5-172">Sous **Système**, sélectionnez **Administration**.</span><span class="sxs-lookup"><span data-stu-id="040c5-172">Under **System**, select **Administration**.</span></span>

    <span data-ttu-id="040c5-173">![Bouton Administration dans Dynamics 365](media/administration-button.PNG "Bouton Administration dans Dynamics 365")</span><span class="sxs-lookup"><span data-stu-id="040c5-173">![Administration button in Dynamics 365](media/administration-button.PNG "Administration button in Dynamics 365")</span></span>
 
6.  <span data-ttu-id="040c5-174">Dans la page **[!include[pn-dyn-365](../includes/pn-dyn-365.md)] Paramètres > Administration**, sélectionnez **Paramètres système**.</span><span class="sxs-lookup"><span data-stu-id="040c5-174">In the **[!include[pn-dyn-365](../includes/pn-dyn-365.md)] Settings > Administration** page, select **System Settings**.</span></span>

    <span data-ttu-id="040c5-175">![Paramètres système dans Dynamics 365](media/system-settings.PNG "Paramètres système dans Dynamics 365")</span><span class="sxs-lookup"><span data-stu-id="040c5-175">![System settings in Dynamics 365](media/system-settings.PNG "System settings in Dynamics 365")</span></span>
  
7.  <span data-ttu-id="040c5-176">Dans la boîte de dialogue **Paramètres système**, sélectionnez l'onglet **E-mail**, faites défiler l'écran vers le bas de la boîte de dialogue, puis dans le champ **Définir la limite de la taille de fichier pour les pièces jointes**, entrez **131072**.</span><span class="sxs-lookup"><span data-stu-id="040c5-176">In the **System Settings** dialog box, select the **Email** tab, scroll down to the bottom of the dialog box, and then in the **Set file size limits for attachments** field, enter **131072**.</span></span> <span data-ttu-id="040c5-177">Cliquez sur **OK** lorsque vous avez terminé.</span><span class="sxs-lookup"><span data-stu-id="040c5-177">Select **OK** when you’re done.</span></span>

    <span data-ttu-id="040c5-178">![Boîte de dialogue Paramètres système](media/system-settings-dialog-box.PNG "Boîte de dialogue Paramètres système")</span><span class="sxs-lookup"><span data-stu-id="040c5-178">![System settings dialog box](media/system-settings-dialog-box.PNG "System settings dialog box")</span></span>
 
8.  <span data-ttu-id="040c5-179">Revenez dans le [Centre d'administration Dynamics 365](https://port.crm.dynamics.com/G/Instances/InstancePicker.aspx), puis sélectionnez le petit bouton Modifier en regard de **Solutions**.</span><span class="sxs-lookup"><span data-stu-id="040c5-179">Go back to the [Dynamics 365 Administration Center](https://port.crm.dynamics.com/G/Instances/InstancePicker.aspx), and select the small edit button next to **Solutions**.</span></span>

    <span data-ttu-id="040c5-180">![Bouton Modifier Solutions](media/solutions-edit-button.PNG "Bouton Modifier Solutions")</span><span class="sxs-lookup"><span data-stu-id="040c5-180">![Solutions Edit button](media/solutions-edit-button.PNG "Solutions Edit button")</span></span>
 
    > [!NOTE]
    > <span data-ttu-id="040c5-181">Vous pouvez également accéder au Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)] à partir du portail PowerApps.</span><span class="sxs-lookup"><span data-stu-id="040c5-181">You can also get to the [!include[pn-dyn-365](../includes/pn-dyn-365.md)] Administration Center from the PowerApps portal.</span></span>
    
8.  <span data-ttu-id="040c5-182">Sélectionnez la solution [!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)] dans la liste, puis sélectionnez **Installer**.</span><span class="sxs-lookup"><span data-stu-id="040c5-182">Select the [!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)] solution in the list, and then select **Install**.</span></span> 

    <span data-ttu-id="040c5-183">![Bouton Solutions Installer](media/solutions-install-button.PNG "Bouton Solutions Installer")</span><span class="sxs-lookup"><span data-stu-id="040c5-183">![Solutions Install button](media/solutions-install-button.PNG "Solutions Install button")</span></span>
    
9. <span data-ttu-id="040c5-184">Dans la boîte de dialogue **Conditions d'utilisation**, examinez les conditions, puis sélectionnez **Installer** lorsque vous êtes prêt.</span><span class="sxs-lookup"><span data-stu-id="040c5-184">In the **Terms of Service** dialog box, review the terms, and then select **install** when you're ready.</span></span>

   <span data-ttu-id="040c5-185">Dans l'écran **Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)]**, le message suivant apparaît en surbrillance jaune pour indiquer que la solution est sur le point d'être installée :</span><span class="sxs-lookup"><span data-stu-id="040c5-185">In the **[!include[pn-dyn-365](../includes/pn-dyn-365.md)] Administration Center** screen, you'll see the following message highlighted in yellow showing that the solution is about to be installed:</span></span>

   <span data-ttu-id="040c5-186">![Message d'installation de la solution](media/installing-solution.PNG "Message d'installation de la solution")</span><span class="sxs-lookup"><span data-stu-id="040c5-186">![Solution installing message](media/installing-solution.PNG "Solution installing message")</span></span>
   
   <span data-ttu-id="040c5-187">Le champ **Statut** à gauche du message jaune indique **Installation en attente** lorsque la solution est en cours d'installation.</span><span class="sxs-lookup"><span data-stu-id="040c5-187">The **Status** field to the left of the yellow message will say **Installation pending** while the solution is being installed.</span></span> <span data-ttu-id="040c5-188">Lorsque la solution est installée, le contenu du champ **Statut** est remplacé par **Installé**.</span><span class="sxs-lookup"><span data-stu-id="040c5-188">When the solution has finished installing, the **Status** field changes to **Installed**.</span></span>
 
    > [!NOTE]
    > <span data-ttu-id="040c5-189">Le processus d'installation peut prendre jusqu'à une heure et est variable en fonction du jour et de la région.</span><span class="sxs-lookup"><span data-stu-id="040c5-189">The installation process can take up to one hour and is variable based on the time of day and region.</span></span> <span data-ttu-id="040c5-190">Si le statut n'a pas changé au bout d'une heure, essayez d'actualiser l'écran.</span><span class="sxs-lookup"><span data-stu-id="040c5-190">If the status hasn't changed after an hour, try refreshing your screen.</span></span> <span data-ttu-id="040c5-191">Si l'installation échoue, vous verrez ce message :</span><span class="sxs-lookup"><span data-stu-id="040c5-191">If the installation fails, you'll see this message:</span></span><br><span data-ttu-id="040c5-192">![Échec de l'installation](media/failed-install.PNG "Échec de l'installation")</span><span class="sxs-lookup"><span data-stu-id="040c5-192">![Failed installation](media/failed-install.PNG "Failed installation")</span></span>

### <span data-ttu-id="040c5-193">Paramétrer des rôles d'utilisateur pour la solution<a name="user-roles"></a></span><span class="sxs-lookup"><span data-stu-id="040c5-193">Set up user roles for the solution<a name="user-roles"></a></span></span>

> [!NOTE]
> <span data-ttu-id="040c5-194">L'affichage d'un utilisateur dans le Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)] peut prendre jusqu'à une heure, une fois les licences ajoutées dans le Centre d'administration [!include[cc-microsoft](../includes/cc-microsoft.md)] 365.</span><span class="sxs-lookup"><span data-stu-id="040c5-194">It can take up to one hour for a user to appear in the [!include[pn-dyn-365](../includes/pn-dyn-365.md)] admin center after the licenses are added in the [!include[cc-microsoft](../includes/cc-microsoft.md)] 365 admin center.</span></span> 

1.  <span data-ttu-id="040c5-195">Une fois la solution installée, accédez au [Centre d'administration Dynamics 365](https://port.crm.dynamics.com/G/Instances/InstancePicker.aspx), sélectionnez l'instance [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] qui vient d'être créée dans la liste des instances, puis sélectionnez **Ouvrir**.</span><span class="sxs-lookup"><span data-stu-id="040c5-195">After the solution has finished installing, go to the [Dynamics 365 Administration Center](https://port.crm.dynamics.com/G/Instances/InstancePicker.aspx), select the newly created [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] instance from the list of instances, and then select **Open**.</span></span>

2. <span data-ttu-id="040c5-196">Sur la page **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]**, sélectionnez **Paramètres**, puis sélectionnez **Paramètres avancés**.</span><span class="sxs-lookup"><span data-stu-id="040c5-196">On the **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]** page, select **Settings**, and then select **Advanced Settings**.</span></span>

    <span data-ttu-id="040c5-197">![Paramètres avancés Dynamics 365](media/roles-advanced-settings.PNG "Paramètres avancés Dynamics 365")</span><span class="sxs-lookup"><span data-stu-id="040c5-197">![Dynamics 365 Advanced Settings](media/roles-advanced-settings.PNG "Dynamics 365 Advanced Settings")</span></span>
    
    > [!IMPORTANT]
    > <span data-ttu-id="040c5-198">Vous pouvez accéder aux données [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] via la vignette Guides Hub (version préliminaire) de l'écran précédent, mais nous déconseillons d'effectuer des modifications dans Guides Hub.</span><span class="sxs-lookup"><span data-stu-id="040c5-198">You can access [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] data through the Guides Hub (Preview) tile in the preceding screen, but we recommend that you not make any changes in the Guides Hub.</span></span> <span data-ttu-id="040c5-199">Toute modification apportée peut avoir des conséquences imprévues pour les applications [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="040c5-199">Any changes you make can have unintended consequences for the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] apps.</span></span>
 
3.   <span data-ttu-id="040c5-200">Dans l'écran **[!include[pn-dyn-365](../includes/pn-dyn-365.md)] > Gestion d'entreprise**, sélectionnez la liste déroulante **Paramètres**.</span><span class="sxs-lookup"><span data-stu-id="040c5-200">In the **[!include[pn-dyn-365](../includes/pn-dyn-365.md)] > Business Management** screen, select the **Settings** drop-down list.</span></span>
    
     <span data-ttu-id="040c5-201">![Écran2 Gestion d'entreprise](media/business-management.PNG "Écran Gestion d'entreprise")</span><span class="sxs-lookup"><span data-stu-id="040c5-201">![Business Management screen2](media/business-management.PNG "Business Management screen")</span></span>

4.  <span data-ttu-id="040c5-202">Sur la page **[!include[pn-dyn-365](../includes/pn-dyn-365.md)] Paramètres** > **Administration**, sous **Système**, sélectionnez **Sécurité**.</span><span class="sxs-lookup"><span data-stu-id="040c5-202">On the **[!include[pn-dyn-365](../includes/pn-dyn-365.md)] Settings** > **Administration** page, under **System**, select **Security**.</span></span> 

    <span data-ttu-id="040c5-203">![Paramètre de sécurité Dynamics 365](media/security-setting.PNG "Paramètre de sécurité Dynamics 365")</span><span class="sxs-lookup"><span data-stu-id="040c5-203">![Dynamics 365 Security setting](media/security-setting.PNG "Dynamics 365 Security setting")</span></span>
 
4.  <span data-ttu-id="040c5-204">Dans la page **Sécurité**, sélectionnez **Utilisateurs**.</span><span class="sxs-lookup"><span data-stu-id="040c5-204">On the **Security** page, select **Users**.</span></span>

    <span data-ttu-id="040c5-205">![Paramètre Utilisateurs Dynamics 365](media/select-users.PNG "Paramètre Utilisateurs Dynamics 365")</span><span class="sxs-lookup"><span data-stu-id="040c5-205">![Dynamics 365 Users setting](media/select-users.PNG "Dynamics 365 Users setting")</span></span>
 
5.  <span data-ttu-id="040c5-206">Sélectionnez l'utilisateur, puis sélectionnez **Gérer les rôles**.</span><span class="sxs-lookup"><span data-stu-id="040c5-206">Select the user, and then select **Manage** roles.</span></span> 

    <span data-ttu-id="040c5-207">![Commande Gérer les rôles](media/manage-roles-command.PNG "Commande Gérer les rôles")</span><span class="sxs-lookup"><span data-stu-id="040c5-207">![Manage Roles command](media/manage-roles-command.PNG "Manage Roles command")</span></span>
 
6.  <span data-ttu-id="040c5-208">Dans la boîte de dialogue **Gérer les rôles d'utilisateurs**, sélectionnez les rôles suivants :</span><span class="sxs-lookup"><span data-stu-id="040c5-208">In the **Manage User Roles** dialog box, select the following roles:</span></span> 

    - <span data-ttu-id="040c5-209">Utilisateur Common Data Service</span><span class="sxs-lookup"><span data-stu-id="040c5-209">Common Data Service User</span></span>
    
    - <span data-ttu-id="040c5-210">Auteur [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]</span><span class="sxs-lookup"><span data-stu-id="040c5-210">[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] Author</span></span>
    
    - <span data-ttu-id="040c5-211">Administrateur système</span><span class="sxs-lookup"><span data-stu-id="040c5-211">System Administrator</span></span> 
       
      <span data-ttu-id="040c5-212">![Boîte de dialogue Gérer les rôles renseignée](media/manage-roles-dialog-box.PNG "Boîte de dialogue Gérer les rôles renseignée")</span><span class="sxs-lookup"><span data-stu-id="040c5-212">![Manage Roles dialog box filled in](media/manage-roles-dialog-box.PNG "Manage Roles dialog box filled in")</span></span>
      
      > [!NOTE]
      > <span data-ttu-id="040c5-213">Sélectionnez le rôle Administrateur système s'il s'agit de l'utilisateur principal/de l'administrateur. Sinon, ne sélectionnez pas ce rôle.</span><span class="sxs-lookup"><span data-stu-id="040c5-213">Select the System Administrator role if this is the main user/admin. Otherwise, do not select that role.</span></span>
 
     
## <a name="step-4-install-the-applications"></a><span data-ttu-id="040c5-214">Étape 4 : Installer les applications</span><span class="sxs-lookup"><span data-stu-id="040c5-214">Step 4: Install the applications</span></span>

<span data-ttu-id="040c5-215">Il y a deux applications [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] :</span><span class="sxs-lookup"><span data-stu-id="040c5-215">There are two [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] applications:</span></span> 

- <span data-ttu-id="040c5-216">Application de création du PC</span><span class="sxs-lookup"><span data-stu-id="040c5-216">PC authoring application</span></span>

- <span data-ttu-id="040c5-217">Application [!include[pn-hololens](../includes/pn-hololens.md)], avec un mode Créer et un mode Opérateur</span><span class="sxs-lookup"><span data-stu-id="040c5-217">[!include[pn-hololens](../includes/pn-hololens.md)] application, which has an Author mode and an Operator mode</span></span>

<span data-ttu-id="040c5-218">Vous pouvez installer les applications à partir de [!include[cc-microsoft](../includes/cc-microsoft.md)] Store tel que décrit dans la section suivante.</span><span class="sxs-lookup"><span data-stu-id="040c5-218">You can install the apps from [!include[cc-microsoft](../includes/cc-microsoft.md)] Store as described in the next section.</span></span>

> [!NOTE]
> <span data-ttu-id="040c5-219">Si vous ne pouvez pas accéder à [!include[cc-microsoft](../includes/cc-microsoft.md)] Store en raison de politiques d'entreprise, contactez votre administrateur pour qu'il distribue l'application.</span><span class="sxs-lookup"><span data-stu-id="040c5-219">If you can’t access [!include[cc-microsoft](../includes/cc-microsoft.md)] Store due to company policies, please contact your administrator to distribute the app.</span></span>

<span data-ttu-id="040c5-220">Si vous utilisez [!include[cc-microsoft](../includes/cc-microsoft.md)] Store pour Entreprises pour distribuer vos applications, les utilisateurs peuvent les installer à partir du magasin privé de votre organisation ou d'un lien que vous leur envoyez par e-mail.</span><span class="sxs-lookup"><span data-stu-id="040c5-220">If you use [!include[cc-microsoft](../includes/cc-microsoft.md)] Store for Business to distribute your apps, you can have users install the apps from your organization’s private store or from an email link that you send.</span></span> <span data-ttu-id="040c5-221">Les instructions sont fournies plus loin dans cette rubrique.</span><span class="sxs-lookup"><span data-stu-id="040c5-221">Instructions are provided later in this topic.</span></span>

### <a name="install-the-apps-from-microsoft-store"></a><span data-ttu-id="040c5-222">Installer les applications à partir de Microsoft Store</span><span class="sxs-lookup"><span data-stu-id="040c5-222">Install the apps from Microsoft Store</span></span>

#### <a name="install-the-pc-authoring-app"></a><span data-ttu-id="040c5-223">Installer l'application de création sur PC</span><span class="sxs-lookup"><span data-stu-id="040c5-223">Install the PC authoring app</span></span> 
1.  <span data-ttu-id="040c5-224">Assurez-vous que votre [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC exécute la dernière version de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] (10.0.16299 ou ultérieure).</span><span class="sxs-lookup"><span data-stu-id="040c5-224">Check to make sure your [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC is running the latest [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] build (must be build 10.0.16299 or later).</span></span>

2.  <span data-ttu-id="040c5-225">Sur votre PC, allez dans **Démarrer** ![Bouton Démarrer](media/windows-button.png "Bouton Démarrer") > **[!include[cc-microsoft](../includes/cc-microsoft.md)] Store** ![Bouton Store](media/store-button.png "Bouton Store"), puis recherchez [!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)].</span><span class="sxs-lookup"><span data-stu-id="040c5-225">On your PC, go to **Start** ![Start button)](media/windows-button.png "Start button") > **[!include[cc-microsoft](../includes/cc-microsoft.md)] Store** ![Store button)](media/store-button.png "Store button"), and then search for “[!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)].”</span></span>

3.  <span data-ttu-id="040c5-226">Dans [!include[cc-microsoft](../includes/cc-microsoft.md)] Store, sélectionnez **Obtenir** en regard de l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] pour la télécharger et l'installer.</span><span class="sxs-lookup"><span data-stu-id="040c5-226">In [!include[cc-microsoft](../includes/cc-microsoft.md)] Store, select **Get** for the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] app to download, and install the application.</span></span>

    <span data-ttu-id="040c5-227">![Application préliminaire dans Microsoft Store](media/preview-app.PNG "Application préliminaire dans Microsoft Store")</span><span class="sxs-lookup"><span data-stu-id="040c5-227">![Preview app in Microsoft Store](media/preview-app.PNG "Preview app in Microsoft Store")</span></span>

    > [!NOTE]
    > <span data-ttu-id="040c5-228">Pour obtenir des instructions sur l'ouverture et la connexion à l'application, voir [Création de guide](authoring-overview.md).</span><span class="sxs-lookup"><span data-stu-id="040c5-228">For instructions on opening and signing in to the app, see the [authoring guide](authoring-overview.md).</span></span>

#### <a name="install-the-hololens-app"></a><span data-ttu-id="040c5-229">Installer l'application HoloLens</span><span class="sxs-lookup"><span data-stu-id="040c5-229">Install the HoloLens app</span></span>

1.  <span data-ttu-id="040c5-230">Assurez-vous qu'[!include[pn-hololens](../includes/pn-hololens.md)] exécute la version 10.0.14393.0 ou ultérieure.</span><span class="sxs-lookup"><span data-stu-id="040c5-230">Make sure [!include[pn-hololens](../includes/pn-hololens.md)] is running build 10.0.14393.0 or later.</span></span> <span data-ttu-id="040c5-231">Nous vous recommandons de mettre à jour [!include[pn-hololens](../includes/pn-hololens.md)] vers des versions plus récentes quand elles sont disponibles.</span><span class="sxs-lookup"><span data-stu-id="040c5-231">We recommend updating [!include[pn-hololens](../includes/pn-hololens.md)] to newer versions when available.</span></span> <span data-ttu-id="040c5-232">Voir [Gérer les mises à jour vers HoloLens](https://docs.microsoft.com/en-us/HoloLens/hololens-updates) pour obtenir des instructions sur l'utilisation de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Update pour Entreprise.</span><span class="sxs-lookup"><span data-stu-id="040c5-232">See [Manage updates to HoloLens](https://docs.microsoft.com/en-us/HoloLens/hololens-updates) for instructions on using [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Update for Business.</span></span>

2.  <span data-ttu-id="040c5-233">Dans [!include[pn-hololens](../includes/pn-hololens.md)], utilisez l'écartement des doigts paume vers le haut pour ouvrir le menu **Accueil**, puis ouvrez l'application [!include[cc-microsoft](../includes/cc-microsoft.md)] Store et recherchez [!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)].</span><span class="sxs-lookup"><span data-stu-id="040c5-233">On your [!include[pn-hololens](../includes/pn-hololens.md)], use the bloom gesture to open the **Home** menu, and then open the [!include[cc-microsoft](../includes/cc-microsoft.md)] Store app and search for “[!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)]”.</span></span>

3.  <span data-ttu-id="040c5-234">Sélectionnez **Installer** pour télécharger et installer l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="040c5-234">Select **Install** to download and install the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] application.</span></span>

> [!NOTE] 
> <span data-ttu-id="040c5-235">Pour obtenir des instructions sur l'ouverture et la connexion à l'application, si vous êtes un auteur, consultez la [rubrique de création HoloLens](hololens-authoring.md).</span><span class="sxs-lookup"><span data-stu-id="040c5-235">For instructions on opening and signing in to the app, if you're an author, see the [HoloLens authoring topic](hololens-authoring.md).</span></span> <span data-ttu-id="040c5-236">Les opérateurs peuvent utiliser le [manuel de l'opérateur Dynamics 365 Guides](operator-guide.md).</span><span class="sxs-lookup"><span data-stu-id="040c5-236">Operators can use the [Dynamics 365 Guides Operator's manual](operator-guide.md).</span></span>

### <a name="distribute-the-apps-through-the-microsoft-store-for-business"></a><span data-ttu-id="040c5-237">Distribuer les applications via Microsoft Store pour Entreprises</span><span class="sxs-lookup"><span data-stu-id="040c5-237">Distribute the apps through the Microsoft Store for Business</span></span>

1.  <span data-ttu-id="040c5-238">Accédez à [Microsoft Store pour Entreprises](https://businessstore.microsoft.com/en-us/store).</span><span class="sxs-lookup"><span data-stu-id="040c5-238">Go to the [Microsoft Store for Business](https://businessstore.microsoft.com/en-us/store).</span></span>

2.  <span data-ttu-id="040c5-239">[Faites l'acquisition de la ou des applications](https://docs.microsoft.com/en-us/microsoft-store/acquire-apps-microsoft-store-for-business).</span><span class="sxs-lookup"><span data-stu-id="040c5-239">[Acquire the app(s)](https://docs.microsoft.com/en-us/microsoft-store/acquire-apps-microsoft-store-for-business).</span></span>

3.  <span data-ttu-id="040c5-240">Choisissez l'une des méthodes de distribution suivantes :</span><span class="sxs-lookup"><span data-stu-id="040c5-240">Choose one of the following distribution methods:</span></span>

    - [<span data-ttu-id="040c5-241">Magasin privé</span><span class="sxs-lookup"><span data-stu-id="040c5-241">Private store</span></span>](https://docs.microsoft.com/en-us/microsoft-store/distribute-apps-from-your-private-store)
    
    - [<span data-ttu-id="040c5-242">Lien de courrier électronique</span><span class="sxs-lookup"><span data-stu-id="040c5-242">Email link</span></span>](https://docs.microsoft.com/en-us/microsoft-store/assign-apps-to-employees)
    
    - [<span data-ttu-id="040c5-243">Gestion des périphériques mobiles</span><span class="sxs-lookup"><span data-stu-id="040c5-243">Mobile device management</span></span>](https://docs.microsoft.com/en-us/microsoft-store/configure-mdm-provider-microsoft-store-for-business)

<span data-ttu-id="040c5-244">Pour plus d'informations sur l'ouverture et la connexion à l'application du PC après l'avoir installée, voir [Création de guide](authoring-overview.md).</span><span class="sxs-lookup"><span data-stu-id="040c5-244">For information on opening and signing in to the PC application after installing it, see the [authoring guide](authoring-overview.md).</span></span>

<span data-ttu-id="040c5-245">Pour plus d'informations sur l'ouverture et la connexion à l'application [!include[pn-hololens](../includes/pn-hololens.md)], accédez à l'une des options suivantes, selon que vous êtes auteur ou opérateur :</span><span class="sxs-lookup"><span data-stu-id="040c5-245">For information on opening and signing in to the [!include[pn-hololens](../includes/pn-hololens.md)] application, go to one of the following, depending on whether you're an author or an operator:</span></span>

   - [<span data-ttu-id="040c5-246">Création HoloLens</span><span class="sxs-lookup"><span data-stu-id="040c5-246">HoloLens authoring</span></span>](hololens-authoring.md)
   
   - [<span data-ttu-id="040c5-247">Manuel de l'opérateur</span><span class="sxs-lookup"><span data-stu-id="040c5-247">Operator's manual</span></span>](operator-guide.md)
   
## <span data-ttu-id="040c5-248">Étape 5 : Ajouter des comptes d'utilisateur supplémentaires (facultatif)<a name="user-accounts"></a></span><span class="sxs-lookup"><span data-stu-id="040c5-248">Step 5: Add additional user accounts (optional)<a name="user-accounts"></a></span></span>

<span data-ttu-id="040c5-249">Vous devrez créer un compte d'utilisateur pour toutes les personnes à que vous affectez une licence.</span><span class="sxs-lookup"><span data-stu-id="040c5-249">You’ll need to create a user account for anyone you assign a license to.</span></span> <span data-ttu-id="040c5-250">Créez un compte d'utilisateur pour toutes les personnes de votre équipe qui vont utiliser [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="040c5-250">Create a new user account for anyone on your team who will use [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span></span> <span data-ttu-id="040c5-251">Vous devez créer des comptes d'utilisateur dans le Centre d'administration Microsoft 365 [!include[cc-microsoft](../includes/cc-microsoft.md)], puis affecter des licences à ces utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="040c5-251">You create user accounts in the [!include[cc-microsoft](../includes/cc-microsoft.md)] 365 Admin Center, and then assign licenses to those users.</span></span>

### <a name="add-a-user-account"></a><span data-ttu-id="040c5-252">Ajouter un compte d'utilisateur</span><span class="sxs-lookup"><span data-stu-id="040c5-252">Add a user account</span></span>

1.  <span data-ttu-id="040c5-253">Accédez à [Centre d'administration Microsoft 365](https://admin.microsoft.com/AdminPortal/Home).</span><span class="sxs-lookup"><span data-stu-id="040c5-253">Go to the [Microsoft 365 Admin Center](https://admin.microsoft.com/AdminPortal/Home).</span></span>

2.  <span data-ttu-id="040c5-254">Sélectionnez **Ajouter un utilisateur**.</span><span class="sxs-lookup"><span data-stu-id="040c5-254">Select **Add a user**.</span></span>

    <span data-ttu-id="040c5-255">![Ajouter un utilisateur](media/add-user.PNG "Ajouter un utilisateur")</span><span class="sxs-lookup"><span data-stu-id="040c5-255">![Add a user](media/add-user.PNG "Add a user")</span></span>
 
    <span data-ttu-id="040c5-256">La boîte de dialogue **Nouvel utilisateur** s'affiche :</span><span class="sxs-lookup"><span data-stu-id="040c5-256">You’ll see the **New user** dialog box:</span></span>
    
    <span data-ttu-id="040c5-257">![Boîte de dialogue Nouvel utilisateur](media/new-user-dialog-box.PNG "Boîte de dialogue Nouvel utilisateur")</span><span class="sxs-lookup"><span data-stu-id="040c5-257">![New User dialog box](media/new-user-dialog-box.PNG "New user dialog box")</span></span>
 
3.  <span data-ttu-id="040c5-258">Dans la boîte de dialogue **Nouvel utilisateur**, renseignez les informations utilisateur suivantes :</span><span class="sxs-lookup"><span data-stu-id="040c5-258">In the **New user** dialog box, fill in the following user information:</span></span>

    - <span data-ttu-id="040c5-259">Ajoutez le prénom, le nom, le nom complet et le nom d'utilisateur.</span><span class="sxs-lookup"><span data-stu-id="040c5-259">Add the first, last, display name, and user name.</span></span>

    - <span data-ttu-id="040c5-260">**Domaine.**</span><span class="sxs-lookup"><span data-stu-id="040c5-260">**Domain.**</span></span> <span data-ttu-id="040c5-261">Laissez le domaine tel quel.</span><span class="sxs-lookup"><span data-stu-id="040c5-261">Leave the domain as is.</span></span> <span data-ttu-id="040c5-262">Il est automatiquement renseigné en fonction de la société que vous avez entrée lorsque vous vous êtes inscrit pour la version préliminaire.</span><span class="sxs-lookup"><span data-stu-id="040c5-262">It's automatically filled out based on the company you entered when you signed up for the preview.</span></span> 

    - <span data-ttu-id="040c5-263">**Mot de passe.**</span><span class="sxs-lookup"><span data-stu-id="040c5-263">**Password.**</span></span> <span data-ttu-id="040c5-264">Le système génère un ID utilisateur et un mot de passe temporaires pour l'utilisateur.</span><span class="sxs-lookup"><span data-stu-id="040c5-264">The system generates a user ID and temporary password for the user.</span></span> <span data-ttu-id="040c5-265">Nous vous recommandons d'envoyer les informations d'identification temporaires à l'utilisateur via e-mail et d'inviter l'utilisateur à changer de mot de passe à la première connexion.</span><span class="sxs-lookup"><span data-stu-id="040c5-265">We recommend that you send the temporary credentials to the user via email and have the user change the password at first sign in.</span></span> <span data-ttu-id="040c5-266">Pour appliquer cela, sélectionnez la flèche vers le bas, puis activez la case à cocher **Demander à cet utilisateur de modifier son mot de passe lorsqu'il se connecte pour la première fois**.</span><span class="sxs-lookup"><span data-stu-id="040c5-266">To enforce that this happens, select the down arrow, and then select the **Make this user change their password when they first sign in** check box.</span></span> 
    
      <span data-ttu-id="040c5-267">![Case à cocher pour l'application du mot de passe](media/password-enforcement.PNG "Case à cocher pour l'application du mot de passe")</span><span class="sxs-lookup"><span data-stu-id="040c5-267">![Password enforcement check box](media/password-enforcement.PNG "Password enforcement check box")</span></span>

    - <span data-ttu-id="040c5-268">**Rôles.**</span><span class="sxs-lookup"><span data-stu-id="040c5-268">**Roles.**</span></span> <span data-ttu-id="040c5-269">Développez cette section et sélectionnez l'option **Utilisateur (aucun accès Administrateur)**.</span><span class="sxs-lookup"><span data-stu-id="040c5-269">Expand this section and select the **User (no administrator access)** option.</span></span> 
    
      <span data-ttu-id="040c5-270">![Modifier les rôles d'utilisateur](media/user-roles.PNG "Modifier les rôles d'utilisateur")</span><span class="sxs-lookup"><span data-stu-id="040c5-270">![Edit user roles](media/user-roles.PNG "Edit user roles")</span></span>
 

    - <span data-ttu-id="040c5-271">**Licences de produits**.</span><span class="sxs-lookup"><span data-stu-id="040c5-271">**Product licenses**.</span></span> <span data-ttu-id="040c5-272">Développez cette section, puis déplacez le curseur sur **Dynamics 365 Guides** **Activé**.</span><span class="sxs-lookup"><span data-stu-id="040c5-272">Expand this section, and then turn the **Dynamics 365 Guides** slider to **On**.</span></span> <span data-ttu-id="040c5-273">Vous pouvez affecter jusqu'à 25 utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="040c5-273">You can assign up to 25 users.</span></span>
    
      <span data-ttu-id="040c5-274">![Boîte de dialogue Licences de produits](media/new-user-plans.PNG "Boîte de dialogue Licences de produits")</span><span class="sxs-lookup"><span data-stu-id="040c5-274">![Product Licenses dialog box](media/new-user-plans.PNG "Product Licenses dialog box")</span></span>
 
4.  <span data-ttu-id="040c5-275">Sélectionnez **Ajouter** lorsque vous avez terminé.</span><span class="sxs-lookup"><span data-stu-id="040c5-275">Select **Add** when you’re done.</span></span>

    <span data-ttu-id="040c5-276">Lorsque vous ajoutez un utilisateur, celui-ci reçoit une notification par e-mail de l'équipe en ligne de services [!include[cc-microsoft](../includes/cc-microsoft.md)] qui inclut leur ID utilisateur et leur mot de passe temporaire.</span><span class="sxs-lookup"><span data-stu-id="040c5-276">When you add a user, the user gets an email notification from the [!include[cc-microsoft](../includes/cc-microsoft.md)] Online Services Team that includes their user ID and    temporary password.</span></span> <span data-ttu-id="040c5-277">Il doit utiliser ces informations pour se connecter à [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="040c5-277">They’ll use this information to sign in to [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span></span>

5. <span data-ttu-id="040c5-278">Si ce n'est déjà fait, [paramétrez des rôles d'utilisateur pour la solution](#user-roles) comme décrit précédemment dans cette rubrique.</span><span class="sxs-lookup"><span data-stu-id="040c5-278">If you haven't already done so, [set up user roles for the solution](#user-roles) as described earlier in this topic.</span></span>

## <a name="step-6-set-up-guides-analytics-reports"></a><span data-ttu-id="040c5-279">Étape 6 : Paramétrer les états d'Analyses de Guides</span><span class="sxs-lookup"><span data-stu-id="040c5-279">Step 6: Set up Guides Analytics reports</span></span> 

[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] <span data-ttu-id="040c5-280">inclut des états [!include[pn-power-bi](../includes/pn-power-bi.md)] (appelés Analyses de Guides) qui permettent d'analyser les processus des guides.</span><span class="sxs-lookup"><span data-stu-id="040c5-280">includes [!include[pn-power-bi](../includes/pn-power-bi.md)] reports (called Guides Analytics) that you can use to analyze guides processes.</span></span> <span data-ttu-id="040c5-281">Vous pouvez partager ces états au sein de votre organisation en les publiant dans le service [!include[pn-power-bi](../includes/pn-power-bi.md)].</span><span class="sxs-lookup"><span data-stu-id="040c5-281">You can share these reports within your organization by publishing them to the [!include[pn-power-bi](../includes/pn-power-bi.md)] Service.</span></span> <span data-ttu-id="040c5-282">Cela permet à toute personne de votre organisation ayant une licence Pro [!include[pn-power-bi](../includes/pn-power-bi.md)] d'accéder à l'état via l'interface Web du service [!include[pn-power-bi](../includes/pn-power-bi.md)] accessible sur [https://powerbi.microsoft.com](https://powerbi.microsoft.com).</span><span class="sxs-lookup"><span data-stu-id="040c5-282">This allows anyone in your organization with a [!include[pn-power-bi](../includes/pn-power-bi.md)] Pro license to access the report through the [!include[pn-power-bi](../includes/pn-power-bi.md)] Service web interface accessible at [https://powerbi.microsoft.com](https://powerbi.microsoft.com).</span></span>  

[!include[pn-power-bi](../includes/pn-power-bi.md)] <span data-ttu-id="040c5-283">fournit plusieurs systèmes pour partager des états avec d'autres personnes de votre organisation.</span><span class="sxs-lookup"><span data-stu-id="040c5-283">provides several mechanisms for sharing reports with others in your organization.</span></span> <span data-ttu-id="040c5-284">Nous vous recommandons de lire [Comment partager votre travail dans Power BI](https://docs.microsoft.com/en-us/power-bi/service-how-to-collaborate-distribute-dashboards-reports) pour obtenir une vue d'ensemble.</span><span class="sxs-lookup"><span data-stu-id="040c5-284">We recommend reading [Ways to share your work in Power BI](https://docs.microsoft.com/en-us/power-bi/service-how-to-collaborate-distribute-dashboards-reports) for an overview.</span></span> <span data-ttu-id="040c5-285">Pour partager facilement vos états dans votre organisation en lecture seule, publiez-les sous forme d'application [!include[pn-power-bi](../includes/pn-power-bi.md)].</span><span class="sxs-lookup"><span data-stu-id="040c5-285">A great way to share your reports within your organization in a read-only fashion is to publish them as a [!include[pn-power-bi](../includes/pn-power-bi.md)] app.</span></span> <span data-ttu-id="040c5-286">Cela implique de suivre les étapes bien documentées suivantes :</span><span class="sxs-lookup"><span data-stu-id="040c5-286">This involves the following well-documented steps:</span></span> 

1.  <span data-ttu-id="040c5-287">[Créer un espace de travail dans le service Power BI](https://docs.microsoft.com/en-us/power-bi/service-create-workspaces).</span><span class="sxs-lookup"><span data-stu-id="040c5-287">[Create a workspace in the Power BI Service](https://docs.microsoft.com/en-us/power-bi/service-create-workspaces).</span></span> 

2.  <span data-ttu-id="040c5-288">[Publier les états d'Analyses de Guides dans cet espace de travail via Power BI Desktop](https://docs.microsoft.com/en-us/power-bi/desktop-upload-desktop-files).</span><span class="sxs-lookup"><span data-stu-id="040c5-288">[Publish your Guides Analytics reports to this workspace using Power BI Desktop](https://docs.microsoft.com/en-us/power-bi/desktop-upload-desktop-files).</span></span> 

3.  <span data-ttu-id="040c5-289">[Publier le contenu de l'espace de travail en tant qu'application dans le service Power BI](https://docs.microsoft.com/en-us/power-bi/service-create-distribute-apps).</span><span class="sxs-lookup"><span data-stu-id="040c5-289">[Publish the contents of your workspace as an app in the Power BI Service](https://docs.microsoft.com/en-us/power-bi/service-create-distribute-apps).</span></span>  

### <a name="see-also"></a><span data-ttu-id="040c5-290">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="040c5-290">See also</span></span>

[<span data-ttu-id="040c5-291">Mise en route de Dynamics 365 Guides en version préliminaire</span><span class="sxs-lookup"><span data-stu-id="040c5-291">Get started with Dynamics 365 Guides in preview</span></span>](get-started.md)<br>
[<span data-ttu-id="040c5-292">Créer un guide</span><span class="sxs-lookup"><span data-stu-id="040c5-292">Author a guide</span></span>](authoring-overview.md)<br>
[<span data-ttu-id="040c5-293">Manuel de l'opérateur</span><span class="sxs-lookup"><span data-stu-id="040c5-293">Operator's manual</span></span>](operator-guide.md)<br>
[<span data-ttu-id="040c5-294">Analyser les guides pour rendre les processus plus efficaces</span><span class="sxs-lookup"><span data-stu-id="040c5-294">Analyze your guides to improve process efficiencies</span></span>](analytics-guide.md)<br>
[<span data-ttu-id="040c5-295">FAQ</span><span class="sxs-lookup"><span data-stu-id="040c5-295">FAQ</span></span>](faq.md)






