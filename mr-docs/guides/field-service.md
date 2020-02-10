---
author: makamat
description: Intégration de Dynamics 365 Field Service dans Dynamics 365 Guides pour que les techniciens sur le terrain puissent suivre un guide lorsqu'ils exécutent un ordre de travail
ms.author: makamat
ms.date: 01/28/2020
ms.service: crm-online
ms.topic: article
title: Intégrer Dynamics 365 Field Service dans Dynamics 365 Guides
ms.reviewer: v-brycho
ms.openlocfilehash: 090dc5e7dd61f9f26acb10c4764483903171574a
ms.sourcegitcommit: 217d31bb34e67a6b8823d5ddac7ef8d56d054139
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/29/2020
ms.locfileid: "2994743"
---
# <a name="integrate-dynamics-365-field-service-with-dynamics-365-guides"></a><span data-ttu-id="c9f6b-103">Intégrer Dynamics 365 Field Service dans Dynamics 365 Guides</span><span class="sxs-lookup"><span data-stu-id="c9f6b-103">Integrate Dynamics 365 Field Service with Dynamics 365 Guides</span></span>

<span data-ttu-id="c9f6b-104">L'intégration de [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)] (disponible dans la version 104.1907.19001) permet aux clients [!include[pn-field-service](../includes/pn-field-service.md)] d'associer des guides aux tâches [!include[pn-field-service](../includes/pn-field-service.md)] dans [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)].</span><span class="sxs-lookup"><span data-stu-id="c9f6b-104">[!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)] integration (included in version 104.1907.19001) enables [!include[pn-field-service](../includes/pn-field-service.md)] customers to attach guides to [!include[pn-field-service](../includes/pn-field-service.md)] tasks in [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)].</span></span> <span data-ttu-id="c9f6b-105">Lorsque des tâches sont attribuées aux techniciens, ils peuvent alors utiliser un onglet **[!include[pn-field-service](../includes/pn-field-service.md)]** dédié dans l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] [!include[pn-hololens](../includes/pn-hololens.md)] pour lancer le guide et faire leur travail.</span><span class="sxs-lookup"><span data-stu-id="c9f6b-105">When work orders are assigned to technicians, the technicians can use a dedicated **[!include[pn-field-service](../includes/pn-field-service.md)]** tab in the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] [!include[pn-hololens](../includes/pn-hololens.md)] app to launch the assigned guide and do their work.</span></span>

<span data-ttu-id="c9f6b-106">![Sélectionner un guide](media/select-guide.PNG "Sélectionner un guide")</span><span class="sxs-lookup"><span data-stu-id="c9f6b-106">![Select guide](media/select-guide.PNG "Select guide")</span></span>   

> [!IMPORTANT]
> <span data-ttu-id="c9f6b-107">Pour associer des guides à des tâches de service dans [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)], vous devez disposer d'une instance existante de [!include[pn-dyn-365](../includes/pn-dyn-365.md)] Customer Engagement (CRM) avec [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)] version 8.6.0.183 ou ultérieure.</span><span class="sxs-lookup"><span data-stu-id="c9f6b-107">To attach guides to service tasks in [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)], you need to have an existing [!include[pn-dyn-365](../includes/pn-dyn-365.md)] Customer Engagement (CRM) instance with [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)] version 8.6.0.183 or later.</span></span> <span data-ttu-id="c9f6b-108">Vous devez également effectuer une mise à jour vers la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] version 104.1907.0.33 ou ultérieure ([en savoir plus sur la mise à niveau de la solution Dynamics 365 Guides](upgrade.md)) et les applications sur PC [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et [!include[pn-hololens](../includes/pn-hololens.md)] versions 104.1907.19001.</span><span class="sxs-lookup"><span data-stu-id="c9f6b-108">You also need to update to [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] solution version 104.1907.0.33 or later ([learn how to upgrade the Dynamics 365 Guides solution](upgrade.md)) and [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] PC and [!include[pn-hololens](../includes/pn-hololens.md)] app versions 104.1907.19001.</span></span>

## <a name="enable-your-technicians-to-use-dynamics-365-guides-for-work-orders"></a><span data-ttu-id="c9f6b-109">Permettre aux techniciens d'utiliser Dynamics 365 Guides pour leur travail</span><span class="sxs-lookup"><span data-stu-id="c9f6b-109">Enable your technicians to use Dynamics 365 Guides for work orders</span></span>

1. <span data-ttu-id="c9f6b-110">Créez un guide à l'aide des applications sur PC [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et [!include[pn-hololens](../includes/pn-hololens.md)].</span><span class="sxs-lookup"><span data-stu-id="c9f6b-110">Create a guide using the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] PC and [!include[pn-hololens](../includes/pn-hololens.md)] apps.</span></span> <span data-ttu-id="c9f6b-111">Pour plus d'informations sur la création d'un guide, voir :</span><span class="sxs-lookup"><span data-stu-id="c9f6b-111">For information on creating a guide, see:</span></span>
  
   - [<span data-ttu-id="c9f6b-112">Présentation de la création d'un guide dans l'application du PC</span><span class="sxs-lookup"><span data-stu-id="c9f6b-112">Overview of authoring a guide in the PC app</span></span>](pc-app-overview.md)
   
   - [<span data-ttu-id="c9f6b-113">Présentation de la création d'un guide dans l'application HoloLens</span><span class="sxs-lookup"><span data-stu-id="c9f6b-113">Overview of authoring a guide in the HoloLens app</span></span>](hololens-app-overview.md)
   
2. <span data-ttu-id="c9f6b-114">Créez un ordre de travail [!include[pn-field-service](../includes/pn-field-service.md)] et joignez-y une tâche de service.</span><span class="sxs-lookup"><span data-stu-id="c9f6b-114">Create a [!include[pn-field-service](../includes/pn-field-service.md)] work order and attach a service task to it.</span></span> 

   1. <span data-ttu-id="c9f6b-115">Pour créer un ordre de travail dans [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)], sélectionnez **Ordres de travail** dans le volet de navigation de gauche, puis sélectionnez **Nouvel ordre de travail**.</span><span class="sxs-lookup"><span data-stu-id="c9f6b-115">To create a new work order in [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)], select **Work Orders** in the left navigation, and then select **New Work Order**.</span></span>
   
      <span data-ttu-id="c9f6b-116">![Créer un ordre de travail](media/create-work-order.PNG "Créer un ordre de travail")</span><span class="sxs-lookup"><span data-stu-id="c9f6b-116">![Create work order](media/create-work-order.PNG "Create work order")</span></span>  
      
   2. <span data-ttu-id="c9f6b-117">Dans la vue **Tâches de service**, sélectionnez le bouton **Plus de commandes** (...), puis sélectionnez **Ajouter la nouvelle tâche de service à l'ordre de travail**.</span><span class="sxs-lookup"><span data-stu-id="c9f6b-117">In the **Service Tasks** view, select the **More Commands** button (...), and then select **Add New Work Order Service Task**.</span></span>
   
      <span data-ttu-id="c9f6b-118">![Ajouter une nouvelle tâche](media/add-new-task.PNG "Ajouter une nouvelle tâche")</span><span class="sxs-lookup"><span data-stu-id="c9f6b-118">![Add new task](media/add-new-task.PNG "Add new task")</span></span>   
      
   3. <span data-ttu-id="c9f6b-119">Dans la vue **Nouvelle tâche de service de l'ordre de travail**, sélectionnez un type de tâche, entrez éventuellement une description, puis sélectionnez un guide à associer à la tâche de service.</span><span class="sxs-lookup"><span data-stu-id="c9f6b-119">In the **New Work Order Service Task** view, select a task type, provide an optional description, and then select a guide to associate with the service task.</span></span> <span data-ttu-id="c9f6b-120">Sélectionnez **Enregistrer** une fois terminé.</span><span class="sxs-lookup"><span data-stu-id="c9f6b-120">Select **Save** when you're done.</span></span>
   
      <span data-ttu-id="c9f6b-121">![Sélectionner un type de tâche et associer un guide](media/new-work-order-options.PNG "Sélectionner un type de tâche et associer un guide")</span><span class="sxs-lookup"><span data-stu-id="c9f6b-121">![Select task type and associate guide](media/new-work-order-options.PNG "Select task type and associate guide")</span></span>   
      
3. <span data-ttu-id="c9f6b-122">Affectez l'ordre de travail à une ressource (le technicien).</span><span class="sxs-lookup"><span data-stu-id="c9f6b-122">Assign the work order to a resource (the technician).</span></span> <span data-ttu-id="c9f6b-123">Vous devez pour cela faire une réservation pour la ressource :</span><span class="sxs-lookup"><span data-stu-id="c9f6b-123">To do this, you need to create a booking for the resource:</span></span>

   1. <span data-ttu-id="c9f6b-124">Dans la vue **Ordre de travail**, faites défiler l'écran vers l'onglet **Réservations**, sélectionnez le bouton **Plus de commandes** (...), puis sélectionnez **Ajouter une nouvelle ressource pouvant être réservée**.</span><span class="sxs-lookup"><span data-stu-id="c9f6b-124">In the **Work Order** view, scroll down to the **Bookings** tab, select the **More Commands** (...) button, and then select **Add New Bookable Resource**.</span></span>
   
      <span data-ttu-id="c9f6b-125">![Ajouter une ressource pouvant être réservée](media/add-bookable-resource.PNG "Ajouter une ressource pouvant être réservée")</span><span class="sxs-lookup"><span data-stu-id="c9f6b-125">![Add bookable resource](media/add-bookable-resource.PNG "Add bookable resource")</span></span>   
      
   2. <span data-ttu-id="c9f6b-126">Dans la vue **Nouvelle réservation d'une ressource**, planifiez la tâche de service au moment opportun pour le technicien, puis sélectionnez le technicien approprié comme ressource.</span><span class="sxs-lookup"><span data-stu-id="c9f6b-126">In the **New Bookable Resource Booking** view, schedule the service task at the appropriate time for the technician, and then select the appropriate technician as the resource.</span></span>
   
      <span data-ttu-id="c9f6b-127">![Planifier et sélectionner une ressource](media/schedule-select-resource.PNG "Planifier et sélectionner une ressource")</span><span class="sxs-lookup"><span data-stu-id="c9f6b-127">![Schedule and select resource](media/schedule-select-resource.PNG "Schedule and select resource")</span></span>   
      
4. <span data-ttu-id="c9f6b-128">Demandez à votre technicien de lancer l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] dans [!include[pn-hololens](../includes/pn-hololens.md)].</span><span class="sxs-lookup"><span data-stu-id="c9f6b-128">Have your technician launch the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] app on [!include[pn-hololens](../includes/pn-hololens.md)].</span></span> <span data-ttu-id="c9f6b-129">Une fois connecté, le technicien voit l'onglet **[!include[pn-field-service](../includes/pn-field-service.md)]**. Cet onglet affiche le guide (et tous les autres guides qui lui ont été affectés) avec une brève description de la réservation et de la planification de l'ordre.</span><span class="sxs-lookup"><span data-stu-id="c9f6b-129">After signing in, the technician will see the **[!include[pn-field-service](../includes/pn-field-service.md)]** tab. The tab shows the guide (and any other guides assigned to them) along with a brief description of the booking and when that order is scheduled.</span></span>

    <span data-ttu-id="c9f6b-130">![Sélectionner un guide](media/select-guide-3.PNG "Sélectionner un guide")</span><span class="sxs-lookup"><span data-stu-id="c9f6b-130">![Select guide](media/select-guide-3.PNG "Select guide")</span></span>   
    

> [!NOTE]
> <span data-ttu-id="c9f6b-131">Gardez à l'esprit les points suivants :</span><span class="sxs-lookup"><span data-stu-id="c9f6b-131">Keep the following points in mind:</span></span>
>
> - <span data-ttu-id="c9f6b-132">L'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] [!include[pn-hololens](../includes/pn-hololens.md)] affiche les ordres de travail planifiés pour le jour même et les huit jours suivants.</span><span class="sxs-lookup"><span data-stu-id="c9f6b-132">The [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] [!include[pn-hololens](../includes/pn-hololens.md)] app shows work orders that are scheduled for the current day and the following eight days.</span></span>
>
> - <span data-ttu-id="c9f6b-133">Les ordres de travail continuent à s'afficher sur [!include[pn-hololens](../includes/pn-hololens.md)] jusqu'à ce qu'ils soient marqués comme **Terminés** dans [!include[pn-field-service](../includes/pn-field-service.md)] ou affectés à quelqu'un d'autre.</span><span class="sxs-lookup"><span data-stu-id="c9f6b-133">Work orders continue to appear on [!include[pn-hololens](../includes/pn-hololens.md)] until they are either marked as **Complete** in [!include[pn-field-service](../includes/pn-field-service.md)] or assigned to someone else.</span></span>

### <a name="known-issues"></a><span data-ttu-id="c9f6b-134">Problèmes connus</span><span class="sxs-lookup"><span data-stu-id="c9f6b-134">Known issues</span></span>

- <span data-ttu-id="c9f6b-135">Les noms des tâches de service contenant plus de 50 caractères sont coupés dans l'interface utilisateur [!include[pn-hololens](../includes/pn-hololens.md)].</span><span class="sxs-lookup"><span data-stu-id="c9f6b-135">Service task names that are longer than approximately 50 characters are cut off in the [!include[pn-hololens](../includes/pn-hololens.md)] user interface.</span></span>

- <span data-ttu-id="c9f6b-136">Lorsque vous affectez un guide à une tâche de service [!include[pn-field-service](../includes/pn-field-service.md)], vous disposez d'une option pour créer un nouveau guide.</span><span class="sxs-lookup"><span data-stu-id="c9f6b-136">When assigning a guide to a [!include[pn-field-service](../includes/pn-field-service.md)] service task, there's an option to create a new guide.</span></span> <span data-ttu-id="c9f6b-137">N'utilisez pas cette option pour créer un nouveau guide.</span><span class="sxs-lookup"><span data-stu-id="c9f6b-137">Do not use this option to create a new guide.</span></span> <span data-ttu-id="c9f6b-138">Les guides doivent être créés à l'aide du PC [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et des applications [!include[pn-hololens](../includes/pn-hololens.md)] tel que décrit à l'étape 1 de cette procédure.</span><span class="sxs-lookup"><span data-stu-id="c9f6b-138">Guides must be created using the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] PC and [!include[pn-hololens](../includes/pn-hololens.md)] apps as described in step 1 of this procedure.</span></span>
   
   <span data-ttu-id="c9f6b-139">![Créer un guide à partir de Field Service](media/create-new-guide-from-field-service.PNG "Créer un guide à partir de Field Service")</span><span class="sxs-lookup"><span data-stu-id="c9f6b-139">![Create a new guide from Field Service](media/create-new-guide-from-field-service.PNG "Create a new guide from Field Service")</span></span>   

## <a name="see-also"></a><span data-ttu-id="c9f6b-140">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="c9f6b-140">See also</span></span>

[<span data-ttu-id="c9f6b-141">Présentation de Dynamics 365 Field Service</span><span class="sxs-lookup"><span data-stu-id="c9f6b-141">Overview of Dynamics 365 Field Service</span></span>](https://docs.microsoft.com/dynamics365/customer-engagement/field-service/overview)
      
      
   
