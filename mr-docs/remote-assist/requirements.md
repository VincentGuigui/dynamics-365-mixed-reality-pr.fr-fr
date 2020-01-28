---
author: sophiasysun
description: Exigences techniques pour le déploiement et l'utilisation de Microsoft Dynamics 365 Remote Assist
ms.author: sopsun
ms.date: 10/01/2019
ms.service: crm-online
ms.topic: article
title: Configuration requise pour Dynamics 365 Remote Assist
ms.reviewer: v-brycho
ms.openlocfilehash: 4d96f4ae2f2b34741bda104aa6094cbdee8cd77f
ms.sourcegitcommit: 56579384c418edd4f37cd750751fc8e4d8883a65
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 12/20/2019
ms.locfileid: "2921084"
---
# <a name="requirements-for-setting-up-dynamics-365-remote-assist"></a>Configuration requise pour paramétrer Dynamics 365 Remote Assist

Les tableaux suivants répertorient les exigences techniques pour le déploiement et l'utilisation de [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] dans toute votre organisation.

## <a name="device-requirements"></a>Configuration requise pour l'appareil

| **Appareil**               | **Configuration requise du SE**                                                                                                                                                  | **Détails**                                                                                                                                                                                                                    |
|--------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [!include[pn-hololens](../includes/pn-hololens.md)]                 | Version 10.0.14393.0 ou ultérieure. La version 10.0.14393.0 d'[!include[pn-hololens](../includes/pn-hololens.md)] est le minimum prenant en charge [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)]. Nous vous recommandons de mettre à jour [!include[pn-hololens](../includes/pn-hololens.md)] vers des versions plus récentes quand elles sont disponibles. | Voir [Gérer les mises à jour vers HoloLens](https://docs.microsoft.com/HoloLens/hololens-updates) pour obtenir des instructions sur l'utilisation de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Update pour Entreprise, Gestion des périphériques mobiles (GPM) et [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Server Update Services (WSUS). |
| PC [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 (facultatif) | Toute version de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10.| Un PC [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 peut collaborer avec [!include[pn-hololens](../includes/pn-hololens.md)] en utilisant [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)].|
|Appareil mobile (facultatif)|Tout téléphone ou tablette iOS ou [!include[tn-android](../includes/tn-android.md)] qui exécute [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] Mobile.|Un téléphone ou une tablette exécutant [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] Mobile peut collaborer avec [!include[pn-hololens](../includes/pn-hololens.md)].|

## <a name="licensing-and-product-requirements"></a>Gestion des licences et configuration requise du produit

| **Produit requis**|**Détails**|**En savoir plus**|
|---------------|-------------------------------------------------------|----------------------------------------------------------|
|[!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)]|Logiciel [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)]<br></br>**Notez** que [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] est inclus dans l'abonnement [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] pour les personnes avec une licence [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] sur [!include[pn-hololens](../includes/pn-hololens.md)]. Une licence [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] est également requise pour les personnes (spécialistes) qui communiquent avec un utilisateur de [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] sur [!include[pn-hololens](../includes/pn-hololens.md)]. [!include[pn-teams](../includes/pn-teams.md)] peut être disponible [en téléchargement gratuit](https://teams.microsoft.com/downloads) pour ces utilisateurs.| [Acheter et déployer Dynamics 365 Remote Assist](../licensing/buy-and-deploy.md)|
|Compte [!include[pn-azure](../includes/pn-azure.md)] Active Directory ([!include[pn-azure](../includes/pn-azure.md)] AD)|Requis pour : <ul><li>Achat d'abonnement et affectation de licences. Vous aurez besoin d'un compte [!include[pn-azure](../includes/pn-azure.md)] AD pour chaque utilisateur sous licence. </li><li>Répartition d'applications par le biais de [!include[cc-microsoft](../includes/cc-microsoft.md)] Store pour Entreprises. </li><li>Utilisateurs au moment de la connexion à l'application. </ul> | [Mise en route d'Azure AD](https://docs.microsoft.com/azure/active-directory/fundamentals/get-started-azure-ad) |
| [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)] (facultatif). **Veuillez noter** que la version 8.2 ou ultérieure de [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)] est requise. |[!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] requiert une licence [!include[pn-dyn-365](../includes/pn-dyn-365.md)] si vous souhaitez afficher les réservations [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)] dans [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)]. Pour afficher les tableaux de bord [!include[pn-power-bi](../includes/pn-power-bi.md)] liés aux réservations [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)] dans [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)], les utilisateurs doivent disposer d'une licence [!include[pn-power-bi](../includes/pn-power-bi.md)] valide. | [En savoir plus sur Dynamics 365 Field Service](https://dynamics.microsoft.com/field-service/overview/)|

## <a name="network-requirements"></a>Configuration réseau

La bande passante recommandée pour un niveau de performance optimal de [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] est de 1,5 MB/s.
Bien que les appels audio/vidéo soient possibles dans les environnements à bande passante réduite, vous pourriez faire face à une dégradation de fonctionnalité d'[!include[pn-hololens](../includes/pn-hololens.md)], limitant l'expérience utilisateur. Pour tester la bande passante du réseau de votre société, procédez comme suit :

1.  Demandez à un utilisateur de [!include[pn-teams](../includes/pn-teams.md)] de commencer un appel vidé avec un autre utilisateur de [!include[pn-teams](../includes/pn-teams.md)].

2.  Ajoutez un appel vidéo distinct entre un troisième et un quatrième utilisateurs, et un autre pour un cinquième et un sixième utilisateurs.

3.  Continuez d'ajouter des appelants vidéo pour effectuer un test de contrainte de la bande passante de votre réseau jusqu'à ce que vous soyez sûr que plusieurs utilisateurs peuvent parvenir à se connecter à des appels vidéo simultanément.

Voir [Préparer le réseau de votre organisation pour Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/prepare-network) pour en savoir plus.

### <a name="see-also"></a>Voir aussi
[Présentation de Dynamics 365 Remote Assist](index.md)<br/>
[Essayer Dynamics 365 Remote Assist gratuitement](try-remote-assist-free.md)<br/>
[Acheter et déployer Dynamics 365 Remote Assist](buy-and-deploy-remote-assist.md)<br>
[Guide de l'utilisateur](user-guide.md)<br/>
[Paramétrer et utiliser Microsoft Teams avec Dynamics 365 Remote Assist](use-microsoft-teams-with-remote-assist.md)<br/>
[Vidéos pratiques](videos.md)<br/>
[FAQ](faq.md)<br/>
