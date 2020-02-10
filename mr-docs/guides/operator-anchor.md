---
author: Mamaylya
description: Ancrer un guide dans l'application Dynamics 365 Guides HoloLens si vous êtes opérateur
ms.author: mamaylya
ms.date: 01/28/2020
ms.service: crm-online
ms.topic: article
title: Ancrer un guide dans l'application Dynamics 365 Guides HoloLens en tant qu'opérateur
ms.reviewer: v-brycho
ms.openlocfilehash: 3af6eed45f38d3dd818bda41eb8aa2c238f63384
ms.sourcegitcommit: 217d31bb34e67a6b8823d5ddac7ef8d56d054139
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/29/2020
ms.locfileid: "2995264"
---
# <a name="anchor-a-guide-in-the-dynamics-365-guides-hololens-app-operators"></a><span data-ttu-id="2b0d3-103">Ancrer un guide dans l'application Dynamics 365 Guides HoloLens (opérateurs)</span><span class="sxs-lookup"><span data-stu-id="2b0d3-103">Anchor a guide in the Dynamics 365 Guides HoloLens app (operators)</span></span>

<span data-ttu-id="2b0d3-104">La première chose qui s'affiche lorsque vous ouvrez un guide ce sont les instructions d'ancrage.</span><span class="sxs-lookup"><span data-stu-id="2b0d3-104">The first thing you see when you open a guide is the anchoring instructions for the guide.</span></span>  

<span data-ttu-id="2b0d3-105">![Analyser le point d'ancrage imprimé](media/scan-printed-anchor.png "Analyser le point d'ancrage imprimé")</span><span class="sxs-lookup"><span data-stu-id="2b0d3-105">![Scan printed anchor](media/scan-printed-anchor.png "Scan printed anchor")</span></span> 

> [!NOTE]
> <span data-ttu-id="2b0d3-106">L'écran supérieur indique les instructions d'ancrage pour un point d'ancrage imprimé.</span><span class="sxs-lookup"><span data-stu-id="2b0d3-106">The screen above shows the anchoring instructions for a printed anchor.</span></span> <span data-ttu-id="2b0d3-107">Cet écran aurait un aspect différent si vous deviez ancrer votre guide avec une ancre numérique.</span><span class="sxs-lookup"><span data-stu-id="2b0d3-107">This screen would look different if you need to anchor your guide with a digital anchor.</span></span> <span data-ttu-id="2b0d3-108">Les instructions d’ancrage vous indiqueront comment procéder pour ancrer votre guide.</span><span class="sxs-lookup"><span data-stu-id="2b0d3-108">The anchoring instructions will tell you how to go about anchoring your guide.</span></span>

<span data-ttu-id="2b0d3-109">L'ancrage d'un guide est une étape cruciale, comme l'étalonnage [!include[pn-hololens](../includes/pn-hololens.md)].</span><span class="sxs-lookup"><span data-stu-id="2b0d3-109">Anchoring a guide is a crucial step, just like calibrating [!include[pn-hololens](../includes/pn-hololens.md)].</span></span> <span data-ttu-id="2b0d3-110">Vous devez ancrer un guide pour garantir que les instructions holographiques sont bien alignées avec le monde réel.</span><span class="sxs-lookup"><span data-stu-id="2b0d3-110">You anchor a guide to make sure that the holographic instructions line up with your real-world environment.</span></span> <span data-ttu-id="2b0d3-111">Si les hologrammes ne sont pas alignés, vous risquez d'être perdu au moment d'effectuer une tâche.</span><span class="sxs-lookup"><span data-stu-id="2b0d3-111">If the holograms don’t line up, you’ll likely be confused when you try to do a task.</span></span> <span data-ttu-id="2b0d3-112">Cela risque même de provoquer des dégâts.</span><span class="sxs-lookup"><span data-stu-id="2b0d3-112">You could even cause damage.</span></span> <span data-ttu-id="2b0d3-113">Vous risquez par exemple de percer un trou au mauvais endroit.</span><span class="sxs-lookup"><span data-stu-id="2b0d3-113">For example, you might drill a hole in the wrong place.</span></span> 

## <a name="printed-anchors-vs-digital-anchors"></a><span data-ttu-id="2b0d3-114">Différences entre les points d'ancrage imprimés et les points d'ancrage numériques</span><span class="sxs-lookup"><span data-stu-id="2b0d3-114">Printed anchors vs digital anchors</span></span>

<span data-ttu-id="2b0d3-115">Il existe deux types de points d'ancrage : un point d'ancrage imprimé et un point d'ancrage numérique.</span><span class="sxs-lookup"><span data-stu-id="2b0d3-115">There are two types of anchors: a printed anchor and a digital anchor.</span></span> <span data-ttu-id="2b0d3-116">La façon dont vous ancrez votre guide dépend de la méthode utilisée.</span><span class="sxs-lookup"><span data-stu-id="2b0d3-116">The way you anchor your guide depends on which method is used.</span></span>

### <a name="anchor-your-guide-using-a-printed-anchor"></a><span data-ttu-id="2b0d3-117">Ancrer un guide à l'aide d'un point d'ancrage imprimé</span><span class="sxs-lookup"><span data-stu-id="2b0d3-117">Anchor your guide using a printed anchor</span></span>

1. <span data-ttu-id="2b0d3-118">Permet de rechercher un point d'ancrage imprimé associé à un objet physique dans votre environnement en monde réel.</span><span class="sxs-lookup"><span data-stu-id="2b0d3-118">Look for a printed anchor attached to a physical object in your real-world environment.</span></span> <span data-ttu-id="2b0d3-119">Voici un aperçu d'un point d'ancrage imprimé :</span><span class="sxs-lookup"><span data-stu-id="2b0d3-119">The printed anchor looks like this:</span></span> 

   <span data-ttu-id="2b0d3-120">![Marqueur imprimé](media/printed-marker.PNG "Marqueur imprimé")</span><span class="sxs-lookup"><span data-stu-id="2b0d3-120">![Printed marker](media/printed-marker.PNG "Printed marker")</span></span>

2. <span data-ttu-id="2b0d3-121">Dans votre application HoloLens, [!include[pn-hololens](../includes/pn-hololens.md)], vous verrez un hologramme très semblable au point d'ancrage imprimé.</span><span class="sxs-lookup"><span data-stu-id="2b0d3-121">On your HoloLens [!include[pn-hololens](../includes/pn-hololens.md)], you’ll see a hologram that looks very similar to the printed anchor.</span></span> <span data-ttu-id="2b0d3-122">Recherchez le point d'ancrage imprimé dans le monde réel, puis alignez l'hologramme du point d'ancrage avec le point d'ancrage imprimé.</span><span class="sxs-lookup"><span data-stu-id="2b0d3-122">Find the printed anchor in your real-world environment, and then align the anchor hologram with the printed anchor.</span></span>    
   
3. <span data-ttu-id="2b0d3-123">Si la case à cocher verte est alignée sur le point d'ancrage imprimé, pointez du regard l'option **Confirmer** pour la sélectionner.</span><span class="sxs-lookup"><span data-stu-id="2b0d3-123">When the green box is aligned to the printed anchor, gaze at **Confirm** to select it.</span></span>

   <span data-ttu-id="2b0d3-124">![Marqueur holographique](media/align-marker.PNG "Marqueur holographique")</span><span class="sxs-lookup"><span data-stu-id="2b0d3-124">![Holographic marker](media/align-marker.PNG "Holographic marker")</span></span> 

4. <span data-ttu-id="2b0d3-125">Lorsque vous voyez l'écran **Point d'ancrage imprimé trouvé**, suivez les instructions à l'écran, puis sélectionnez **Confirmer** pour continuer.</span><span class="sxs-lookup"><span data-stu-id="2b0d3-125">When you see the **Printed anchor found** screen, follow the instructions on the screen, and then select **Confirm** to continue.</span></span> 
 
   <span data-ttu-id="2b0d3-126">![Écran Point d'ancrage imprimé trouvé](media/printed-anchor-found.png "Écran Point d'ancrage imprimé trouvé")</span><span class="sxs-lookup"><span data-stu-id="2b0d3-126">![Printed anchor found screen](media/printed-anchor-found.png "Printed anchor found screen")</span></span> 

### <a name="anchor-your-guide-using-a-digital-anchor"></a><span data-ttu-id="2b0d3-127">Ancrer un guide à l'aide d'un point d'ancrage numérique</span><span class="sxs-lookup"><span data-stu-id="2b0d3-127">Anchor your guide using a digital anchor</span></span>

<span data-ttu-id="2b0d3-128">Avec un point d'ancrage numérique, vous alignez un hologramme sur votre [!include[pn-hololens](../includes/pn-hololens.md)] avec un objet similaire dans le monde réel.</span><span class="sxs-lookup"><span data-stu-id="2b0d3-128">With a digital anchor, you align a hologram on your [!include[pn-hololens](../includes/pn-hololens.md)] with a similar object in the real world.</span></span> 

<span data-ttu-id="2b0d3-129">![Exemple de point d'ancrage numérique](media/digital-anchor-example.PNG "Exemple de point d'ancrage numérique")</span><span class="sxs-lookup"><span data-stu-id="2b0d3-129">![Digital anchor example](media/digital-anchor-example.PNG "Digital anchor example")</span></span> 

<span data-ttu-id="2b0d3-130">Pour aligner le point d'ancrage numérique sur son homologue du monde réel, cliquez longuement dans l’air pour déplacer l'hologramme, puis appuyez longuement sur les sphères bleues pour faire pivoter l'hologramme, si nécessaire.</span><span class="sxs-lookup"><span data-stu-id="2b0d3-130">To align the digital anchor with its real-world counterpart, air tap and hold to move the hologram, and tap and hold the blue spheres to rotate the hologram, if needed.</span></span>

<span data-ttu-id="2b0d3-131">![Faire pivoter le point d'ancrage numérique](media/rotate-digital-anchor.PNG "Faire pivoter le point d'ancrage numérique")</span><span class="sxs-lookup"><span data-stu-id="2b0d3-131">![Rotate digital anchor](media/rotate-digital-anchor.PNG "Rotate digital anchor")</span></span>

## <a name="where-alignment-information-is-stored"></a><span data-ttu-id="2b0d3-132">Où sont enregistrées les informations d'alignement</span><span class="sxs-lookup"><span data-stu-id="2b0d3-132">Where alignment information is stored</span></span> 

<span data-ttu-id="2b0d3-133">Lorsque vous alignez votre guide, si vous utilisez [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-hololens](../includes/pn-hololens.md)] Commercial Suite, les informations d'alignement sont enregistrées dans votre [!include[pn-hololens](../includes/pn-hololens.md)], vous n'avez donc pas à réaligner le guide chaque fois que vous l'ouvrez.</span><span class="sxs-lookup"><span data-stu-id="2b0d3-133">When you align your guide, if you’re using the [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-hololens](../includes/pn-hololens.md)] Commercial Suite, the alignment information is stored on [!include[pn-hololens](../includes/pn-hololens.md)] so you don’t have to realign the guide every time you open it.</span></span> <span data-ttu-id="2b0d3-134">Vous pouvez toutefois réaligner un guide à tout moment, si vous estimez que les hologrammes ne sont pas bien alignés.</span><span class="sxs-lookup"><span data-stu-id="2b0d3-134">You can realign a guide at any time, though, if you feel the holograms are out of alignment.</span></span> <span data-ttu-id="2b0d3-135">Pour plus d'informations, consultez les informations sur le bouton **Ancrer** dans la section suivante.</span><span class="sxs-lookup"><span data-stu-id="2b0d3-135">For more information, read about the **Anchor** button in the next section.</span></span> 
 
## <a name="whats-next"></a><span data-ttu-id="2b0d3-136">Étapes suivantes</span><span class="sxs-lookup"><span data-stu-id="2b0d3-136">What's next?</span></span>

[<span data-ttu-id="2b0d3-137">Étalonner HoloLens</span><span class="sxs-lookup"><span data-stu-id="2b0d3-137">Calibrate your HoloLens</span></span>](operator-calibrate.md)<br>
[<span data-ttu-id="2b0d3-138">Installer l'application et se connecter</span><span class="sxs-lookup"><span data-stu-id="2b0d3-138">Install the app and sign in</span></span>](install-sign-in-operator.md)<br>
[<span data-ttu-id="2b0d3-139">Mouvements pour naviguer dans l'application</span><span class="sxs-lookup"><span data-stu-id="2b0d3-139">Gestures for navigating the app</span></span>](operator-gestures.md)<br>
[<span data-ttu-id="2b0d3-140">Utiliser un guide</span><span class="sxs-lookup"><span data-stu-id="2b0d3-140">Operate a guide</span></span>](operator-orientation.md)
