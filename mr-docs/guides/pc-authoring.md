---
author: Mamaylya
description: Tout ce que vous devez savoir sur l'utilisation de l'application de création du PC pour créer un guide dans Dynamics 365 Guides.
ms.author: mamaylya
ms.date: 10/01/2019
ms.service: crm-online
ms.topic: article
title: Utiliser l'application de création du PC pour créer un guide dans Dynamics 365 Guides
ms.reviewer: v-brycho
ms.openlocfilehash: bda3d8b4ca2f38a1212c8233b5cc123ea050681c
ms.sourcegitcommit: 40992f99110d02b2120a930679c5f681b0a6227a
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/25/2019
ms.locfileid: "2050010"
---
# <a name="use-the-pc-authoring-application-to-create-a-guide-in-dynamics-365-guides"></a>Utiliser l'application de création du PC pour créer un guide dans Dynamics 365 Guides

[Visionner une vidéo sur la création sur PC](https://aka.ms/pcauthor)

Utiliser l'application de création du PC pour créer un guide dans [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] pour :

- Créer un guide

- Choisir une méthode d'ancrage

- Ajouter des tâches et des étapes

- Écrire des instructions pour les étapes

- Affectez différents types de ressources pour prendre en charge ces étapes. Parmi les ressources de prise en charge on trouve :

  - Composants 3D
  
  - Objets 3D, tels que les objets de la boîte à outils 3D (flèches et numéros, par exemple)
  
  - Support 2D (images et vidéos)
  
![Création PC](media/pc-authoring.PNG "Création PC")

## <a name="install-open-and-sign-in-to-the-pc-application"></a>Installer, ouvrir, puis se connecter à l'application du PC
Utilisez ces instructions pour installer l'application (si elle n'a pas encore été installée) et pour vous connecter.

### <a name="install-the-app"></a>Installer l'application 
1.  Sur votre [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC, vérifiez que la dernière version de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 est installée (10.0.16299 ou ultérieure).

2.  Allez dans **Démarrer** ![Bouton Démarrer](media/windows-button.png "Bouton Démarrer") > **[!include[cc-microsoft](../includes/cc-microsoft.md)] Store** ![Bouton Store](media/store-button.png "Bouton Store"), puis recherchez [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

3.  Sélectionnez **Installer** pour télécharger et installer [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

### <a name="sign-in-to-the-app"></a>Se connecter à l'application
1.  Ouvrez l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] à partir du menu **Démarrer** de votre PC. 

2.  Dans l'écran **Bienvenue dans Guides**, sélectionnez **Se connecter**.

    ![Bienvenue dans Guides](media/welcome.PNG "Bienvenue dans Guides")
    
3.  Dans la boîte de dialogue **Connexion**, sélectionnez **Compte professionnel ou scolaire**, puis sélectionnez **Continuer**. 

4.  Dans l'écran **Connexion**, entrez le compte et le mot de passe utilisateur qui vous sont affectés par votre organisation. 

    ![Se connecter à l'application du PC](media/sign-in-pc.PNG "Se connecter à l'application du PC")
 
5.  Sélectionnez l'instance à utiliser s'il y en a plusieurs, puis sélectionnez **Continuer**.

    ![Choisir une instance](media/choose-instance-pc.PNG "Choisir une instance")

## <a name="create-a-new-guide"></a>Créer un nouveau guide

1.  Ouvrez l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

2.  Sélectionnez **Créer un nouveau guide**.

     ![Créer un nouveau guide](media/create-guide.PNG "Créer un nouveau guide")

3.  Entrez un nom pour le guide. Si vous voulez créer plusieurs versions du guide, vous pouvez ajouter _v2, _v3, etc. dans le nom. 

     ![Nommer le guide](media/name-guide.PNG "Nommer le guide")

## <a name="saving-how-changes-are-synced-between-the-pc-app-and-hololens-app"></a>Enregistrement : manière dont les modifications sont synchronisées entre l'application du PC et l'application HoloLens

L'application de création sur PC et l'application [!include[pn-hololens](../includes/pn-hololens.md)] sont connectées via le cloud, où les fichiers et les ressources [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] sont stockés. Lorsque vous créez des instructions, les modifications sont enregistrées sur le PC et sur [!include[pn-hololens](../includes/pn-hololens.md)]. Il est ainsi très facile de passer d'un appareil à un autre. L'enregistrement automatique permet de vérifier les nouvelles modifications toutes les 4 secondes. Vous devez être en ligne pour utiliser [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]

> [!NOTE]
> Lorsque vous basculez d'un périphérique à l'autre, il est préférable de fermer le guide pour vous assurer que vous ne perdrez pas votre travail. 

## <a name="choose-an-anchoring-method-for-your-guide"></a>Choisir une méthode d'ancrage pour votre guide.

L'étape suivante consiste à choisir une méthode d'ancrage pour votre guide. L'ancrage est la manière dont vous attachez vos hologrammes à votre environnement en monde réel. [En savoir plus sur l'ancrage et le mode de création d'un point d'ancrage](anchor.md).

## <a name="structure-your-guide-in-the-outline-page"></a>Structurer votre guide dans la page Plan

Une fois que vous avez choisi une méthode d'ancrage, la page **Plan** s'affiche. C'est dans cette page que vous allez créer la structure de votre guide en ajoutant autant de tâches et d'étapes que nécessaire. Les *tâches* sont des groupes d'étapes. Les *étapes* constituent une petite partie d'un travail qu'un opérateur doit effectuer pour réaliser une tâche. Les étapes constituent les éléments centraux dans [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

Lorsque vous ouvrez la page **Plan** pour la première fois, vous voyez qu'une tâche ou une étape est déjà créée pour vous. 

![Créer une tâche et une étape](media/create-task-2.PNG "Créer une tâche et une étape")
  
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

Voici l'exemple d'une page **Plan** remplie :

![Page Plan remplie à partir du guide Câblage de pylône](media/finished-outline-page.PNG "Page Plan remplie à partir du guide Câblage de pylône")
  
## <a name="create-steps-and-assign-assets-in-the-step-card-page"></a>Créer des étapes et affecter des ressources dans la page Fiche étape

Il est possible de créer des étapes dans la page **Plan**, mais vous allez probablement les créer plutôt dans la page Fiche étape WYSIWYG. Les instructions que vous créez sur la page Fiche étape correspond à ce que l'opérateur voit dans [!include[pn-hololens](../includes/pn-hololens.md)].

Dans la page Fiche étape, vous devez rédiger des instructions et affecter des ressources de prise en charge aux étapes, comme du contenu ou du support 3D (image ou vidéo). 

### <a name="open-the-step-card-page-and-add-instructions"></a>Ouvrir la page Fiche étape et ajouter des instructions

1. Cliquez sur chaque étape de la page **Contour**, ou sélectionnez **Étape** dans la navigation gauche. 

   ![Commande d'étape dans le volet de navigation gauche](media/left-nav-step.PNG "Commande d'étape dans le volet de navigation gauche")

2. Entrez les instructions dans le rectangle au milieu de l'écran Fiche étape.

### <a name="add-3d-content-or-media-to-support-a-step"></a>Ajouter du contenu ou du support 3D pour prendre en charge une étape 

1. À droite de l'écran, sélectionnez une étiquette en regard du type d'élément à ajouter (**Composants 3D**, **Images**, **Vidéos**, ou **Boîte à outils 3D**).

2. Faites glisser l'objet vers la zone appropriée sous les instructions. Par exemple, pour ajouter une image ou une vidéo, faites glisser l'image ou la vidéo vers la zone **Image ou vidéo**. Pour déplacer un composant 3D ou un objet de la boîte à outils 3D, faites-le glisser vers l'une des zones **Composants 3D**. 

   ![Créer une étape avec la fiche étape](media/drag-object.PNG "Créer une étape avec la fiche étape")

   > [!NOTE]
   > L'ensemble des zones sous les instructions est appelé « emplacement. »
  
Lorsque vous consultez votre guide en mode Créer [!include[pn-hololens](../includes/pn-hololens.md)], vous pouvez voir toutes les ressources que vous avez associées aux étapes, et vous pouvez les placer à l'endroit qui convient dans le monde réel. Par exemple, si vous affectez un pointeur à une étape dans l'application du PC, vous devez aligner ce pointeur avec l'élément auquel il fait référence dans l'application de création [!include[pn-hololens](../includes/pn-hololens.md)] dans le monde réel. Ce qui apparaît dans la page Fiche étape est très similaire à ce que vous voyez dans [!include[pn-hololens](../includes/pn-hololens.md)]. 

### <a name="best-practices-for-the-step-card-page"></a>Meilleures pratiques en matière de page Fiche étape

- Il est facile d'ajouter une étape à partir de la page Fiche étape. Il suffit de sélectionner **Ajouter une nouvelle étape** dans le coin supérieur droit de la page. Inutile de revenir à la page **Plan**. 

- N'ayez pas peur d'avoir beaucoup d'étapes, mais faites en sorte que le texte soit court. Le texte d'instruction est par exemple limité à 280 caractères par étape pour ne pas qu'il soit trop long.

- Essayez de coller à un type de ressource (image, vidéo, ou objet 3D) par étape. S'il y a trop de support ou de contenu 3D, cela peut assommer l'opérateur et être trop long à intégrer. Réfléchissez au type de contenu qui est le plus percutant.

- Rédigez le guide dans un langage courant pour des résultats optimaux. N'utilisez pas de jargon technique que personne ne comprend ou ne connaît.

- Utilisez des mots descriptifs comme « trouver », « rechercher », « obtenir », « prendre », « poser », « insérer », « attacher » et « supprimer ».

- Il est utile d'ajouter une étape **NOTE** à des fins de contrôles de la qualité. Ce type d'étape peut avoir lieu avant ou après une autre étape. Veillez juste à la placer au bon endroit.

- Ajoutez une étape **AVERTISSEMENT** pour les éléments susceptibles d'être dangereux ou de provoquer un problème qualitatif. Lorsque vous passez en mode Créer dans [!include[pn-hololens](../includes/pn-hololens.md)], vous pouvez appliquer un style pour renforcer l'avertissement.

- Le fait d'ajouter de petites étapes numérotées dans une étape peut parfois aider, mais n'ayez pas peur de créer des étapes distinctes pour faciliter la lecture.

- Lorsque vous avez terminé d'écrire une étape, vous devez déplacer le curseur en dehors de la zone de texte pour activer l'enregistrement automatique. 

### Importez vos propres objets 3D personnalisés<a name="import"></a>

Vous pouvez importer vos propres objets 3D personnalisés pour les ajouter à la bibliothèque des **Composants 3D**, puis affecter des composants à une étape. 

Pour importer vos propres objets 3D :

1.  Sélectionnez la commande **Importer** dans le coin supérieur droit de l'écran Fiche étape. 

2.  Localisez l'objet 3D à importer, puis sélectionnez **Ouvrir**.

    ![Importer un composant 3D personnalisé](media/import-object.PNG "Importer un composant 3D personnalisé")
    
> [!NOTE]
> [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] prend en charge les formats de fichier glTF, GLB et FBX. Vous pouvez utiliser une combinaison d'outils tiers et de [!include[pn-dyn-365-import-tool](../includes/pn-dyn-365-import-tool.md)] pour préparer vos modèles 3D (CAO) ou vous pouvez utiliser le service de conciergerie d'Import Tool pour que [!include[cc-microsoft](../includes/cc-microsoft.md)] convertisse et optimise les modèles à votre place. Pour plus d'informations sur Import Tool, consultez les rubriques suivantes :<br>- [Présentation de l'Import Tool](https://docs.microsoft.com/dynamics365/mixed-reality/import-tool/index)<br>- [Optimiser vos modèles 3D](https://docs.microsoft.com/dynamics365/mixed-reality/import-tool/optimize-models)<br>- [Meilleures pratiques pour les modèles 3D](https://docs.microsoft.com/dynamics365/mixed-reality/import-tool/best-practices)<br>- [Utiliser Dynamics 365 Import Tool](https://docs.microsoft.com/dynamics365/mixed-reality/import-tool/import-tool)

### <a name="add-3d-objects-from-the-3d-toolkit-to-support-your-steps"></a>Ajoutez des objets 3D provenant de la boîte à outils 3D pour prendre en charge les étapes

[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] est fourni avec une bibliothèque d'objets 3D prédéfinis incluse dans la boîte à outils 3D. Ces objets sont optimisés pour fonctionner parfaitement avec [!include[pn-hololens](../includes/pn-hololens.md)]. Utilisez les objets de la boîte à outils 3D comme n'importe quelle autre ressource pour prendre en charge les étapes et faire passer votre message. Le fait d'avoir une bibliothèque prête à l'emploi facilite les premiers pas si jamais votre société n'a pas de contenu 3D.
 
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
|CTRL + Gauche, Droite|Accéder à la tâche ou à l'étape précédente ou suivante, en fonction de ce qui est sélectionné|
|CTRL + Flèche vers le haut ou Flèche vers le bas|Accéder à la tâche ou à l'étape ci-dessus ou ci-dessous, en fonction de ce qui est sélectionné|
|Win + Flèche vers le bas|Réduire la fenêtre active|
|Win + Flèche vers le haut|Agrandir la fenêtre active|

> [!NOTE]
> Microsoft continuera à prendre en charge les lecteurs d’écran, le contraste élevé et la convivialité du clavier.

## <a name="whats-next"></a>Étapes suivantes
Après avoir créé votre guide sur le PC, sélectionnez une méthode d'ancrage, puis créez les tâches et les étapes. Vous êtes alors prêt à [tester les éléments sur HoloLens dans le monde réel et à placer vos hologrammes](hololens-authoring.md).

> [!IMPORTANT]
> Lorsque vous passez du PC à [!include[pn-hololens](../includes/pn-hololens.md)], vous devez sélectionner **Actualiser** quand vous commencez à travailler sur un appareil pour être sûr qu'il s'agit bien de la dernière version du guide. 

Ne vous inquiétez pas si votre guide n'est pas complètement finalisé avant de passer à l'application de création [!include[pn-hololens](../includes/pn-hololens.md)]. Vous pourrez toujours revenir à l'application du PC pour modifier et restructurer votre guide. Il est en fait préférable d'effectuer un test rapide de la fluidité dans [!include[pn-hololens](../includes/pn-hololens.md)] et de revenir ensuite dans l'application du PC pour apporter des modifications avant de placer tous les hologrammes dans [!include[pn-hololens](../includes/pn-hololens.md)].

> [!TIP]
> Si vous créez plusieurs versions du même guide, vous pouvez utiliser la commande **Enregistrer une copie** du menu **Fichier**. C'est parfait pour les guides qui sont similaires mais qui ont des étapes différentes. Vous n'avez pas à tout recommencer à zéro !

### <a name="see-also"></a>Voir aussi

[Présentation de la création d'un guide](authoring-overview.md)<br>
[Choisir une méthode d'ancrage pour votre guide.](anchor.md)<br>
[Créer dans l'application HoloLens](hololens-authoring.md)<br>
 
