---
author: Mamaylya
description: Éléments à garder à l'esprit avant de passer à la création dans Dynamics 365 Guides (version préliminaire), notamment l'affectation de noms de fichier et de support.
ms.author: mamaylya
ms.date: 05/30/2019
ms.service: crm-online
ms.topic: article
title: Éléments à garder à l'esprit avant de passer à la création dans Dynamics 365 Guides (version préliminaire)
ms.reviewer: v-brycho
ms.openlocfilehash: e554fdd00dd940408a4c2a51f29422bee1058ce8
ms.sourcegitcommit: 8770ec043776563f3f9e87ee89f241c68015f576
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/31/2019
ms.locfileid: "1797377"
---
# <a name="before-you-start-authoring-a-guide-in-dynamics-365-guides-preview"></a>Avant de passer à la création d'un guide dans Dynamics 365 Guides (version préliminaire)

[!INCLUDE [cc-beta-prerelease-disclaimer](../includes/cc-beta-prerelease-disclaimer.md)]
 
Avant de passer à la création dans [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)], vous devez comprendre votre projet et vous organiser. Voici une liste de contrôle rapide pour partir du bon pied :

- Collectez autant de contenu que vous pouvez avant de commencer à créer votre guide. Cela inclut des images, des vidéos, et du contenu 3D (si vous en avez) et les objets physiques eux-mêmes (si possible). Ne vous inquiétez pas si vous n'avez pas contenu 3D. 
[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] inclut une boîte à outils 3D que vous pouvez utiliser pour démarrer.

- Assurez-vous d'avoir suffisamment d'espace pour bien comprendre l'environnement du monde réel. Vous aurez également besoin d'avoir de l'espace pour ancrer le guide et placer des hologrammes ultérieurement.

- Vous devez bien connaître l'espace, l'assemblage, ainsi que le flux de travail faisant l'objet de votre création.

- Une bonne manière de démarrer consiste à créer une vidéo de l'assemblage que vous souhaitez afficher, ou de demander à quelqu'un (un expert de ce processus, par exemple) de le créer pour vous. Vous pouvez vous reporter à la vidéo à mesure que vous créez votre guide. Si vous utilisez une vidéo comme point de départ, assurez-vous toutefois qu'elle soit bien représentative du guide que vous voulez créer. Est-ce que vous créez un guide pour un expert ou un novice, par exemple ?

## <a name="use-media-and-3d-content-to-your-advantage"></a>Tirer profit du support et du contenu 3D

Lorsque vous réfléchissez au support et au contenu 3D à utiliser pour votre projet, n'oubliez pas que la taille est très importante sur [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-hololens](../includes/pn-hololens.md)], à la fois pour la qualité de l'expérience et les performances. Il est recommandé d'utiliser des ressources haute-fidélité quand les détails ont de l'importance et des ressources basse fidélité pour connaître les principes essentiels quand les détails ont peu d'importance.

### <a name="best-practices-for-pictures-images"></a>Pratiques recommandées pour les images

- Les images sont :

  - Parfaites pour servir de référence rapide, pour le contrôle ou des techniques spéciales.
  
  - Une manière économique et parfaite pour guider un opérateur, alors n'hésitez pas à en utiliser. 
  
  - Très efficaces pour identifier les modèles, les formes, ou les couleurs spécifiques.
  
- Lorsque vous prenez une photo :

  - Veillez à prendre une photo de l'objet en entier pour avoir un contexte général, ainsi qu'à le prendre en gros plan pour avoir de la précision.
  
  - Gardez bien la perspective de l'opérateur à l'esprit. Il est utile de prendre une photo à partir de l'angle que l'opérateur utilisera également.

- Pour des raisons de performances, n'utilisez pas d'images de qualité 4K/HD. **La taille totale d'image ne doit pas dépasser 100 Ko.**

### <a name="best-practices-for-videos"></a>Meilleures pratiques en matière de vidéos

- Les vidéos sont :

  - Parfaites pour les utilisateurs débutants.
  
  - Très utiles pour afficher des mouvements spécifiques de la main.
  
- Faites en sorte que les vidéos soient courtes et concentrées sur une seule étape.

- Les vidéos de présentation ne fonctionnent pas bien en général, car les opérateurs risquent de penser qu'ils sont supposés réaliser l'assemblage pendant qu'ils regardent la vidéo de présentation. 

- Lorsque vous réalisez la vidéo, veillez à utiliser un objectif grand angle pour avoir le contexte ainsi qu'un plan rapproché pour avoir les mouvements des mains et les tâches.

- Les vidéos efficaces « enseignent » comment réaliser une tâche. Si vous vous contentez de faire une vidéo d'un ouvrier de l'usine en train d'exécuter un processus qu'il connaît très bien, il est probable :

  - Qu'il va bouger trop rapidement.
  
  - Qu'il ne va pas parler lors de l'exécution étape par étape des tâches.
  
  - Qu'il ne va pas enseigner la tâche comme il devrait le faire.
  
- L'audio est très utile pour des instructions détaillées. Le fait de regarder quelqu'un effectuer une tâche sans audio ne fournit pas suffisamment de contexte. Vous devez utiliser des sous-titres, le cas échéant, si les environnements sont bruyants.

### <a name="best-practices-for-3d-content"></a>Meilleures pratiques en matière de contenu 3D

Le contenu 3D est recommandé pour ajouter de la clarté en contexte. [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] inclut une boîte à outils 3D de modèles 3D que vous pouvez utiliser pour ajouter de la clarté dans vos instructions. Par exemple, la boîte à outils 3D contient des flèches, des mains, des zones et des icônes. Ces ressources sont déjà optimisées pour [!include[pn-hololens](../includes/pn-hololens.md)]. Pour plus d'informations, voir le [Guide sur la création](pc-authoring.md).

Vous pouvez également créer et importer vos propres composants 3D personnalisés à l'aide de modèles de CAO. [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] prend en charge les formats de fichier glTF, GLB et FBX. Vous pouvez utiliser une combinaison d'outils tiers et de [!include[pn-dyn-365-import-tool](../includes/pn-dyn-365-import-tool.md)] pour préparer vos modèles 3D ou vous pouvez utiliser le service de conciergerie d'Import Tool pour que [!include[cc-microsoft](../includes/cc-microsoft.md)] convertisse et optimise les modèles à votre place. Pour plus d'informations sur Import Tool et la préparation de modèles 3D, voir les rubriques suivantes :

- [Présentation de l'Import Tool](https://docs.microsoft.com/en-us/dynamics365/mixed-reality/import-tool/)

- [Optimiser vos modèles 3D](https://docs.microsoft.com/en-us/dynamics365/mixed-reality/import-tool/optimize-models)

- [Meilleures pratiques pour les modèles 3D](https://docs.microsoft.com/en-us/dynamics365/mixed-reality/import-tool/best-practices)

## <a name="set-up-a-folder-structure"></a>Paramétrer une structure de dossiers

Pour organiser du contenu, vous pouvez créer une structure de dossiers avec des dossiers séparés pour le texte, les ressources 3D, les images, et les vidéos pour trouver et utiliser facilement les différents types de ressources.

![Structure de dossier](media/folder-structure.PNG "Structure de dossier")
 
### <a name="best-practices-for-file-names"></a>Meilleures pratiques en matière de noms de fichier

Au moment de nommer vos éléments du contenu, pensez à utiliser des préfixes standard afin que toutes vos ressources soient organisées ensemble dans la bibliothèque.

Par exemple :

- atv_eng_01.png

- atv_eng_video01.wmv

### <a name="see-also"></a>Voir aussi

[Présentation de la création de Dynamics 365 Guides](authoring-overview.md)<br>
[Créer un guide à l'aide de l'application du PC](pc-authoring.md)<br>
[Tester votre guide et placer des hologrammes dans l'application HoloLens](hololens-authoring.md)<br>
