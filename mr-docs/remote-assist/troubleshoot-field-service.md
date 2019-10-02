---
author: bencorn
description: Comment vous assurer de disposer des version, vues et données qui conviennent pour intégrer Dynamics 365 for Field Service dans Dynamics 365 Remote Assist
ms.author: bencorn
ms.date: 06/04/2019
ms.service: crm-online
ms.topic: article
title: Intégrer Dynamics 365 for Field Service dans Dynamics 365 Remote Assist
ms.reviewer: v-brycho
ms.openlocfilehash: 59e3017158b82a9bc079247a0c2c31f09c57682a
ms.sourcegitcommit: 73dff7bbeecc69366e1b98fa4db4a7b00762fb80
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 08/02/2019
ms.locfileid: "1847943"
---
# <a name="troubleshoot-field-service-integration-with-dynamics-365-remote-assist"></a>Détecter les problèmes d'intégration de Field Service dans Dynamics 365 Remote Assist

Si votre organisation utilise [Dynamics 365 for Field Service](https://dynamics.microsoft.com/en-us/field-service/overview/?&OCID=AID720979_SEM_yeaT05hp&lnkd=Bing_D365_Brand) pour gérer les ordres de travail [!include[pn-field-service](../includes/pn-field-service.md)], le collaborateur de première ligne, en utilisant [!include[pn-hololens](../includes/pn-hololens.md)], peut consulter les réservations [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)] depuis [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] et appeler rapidement l'expert répertorié dans le champ **Contacter le support**, le cas échéant. Cela permet aux collaborateurs de première ligne d'effectuer des appels tête relevée, mains libres via [!include[pn-hololens](../includes/pn-hololens.md)] dans le cadre d'une réservation [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)].

Cette rubrique décrit les éléments suivants :

- Conditions d'intégration de [!include[pn-field-service](../includes/pn-field-service.md)]
- Comment s'assurer que [!include[pn-field-service](../includes/pn-field-service.md)] est correctement configuré 
- Comment mettre à jour l'instance [!include[pn-dyn-365](../includes/pn-dyn-365.md)] si vous n'avez pas la version correcte de [!include[pn-field-service](../includes/pn-field-service.md)]
- Comment ajouter des données pour des champs obligatoires dans une réservation et un ordre de travail [!include[pn-field-service](../includes/pn-field-service.md)]
- Comment personnaliser le volet **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]** qui s'affiche dans [!include[pn-remote-assist](../includes/pn-remote-assist.md)]

## <a name="requirements"></a>Configuration requise

Avant de commencer, assurez-vous d'avoir la configuration suivante :

- Un tenant [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-azure](../includes/pn-azure.md)] avec des abonnements [!include[pn-dyn-365](../includes/pn-dyn-365.md)] **et** [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)]. Les deux sont requis. [!include[pn-remote-assist](../includes/pn-remote-assist.md)] n'est inclus dans aucune offre groupée [!include[pn-dyn-365](../includes/pn-dyn-365.md)].

  > [!NOTE]  
  > Le tenant peut avoir plus d'une instance [!include[pn-dyn-365](../includes/pn-dyn-365.md)]. [!include[pn-remote-assist](../includes/pn-remote-assist.md)] permet de sélectionner une instance depuis l'application.

- Vous devez avoir un accès administrateur pour ajouter ou mettre à jour l'instance de tenant [!include[pn-dyn-365](../includes/pn-dyn-365.md)].
- L'application [!include[pn-field-service](../includes/pn-field-service.md)] doit être installée sur l'instance [!include[pn-dyn-365](../includes/pn-dyn-365.md)], et elle doit inclure la vue **Mes réservations en cours**. Pour s'assurer que cette vue est installée, nous recommandons [!include[pn-field-service](../includes/pn-field-service.md)] version 8.2, ou ultérieure. Cette rubrique décrit la procédure permettant de s'assurer de disposer de la version et de la vue correctes.
- Le tenant doit avoir au moins deux comptes d'utilisateur.
- Les licences suivantes doivent être affectées aux comptes d'utilisateur :
  - Licence [!include[pn-office-365](../includes/pn-office-365.md)] qui inclut [!include[cc-microsoft](../includes/cc-microsoft.md)][!include[pn-teams](../includes/pn-teams.md)]
  - [!include[pn-remote-assist](../includes/pn-remote-assist.md)]
  - Licence [!include[pn-dyn-365](../includes/pn-dyn-365.md)] qui inclut [!include[pn-field-service](../includes/pn-field-service.md)]

## <a name="confirm-that-the-my-in-progress-bookings-view-is-included"></a>Confirmer que la vue **Mes réservations en cours** est incluse

Si vous avez une instance mais que vous n'êtes pas certain que la vue correcte soit installée, procédez comme suit pour confirmer :

1. Assurez-vous d'être inscrit comme administrateur pour l'instance [!include[pn-dyn-365](../includes/pn-dyn-365.md)].

2. Sélectionnez **Service** > **Paramètres** > **Personnalisations** > **Personnaliser le système**.

   ![Sélection de Personnalisations](media/Customizations.PNG "Sélection de Personnalisations")
   
3. Dans l'écran [!include[pn-powerapps](../includes/pn-powerapps.md)], développez **Entités**, développez l'entité **Réservation de ressources pouvant être réservées**, puis sélectionnez **Vues**.

4. Dans l'écran **Vues**, vérifiez que la vue **Mes réservations en cours** est répertoriée.

   ![Vue Ressource pouvant être réservée](media/bookable-resource-views.PNG "Vue Ressource pouvant être réservée")
   
5. Effectuez l'une des opérations suivantes :

   - Si la vue est répertoriée, allez à [Ajouter un ordre de travail et une réservation](#add-a-work-order-and-booking) plus loin dans cette rubrique.
   
   - Si la vue n'est pas répertoriée, allez à [Mettre à jour l'instance Dynamics 365](#upgrade-the-dynamics-365-instance), la prochaine procédure de cette rubrique.
   
## <a name="upgrade-the-dynamics-365-instance"></a>Mettre à jour l'instance Dynamics 365

Si la vue **Mes réservations en cours** n'est pas répertoriée comme décrit dans la procédure précédente, vous devez mettre à jour votre [!include[pn-field-service](../includes/pn-field-service.md)] version 8.2, ou ultérieure. Les mises à jour de[!include[pn-dyn-365](../includes/pn-dyn-365.md)] ne se produisent automatiquement ; elles sont effectuées par les clients. 

Pour mettre à jour une instance :

1. Allez au centre d'administration de [!include[pn-dyn-365](../includes/pn-dyn-365.md)], sélectionnez l'onglet **Instances**, puis sélectionnez **Solutions** pour voir de quelle version de [!include[pn-field-service](../includes/pn-field-service.md)] vous disposez. 

   ![Centre d'administration affichant la version de Field Service](media/admin-center.PNG "Centre d'administration affichant la version de Field Service")

2. Effectuez l'une des opérations suivantes :

   - Si vous n'avez pas la version 8.2 ou ultérieure, un bouton **Mettre à jour** apparaît à droite de l'écran dans la zone **[!include[pn-field-service](../includes/pn-field-service.md)]**. Sélectionnez le bouton **Mettre à jour** pour démarrer le processus de mise à jour. 
   
     S'il n'y a pas de bouton **Mettre à jour**, vous pouvez obtenir la version 8.2 ou ultérieure en [vous inscrivant à un essai](https://appsource.microsoft.com/en-us/product/dynamics-365/mscrm.40fd37ef-dca4-4b0d-9f41-d16703b7d070?tab=Overview) ou en allant au [portail Insider de Dynamics](http://experience.dynamics.com/insider).

     > [!NOTE]
     > Si l'installation de [!include[pn-field-service](../includes/pn-field-service.md)] échoue, vous devrez peut-être réinitialiser ou créer une nouvelle instance. L'installation de [!include[pn-field-service](../includes/pn-field-service.md)] nécessite des étapes spécifiques et leur réalisation sans en respecter l'ordre peut entraîner l'échec de cette installation. [En savoir plus sur l'installation de Field Service.](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/field-service/install-field-service)

   - Si la version correcte de [!include[pn-field-service](../includes/pn-field-service.md)] est installée et la vue **Mes réservations en cours** est incluse, allez à [Ajouter un ordre de travail et une réservation](#add-a-work-order-and-booking), la prochaine procédure de cette rubrique.
   
## <a name="add-a-work-order-and-booking"></a>Ajouter un ordre de travail et une réservation
   
Les données ne figurent pas dans le volet **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]** dans [!include[pn-remote-assist](../includes/pn-remote-assist.md)], à moins que les conditions suivantes soient remplies :
   
- Un ordre de travail au moins est nécessaire.

- Les champs suivants dans l'ordre de travail doivent avoir une valeur :
   
   |**Champ**|**Valeur**|
   |------------------|---------------------------------------------------------------------------------------------------|
   |État du système|La valeur pour ce champ doit être définie sur **En cours**.|
   |Ressource|Stocke l'adresse e-mail de l'utilisateur de [!include[pn-hololens](../includes/pn-hololens.md)]. Cette adresse doit correspondre à l'adresse e-mail pour l'utilisateur de [!include[pn-hololens](../includes/pn-hololens.md)].|
 
### <a name="create-a-work-order"></a>Créer un ordre de travail
   
1.  Ouvrez l'instance [!include[pn-dyn-365](../includes/pn-dyn-365.md)] dans votre navigateur.

2.  Sélectionnez le menu déroulant en regard de **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]**, sélectionnez **[!include[pn-field-service](../includes/pn-field-service.md)]**, puis sélectionnez **Nouveau**.

3.  Complétez tous les champs qui contiennent un astérisque.

    ![Écran Ordre de travail](media/work-order.PNG "Écran Ordre de travail")
    
4.  Sélectionnez **Enregistrer** dans le coin inférieur droit de la fenêtre.

### <a name="add-values-for-the-required-fields"></a>Ajouter des valeurs pour les champs requis

1.  Sélectionnez l'onglet **Paramètres**.  

2.  Sélectionnez l'option **Réserver** en haut de l'écran. Vous utilisez cette option pour réserver un temps permettant à la ressource d'exécuter le travail.

3.  Dans le champ **Ressource**, entrez la ressource pour l'utilisateur de [!include[pn-hololens](../includes/pn-hololens.md)]. L'adresse e-mail de la ressource doit correspondre à celle de l'utilisateur de [!include[pn-hololens](../includes/pn-hololens.md)]. Si vous ne sélectionnez pas une ressource, ou si les adresses e-mail ne correspondent pas, les données ne s'affichent pas dans le volet **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]** dans [!include[pn-remote-assist](../includes/pn-remote-assist.md)].

4.  Sélectionnez les informations de réservation, puis définissez le champ **Statut de réservation** sur **En cours**.

    ![Champ Statut de réservation](media/booking-status.PNG "Champ Statut de réservation")
    
5.  Apportez des modifications à d'autres champs comme souhaité (aucune autre donnée n'est requise pour que les données s'affichent dans le volet **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]** dans [!include[pn-remote-assist](../includes/pn-remote-assist.md)]).

6.  Enregistrez vos modifications.

## <a name="add-custom-fields-to-the-dynamics-365-pane-in-remote-assist-optional"></a>Ajouter des champs personnalisés au volet **Dynamics 365** dans Remote Assist (facultatif)

Vous pouvez personnaliser le volet **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]** dans [!include[pn-remote-assist](../includes/pn-remote-assist.md)] en personnalisant des champs, des formulaires ou la vue **Mes réservations en cours** dans [!include[pn-dyn-365](../includes/pn-dyn-365.md)].

Pour personnaliser des champs, des formulaires ou des vues dans [!include[pn-dyn-365](../includes/pn-dyn-365.md)] :

1. Sélectionnez **Service** > **Paramètres** > **Personnalisations** > **Personnaliser le système**.

   ![Sélection de Personnalisations](media/Customizations.PNG "Sélection de Personnalisations")
    
2. Développez **Entités**, ouvrez l'entité à modifier, puis sélectionnez **Champs**, **Formulaires** ou **Vues**, en fonction de l'opération à effectuer. 

Le tableau suivant présente des exemples de types de modifications que vous pouvez souhaiter apporter dans [!include[pn-dyn-365](../includes/pn-dyn-365.md)], ainsi que la procédure à suivre pour les appliquer.

|**Pour**|**Effectuez l'opération suivante**|**Exemple**|
|------------------|---------------------------------------------------|--------------------------------------------------------|
|Ajouter un nouveau champ qui n'existe pas déjà dans [!include[pn-dyn-365](../includes/pn-dyn-365.md)]|Créez le champ dans l'entité que vous souhaitez modifier, puis ajoutez ce champ à la vue **Mes réservations en cours**.|Dans l'écran **Personnalisations**, ouvrez l'entité **Ordre de travail**, puis ajoutez le champ que vous souhaitez.<br /><br />**Note** Veillez à ajouter des données au champ. Le champ ne s'affiche pas s'il n'y a aucune donnée.|
|Ajouter un champ existant à la vue **Mes réservations en cours**|Dans la vue **Mes réservations en cours**, ajoutez une colonne pour le champ. Vous pouvez ajouter un champ depuis n'importe quelle entité dans [!include[pn-dyn-365](../includes/pn-dyn-365.md)].|Dans l'écran **Personnalisations**, ouvrez l'entité **Réservation de ressources pouvant être réservées**, sélectionnez la vue **Mes réservations en cours**, puis choisissez **Ajouter des colonnes**.<br /><br />**Note** Veillez à ajouter des données au champ. Le champ ne s'affiche pas s'il n'y a aucune donnée.|
|Ajouter un lien web [!include[pn-power-bi](../includes/pn-power-bi.md)]. Dans [!include[pn-hololens](../includes/pn-hololens.md)], lorsque l'utilisateur sélectionne le lien, il s'ouvre automatiquement dans le navigateur [!include[pn-edge](../includes/pn-edge.md)].|Créez un champ qui prend en charge les chaînes de texte.|Entrez n'importe quel lien web dans les données de champ, telles qu'un lien qui ouvre un tableau de bord [!include[pn-power-bi](../includes/pn-power-bi.md)].  Tant qu'il s'agit d'une URL valide, il devient automatiquement un lien.|

### <a name="see-also"></a>Voir aussi

- [Créer ou modifier des champs dans Dynamics 365](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/customize/create-edit-fields)

- [Créer ou modifier des vues dans Dynamics 365](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/customize/create-edit-views)
