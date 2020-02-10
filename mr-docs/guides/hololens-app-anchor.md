---
author: Mamaylya
description: Découvrez comment ancrer un guide lorsque vous utilisez l'application Microsoft Dynamics 365 Guides HoloLens en mode Créer.
ms.author: mamaylya
ms.date: 01/28/2020
ms.service: crm-online
ms.topic: article
title: Ancrer un guide en mode Créer à l'aide de l'application Dynamics 365 Guides HoloLens
ms.reviewer: v-brycho
ms.openlocfilehash: 8f7d48182d3f3880d7963ab260c99706ad64206e
ms.sourcegitcommit: 217d31bb34e67a6b8823d5ddac7ef8d56d054139
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/29/2020
ms.locfileid: "2995261"
---
# <a name="anchor-a-guide-by-using-the-dynamics-365-guides-hololens-app-in-author-mode"></a>Ancrer un guide à l'aide de l'application Dynamics 365 Guides HoloLens en mode Créer

La première chose que vous voyez lorsque vous ouvrez un guide dans l'application Microsoft Dynamics 365 Guides HoloLens ce sont les instructions d'ancrage qui ont été créées dans l'application du PC Dynamics 365 Guides. La méthode que vous utilisez pour ancrer le guide dépend du type d'ancrage qui a été créé dans l'application du PC. Pour plus d'informations sur la création d'une ancre et sur les types d'ancrage, consultez [Ancrer votre guide dans le monde réel dans l'application du PC Dynamics 365 Guides](anchor.md).

## <a name="anchor-a-guide-by-using-a-printed-anchor"></a>Ancrer un guide à l'aide d'un point d'ancrage imprimé

1. Branchez votre appareil HoloLens, tenez-vous à environ deux mètres du point d'ancrage imprimé.

2. Sur la page **Analyser le point d'ancrage imprimé**, sélectionnez **Lancer l'analyse**.

    ![Bouton Lancer l'analyse sur la page Analyser le point d'ancrage imprimé](media/scan-printed-anchor.png "Bouton Lancer l'analyse sur la page Analyser le point d'ancrage imprimé")

    Sur [!include[pn-hololens](../includes/pn-hololens.md)], vous verrez une image de marqueur holographique qui ressemble à l'illustration suivante.

    ![Image d'un marqueur holographique](media/scanning.PNG "Image d'un marqueur holographique")

3. Fixez le point d'ancrage imprimé avec votre [!include[pn-hololens](../includes/pn-hololens.md)] jusqu'à ce qu'un contour vert apparaisse. Effectuez un pointage du regard pour aligner la zone verte à cocher sur le marqueur, puis sélectionnez **Confirmer**.

    ![Alignement avec le marqueur](media/align-marker.PNG "Alignement avec le marqueur")

    Lorsque le guide est correctement aligné, la page **Point d'ancrage imprimé trouvé** s'affiche.

    ![Page Point d'ancrage imprimé trouvé](media/printed-anchor-found.png "Page Point d'ancrage imprimé trouvé")

## <a name="anchor-a-guide-by-using-a-digital-anchor"></a>Ancrer un guide à l'aide d'un point d'ancrage numérique

- Cliquez longuement dans l’air pour déplacer et aligner le point d'ancrage numérique à ses équivalents du monde réel. Pour faire pivoter l'ancre, appuyez longuement sur les sphères bleues.

    ![Rotation d'un point d'ancrage numérique](media/rotate-digital-anchor.PNG "Rotation d'un point d'ancrage numérique")

> [!TIP]
> Sur [!include[pn-hololens](../includes/pn-hololens.md)] 2, vous pouvez utiliser votre main pour sélectionner et placer directement une ancre numérique lorsque vous créez un guide.

## <a name="re-anchor-a-guide"></a>Ancrer à nouveau un guide

Lorsque vous ancrez votre guide, les informations d'ancrage sont stockées sur votre [!include[pn-hololens](../includes/pn-hololens.md)]. Par conséquent, vous n'avez pas besoin de ré-ancrer le guide chaque fois que vous l'ouvrez. Vous pouvez toutefois utiliser le bouton **Ancrer** pour ancrer à nouveau un guide à tout moment, si vous estimez que les hologrammes ne sont pas bien alignés. Pour plus d'informations, voir [Placer des hologrammes, ajouter des styles, etc.](hololens-app-orientation.md)

> [!NOTE]
> Vous devrez peut-être ajuster le décalage du matériel dans les appareils [!include[pn-hololens](../includes/pn-hololens.md)] 1 pour garantir le positionnement exact du contenu 3D. [En savoir plus sur l'ajustement du décalage du matériel](https://docs.microsoft.com/dynamics365/mixed-reality/guides/known-issues#uploading-new-3d-models-with-names-matching-any-of-the-pre-packaged-models-in-the-3d-toolkit-will-overwrite-the-files-in-the-3d-toolkit).

## <a name="whats-next"></a>Étapes suivantes

[Placer des hologrammes, ajouter des styles, etc.](hololens-app-orientation.md)
