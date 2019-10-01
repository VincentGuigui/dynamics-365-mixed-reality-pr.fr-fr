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
# <a name="use-the-windows-device-portal-to-streamline-hololens-calibration"></a><span data-ttu-id="5d29c-103">Utiliser le portail d'appareil Windows pour simplifier l'étalonnage d'HoloLens</span><span class="sxs-lookup"><span data-stu-id="5d29c-103">Use the Windows Device Portal to streamline HoloLens calibration</span></span>

[!INCLUDE [cc-beta-prerelease-disclaimer](../includes/cc-beta-prerelease-disclaimer.md)]
 
<span data-ttu-id="5d29c-104">Vous pouvez utiliser le portail d'appareil Windows pour configurer et gérer Microsoft HoloLens à distance à l'aide du Wi-Fi ou d'un câble USB.</span><span class="sxs-lookup"><span data-stu-id="5d29c-104">You can use the Windows Device Portal to configure and manage Microsoft HoloLens remotely with Wi-Fi or USB.</span></span> <span data-ttu-id="5d29c-105">Le portail d'appareil Windows est un serveur Web sur HoloLens auquel vous pouvez vous connecter à l'aide d'un navigateur Web de votre PC.</span><span class="sxs-lookup"><span data-stu-id="5d29c-105">The Windows Device Portal is a web server on HoloLens that you can connect to from a web browser on your PC.</span></span> <span data-ttu-id="5d29c-106">Le portail inclut de nombreux outils qui permettent de gérer votre HoloLens.</span><span class="sxs-lookup"><span data-stu-id="5d29c-106">The portal includes many tools that help you manage your HoloLens.</span></span> <span data-ttu-id="5d29c-107">Il offre également une méthode rapide pour mettre à jour les paramètres de distance interpupillaire (DIP) au moment de faire passer les utilisateurs sur HoloLens.</span><span class="sxs-lookup"><span data-stu-id="5d29c-107">The portal also offers a fast way to update interpupillary distance settings (IPDs) when switching users on HoloLens.</span></span> <span data-ttu-id="5d29c-108">La mise à jour d'un DIP via le portail prend environ **2 secondes**.</span><span class="sxs-lookup"><span data-stu-id="5d29c-108">Updating an IPD via the portal takes about **2 seconds**.</span></span> <span data-ttu-id="5d29c-109">La mise à jour d'un DIP en étalonnant à nouveau HoloLens prend environ **2 minutes**.</span><span class="sxs-lookup"><span data-stu-id="5d29c-109">Updating the IPD by recalibrating HoloLens takes about **2 minutes**.</span></span>

<span data-ttu-id="5d29c-110">Pour utiliser le portail :</span><span class="sxs-lookup"><span data-stu-id="5d29c-110">To use the portal:</span></span>

1. <span data-ttu-id="5d29c-111">Procurez-vous votre DIP en étalonnant le périphérique HoloLens.</span><span class="sxs-lookup"><span data-stu-id="5d29c-111">Get your IPD by calibrating the HoloLens device.</span></span> 

2. <span data-ttu-id="5d29c-112">Notez votre DIP.</span><span class="sxs-lookup"><span data-stu-id="5d29c-112">Write your IPD down.</span></span>

3. <span data-ttu-id="5d29c-113">Entrez-le dans le portail chaque fois que vous faites passer des utilisateurs dans HoloLens.</span><span class="sxs-lookup"><span data-stu-id="5d29c-113">Enter it in the portal every time you switch users on HoloLens.</span></span> 

## <a name="set-up-your-hololens-to-use-the-windows-device-portal"></a><span data-ttu-id="5d29c-114">Configurer HoloLens pour utiliser le portail d'appareil Windows</span><span class="sxs-lookup"><span data-stu-id="5d29c-114">Set up your HoloLens to use the Windows Device Portal</span></span>

<span data-ttu-id="5d29c-115">Avant d'accéder au portail d'appareil Windows, vous devez le configurer dans HoloLens :</span><span class="sxs-lookup"><span data-stu-id="5d29c-115">Before accessing the Windows Device Portal, you need to set it up on HoloLens:</span></span>

1.  <span data-ttu-id="5d29c-116">Branchez votre appareil HoloLens et mettez-le sous tension.</span><span class="sxs-lookup"><span data-stu-id="5d29c-116">Put on your HoloLens device and turn on the power.</span></span>

2.  <span data-ttu-id="5d29c-117">Écartez des doigts paume vers le haut pour ouvrir le menu **Démarrer**.</span><span class="sxs-lookup"><span data-stu-id="5d29c-117">Do the bloom gesture to open the **Start** menu.</span></span>

3.  <span data-ttu-id="5d29c-118">Pointez la vignette **Paramètres** du regard et cliquez dans l'air pour la sélectionner.</span><span class="sxs-lookup"><span data-stu-id="5d29c-118">Gaze at the **Settings** tile, and then do an air tap to select it.</span></span> <span data-ttu-id="5d29c-119">Cliquez une deuxième fois dans l'air pour placer l'application dans votre environnement.</span><span class="sxs-lookup"><span data-stu-id="5d29c-119">Do a second air tap to place the app in your environment.</span></span> <span data-ttu-id="5d29c-120">Cela démarre l'application Paramètres.</span><span class="sxs-lookup"><span data-stu-id="5d29c-120">This starts the Settings app.</span></span>

4.  <span data-ttu-id="5d29c-121">Sélectionnez l'élément de menu **Mettre à jour**.</span><span class="sxs-lookup"><span data-stu-id="5d29c-121">Select the **Update** menu item.</span></span>

5.  <span data-ttu-id="5d29c-122">Sélectionnez l'élément de menu **Pour les développeurs**.</span><span class="sxs-lookup"><span data-stu-id="5d29c-122">Select the **For developers** menu item.</span></span>

6.  <span data-ttu-id="5d29c-123">Activez le **Mode développeur**.</span><span class="sxs-lookup"><span data-stu-id="5d29c-123">Turn on **Developer Mode**.</span></span>

7.  <span data-ttu-id="5d29c-124">Faites défiler l'écran et activez **Activer le portail d'appareil**.</span><span class="sxs-lookup"><span data-stu-id="5d29c-124">Scroll down and turn on **Enable Device Portal**.</span></span>

    <span data-ttu-id="5d29c-125">![Paramètre Activer le portail d'appareil](media/developers-settings.PNG "Paramètre Activer le portail d'appareil")</span><span class="sxs-lookup"><span data-stu-id="5d29c-125">![Enable Device Portal setting](media/developers-settings.PNG "Enable Device Portal setting")</span></span>
 
## <a name="connect-with-wi-fi"></a><span data-ttu-id="5d29c-126">Se connecter avec le WiFi</span><span class="sxs-lookup"><span data-stu-id="5d29c-126">Connect with Wi-Fi</span></span>

1.  <span data-ttu-id="5d29c-127">[Connectez HoloLens au Wi-Fi](https://docs.microsoft.com/en-us/windows/mixed-reality/connecting-to-wi-fi-on-hololens).</span><span class="sxs-lookup"><span data-stu-id="5d29c-127">[Connect your HoloLens to Wi-Fi](https://docs.microsoft.com/en-us/windows/mixed-reality/connecting-to-wi-fi-on-hololens).</span></span>

2.  <span data-ttu-id="5d29c-128">Recherchez l'adresse IP de votre appareil.</span><span class="sxs-lookup"><span data-stu-id="5d29c-128">Look up your device's IP address.</span></span>

    - <span data-ttu-id="5d29c-129">Pour trouver l'adresse IP sur l'appareil, accédez à **Paramètres > Réseau et Internet > WiFi > Options avancées**.</span><span class="sxs-lookup"><span data-stu-id="5d29c-129">To find the IP address on the device, go to **Settings > Network & Internet > Wi-Fi > Advanced Options**.</span></span>
    
    - <span data-ttu-id="5d29c-130">Pour accéder à l'adresse IP à partir d'un navigateur Web sur votre PC, allez dans https://<votre_adresse_IP_HoloLens>.</span><span class="sxs-lookup"><span data-stu-id="5d29c-130">To find the IP address from a web browser on your PC, go to https://<your_HoloLens_IP_address>.</span></span>
    
      <span data-ttu-id="5d29c-131">Le navigateur afficher le message suivant : « Un problème concernant le certificat de sécurité de ce site a été détecté ».</span><span class="sxs-lookup"><span data-stu-id="5d29c-131">The browser displays the following message: "There’s a problem with this website’s security certificate."</span></span> <span data-ttu-id="5d29c-132">Cela est dû au fait que le certificat émis pour le portail d'appareil est un certificat de test.</span><span class="sxs-lookup"><span data-stu-id="5d29c-132">This happens because the certificate issued to the Device Portal is a test certificate.</span></span> <span data-ttu-id="5d29c-133">Vous pouvez ignorer cette erreur pour l'instant.</span><span class="sxs-lookup"><span data-stu-id="5d29c-133">You can ignore this error for now.</span></span>

      <span data-ttu-id="5d29c-134">Vous arrivez alors au portail d'appareil Windows.</span><span class="sxs-lookup"><span data-stu-id="5d29c-134">This takes you to the Windows Device Portal.</span></span> <span data-ttu-id="5d29c-135">Vous pouvez alors définir le DIP à l'aide de la procédure décrite plus loin dans cette rubrique.</span><span class="sxs-lookup"><span data-stu-id="5d29c-135">Then you can set the IPD using the procedure later in this topic.</span></span>

## <a name="connect-with-usb"></a><span data-ttu-id="5d29c-136">Se connecter avec un câble USB</span><span class="sxs-lookup"><span data-stu-id="5d29c-136">Connect with USB</span></span>

1.  <span data-ttu-id="5d29c-137">[Installez les outils](https://docs.microsoft.com/en-us/windows/mixed-reality/install-the-tools) pour installer Visual Studio Update 1 avec les outils de développement Windows 10 sur votre PC.</span><span class="sxs-lookup"><span data-stu-id="5d29c-137">[Install the tools](https://docs.microsoft.com/en-us/windows/mixed-reality/install-the-tools) to make sure you have Visual Studio Update 1 with the Windows 10 developer tools installed on your PC.</span></span> <span data-ttu-id="5d29c-138">La connectivité USB est alors activée :</span><span class="sxs-lookup"><span data-stu-id="5d29c-138">This enables USB connectivity.</span></span>

2.  <span data-ttu-id="5d29c-139">Connectez votre appareil HoloLens à votre PC avec un câble micro-USB.</span><span class="sxs-lookup"><span data-stu-id="5d29c-139">Connect your HoloLens device to your PC with a micro-USB cable.</span></span>

3.  <span data-ttu-id="5d29c-140">Dans votre navigateur Web sur votre PC, accédez à [http://127.0.0.1:10080](http://127.0.0.1:10080).</span><span class="sxs-lookup"><span data-stu-id="5d29c-140">From a web browser on your PC, go to [http://127.0.0.1:10080](http://127.0.0.1:10080).</span></span>

    <span data-ttu-id="5d29c-141">Vous arrivez alors au portail d'appareil Windows.</span><span class="sxs-lookup"><span data-stu-id="5d29c-141">This takes you to the Windows Device Portal.</span></span> <span data-ttu-id="5d29c-142">Vous pouvez alors définir le DIP à l'aide de la procédure décrite dans la rubrique suivante.</span><span class="sxs-lookup"><span data-stu-id="5d29c-142">Then you can set the IPD using the procedure in the next topic.</span></span>

## <a name="use-the-windows-device-portal-to-update-your-ipd"></a><span data-ttu-id="5d29c-143">Utiliser le portail d'appareil Windows pour mettre à jour votre DIP</span><span class="sxs-lookup"><span data-stu-id="5d29c-143">Use the Windows Device Portal to update your IPD</span></span>

<span data-ttu-id="5d29c-144">Vous êtes désormais prêt à modifier les paramètres DIP de l'appareil à l'aide du portail d'appareil Windows.</span><span class="sxs-lookup"><span data-stu-id="5d29c-144">Now you’re ready to change the IPD settings for the device using the Windows Device Portal.</span></span> <span data-ttu-id="5d29c-145">Pour obtenir votre DIP pour la première fois :</span><span class="sxs-lookup"><span data-stu-id="5d29c-145">To obtain your IPD for the first time:</span></span>

1.  <span data-ttu-id="5d29c-146">Dans le portail d'appareil Windows, accédez à **Système > Préférences**.</span><span class="sxs-lookup"><span data-stu-id="5d29c-146">In the Windows Device Portal, go to **System > Preferences**.</span></span> 

    <span data-ttu-id="5d29c-147">Votre DIP s'affiche si c'est vous qui avez effectué l'étalonnage de HoloLens.</span><span class="sxs-lookup"><span data-stu-id="5d29c-147">You’ll see your IPD if you were the person that did the HoloLens calibration.</span></span>

2.  <span data-ttu-id="5d29c-148">Notez le numéro.</span><span class="sxs-lookup"><span data-stu-id="5d29c-148">Write the number down.</span></span> <span data-ttu-id="5d29c-149">À l'avenir, lorsque vous devez modifier les paramètres DIP sur l'appareil, connectez-vous à l'appareil, accédez au portail d'appareil Windows, puis modifiez les informations de DIP dans le même champ.</span><span class="sxs-lookup"><span data-stu-id="5d29c-149">In the future, whenever you need to change the IPD settings on the device, sign in to the device, go to the Windows Device Portal, and then change the IPD information in this same field.</span></span> 

    <span data-ttu-id="5d29c-150">![Paramètre DIP](media/ipd-setting.PNG "Paramètre DIP")</span><span class="sxs-lookup"><span data-stu-id="5d29c-150">![IPD setting](media/ipd-setting.PNG "IPD setting")</span></span>
 
> [!TIP]
> <span data-ttu-id="5d29c-151">Pensez à conserver un fichier partagé des DIP avec tous des membres de l'équipe, ou demandez aux utilisateurs de mémoriser leur DIP.</span><span class="sxs-lookup"><span data-stu-id="5d29c-151">Consider keeping a shared file with all your team members’ IPDs, or have users memorize their IPD.</span></span> 


