---
author: Mamaylya
description: Découvrez comment ancrer des hologrammes dans Dynamics 365 Guides et comment créer un point d'ancrage imprimé ou un point d'ancrage numérique.
ms.author: mamaylya
ms.date: 01/28/2020
ms.service: crm-online
ms.topic: article
title: Choisir une méthode d'ancrage pour votre guide dans Dynamics 365 Guides
ms.reviewer: v-brycho
ms.openlocfilehash: 38d9b570075ee16d726db20eb74c385e0d378543
ms.sourcegitcommit: 217d31bb34e67a6b8823d5ddac7ef8d56d054139
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/29/2020
ms.locfileid: "2994557"
---
# <a name="anchor-your-guide-to-the-real-world-in-the-dynamics-365-guides-pc-app"></a>Ancrer votre guide dans le monde réel dans l'application du PC Dynamics 365 Guides

Lorsque vous créez un guide avec l'application du PC [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], l'une des premières étapes consiste à choisir une méthode d'ancrage. Lorsque vous ancrez un guide, vous le synchronisez dans l'espace avec un environnement du monde réel (une usine, par exemple). L'ancrage permet de savoir où sont placés les hologrammes dans le monde réel. Vous devez créer un point d'ancrage pour votre guide pour qu'il fonctionne sur [!include[pn-hololens](../includes/pn-hololens.md)].

Il est important de s'assurer que l'alignement de votre guide est correct et aussi précis que possible. Si le guide est mal aligné, vos instructions risquent d'indiquer des actions à des emplacements incorrects, ce qui peut provoquer de la confusion chez l'opérateur ou endommager des composants.

## <a name="two-ways-to-anchor-a-guide"></a>Il existe deux façons d'ancrer un guide

Il existe deux façons d'ancrer un guide :

- Avec un **point d'ancrage imprimé** (recommandé), vous alignez un guide en pointant du regard (en analysant) un point d'ancrage imprimé associé à un objet physique dans le monde réel.

- Avec un **point d'ancrage numérique**, vous alignez un guide sur un hologramme 3D numérique qui est superposé sur un objet physique dans le monde réel. 

Un point d'ancrage imprimé est recommandé, car il est plus précis. Vous souhaitez ou vous devez peut-être utiliser un point d'ancrage numérique pour les raisons suivantes :

- Il n'est pas possible d'associer un point d'ancrage imprimé car il a été créé dans un emplacement différent de celui où se trouvent les pièces.

- Il n'est pas possible d'associer un point d'ancrage imprimé en raison de la présence de pièces mobiles.

- Vous ne pouvez pas garantir que l'emplacement du point d'ancrage imprimé est identique à chaque fois.

- La pièce est trop petite pour être attachée à un point d'ancrage imprimé.

[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] comprend un assistant d'**ancrage** qui facilite la sélection et la configuration du type d'ancrage le plus approprié à votre situation.

## <a name="anchor-your-guide-by-using-a-printed-anchor"></a>Ancrer un guide à l'aide d'un point d'ancrage imprimé

![Graphique de la caméra vidéo](media/video-camera.PNG "Graphique de la caméra vidéo") [Visionner une vidéo sur la création d'un point d'ancrage imprimé](https://aka.ms/guidesprintedanchor)

La création d'un point d'ancrage imprimé implique quatre étapes de base :

1. Utilisez l'assistant d'**ancrage** pour sélectionner une méthode d'ancrage.

2. Imprimez l'ancre à partir du fichier PDF créé par l'assistant d'**ancrage**.

3. Associez l'ancre imprimée à un objet physique dans le monde réel.

4. Pointez l'ancre du regard sur [!include[pn-hololens](../includes/pn-hololens.md)] pour ancrer le guide.

### <a name="set-up-a-printed-anchor"></a>Paramétrer le point d'ancrage imprimé

Vous pouvez accéder à l'assistant d'**ancrage** à partir de la page **Plan**. La page **Plan** apparaît automatiquement après avoir créé ou ouvert un guide.

1. Sur la page **Plan**, sélectionnez **Définir votre point d'ancrage maintenant**.

    ![Bouton Définir votre point d'ancrage maintenant](media/outline-page-3.PNG "Définir votre point d'ancrage maintenant")

2. Sur la page **Choisir une méthode d'ancrage**, dans la section **Point d'ancrage imprimé**, choisissez **Sélectionner**.

    ![Bouton de sélection de la vignette de point d'ancrage imprimé](media/choose-anchor-method.PNG "Bouton de sélection de la vignette de point d'ancrage imprimé")

3. À l'étape 1 de l'assistant, sélectionnez **Enregistrer pour imprimer** pour créer un fichier PDF nommé **Guides-PrintedAnchor**. Ce fichier comprend l'ancre que vous imprimerez à l'étape 6.

    ![Bouton Enregistrer pour imprimer](media/save-to-print-button.PNG "Bouton Enregistrer pour imprimer")

4. Ouvrez le fichier **Guides-PrintedAnchor** dans Adobe Acrobat Reader sur l'ordinateur.

5. Sélectionnez **Fichier** \> **Imprimer**, puis sous **Dimensionnement et gestion des pages**, sélectionnez l'option **Taille réelle**.

    ![Option de taille réelle](media/adobe-actual-size.PNG "Option de taille réelle")

6. Imprimez la dernière page du document sur du papier mat. (Le papier brillant peut compliquer la numérisation.)

7. Après l'impression, assurez-vous que l'espacement du marqueur correspond aux mesures figurant dans l'illustration suivante.

    ![Mesures du point d'ancrage imprimé](media/printed-anchor-measurements.PNG "Mesures du point d'ancrage imprimé")

    > [!NOTE]
    > Si l'espacement du point d'ancrage n'est pas de +/- 0,1 mm, dans la boîte de dialogue **Imprimer**, sélectionnez l'option **Échelle personnalisée**, puis modifiez le pourcentage pour compenser l'écart de taille. Par exemple, si vous imprimez le point d'ancrage et que le résultat est de 49 mm, vous devez remplacer l'échelle par 100,4 % pour obtenir 49,196 mm, et ainsi respecter ainsi le seuil de tolérance.

8. Associez l'ancre imprimée à un objet physique dans le monde réel, puis prenez une photo de l'endroit où vous placez le point d'ancrage numérique pour aider l'opérateur à le trouver.

9. Revenez à l'assistant d'**ancrage** de l'application du PC, puis sélectionnez **Suivant** deux fois. 

10. À l'étape 3 de l'assistant, sélectionnez le bouton **Importer** pour importer la photo que vous avez prise à l'étape 8. Faites-la ensuite glisser vers la zone **Importer la photo du placement du point d'ancrage**. Lorsque vous avez terminé, sélectionnez **Suivant** pour passer à l'étape suivante.

    ![Bouton d'importation](media/import-buttton.PNG "Bouton d'importation")

11. À l'étape 4 de l'assistant, si vous souhaitez modifier les instructions par défaut de l'opérateur, sélectionnez **Modifier le texte de la fiche étape**, puis entrez vos instructions. Lorsque vous avez terminé, sélectionnez **Suivant** pour passer à l'étape suivante.

    ![Bouton Modifier le texte de la fiche étape](media/edit-step-card-text-button.PNG "Bouton Modifier le texte de la fiche étape")

12. Branchez votre appareil [!include[pn-hololens](../includes/pn-hololens.md)], ouvrez votre guide, puis pointez l'ancre imprimée du regard pour ancrer le guide.

### <a name="best-practices-for-printed-anchors"></a>Recommandations en matière de points d'ancrage imprimés

Gardez à l'esprit les points suivants lorsque vous utilisez des points d'ancrage imprimés :

- **Surface du support.** Veillez à imprimer l'ancre sur du papier mat et ne plastifiez pas le papier. En effet, le papier brillant peut compliquer la numérisation en raison des reflets de la lumière. De plus, veillez à placer l'ancre sur une surface plate. Un ancre placée sur une surface plate et non sur une surface courbe ou déformée risque d'entraver l'alignement et la détection.

- **Même point d'ancrage pour la création et l'impression.** Pour une précision optimale, utilisez le **même** point d'ancrage imprimé pour la création et l'exécution.

- **Taille.** Assurez-vous que votre point d'ancrage imprimé a la taille exacte indiquée dans cette rubrique. Une taille de point d'ancrage incorrecte entraîne un mauvais alignement du guide.

    - Certaines applications et imprimantes peuvent modifier la taille de l'image.

    - Si l'ancre est supérieure à celle indiquée, [!include[pn-hololens](../includes/pn-hololens.md)] interprète la différence d'échelle en distance. L'ancre est alors identifiée comme étant plus proche que ce qu'elle ne l'est en réalité.

    - Pour s'assurer que le point d'ancrage n'est pas redimensionné, la meilleure façon est d'imprimer à partir du fichier .pdf (comme décrit précédemment dans cette rubrique).

- **Emplacement.** Placez l'ancre en dehors du passage à un emplacement facile d'accès sur l'objet physique.

    - L'emplacement de l'ancre imprimé est idéalement central lors de la procédure.

    - Le contenu placé plus loin du point d'ancrage imprimé sera moins précis.

    - Placez le point d'ancrage à un emplacement où les opérateurs peuvent l'analyser de nouveau rapidement à des fins de réalignement à tout moment.

    - Idéalement, l'ancre ne doit pas être déplacée après avoir été placée. Si elle ne peut pas être placée à un emplacement définitif, envisagez de créer un support pour pouvoir la placer systématiquement au même emplacement/selon la même orientation.

    - Prenez une photo ou une vidéo pour documenter le positionnement du point d'ancrage imprimé et l'ajouter aux instructions du guide et renforcer ainsi la confiance de l'opérateur. Pour prendre une photo ou une vidéo à partir de [!include[pn-hololens](../includes/pn-hololens.md)], voir [Capture de Réalité Mixte](https://docs.microsoft.com/windows/mixed-reality/mixed-reality-capture).

- **Angle de numérisation.** Placez-vous directement face au point d'ancrage, à la distance adéquate lorsque vous le pointez du regard. 

    - Numériser l'ancre sous l'angle de votre champ de vision peut entraîner un échec de détection ou un problème d'alignement.

    - La plage de numérisation idéale va de 60 à 80 cm.

### <a name="how-hololens-establishes-anchor-position-scale-and-orientation"></a>Procédure d'HoloLens pour établir le positionnement, le dimensionnement et l'orientation du point d'ancrage

Durant la numérisation, la caméra avant de [!include[pn-hololens](../includes/pn-hololens.md)] mesure les distances horizontales et verticales par rapport au point d'ancrage. Ces informations sont combinées aux valeurs réelles du point d'ancrage stockées en interne dans l'application (49,2 mm et 32,8 mm) afin d'établir précisément le positionnement, l'échelle et l'orientation dans l'espace du point d'ancrage.

[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] inclut une méthode de correction supplémentaire permettant à l'utilisateur d'améliorer l'alignement en remplaçant manuellement le décalage susceptible d'être généré par les fluctuations de l'image obtenue et de la taille de l'ancre. Pour plus d'informations, consultez la section [Positionnement correct des hologrammes pour des ancres de code circulaire](known-issues.md#how-do-i-address-hardware-offset-in-hololens-1-devices-to-ensure-accurate-placement-of-holograms-for-printed-anchor-alignment).

## <a name="anchor-your-guide-by-using-a-digital-anchor"></a>Ancrer un guide à l'aide d'un point d'ancrage numérique

![Graphique de la caméra vidéo](media/video-camera.PNG "Graphique de la caméra vidéo") [Visionner une vidéo sur la création d'un point d'ancrage numérique](https://aka.ms/guidesdigitalanchor)

Un point d'ancrage numérique implique deux étapes de base :

1. Utilisez l'assistant d'**ancrage** dans l'application du PC pour importer un modèle 3D personnalisé pouvant être utilisé comme ancre. Attribuez ensuite le modèle 3D comme point d'ancrage pour le guide. Il peut s'agir d'une représentation d'un objet physique ou d'un objet 3D générique. Un point d'ancrage numérique par défaut est utilisé si vous ne sélectionnez pas de modèle 3D personnalisé.

2. Dans l'application [!include[pn-hololens](../includes/pn-hololens.md)], en mode **Créer**, vous devez faire des mouvements pour aligner le point d'ancrage numérique sur un objet physique dans le monde réel.

### <a name="set-up-a-digital-anchor"></a>Paramétrer un point d'ancrage numérique

Vous pouvez accéder à l'assistant d'**ancrage** à partir de la page **Plan**. La page **Plan** apparaît automatiquement après avoir créé ou ouvert un guide.

1. Sur la page **Plan**, sélectionnez **Définir votre point d'ancrage maintenant**.

   ![Bouton Définir votre point d'ancrage maintenant](media/outline-page-3.PNG "Définir votre point d'ancrage maintenant")

2. Sur la page **Choisir une méthode d'ancrage**, dans la section **Point d'ancrage numérique**, choisissez **Sélectionner**.

   ![Bouton de sélection de la vignette Point d'ancrage numérique](media/choose-anchor-method-digital-anchor.PNG "Bouton de sélection de la vignette Point d'ancrage numérique")

3. À l'étape 1 de l'assistant, sélectionnez **Importation**, recherchez votre modèle 3D personnalisé, puis sélectionnez **Ouvrir** pour l'importer. Le modèle est ajouté à l'onglet **Objets 3D** de la galerie.

   ![Bouton d'importation](media/import-button-digital-anchor.PNG "Bouton d'importation")

4. Faites glisser le modèle 3D de l'onglet **Objets 3D** vers la zone **Attribuer un point d'ancrage numérique**. Le modèle 3D est attribué comme point d'ancrage numérique pour le guide. Lorsque vous avez terminé, sélectionnez **Suivant** pour passer à l'étape suivante.

   ![Zone Attribuer un point d'ancrage numérique](media/drag-model-digital-anchor.PNG "Zone Attribuer un point d'ancrage numérique")

5. Branchez votre appareil [!include[pn-hololens](../includes/pn-hololens.md)], ouvrez le guide, puis cliquez longuement dans l'air pour déplacer le point d'ancrage numérique directement sur un objet physique dans votre environnement de travail. Si vous devez faire pivoter l'objet, cliquez longuement dans l'air pour déplacer les sphères bleues.

   ![Sphères bleues](media/blue-spheres-digital-anchor.PNG "Sphères bleues")

   > [!TIP]
   > Sur [!include[pn-hololens](../includes/pn-hololens.md)] 2, vous pouvez utiliser votre main pour sélectionner et placer directement une ancre numérique lorsque vous créez un guide. Pour en savoir plus, consultez [Placer des hologrammes](https://docs.microsoft.com/dynamics365/mixed-reality/guides/hololens-authoring#place-your-holograms).

6. Prenez une photo de l'endroit où vous placez le point d'ancrage numérique, pour aider l'opérateur à le trouver.

7. Revenez à l'application du PC, puis sélectionnez **Suivant** deux fois dans l'assistant.

8. À l'étape 4 de l'assistant, sélectionnez le bouton **Importer** pour importer la photo que vous avez prise à l'étape 6. Faites-la ensuite glisser vers la zone **Importer une photo de l'emplacement du point d'ancrage**. Lorsque vous avez terminé, sélectionnez **Suivant** pour passer à l'étape suivante.

    ![Zone Importer une photo de l'emplacement du point d'ancrage](media/drag-photo-digital-anchor.PNG "Zone Importer une photo de l'emplacement du point d'ancrage")

9. À l'étape 5 de l'assistant, si vous souhaitez modifier les instructions par défaut de l'opérateur, sélectionnez **Modifier le texte de la fiche étape**, puis entrez vos instructions. Lorsque vous avez terminé, sélectionnez **Suivant** pour passer à l'étape suivante et sélectionnez **Confirmer**.

    ![Bouton Modifier le texte de la fiche étape](media/edit-step-card-text-digital-anchor.PNG "Bouton Modifier le texte de la fiche étape")

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

    - Vous devez toujours regarder le point d'ancrage numérique à partir de plusieurs angles afin de garantir qu'il est bien aligné à l'objet physique.

## <a name="change-from-one-anchor-type-to-the-other"></a>Passer d'un type d'ancrage à l'autre

1. Sur la page **Plan**, sélectionnez l'ancre en haut de la page ou sélectionnez le bouton **Ancrer** dans le volet de navigation de gauche. L'assistant d'**ancrage** s'ouvre.

    ![Bouton Ancrer et ancre](media/change-anchor-method.PNG "Bouton Ancrer et ancre")

2. Dans le coin inférieur gauche de la fenêtre de l'assistant, sélectionnez **Modifier la méthode d'ancrage**.

   ![Bouton Modifier la méthode d'ancrage](media/change-anchor-method-button.PNG "Bouton Modifier la méthode d'ancrage")

3. Sélectionnez le type d'ancrage à modifier.

4. Dans le message d'avertissement qui s'affiche, sélectionnez **Changer de méthode d'ancrage**.

## <a name="other-factors-that-affect-anchoring-accuracy"></a>D'autres facteurs qui affectent la précision d'ancrage

Les facteurs suivants peuvent aussi affecter la précision du positionnement de l'ancre et/ou la perception de l'alignement par l'utilisateur :

- **Paramètre de distance interpupillaire (DIP).** La DIP est la distance entre le centre de chacune des pupilles de l'utilisateur. Les utilisateurs n'ont pas tous la même DIP, il est donc primordial de définir une DIP appropriée pour permettre à [!include[pn-hololens](../includes/pn-hololens.md)] d'adapter son affichage. Un paramètre DIP incorrect peut entraîner une mauvaise perception. Il peut également provoquer une instabilité des hologrammes dans l'espace. Pour étalonner votre DIP dans [!include[pn-hololens](../includes/pn-hololens.md)] 1, [utilisez l'application Étalonnage d'HoloLens](https://docs.microsoft.com/windows/mixed-reality/calibration).

- **Analyse préalable de l'environnement.** [!include[pn-hololens](../includes/pn-hololens.md)] analyse activement son environnement à la recherche de caractéristiques pour cartographier les éléments environnants. Cette analyse se produit lorsque l'appareil est activé et qu'un utilisateur est connecté. Cette opération ne dépend pas du fait que vous soyez ou non dans le shell [!include[pn-hololens](../includes/pn-hololens.md)] ou les applications en cours d'exécution. [!include[pn-hololens](../includes/pn-hololens.md)] améliore constamment la précision de ces cartes grâce à l'analyse de l'environnement sous différents angles, qu'il enregistre ensuite sur l'appareil. Les hologrammes sont placés en fonction de ces cartes. Plus la carte est précise et plus le positionnement de l'hologramme est précis lui aussi.

    Avant d'utiliser [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] sur un [!include[pn-hololens](../includes/pn-hololens.md)] qui n'a encore jamais cartographié cet environnement, l'utilisateur doit installer le casque [!include[pn-hololens](../includes/pn-hololens.md)] devant ses yeux, se connecter à l'appareil et se déplacer dans la pièce où se trouvent/devraient s'afficher les instructions de l'hologramme. Bien que l'utilisateur puisse effectuer cette étape à partir du shell [!include[pn-hololens](../includes/pn-hololens.md)], nous recommandons de masquer le menu **Démarrer** afin que l'utilisateur puisse voir l'espace pendant qu'il se déplace. Le fait que l'utilisateur déplace sans se presser et de regarder lentement vers le haut et le bas permet à l'appareil de détecter les caractéristiques et de créer des cartes précises. Cela s'appelle l'« analyse préalable » car elle est effectuée avant d'exécuter [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Vous n'avez à la faire qu'une seule fois pour chaque environnement car [!include[pn-hololens](../includes/pn-hololens.md)] enregistre les cartes qu'il a créées dans l'appareil et garde en mémoire les espaces qu'il a analysés.

    Les environnements très sombres ou très lumineux, ou ceux composés de surfaces réfléchissantes (miroirs), ainsi que les surfaces sombres ou monochromes, risquent d'avoir un impact négatif sur la capacité de [!include[pn-hololens](../includes/pn-hololens.md)] à identifier l'espace. Ceci peut à la longue affecter la position et la stabilité de l'hologramme.

- **Impact du positionnement d'un appareil sur [!include[pn-hololens](../includes/pn-hololens.md)] 1.** [!include[pn-hololens](../includes/pn-hololens.md)] utilise une nouvelle technologie d'affichage pour projeter des images dans le champ de vision de l'utilisateur, ce qui crée des hologrammes. Avec [!include[pn-hololens](../includes/pn-hololens.md)] 1, la façon dont un utilisateur porte l'appareil sur la tête a énormément d'impact sur la perception du positionnement des hologrammes. Pour bien comprendre cela, la meilleure façon est d'ajuster le positionnement de l'appareil tout en alignant les hologrammes à leurs homologues physiques dans [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Notez combien l'alignement des hologrammes est affecté lorsque vous déplacez l'appareil de gauche à droite, de haut en bas et si vous faites avancer ou reculer l'affichage. Les utilisateurs doivent toujours porter l'appareil de la même façon et comprendre que de petits décalages dans son positionnement sont à peine perceptibles, mais peuvent entraîner d'importants changements dans la façon dont sont perçus les emplacements des hologrammes. [!include[pn-hololens](../includes/pn-hololens.md)] 2 règle les problèmes de positionnement de l'appareil grâce à une technologie de suivi oculaire.

## <a name="whats-next"></a>Étapes suivantes

[Structurer votre guide dans la page Plan](structure-guide.md)<br>
[Créer des étapes et ajouter du contenu 3D ou des supports 2D](create-steps-assign-media.md)<br>
[En savoir plus sur les raccourcis clavier](keyboard-shortcuts-pc-app.md)
