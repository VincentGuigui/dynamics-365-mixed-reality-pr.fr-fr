---
author: Makamat
description: Décrit comment désactiver le stockage des données d'événements Dynamics 365 Guides, pour des raisons de confidentialité, dans Common Data Service.
ms.author: makamat
ms.date: 07/09/2019
ms.service: crm-online
ms.topic: article
title: Désactiver le stockage des données d'événements Dynamics 365 Guides dans Common Data Service
ms.reviewer: v-brycho
ms.openlocfilehash: 8e19ebc56dc4abc01cae3ca68aea380c49791830
ms.sourcegitcommit: 40992f99110d02b2120a930679c5f681b0a6227a
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/25/2019
ms.locfileid: "2050049"
---
# <a name="opt-out-of-storing-dynamics-365-guides-events-data-in-common-data-service"></a>Désactiver le stockage des données d'événements Dynamics 365 Guides dans Common Data Service

Les applications Dynamics 365 Guides permettent aux équipes de capturer des statistiques d'utilisation et des informations de suivi du temps détaillées. Ces données sont utilisées pour fournir des mesures de performances des opérateurs et pour vous aider à identifier les opportunités d'optimisation des processus. Les administrateurs peuvent désactiver la collecte de données pour des utilisateurs spécifiques s'ils le souhaitent. 

Pour ce faire :

1.  Accédez à powerapps.microsoft.com et connectez-vous avec votre compte d'administrateur.

2.  Dans le menu déroulant du client/de l'instance, sélectionnez l'instance où Dynamics 365 Guides est installé.

3.  Sélectionnez l'application Guides dans la liste. Un nouvel onglet s'ouvre pour le portail Guides.

4.  Dans le volet de navigation de gauche, accédez à **Paramètres utilisateur**.

    ![Paramètres utilisateur](media/data-opt-out-user-setting.PNG "Paramètres utilisateur")
 
5.  Sélectionnez **Nouveau**.

    ![Sélectionnez Nouveau](media/data-opt-out-new.PNG "Sélectionnez Nouveau")
 
6.  Complétez le formulaire comme suit :

    - **Nom :** désactivez l'*ajout d'un nom d'utilisateur ici*.

    - **Enregistrer l'utilisation des guides :** oui.

    - **Appartient à :** nom d'utilisateur. 

7.  Sélectionnez **Enregistrer**.

    ![Formulaire complété](media/data-opt-out-filled-out-form.PNG "Formulaire complété")
 
### <a name="see-also"></a>Voir aussi

[Analyser l'utilisation des guides](analytics-guide.md)
