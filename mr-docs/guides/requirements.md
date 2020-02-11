---
author: Mamaylya
description: En savoir plus sur les exigences relatives aux appareils et aux licences pour l'installation et l'utilisation de Microsoft Dynamics 365 Guides.
ms.author: mamaylya
ms.date: 01/28/2020
ms.service: crm-online
ms.topic: article
title: Exigences relatives aux appareils et aux licences pour Dynamics 365 Guides
ms.reviewer: v-brycho
ms.openlocfilehash: 63a0045a770e16040cf9dbad7c004c23732cf03c
ms.sourcegitcommit: 217d31bb34e67a6b8823d5ddac7ef8d56d054139
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/29/2020
ms.locfileid: "2994892"
---
# <a name="device-and-licensing-requirements-for-dynamics-365-guides"></a>Exigences relatives aux appareils et aux licences pour Dynamics 365 Guides

Le tableau suivant répertorie les exigences techniques pour le déploiement et l'utilisation de [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] dans toute votre organisation.

## <a name="device-requirements"></a>Exigences relatives aux appareils
| Appareil | Plateforme | Exigences relatives au système d'exploitation | Détails |
|---|---|---|---|
| [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-hololens](../includes/pn-hololens.md)] | x86, ARM | Version 10.0.17134 ou ultérieure.<p>La version 10.0.17134 d'[!include[pn-hololens](../includes/pn-hololens.md)] est la première version qui prend en charge [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Nous vous recommandons d'effectuer une mise à jour de [!include[pn-hololens](../includes/pn-hololens.md)] vers des versions plus récentes quand elles sont disponibles.</p> | Pour plus d'informations sur l'utilisation de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Update pour Entreprise, Gestion des périphériques mobiles et [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Server Update Services (WSUS), voir [Gérer les mises à jour vers HoloLens](https://docs.microsoft.com/HoloLens/hololens-updates). |
| Un ordinateur (PC) en cours d'exécution [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 (requis pour créer des guides) | x64 | Un PC qui exécute [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 avec la version 10.0.17134 (Avril 2018, Mise à jour 1803) ou ultérieure | Un PC qui exécute [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 permet de créer et de modifier les guides qui sont alors disponibles dans [!include[pn-hololens](../includes/pn-hololens.md)]. |

## <a name="licensing-and-product-requirements"></a>Gestion des licences et configuration requise du produit

| Produit requis | Détails | En savoir plus |
|---|---|---|
| [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] | Un logiciel [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] qui s'exécute sur un PC et [!include[pn-hololens](../includes/pn-hololens.md)] avec un abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] valide est requis.<p>**Remarque** Les services Common Data Service et Power Apps sont inclus dans l'abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] pour les personnes utilisant une licence [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</p> | [Acheter et déployer Dynamics 365 Guides](setup.md)<p>Vous pouvez également vous [inscrire pour un essai gratuit de Dynamics 365](setup.md).</p> |
| Application [!include[pn-power-bi](../includes/pn-power-bi.md)] Desktop | [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] nécessite l'application [!include[pn-power-bi](../includes/pn-power-bi.md)] Desktop pour afficher le tableau de bord analytique.<p>**Remarque :** L'application [!include[pn-power-bi](../includes/pn-power-bi.md)] Desktop est [disponible en téléchargement gratuit](https://powerbi.microsoft.com/desktop/).</p> | [En savoir plus sur Power BI](https://powerbi.microsoft.com/desktop/) |
| Compte Azure Active Directory (Azure AD) | Requis pour :<ul><li>Achat de l'abonnement [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et affectation de licences. Vous aurez besoin d'un compte Azure AD pour chaque utilisateur sous licence.</li><li>Utilisateurs au moment de la connexion à l'application.</li></ul> | [Mise en route d'Azure AD](https://docs.microsoft.com/azure/active-directory/fundamentals/active-directory-whatis) |
| Connectivité réseau | L'accès Internet est requis pour télécharger l'application et utiliser toutes ses fonctionnalités à la fois pour le PC et [!include[pn-hololens](../includes/pn-hololens.md)]. | |

## <a name="whats-next"></a>Étapes suivantes

[Présentation de la configuration](setup.md)
