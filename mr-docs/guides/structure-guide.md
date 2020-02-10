---
author: Mamaylya
description: Apprendre à structurer un guide à l'aide de la page Plan de l'application du PC Dynamics 365 Guides
ms.author: mamaylya
ms.date: 01/28/2020
ms.service: crm-online
ms.topic: article
title: Utiliser la page Plan pour créer la structure d'un guide dans l'application du PC Dynamics 365 Guides
ms.reviewer: v-brycho
ms.openlocfilehash: a7dd5d293ced72cf51cb601a98655b3d5131a1cd
ms.sourcegitcommit: 217d31bb34e67a6b8823d5ddac7ef8d56d054139
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/29/2020
ms.locfileid: "2995267"
---
# <a name="structure-your-guide-in-the-outline-page-in-the-dynamics-365-guides-pc-app"></a>Structurer votre guide dans la page Plan de l'application du PC Dynamics 365 Guides

Une fois que vous avez [créé un guide](create-guide.md) avec l'application du PC [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] ou ouvert un guide existant, la page **Plan** s'affiche. C'est dans cette page **Plan** que vous allez créer la structure de votre guide en ajoutant autant de tâches et d'étapes que nécessaire. Les tâches sont des groupes d'étapes. Les étapes constituent une petite partie d'un travail qu'un opérateur doit effectuer pour réaliser une tâche. Les étapes constituent les éléments centraux dans [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

![Page Plan](media/outline-page-3.PNG "Page Plan")

>[!NOTE]
>Vous pouvez également utiliser la page **Plan** pour choisir une méthode d'ancrage pour le guide ou pour modifier celle existante. Pour plus d'informations sur l'ancrage d'un guide, voir [Ancrer votre guide dans le monde réel](anchor.md).

La page **Plan** offre une bonne manière de démarrer votre guide ou d'en obtenir une idée globale après avoir ajouté toutes les tâches et les étapes. Vous pouvez également restructurer votre guide à partir de la page **Plan** en faisant glisser les tâches et les étapes.

La page **Plan** comprend une étape spéciale appelée **Étape d'achèvement** qui est incluse dans tous les guides. Cette étape indique aux opérateurs quand ils ont atteint la fin du guide. L'**étape d'achèvement** inclut du texte par défaut que vous pouvez personnaliser comme vous le souhaitez.

![Étape d'achèvement](media/completion-step.PNG "Étape d'achèvement")

Voici l'exemple d'une page **Plan** remplie :

![Page Plan remplie à partir du guide Câblage de pylône](media/finished-outline-page.png "Page Plan remplie à partir du guide Câblage de pylône")

## <a name="go-to-other-pages-from-the-outline-page"></a>Accéder à d'autres pages de la page Plan

Utilisez les boutons de la barre de navigation sur le côté gauche de la page **Plan** pour accéder à d'autres pages de l'application du PC. Le tableau suivant décrit les boutons de la barre de navigation.

|Bouton|Nom|Action|
|--------|----------------|----------------------------------------------------------|
|![Bouton Ouvrir la navigation](media/open-navigation-button.png "Bouton Ouvrir la navigation")|**Ouvrir la navigation**|Développez la barre de navigation pour inclure des descripteurs pour chaque bouton.|
|![Bouton Accueil](media/home-button-pc-app.png "Bouton Accueil")|**Accueil**|Accédez à la page d'**accueil**. Dans la page d'**accueil** vous pourrez créer un guide ou en ouvrir un existant.|
|![Bouton Analyser](media/analyze-button-pc-app.png "Bouton Analyser")|**Analyser**|Accédez à la page **Analyser**. Dans la page **Analyser**, vous pourrez configurer les états Power BI (Guides Analytics) pour analyser vos guides.|
|![Bouton Ancrer](media/anchor-button-pc-app.png "Bouton Ancrer")|**Ancrer**|Accédez à l'assistant **Choisir une méthode d'ancrage**. Dans l'assistant, vous pouvez sélectionner différentes méthodes d'ancrage pour votre guide ou modifier le type de méthode d'ancrage.|
|![Bouton Étape](media/step-button-pc-app.png "Bouton Étape")|**Étape**|Accédez à la page **Éditeur d'étape**. Dans la page **Éditeur d'étape**, vous pouvez ajouter votre texte d’instruction et ajouter du contenu de prise en charge 2D ou 3D.|

## <a name="work-with-tasks-and-steps"></a>Travailler avec des tâches et des étapes

Lorsque vous ouvrez la page **Plan** pour un guide qui vient d'être créé, vous voyez qu'une tâche ou une étape est déjà créée pour vous. 

![Créer une tâche et une étape](media/outline-page-4.png "Créer une tâche et une étape")

Le tableau suivant décrit les actions pour travailler avec des tâches et des étapes.

|Pour|Effectuez l'opération suivante|
|------------------------------|-------------------------------------------------------------|
|Modifier un nom de tâche|Tapez un nouveau nom dans la zone **Nom de la tâche**.|
|Entrer des instructions pour une étape|Saisissez votre texte dans la case sous le nom de la tâche. Lorsque vous commencez à taper votre texte, l'**Éditeur d'étape**apparaît. Pour en savoir plus sur l'utilisation de l'**Éditeur d'étape**, voir [Créer des étapes et ajouter des modèles 3D ou des supports 2D](create-steps-assign-media.md).|
|Ajouter une nouvelle tâche|Sélectionnez **Ajouter une tâche** sous la dernière tâche/série d'étapes. Vous pouvez également sélectionner le bouton **Menu des tâches** (...) à droite du nom de la tâche, puis sélectionner **Insérer une tâche**.|
|Ajouter une étape|Sélectionnez **Ajouter une étape**.|
|Supprimer une tâche et ses étapes|Sélectionnez le bouton **Menu des tâches** (...) à droite du nom de la tâche, puis sélectionnez **Supprimer la tâche et les étapes**.
|Modifier les instructions de l'étape d'**achèvement**|Sélectionnez l'étape d'**achèvement**. La page **Éditeur d'étape** s'ouvre. Pour en savoir plus sur l'utilisation de l'**Éditeur d'étape**, voir [Créer des étapes et ajouter des modèles 3D ou des supports 2D](create-steps-assign-media.md).|
|Réorganiser les tâches ou les étapes|Faites glisser la tâche ou l'étape pour la déplacer où vous le souhaitez.|

## <a name="best-practices-for-the-outline-page"></a>Meilleures pratiques en matière de page Plan

- Pour fournir un contexte général, ajoutez une tâche de vue d'ensemble au début du guide. Cette tâche ne contient qu'une seule étape qui indique sur quoi porte le guide. C'est également un bon endroit pour répertorier toutes les tâches abordées dans le guide. 

- Ajoutez une étape au début et à la fin de chaque tâche pour indiquer à l'opérateur quand il doit commencer ou terminer une tâche, et pour qu'il sache qu'il a réussi une fois qu'il a terminé une tâche.

- N'ayez pas peur d'avoir beaucoup d'étapes, mais gardez bien à l'esprit qu'elles doivent être courtes pour de meilleurs résultats. 

- Pensez à ajouter des étapes indiquant des trucs et des astuces. 

## <a name="whats-next"></a>Étapes suivantes

[Ancrer votre guide dans le monde réel](anchor.md)<br>
[Créer des étapes et ajouter du contenu 3D ou des supports 2D](create-steps-assign-media.md)<br>
[En savoir plus sur les raccourcis clavier](keyboard-shortcuts-pc-app.md)<br>

