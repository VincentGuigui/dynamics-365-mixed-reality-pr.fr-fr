---
author: makamat
description: Comment intégrer Dynamics 365 Field Service dans Dynamics 365 Guides (version préliminaire) pour que les techniciens de Field Service puissent suivre des instructions lorsqu'ils travaillent
ms.author: makamat
ms.date: 07/23/2019
ms.service: crm-online
ms.topic: article
title: Intégrer Dynamics 365 for Field Service dans Dynamics 365 Guides (version préliminaire)
ms.reviewer: v-brycho
ms.openlocfilehash: 1c54fb696df06e694927e671fa8b0ded1d7c497c
ms.sourcegitcommit: 8770ec043776563f3f9e87ee89f241c68015f576
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/31/2019
ms.locfileid: "1797404"
---
# <a name="integrate-dynamics-365-for-field-service-with-dynamics-365-guides-preview"></a>Intégrer Dynamics 365 for Field Service dans Dynamics 365 Guides (version préliminaire)

L'intégration de [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)] (inclus dans la version 104.1907.19001 de la version préliminaire publique) permet aux clients [!include[pn-field-service](../includes/pn-field-service.md)] d'associer des instructions aux tâches de [!include[pn-field-service](../includes/pn-field-service.md)] dans [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)]. Lorsque des tâches sont attribuées aux techniciens, ils peuvent alors utiliser un onglet **[!include[pn-field-service](../includes/pn-field-service.md)]** dédié dans l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] [!include[pn-hololens](../includes/pn-hololens.md)] pour lancer le guide et faire leur travail.

![Sélectionner un guide](media/select-guide.PNG "Sélectionner un guide")   

> [!IMPORTANT]
> Pour associer des guides à des tâches de service dans [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)], vous devez disposer d'une instance existante de [!include[pn-dyn-365](../includes/pn-dyn-365.md)] Customer Engagement (CRM) avec [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)] version 8.6.0.183 ou ultérieure. Vous devez également effectuer une mise à jour vers la version 104.1907.0.33 ou ultérieure de la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] ([voir comment mettre à niveau la solution Dynamics 365 Guides](upgrade.md)), et les versions 104.1907.19001 du PC [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et de l'application [!include[pn-hololens](../includes/pn-hololens.md)] ([voir comment s'inscrire à la version préliminaire et installer les applications](setup.md)).

## <a name="enable-your-technicians-to-use-dynamics-365-guides-for-work-orders"></a>Permettre aux techniciens d'utiliser Dynamics 365 Guides pour leur travail

1. Créez un guide à l'aide du PC [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et des applications [!include[pn-hololens](../includes/pn-hololens.md)]. Pour plus d'informations sur la création d'un guide, voir :
  
   - [Utiliser l'application de création sur PC pour créer un guide](pc-authoring.md)
   
   - [Utiliser l'application HoloLens pour placer vos hologrammes](hololens-authoring.md)
   
2. Créez un ordre de travail [!include[pn-field-service](../includes/pn-field-service.md)] et joignez-y une tâche de service. 

   1. Pour créer un ordre de travail dans [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)], sélectionnez **Ordres de travail** dans le volet de navigation de gauche, puis sélectionnez **Nouvel ordre de travail**.
   
      ![Créer un ordre de travail](media/create-work-order.PNG "Créer un ordre de travail")  
      
   2. Dans la vue **Tâches de service**, sélectionnez le bouton **Plus de commandes** (...), puis sélectionnez **Ajouter la nouvelle tâche de service à l'ordre de travail**.
   
      ![Ajouter une nouvelle tâche](media/add-new-task.PNG "Ajouter une nouvelle tâche")   
      
   3. Dans la vue **Nouvelle tâche de service de l'ordre de travail**, sélectionnez un type de tâche, entrez éventuellement une description, puis sélectionnez un guide à associer à la tâche de service. Sélectionnez **Enregistrer** une fois terminé.
   
      ![Sélectionner un type de tâche et associer un guide](media/new-work-order-options.PNG "Sélectionner un type de tâche et associer un guide")   
      
3. Affectez l'ordre de travail à une ressource (le technicien). Vous devez pour cela faire une réservation pour la ressource :

   1. Dans la vue **Ordre de travail**, faites défiler l'écran vers l'onglet **Réservations**, sélectionnez le bouton **Plus de commandes** (...), puis sélectionnez **Ajouter une nouvelle ressource pouvant être réservée**.
   
      ![Ajouter une ressource pouvant être réservée](media/add-bookable-resource.PNG "Ajouter une ressource pouvant être réservée")   
      
   2. Dans la vue **Nouvelle réservation d'une ressource**, planifiez la tâche de service au moment opportun pour le technicien, puis sélectionnez le technicien approprié comme ressource.
   
      ![Planifier et sélectionner une ressource](media/schedule-select-resource.PNG "Planifier et sélectionner une ressource")   
      
4. Demandez à votre technicien de lancer l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] dans [!include[pn-hololens](../includes/pn-hololens.md)]. Une fois connecté, le technicien voit l'onglet **[!include[pn-field-service](../includes/pn-field-service.md)]**. Cet onglet affiche le guide (et tous les autres guides qui lui ont été affectés) avec une brève description de la réservation et de la planification de l'ordre.

    ![Sélectionner un guide](media/select-guide-3.PNG "Sélectionner un guide")   
    
    
> [!NOTE]
> Gardez à l'esprit les points suivants :<br><br>- L'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] [!include[pn-hololens](../includes/pn-hololens.md)] affiche les ordres de travail planifiés pour le jour même et les huit jours suivants.<br><br>- Les ordres de travail continuent à s'afficher sur [!include[pn-hololens](../includes/pn-hololens.md)] jusqu'à ce qu'ils soient marqués comme **Terminés** dans [!include[pn-field-service](../includes/pn-field-service.md)] ou affectés à quelqu'un d'autre.

### <a name="known-issues"></a>Problèmes connus

- Les noms des tâches de service contenant plus de 50 caractères sont coupés dans l'interface utilisateur [!include[pn-hololens](../includes/pn-hololens.md)].

- Lorsque vous affectez un guide à une tâche de service [!include[pn-field-service](../includes/pn-field-service.md)], vous disposez d'une option pour créer un nouveau guide. N'utilisez pas cette option pour créer un nouveau guide. Les guides doivent être créés à l'aide du PC [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et des applications [!include[pn-hololens](../includes/pn-hololens.md)] tel que décrit à l'étape 1 de cette procédure.
   
   ![Créer un guide à partir de Field Service](media/create-new-guide-from-field-service.PNG "Créer un guide à partir de Field Service")   

### <a name="see-also"></a>Voir aussi

[Présentation de Dynamics 365 for Field Service](https://docs.microsoft.com/dynamics365/customer-engagement/field-service/overview)
      
      
   
