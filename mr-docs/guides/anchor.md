---
author: Mamaylya
description: Découvrez comment ancrer des hologrammes dans Dynamics 365 Guides et comment créer un point d'ancrage imprimé ou un point d'ancrage numérique.
ms.author: mamaylya
ms.date: 10/01/2019
ms.service: crm-online
ms.topic: article
title: Choisir une méthode d'ancrage pour votre guide dans Dynamics 365 Guides
ms.reviewer: v-brycho
ms.openlocfilehash: f0989e200c22092b7c04cf36ef82925644c9e444
ms.sourcegitcommit: f37698eb33fd4d198b054e73ce3d9ec680c56e21
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/02/2019
ms.locfileid: "2537130"
---
# <a name="anchor-your-guide-to-the-real-world"></a>Ancrer votre guide dans le monde réel

Lorsque vous créez un guide avec [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], une des premières étapes consiste à choisir une méthode d'ancrage. Lorsque vous ancrez un guide, vous le synchronisez dans l'espace avec un environnement du monde réel. L'ancrage permet de savoir où sont placés les hologrammes dans le monde réel. Vous devez créer un point d'ancrage pour votre guide pour qu'il fonctionne sur HoloLens.

Il est important de s'assurer que l'alignement de votre guide est correct et aussi précis que possible. Si le guide est mal aligné, vos instructions risquent d'indiquer des actions à des emplacements incorrects, ce qui peut créer la confusion chez l'opérateur ou endommager des composants.

Il existe deux façons d'ancrer un guide :

- Avec un **point d'ancrage imprimé** (recommandé), vous alignez un guide en pointant du regard (analysant) un point d'ancrage imprimé associé à un objet physique dans le monde réel. [Visionner une vidéo sur la création d'un point d'ancrage imprimé](https://aka.ms/guidesprintedanchor).

- Avec un **point d'ancrage numérique**, vous alignez un guide sur un hologramme 3D numérique qui est superposé sur un objet physique dans le monde réel. [Visionner une vidéo sur la création d'un point d'ancrage numérique](https://aka.ms/guidesdigitalanchor).

Un point d'ancrage imprimé est recommandé, car il est plus précis. Vous souhaitez ou vous devez peut-être utiliser un point d'ancrage numérique pour les raisons suivantes :

- Il n'est pas possible d'associer un point d'ancrage imprimé car il a été créé dans un emplacement différent de celui où se trouvent les pièces.

- Il n'est pas possible d'associer un point d'ancrage imprimé en raison de la présence de pièces mobiles.

- Vous ne pouvez pas garantir que l'emplacement du point d'ancrage imprimé est identique à chaque fois.

- La pièce est trop petite pour être attachée à un point d'ancrage imprimé.

## <a name="anchor-your-guide-by-using-a-printed-anchor"></a>Ancrer un guide à l'aide d'un point d'ancrage imprimé

L'utilisation d'un point d'ancrage imprimé implique trois étapes de base :

1.  L'impression d'un point d'ancrage [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

2.  L'association du marqueur à un objet physique dans le monde réel.

3.  Le pointage du point d'ancrage imprimé du regard pour aligner le guide.
   
Pour imprimer le point d'ancrage :

1. Assurez-vous que le fichier .pdf du point d'ancrage imprimé de Guides a été enregistré à partir de la page Configuration du point d'ancrage de l'application sur PC, puis ouvrez-le dans Adobe Acrobat Reader. 

2.  Dans le menu **Fichier**, sélectionnez **Imprimer**.

3.  Sous **Dimensionnement et gestion des pages**, sélectionnez l'option **Taille réelle**.

4.  L'impression de la dernière page du document en papier mat en tant que papier brillant peut affecter la numérisation. 

5.  Après l'impression, assurez-vous que l'espacement du marqueur correspond aux mesures figurant dans l'illustration suivante :

    ![Espacement du marqueur](media/marker-spacing.png "Espacement du marqueur")
 
> [!NOTE]
> Si l'espacement du marqueur n'est pas de +/- 0,1 mm, dans la boîte de dialogue **Imprimer**, sélectionnez l'option **Échelle personnalisée**, puis modifiez le pourcentage pour compenser l'écart de taille. Par exemple, si vous imprimez le point d'ancrage et que le résultat est de 49 mm, vous devez remplacer l'échelle par 100,4 % pour obtenir 49,196 mm, qui doit se situer dans la tolérance.

### <a name="best-practices-for-printed-anchors"></a>Recommandations en matière de points d'ancrage imprimés

Gardez à l'esprit les points suivants lorsque vous utilisez des points d'ancrage imprimés :

- **Même point d'ancrage pour la création et l'impression.** Pour une précision optimale, utilisez le **même** point d'ancrage imprimé pour la création et l'exécution. 

- **Taille.** Assurez-vous que votre point d'ancrage imprimé a la taille exacte indiquée dans ce document. Une taille de point d'ancrage incorrecte entraîne un mauvais alignement du guide. 

  - Certaines applications et imprimantes peuvent modifier la taille de l'image.
  
  - Si le point d'ancrage imprimé est supérieur à celui indiqué, [!include[pn-hololens](../includes/pn-hololens.md)] interprète la différence d'échelle en distance. Le point d'ancrage est alors identifié comme étant plus proche qu'il ne l'est réellement. 
  
  - L'impression à partir du fichier .pdf (comme décrit précédemment dans cette rubrique) est la meilleure façon de s'assurer que le point d'ancrage n'est pas redimensionné. 
  
- **Emplacement.** Placez le point d'ancrage sur l'objet physique dans un emplacement auquel il est facile d'accéder et à l'écart.

  - L'emplacement du point d'ancrage imprimé est idéalement central lors de la procédure.
  
  - Le contenu placé plus loin du point d'ancrage imprimé sera moins précis.
  
  - Placez le point d'ancrage à un emplacement où les opérateurs peuvent l'analyser de nouveau rapidement à des fins de réalignement à tout moment.
  
  - Prenez une photo ou une vidéo pour documenter le positionnement du point d'ancrage imprimé et l'ajouter aux instructions du guide et renforcer ainsi la confiance de l'opérateur. Pour prendre une photo ou une vidéo à partir de [!include[pn-hololens](../includes/pn-hololens.md)], voir [Capture de Réalité Mixte](https://docs.microsoft.com/windows/mixed-reality/mixed-reality-capture).
  
- **Angle de numérisation.** Placez-vous directement face au point d'ancrage, à la distance adéquate lorsque vous le pointez du regard. 

  - Une numérisation en angle peut entraîner un mauvais alignement.
  
  - La plage de numérisation idéale va de 60 à 80 cm.

### <a name="how-hololens-establishes-anchor-position-scale-and-orientation"></a>Procédure d'HoloLens pour établir le positionnement, le dimensionnement et l'orientation du point d'ancrage

Lors de la numérisation, la caméra avant de [!include[pn-hololens](../includes/pn-hololens.md)] mesure les distances horizontales et verticales par rapport au point d'ancrage. Ces informations sont combinées aux valeurs réelles du point d'ancrage stockées en interne dans l'application (49,2 mm et 32,8 mm comme indiqué dans l'illustration précédente) afin d'établir précisément le positionnement, l'échelle et l'orientation dans l'espace du point d'ancrage.

## <a name="anchor-your-guide-by-using-a-digital-anchor"></a>Ancrer un guide à l'aide d'un point d'ancrage numérique

Un point d'ancrage numérique implique deux étapes de base :

1.  À l'aide de l'application de création sur PC, importez et affectez un modèle 3D au flux de configuration du point d'ancrage numérique. Il peut s'agir d'une représentation d'un objet physique ou d'un objet 3D générique. Un point d'ancrage numérique par défaut est utilisé si vous ne sélectionnez pas de modèle 3D personnalisé.

2.  À l'aide du mode Créer dans [!include[pn-hololens](../includes/pn-hololens.md)], alignez le point d'ancrage numérique sur un objet physique dans le monde réel.

Pour importer un modèle 3D et l'affecter comme point d'ancrage numérique à l'aide de l'application de création sur PC : 

1.  Ouvrez l'application de création sur PC.

2.  Sélectionnez la commande **Importer** sur le côté droit de l'écran. 

3.  Dans la boîte de dialogue **Ouvrir**, sélectionnez le modèle 3D à utiliser comme jumeau numérique, puis sélectionnez **Ouvrir**.

    Le modèle 3D est alors ajouté dans la section **Composants 3D** de la bibliothèque.
    
4. Assurez-vous d'avoir sélectionné **Point d'ancrage numérique** comme type de point d'ancrage.
    
5. Dans l'étape 1, **Affecter**, de l'assistant d'ancrage, faites glisser le modèle 3D de la section Composants 3D vers l'emplacement. Le modèle 3D est alors affecté comme point d'ancrage numérique. 
   
> [!NOTE]
> Il est recommandé de prendre une photo ou une vidéo de l'objet physique de base et de l'emplacement où l'opérateur alignera le point d'ancrage numérique, et de charger la photo ou la vidéo dans l'étape 3 de l'assistant d'ancrage. Vous pouvez également personnaliser les instructions à l'étape 4 de l'assistant pour fournir des indications plus spécifiques sur quoi aligner le point d'ancrage numérique. 

Lorsque vous basculez dans l'application de création [!include[pn-hololens](../includes/pn-hololens.md)], vous pouvez faire un mouvement pour insérer la représentation 3D directement sur l'objet physique dans votre environnement de travail.

### <a name="to-align-the-digital-anchor-in-hololens"></a>Pour aligner le point d'ancrage numérique dans HoloLens

1. Ouvrez le guide dans HoloLens.

2. À l'invite, cliquez longuement dans l'air pour déplacer le point d'ancrage numérique directement sur un objet physique dans votre environnement de travail. Si vous devez faire pivoter l'objet, cliquez longuement dans l'air pour déplacer les sphères bleues.

### <a name="best-practices-for-digital-anchors"></a>Recommandations en matière de points d'ancrage numériques

- **Taille.** Sélectionnez un point d'ancrage numérique qui ne soit ni trop petit ni trop grand. 

  - Ce sont les objets numériques de taille moyenne qui conviennent le mieux. Il est difficile de manipuler les hologrammes très petits ou très grands. 
  
  - Le taille d'une boîte à chaussures ou un peu plus grande est idéale.
  
- **Position.** Choisissez un point d'ancrage numérique le plus proche possible du centre de la tâche à effectuer. Plus vous placez le contenu numérique loin du jumeau numérique, moins il sera précis.

- **Forme.** Sélectionnez un point d'ancrage numérique contenant une forme non-uniforme ou peu courante. Il est plus simple d'aligner des formes peu courantes.

  - Évitez les objets qui se reflètent. Cela peut entraîner un décalage à 180 degrés.
  
  - Choisissez des formes avec des bords et des coins clairement définis pour vous aider à orienter le contenu correctement.
  
- **Identifiable.** Sélectionnez un point d'ancrage numérique clairement défini, aisément reconnaissable, et facile à trouver pour l'opérateur. Assurez-vous qu'il puisse bien accéder à l'objet sans être gêné.

- **Direction d'alignement.** Alignez toujours le point d'ancrage numérique à votre objet physique à partir de la même direction. Cela augmente la répétabilité pour les opérateurs.

  - Si le placement est effectué à partir de perspectives différentes, cela peut entraîner un mauvais alignement.
  
  - Vous devez toujours le regarder à partir de plusieurs angles afin de garantir que le point d'ancrage numérique est bien aligné à l'objet physique.

## <a name="ensure-accuracy-of-anchors-alignment"></a>Garantir la précision des points d'ancrage (alignement)
Quelle que soit la méthode utilisée pour l'ancrage, ces facteurs supplémentaires peuvent impacter la précision de l'alignement et/ou la perception de l'utilisateur de l'alignement :

- **Paramètre de distance interpupillaire (DIP).** Le DIP est la distance entre le centre de chacune des pupilles de l'utilisateur. Il est primordial de définir un DIP approprié pour permettre à [!include[pn-hololens](../includes/pn-hololens.md)] d'adapter son affichage car les utilisateurs n'ont pas tous le même DIP. Un paramètre incorrect de DIP peut engendrer une mauvaise perception des hologrammes dans l'espace ainsi que leur instabilité. [Utiliser l'application d'étalonnage HoloLens pour étalonner votre DIP](https://docs.microsoft.com/windows/mixed-reality/calibration). 

- **Analyse préalable de l'environnement.** [!include[pn-hololens](../includes/pn-hololens.md)] analyse activement son environnement à la recherche de caractéristiques visibles pour créer des cartes. Cela se produit lorsque l'appareil est activé et qu'un utilisateur est connecté. Cette opération ne dépend pas du fait que vous soyez ou non dans le shell [!include[pn-hololens](../includes/pn-hololens.md)] ou les applications en cours d'exécution. [!include[pn-hololens](../includes/pn-hololens.md)] améliore constamment la précision de ces cartes grâce à l'analyse de l'environnement sous différents angles, qu'il enregistre ensuite sur l'appareil. Les hologrammes sont placés en fonction de ces cartes. Plus la carte est précise et plus la disposition des hologrammes est elle aussi précise.

Avant d'utiliser [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] sur un [!include[pn-hololens](../includes/pn-hololens.md)] qui ne maîtrise pas bien son environnement, l'utilisateur doit allumer [!include[pn-hololens](../includes/pn-hololens.md)], se connecter à l'appareil et parcourir l'espace où les instructions de l'hologramme sont ou seront placées. Cela peut être réalisé lorsque l'utilisateur se trouve dans le shell [!include[pn-hololens](../includes/pn-hololens.md)], mais nous lui recommandons de masquer le menu **Démarrer** pour afficher l'espace lorsqu'il se déplace. Le fait de se déplacer sans se presser et de regarder lentement vers le haut et le bas permet à l'appareil de détecter les caractéristiques et de créer des cartes précises. Cela s'appelle l'« analyse préalable » car elle est effectuée avant d'exécuter [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Vous n'avez à la faire qu'une seule fois pour chaque environnement car [!include[pn-hololens](../includes/pn-hololens.md)] enregistre les cartes qu'il a créées dans l'appareil et garde en mémoire les espaces qu'il a analysés.

   Les environnements très foncés ou très lumineux, ou ceux composés de surfaces très réfléchies (miroirs), ainsi que les surfaces sombres ou monochromes, risquent d'avoir un impact négatif sur la capacité d'[!include[pn-hololens](../includes/pn-hololens.md)] à identifier l'espace, ce qui aura un impact sur la position et la stabilité de l'hologramme.

- **Impact du positionnement d'un appareil.** [!include[pn-hololens](../includes/pn-hololens.md)] utilise une nouvelle technologie d'affichage pour projeter des images dans le champ de vision de l'utilisateur, ce qui crée des hologrammes. La façon dont l'utilisateur porte l'appareil sur la tête a un impact énorme sur la façon dont est perçue la position des hologrammes. Pour bien comprendre cela, la meilleure façon est d'ajuster le positionnement de l'appareil tout en alignant les hologrammes à leurs homologues physiques dans [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Observez comment l'alignement des hologrammes est affecté lorsque vous déplacez l'appareil de gauche à droite, de haut en bas et si vous faites avancer ou reculer l'affichage. Les utilisateurs doivent toujours porter l'appareil de la même façon et comprendre que de petits décalages dans son positionnement sont à peine perceptibles, mais peuvent entraîner d'importants changements dans la façon dont sont perçus les emplacements des hologrammes.
   
- **Utilisation du même point d'ancrage pour la création et l'exécution.** Pour une précision optimale, utilisez le même point d'ancrage pour la création et l'exécution. 

### <a name="see-also"></a>Voir aussi

[Créer un guide à l'aide de l'application du PC](pc-authoring.md)</br>
[Créer un guide à l'aide de l'application HoloLens](hololens-authoring.md)
