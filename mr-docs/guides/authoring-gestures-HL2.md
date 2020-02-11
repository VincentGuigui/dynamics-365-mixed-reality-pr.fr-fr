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
# <a name="hololens-2-gestures-for-authoring-and-navigating-in-dynamics-365-guides"></a>Mouvements HoloLens 2 pour la création et la navigation dans Dynamics 365 Guides

Le suivi de la main dans Microsoft [!include[pn-hololens](../includes/pn-hololens.md)] 2 fournit des interactions instinctives pour les auteurs. Vous pouvez sélectionner et positionner des hologrammes par contact direct, comme s'il s'agissait d'objets réels. Vous pouvez aussi utiliser les rayons émanant de la main pour interagir avec les hologrammes qui sont hors de portée.

> [!NOTE]
> Si vous utilisez HoloLens 1, voir [Mouvements pour la création et la navigation pour HoloLens1](authoring-gestures.md).

## <a name="basic-actions-and-gestures-to-know"></a>Actions et gestes de base à connaître

Pour créer ou naviguer dans [!include[pn-hololens](../includes/pn-hololens.md)] 2, vous devez savoir comment effectuer ces actions et ces mouvements :

- **Toucher**. Avec [!include[pn-hololens](../includes/pn-hololens.md)] 2 et [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous pouvez atteindre et toucher ou saisir des hologrammes. Cette approche est le moyen le plus simple et le plus intuitif de créer des guides. Comme le montre l'animation suivante, lorsque [!include[pn-hololens](../includes/pn-hololens.md)] voit votre main, un pointeur flottant (semblable à un pointeur de souris) apparaît près du bout de votre index pour vous aider à cibler les éléments.

    ![Animation tactile](media/touch-dwell-animation.gif "Animation tactile")

    > [!IMPORTANT]
    > Utilisez l'interaction tactile pour travailler avec des pièces que vous avez placées dans le monde réel. Dans [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], les fiches d'instructions (fiches étapes) doivent être tenues hors de portée lors de l'interaction tactile.

- **Rayon émanant de la main**. Pour utiliser un rayon émanant de la main, tendez la main devant vous, la paume tournée vers l'extérieur. Un pointeur laser (rayon manuel) apparaît. Après avoir ciblé un élément avec votre main, vous pouvez agir sur cette cible de différentes manières, comme décrit plus loin dans cette rubrique.

    ![Exemple de rayon émanant de la main](media/hand-rays-example.PNG "Exemple de rayon émanant de la main")

- **Pointer du regard**. Si l'élément comporte une zone ou un cercle de sélection (bouton de pointage du regard), vous pouvez le sélectionner en le pointant du regard. L'élément est sélectionné lorsque la zone ou le cercle est rempli. Vous allez souvent pointer du regard et cliquer dans l'air en même temps. Lorsque vous pointez du regard, tournez toute la tête, pas seulement vos yeux. Le pointeur suit.

    ![Animation pointage du regard](media/gaze-animation.gif "Animation pointage du regard")

- **Cliquer dans l'air**. Maintenez la main tendue devant vous, le poing légèrement desserré, puis pointez votre index en direction du plafond, baissez votre index, puis relevez-le rapidement.

    ![Animation en cliquant dans l'air](media/air-tap-animation.gif "Animation en cliquant dans l'air")

- **Cliquer longuement dans l’air**. Commencez par cliquer dans l'air, mais laissez votre doigt vers le bas au lieu de le lever de nouveau.

### <a name="gesture-frame"></a>Cadre du mouvement

Il est également important de connaître le cadre du mouvement. [!include[pn-hololens](../includes/pn-hololens.md)] 2 comporte des capteurs capables de détecter à plusieurs mètres d'un côté ou de l'autre. Lorsque vous faites des mouvements, vous devez rester à l'intérieur de ce cadre. Sinon, [!include[pn-hololens](../includes/pn-hololens.md)] ne les verra pas. Lorsque vous vous déplacez, la cadre se déplace avec vous. Lorsque votre main est à l'intérieur du cadre, un rayon va apparaître de votre paume. Si [!include[pn-hololens](../includes/pn-hololens.md)] ne peut pas voir vos mains, et que vous regardez un élément d'interface utilisateur (UI), vous verrez le pointeur de regard au centre de votre affichage.

## <a name="work-with-close-up-ui-elements-and-holograms-by-using-touch"></a>Travailler avec des éléments d'interface utilisateur et des hologrammes en gros plan en utilisant le toucher

Pour utiliser des éléments d'interface utilisateur et des hologrammes en gros plan, vous pouvez simplement les atteindre et les toucher ou les saisir avec vos mains. Lorsque votre main se rapproche suffisamment pour toucher ou saisir un hologramme, un visuel apparaît autour du contrôle pour vous indiquer ce qu'il fait.

### <a name="select-a-button"></a>Sélectionner un bouton

- Appuyez sur le bouton avec votre index.

### <a name="select-a-hologram"></a>Sélectionner un hologramme

- Touchez l'hologramme avec votre index. Les contrôles apparaîtront.

    ![Animation tactile](media/touch-dwell-animation.gif "Animation tactile")

### <a name="move-a-hologram"></a>Déplacer un hologramme

- Saisissez la grande sphère blanche au centre des contrôles avec vos mains et déplacez-la où vous le souhaitez. La sphère s'allumera en fonction de la position de votre index.

    ![Déplacer un hologramme en utilisant le toucher](media/touch-move.gif "Déplacer un hologramme en utilisant le toucher")

### <a name="rotate-a-hologram"></a>Faire pivoter un hologramme

- Pincez l'une des sphères bleues (contrôles de rotation) et faites-la pivoter comme vous le souhaitez. Des flèches apparaissent autour des contrôles de rotation pour indiquer dans quelle direction ils peuvent être tournés.

    **Rotation gauche/droite**

    ![Faire pivoter vers la droite en utilisant le toucher](media/touch-rotate-right.gif "Faire pivoter vers la droite en utilisant le toucher")

    **Rotation haut/bas**

    ![Tourner de haut en bas en utilisant le toucher](media/touch-rotate-up-down.gif "Tourner de haut en bas en utilisant le toucher")

    **Rotation libre**

    ![Faire pivoter dans n'importe quelle direction en utilisant le toucher](media/touch-free-rotate.gif "Faire pivoter dans n'importe quelle direction en utilisant le toucher")

### <a name="change-the-size-of-a-hologram"></a>Modifier la taille d'un hologramme

- Pincez le cadran bleu (contrôle **Échelle**) sur le côté droit de la pièce. Une piste de curseur apparaît au-dessus et en dessous du contrôle **Échelle** pour afficher la mise à l'échelle vers le haut ou vers le bas.

    ![Changer la taille en utilisant le toucher](media/touch-scale-hologram.gif "Changer la taille en utilisant le toucher")

### <a name="edit-a-hologram"></a>Modifier un hologramme

- Touchez le bouton **Modifier l'hologramme** avec votre doigt, puis appuyez sur la commande souhaitée.

    ![Modifier un hologramme en utilisant le toucher](media/touch-edit-menu.gif "Modifier un hologramme en utilisant le toucher")

## <a name="work-with-far-away-ui-elements-and-holograms-by-using-hand-rays-and-gaze"></a>Travailler avec des éléments d'interface utilisateur et des hologrammes éloignés en utilisant le rayon émanant de la main et le pointage du regard

Vous pouvez utiliser les rayons émanant de la main pour travailler avec des éléments d'interface utilisateur et des hologrammes éloignés. Vous pouvez utiliser le pointage du regard pour travailler à distance avec la fiche d'instructions, mais vous ne pouvez pas l'utiliser pour manipuler des hologrammes.

> [!TIP]
> Lorsque vous créez un guide, si votre main est visible, les rayons émanant de la main sont activés et le pointage du regard est désactivé. Pour utiliser le pointage du regard, placez vos mains sur les côtés, de sorte que l'appareil [!include[pn-hololens](../includes/pn-hololens.md)] 2 ne puisse pas les voir.

### <a name="select-a-button-or-ui-element-with-a-hand-ray"></a>Sélectionner un bouton ou un élément d'interface utilisateur avec un rayon émanant de la main

1. Pointez le rayon émanant de la main sur l'objet pour le cibler.

2. Suives l'une de ces étapes :

    - Cliquez dans l'air pour sélectionner l'objet.

    - S'il y a une boîte de sélection ou un cercle, maintenez le rayon émanant de la main dessus jusqu'à ce qu'il soit sélectionné.

        ![Animation du rayon de la main s'attardant sur une fiche d'instructions](media/hand-ray-dwell-instruction-card-animation.gif "Animation du rayon de la main s'attardant sur une fiche d'instructions")

### <a name="manipulate-a-hologram-by-using-a-hand-ray"></a>Manipuler un hologramme à l'aide d'un rayon émanant de la main

1. Pointez le rayon émanant de la main sur l'objet pour le cibler. Des contrôles apparaissent autour de l'hologramme.

    ![Animation du rayon de la main](media/hand-ray-dwell-animation.gif "Animation du rayon de la main")

2. Suives l'une de ces étapes :

    - Pour déplacer l'hologramme, cliquez longuement dans l’air sur rayon émanant de la main, déplacez l'hologramme où vous le souhaitez, puis relâchez.

        ![Animation du déplacement du rayon émanant de la main](media/hand-ray-move-animation.gif "Animation du déplacement du rayon émanant de la main")

    - Pour faire pivoter l'hologramme, cliquez longuement dans l'air sur l'une des sphères bleues. faites pivoter l'hologramme, puis relâchez.

        **Rotation gauche/droite**

        ![Animation de la rotation du rayon émanant de la main vers la gauche ou la droite](media/hand-ray-rotate-left-right-animation.gif "Animation de la rotation du rayon émanant de la main vers la gauche ou la droite")

        **Rotation libre**

        ![Animation de la rotation sans rayon émanant de la main](media/hand-ray-free-rotate-animation.gif "Animation de la rotation sans rayon émanant de la main")

    - Pour modifier la taille d'un hologramme, cliquez longuement dans l’air sur le contrôle **Échelle**. Pendant que vous appuyez sur le contrôle, déplacez-le vers le haut ou vers le bas le long du curseur.

        ![Animation de la mise à l'échelle du rayon émanant de la main](media/hand-ray-scale-animation.gif "Animation de la mise à l'échelle du rayon émanant de la main")

    - Pour modifier l'hologramme, cliquez dans l'air sur le bouton **Modifier**, puis sur les sélections souhaitées.

        ![Animation de la modification d'un hologramme avec un rayon émanant de la main](media/hand-ray-edit-hologram-animation.gif "Animation de la modification d'un hologramme avec un rayon émanant de la main")

### <a name="select-an-item-on-the-instruction-card-by-using-gaze"></a>Sélectionner un élément sur la fiche d'instructions en utilisant le pointage du regard

1. Mettez vos mains sur les côtés et pointez du regard le bouton ou l'élément d'interface utilisateur.

2. Continuez à pointer du regard jusqu'à ce que le bouton soit rempli.

    ![Animation du pointage du regard](media/gaze-animation.gif "Animation pointage du regard")

## <a name="open-the-start-menu"></a>Ouvrir le menu Démarrer

Sur HoloLens 2, vous pouvez utiliser une ou deux mains pour ouvrir le menu **Démarrer**. Si vous ne savez pas quoi faire, l'ouverture du menu **Démarrer** est un bon moyen de vous réorienter.

### <a name="open-the-start-menu-with-one-hand"></a>Ouvrez le menu Démarrer d'une main

1. Tendez l'une de vos mains, la paume vers le haut et regardez votre poignet. Vous devriez voir un logo Microsoft Windows holographique.

2. Avec la main que vous tendez, touchez votre index avec votre pouce dans un mouvement de pincement.

    ![Ouvrir le menu Démarrer d'une seule main](media/open-start-menu-one-hand.png "Ouvrez le menu Démarrer d'une main")

### <a name="open-the-start-menu-with-two-hands"></a>Ouvrir le menu Démarrer avec les deux mains

1. Tendez l'une de vos mains, la paume vers le haut et regardez votre poignet. Vous devriez voir un logo Windows holographique.

2. Avec l'index de votre autre main, touchez le logo Windows.

    ![Graphique de la caméra vidéo](media/video-camera.PNG) [Visionner une vidéo sur l'ouverture du menu Démarrer avec les deux mains](https://www.microsoft.com/videoplayer/embed/RE3Wxng)

## <a name="need-a-tutorial-on-gestures"></a>Besoin d'un didacticiel pour apprendre les mouvements ?

Pour accéder à un didacticiel pour apprendre les mouvements de base, ouvrez le menu **Démarrer**, puis sélectionnez **Conseils**. Cette action ferme l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

## <a name="see-also"></a>Voir aussi

[Mouvements HoloLens 2 pour faire fonctionner (parcourir) un guide](operator-gestures-HL2.md)<br>
[Étalonner votre appareil HoloLens 2](operator-calibrate-HL2.md)<br>
[Mouvements HoloLens 1 pour la création et la navigation d'un guide](authoring-gestures.md)<br>
[Mouvements HoloLens 1 pour faire fonctionner (parcourir) un guide](operator-gestures.md)
