---
author: MatthewJonPaul
description: Exigences techniques pour le déploiement et l'utilisation de Microsoft Dynamics 365 Remote Assist
ms.author: mapau
ms.date: 4/01/2019
ms.service: crm-online
ms.topic: article
title: Configuration requise pour Dynamics 365 Remote Assist
ms.reviewer: v-brycho
ms.openlocfilehash: 7ae3b24bcc25f6b07147511ea22102162cdb5dcc
ms.sourcegitcommit: 157b70ec12e7cc459231aa5e32d311ebc09727d8
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/25/2019
ms.locfileid: "1575463"
---
# <a name="requirements-for-setting-up-dynamics-365-remote-assist"></a>Configuration requise pour paramétrer Dynamics 365 Remote Assist

Les tableaux suivants répertorient les exigences techniques pour le déploiement et l'utilisation de [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] dans toute votre organisation.

## <a name="device-requirements"></a>Configuration requise pour l'appareil

| **Appareil**               | **Configuration requise du SE**                                                                                                                                                  | **Détails**                                                                                                                                                                                                                    |
|--------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [!include[pn-hololens](../includes/pn-hololens.md)]                 | Version 10.0.14393.0 ou ultérieure. La version 10.0.14393.0 d'[!include[pn-hololens](../includes/pn-hololens.md)] est le minimum prenant en charge [!include[pn-remote-assist](../includes/pn-remote-assist.md)]. Nous vous recommandons de mettre à jour [!include[pn-hololens](../includes/pn-hololens.md)] vers des versions plus récentes quand elles sont disponibles. | Voir [Gérer les mises à jour vers HoloLens](https://docs.microsoft.com/en-us/HoloLens/hololens-updates) pour obtenir des instructions sur l'utilisation de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Update pour Entreprise, Gestion des périphériques mobiles (GPM) et [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Server Update Services (WSUS). |
| PC [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 (facultatif) | Toute version de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10.| Un PC [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 peut collaborer avec [!include[pn-hololens](../includes/pn-hololens.md)] en utilisant [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)].|
|Appareil mobile (facultatif)|Tout téléphone ou tablette iOS ou Android qui exécute Microsoft Teams Mobile.|Un téléphone ou une tablette exécutant Microsoft Teams Mobile peut collaborer avec HoloLens.|

## <a name="licensing-and-product-requirements"></a>Gestion des licences et configuration requise du produit

| **Produit requis**|**Détails**|**En savoir plus**|
|---------------|-------------------------------------------------------|----------------------------------------------------------|
|Remote Assist|Logiciel Remote Assist<br></br>**Note** Microsoft Teams est inclus dans l'abonnement Remote Assist pour les personnes avec une licence Remote Assist sur HoloLens. Une licence Microsoft Teams est également requise pour les personnes (experts) qui communiquent avec un utilisateur de Remote Assist sur HoloLens. Teams peut être disponible [en téléchargement gratuit](https://teams.microsoft.com/downloads) pour ces utilisateurs.| [Acheter et déployer Remote Assist](../licensing/buy-and-deploy.md)|
|Compte Azure Active Directory (Azure AD)|Requis pour : <ul><li>Achat d'abonnement et affectation de licences. Vous aurez besoin d'un compte Azure AD pour chaque utilisateur sous licence. </li><li>Répartition d'applications par le biais de Microsoft Store pour Entreprises. </li><li>Utilisateurs au moment de la connexion à l'application. </ul> | [Mise en route d'Azure AD](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/get-started-azure-ad) |
| Dynamics 365 for Field Service (facultatif). **Veuillez noter** que la version 8.2 ou ultérieure de Field Service est requise. |Remote Assist requiert une licence Dynamics 365 si vous souhaitez afficher les réservations Dynamics 365 for Field Service dans Remote Assist. Pour afficher les tableaux de bord Power BI liés aux réservations Dynamics 365 for Field Service dans Remote Assist, les utilisateurs doivent disposer d'une licence Power BI valide. | [En savoir plus sur Dynamics 365 for Field Service](https://dynamics.microsoft.com/en-us/field-service/overview/)|

## <a name="network-requirements"></a>Exigences du réseau

La bande passante recommandée pour un niveau de performance optimal de [!include[pn-remote-assist](../includes/pn-remote-assist.md)] est de 1,5 MB/s.
Bien que les appels audio/vidéo soient possibles dans les environnements à bande passante réduite, vous pourriez faire face à une dégradation de fonctionnalité d'[!include[pn-hololens](../includes/pn-hololens.md)], limitant l'expérience utilisateur. Pour tester la bande passante du réseau de votre société, procédez comme suit :

1.  Demandez à un utilisateur de [!include[pn-teams](../includes/pn-teams.md)] de commencer un appel vidé avec un autre utilisateur de [!include[pn-teams](../includes/pn-teams.md)].

2.  Ajoutez un appel vidéo distinct entre un troisième et un quatrième utilisateurs, et un autre pour un cinquième et un sixième utilisateurs.

3.  Continuez d'ajouter des appelants vidéo pour effectuer un test de contrainte de la bande passante de votre réseau jusqu'à ce que vous soyez sûr que plusieurs utilisateurs peuvent parvenir à se connecter à des appels vidéo simultanément.

Voir [Préparer le réseau de votre organisation pour Microsoft Teams](https://docs.microsoft.com/en-us/MicrosoftTeams/prepare-network) pour en savoir plus.

### <a name="see-also"></a>Voir aussi
[Présentation de Remote Assist](index.md)<br/>
[Essayer Remote Assist gratuitement](try-remote-assist-free.md)<br/>
[Acheter et déployer Remote Assist](buy-and-deploy-remote-assist.md)<br>
[Guide de l'utilisateur](user-guide.md)<br/>
[Configurer et utiliser Microsoft Teams avec Remote Assist](use-microsoft-teams-with-remote-assist.md)<br/>
[Vidéos pratiques](https://go.microsoft.com/fwlink/p/?linkid=2021485)<br/>
[FAQ](faq.md)<br/>
