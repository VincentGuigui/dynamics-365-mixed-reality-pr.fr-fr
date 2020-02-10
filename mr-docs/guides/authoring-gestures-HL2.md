---
author: Mamaylya
description: Découvrez comment utiliser le toucher, le rayon émanant de la main et le pointage du regard d'HoloLens 2 pour naviguer et manipuler les hologrammes dans Microsoft Dynamics 365 Guides.
ms.author: mamaylya
ms.date: 01/28/2020
ms.service: crm-online
ms.topic: article
title: Manipulations HoloLens 2 (par exemple, le toucher, le rayon émanant de la main et le pointage du regard) pour créer et naviguer dans Dynamics 365 Guides
ms.reviewer: v-brycho
ms.openlocfilehash: 6150fb31892d4f48f74625e3d1e8008e70cf9d91
ms.sourcegitcommit: 217d31bb34e67a6b8823d5ddac7ef8d56d054139
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/29/2020
ms.locfileid: "2995249"
---
# <a name="hololens-2-gestures-for-authoring-and-navigating-in-dynamics-365-guides"></a><span data-ttu-id="60e2f-103">Mouvements HoloLens 2 pour la création et la navigation dans Dynamics 365 Guides</span><span class="sxs-lookup"><span data-stu-id="60e2f-103">HoloLens 2 gestures for authoring and navigating in Dynamics 365 Guides</span></span>

<span data-ttu-id="60e2f-104">Le suivi de la main dans Microsoft [!include[pn-hololens](../includes/pn-hololens.md)] 2 fournit des interactions instinctives pour les auteurs.</span><span class="sxs-lookup"><span data-stu-id="60e2f-104">Hand-tracking in Microsoft [!include[pn-hololens](../includes/pn-hololens.md)] 2 provides instinctual interactions for authors.</span></span> <span data-ttu-id="60e2f-105">Vous pouvez sélectionner et positionner des hologrammes par contact direct, comme s'il s'agissait d'objets réels.</span><span class="sxs-lookup"><span data-stu-id="60e2f-105">You can select and position holograms by using direct touch, just as if they were real objects.</span></span> <span data-ttu-id="60e2f-106">Vous pouvez aussi utiliser les rayons émanant de la main pour interagir avec les hologrammes qui sont hors de portée.</span><span class="sxs-lookup"><span data-stu-id="60e2f-106">You can also use hand rays to interact with holograms that are out of reach.</span></span>

> [!NOTE]
> <span data-ttu-id="60e2f-107">Si vous utilisez HoloLens 1, voir [Mouvements pour la création et la navigation pour HoloLens1](authoring-gestures.md).</span><span class="sxs-lookup"><span data-stu-id="60e2f-107">If you're using HoloLens 1, see [Authoring and navigating gestures for HoloLens 1](authoring-gestures.md).</span></span>

## <a name="basic-actions-and-gestures-to-know"></a><span data-ttu-id="60e2f-108">Actions et gestes de base à connaître</span><span class="sxs-lookup"><span data-stu-id="60e2f-108">Basic actions and gestures to know</span></span>

<span data-ttu-id="60e2f-109">Pour créer ou naviguer dans [!include[pn-hololens](../includes/pn-hololens.md)] 2, vous devez savoir comment effectuer ces actions et ces mouvements :</span><span class="sxs-lookup"><span data-stu-id="60e2f-109">To author or navigate in [!include[pn-hololens](../includes/pn-hololens.md)] 2, you must know how to do these actions and gestures:</span></span>

- <span data-ttu-id="60e2f-110">**Toucher**.</span><span class="sxs-lookup"><span data-stu-id="60e2f-110">**Touch**.</span></span> <span data-ttu-id="60e2f-111">Avec [!include[pn-hololens](../includes/pn-hololens.md)] 2 et [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous pouvez atteindre et toucher ou saisir des hologrammes.</span><span class="sxs-lookup"><span data-stu-id="60e2f-111">With [!include[pn-hololens](../includes/pn-hololens.md)] 2 and [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], you can reach out and touch or grab holograms.</span></span> <span data-ttu-id="60e2f-112">Cette approche est le moyen le plus simple et le plus intuitif de créer des guides.</span><span class="sxs-lookup"><span data-stu-id="60e2f-112">This approach is the easiest and most intuitive way to author guides.</span></span> <span data-ttu-id="60e2f-113">Comme le montre l'animation suivante, lorsque [!include[pn-hololens](../includes/pn-hololens.md)] voit votre main, un pointeur flottant (semblable à un pointeur de souris) apparaît près du bout de votre index pour vous aider à cibler les éléments.</span><span class="sxs-lookup"><span data-stu-id="60e2f-113">As the following animation shows, when [!include[pn-hololens](../includes/pn-hololens.md)] sees your hand, a floating pointer (similar to a mouse pointer) appears near the tip of your index finger to help you target elements.</span></span>

    <span data-ttu-id="60e2f-114">![Animation tactile](media/touch-dwell-animation.gif "Animation tactile")</span><span class="sxs-lookup"><span data-stu-id="60e2f-114">![Touch dwell animation](media/touch-dwell-animation.gif "Touch dwell animation")</span></span>

    > [!IMPORTANT]
    > <span data-ttu-id="60e2f-115">Utilisez l'interaction tactile pour travailler avec des pièces que vous avez placées dans le monde réel.</span><span class="sxs-lookup"><span data-stu-id="60e2f-115">Use touch interaction to work with parts that you've placed in the world.</span></span> <span data-ttu-id="60e2f-116">Dans [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], les fiches d'instructions (fiches étapes) doivent être tenues hors de portée lors de l'interaction tactile.</span><span class="sxs-lookup"><span data-stu-id="60e2f-116">In [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], instruction cards (Step cards) are meant to be kept out of the way so that they are out of reach for touch interaction.</span></span>

- <span data-ttu-id="60e2f-117">**Rayon émanant de la main**.</span><span class="sxs-lookup"><span data-stu-id="60e2f-117">**Hand ray**.</span></span> <span data-ttu-id="60e2f-118">Pour utiliser un rayon émanant de la main, tendez la main devant vous, la paume tournée vers l'extérieur.</span><span class="sxs-lookup"><span data-stu-id="60e2f-118">To use a hand ray, hold your hand in front of you, with your palm facing away.</span></span> <span data-ttu-id="60e2f-119">Un pointeur laser (rayon manuel) apparaît.</span><span class="sxs-lookup"><span data-stu-id="60e2f-119">A laser pointer (hand ray) appears.</span></span> <span data-ttu-id="60e2f-120">Après avoir ciblé un élément avec votre main, vous pouvez agir sur cette cible de différentes manières, comme décrit plus loin dans cette rubrique.</span><span class="sxs-lookup"><span data-stu-id="60e2f-120">After you target an item with your hand ray, you can act on that target in different ways, as described later in this topic.</span></span>

    <span data-ttu-id="60e2f-121">![Exemple de rayon émanant de la main](media/hand-rays-example.PNG "Exemple de rayon émanant de la main")</span><span class="sxs-lookup"><span data-stu-id="60e2f-121">![Hand ray example](media/hand-rays-example.PNG "Hand ray example")</span></span>

- <span data-ttu-id="60e2f-122">**Pointer du regard**.</span><span class="sxs-lookup"><span data-stu-id="60e2f-122">**Gaze**.</span></span> <span data-ttu-id="60e2f-123">Si l'élément comporte une zone ou un cercle de sélection (bouton de pointage du regard), vous pouvez le sélectionner en le pointant du regard.</span><span class="sxs-lookup"><span data-stu-id="60e2f-123">If the item has a selection box or circle (gaze/dwell button), you can select the item by gazing at it.</span></span> <span data-ttu-id="60e2f-124">L'élément est sélectionné lorsque la zone ou le cercle est rempli.</span><span class="sxs-lookup"><span data-stu-id="60e2f-124">The item is selected when the box or circle is filled.</span></span> <span data-ttu-id="60e2f-125">Vous allez souvent pointer du regard et cliquer dans l'air en même temps.</span><span class="sxs-lookup"><span data-stu-id="60e2f-125">Often, you will use gaze and air tap together.</span></span> <span data-ttu-id="60e2f-126">Lorsque vous pointez du regard, tournez toute la tête, pas seulement vos yeux.</span><span class="sxs-lookup"><span data-stu-id="60e2f-126">When you gaze, turn your whole head, not just your eyes.</span></span> <span data-ttu-id="60e2f-127">Le pointeur suit.</span><span class="sxs-lookup"><span data-stu-id="60e2f-127">The pointer will follow.</span></span>

    <span data-ttu-id="60e2f-128">![Animation pointage du regard](media/gaze-animation.gif "Animation pointage du regard")</span><span class="sxs-lookup"><span data-stu-id="60e2f-128">![Gaze animation](media/gaze-animation.gif "Gaze animation")</span></span>

- <span data-ttu-id="60e2f-129">**Cliquer dans l'air**.</span><span class="sxs-lookup"><span data-stu-id="60e2f-129">**Air tap**.</span></span> <span data-ttu-id="60e2f-130">Maintenez la main tendue devant vous, le poing légèrement desserré, puis pointez votre index en direction du plafond, baissez votre index, puis relevez-le rapidement.</span><span class="sxs-lookup"><span data-stu-id="60e2f-130">Hold your hand straight out in front of you in a loose fist, point your index finger straight up toward the ceiling, tap your finger down, and then quickly raise it back up again.</span></span>

    <span data-ttu-id="60e2f-131">![Animation en cliquant dans l'air](media/air-tap-animation.gif "Animation en cliquant dans l'air")</span><span class="sxs-lookup"><span data-stu-id="60e2f-131">![Air tap animation](media/air-tap-animation.gif "Air tap animation")</span></span>

- <span data-ttu-id="60e2f-132">**Cliquer longuement dans l’air**.</span><span class="sxs-lookup"><span data-stu-id="60e2f-132">**Air tap and hold**.</span></span> <span data-ttu-id="60e2f-133">Commencez par cliquer dans l'air, mais laissez votre doigt vers le bas au lieu de le lever de nouveau.</span><span class="sxs-lookup"><span data-stu-id="60e2f-133">Start by air tapping, but keep your finger down instead of raising it back up.</span></span>

### <a name="gesture-frame"></a><span data-ttu-id="60e2f-134">Cadre du mouvement</span><span class="sxs-lookup"><span data-stu-id="60e2f-134">Gesture frame</span></span>

<span data-ttu-id="60e2f-135">Il est également important de connaître le cadre du mouvement.</span><span class="sxs-lookup"><span data-stu-id="60e2f-135">It's also important to know about the gesture frame.</span></span> [!include[pn-hololens](../includes/pn-hololens.md)] <span data-ttu-id="60e2f-136">2 comporte des capteurs capables de détecter à plusieurs mètres d'un côté ou de l'autre.</span><span class="sxs-lookup"><span data-stu-id="60e2f-136">2 has sensors that can see a few feet to each side of you.</span></span> <span data-ttu-id="60e2f-137">Lorsque vous faites des mouvements, vous devez rester à l'intérieur de ce cadre.</span><span class="sxs-lookup"><span data-stu-id="60e2f-137">When you use gestures, you must keep them inside that frame.</span></span> <span data-ttu-id="60e2f-138">Sinon, [!include[pn-hololens](../includes/pn-hololens.md)] ne les verra pas.</span><span class="sxs-lookup"><span data-stu-id="60e2f-138">Otherwise, [!include[pn-hololens](../includes/pn-hololens.md)] won't see them.</span></span> <span data-ttu-id="60e2f-139">Lorsque vous vous déplacez, la cadre se déplace avec vous.</span><span class="sxs-lookup"><span data-stu-id="60e2f-139">As you move around, the frame moves with you.</span></span> <span data-ttu-id="60e2f-140">Lorsque votre main est à l'intérieur du cadre, un rayon va apparaître de votre paume.</span><span class="sxs-lookup"><span data-stu-id="60e2f-140">When your hand is inside the frame, a hand ray will appear from your palm.</span></span> <span data-ttu-id="60e2f-141">Si [!include[pn-hololens](../includes/pn-hololens.md)] ne peut pas voir vos mains, et que vous regardez un élément d'interface utilisateur (UI), vous verrez le pointeur de regard au centre de votre affichage.</span><span class="sxs-lookup"><span data-stu-id="60e2f-141">If [!include[pn-hololens](../includes/pn-hololens.md)] can't see your hands, and you're looking at a user interface (UI) element, you'll see the gaze pointer in the center of your display.</span></span>

## <a name="work-with-close-up-ui-elements-and-holograms-by-using-touch"></a><span data-ttu-id="60e2f-142">Travailler avec des éléments d'interface utilisateur et des hologrammes en gros plan en utilisant le toucher</span><span class="sxs-lookup"><span data-stu-id="60e2f-142">Work with close-up UI elements and holograms by using touch</span></span>

<span data-ttu-id="60e2f-143">Pour utiliser des éléments d'interface utilisateur et des hologrammes en gros plan, vous pouvez simplement les atteindre et les toucher ou les saisir avec vos mains.</span><span class="sxs-lookup"><span data-stu-id="60e2f-143">For close-up UI elements and holograms, you can just reach out and touch or grab them with your hands.</span></span> <span data-ttu-id="60e2f-144">Lorsque votre main se rapproche suffisamment pour toucher ou saisir un hologramme, un visuel apparaît autour du contrôle pour vous indiquer ce qu'il fait.</span><span class="sxs-lookup"><span data-stu-id="60e2f-144">When your hand gets close enough to touch or grab a hologram, a visual appears around the control to let you know what that control does.</span></span>

### <a name="select-a-button"></a><span data-ttu-id="60e2f-145">Sélectionner un bouton</span><span class="sxs-lookup"><span data-stu-id="60e2f-145">Select a button</span></span>

- <span data-ttu-id="60e2f-146">Appuyez sur le bouton avec votre index.</span><span class="sxs-lookup"><span data-stu-id="60e2f-146">Push the button with your index finger.</span></span>

### <a name="select-a-hologram"></a><span data-ttu-id="60e2f-147">Sélectionner un hologramme</span><span class="sxs-lookup"><span data-stu-id="60e2f-147">Select a hologram</span></span>

- <span data-ttu-id="60e2f-148">Touchez l'hologramme avec votre index.</span><span class="sxs-lookup"><span data-stu-id="60e2f-148">Touch the hologram with your index finger.</span></span> <span data-ttu-id="60e2f-149">Les contrôles apparaîtront.</span><span class="sxs-lookup"><span data-stu-id="60e2f-149">The controls will appear.</span></span>

    <span data-ttu-id="60e2f-150">![Animation tactile](media/touch-dwell-animation.gif "Animation tactile")</span><span class="sxs-lookup"><span data-stu-id="60e2f-150">![Touch dwell animation](media/touch-dwell-animation.gif "Touch dwell animation")</span></span>

### <a name="move-a-hologram"></a><span data-ttu-id="60e2f-151">Déplacer un hologramme</span><span class="sxs-lookup"><span data-stu-id="60e2f-151">Move a hologram</span></span>

- <span data-ttu-id="60e2f-152">Saisissez la grande sphère blanche au centre des contrôles avec vos mains et déplacez-la où vous le souhaitez.</span><span class="sxs-lookup"><span data-stu-id="60e2f-152">Grab the large white sphere in the center of the controls with your hands, and move it where you want.</span></span> <span data-ttu-id="60e2f-153">La sphère s'allumera en fonction de la position de votre index.</span><span class="sxs-lookup"><span data-stu-id="60e2f-153">The sphere will light up based on where your index finger is in relation to it.</span></span>

    <span data-ttu-id="60e2f-154">![Déplacer un hologramme en utilisant le toucher](media/touch-move.gif "Déplacer un hologramme en utilisant le toucher")</span><span class="sxs-lookup"><span data-stu-id="60e2f-154">![Move a hologram by using touch](media/touch-move.gif "Move a hologram by using touch")</span></span>

### <a name="rotate-a-hologram"></a><span data-ttu-id="60e2f-155">Faire pivoter un hologramme</span><span class="sxs-lookup"><span data-stu-id="60e2f-155">Rotate a hologram</span></span>

- <span data-ttu-id="60e2f-156">Pincez l'une des sphères bleues (contrôles de rotation) et faites-la pivoter comme vous le souhaitez.</span><span class="sxs-lookup"><span data-stu-id="60e2f-156">Pinch one of the blue spheres (rotation controls), and rotate it the way that you want.</span></span> <span data-ttu-id="60e2f-157">Des flèches apparaissent autour des contrôles de rotation pour indiquer dans quelle direction ils peuvent être tournés.</span><span class="sxs-lookup"><span data-stu-id="60e2f-157">Arrows appear around the rotation controls to show which direction they can be rotated.</span></span>

    <span data-ttu-id="60e2f-158">**Rotation gauche/droite**</span><span class="sxs-lookup"><span data-stu-id="60e2f-158">**Left/right rotation**</span></span>

    <span data-ttu-id="60e2f-159">![Faire pivoter vers la droite en utilisant le toucher](media/touch-rotate-right.gif "Faire pivoter vers la droite en utilisant le toucher")</span><span class="sxs-lookup"><span data-stu-id="60e2f-159">![Rotate right by using touch](media/touch-rotate-right.gif "Rotate right by using touch")</span></span>

    <span data-ttu-id="60e2f-160">**Rotation haut/bas**</span><span class="sxs-lookup"><span data-stu-id="60e2f-160">**Up/down rotation**</span></span>

    <span data-ttu-id="60e2f-161">![Tourner de haut en bas en utilisant le toucher](media/touch-rotate-up-down.gif "Tourner de haut en bas en utilisant le toucher")</span><span class="sxs-lookup"><span data-stu-id="60e2f-161">![Rotate up and down by using touch](media/touch-rotate-up-down.gif "Rotate up and down by using touch")</span></span>

    <span data-ttu-id="60e2f-162">**Rotation libre**</span><span class="sxs-lookup"><span data-stu-id="60e2f-162">**Free rotation**</span></span>

    <span data-ttu-id="60e2f-163">![Faire pivoter dans n'importe quelle direction en utilisant le toucher](media/touch-free-rotate.gif "Faire pivoter dans n'importe quelle direction en utilisant le toucher")</span><span class="sxs-lookup"><span data-stu-id="60e2f-163">![Free rotate by using touch](media/touch-free-rotate.gif "Free rotate by using touch")</span></span>

### <a name="change-the-size-of-a-hologram"></a><span data-ttu-id="60e2f-164">Modifier la taille d'un hologramme</span><span class="sxs-lookup"><span data-stu-id="60e2f-164">Change the size of a hologram</span></span>

- <span data-ttu-id="60e2f-165">Pincez le cadran bleu (contrôle **Échelle**) sur le côté droit de la pièce.</span><span class="sxs-lookup"><span data-stu-id="60e2f-165">Pinch the blue dial (**Scale** control) on the right side of the part.</span></span> <span data-ttu-id="60e2f-166">Une piste de curseur apparaît au-dessus et en dessous du contrôle **Échelle** pour afficher la mise à l'échelle vers le haut ou vers le bas.</span><span class="sxs-lookup"><span data-stu-id="60e2f-166">A slider track appears above and below the **Scale** control to show scaling up or down.</span></span>

    <span data-ttu-id="60e2f-167">![Changer la taille en utilisant le toucher](media/touch-scale-hologram.gif "Changer la taille en utilisant le toucher")</span><span class="sxs-lookup"><span data-stu-id="60e2f-167">![Change the size by using touch](media/touch-scale-hologram.gif "Change the size by using touch")</span></span>

### <a name="edit-a-hologram"></a><span data-ttu-id="60e2f-168">Modifier un hologramme</span><span class="sxs-lookup"><span data-stu-id="60e2f-168">Edit a hologram</span></span>

- <span data-ttu-id="60e2f-169">Touchez le bouton **Modifier l'hologramme** avec votre doigt, puis appuyez sur la commande souhaitée.</span><span class="sxs-lookup"><span data-stu-id="60e2f-169">Touch the **Edit hologram** button with your finger, and then touch the command that you want.</span></span>

    <span data-ttu-id="60e2f-170">![Modifier un hologramme en utilisant le toucher](media/touch-edit-menu.gif "Modifier un hologramme en utilisant le toucher")</span><span class="sxs-lookup"><span data-stu-id="60e2f-170">![Edit a hologram by using touch](media/touch-edit-menu.gif "Edit a hologram by using touch")</span></span>

## <a name="work-with-far-away-ui-elements-and-holograms-by-using-hand-rays-and-gaze"></a><span data-ttu-id="60e2f-171">Travailler avec des éléments d'interface utilisateur et des hologrammes éloignés en utilisant le rayon émanant de la main et le pointage du regard</span><span class="sxs-lookup"><span data-stu-id="60e2f-171">Work with far-away UI elements and holograms by using hand rays and gaze</span></span>

<span data-ttu-id="60e2f-172">Vous pouvez utiliser les rayons émanant de la main pour travailler avec des éléments d'interface utilisateur et des hologrammes éloignés.</span><span class="sxs-lookup"><span data-stu-id="60e2f-172">You can use hand rays to work with UI elements and holograms from a distance.</span></span> <span data-ttu-id="60e2f-173">Vous pouvez utiliser le pointage du regard pour travailler à distance avec la fiche d'instructions, mais vous ne pouvez pas l'utiliser pour manipuler des hologrammes.</span><span class="sxs-lookup"><span data-stu-id="60e2f-173">You can use gaze to work with the instruction card from a distance, but you can't use it to manipulate holograms.</span></span>

> [!TIP]
> <span data-ttu-id="60e2f-174">Lorsque vous créez un guide, si votre main est visible, les rayons émanant de la main sont activés et le pointage du regard est désactivé.</span><span class="sxs-lookup"><span data-stu-id="60e2f-174">When you author a guide, if your hand is visible, hand rays are enabled and gaze is disabled.</span></span> <span data-ttu-id="60e2f-175">Pour utiliser le pointage du regard, placez vos mains sur les côtés, de sorte que l'appareil [!include[pn-hololens](../includes/pn-hololens.md)] 2 ne puisse pas les voir.</span><span class="sxs-lookup"><span data-stu-id="60e2f-175">To use gaze, place your hands at your sides, so that the [!include[pn-hololens](../includes/pn-hololens.md)] 2 device can't see them.</span></span>

### <a name="select-a-button-or-ui-element-with-a-hand-ray"></a><span data-ttu-id="60e2f-176">Sélectionner un bouton ou un élément d'interface utilisateur avec un rayon émanant de la main</span><span class="sxs-lookup"><span data-stu-id="60e2f-176">Select a button or UI element with a hand ray</span></span>

1. <span data-ttu-id="60e2f-177">Pointez le rayon émanant de la main sur l'objet pour le cibler.</span><span class="sxs-lookup"><span data-stu-id="60e2f-177">Point your hand ray at the object to target it.</span></span>

2. <span data-ttu-id="60e2f-178">Suives l'une de ces étapes :</span><span class="sxs-lookup"><span data-stu-id="60e2f-178">Follow one of these steps:</span></span>

    - <span data-ttu-id="60e2f-179">Cliquez dans l'air pour sélectionner l'objet.</span><span class="sxs-lookup"><span data-stu-id="60e2f-179">Air tap to select the object.</span></span>

    - <span data-ttu-id="60e2f-180">S'il y a une boîte de sélection ou un cercle, maintenez le rayon émanant de la main dessus jusqu'à ce qu'il soit sélectionné.</span><span class="sxs-lookup"><span data-stu-id="60e2f-180">If there is a selection box or circle, hold your hand ray on it until it's selected.</span></span>

        <span data-ttu-id="60e2f-181">![Animation du rayon de la main s'attardant sur une fiche d'instructions](media/hand-ray-dwell-instruction-card-animation.gif "Animation du rayon de la main s'attardant sur une fiche d'instructions")</span><span class="sxs-lookup"><span data-stu-id="60e2f-181">![Hand ray dwell on an instruction card animation](media/hand-ray-dwell-instruction-card-animation.gif "Hand ray dwell on an instruction card animation")</span></span>

### <a name="manipulate-a-hologram-by-using-a-hand-ray"></a><span data-ttu-id="60e2f-182">Manipuler un hologramme à l'aide d'un rayon émanant de la main</span><span class="sxs-lookup"><span data-stu-id="60e2f-182">Manipulate a hologram by using a hand ray</span></span>

1. <span data-ttu-id="60e2f-183">Pointez le rayon émanant de la main sur l'objet pour le cibler.</span><span class="sxs-lookup"><span data-stu-id="60e2f-183">Point your hand ray at the object to target it.</span></span> <span data-ttu-id="60e2f-184">Des contrôles apparaissent autour de l'hologramme.</span><span class="sxs-lookup"><span data-stu-id="60e2f-184">Controls appear around the hologram.</span></span>

    <span data-ttu-id="60e2f-185">![Animation du rayon de la main](media/hand-ray-dwell-animation.gif "Animation du rayon de la main")</span><span class="sxs-lookup"><span data-stu-id="60e2f-185">![Hand ray dwell animation](media/hand-ray-dwell-animation.gif "Hand ray dwell animation")</span></span>

2. <span data-ttu-id="60e2f-186">Suives l'une de ces étapes :</span><span class="sxs-lookup"><span data-stu-id="60e2f-186">Follow one of these steps:</span></span>

    - <span data-ttu-id="60e2f-187">Pour déplacer l'hologramme, cliquez longuement dans l’air sur rayon émanant de la main, déplacez l'hologramme où vous le souhaitez, puis relâchez.</span><span class="sxs-lookup"><span data-stu-id="60e2f-187">To move the hologram, air tap and hold the hand ray, move the hologram where you want it, and then release.</span></span>

        <span data-ttu-id="60e2f-188">![Animation du déplacement du rayon émanant de la main](media/hand-ray-move-animation.gif "Animation du déplacement du rayon émanant de la main")</span><span class="sxs-lookup"><span data-stu-id="60e2f-188">![Hand ray move animation](media/hand-ray-move-animation.gif "Hand ray move animation")</span></span>

    - <span data-ttu-id="60e2f-189">Pour faire pivoter l'hologramme, cliquez longuement dans l'air sur l'une des sphères bleues. faites pivoter l'hologramme, puis relâchez.</span><span class="sxs-lookup"><span data-stu-id="60e2f-189">To rotate the hologram, air tap and hold one of the blue spheres, rotate the hologram, and then release.</span></span>

        <span data-ttu-id="60e2f-190">**Rotation gauche/droite**</span><span class="sxs-lookup"><span data-stu-id="60e2f-190">**Left/right rotation**</span></span>

        <span data-ttu-id="60e2f-191">![Animation de la rotation du rayon émanant de la main vers la gauche ou la droite](media/hand-ray-rotate-left-right-animation.gif "Animation de la rotation du rayon émanant de la main vers la gauche ou la droite")</span><span class="sxs-lookup"><span data-stu-id="60e2f-191">![Hand ray rotate left or right animation](media/hand-ray-rotate-left-right-animation.gif "Hand ray rotate left or right animation")</span></span>

        <span data-ttu-id="60e2f-192">**Rotation libre**</span><span class="sxs-lookup"><span data-stu-id="60e2f-192">**Free rotation**</span></span>

        <span data-ttu-id="60e2f-193">![Animation de la rotation sans rayon émanant de la main](media/hand-ray-free-rotate-animation.gif "Animation de la rotation sans rayon émanant de la main")</span><span class="sxs-lookup"><span data-stu-id="60e2f-193">![Hand ray free rotate animation](media/hand-ray-free-rotate-animation.gif "Hand ray free rotate animation")</span></span>

    - <span data-ttu-id="60e2f-194">Pour modifier la taille d'un hologramme, cliquez longuement dans l’air sur le contrôle **Échelle**.</span><span class="sxs-lookup"><span data-stu-id="60e2f-194">To change the size of a hologram, air tap and hold the **Scale** control.</span></span> <span data-ttu-id="60e2f-195">Pendant que vous appuyez sur le contrôle, déplacez-le vers le haut ou vers le bas le long du curseur.</span><span class="sxs-lookup"><span data-stu-id="60e2f-195">While you hold the control, move it up or down along the slider track.</span></span>

        <span data-ttu-id="60e2f-196">![Animation de la mise à l'échelle du rayon émanant de la main](media/hand-ray-scale-animation.gif "Animation de la mise à l'échelle du rayon émanant de la main")</span><span class="sxs-lookup"><span data-stu-id="60e2f-196">![Hand ray scale animation](media/hand-ray-scale-animation.gif "Hand ray scale animation")</span></span>

    - <span data-ttu-id="60e2f-197">Pour modifier l'hologramme, cliquez dans l'air sur le bouton **Modifier**, puis sur les sélections souhaitées.</span><span class="sxs-lookup"><span data-stu-id="60e2f-197">To edit the hologram, air tap the **Edit** button, and then air tap the selections that you want.</span></span>

        <span data-ttu-id="60e2f-198">![Animation de la modification d'un hologramme avec un rayon émanant de la main](media/hand-ray-edit-hologram-animation.gif "Animation de la modification d'un hologramme avec un rayon émanant de la main")</span><span class="sxs-lookup"><span data-stu-id="60e2f-198">![Hand ray edit a hologram animation](media/hand-ray-edit-hologram-animation.gif "Hand ray edit a hologram animation")</span></span>

### <a name="select-an-item-on-the-instruction-card-by-using-gaze"></a><span data-ttu-id="60e2f-199">Sélectionner un élément sur la fiche d'instructions en utilisant le pointage du regard</span><span class="sxs-lookup"><span data-stu-id="60e2f-199">Select an item on the instruction card by using gaze</span></span>

1. <span data-ttu-id="60e2f-200">Mettez vos mains sur les côtés et pointez du regard le bouton ou l'élément d'interface utilisateur.</span><span class="sxs-lookup"><span data-stu-id="60e2f-200">Put your hands at your sides, and gaze at the button or UI element.</span></span>

2. <span data-ttu-id="60e2f-201">Continuez à pointer du regard jusqu'à ce que le bouton soit rempli.</span><span class="sxs-lookup"><span data-stu-id="60e2f-201">Continue to gaze until the button is filled.</span></span>

    <span data-ttu-id="60e2f-202">![Animation du pointage du regard](media/gaze-animation.gif "Animation pointage du regard")</span><span class="sxs-lookup"><span data-stu-id="60e2f-202">![Gaze animation](media/gaze-animation.gif "Gaze animation")</span></span>

## <a name="open-the-start-menu"></a><span data-ttu-id="60e2f-203">Ouvrir le menu Démarrer</span><span class="sxs-lookup"><span data-stu-id="60e2f-203">Open the Start menu</span></span>

<span data-ttu-id="60e2f-204">Sur HoloLens 2, vous pouvez utiliser une ou deux mains pour ouvrir le menu **Démarrer**.</span><span class="sxs-lookup"><span data-stu-id="60e2f-204">On HoloLens 2, you can use either one hand or two hands to open the **Start** menu.</span></span> <span data-ttu-id="60e2f-205">Si vous ne savez pas quoi faire, l'ouverture du menu **Démarrer** est un bon moyen de vous réorienter.</span><span class="sxs-lookup"><span data-stu-id="60e2f-205">If you're ever unsure what to do, opening the **Start** menu is a good way to get reoriented.</span></span>

### <a name="open-the-start-menu-with-one-hand"></a><span data-ttu-id="60e2f-206">Ouvrez le menu Démarrer d'une main</span><span class="sxs-lookup"><span data-stu-id="60e2f-206">Open the Start menu with one hand</span></span>

1. <span data-ttu-id="60e2f-207">Tendez l'une de vos mains, la paume vers le haut et regardez votre poignet.</span><span class="sxs-lookup"><span data-stu-id="60e2f-207">Hold out one of your hands with the palm facing up, and look at your wrist.</span></span> <span data-ttu-id="60e2f-208">Vous devriez voir un logo Microsoft Windows holographique.</span><span class="sxs-lookup"><span data-stu-id="60e2f-208">You should see a holographic Microsoft Windows logo.</span></span>

2. <span data-ttu-id="60e2f-209">Avec la main que vous tendez, touchez votre index avec votre pouce dans un mouvement de pincement.</span><span class="sxs-lookup"><span data-stu-id="60e2f-209">With the hand that you're holding out, touch your index finger to your thumb in a pinching motion.</span></span>

    <span data-ttu-id="60e2f-210">![Ouvrir le menu Démarrer d'une seule main](media/open-start-menu-one-hand.png "Ouvrez le menu Démarrer d'une main")</span><span class="sxs-lookup"><span data-stu-id="60e2f-210">![Open the Start menu with one hand](media/open-start-menu-one-hand.png "Open the Start menu with one hand")</span></span>

### <a name="open-the-start-menu-with-two-hands"></a><span data-ttu-id="60e2f-211">Ouvrir le menu Démarrer avec les deux mains</span><span class="sxs-lookup"><span data-stu-id="60e2f-211">Open the Start menu with two hands</span></span>

1. <span data-ttu-id="60e2f-212">Tendez l'une de vos mains, la paume vers le haut et regardez votre poignet.</span><span class="sxs-lookup"><span data-stu-id="60e2f-212">Hold out one of your hands with the palm facing up, and look at your wrist.</span></span> <span data-ttu-id="60e2f-213">Vous devriez voir un logo Windows holographique.</span><span class="sxs-lookup"><span data-stu-id="60e2f-213">You should see a holographic Windows logo.</span></span>

2. <span data-ttu-id="60e2f-214">Avec l'index de votre autre main, touchez le logo Windows.</span><span class="sxs-lookup"><span data-stu-id="60e2f-214">With the index finger of your other hand, touch the Windows logo.</span></span>

    <span data-ttu-id="60e2f-215">![Graphique de la caméra vidéo](media/video-camera.PNG) [Visionner une vidéo sur l'ouverture du menu Démarrer avec les deux mains](https://www.microsoft.com/videoplayer/embed/RE3Wxng)</span><span class="sxs-lookup"><span data-stu-id="60e2f-215">![Video camera graphic](media/video-camera.PNG) [Watch a video about opening the Start menu with two hands](https://www.microsoft.com/videoplayer/embed/RE3Wxng)</span></span>

## <a name="need-a-tutorial-on-gestures"></a><span data-ttu-id="60e2f-216">Besoin d'un didacticiel pour apprendre les mouvements ?</span><span class="sxs-lookup"><span data-stu-id="60e2f-216">Need a tutorial on gestures?</span></span>

<span data-ttu-id="60e2f-217">Pour accéder à un didacticiel pour apprendre les mouvements de base, ouvrez le menu **Démarrer**, puis sélectionnez **Conseils**.</span><span class="sxs-lookup"><span data-stu-id="60e2f-217">For a tutorial on some basic gestures, open the **Start** menu, and then select **Tips**.</span></span> <span data-ttu-id="60e2f-218">Cette action ferme l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="60e2f-218">This action closes the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] app.</span></span>

## <a name="see-also"></a><span data-ttu-id="60e2f-219">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="60e2f-219">See also</span></span>

[<span data-ttu-id="60e2f-220">Mouvements HoloLens 2 pour faire fonctionner (parcourir) un guide</span><span class="sxs-lookup"><span data-stu-id="60e2f-220">HoloLens 2 gestures for operating (navigating) a guide</span></span>](operator-gestures-HL2.md)<br>
[<span data-ttu-id="60e2f-221">Étalonner votre appareil HoloLens 2</span><span class="sxs-lookup"><span data-stu-id="60e2f-221">Calibrate your HoloLens 2 device</span></span>](operator-calibrate-HL2.md)<br>
[<span data-ttu-id="60e2f-222">Mouvements HoloLens 1 pour la création et la navigation d'un guide</span><span class="sxs-lookup"><span data-stu-id="60e2f-222">HoloLens 1 gestures for authoring and navigating a guide</span></span>](authoring-gestures.md)<br>
[<span data-ttu-id="60e2f-223">Mouvements HoloLens 1 pour faire fonctionner (parcourir) un guide</span><span class="sxs-lookup"><span data-stu-id="60e2f-223">HoloLens 1 gestures for operating (navigating) a guide</span></span>](operator-gestures.md)
