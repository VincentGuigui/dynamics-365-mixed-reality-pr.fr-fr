---
author: Mamaylya
description: Découvrez comment mettre à niveau la solution Microsoft Dynamics 365 Guides lorsqu'une nouvelle version nécessite une mise à jour.
ms.author: mamaylya
ms.date: 01/28/2020
ms.service: crm-online
ms.topic: article
title: Mettre à niveau la solution Dynamics 365 Guides
ms.reviewer: v-brycho
ms.openlocfilehash: e3ade875c4ef681ee89fcf239a4903c436ae3601
ms.sourcegitcommit: 217d31bb34e67a6b8823d5ddac7ef8d56d054139
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/29/2020
ms.locfileid: "2994734"
---
# <a name="upgrade-the-dynamics-365-guides-solution"></a><span data-ttu-id="456f1-103">Mettre à niveau la solution Dynamics 365 Guides</span><span class="sxs-lookup"><span data-stu-id="456f1-103">Upgrade the Dynamics 365 Guides solution</span></span>

<span data-ttu-id="456f1-104">Cette rubrique concerne les administrateurs [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365](../includes/pn-dyn-365.md)].</span><span class="sxs-lookup"><span data-stu-id="456f1-104">This topic is for [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365](../includes/pn-dyn-365.md)] administrators.</span></span> <span data-ttu-id="456f1-105">Certaines versions de [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] nécessitent une mise à jour de la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="456f1-105">Some releases of [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] require an update to the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] solution.</span></span> <span data-ttu-id="456f1-106">Lorsqu'une mise à jour est nécessaire, l'utilisateur verra une notification s'afficher dans le volet **Nouveautés**.</span><span class="sxs-lookup"><span data-stu-id="456f1-106">When an update is required, the user will see a notification in the **What's new** panel.</span></span>

<span data-ttu-id="456f1-107">Gardez à l'esprit les points suivants :</span><span class="sxs-lookup"><span data-stu-id="456f1-107">Keep the following in mind:</span></span>

- <span data-ttu-id="456f1-108">Avant de mettre la solution à jour dans le Centre d'administration Power Platform, assurez-vous que le PC [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et les applications [!include[pn-hololens](../includes/pn-hololens.md)] ont été mis à jour vers la dernière version du [!include[cc-microsoft](../includes/cc-microsoft.md)] Store.</span><span class="sxs-lookup"><span data-stu-id="456f1-108">Before you update the solution in the Power Platform admin center, make sure that the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] PC and [!include[pn-hololens](../includes/pn-hololens.md)] apps have been updated to the latest version from the [!include[cc-microsoft](../includes/cc-microsoft.md)] Store.</span></span>

- <span data-ttu-id="456f1-109">Les mises à jour de la solution doivent être effectuées lorsque les applications sur PC et [!include[pn-hololens](../includes/pn-hololens.md)] ne sont pas utilisées.</span><span class="sxs-lookup"><span data-stu-id="456f1-109">Updates to the solution must be done when the PC and [!include[pn-hololens](../includes/pn-hololens.md)] apps are not in use.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="456f1-110">Si vous utilisez actuellement la version préliminaire publique [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] pour obtenir la version d'octobre 2019, vous devez rechercher la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], puis sélectionner **Installer** au lieu de **Mettre à niveau**.</span><span class="sxs-lookup"><span data-stu-id="456f1-110">If you're currently using the public preview version of [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], to get the October 2019 release, you'll need to search for the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] solution, and then select **Install** instead of **Upgrade**.</span></span> <span data-ttu-id="456f1-111">Cela installe la version en disponibilité générale de la solution et supprime la solution préliminaire publique.</span><span class="sxs-lookup"><span data-stu-id="456f1-111">This installs the general availability (GA) version of the solution and removes the public preview solution.</span></span> <span data-ttu-id="456f1-112">Pour plus d'informations, voir [Transition entre la version préliminaire publique et la disponibilité générale](public-preview-transition.md).</span><span class="sxs-lookup"><span data-stu-id="456f1-112">For more information, see [Transition from public preview to GA](public-preview-transition.md).</span></span>

<span data-ttu-id="456f1-113">Pour mettre à niveau la solution :</span><span class="sxs-lookup"><span data-stu-id="456f1-113">To upgrade the solution:</span></span>

1. <span data-ttu-id="456f1-114">Accédez au [Centre d'administration Power Platform](https://admin.powerplatform.microsoft.com/environments), puis connectez-vous avec les informations d'identification disposant des autorisations de l'administrateur pour [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="456f1-114">Go to the [Power Platform admin center](https://admin.powerplatform.microsoft.com/environments) and sign in with the user credentials that have admin permissions for [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span></span> 

2. <span data-ttu-id="456f1-115">Pour sélectionner l'environnement, activez la case à cocher, sélectionnez le bouton **Autres actions d'environnement** (les trois points), puis sélectionnez **Gérer les solutions**.</span><span class="sxs-lookup"><span data-stu-id="456f1-115">To select the environment, select the check mark, select the **More environment actions** (three dots) button, and then select **Manage Solutions**.</span></span> 

   <span data-ttu-id="456f1-116">![Gérer les solutions](media/manage-solutions.PNG "Gérer les solutions")</span><span class="sxs-lookup"><span data-stu-id="456f1-116">![Manage solutions](media/manage-solutions.PNG "Manage solutions")</span></span>

3. <span data-ttu-id="456f1-117">Dans la liste des solutions, sélectionnez **[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]**, puis sélectionnez **Mettre à niveau**.</span><span class="sxs-lookup"><span data-stu-id="456f1-117">Select **[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]** in the list of solutions, and then select **Upgrade**.</span></span>
 
   <span data-ttu-id="456f1-118">![Bouton Mettre à niveau](media/upgrade.PNG "Bouton Mettre à niveau")</span><span class="sxs-lookup"><span data-stu-id="456f1-118">![Upgrade button](media/upgrade.PNG "Upgrade button")</span></span>   
  
4. <span data-ttu-id="456f1-119">Examinez les Conditions de service, puis sélectionnez **Accepter** si vous êtes prêt(e) à commencer la mise à niveau.</span><span class="sxs-lookup"><span data-stu-id="456f1-119">Review the Terms of service, and then select **Accept** if you're ready to start the upgrade.</span></span> 

   <span data-ttu-id="456f1-120">Le statut de la solution passe à **Installation en attente,** puis à **Installé** lorsque la mise à niveau est terminée.</span><span class="sxs-lookup"><span data-stu-id="456f1-120">The status of the solution changes to **Installation pending,** and then changes to **Installed** when the upgrade is complete.</span></span> 
 
<span data-ttu-id="456f1-121">Pour plus d'informations sur la mise à niveau de la solution [!include[pn-dyn-365](../includes/pn-dyn-365.md)][voir Installer, mettre à jour ou supprimer une solution par défaut](https://docs.microsoft.com/dynamics365/customer-engagement/admin/install-remove-preferred-solution).</span><span class="sxs-lookup"><span data-stu-id="456f1-121">For more information about upgrading a [!include[pn-dyn-365](../includes/pn-dyn-365.md)] solution, [see Install, update, or remove a preferred solution](https://docs.microsoft.com/dynamics365/customer-engagement/admin/install-remove-preferred-solution).</span></span>
