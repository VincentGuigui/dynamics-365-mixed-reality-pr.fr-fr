---
author: Mamaylya
description: Exigences techniques pour l'installation et l'utilisation de Dynamics 365 Guides
ms.author: mamaylya
ms.date: 10/01/2019
ms.service: crm-online
ms.topic: article
title: Exigences techniques pour Dynamics 365 Guides
ms.reviewer: v-brycho
ms.openlocfilehash: a88e8d9fd131cbfc317ce0a64b42932849143fcb
ms.sourcegitcommit: 15f2c0f0ac19d9516135d89c44550a2b77cd181e
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/27/2019
ms.locfileid: "2224228"
---
# <a name="requirements-for-dynamics-365-guides"></a>Configuration requise pour Dynamics 365 Guides

Le tableau suivant répertorie les exigences techniques pour le déploiement et l'utilisation de [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] dans toute votre organisation.

## <a name="device-requirements"></a>Configuration requise pour l'appareil
|Appareil|Configuration requise du SE|Détails|
|----------------------------------------|---------------------------------------------|-------------------------------------|
|[!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-hololens](../includes/pn-hololens.md)]|Version 10.0.17134 ou ultérieure. La version 10.0.17134 d'HoloLens est le minimum prenant en charge [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Nous vous recommandons de mettre à jour HoloLens vers des versions plus récentes quand elles sont disponibles. |Voir [Gérer les mises à jour vers HoloLens](https://docs.microsoft.com/HoloLens/hololens-updates) pour obtenir des instructions sur l'utilisation de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Update pour Entreprise, Gestion des périphériques mobiles (GPM) et [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Server Update Services (WSUS).|
|[!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC (requis pour créer un guide)|[!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC avec la version 10.0.17134 (Avril 2018, Mise à jour 1803) ou ultérieure|[!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC permet de créer et de modifier les guides qui sont alors disponibles dans [!include[pn-hololens](../includes/pn-hololens.md)].|

## <a name="licensing-and-product-requirements"></a>Gestion des licences et configuration requise du produit

|Produit requis|Détails|En savoir plus|
|-------------------------------|-------------------------------------------------------|-------------------------------------------|
|[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]|Le logiciel[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] sur PC et HoloLens avec un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] valide sont requis.</br><br>**Remarque** Les services Common Data Service et PowerApps sont inclus dans l'abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] pour les personnes utilisant une licence [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].|[Acheter et déployer Dynamics 365 Guides](setup.md)</br><br>Vous pouvez également vous [inscrire pour un essai gratuit de Dynamics 365](setup.md).|
|Application Power BI Desktop|[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] nécessite l'application Power BI Desktop pour afficher le tableau de bord analytique.</br><br>**Remarque** L'application Power BI Desktop est [disponible en téléchargement gratuit](https://powerbi.microsoft.com/desktop/).|[En savoir plus sur Power BI](https://powerbi.microsoft.com/desktop/)|
|Compte Azure Active Directory (Azure AD)|Requis pour :</br><br>- Achat de l'abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et affectation de licences. Vous aurez besoin d'un compte Azure AD pour chaque utilisateur sous licence.</br><br>- Utilisateurs au moment de la connexion à l'application.|[Mise en route d'Azure AD](https://docs.microsoft.com/azure/active-directory/fundamentals/active-directory-whatis)|
|Connectivité réseau|L'accès Internet est requis pour télécharger l'application et utiliser toutes ses fonctionnalités à la fois pour le PC et HoloLens.||

### <a name="see-also"></a>Voir aussi

[Acheter et déployer Dynamics 365 Guides](setup.md)<br>
[Mettre à niveau la solution (pour les administrateurs)](upgrade.md)
