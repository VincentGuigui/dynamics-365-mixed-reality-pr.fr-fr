---
author: Mamaylya
description: Apprenez à exploiter un guide dans Dynamics 365 Guides en utilisant l'application HoloLens.
ms.author: mamaylya
ms.date: 01/28/2020
ms.service: crm-online
ms.topic: article
title: Utiliser un guide dans Dynamics 365 Guides
ms.reviewer: v-brycho
ms.openlocfilehash: 6684446712ac92ced42352a33d20bbc2438c1222
ms.sourcegitcommit: 217d31bb34e67a6b8823d5ddac7ef8d56d054139
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/29/2020
ms.locfileid: "2995266"
---
# <a name="operate-a-guide-in-dynamics-365-guides"></a>Utiliser un guide dans Dynamics 365 Guides

![Graphique de la caméra vidéo](media/video-camera.PNG "Graphique de la caméra vidéo") [Visionner une vidéo sur l'utilisation d'un guide](https://aka.ms/guidesoperate)

Lorsque vous ouvrez un guide en tant qu'opérateur avec l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] HoloLens, une fiche étape rassemblant tout ce que vous effectuez dans ce guide s'affiche. La fiche étape fournit des instructions à suivre pour réaliser une tâche. Elle contient également deux boutons à utiliser pour parcourir un guide : les boutons **Étape suivante** et **Retour**. Lorsque vous parcourez les étapes d'une tâche, la fiche étape vous accompagne dans [!include[pn-hololens](../includes/pn-hololens.md)] pour conserver vos instructions quand vous en avez besoin. 

![Fiche étape avec les boutons Étape suivante et Précédent](media/pin.PNG "Fiche étape avec les boutons Étape suivante et Précédent")  

## <a name="get-oriented-with-the-step-card"></a>Se repérer avec la fiche étape

Outre les boutons **Étape suivante** et **Précédent**, la fiche étape inclut un certain nombre de boutons individuels et d'éléments de l'IU pour vous aider à entreprendre différentes actions. 

![Boutons de la fiche étape](media/operator-step-card-orientation.PNG "Boutons de la fiche étape")   

Voici une description des boutons et d'autres éléments de l'IU de la fiche étape :

|Nombre|Bouton/Exemple|Nom|Description|
|---|--|------------------|------------------------------------------------------------------------------------|
|1|![Bouton Accueil](media/home-button.png "Bouton Accueil")|Accueil|Choisissez un autre guide.|
|2|![Bouton Mode suivi](media/follow-button.png "Bouton Mode suivi")|Mode suivi|Faites en sorte que la fiche étape vous suive ou verrouillez-la à un emplacement.<br><br>Si vous désactivez le Mode suivi, la fiche étape reste où elle est. Vous pouvez saisir la fiche à tout moment à l'aide de la barre de navigation et la déplacer où vous voulez. Pour plus d'informations, consultez la section **Suivre et épingler** plus loin dans cette rubrique.|
|3|![Bouton Ancrer](media/anchor-button.PNG "Bouton Ancrer")|Bouton Ancrer|Ancrez à nouveau (réalignez) le guide.<br><br>Il arrive qu'[!include[pn-hololens](../includes/pn-hololens.md)] ne puisse plus se repérer, ce qui provoque un mauvais alignement des hologrammes. Pour résoudre ce problème, vous devez ancrer à nouveau le guide en pointant du regard le point d'ancrage imprimé ou le point d'ancrage numérique. Pour plus d'informations, voir « Ancrer le guide » plus haut dans cette rubrique.|
|4|![Bouton Paramètres](media/settings-button.png "Bouton Paramètres")|Paramètres|Affiche la version de [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] que vous utilisez.| 
|5|![Bouton Profil](media/profile-button.png "Bouton Profil")|Profil|Pour se connecter et se déconnecter.| 
|6|![Progression d'étape](media/step-progress.PNG "Progression d'étape")|Progression d'étape|Indique où vous êtes dans l'étape.|
|7|![Bouton Plan](media/outline-button.png "Bouton Plan")|Plan|Pour accéder à la page **Plan**.<br><br>Utilisez la page **Plan** pour parcourir rapidement votre guide. Voici à quoi ressemble la page **Plan** dans le guide Câblage de pylône :</br><br>![Page Plan HoloLens](media/outline-operator.PNG "Page Plan HoloLens")| 
|8|![Nom de la tâche](media/task-name-table.PNG "Nom de la tâche")|Nom de la tâche|Nom de la tâche sur laquelle vous travaillez.| 
|9|![Progression de la tâche](media/task-progress.PNG "Progression de la tâche")|Progression de la tâche|Indique où vous en êtes dans la tâche.| 
 
## <a name="use-a-dotted-line-to-help-you-find-the-focus-area-for-a-step"></a>Utiliser une ligne pointillée pour rechercher la zone ciblée dans une étape 
Les fiches étape sont liées par des lignes pointillées holographiques aux zones physiques de la zone de travail. Ces lignes pointillées vous aident à rechercher la zone où vous devez agir. 

![Ligne pointillée holographique](media/dotted-line.PNG "Ligne pointillée holographique")

### <a name="dotted-line-tips-and-tricks"></a>Trucs et astuces sur les lignes pointillées 

- Suivez la ligne pointillée pour trouver la zone physique où vous devez travailler. Suivez la ligne pointillée jusqu'à la fiche étape pour lire les instructions. 

- Si la ligne pointillée pointe derrière vous, allez sur le côté et continuez à la suivre. Notez que la ligne pointillée peut parfois passer par des objets du monde réel. 

## <a name="follow-and-pinning"></a>Suivre et épingler 

Vous remarquerez que partout où vous regardez, la fiche étape suit votre regard. Lorsque vous travaillez, vous n'avez pas besoin de chercher les instructions. Vous pouvez faire en sorte que la fiche étape ne vous suive plus en désactivant le mode suivi dans la barre de navigation. 

![Désactiver le mode suivi](media/follow-button-nav-bar.PNG "Désactiver le mode suivi")

Vous pouvez saisir la barre de navigation à tout moment et la placer la fiche où vous voulez.

![Saisir la barre de navigation](media/follow-button-move-card.PNG "Saisir la barre de navigation")

## <a name="access-a-website-linked-from-the-step-card"></a>Accéder à un site Web lié à partir de la fiche étape

Si une fiche étape comprend un bouton **Lien du site Web**, vous pouvez accéder à ce site Web en sélectionnant le bouton. Par exemple, il peut y avoir un lien vers un diagramme de pièces ou un système d'inventaire de pièces. Le site Web s'ouvre dans le navigateur Edge HoloLens. Lorsque vous fermez le navigateur, vous revenez à l'étape où vous étiez. 

![Bouton de lien du site Web](media/website-button-runtime.PNG "Bouton de lien du site Web")

## <a name="turn-off-holograms"></a>Désactiver des hologrammes 
Vous pouvez désactiver des hologrammes (ou les activer à nouveau) du regard si vous jamais vous sentez qu'ils se décalent. Pour désactiver un hologramme, pointez du regard l'« œil » au milieu de la ligne pointillée. 

![Désactiver des hologrammes](media/dotted-line-toggle-visibility.PNG "Désactiver des hologrammes")  

## <a name="see-also"></a>Voir aussi

![Graphique de la caméra vidéo](media/video-camera.PNG "Graphique de la caméra vidéo") [Visionner une vidéo sur l'utilisation d'un guide](https://aka.ms/guidesoperate)<br>
![Graphique du document](media/doc-icon.PNG "Graphique du document") [Étalonner HoloLens](https://docs.microsoft.com/windows/mixed-reality/calibration)



