---
author: Mamaylya
description: Mettre à niveau la solution Dynamics 365 Guides (version préliminaire)
ms.author: mamaylya
ms.date: 10/01/2019
ms.service: crm-online
ms.topic: article
title: Mettre à niveau la solution Dynamics 365 Guides (version préliminaire)
ms.reviewer: v-brycho
ms.openlocfilehash: 2cb38358f137f362c6066e1a73fc5bfe820fe0f6
ms.sourcegitcommit: f37698eb33fd4d198b054e73ce3d9ec680c56e21
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/02/2019
ms.locfileid: "2537618"
---
# <a name="upgrade-the-dynamics-365-guides-solution-for-admins"></a><span data-ttu-id="faf97-103">Mettre à niveau la solution Dynamics 365 Guides (pour les administrateurs)</span><span class="sxs-lookup"><span data-stu-id="faf97-103">Upgrade the Dynamics 365 Guides solution (for admins)</span></span>

<span data-ttu-id="faf97-104">Cette rubrique concerne les administrateurs [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365](../includes/pn-dyn-365.md)].</span><span class="sxs-lookup"><span data-stu-id="faf97-104">This topic is for [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365](../includes/pn-dyn-365.md)] administrators.</span></span> <span data-ttu-id="faf97-105">Certaines versions de [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] nécessitent une mise à jour de la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="faf97-105">Some releases of [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] require an update to the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] solution.</span></span> <span data-ttu-id="faf97-106">Lorsqu'une mise à jour est nécessaire, l'utilisateur verra une notification s'afficher dans le volet **Nouveautés**.</span><span class="sxs-lookup"><span data-stu-id="faf97-106">When an update is required, the user will see a notification in the **What's new** panel.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="faf97-107">Gardez à l'esprit les points suivants :</span><span class="sxs-lookup"><span data-stu-id="faf97-107">Keep the following in mind:</span></span><br><br><span data-ttu-id="faf97-108">- Avant de mettre la solution à jour dans le Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)], assurez-vous que le PC [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et les applications [!include[pn-hololens](../includes/pn-hololens.md)] ont été mis à jour vers la dernière version du [!include[cc-microsoft](../includes/cc-microsoft.md)] Store.</span><span class="sxs-lookup"><span data-stu-id="faf97-108">- Before updating the solution in the [!include[pn-dyn-365](../includes/pn-dyn-365.md)] Administration Center, make sure that the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] PC and [!include[pn-hololens](../includes/pn-hololens.md)] apps have been updated to the latest version from the [!include[cc-microsoft](../includes/cc-microsoft.md)] Store.</span></span><br><br><span data-ttu-id="faf97-109">- Les mises à jour de la solution doivent être effectuées lorsque les applications sur PC et [!include[pn-hololens](../includes/pn-hololens.md)] ne sont pas utilisées.</span><span class="sxs-lookup"><span data-stu-id="faf97-109">- Updates to the solution must be done when the PC and [!include[pn-hololens](../includes/pn-hololens.md)] apps are not in use.</span></span>  

<span data-ttu-id="faf97-110">Pour mettre à niveau la solution :</span><span class="sxs-lookup"><span data-stu-id="faf97-110">To upgrade the solution:</span></span>

1. <span data-ttu-id="faf97-111">Accédez au Centre d'administration Dynamics 365, puis connectez-vous avec les informations d'identification disposant des autorisations de l'administrateur pour [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="faf97-111">Go to the Dynamics 365 Administration Center and sign in with the user credentials that have admin permissions for [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span></span> 

   > [!NOTE]
   > <span data-ttu-id="faf97-112">Pour accéder au Centre d'administration Dynamics 365, accédez au [Centre d'administration Microsoft 365](https://admin.microsoft.com/AdminPortal/Home), puis sélectionnez **Centres d'administration** > **Dynamics 365**, comme indiqué ci-dessous.</span><span class="sxs-lookup"><span data-stu-id="faf97-112">To go to the Dynamics 365 Administration Center, go to the [Microsoft 365 Admin Center](https://admin.microsoft.com/AdminPortal/Home), and then select **Admin centers** > **Dynamics 365** as shown below.</span></span>
   
   <span data-ttu-id="faf97-113">![Centre d'administration Microsoft](media/microsoft-admin-center.PNG "Centre d'administration Microsoft")</span><span class="sxs-lookup"><span data-stu-id="faf97-113">![Microsoft Admin Center](media/microsoft-admin-center.PNG "Microsoft Admin Center")</span></span> 

2. <span data-ttu-id="faf97-114">Sélectionnez l'onglet **Instances**, puis choisissez une instance ayant la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] installée.</span><span class="sxs-lookup"><span data-stu-id="faf97-114">Select the **Instances** tab, and then choose an instance that has the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] solution installed.</span></span>

3. <span data-ttu-id="faf97-115">Sélectionnez le petit bouton Modifier en regard de **Solutions** pour afficher la liste des solutions.</span><span class="sxs-lookup"><span data-stu-id="faf97-115">Select the small edit button next to **Solutions** to see the list of solutions.</span></span> 
 
   <span data-ttu-id="faf97-116">![Bouton Solutions](media/solutions.PNG "Bouton Solutions")</span><span class="sxs-lookup"><span data-stu-id="faf97-116">![Solutions button](media/solutions.PNG "Solutions button")</span></span>
 
4. <span data-ttu-id="faf97-117">Dans la liste des solutions, sélectionnez **[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]**, puis sélectionnez **Mettre à niveau**.</span><span class="sxs-lookup"><span data-stu-id="faf97-117">In the list of solutions, select **[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]**, and then select **Upgrade**.</span></span>  
 
   <span data-ttu-id="faf97-118">![Bouton Mettre à niveau](media/upgrade.PNG "Bouton Mettre à niveau")</span><span class="sxs-lookup"><span data-stu-id="faf97-118">![Upgrade button](media/upgrade.PNG "Upgrade button")</span></span>
   
   > [!IMPORTANT]
   > <span data-ttu-id="faf97-119">Si vous utilisez actuellement la version préliminaire publique [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] pour obtenir la version d'octobre 2019, vous devez rechercher la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], puis sélectionner **Installer** au lieu de **Mettre à niveau**.</span><span class="sxs-lookup"><span data-stu-id="faf97-119">If you're currently using the public preview version of [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], to get the October 2019 release, you'll need to search for the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] solution, and then select **Install** instead of **Upgrade**.</span></span> <span data-ttu-id="faf97-120">Cela installe la version en disponibilité générale de la solution et supprime la solution préliminaire publique.</span><span class="sxs-lookup"><span data-stu-id="faf97-120">This will install the GA version of the solution and remove the public preview solution.</span></span>
   
5. <span data-ttu-id="faf97-121">Examinez les Conditions de service, puis sélectionnez **Accepter** si vous êtes prêt(e) à commencer la mise à niveau.</span><span class="sxs-lookup"><span data-stu-id="faf97-121">Review the Terms of service, and then select **Accept** if you're ready to start the upgrade.</span></span> 

   <span data-ttu-id="faf97-122">Le statut de la solution passe à **Installation en attente,** puis à **Installé** lorsque la mise à niveau est terminée.</span><span class="sxs-lookup"><span data-stu-id="faf97-122">The status of the solution changes to **Installation pending,** and then changes to **Installed** when the upgrade is complete.</span></span> 
 
<span data-ttu-id="faf97-123">Pour plus d'informations sur la mise à niveau de la solution [!include[pn-dyn-365](../includes/pn-dyn-365.md)][voir Installer, mettre à jour ou supprimer une solution par défaut](https://docs.microsoft.com/dynamics365/customer-engagement/admin/install-remove-preferred-solution).</span><span class="sxs-lookup"><span data-stu-id="faf97-123">For more information on upgrading a [!include[pn-dyn-365](../includes/pn-dyn-365.md)] solution, [see Install, update, or remove a preferred solution](https://docs.microsoft.com/dynamics365/customer-engagement/admin/install-remove-preferred-solution).</span></span>
