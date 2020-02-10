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
# <a name="anchor-a-guide-in-the-dynamics-365-guides-hololens-app-operators"></a>Ancrer un guide dans l'application Dynamics 365 Guides HoloLens (opérateurs)

La première chose qui s'affiche lorsque vous ouvrez un guide ce sont les instructions d'ancrage.  

![Analyser le point d'ancrage imprimé](media/scan-printed-anchor.png "Analyser le point d'ancrage imprimé") 

> [!NOTE]
> L'écran supérieur indique les instructions d'ancrage pour un point d'ancrage imprimé. Cet écran aurait un aspect différent si vous deviez ancrer votre guide avec une ancre numérique. Les instructions d’ancrage vous indiqueront comment procéder pour ancrer votre guide.

L'ancrage d'un guide est une étape cruciale, comme l'étalonnage [!include[pn-hololens](../includes/pn-hololens.md)]. Vous devez ancrer un guide pour garantir que les instructions holographiques sont bien alignées avec le monde réel. Si les hologrammes ne sont pas alignés, vous risquez d'être perdu au moment d'effectuer une tâche. Cela risque même de provoquer des dégâts. Vous risquez par exemple de percer un trou au mauvais endroit. 

## <a name="printed-anchors-vs-digital-anchors"></a>Différences entre les points d'ancrage imprimés et les points d'ancrage numériques

Il existe deux types de points d'ancrage : un point d'ancrage imprimé et un point d'ancrage numérique. La façon dont vous ancrez votre guide dépend de la méthode utilisée.

### <a name="anchor-your-guide-using-a-printed-anchor"></a>Ancrer un guide à l'aide d'un point d'ancrage imprimé

1. Permet de rechercher un point d'ancrage imprimé associé à un objet physique dans votre environnement en monde réel. Voici un aperçu d'un point d'ancrage imprimé : 

   ![Marqueur imprimé](media/printed-marker.PNG "Marqueur imprimé")

2. Dans votre application HoloLens, [!include[pn-hololens](../includes/pn-hololens.md)], vous verrez un hologramme très semblable au point d'ancrage imprimé. Recherchez le point d'ancrage imprimé dans le monde réel, puis alignez l'hologramme du point d'ancrage avec le point d'ancrage imprimé.    
   
3. Si la case à cocher verte est alignée sur le point d'ancrage imprimé, pointez du regard l'option **Confirmer** pour la sélectionner.

   ![Marqueur holographique](media/align-marker.PNG "Marqueur holographique") 

4. Lorsque vous voyez l'écran **Point d'ancrage imprimé trouvé**, suivez les instructions à l'écran, puis sélectionnez **Confirmer** pour continuer. 
 
   ![Écran Point d'ancrage imprimé trouvé](media/printed-anchor-found.png "Écran Point d'ancrage imprimé trouvé") 

### <a name="anchor-your-guide-using-a-digital-anchor"></a>Ancrer un guide à l'aide d'un point d'ancrage numérique

Avec un point d'ancrage numérique, vous alignez un hologramme sur votre [!include[pn-hololens](../includes/pn-hololens.md)] avec un objet similaire dans le monde réel. 

![Exemple de point d'ancrage numérique](media/digital-anchor-example.PNG "Exemple de point d'ancrage numérique") 

Pour aligner le point d'ancrage numérique sur son homologue du monde réel, cliquez longuement dans l’air pour déplacer l'hologramme, puis appuyez longuement sur les sphères bleues pour faire pivoter l'hologramme, si nécessaire.

![Faire pivoter le point d'ancrage numérique](media/rotate-digital-anchor.PNG "Faire pivoter le point d'ancrage numérique")

## <a name="where-alignment-information-is-stored"></a>Où sont enregistrées les informations d'alignement 

Lorsque vous alignez votre guide, si vous utilisez [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-hololens](../includes/pn-hololens.md)] Commercial Suite, les informations d'alignement sont enregistrées dans votre [!include[pn-hololens](../includes/pn-hololens.md)], vous n'avez donc pas à réaligner le guide chaque fois que vous l'ouvrez. Vous pouvez toutefois réaligner un guide à tout moment, si vous estimez que les hologrammes ne sont pas bien alignés. Pour plus d'informations, consultez les informations sur le bouton **Ancrer** dans la section suivante. 
 
## <a name="whats-next"></a>Étapes suivantes

[Étalonner HoloLens](operator-calibrate.md)<br>
[Installer l'application et se connecter](install-sign-in-operator.md)<br>
[Mouvements pour naviguer dans l'application](operator-gestures.md)<br>
[Utiliser un guide](operator-orientation.md)
