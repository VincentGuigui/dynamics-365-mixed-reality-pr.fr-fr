---
author: Mamaylya
description: Tout ce que vous devez savoir sur l'utilisation de l'application de création du PC pour créer un guide dans Dynamics 365 Guides (version préliminaire).
ms.author: mamaylya
ms.date: 07/09/2019
ms.service: crm-online
ms.topic: article
title: Utiliser l'application de création du PC pour créer un guide dans Dynamics 365 Guides (version préliminaire)
ms.reviewer: v-brycho
ms.openlocfilehash: 7c2beeb06cfb4a4ec658730259b9f92bc1bd5f2b
ms.sourcegitcommit: 8770ec043776563f3f9e87ee89f241c68015f576
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/31/2019
ms.locfileid: "1797449"
---
# <a name="use-the-pc-authoring-application-to-create-a-guide-in-dynamics-365-guides-preview"></a>Utiliser l'application de création du PC pour créer un guide dans Dynamics 365 Guides (version préliminaire)

[!INCLUDE [cc-beta-prerelease-disclaimer](../includes/cc-beta-prerelease-disclaimer.md)]
 
Utiliser l'application de création du PC pour créer un guide dans [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)] pour :

- Créer un guide

- Choisir une méthode d'ancrage

- Ajouter des tâches et des étapes

- Écrire des instructions pour les étapes

- Affectez différents types de ressources pour prendre en charge ces étapes. Parmi les ressources de prise en charge on trouve :

  - Composants 3D
  
  - Objets 3D, tels que les objets de la boîte à outils 3D (flèches et numéros, par exemple)
  
  - Support 2D (images et vidéos)

## <a name="install-open-and-sign-in-to-the-pc-application"></a>Installer, ouvrir, puis se connecter à l'application du PC
Utilisez ces instructions pour installer l'application (si elle n'a pas encore été installée) et pour vous connecter.

### <a name="install-the-app"></a>Installer l'application 
1.  Sur votre [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC, vérifiez que la dernière version de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 est installée (10.0.16299 ou ultérieure).

2.  Allez dans **Démarrer** ![Bouton Démarrer](media/windows-button.png "Bouton Démarrer") > **[!include[cc-microsoft](../includes/cc-microsoft.md)] Store** ![Bouton Store](media/store-button.png "Bouton Store"), puis recherchez [!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)].

3.  Sélectionnez **Installer** pour télécharger et installer [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

### <a name="sign-in-to-the-app"></a>Se connecter à l'application
1.  Ouvrez l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] à partir du menu **Démarrer** de votre PC. 

2.  Dans l'écran **Bienvenue dans Guides**, sélectionnez **Se connecter**.

    ![Bienvenue dans Guides](media/welcome-to-guides.PNG "Bienvenue dans Guides")
    
3.  Dans la boîte de dialogue **Connexion**, sélectionnez **Compte professionnel ou scolaire**, puis sélectionnez **Continuer**. 

4.  Dans l'écran **Connexion**, entrez le compte et le mot de passe utilisateur qui vous sont affectés par votre organisation. Si vous êtes administrateur, ce sont les informations d'identification que vous avez créées lorsque vous vous êtes inscrit pour la version préliminaire.

    ![Se connecter à l'application du PC](media/sign-in-pc.PNG "Se connecter à l'application du PC")
 
5.  Sélectionnez l'instance à utiliser s'il y en a plusieurs, puis sélectionnez **Continuer**.

    ![Choisir une instance](media/choose-instance-pc.PNG "Choisir une instance")

## <a name="create-a-new-guide"></a>Créer un nouveau guide

1.  Ouvrez l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

2.  Sélectionnez **Créer un nouveau guide**.

3.  Entrez un nom pour le guide. Si vous voulez créer plusieurs versions du guide, vous pouvez ajouter _v2, _v3, etc. dans le nom. 

## <a name="saving-how-changes-are-synced-between-the-pc-app-and-hololens-app"></a>Enregistrement : manière dont les modifications sont synchronisées entre l'application du PC et l'application HoloLens

L'application de création sur PC et l'application [!include[pn-hololens](../includes/pn-hololens.md)] sont connectées via le cloud, où les fichiers et les ressources [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] sont stockés. Lorsque vous créez des instructions, les modifications sont enregistrées sur le PC et sur [!include[pn-hololens](../includes/pn-hololens.md)]. Il est ainsi très facile de passer d'un appareil à un autre. L'enregistrement automatique permet de vérifier les nouvelles modifications toutes les 4 secondes. 

> [!IMPORTANT]
> Pour cette version préliminaire, il faut tenir compte de certains éléments lors de la synchronisation des appareils :<br><br>- Il est recommandé de toujours sélectionner **Actualiser** avant d'apporter des modifications lorsque vous changez d'appareil. Cela vous garantit de toujours disposer de la dernière version du fichier à partir de l'autre appareil.<br><br>- Si la même version d'un guide est ouverte sur le PC et sur [!include[pn-hololens](../includes/pn-hololens.md)], l'application l'actualise automatiquement lorsqu'elle détecte que vous avez apporté une modification dans l'autre application. Par exemple, si le guide est ouvert dans [!include[pn-hololens](../includes/pn-hololens.md)] et que vous ajoutez une étape dans l'application du PC, le guide est automatiquement actualisé dans [!include[pn-hololens](../includes/pn-hololens.md)]. Vous pouvez remarquer le processus d'actualisation.<br><br>- Lorsque vous ajoutez du texte au guide dans l'application du PC, la fonctionnalité de publication automatique s'active uniquement lorsque vous déplacez le curseur en dehors de la zone de texte. Si vous ajoutez du texte à une étape, conservez votre curseur dans la zone de texte, puis faites la modification dans [!include[pn-hololens](../includes/pn-hololens.md)], sinon vous perdrez le texte que vous avez entré sur le PC lors de la mise à jour avec les modifications provenant d'[!include[pn-hololens](../includes/pn-hololens.md)]. Ce problème sera traité dans notre prochaine version. 

## <a name="choose-an-anchoring-method"></a>Choisir une méthode d'ancrage 

Après avoir donné un nom à votre guide, la page **Plan** s'affiche, ainsi qu'une invite pour créer un point d'ancrage.

![Page Plan avec une invite de point d'ancrage](media/outline-page.PNG "Page Plan avec une invite de point d'ancrage")

- Sélectionnez **Définir votre point d'ancrage maintenant** pour afficher l'écran **Choisir une méthode d'ancrage**.

![Écran des méthodes d'ancrage](media/choose-anchor-method.PNG "Écran des méthodes d'ancrage")

### <a name="how-anchoring-works-and-types-of-anchors"></a>Fonctionnement de l'ancrage et types de points d'ancrage

L'ancrage est utilisé pour synchroniser vos instructions avec le monde réel. Lorsque vous ancrez votre guide, vos instructions coïncident avec l'espace auquel elles se rapportent et elles deviennent alors significatives. Le contenu est centré autour de ce point d'ancrage.

Il existe deux types de points d'ancrage :

- Avec un **point d'ancrage imprimé** (recommandé), vous pouvez associer un marqueur imprimé à un objet physique dans le monde réel. Après avoir créé le guide, pour ancrer le guide dans le monde réel, vous devez pointer du regard le marqueur à l'aide d'[!include[pn-hololens](../includes/pn-hololens.md)].

- Avec un **point d'ancrage numérique**, vous devez importer une représentation 3D (comme un modèle de CAO ou un modèle numérisé), puis placer cette représentation directement sur un objet physique dans le monde réel. Après avoir créé le guide, vous devez faire un mouvement pour l'ancrer dans le monde réel.

**Il est extrêmement important de garantir que l'ancrage est correct et aussi exact que possible.** Si l'ancrage n'est pas correct, vos instructions peuvent provoquer de la confusion chez l'opérateur et engendrer des dommages onéreux. Un opérateur risque par exemple de percer un trou au mauvais endroit ou d'assembler la mauvaise pièce. 

Les points d'ancrage imprimés fournissent plus de précision. Vous souhaitez ou vous devez peut-être utiliser un point d'ancrage numérique pour les raisons suivantes :

- Il n'est pas possible d'associer un point d'ancrage imprimé car il a été créé dans un emplacement différent de celui où se trouvent les pièces.

- Il n'est pas possible d'associer un point d'ancrage imprimé en raison de la présence de pièces mobiles.

- Vous ne pouvez pas garantir que l'emplacement du point d'ancrage imprimé est identique à chaque fois.

- La pièce est trop petite pour être attachée à un point d'ancrage imprimé.

### <a name="anchor-your-guide-by-using-a-printed-anchor"></a>Ancrer un guide à l'aide d'un point d'ancrage imprimé

L'utilisation d'un point d'ancrage imprimé implique trois étapes de base :

1.  L'impression d'un marqueur.

2.  L'association du marqueur à un objet physique dans le monde réel.

3.  Le pointage du marqueur du regard pour ancrer le guide.

Pour imprimer le marqueur :

1.  Dans l'écran **Choisir une méthode d'ancrage**, dans la section **Point d'ancrage imprimé**, choisissez **Sélectionner**.

    ![Écran des méthodes d'ancrage](media/choose-anchor-method.PNG "Écran des méthodes d'ancrage")

2.  Dans l'écran **Imprimer et placer le point d'ancrage**, sélectionnez **Enregistrer pour imprimer** pour enregistrer le fichier marker.pdf sur votre PC.

    ![Écran Imprimer et placer le point d'ancrage](media/print-anchor.PNG "Écran Imprimer et placer le point d'ancrage")

3.  Ouvrez le fichier marker.pdf sur votre PC dans Adobe Acrobat Reader.

4.  Dans le menu **Fichier**, sélectionnez **Imprimer**.

5.  Sous **Dimensionnement et gestion des pages**, sélectionnez l'option **Taille réelle**.

    ![Imprimer un marqueur](media/print-marker.PNG "Imprimer un marqueur")

4.  Imprimez la dernière page du document sur du papier mat (le papier brillant peut affecter la numérisation). 

5.  Après l'impression, assurez-vous que l'espacement du marqueur correspond aux mesures figurant dans l'illustration suivante :

    ![Espacement du marqueur](media/marker-spacing.PNG "Espacement du marqueur")
 
> [!NOTE]
> Si l'espacement du marqueur n'est pas de +/- 0,1 mm, dans la boîte de dialogue **Imprimer**, sélectionnez l'option **Échelle personnalisée**, puis modifiez le pourcentage pour compenser l'écart de taille. Par exemple, si vous imprimez le marqueur et que le résultat est de 49 mm, vous devez remplacer l'échelle par 100,4 % pour obtenir 49,196 mmm, qui doit se situer dans la tolérance.<br>Vous devrez peut-être ajuster le décalage du matériel dans les appareils Hololens 1 pour garantir le positionnement exact du contenu 3D. [En savoir plus sur l'ajustement du décalage du matériel](https://docs.microsoft.com/dynamics365/mixed-reality/guides/known-issues#uploading-new-3d-models-with-names-matching-any-of-the-pre-packaged-models-in-the-3d-toolkit-will-overwrite-the-files-in-the-3d-toolkit).

#### <a name="best-practices-for-printed-anchors"></a>Recommandations en matière de points d'ancrage imprimés

Gardez à l'esprit les points suivants lorsque vous utilisez des points d'ancrage imprimés :

- **Taille.** Assurez-vous que la taille du point d'ancrage imprimé est exacte dans ce document. Une taille de point d'ancrage incorrecte entraîne un mauvais alignement du guide. 

  - Certaines applications et imprimantes peuvent modifier la taille de l'image.
  
  - Si le point d'ancrage imprimé est supérieur à celui indiqué, [!include[pn-hololens](../includes/pn-hololens.md)] interprète la différence d'échelle en distance. Le point d'ancrage est alors identifié comme étant plus proche qu'il ne l'est réellement. 
  
  - L'impression à partir du fichier .pdf (comme décrit précédemment dans cette rubrique) est la meilleure façon de s'assurer que le point d'ancrage n'est pas redimensionné. 
  
- **Emplacement.** Placez le point d'ancrage sur l'objet physique dans un emplacement auquel il est facile d'accéder et à l'écart.

  - L'emplacement du point d'ancrage est idéalement central lors de la procédure.
  
  - Le contenu placé plus loin du point d'ancrage imprimé sera moins précis.
  
  - Placez le point d'ancrage à un emplacement où les opérateurs peuvent l'analyser de nouveau rapidement à des fins de réalignement à tout moment.
  
  - Prenez une photo ou une vidéo pour documenter le positionnement du point d'ancrage et l'ajouter aux instructions du guide et renforcer ainsi la confiance de l'opérateur. Pour prendre une photo ou une vidéo à partir de [!include[pn-hololens](../includes/pn-hololens.md)], voir [Capture de Réalité Mixte](https://docs.microsoft.com/windows/mixed-reality/mixed-reality-capture).
  
- **Angle de numérisation.** Placez-vous directement face au point d'ancrage, à la distance adéquate lorsque vous le pointez du regard. 

  - Une numérisation en angle peut entraîner un mauvais alignement.
  
  - La plage de numérisation idéale va de 60 à 80 cm.

#### <a name="how-hololens-establishes-anchor-position-scale-and-orientation"></a>Procédure d'HoloLens pour établir le positionnement, le dimensionnement et l'orientation du point d'ancrage

Lors de la numérisation, la caméra avant de [!include[pn-hololens](../includes/pn-hololens.md)] mesure les distances horizontales et verticales par rapport au point d'ancrage. Ces informations sont combinées aux valeurs réelles du point d'ancrage stockées en interne dans l'application (49,2 mm et 32,8 mm comme indiqué dans l'illustration précédente) afin d'établir précisément le positionnement, l'échelle et l'orientation dans l'espace du point d'ancrage.

### <a name="align-your-guide-by-using-a-digital-anchor"></a>Aligner un guide à l'aide d'un point d'ancrage numérique

Un point d'ancrage numérique implique deux étapes de base :

1.  L'utilisation de l'application de création sur PC, l'importation d'une représentation 3D d'un objet physique. Il peut s'agir d'un modèle de CAO utilisé pour créer l'objet physique ou d'un modèle analysé après la fabrication. Si vous n'avez pas de représentation 3D, vous pouvez ignorer cette étape et utiliser le modèle 3D prédéfini inclus dans [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

2.  En mode Créer [!include[pn-hololens](../includes/pn-hololens.md)], placez la représentation numérique 3D directement sur une partie physique.

Pour importer une représentation 3D : 

1.  Ouvrez l'application de création sur PC.

2.  Sélectionnez la commande **Importer** sur le côté droit de l'écran. 

3.  Dans la boîte de dialogue **Ouvrir**, sélectionnez la représentation 3D à utiliser, puis sélectionnez **Ouvrir**.

    La représentation 3D est alors ajoutée dans la section **Composants 3D** de la bibliothèque.
    
4.  Dans la bibliothèque, sélectionnez **Composants 3D**, puis faites glisser la représentation 3D vers la zone d'ancrage numérique. Si vous ne souhaitez pas sélectionner de point d'ancrage numérique à ce stade, sélectionnez **Suivant**. Le guide est alors créé avec un modèle 3D prédéfini, semblable à ceci :

    ![Point d'ancrage prédéfini](media/digital-anchor.PNG "Point d'ancrage prédéfini")
   
> [!NOTE]
> Il est donc recommandé de prendre une photo ou une vidéo de l'objet physique de base et de son emplacement, et de charger la photo ou la vidéo vers la zone de référence du **point d'ancrage numérique**. Pour prendre une photo ou une vidéo à partir de [!include[pn-hololens](../includes/pn-hololens.md)], voir [Capture de Réalité Mixte](https://docs.microsoft.com/windows/mixed-reality/mixed-reality-capture). Vous pouvez également personnaliser les instructions dans la zone **Instructions de l'opérateur** afin de fournir des indications plus spécifiques.

Lorsque vous basculez dans l'application de création [!include[pn-hololens](../includes/pn-hololens.md)], vous pouvez faire un mouvement pour insérer la représentation 3D directement sur l'objet physique dans votre environnement de travail.

#### <a name="best-practices-for-digital-anchors"></a>Recommandations en matière de points d'ancrage numériques

- **Taille.** Sélectionnez un point d'ancrage numérique qui ne soit ni trop petit ni trop grand. 

  - Ce sont les objets numériques de taille moyenne qui conviennent le mieux. Il est difficile de manipuler les hologrammes très petits ou très grands. 
  
  - Le taille d'une boîte à chaussures ou un peu plus grande est idéale.
  
- **Position.** Choisissez un point d'ancrage numérique le plus proche possible du centre de la tâche à effectuer. Plus vous placez le contenu numérique loin du point d'ancrage numérique, moins il sera précis.

- **Forme.** Sélectionnez un point d'ancrage numérique contenant une forme non-uniforme ou peu courante. Il est plus simple d'aligner des formes peu courantes.

  - Évitez les objets qui se reflètent. Cela peut entraîner un décalage à 180 degrés.
  
  - Choisissez des formes avec des bords et des coins clairement définis pour vous aider à orienter le contenu correctement.
  
- **Identifiable.** Sélectionnez un point d'ancrage numérique clairement défini, aisément reconnaissable, et facile à trouver pour l'opérateur. Assurez-vous qu'il puisse bien accéder à l'objet sans être gêné.

- **Direction d'alignement.** Alignez toujours le point d'ancrage numérique à votre objet physique à partir de la même direction. Cela augmente la répétabilité pour les opérateurs.

  - Si le placement est effectué à partir de perspectives différentes, cela peut entraîner un mauvais alignement.
  
  - Vous devez toujours le regarder à partir de plusieurs angles afin de garantir que le point d'ancrage numérique est bien aligné à l'objet physique.

### <a name="ensure-accuracy-of-anchors-alignment"></a>Garantir la précision des points d'ancrage (alignement)
Quelle que soit la méthode utilisée pour l'ancrage, ces facteurs supplémentaires peuvent impacter la précision de l'alignement et/ou la perception de l'utilisateur de l'alignement :

- **Paramètre de distance interpupillaire (DIP).** Le DIP est la distance entre le centre de chacune des pupilles de l'utilisateur. Il est primordial de définir un DIP approprié pour permettre à [!include[pn-hololens](../includes/pn-hololens.md)] d'adapter son affichage car les utilisateurs n'ont pas tous le même DIP. Un paramètre incorrect de DIP peut engendrer une mauvaise perception des hologrammes dans l'espace ainsi que leur instabilité. [Utiliser l'application d'étalonnage HoloLens pour étalonner votre DIP](https://docs.microsoft.com/en-us/windows/mixed-reality/calibration). 

- **Analyse préalable de l'environnement.** [!include[pn-hololens](../includes/pn-hololens.md)] analyse activement son environnement à la recherche de caractéristiques visibles pour créer des cartes. Cela se produit lorsque l'appareil est activé et qu'un utilisateur est connecté. Cette opération ne dépend pas du fait que vous soyez ou non dans le shell [!include[pn-hololens](../includes/pn-hololens.md)] ou les applications en cours d'exécution. [!include[pn-hololens](../includes/pn-hololens.md)] améliore constamment la précision de ces cartes grâce à l'analyse de l'environnement sous différents angles, qu'il enregistre ensuite sur l'appareil. Les hologrammes sont placés en fonction de ces cartes. Plus la carte est précise et plus la disposition des hologrammes est elle aussi précise.
Avant d'utiliser [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] sur un [!include[pn-hololens](../includes/pn-hololens.md)] qui ne maîtrise pas bien son environnement, l'utilisateur doit allumer [!include[pn-hololens](../includes/pn-hololens.md)], se connecter à l'appareil et parcourir l'espace où les instructions de l'hologramme sont ou seront placées. Cela peut être réalisé lorsque l'utilisateur se trouve dans le shell [!include[pn-hololens](../includes/pn-hololens.md)], mais nous lui recommandons de masquer le menu **Démarrer** pour afficher l'espace lorsqu'il se déplace. Le fait de se déplacer sans se presser et de regarder lentement vers le haut et le bas permet à l'appareil de détecter les caractéristiques et de créer des cartes précises. Cela s'appelle l'« analyse préalable » car elle est effectuée avant d'exécuter [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Vous n'avez à la faire qu'une seule fois pour chaque environnement car [!include[pn-hololens](../includes/pn-hololens.md)] enregistre les cartes qu'il a créées dans l'appareil et garde en mémoire les espaces qu'il a analysés.

   Les environnements très foncés ou très lumineux, ou ceux composés de surfaces très réfléchies (miroirs), ainsi que les surfaces sombres ou monochromes, risquent d'avoir un impact négatif sur la capacité d'[!include[pn-hololens](../includes/pn-hololens.md)] à identifier l'espace, ce qui aura un impact sur la position et la stabilité de l'hologramme.

- **Impact du positionnement d'un appareil.** [!include[pn-hololens](../includes/pn-hololens.md)] utilise une nouvelle technologie d'affichage pour projeter des images dans le champ de vision de l'utilisateur, ce qui crée des hologrammes. La façon dont l'utilisateur porte l'appareil sur la tête a un impact énorme sur la façon dont est perçue la position des hologrammes. 

   Pour bien comprendre cela, la meilleure façon est d'ajuster le positionnement de l'appareil tout en alignant les hologrammes à leurs homologues physiques dans [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Observez comment l'alignement des hologrammes est affecté lorsque vous déplacez l'appareil de gauche à droite, de haut en bas et si vous faites avancer ou reculer l'affichage. Les utilisateurs doivent toujours porter l'appareil de la même façon et comprendre que de petits décalages dans son positionnement sont à peine perceptibles, mais peuvent entraîner d'importants changements dans la façon dont sont perçus les emplacements des hologrammes.

## <a name="structure-your-guide-in-the-outline-page"></a>Structurer votre guide dans la page Plan

Une fois que vous avez choisi une méthode d'ancrage, la page **Plan** s'affiche. C'est dans cette page que vous allez créer la structure de votre guide en ajoutant autant de tâches et d'étapes que nécessaire. Les *tâches* sont des groupes d'étapes. Les *étapes* constituent une petite partie d'un travail qu'un opérateur doit effectuer pour réaliser une tâche. Les étapes constituent les éléments centraux dans [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

Lorsque vous ouvrez la page **Plan** pour la première fois, vous voyez qu'une tâche ou une étape est déjà créée pour vous. 

![Créer une tâche et une étape](media/task-name.PNG "Créer une tâche et une étape")
  
Commencez par entrer le nom de la tâche, puis tapez les instructions de la première étape dans la zone. Lorsque vous devez ajouter une nouvelle étape, sélectionnez **Ajouter une étape**. Lorsque vous êtes prêt à ajouter une autre tâche, sélectionnez **Ajoutez une tâche**. C'est tout simple !

En réalité, vous allez probablement créer la plupart de vos étapes à partir de la fiche étape (voir la section suivante), mais la page **Plan** offre une bonne manière de démarrer votre guide ou d'en obtenir une idée globale après avoir ajouté toutes les tâches et les étapes. Vous pouvez également restructurer votre guide à partir de la page **Plan** en faisant glisser les tâches et les étapes.

Outre les tâches et les étapes, la page **Plan** contient :

- Des instructions personnalisables par l'opérateur.

- Une étape spéciale appelée étape d'achèvement qui indique aux opérateurs quand ils ont atteint la fin du guide. L'étape d'achèvement inclut du texte par défaut que vous pouvez personnaliser comme vous le souhaitez.

  ![Page Plan](media/completion-step.PNG "Page Plan")
 
> [!NOTE]
> Lorsque vous commencez à travailler sur un guide, sélectionnez **Actualiser** pour vous assurer qu'il s'agit bien de la dernière version. 

### <a name="best-practices-for-the-outline-page"></a>Meilleures pratiques en matière de page Plan

- Pour fournir un contexte général, ajoutez une tâche de vue d'ensemble au début du guide. Cette tâche ne contient qu'une seule étape qui indique sur quoi porte le guide. C'est également un bon endroit pour répertorier toutes les tâches abordées dans le guide. 

- Ajoutez une étape au début et à la fin de chaque tâche pour indiquer à l'opérateur quand il doit commencer ou terminer une tâche, et pour qu'il sache qu'il a réussi une fois qu'il a terminé une tâche.

- N'ayez pas peur d'avoir beaucoup d'étapes, mais gardez bien à l'esprit qu'elles doivent être courtes pour de meilleurs résultats. 

- Pensez à ajouter des étapes indiquant des trucs et des astuces. 

- N'oubliez pas d'actualiser le guide quand vous passez du PC à [!include[pn-hololens](../includes/pn-hololens.md)], et assurez-vous de placer le curseur en dehors de la zone de texte quand vous rédigez des étapes pour activer l'enregistrement automatique. 

Voici la page **Plan** de l'exemple de guide qui montre à quoi ressemble une page **Plan** une fois terminée :

![Page Plan de l'exemple de guide une fois terminée](media/finished-outline-page.PNG "Page Plan de l'exemple de guide une fois terminée")
  
## <a name="create-steps-and-assign-assets-in-the-step-card-page"></a>Créer des étapes et affecter des ressources dans la page Fiche étape

Il est possible de créer des étapes dans la page **Plan**, mais vous allez probablement les créer plutôt dans la page Fiche étape WYSIWYG.  

Dans la page Fiche étape, vous devez rédiger des instructions et affecter des ressources de prise en charge aux étapes, comme du contenu ou du support 3D (image ou vidéo). 

### <a name="open-the-step-card-page-and-add-instructions"></a>Ouvrir la page Fiche étape et ajouter des instructions

1. Double-cliquez sur une étape de la page **Plan**. 

2. Entrez les instructions dans le rectangle noir au milieu de l'écran Fiche étape.

### <a name="add-3d-content-or-media-to-support-a-step"></a>Ajouter du contenu ou du support 3D pour prendre en charge une étape 

1. À droite de l'écran, sélectionnez une étiquette en regard du type d'élément à ajouter (**Composants 3D**, **Images**, **Vidéos**, ou **Boîte à outils 3D**).

2. Faites glisser l'objet vers la zone appropriée sous les instructions. Par exemple, pour ajouter une image ou une vidéo, faites glisser l'image ou la vidéo vers la zone **Image ou vidéo**. Pour déplacer un composant 3D ou un objet de la boîte à outils 3D, faites-le glisser vers l'une des zones **Composants 3D**. 

   ![Créer une étape avec la fiche étape](media/drag-object.PNG "Créer une étape avec la fiche étape")

   > [!NOTE]
   > L'ensemble des zones sous les instructions est appelé « emplacement. »
  
Lorsque vous consultez votre guide en mode Créer [!include[pn-hololens](../includes/pn-hololens.md)], vous pouvez voir toutes les ressources que vous avez associées aux étapes, et vous pouvez les placer à l'endroit qui convient dans le monde réel. Par exemple, si vous affectez un pointeur à une étape dans l'application du PC, vous devez aligner ce pointeur avec l'élément auquel il fait référence dans l'application de création [!include[pn-hololens](../includes/pn-hololens.md)]. Ce qui apparaît dans la page Fiche étape est très similaire à ce que vous voyez dans [!include[pn-hololens](../includes/pn-hololens.md)]. 

### <a name="best-practices-for-the-step-card-page"></a>Meilleures pratiques en matière de page Fiche étape

- Il est facile d'ajouter une étape à partir de la page Fiche étape. Il suffit de sélectionner **Ajouter une nouvelle étape** dans le coin inférieur droit de la page. Inutile de revenir à la page **Plan**. 

- N'ayez pas peur d'avoir beaucoup d'étapes, mais faites en sorte que le texte soit court. Le texte d'instruction est par exemple limité à 280 caractères par étape pour ne pas qu'il soit trop long.

- Essayez de coller à un type de ressource (image, vidéo, ou objet 3D) par étape. S'il y a trop de support ou de contenu 3D, cela peut assommer l'opérateur et être trop long à intégrer. Réfléchissez au type de contenu qui est le plus percutant.

- Rédigez le guide dans un langage courant pour des résultats optimaux. N'utilisez pas de jargon technique que personne ne comprend ou ne connaît.

- Utilisez des mots descriptifs comme « trouver », « rechercher », « obtenir », « prendre », « poser », « insérer », « attacher » et « supprimer ».

- Il est utile d'ajouter une étape **NOTE** à des fins de contrôles de la qualité. Ce type d'étape peut avoir lieu avant ou après une autre étape. Veillez juste à la placer au bon endroit.

- Ajoutez une étape **AVERTISSEMENT** pour les éléments susceptibles d'être dangereux ou de provoquer un problème qualitatif. Lorsque vous passez en mode Créer dans [!include[pn-hololens](../includes/pn-hololens.md)], vous pouvez appliquer un style pour renforcer l'avertissement.

- Le fait d'ajouter de petites étapes numérotées dans une étape peut parfois aider, mais n'ayez pas peur de créer des étapes distinctes pour faciliter la lecture.

- Lorsque vous avez terminé d'écrire une étape, vous devez déplacer le curseur en dehors de la zone de texte pour activer l'enregistrement automatique. 

### Importer vos propres objets 3D personnalisés afin de les ajouter à la liste des composants 3D<a name="import"></a>

Vous pouvez importer vos propres objets 3D personnalisés pour les ajouter à la liste des **Composants 3D**, puis affecter des composants à une étape. 

Pour importer vos propres objets 3D :

1.  Sélectionnez la commande **Importer** dans le coin supérieur droit de l'écran Fiche étape. 

2.  Localisez l'objet 3D à importer, puis sélectionnez **Ouvrir**.

    ![Importer un composant 3D personnalisé](media/import-object.PNG "Importer un composant 3D personnalisé")
    
> [!NOTE]
> [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] prend en charge les formats de fichier glTF, GLB et FBX. Vous pouvez utiliser une combinaison d'outils tiers et de [!include[pn-dyn-365-import-tool](../includes/pn-dyn-365-import-tool.md)] pour préparer vos modèles 3D (CAO) ou vous pouvez utiliser le service de conciergerie d'Import Tool pour que [!include[cc-microsoft](../includes/cc-microsoft.md)] convertisse et optimise les modèles à votre place. Pour plus d'informations sur Import Tool, consultez les rubriques suivantes :<br>- [Présentation de l'Import Tool](https://docs.microsoft.com/dynamics365/mixed-reality/import-tool/index)<br>- [Optimiser vos modèles 3D](https://docs.microsoft.com/dynamics365/mixed-reality/import-tool/optimize-models)<br>- [Meilleures pratiques pour les modèles 3D](https://docs.microsoft.com/dynamics365/mixed-reality/import-tool/best-practices)<br>- [Utiliser Dynamics 365 Import Tool](https://docs.microsoft.com/dynamics365/mixed-reality/import-tool/import-tool)

### <a name="add-3d-objects-from-the-3d-toolkit-to-support-your-steps"></a>Ajoutez des objets 3D provenant de la boîte à outils 3D pour prendre en charge les étapes

[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] est fourni avec une bibliothèque d'objets 3D prédéfinis incluse dans la boîte à outils 3D. Ces objets sont optimisés pour fonctionner parfaitement avec [!include[pn-hololens](../includes/pn-hololens.md)]. Utilisez les objets de la boîte à outils 3D comme n'importe quelle autre ressource pour prendre en charge les étapes et faire passer votre message. Le fait d'avoir une bibliothèque prête à l'emploi facilite les premiers pas si jamais votre société n'a pas de contenu 3D.

![Ajouter un objet à partir de la boîte à outils 3D](media/3d-toolkit.PNG "Ajouter un objet à partir de la boîte à outils 3D")
 
La boîte à outils 3D inclut des marqueurs, des flèches, des outils génériques, des mains, des nombres, des symboles, et des zones. Voici à quoi ressemblent les modèles :

![Liste des objets de la boîte à outils 3D](media/3D-toolkit-objects.PNG "Liste des objets de la boîte à outils 3D")

Vous devez ajouter un objet 3D à partir de la boîte à outils 3D dans la page Fiche étape, puis le placer en mode Créer [!include[pn-hololens](../includes/pn-hololens.md)]. Vous pouvez utiliser le même objet (instance) autant de fois que vous voulez dans une étape.

> [!NOTE]
> Vous pouvez également ajouter des objets 3D à partir de la boîte à outils 3D dans l'application de création [!include[pn-hololens](../includes/pn-hololens.md)]. Vous n'avez pas à les ajouter dans le PC si vous préférez le faire dans l'application de création [!include[pn-hololens](../includes/pn-hololens.md)].

Pour ajouter un objet à partir de la boîte à outils 3D :

1. Sélectionnez l'onglet **Boîte à outils 3D**.

2.  Sélectionnez la catégorie d'objets appropriée.
    
3.  Faites glisser l'objet souhaité de la liste vers une zone **Composants 3D** sous la fiche étape.

    ![Faire glisser un objet à partir de la boîte à outils 3D](media/3d-part.PNG "Faire glisser un objet à partir de la boîte à outils 3D")
 
### <a name="best-practices-for-3d-toolkit"></a>Meilleures pratiques en matière de boîte à outils 3D

- Utilisez des pointeurs pour transmettre des informations spatiales comme une position, une direction, et une translation.

- Utilisez la flèche pour que l'opérateur insère une pièce dans une partie fixe (resserrer un boulon à la main dans un trou taraudé, par exemple). 

- Utilisez l'une des postures manuelles pour que l'opérateur utilise sa main d'une manière spécifique pour orienter ou manipuler quelque chose. Il existe de nombreuses postures pour des interactions spécifiques, comme tirer, pousser, pincer, saisir, etc. Combinez ces standards avec des flèches et/ou des icônes pour ajouter une signification supplémentaire.

- Ajustez la taille du pointeur, mais jamais en dessous d'1 cm. Sinon, cela peut provoquer des erreurs.

## <a name="keyboard-shortcuts"></a>Raccourcis clavier

Vous pouvez utiliser tous les raccourcis clavier suivants dans l'application du PC :

|Raccourci clavier|Action|
|---------|-------------------------------------------------|
|Ctrl + S|Enregistrer le guide|
|Ctrl + C|Copier|
|Ctrl + V|Coller|
|Ctrl + X|Couper|
|Ctrl + A|Sélectionner tout|
|Ctrl + Z|Annuler la dernière modification du guide|
|Ctrl + Y|Rétablir la dernière modification du guide|
|Ctrl + F4|Fermer la fenêtre active|
|Win + Flèche vers le bas|Réduire la fenêtre active|
|Win + Flèche vers le haut|Agrandir la fenêtre active|

## <a name="whats-next"></a>Étapes suivantes
Après avoir créé votre guide, sélectionnez une méthode d'ancrage, puis créez les tâches et les étapes. Vous êtes alors prêt à [tester les éléments sur HoloLens dans le monde réel et à placer vos hologrammes](hololens-authoring.md).

> [!IMPORTANT]
> Lorsque vous passez du PC à [!include[pn-hololens](../includes/pn-hololens.md)], vous devez sélectionner **Actualiser** quand vous commencez à travailler sur un appareil pour être sûr qu'il s'agit bien de la dernière version du guide. 

Ne vous inquiétez pas si votre guide n'est pas complètement finalisé avant de passer à l'application de création [!include[pn-hololens](../includes/pn-hololens.md)]. Vous pourrez toujours revenir à l'application du PC pour modifier et restructurer votre guide. Il est en fait préférable d'effectuer un test rapide de la fluidité dans [!include[pn-hololens](../includes/pn-hololens.md)] et de revenir ensuite dans l'application du PC pour apporter des modifications avant de placer tous les hologrammes dans [!include[pn-hololens](../includes/pn-hololens.md)].

> [!TIP]
> Si vous créez plusieurs versions du même guide, vous pouvez utiliser la commande **Enregistrer une copie** du menu **Fichier**. C'est parfait pour les guides qui sont similaires mais qui ont des étapes différentes. Vous n'avez pas à tout recommencer à zéro !

### <a name="see-also"></a>Voir aussi

[Présentation de la création d'un guide](authoring-overview.md)<br>
[Tester votre guide et placer des hologrammes dans l'application HoloLens](hololens-authoring.md)<br>
 
