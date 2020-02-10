---
author: Mamaylya
description: Étape 1 de la configuration de Dynamics 365 Guides, qui comprend l'achat d'un abonnement ou l'inscription à un essai gratuit de 30 jours
ms.author: mamaylya
ms.date: 01/28/2020
ms.service: crm-online
ms.topic: article
title: Acheter un abonnement Dynamics 365 Guides ou s'inscrire pour un essai gratuit
ms.reviewer: v-brycho
ms.openlocfilehash: e81427c3ea37b6abb0092e253a1b68b307819cc1
ms.sourcegitcommit: 217d31bb34e67a6b8823d5ddac7ef8d56d054139
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/29/2020
ms.locfileid: "2995257"
---
# <a name="dynamics-365-guides-setup-step-1-buy-a-subscription-or-sign-up-for-a-free-trial"></a><span data-ttu-id="cecc4-103">Étape 1 de la configuration de Dynamics 365 Guides : Acheter un abonnement ou s'inscrire pour un essai gratuit</span><span class="sxs-lookup"><span data-stu-id="cecc4-103">Dynamics 365 Guides setup Step 1: Buy a subscription or sign up for a free trial</span></span> 

>[!NOTE]
><span data-ttu-id="cecc4-104">Avant d'effectuer cette étape, vous devez consulter la rubrique [Présentation de la configuration de Dynamics 365 Guides](setup.md).</span><span class="sxs-lookup"><span data-stu-id="cecc4-104">Before completing this step, make sure to see [Overview of setting up Dynamics 365 Guides](setup.md).</span></span>

<span data-ttu-id="cecc4-105">Il existe deux moyens d'obtenir un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] :</span><span class="sxs-lookup"><span data-stu-id="cecc4-105">There are two ways to get a [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] subscription:</span></span>

- <span data-ttu-id="cecc4-106">Si vous avez un compte professionnel Microsoft, vous pouvez accéder directement au [Centre d'administration Microsoft 365](https://admin.microsoft.com/AdminPortal/Home) et rechercher un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="cecc4-106">If you have a Microsoft work account, you can go directly to the [Microsoft 365 admin center](https://admin.microsoft.com/AdminPortal/Home) and search for a [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] subscription there.</span></span>

- <span data-ttu-id="cecc4-107">Accédez à la page [Mise en route](https://aka.ms/GetGuides).</span><span class="sxs-lookup"><span data-stu-id="cecc4-107">Go to the [Get started](https://aka.ms/GetGuides) page.</span></span> <span data-ttu-id="cecc4-108">Vous pouvez utiliser cette page pour acheter un abonnement ou vous inscrire pour un essai gratuit de 30 jours.</span><span class="sxs-lookup"><span data-stu-id="cecc4-108">You can use this page to buy a subscription or to sign up for a free 30-day trial.</span></span> <span data-ttu-id="cecc4-109">Si vous vous inscrivez pour un essai gratuit, vous pouvez utiliser les informations d'identification d'un compte Dynamics 365 existant ou en créer de nouvelles.</span><span class="sxs-lookup"><span data-stu-id="cecc4-109">If you sign up for a trial, you can use credentials for an existing Dynamics 365 account or you can create new credentials.</span></span> 

    > [!IMPORTANT] 
    > <span data-ttu-id="cecc4-110">Si vous ne disposez pas des autorisations d'administrateur associées à votre compte de travail, vous ne pourrez pas effectuer l'étape 2 du processus de configuration ([Installer la solution](setup-step-two.md)).</span><span class="sxs-lookup"><span data-stu-id="cecc4-110">If you don't have administrator permissions associated with your work account, you won't be able to complete step 2 of the setup process ([Install the solution](setup-step-two.md)).</span></span> <span data-ttu-id="cecc4-111">Veuillez coordonner la configuration avec votre administrateur.</span><span class="sxs-lookup"><span data-stu-id="cecc4-111">Please coordinate setup with your administrator.</span></span> <span data-ttu-id="cecc4-112">Si ce n'est pas possible, vous pouvez vous inscrire pour un essai gratuit de 30 jours en suivant les étapes de la page [Mise en route](https://aka.ms/GetGuides).</span><span class="sxs-lookup"><span data-stu-id="cecc4-112">If that's not possible, you can sign up for a free 30-day trial by following the steps on the [Getting started](https://aka.ms/GetGuides) page.</span></span> <span data-ttu-id="cecc4-113">Lorsque vous vous inscrivez à un essai, vous devez créer un nouvel environnement et le compte d'utilisateur que vous créez aura des autorisations d'administrateur.</span><span class="sxs-lookup"><span data-stu-id="cecc4-113">When you sign up for a trial, you'll create a new environment and the user account you create will have administrator permissions.</span></span> 

## <a name="assign-the-dynamics-365-guides-license-to-user-accounts"></a><span data-ttu-id="cecc4-114">Affecter la licence Dynamics 365 Guides aux comptes d'utilisateur</span><span class="sxs-lookup"><span data-stu-id="cecc4-114">Assign the Dynamics 365 Guides license to user accounts</span></span>

<span data-ttu-id="cecc4-115">Après vous être inscrit(e) pour un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous devez affecter la licence [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] aux comptes d'utilisateur.</span><span class="sxs-lookup"><span data-stu-id="cecc4-115">After you sign up for a [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] subscription, you need to assign the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] license to user accounts.</span></span> <span data-ttu-id="cecc4-116">Pour ce faire :</span><span class="sxs-lookup"><span data-stu-id="cecc4-116">To do this:</span></span>

1. <span data-ttu-id="cecc4-117">Accédez au [Centre d'administration Microsoft 365](https://admin.microsoft.com/AdminPortal/Home) et assurez-vous que le curseur de l'option **Nouveau Centre d'administration** dans le coin supérieur droit de la page est bien défini sur **activé**.</span><span class="sxs-lookup"><span data-stu-id="cecc4-117">Go to the [Microsoft 365 admin center](https://admin.microsoft.com/AdminPortal/Home) and make sure that the slider for **The new admin center** option in the top right of the page is set to **on**.</span></span>

    <span data-ttu-id="cecc4-118">![Curseur Nouveau Centre d'administration](media/new-admin-center-slider.PNG "Curseur Nouveau Centre d'administration")</span><span class="sxs-lookup"><span data-stu-id="cecc4-118">![The new admin center slider](media/new-admin-center-slider.PNG "The new admin center slider")</span></span>

2.  <span data-ttu-id="cecc4-119">Assurez-vous que la licence [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] est affectée à un utilisateur.</span><span class="sxs-lookup"><span data-stu-id="cecc4-119">Make sure that the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] license is assigned to a user.</span></span> <span data-ttu-id="cecc4-120">Pour cela, dans le volet gauche, sélectionnez **Utilisateurs**, **Utilisateurs actifs**, puis activez la case à cocher en regard de l'utilisateur à ajouter.</span><span class="sxs-lookup"><span data-stu-id="cecc4-120">To do this, in the left pane, select **Users**, select **Active users**, and then select the check box for the user you want to add.</span></span> 

    <span data-ttu-id="cecc4-121">![Page Utilisateurs > Utilisateurs actifs](media/users-active-users.PNG "Page Utilisateurs > Utilisateurs actifs")</span><span class="sxs-lookup"><span data-stu-id="cecc4-121">![Users > Active Users page](media/users-active-users.PNG "Users > Active Users page")</span></span>
    
3.  <span data-ttu-id="cecc4-122">Sélectionnez **Gérer les licences de produit**.</span><span class="sxs-lookup"><span data-stu-id="cecc4-122">Select **Manage product licenses**.</span></span>

     <span data-ttu-id="cecc4-123">![Gérer les licences de produit](media/manage-product-licenses.PNG "Gérer les licences de produit")</span><span class="sxs-lookup"><span data-stu-id="cecc4-123">![Manage product licenses](media/manage-product-licenses.PNG "Manage product licenses")</span></span>

4.  <span data-ttu-id="cecc4-124">Sur la page **Licences de produit**, activez la case à cocher pour **[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]**.</span><span class="sxs-lookup"><span data-stu-id="cecc4-124">On the **Product licenses** page, select the check box for **[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]**.</span></span>
  
    <span data-ttu-id="cecc4-125">![Ajouter une licence utilisateur](media/guides-license.PNG "Ajouter une licence utilisateur")</span><span class="sxs-lookup"><span data-stu-id="cecc4-125">![Add user license](media/guides-license.PNG "Add user license")</span></span> 
 
## <a name="whats-next"></a><span data-ttu-id="cecc4-126">Étapes suivantes</span><span class="sxs-lookup"><span data-stu-id="cecc4-126">What's next?</span></span>

<span data-ttu-id="cecc4-127">Lorsque vous avez terminé cette étape, passez à l'étape 2 du processus de configuration : [Installer la solution](setup-step-two.md)</span><span class="sxs-lookup"><span data-stu-id="cecc4-127">When you're done with this step, go to step 2 in the setup process: [Install the solution](setup-step-two.md)</span></span>

<span data-ttu-id="cecc4-128">Si vous rencontrez des problèmes avec l'une des procédures de cette étape :</span><span class="sxs-lookup"><span data-stu-id="cecc4-128">If you have trouble with any of the procedures in this step, please:</span></span>

- <span data-ttu-id="cecc4-129">Posez des questions sur notre site communautaire à l'adresse https://community.dynamics.com/365/guides.</span><span class="sxs-lookup"><span data-stu-id="cecc4-129">Ask on our community site at https://community.dynamics.com/365/guides.</span></span>

- <span data-ttu-id="cecc4-130">Contactez le service clientèle à l'adresse https://dynamics.microsoft.com/support/.</span><span class="sxs-lookup"><span data-stu-id="cecc4-130">Contact customer service at https://dynamics.microsoft.com/support/.</span></span>
