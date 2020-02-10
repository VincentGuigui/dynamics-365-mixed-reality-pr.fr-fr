---
author: Makamat
description: Découvrez comment désactiver le stockage des données d'utilisation Microsoft Dynamics 365 Guides dans Common Data Service, pour des raisons de confidentialité.
ms.author: makamat
ms.date: 01/28/2020
ms.service: crm-online
ms.topic: article
title: Désactiver le stockage des données d'utilisation Dynamics 365 Guides dans Common Data Service
ms.reviewer: v-brycho
ms.openlocfilehash: e55ee2841cfa57b842615cdffa3b3db027b56f4b
ms.sourcegitcommit: 217d31bb34e67a6b8823d5ddac7ef8d56d054139
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/29/2020
ms.locfileid: "2994795"
---
# <a name="opt-out-of-storing-dynamics-365-guides-usage-data-in-common-data-service"></a>Désactiver le stockage des données d'utilisation Dynamics 365 Guides dans Common Data Service

Les applications Dynamics 365 Guides permettent aux équipes de capturer des statistiques d'utilisation et des informations de suivi du temps détaillées. Ces données sont utilisées pour fournir des mesures de performances des opérateurs et pour vous aider à identifier les opportunités d'optimisation des processus. Les administrateurs peuvent désactiver la collecte de données pour des utilisateurs spécifiques s'ils le souhaitent. 

Pour ce faire :

1.  Accédez à powerapps.microsoft.com et connectez-vous avec votre compte d'administrateur.

2.  Dans le menu déroulant du client/de l'instance, sélectionnez l'instance où Dynamics 365 Guides est installé.

3.  Sélectionnez l'application Guides dans la liste. Un nouvel onglet s'ouvre pour le portail Guides.

4.  Dans le volet de navigation de gauche, accédez à **Paramètres utilisateur**.

    ![Paramètres utilisateur](media/data-opt-out-user-setting.PNG "Paramètres utilisateur")
 
5.  Sélectionnez **Nouveau**.

    ![Sélectionner Nouveau](media/data-opt-out-new.PNG "Sélectionner Nouveau")
 
6.  Complétez le formulaire comme suit :

    - **Nom :** désactivez l'*ajout d'un nom d'utilisateur ici*.

    - **Enregistrer l'utilisation des guides :** oui.

    - **Appartient à :** nom d'utilisateur. 

7.  Sélectionnez **Enregistrer**.

    ![Formulaire complété](media/data-opt-out-filled-out-form.PNG "Formulaire complété")
 
## <a name="see-also"></a>Voir aussi

[Analyser l'utilisation des guides](analytics-guide.md)
