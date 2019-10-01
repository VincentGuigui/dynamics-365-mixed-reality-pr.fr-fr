---
author: Mamaylya
description: Mettre à niveau la solution Dynamics 365 Guides (version préliminaire)
ms.author: mamaylya
ms.date: 10/01/2019
ms.service: crm-online
ms.topic: article
title: Mettre à niveau la solution Dynamics 365 Guides (version préliminaire)
ms.reviewer: v-brycho
ms.openlocfilehash: 2e858765fc33d3bc95312d3823a3881f1e184acd
ms.sourcegitcommit: 40992f99110d02b2120a930679c5f681b0a6227a
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/25/2019
ms.locfileid: "2049965"
---
# <a name="upgrade-the-dynamics-365-guides-solution-for-admins"></a>Mettre à niveau la solution Dynamics 365 Guides (pour les administrateurs)

Cette rubrique concerne les administrateurs [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365](../includes/pn-dyn-365.md)]. Certaines versions de [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] nécessitent une mise à jour de la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Lorsqu'une mise à jour est nécessaire, l'utilisateur verra une notification s'afficher dans le volet **Nouveautés**.

> [!IMPORTANT]
> Gardez à l'esprit les points suivants :<br><br>- Avant de mettre la solution à jour dans le Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)], assurez-vous que le PC [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et les applications [!include[pn-hololens](../includes/pn-hololens.md)] ont été mis à jour vers la dernière version du [!include[cc-microsoft](../includes/cc-microsoft.md)] Store.<br><br>- Les mises à jour de la solution doivent être effectuées lorsque le PC et les applications [!include[pn-hololens](../includes/pn-hololens.md)] ne sont pas utilisés.  

Pour mettre à niveau la solution :

1. Accédez au [Centre d'administration Dynamics 365](https://port.crm.dynamics.com/G/Instances/InstancePicker.aspx), puis connectez-vous avec vos informations d'identification Administrateur. Si vous avez créé des informations d'identification lors de la connexion, ces informations d'identification doivent disposer d'autorisations d'administrateur. 

2. Sélectionnez l'onglet **Instances**, puis choisissez une instance ayant la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] installée.

3. Sélectionnez le petit bouton Modifier en regard de **Solutions** pour afficher la liste des solutions. 
 
   ![Bouton Solutions](media/solutions.PNG "Bouton Solutions")
 
4. Dans la liste des solutions, sélectionnez **[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]**, puis sélectionnez **Mettre à niveau**.  
 
   ![Bouton Mettre à niveau](media/upgrade.PNG "Bouton Mettre à niveau")
   
   > [!IMPORTANT]
   > Si vous utilisez actuellement la version préliminaire publique [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] pour obtenir la version d'octobre 2019, vous devez rechercher la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], puis sélectionner **Installer** au lieu de **Mettre à niveau**. Cela installe la version en disponibilité générale de la solution et supprime la solution préliminaire publique.
   
5. Examinez les Conditions de service, puis sélectionnez **Accepter** si vous êtes prêt(e) à commencer la mise à niveau. 

   Le statut de la solution passe à **Installation en attente,** puis à **Installé** lorsque la mise à niveau est terminée. 
 
Pour plus d'informations sur la mise à niveau de la solution [!include[pn-dyn-365](../includes/pn-dyn-365.md)][voir Installer, mettre à jour ou supprimer une solution par défaut](https://docs.microsoft.com/dynamics365/customer-engagement/admin/install-remove-preferred-solution).
