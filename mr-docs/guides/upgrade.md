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
# <a name="upgrade-the-dynamics-365-guides-solution"></a>Mettre à niveau la solution Dynamics 365 Guides

Cette rubrique concerne les administrateurs [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365](../includes/pn-dyn-365.md)]. Certaines versions de [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] nécessitent une mise à jour de la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Lorsqu'une mise à jour est nécessaire, l'utilisateur verra une notification s'afficher dans le volet **Nouveautés**.

Gardez à l'esprit les points suivants :

- Avant de mettre la solution à jour dans le Centre d'administration Power Platform, assurez-vous que le PC [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et les applications [!include[pn-hololens](../includes/pn-hololens.md)] ont été mis à jour vers la dernière version du [!include[cc-microsoft](../includes/cc-microsoft.md)] Store.

- Les mises à jour de la solution doivent être effectuées lorsque les applications sur PC et [!include[pn-hololens](../includes/pn-hololens.md)] ne sont pas utilisées.  

> [!IMPORTANT]
> Si vous utilisez actuellement la version préliminaire publique [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] pour obtenir la version d'octobre 2019, vous devez rechercher la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], puis sélectionner **Installer** au lieu de **Mettre à niveau**. Cela installe la version en disponibilité générale de la solution et supprime la solution préliminaire publique. Pour plus d'informations, voir [Transition entre la version préliminaire publique et la disponibilité générale](public-preview-transition.md).

Pour mettre à niveau la solution :

1. Accédez au [Centre d'administration Power Platform](https://admin.powerplatform.microsoft.com/environments), puis connectez-vous avec les informations d'identification disposant des autorisations de l'administrateur pour [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. 

2. Pour sélectionner l'environnement, activez la case à cocher, sélectionnez le bouton **Autres actions d'environnement** (les trois points), puis sélectionnez **Gérer les solutions**. 

   ![Gérer les solutions](media/manage-solutions.PNG "Gérer les solutions")

3. Dans la liste des solutions, sélectionnez **[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]**, puis sélectionnez **Mettre à niveau**.
 
   ![Bouton Mettre à niveau](media/upgrade.PNG "Bouton Mettre à niveau")   
  
4. Examinez les Conditions de service, puis sélectionnez **Accepter** si vous êtes prêt(e) à commencer la mise à niveau. 

   Le statut de la solution passe à **Installation en attente,** puis à **Installé** lorsque la mise à niveau est terminée. 
 
Pour plus d'informations sur la mise à niveau de la solution [!include[pn-dyn-365](../includes/pn-dyn-365.md)][voir Installer, mettre à jour ou supprimer une solution par défaut](https://docs.microsoft.com/dynamics365/customer-engagement/admin/install-remove-preferred-solution).
