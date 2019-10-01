---
author: BryceHo
description: Comment utiliser le portail d'appareil Windows pour accélérer l'étalonnage d'HoloLens lors de l'utilisation de Dynamics 365 Guides en version préliminaire
ms.author: mamaylya
ms.date: 04/29/2019
ms.service: crm-online
ms.topic: article
title: Utiliser le portail d'appareil Windows pour simplifier l'étalonnage d'HoloLens
ms.reviewer: v-brycho
ms.openlocfilehash: b1ec7242ec2849240f7dd1bfe55bd995b29e9db7
ms.sourcegitcommit: 5ce5fa810e391fade0b9fdef30077606cb1ae84d
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 08/22/2019
ms.locfileid: "1918047"
---
# <a name="use-the-windows-device-portal-to-streamline-hololens-calibration"></a>Utiliser le portail d'appareil Windows pour simplifier l'étalonnage d'HoloLens

[!INCLUDE [cc-beta-prerelease-disclaimer](../includes/cc-beta-prerelease-disclaimer.md)]
 
Vous pouvez utiliser le portail d'appareil Windows pour configurer et gérer Microsoft HoloLens à distance à l'aide du Wi-Fi ou d'un câble USB. Le portail d'appareil Windows est un serveur Web sur HoloLens auquel vous pouvez vous connecter à l'aide d'un navigateur Web de votre PC. Le portail inclut de nombreux outils qui permettent de gérer votre HoloLens. Il offre également une méthode rapide pour mettre à jour les paramètres de distance interpupillaire (DIP) au moment de faire passer les utilisateurs sur HoloLens. La mise à jour d'un DIP via le portail prend environ **2 secondes**. La mise à jour d'un DIP en étalonnant à nouveau HoloLens prend environ **2 minutes**.

Pour utiliser le portail :

1. Procurez-vous votre DIP en étalonnant le périphérique HoloLens. 

2. Notez votre DIP.

3. Entrez-le dans le portail chaque fois que vous faites passer des utilisateurs dans HoloLens. 

## <a name="set-up-your-hololens-to-use-the-windows-device-portal"></a>Configurer HoloLens pour utiliser le portail d'appareil Windows

Avant d'accéder au portail d'appareil Windows, vous devez le configurer dans HoloLens :

1.  Branchez votre appareil HoloLens et mettez-le sous tension.

2.  Écartez des doigts paume vers le haut pour ouvrir le menu **Démarrer**.

3.  Pointez la vignette **Paramètres** du regard et cliquez dans l'air pour la sélectionner. Cliquez une deuxième fois dans l'air pour placer l'application dans votre environnement. Cela démarre l'application Paramètres.

4.  Sélectionnez l'élément de menu **Mettre à jour**.

5.  Sélectionnez l'élément de menu **Pour les développeurs**.

6.  Activez le **Mode développeur**.

7.  Faites défiler l'écran et activez **Activer le portail d'appareil**.

    ![Paramètre Activer le portail d'appareil](media/developers-settings.PNG "Paramètre Activer le portail d'appareil")
 
## <a name="connect-with-wi-fi"></a>Se connecter avec le WiFi

1.  [Connectez HoloLens au Wi-Fi](https://docs.microsoft.com/en-us/windows/mixed-reality/connecting-to-wi-fi-on-hololens).

2.  Recherchez l'adresse IP de votre appareil.

    - Pour trouver l'adresse IP sur l'appareil, accédez à **Paramètres > Réseau et Internet > WiFi > Options avancées**.
    
    - Pour accéder à l'adresse IP à partir d'un navigateur Web sur votre PC, allez dans https://<votre_adresse_IP_HoloLens>.
    
      Le navigateur afficher le message suivant : « Un problème concernant le certificat de sécurité de ce site a été détecté ». Cela est dû au fait que le certificat émis pour le portail d'appareil est un certificat de test. Vous pouvez ignorer cette erreur pour l'instant.

      Vous arrivez alors au portail d'appareil Windows. Vous pouvez alors définir le DIP à l'aide de la procédure décrite plus loin dans cette rubrique.

## <a name="connect-with-usb"></a>Se connecter avec un câble USB

1.  [Installez les outils](https://docs.microsoft.com/en-us/windows/mixed-reality/install-the-tools) pour installer Visual Studio Update 1 avec les outils de développement Windows 10 sur votre PC. La connectivité USB est alors activée :

2.  Connectez votre appareil HoloLens à votre PC avec un câble micro-USB.

3.  Dans votre navigateur Web sur votre PC, accédez à [http://127.0.0.1:10080](http://127.0.0.1:10080).

    Vous arrivez alors au portail d'appareil Windows. Vous pouvez alors définir le DIP à l'aide de la procédure décrite dans la rubrique suivante.

## <a name="use-the-windows-device-portal-to-update-your-ipd"></a>Utiliser le portail d'appareil Windows pour mettre à jour votre DIP

Vous êtes désormais prêt à modifier les paramètres DIP de l'appareil à l'aide du portail d'appareil Windows. Pour obtenir votre DIP pour la première fois :

1.  Dans le portail d'appareil Windows, accédez à **Système > Préférences**. 

    Votre DIP s'affiche si c'est vous qui avez effectué l'étalonnage de HoloLens.

2.  Notez le numéro. À l'avenir, lorsque vous devez modifier les paramètres DIP sur l'appareil, connectez-vous à l'appareil, accédez au portail d'appareil Windows, puis modifiez les informations de DIP dans le même champ. 

    ![Paramètre DIP](media/ipd-setting.PNG "Paramètre DIP")
 
> [!TIP]
> Pensez à conserver un fichier partagé des DIP avec tous des membres de l'équipe, ou demandez aux utilisateurs de mémoriser leur DIP. 


