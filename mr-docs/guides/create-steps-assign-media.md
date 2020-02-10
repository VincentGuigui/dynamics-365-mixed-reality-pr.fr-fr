---
author: Mamaylya
description: Créez des étapes et ajoutez du contenu ou du support 3D pour prendre en charge ces étapes dans l'application du PC Microsoft Dynamics 365 Guides.
ms.author: mamaylya
ms.date: 01/28/2020
ms.service: crm-online
ms.topic: article
title: Créer des étapes et ajouter des modèles 3D ou des supports 3D dans l'application du PC Dynamics 365 Guides
ms.reviewer: v-brycho
ms.openlocfilehash: 37d5b7696756505b3a2f1b2a000318d4bddd26fd
ms.sourcegitcommit: 217d31bb34e67a6b8823d5ddac7ef8d56d054139
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/29/2020
ms.locfileid: "2995253"
---
# <a name="create-steps-and-add-3d-models-or-2d-media-in-the-dynamics-365-guides-pc-app"></a>Créer des étapes et ajouter des modèles 3D ou des supports 2D dans l'application du PC Dynamics 365 Guides

Les étapes constituent les éléments centraux de la création d'un guide dans [!include[cc-microsoft](../includes/cc-microsoft.md)][!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Une fois que vous avez créé la [structure de votre guide sur la page **Plan**](structure-guide.md), vous devez utiliser l'éditeur d'étape pour ajouter des instructions et des modèles ou des supports 3D pour prendre en charge ces étapes. Les instructions que vous créez dans l'éditeur d'étape WYSIWYG correspondent à ce que l'opérateur verra sur la fiche étape sur [!include[pn-hololens](../includes/pn-hololens.md)]. L'illustration suivante montre l'éditeur d'étape dans l'application du PC et la fiche étape que l'utilisateur voit sur [!include[pn-hololens](../includes/pn-hololens.md)].

![Éditeur d'étape et fiche étape](media/step-editor-step-card.PNG "Éditeur d'étape et fiche étape")

## <a name="open-the-step-editor-and-add-instructions"></a>Ouvrir la page Éditeur d'étape et ajouter des instructions

Vous devez ouvrir la page **Éditeur d'étape** à partir de la page **Plan**.

1. Sélectionnez chaque étape de la page **Plan** ou sélectionnez **Étape** dans la navigation gauche.

    ![Étape de la page Plan et de la commande d'étape dans le volet gauche de navigation](media/left-nav-step.PNG "Étape de la page Plan et de la commande d'étape dans le volet gauche de navigation")

2. Entrez les instructions dans le rectangle bleu au milieu de la page.

    ![Éditeur d'étape](media/step-editor.PNG "Éditeur d'étape")

3. Lorsque vous êtes prêt à ajouter une autre étape, sélectionnez **Ajouter une nouvelle étape** dans le coin supérieur droit de la page.

### <a name="best-practices-for-instructional-text-and-supporting-content"></a>Meilleures pratiques en matière d'instructions et de contenu de prise en charge

- N'ayez pas peur d'avoir beaucoup d'étapes, mais faites en sorte que le texte soit court. Le texte d'instruction doit par exemple se limiter à 280 caractères par étape.

- Pour optimiser les résultats, rédigez le guide dans un langage courant. Évitez le jargon technique.

- Utilisez des mots descriptifs comme *trouver*, *rechercher*, *obtenir*, *accéder à*, *prendre*, *poser*, *insérer*, *attacher* et *supprimer*.

- Il est utile d'ajouter une étape **NOTE** à des fins de contrôles de la qualité. Ce type d'étape peut avoir lieu avant ou après une autre étape. Veillez juste à la placer au bon endroit.

- Ajoutez une étape **AVERTISSEMENT** pour les éléments susceptibles d'être dangereux ou de provoquer un problème qualitatif. Pour renforcer l'avertissement, vous pouvez [ajouter un style dans l'application HoloLens](create-steps-assign-media.md).

- De petites étapes dans une étape peuvent parfois aider, mais n'ayez pas peur de créer des étapes distinctes pour faciliter la lecture.

- Lorsque vous avez terminé d'écrire une étape, vous devez déplacer le curseur en dehors de la zone de texte pour activer l'enregistrement automatique.

- Essayez de vous limiter à un type de contenu par étape. S'il y a trop de support ou de contenu 3D, cela peut assommer l'opérateur et être trop long à intégrer. Réfléchissez au type de contenu qui est le plus percutant.

## <a name="go-to-other-pages-from-the-step-editor-page"></a>Accéder à d'autres pages de la page Éditeur d'étape

Utilisez les boutons du volet de navigation sur le côté gauche de la page **Éditeur d'étape** pour accéder à d'autres pages de l'application du PC. Le tableau suivant décrit les boutons du volet de navigation.

| Bouton | Nom | Action |
|---|---|---|
| ![Bouton Ouvrir la navigation](media/open-navigation-button.png "Bouton Ouvrir la navigation") | Ouvrir la navigation | Développez le volet de navigation pour qu'il comprenne une description de chaque bouton. |
| ![Bouton Accueil](media/home-button-pc-app.png "Bouton Accueil") | Accueil | Accédez à la page d'**Accueil**, où vous pourrez créer un guide ou en ouvrir un existant. |
| ![Bouton Analyser](media/analyze-button-pc-app.png "Bouton Analyser") | Analyser | Accédez à la page **Analyser**, où vous pourrez configurer les états Microsoft Power BI (Guides Analytics) pour analyser vos guides. |
| ![Bouton Ancrer](media/anchor-button-pc-app.png "Bouton Ancrer")| Ancrer | Ouvrez l'assistant **Choisir une méthode d'ancrage**, où vous pourrez sélectionner différentes méthodes d'ancrage pour votre guide ou modifier le type de méthode d'ancrage. |
| ![Bouton Plan](media/outline-button-pc-app.png "Bouton Plan")| Plan | Accédez à la page **Plan**, où vous pourrez structurer ou restructurer votre guide. Vous pourrez également ouvrir l'assistant **Choisir une méthode d'ancrage** de cette page. |

## <a name="what-can-you-add-to-help-operators-with-a-step"></a>Que pouvez-vous ajouter pour aider les opérateurs dans une étape ?

Vous pouvez ajouter du contenu 3D, des médias ou des liens vers des sites Web pour aider les opérateurs à terminer une étape. Le tableau suivant décrit les différents types de contenu que vous pouvez ajouter.

| Type de contenu | Description | Exemple |
|---|---|---|
| Modèles 3D à partir de la collection 3D | Modèles 3D prêts à l'emploi, tels que des chiffres, des flèches et des mains | Une flèche holographique qui aide les opérateurs à trouver une zone de mise au point |
| Objet 3D | Des modèles 3D spécifiques à votre entreprise | Un hologramme d'objet 3D qui aide les opérateurs à trouver un objet 3D dans le monde réel |
| Image | Un fichier image 2D | Un diagramme qui aide les opérateurs à effectuer une étape complexe |
| Vidéo | Un fichier vidéo | Une courte vidéo qui aide les opérateurs à effectuer une étape complexe |
| Lien du site Web | Un lien vers un site Web externe | Un lien vers un système d'inventaire de pièces |

## <a name="add-a-3d-model-from-the-3d-toolkit"></a>Ajouter un modèle 3D à partir de la collection 3D

[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] contient une bibliothèque d'objets 3D prédéfinis, optimisés pour fonctionner parfaitement avec [!include[pn-hololens](../includes/pn-hololens.md)]. La collection 3D inclut des marqueurs, des flèches, des mains, des nombres, des symboles, et des zones et des outils génériques. L'illustration suivante montre un exemple dans lequel des nombres, des flèches et des zones holographiques sont utilisés pour aider les opérateurs à effectuer une étape.

![Exemple de chiffres, de flèches et de zones holographiques](media/3d-toolkit-example.PNG "Exemple de chiffres, de flèches et de zones holographiques")

Vous pouvez mélanger et assortir différents types de modèles 3D. Vous pouvez aussi utiliser le même objet (instance) autant de fois que vous voulez dans une étape.

Pour ajouter un modèle à partir de la collection 3D, procédez comme suit.

1. Sur le côté droit de la page, sélectionnez l'onglet **collection 3D**, puis sélectionnez la catégorie du type d'élément que vous souhaitez ajouter.

    ![Onglet Collection 3D](media/select-3D-toolkit.PNG "Onglet Collection 3D")

2. Faites glisser le modèle 3D souhaité vers l'un des zones **Objets 3D**.

    ![Déplacement d'un modèle 3D vers une zone Objets 3D](media/select-arrow.PNG "Déplacement d'un modèle 3D vers une zone Objets 3D")

> [!NOTE]
> Vous pouvez également ajouter des modèles 3D à partir de la collection 3D directement dans l'application [!include[pn-hololens](../includes/pn-hololens.md)].

### <a name="best-practices-for-the-3d-toolkit"></a>Meilleures pratiques en matière de collection 3D

- Utilisez des pointeurs pour transmettre des informations spatiales comme une position, une direction, et une translation. Vous pouvez ajuster la taille du pointeur, mais jamais en dessous d'1 cm. Sinon, cela peut provoquer des erreurs.

- Utilisez la flèche pour que l'opérateur insère une pièce dans une partie fixe (par exemple, resserrer un boulon à la main dans un trou taraudé).

- Utilisez l'une des postures manuelles pour que l'opérateur utilise sa main d'une manière spécifique pour orienter ou manipuler quelque chose. Il existe de nombreuses postures pour des interactions spécifiques, comme tirer, pousser, pincer, saisir, etc. Combinez ces standards avec des flèches et/ou des icônes pour ajouter une signification supplémentaire.

Pour plus d'informations sur les façons d'utiliser des objets à partir de la collection 3D, voir [Créer un excellent guide](great-guide.md).

## <a name="add-a-3d-part"></a>Ajouter un objet 3D

1. Sélectionnez l'onglet **Objets 3D** sur le côté droit de la page.

    ![Onglet Objets 3D](media/select-3D-parts.PNG "Onglet Objets 3D")

2. Faites glisser l'objet 3D souhaité vers l'un des zones **Objets 3D**.

    ![Déplacement d'un objet 3D vers une zone Objets 3D](media/drag-3D-part.PNG "Déplacement d'un objet 3D vers une zone Objets 3D")

## Importer un modèle 3D personnalisé à utiliser comme objet 3D<a name="import"></a>

Vous pouvez importer vos propres modèles 3D personnalisés et les ajouter à la bibliothèque d'**Objets 3D**. Pour importer des fichiers, vous pouvez les faire glisser depuis un dossier de fichiers local ou utiliser la commande **Importation**.

### <a name="import-a-file-by-using-a-drag-and-drop-operation"></a>Importer un fichier à l'aide d'une opération glisser-déposer

1. Ouvrez l'Explorateur de fichiers Windows et accédez au dossier contenant les modèles 3D que vous souhaitez importer.

2. Faites glisser les fichiers vers la galerie.

    ![Animation glisser-déplacer](media/drag-drop.gif "Animation glisser-déplacer")

### <a name="import-a-file-by-using-the-import-command"></a>Importer un fichier à l'aide de la commande Importer

1.  Sélectionnez **Importer** dans le coin inférieur droit de la page.

    ![Bouton d'importation](media/import-command.PNG "Bouton d'importation")

2.  Localisez les fichiers à importer, puis sélectionnez **Ouvrir**.

    ![Importation d'un objet 3D personnalisé](media/import-object.PNG "Importation d'un objet 3D personnalisé")

> [!NOTE]
> [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] prend en charge les formats de fichier glTF, GLB, FBX, STL et PLY. Vous pouvez utiliser une combinaison d'outils tiers et de [!include[pn-dyn-365-import-tool](../includes/pn-dyn-365-import-tool.md)] pour préparer vos modèles 3D \[CAO\]) ou vous pouvez utiliser le service de conciergerie d'[!include[pn-dyn-365-import-tool](../includes/pn-dyn-365-import-tool.md)] pour que [!include[cc-microsoft](../includes/cc-microsoft.md)] convertisse et optimise les modèles à votre place. Pour plus d'informations sur [!include[pn-dyn-365-import-tool](../includes/pn-dyn-365-import-tool.md)], voir les rubriques suivantes :
>
> - [Présentation de l'Import Tool](https://docs.microsoft.com/dynamics365/mixed-reality/import-tool/index)
>
> - [Optimiser vos modèles 3D](https://docs.microsoft.com/dynamics365/mixed-reality/import-tool/optimize-models)
>
> - [Meilleures pratiques pour les modèles 3D](https://docs.microsoft.com/dynamics365/mixed-reality/import-tool/best-practices)
>
> - [Utiliser Dynamics 365 Import Tool](https://docs.microsoft.com/dynamics365/mixed-reality/import-tool/import-tool)

## <a name="add-media-images-or-videos"></a>Ajouter un contenu multimédia (images ou vidéos)

1. Sélectionnez l'onglet **Images** ou **Vidéos** sur le côté droit de la page.

    ![Onglets Images et vidéos](media/select-image-video.PNG "Onglets Images et vidéos")

2. Faites glisser l'image ou la vidéo vers la zone **Image ou vidéo**.

    ![Déplacement d'une image ou d'une vidéo vers la zone Image ou vidéo](media/drag-image-video.PNG "Déplacement d'une image ou d'une vidéo vers la zone Image ou vidéo")

## <a name="add-a-website-link-to-a-step"></a>Ajouter un lien de site Web à une étape

Vous pouvez ajouter un lien de site Web à une étape, afin que les opérateurs puissent voir et interagir avec des informations en dehors de [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Par exemple, vous souhaiterez peut-être fournir un lien vers un diagramme de pièces, un système d'inventaire, un tableau de bord d'analyse ou des informations sur les capteurs Internet des objets (IoT). Les liens de sites Web permettent aux auteurs de créer un flux de travail transparent pour les opérateurs.

> [!NOTE]
> Un seul lien de site Web peut être ajouté à chaque étape.

1. Sélectionnez l'onglet **Action** sur le côté droit de la page.

    ![Onglet Action](media/action-tab.PNG "Onglet Action")
 
2. Faites glisser le symbole **Lien du site Web** vers le cercle **Action** dans le coin inférieur droit de la fiche étape.

    ![Déplacement du symbole du lien du site Web vers le cercle Action](media/action-circle.PNG "Déplacement du symbole du lien du site Web vers le cercle Action")

3. Dans la boîte de dialogue **Lien du site Web**, entrez une URL valide commençant par **http://** ou **https://**, puis sélectionnez **Enregistrer**.

    ![Boîte de dialogue de lien du site Web](media/website-dialog.PNG "Boîte de dialogue de lien du site Web")

4. Pour afficher, modifier ou supprimer le lien, cliquez avec le bouton droit sur le bouton **Lien du site Web** dans l'**Éditeur d'étape**.

    ![Bouton de lien du site Web](media/website-button.PNG "Bouton de lien du site Web")

## <a name="whats-next"></a>Étapes suivantes

[Ancrer votre guide dans le monde réel](anchor.md)<br>
[Structurer votre guide dans la page Plan](structure-guide.md)<br>
[En savoir plus sur la création d'un excellent guide de réalité mixte](great-guide.md)<br>
[En savoir plus sur les raccourcis clavier](keyboard-shortcuts-pc-app.md)
