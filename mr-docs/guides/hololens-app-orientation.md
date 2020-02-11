---
author: Mamaylya
description: Orientez-vous avec l'application Microsoft Dynamics 365 Guides HoloLens et découvrez comment placer des hologrammes, ajouter des styles, etc.
ms.author: mamaylya
ms.date: 01/28/2020
ms.service: crm-online
ms.topic: article
title: Placer des hologrammes, ajouter des styles, etc. dans l'application Dynamics 365 Guides HoloLens
ms.reviewer: v-brycho
ms.openlocfilehash: 56405a6fa8940938acc9102d5fd9cf1d5466f9ea
ms.sourcegitcommit: 217d31bb34e67a6b8823d5ddac7ef8d56d054139
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/29/2020
ms.locfileid: "2995242"
---
# <a name="place-holograms-add-styles-and-more-in-the-dynamics-365-guides-hololens-app"></a>Placer des hologrammes, ajouter des styles, etc. dans l'application Dynamics 365 Guides HoloLens

Une fois le guide ancré dans l'application [!include[cc-microsoft](../includes/cc-microsoft.md)][!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)][!include[pn-hololens](../includes/pn-hololens.md)] en mode **Créer**, la page Fiche étape s'affiche. Elle rassemble tout ce que vous effectuez avec votre guide. Votre opérateur y a également accès lorsqu'il utilise le guide. La fiche étape suit l'opérateur afin qu'il puisse avoir les instructions nécessaires lorsqu'il se déplace dans sa zone de travail.

Vous et votre opérateur pouvez parcourir un guide en pointant du regard les flèches **Étape suivante** et **Précédent**. Vous pouvez également faire des mouvements comme cliquer dans l'air.

![Se déplacer dans un guide](media/navigate-example.PNG "Se déplacer dans un guide")

> [!TIP]
> Lorsque vous passez de l'application du PC à l'application HoloLens, sélectionnez **Actualiser** pour être sûr d'avoir la dernière version du guide.

## <a name="get-oriented-with-the-step-card-page"></a>Se repérer avec la page Fiche étape

L'illustration suivante montre les différents éléments de l'interface utilisateur (UI) de la page Fiche étape dans l'application [!include[pn-hololens](../includes/pn-hololens.md)].

![Boutons HoloLens](media/step-card-orientation-2.PNG "Boutons HoloLens")

Voici à quoi sert chaque bouton ou élément d'IU :

| Nombre | Éléments d'interface utilisateur | Nom | Objectif |
|---|---|---|---|
| 1 | ![Bouton Enregistrer](media/save-button.png "Bouton Enregistrer") | Enregistrer | Pour enregistrer le guide. |
| 2 | ![Bouton Annuler](media/undo-button.png "Bouton Annuler") | Annuler | Pour annuler la dernière modification. Vous pouvez annuler jusqu'à 100 modifications. |
| 3 | ![Bouton Rétablir](media/redo-button.png "Bouton Rétablir") | Rétablir | Pour rétablir la dernière modification. Vous pouvez rétablir jusqu'à 100 modifications. |
| 4 | ![Bouton Accueil](media/home-button.png "Bouton Accueil") | Accueil | Pour choisir un autre guide. |
| 5 | ![Bouton Mode suivi](media/follow-button.png "Bouton Mode suivi") | Mode suivi | Pour faire en sorte que la fiche étape vous suive ou pour la verrouiller à un emplacement.<p>[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] contient une fonctionnalité appelée mode **Suivi**. Partout où vous regardez, la fiche étape suit votre regard. Ainsi, vous n'avez pas besoin de chercher les instructions. Si vous désactivez le mode **Suivi**, la fiche étape reste où elle est. Vous pouvez déplacer la fiche étape où vous le souhaitez à tout moment. Il vous suffit simplement de la saisir en utilisant la barre de navigation.</p> |
| 6 | ![Bouton Ancrer](media/anchor-button.PNG "Bouton Ancrer") | Ancrer | Pour ancrer à nouveau (réaligner) votre guide.<p>Il arrive qu'[!include[pn-hololens](../includes/pn-hololens.md)] ne puisse plus se repérer. Pour résoudre ce problème, vous devez ancrer à nouveau le guide en pointant du regard le point d'ancrage imprimé (marqueur) ou le point d'ancrage numérique.</p> |
| 7 | ![Bouton Paramètres](media/settings-button.png "Bouton Paramètres") | Paramètres | Pour accéder au paramètre suivant :<ul><li>**Numéro de version**. Pour afficher la version que vous utilisez.</li></ul> |
| 8 | ![Bouton Profil](media/profile-button.png "Bouton Profil") | Profil | Pour se connecter et se déconnecter. |
| 9 | ![Progression d'étape](media/step-progress.png "Progression d'étape") | Progression d'étape | Pour indiquer où vous êtes dans l'étape. |
| 10 | ![Bouton Plan](media/outline-button.png "Bouton Plan") | Plan | Pour accéder à la page **Plan**.<p>Vous pouvez utiliser la page **Plan** pour parcourir rapidement votre guide.</p> |
| 11 | ![Nom de la tâche](media/task-name-table.PNG "Nom de la tâche") | Nom de la tâche | Pour afficher le nom de la tâche. |
| 12 | ![Progression de la tâche](media/task-progress.PNG "Progression de la tâche") | Progression de la tâche | Pour indiquer où vous êtes dans la tâche en cours. |
| 13 | ![Gemme](media/gem.png "Gemme") | Gemme | En faisant glisser la gemme, vous pouvez créer une ligne pointillée pour attirer l'attention sur une zone en particulier. |
| 14 | (Regardez la zone rectangulaire verte sur l'illustration.) | Corbeille | Pour connaître les objets 3D (modèles) qui peuvent être ajoutées pour l'étape. Parmi les objets 3D on trouve des objets 3D de la collection 3D et de tout modèle 3D (conception assistée par ordinateur \[CAO\] dessins) que vous importez pour imiter des objets 3D dans l'environnement réel de votre opérateur. |

> [!NOTE]
> Les modifications sont enregistrées automatiquement dans le cloud lorsque vous travaillez dans [!include[pn-hololens](../includes/pn-hololens.md)]. Vous devez simplement sélectionner **Actualiser** lorsque vous revenez sur l'ordinateur pour être sûr d'avoir la dernière version du guide.

## <a name="test-the-flow-of-your-guide"></a>Tester la fluidité du guide

Une fois que vous vous êtes repéré(e) dans [!include[pn-hololens](../includes/pn-hololens.md)], nous vous recommandons de parcourir le guide en entier en mode **Opérer** pour en tester la fluidité. Lorsque vous parcourez le guide, notez ce que vous souhaitez modifier dans l'application du PC. Vous pouvez par exemple avoir à déplacer certaines étapes, ajouter des tâches ou des opérations, ou ajouter des ressources de prise en charge. Il est généralement préférable d'effectuer ces modifications dans l'application du PC avant de commencer à placer des hologrammes, des attaches et d'appliquer des styles.

## <a name="add-a-dotted-line-to-link-a-step-card-to-a-focus-area"></a>Ajouter une ligne pointillée pour associer une fiche étape dans une zone ciblée

Vous pouvez ajouter des lignes pointillées (*attaches*) pour lier vos fiches étape aux zones où le travail est effectué. Ces lignes pointillées affichent l'opérateur sur lequel vous concentrer.

![Ligne pointillée holographique](media/tether-example.png "Ligne pointillée holographique")

Pour placer une ligne pointillée, procédez comme suit :

1. Appuyez longuement sur la gemme sous la fiche étape.

2. Faites-la glisser vers l'emplacement du monde réel que vous souhaitez.

    ![Placer une ligne pointillée](media/place-tether.PNG "Placer une ligne pointillée")

    > [!TIP]
    > Le placement n'est pas précis. Par conséquent, si vous connectez une ligne pointillée à un objet 3D à partir de la collection 3D, vous devez placer la ligne pointillée dans la zone générale, puis placer l'objet 3D (un numéro, par exemple) à la fin de la ligne pointillée.

## <a name="place-your-holograms"></a>Placer des hologrammes

À ce stade du processus, vous devez parcourir chaque étape de votre guide et placer toutes les ressources que vous avez associées à cette étape lorsque vous l'avez créée dans l'application du PC. Par exemple, si vous avez ajouté un objet 3D pour aider les opérateurs à prendre en charge une étape, vous devez placer ce composant par-dessus son homologue physique dans le monde réel. Si vous avez ajouté un objet 3D à partir de la collection 3D (une flèche ou un chiffre, par exemple), vous devez placer cet objet dans un emplacement approprié dans le monde réel pour attirer l'attention de l'utilisateur. Vous pouvez placer le même composant 3D ou le même objet 3D autant de fois que vous voulez.

### <a name="what-about-images-and-videos"></a>Et les images et les vidéos ?

Vous n'avez rien à faire pour placer une image ou une vidéo associée à une étape. Elles s'affichent automatiquement lorsque l'opérateur arrive à l'étape.

### <a name="place-a-3d-part"></a>Placer un objet 3D

1. Dans l'emplacement, cliquez dans l'air sur l'objet 3D que vous souhaitez placer.

2. Utilisez le pointage du regard et les mouvements pour placer l'hologramme de l'objet 3D par dessus son homologue physique dans le monde réel. Pour plus d'informations sur la manipulation des hologrammes à l'aide du regard et des mouvements, consultez [Manipuler des hologrammes](#manipulate) plus loin dans cette rubrique.

### <a name="place-a-3d-model-from-the-3d-toolkit"></a>Placer un modèle 3D à partir de la collection 3D

Vous pouvez placer un modèle 3D à partir de la collection 3D de la même manière que vous placez un objet 3D si vous avez ajouté ce modèle 3D à l'emplacement dans l'application du PC. Si vous n'avez pas ajouté le modèle 3D dans l'application du PC, vous pouvez le faire directement à partir de l'application [!include[pn-hololens](../includes/pn-hololens.md)].

1. Cliquez dans l'air sur une zone vide de l'emplacement.

2. Cliquez dans l'air sur une catégorie (une flèche ou une main, par exemple), puis sur le modèle 3D spécifique que vous souhaitez ajouter.

    ![Catégories](media/step-card-hands.png "Catégories")

    L'élément est alors ajouté à votre emplacement et vous pouvez ensuite le placer comme vous le feriez pour un objet 3D.

### <a name="best-practices-for-working-with-3d-content"></a>Pratiques recommandées pour utiliser le contenu 3D

- Assurez-vous que le contenu 3D ne gêne pas l'opérateur qui effectue la tâche.

- Gardez le champ de vision à l'esprit quand vous placez des ressources. Si vous placez un hologramme derrière quelqu'un, il sera très difficile à trouver.

- Utilisez le contenu 3D avec parcimonie et en ayant une objectif clair en tête. Trop de contenu risque de parasiter les instructions et les rendre plus difficiles à suivre.

- N'oubliez pas que vous pouvez lier une attache au contenu 3D pour le rendre facile à détecter.

## Manipuler des hologrammes<a name ="manipulate"></a>

Pour placer un modèle 3D à partir de l'un de vos emplacements, procédez comme suit :

1. Cliquez dans l'air sur un modèle 3D pour l'ajouter à votre monde réel. Il apparaît dans votre monde réel devant la fiche étape.

2. Levez la main pour indiquer que vous êtes prêt et pointez du regard le modèle pour en afficher l'aperçu. Les contrôles 3D apparaissent autour de la ressource et indiquent ainsi qu'elle est à l'état Aperçu.

    Si vous baissez la main, les contrôles 3D disparaissent. Ainsi, si vous regardez des hologrammes, les contrôles ne vous gênent pas. Vous devez regarder la pièce tout en levant la main pour indiquer que vous êtes prêt.

3. Avec les contrôles 3D visibles, cliquez longuement dans l'air n'importe où sur le contrôle de mouvement pour sélectionner le modèle. Déplacez le modèle vers l'emplacement souhaité, puis relâchez pour le placer.

Lorsque vous appuyez sur un objet 3D pour le déplacer, vous le sélectionnez en même temps. Une fois l'objet 3D sélectionné, lorsque vous baissez la main, les contrôles 3D restent jusqu'à ce que vous prévisualisiez ou sélectionniez un autre composant, ou que vous cliquez dans l'air n'importe où dans l'espace vide.

> [!TIP]
> Sur [!include[pn-hololens](../includes/pn-hololens.md)] 2, vous pouvez manipuler les hologrammes directement avec vos mains. Pour sélectionner un hologramme, placez votre main dessus pour afficher les contrôles 3D. Saisissez ensuite l'hologramme, déplacez-le et relâchez-le pour le placer. Lorsque vous avez terminé, cliquez dans l'air n'importe où dans un espace vide. Pour plus d'informations sur la manipulation des hologrammes dans HoloLens 2, voir [Mouvements pour la création et la navigation pour HoloLens 2](authoring-gestures-HL2.md).

#### <a name="rotate-a-hologram"></a>Faire pivoter un hologramme

Il est peu probable qu'une ressource soit orientée correctement lorsque vous la placez ou la déplacez pour la première fois. Vous pouvez utiliser les contrôles de rotation pour la faire pivoter comme vous le souhaitez.

Pour faire pivoter un hologramme, procédez comme suit.

- Cliquez longuement dans l'air sur un contrôle de rotation, puis effectuez l'une des opérations suivantes :

    - Utilisez la sphère haut/bas pour faire pivoter verticalement.

    - Utilisez la sphère gauche/droite pour faire pivoter horizontalement.

    - Utilisez la sphère main libre pour faire pivoter dans n'importe quelle direction.

    > [!TIP]
    > Vous pouvez pointer du regard n'importe quelle sphère pour voir dans quelle direction elle peut être tournée.

    Lorsque vous utilisez un contrôle de rotation, vous avez alors l'impression d'attraper physiquement la sphère et de tourner autour de l'objet, comme une roue.

Les illustrations suivantes montrent comment utiliser les différents contrôles de rotation :

**Rotation libre**

![Rotation libre](media/free-rotation.PNG "Rotation libre")

**Rotation gauche/droite**

![Rotation gauche/droite](media/left-right-rotation.PNG "Rotation gauche/droite")

**Rotation haut/bas**

![Rotation haut/bas](media/up-down-rotation.PNG "Rotation haut/bas")

> [!TIP]
> Sur [!include[pn-hololens](../includes/pn-hololens.md)] 2, vous pouvez utiliser les contrôles de rotation avec vos mains. Pincez l'un des contrôles de rotation disponibles avec votre main et faites pivoter l'hologramme comme vous le souhaitez. Pour plus d'informations sur la manipulation des hologrammes dans HoloLens 2, voir [Mouvements pour la création et la navigation pour HoloLens 2](authoring-gestures-HL2.md).

### <a name="change-the-size-of-a-hologram-after-you-place-it"></a>Modifier la taille d'un hologramme après l'avoir placé

- Cliquez longuement dans l'air sur le contrôle **Mettre à l'échelle un hologramme**, puis déplacez votre main vers le haut ou le bas.

    ![Contrôle Mettre à l'échelle un hologramme](media/scale-hologram.png "Contrôle Mettre à l'échelle un hologramme")

    > [!TIP]
    > Sur [!include[pn-hololens](../includes/pn-hololens.md)] 2, vous pouvez pincer le contrôle **Mettre à l'échelle un hologramme** avec votre main, puis déplacez l'hologramme vers le haut ou vers le bas pour en modifier la taille.

## <a name="add-styles-for-emphasis"></a>Ajouter des styles pour souligner l'importance

Vous pouvez utiliser les styles pour fournir des repères visuels pour donner plus d'importance. Par exemple, vous pouvez ajouter le style **Avertissement** pour indiquer de faire preuve de prudence ou le style **Mise en garde** pour garantir qu'un opérateur ne fasse rien qui pourrait causer un dommage. Une fois les opérateurs habitués au langage visuel fourni par les styles, ils verront leur processus d'apprentissage s'accélérer.

> [!NOTE]
> Vous ne pouvez pas pour l'instant ajouter de styles à partir de l'application du PC. Ils se trouvent uniquement dans [!include[pn-hololens](../includes/pn-hololens.md)].

Pour ajouter un style, procédez comme suit :

1. Cliquez dans l'air sur un hologramme que vous avez déjà placé dans le monde réel pour le sélectionner.

2. Cliquez dans l'air sur le bouton **Modifier l'hologramme** (crayon).

    ![Bouton Modifier l'hologramme](media/edit-hologram.png "Bouton Modifier l'hologramme")

3. Cliquez dans l'air sur **Styles**.

    ![Bouton Styles](media/edit-styles.png "Bouton Styles")

    > [!TIP]
    > Sur [!include[pn-hololens](../includes/pn-hololens.md)] 2, vous pouvez atteindre et sélectionner les **Styles** et les éléments de menu suivants directement avec votre doigt. Pour plus d'informations sur la manipulation des hologrammes dans HoloLens 2, voir [Mouvements pour la création et la navigation pour HoloLens 2](authoring-gestures-HL2.md).

4. Sélectionnez le style à utiliser.

    ![Liste des styles](media/styles.png "Liste des styles")

Voici la liste des styles inclus dans [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et des informations sur leur utilisation :

| Style | Objectif | Comment cela apparaît pour l'opérateur |
|---|---|---|
| Original | Restauration à l'apparence d'origine. | Apparence par défaut |
| Choisir | Indique à l'opérateur de choisir un élément. | Plan |
| Placer | Indique à l'opérateur où placer un élément. | Trait en pointillé |
| Transparent 1 | Affiche un élément sans masquer ce que voit l'opérateur. | Transparent à 50 % |
| Transparent 2 | Superpose un élément sur un autre pour que l'opérateur puisse afficher deux couches. | Transparent à 75 % |
| Avertissement | Avertit d'un problème de sécurité ou de qualité. | Rayé jaune et noir |
| Mise en garde | Indique des zones ou des éléments à éviter. | Voyant rouge clignotant |
| Rayon X | Indique des choses qui se produisent à l'intérieur d'un élément. | Affiche une impulsion par son biais |
| Métal | Donne une finition réaliste en métal à un objet. | Métallique |

![Tous les styles](media/all-styles.PNG "Tous les styles")

### <a name="best-practices-for-styles"></a>Meilleures pratiques pour les styles

- Appliquez des styles pour renforcer les actions.

- Appliquez des styles uniquement pour l'objectif visé. Lorsque les opérateurs apprennent le langage visuel des styles, ils savent qu'un style particulier veut dire une certaine chose, ce qui accélère le processus d'apprentissage.

## <a name="duplicate-a-3d-model-to-use-it-for-similar-items"></a>Dupliquer un modèle 3D pour l'utiliser pour des éléments similaires

Vous avez parfois besoin de plusieurs copies des mêmes modèles 3D pour indiquer des éléments similaires dans la zone de travail. Plutôt que d'ajouter de nouvelles instances d'un modèle 3D à partir de l'emplacement de la ressource et de devoir définir la position et le style à chaque fois, vous pouvez gagner du temps en dupliquant le modèle 3D. La duplication conserve les paramètres de style et de rotation d'origine.

Pour dupliquer un modèle, procédez comme suit.

1. Cliquez dans l'air sur un hologramme que vous avez déjà placé dans le monde réel pour le sélectionner.

2. Cliquez dans l'air sur le bouton **Modifier l'hologramme** (crayon).

    ![Bouton Modifier l'hologramme](media/edit-hologram.png "Bouton Modifier l'hologramme")

3. Sélectionnez **Dupliquer**.

    ![Bouton Dupliquer](media/edit-duplicate.png "Bouton Dupliquer")

    > [!TIP]
    > Sur [!include[pn-hololens](../includes/pn-hololens.md)] 2, vous pouvez atteindre et sélectionner **Dupliquer** directement avec votre doigt. Pour plus d'informations sur la manipulation des hologrammes dans HoloLens 2, voir [Mouvements pour la création et la navigation pour HoloLens 2](authoring-gestures-HL2.md).

## <a name="turn-off-animations"></a>Désactiver les animations

Si vous utilisez des modèles 3D animés dans le guide, vous pouvez désactiver les animations si vous envisagez de les afficher dans une étape et de ne pas les afficher dans un autre. Cette option est disponible dans le menu **Modifier** lorsque vous sélectionnez le modèle.

![Option d'animation désactivée](media/edit-animations.png "Option d'animation désactivée")

Vous pouvez également utiliser cette option lorsque vous appliquez des modèles animés dans l'espace. Arrêtez l'animation, placez le modèle, puis activez de nouveau l'animation. Ainsi l'animation ne vous empêchera pas de placer le modèle.
