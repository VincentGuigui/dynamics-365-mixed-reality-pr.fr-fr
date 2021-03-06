---
author: ornellaalt
description: Options et exigences techniques de l'appareil pour Dynamics 365 Layout
ms.author: ornella
ms.date: 10/01/2019
ms.service: crm-online
ms.topic: article
title: Options et exigences techniques de l'appareil pour Dynamics 365 Layout
ms.reviewer: v-brycho
ms.openlocfilehash: b201a988d0787b6b4b3d57aa369bd31788c9fbd1
ms.sourcegitcommit: 15f2c0f0ac19d9516135d89c44550a2b77cd181e
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/27/2019
ms.locfileid: "2224201"
---
# <a name="device-options-and-technical-requirements-for-dynamics-365-layout"></a>Options et exigences techniques de l'appareil pour Dynamics 365 Layout

[!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-layout](../includes/pn-dyn-365-layout.md)] fonctionne avec un appareil Microsoft [!include[pn-hololens](../includes/pn-hololens.md)] ou avec un casque immersif [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Mixed Reality avec les contrôleurs de mouvement.

## <a name="hololens-requirements"></a>Configuration requise pour HoloLens

| **Configuration requise du SE**          | **Détails**                                                                                                                           |
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------|
| Version 10.0.17134.77 ou ultérieure | Voir [Mettre à jour HoloLens](https://support.microsoft.com/help/12643/hololens-update-hololens) pour obtenir des instructions sur la mise à jour de cette version. |

> [!NOTE]
> Vous pouvez utiliser le dispositif de clic [!include[pn-hololens](../includes/pn-hololens.md)] avec [!include[pn-dyn-365-layout](../includes/pn-dyn-365-layout.md)], mais sa fonctionnalité est limitée. Vous pouvez utiliser le dispositif de clic pour effectuer des sélections dans les menus et pour analyser une pièce, mais vous ne pouvez pas l'utiliser pour manipuler des objets.


## <a name="windows-mixed-reality-headset-requirements"></a>Configuration requise pour le casque Windows Mixed Reality

| **Configuration requise**                          | **Détails**                                                                                                                                                                                                                                                                                                                          |
|-------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| PC [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 avec version 17134.0 ou ultérieure | Le matériel du PC [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 doit pouvoir prendre en charge le casque. Voir [Directives du matériel du PC Windows Mixed Reality](https://support.microsoft.com/help/4039260/windows-10-mixed-reality-pc-hardware-guidelines) pour connaître la configuration requise du matériel spécifique. Nous vous recommandons de respecter les directives du matériel [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Mixed Reality Ultra. |
| Contrôleurs de mouvements                        | Les contrôleurs de mouvements sont des accessoires matériels qui permettent aux utilisateurs d'agir en réalité mixte. Pour en savoir plus, voir [Contrôleurs de mouvement](https://docs.microsoft.com/windows/mixed-reality/motion-controllers).                                                                                                                     |

<a name="technical-requirements"></a>Exigences techniques
----------------------

| **Configuration requise**                   | **Détails**                                                                                                                                                                                                                                                                                                                                                                                             | **En savoir plus**                                                                                                                                                |
|------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [!include[pn-azure-active-directory](../includes/pn-azure-active-directory.md)] ([!include[pn-azure](../includes/pn-azure.md)] AD)  | Obligatoire pour se connecter à [!include[pn-dyn-365-layout](../includes/pn-dyn-365-layout.md)] et pour la distribution d'application par le biais de [Microsoft Store pour Entreprises](https://docs.microsoft.com/microsoft-store/sign-up-microsoft-store-for-business).                                                                                                                                                                                                               | [Mise en route d'Azure AD](https://docs.microsoft.com/azure/active-directory/get-started-azure-ad)                                                     |
| Connectivité réseau               | L'accès Internet est requis pour télécharger l'application et utiliser toutes ses fonctionnalités. Il n'y a aucune condition de bande passante.                                                                                                                                                                                                                                                                                    |                                                                                                                                                               |
| Applications pour le partage    | Le partage d'écran ou l'appel vidéo nécessite une application distincte, telle que [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] sur [!include[pn-hololens](../includes/pn-hololens.md)], ou bien Skype ou Skype Entreprise sur des casques immersifs. <br> <br>  Un PC [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 qui réponde aux spécifications de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Mixed Reality Ultra est également requis pour le partage d'écran ou l'appel vidéo lors de l'utilisation de [!include[pn-dyn-365-layout](../includes/pn-dyn-365-layout.md)] avec un casque immersif.                                                                                                                                                                                                               | [Dynamics 365 Remote Assist](../remote-assist/user-guide.md) <br> <br>  [Directives matérielles du PC Windows Mixed Reality](https://support.microsoft.com/help/4039260/windows-10-mixed-reality-pc-hardware-guidelines)                     |               
| [!include[pn-dyn-365-import-tool](../includes/pn-dyn-365-import-tool.md)] | [!include[pn-dyn-365-import-tool](../includes/pn-dyn-365-import-tool.md)] s'exécute sur des PC [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 et est requis pour le transfert de modèles 3D existants de votre PC vers [!include[pn-dyn-365-layout](../includes/pn-dyn-365-layout.md)], afin de permettre leur affichage et leur modification depuis [!include[pn-hololens](../includes/pn-hololens.md)] ou des casques immersifs. [!include[pn-dyn-365-import-tool](../includes/pn-dyn-365-import-tool.md)] est également requis pour le transfert des dimensions de l'espace [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-visio](../includes/pn-visio.md)] vers [!include[pn-hololens](../includes/pn-hololens.md)] ou des casques immersifs. | [Dynamics 365 Import Tool (version préliminaire)](https://docs.microsoft.com/dynamics365/mixed-reality/import-tool)    |

### <a name="see-also"></a>Voir aussi
[Essayer Dynamics 365 Layout gratuitement](try-layout-free.md)<br/>
[Acheter et déployer Dynamics 365 Layout](buy-and-deploy-layout.md)<br>
[Guide de l'utilisateur](user-guide.md)<br/>
[Vidéos pratiques](videos.md)<br/>
[FAQ](faq.md)<br/>
