---
author: Mamaylya
description: Glossaire des termes pour Dynamics 365 Guides
ms.author: Mamaylya
ms.date: 10/01/2019
ms.service: crm-online
ms.topic: article
title: Glossaire des termes pour Dynamics 365 Guides
ms.reviewer: v-brycho
ms.openlocfilehash: 6502ec4dc6b5a0011035d619451998e66e50ecfd
ms.sourcegitcommit: 40992f99110d02b2120a930679c5f681b0a6227a
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/25/2019
ms.locfileid: "2049947"
---
# <a name="glossary-of-terms-for-dynamics-365-guides"></a>Glossaire des termes pour Dynamics 365 Guides

Ce glossaire peut s'avérer utile lorsque vous travaillez avec [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

## <a name="3d-parts"></a>Composants 3D
Contenu 3D que vous attribuez à une étape pour la prendre en charge. Vous devez affectez des composants 3D dans l'application du PC, puis placer les hologrammes dans le monde réel en mode Créer [!include[pn-hololens](../includes/pn-hololens.md)].

## <a name="3d-toolkit"></a>Boîte à outils 3D
Bibliothèque d'objets prédéfinis inclus dans [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] que vous pouvez utiliser pour commencer immédiatement. Il existe par exemple des objets 3D tels que des pointeurs et des flèches que vous pouvez ajouter à une étape pour la prendre en charge.

## <a name="air-tap"></a>Cliquer dans l'air
Mouvement équivalent à un « clic » de souris. Pour savoir comment cliquer dans l'air, voir [Mouvements à connaître](authoring-gestures.md).

## <a name="anchoring-alignment"></a>Ancrer (alignement)
Processus permettant de s'assurer qu'un guide est bien « aligné » avec les objets associés dans le monde réel quand il est utilisé sur [!include[pn-hololens](../includes/pn-hololens.md)]. L'ancrage est primordial et obligatoire pour créer n'importe quel guide. Pour plus d'informations, voir le [Guide sur la création](pc-authoring.md).

## <a name="author"></a>Auteur
Personne qui crée un guide.

## <a name="calibration"></a>Étalonnage
Processus dans lequel [!include[pn-hololens](../includes/pn-hololens.md)] ajuste l'affichage de l'hologramme selon la distance interpupillaire (DIP) de l'utilisateur. L'appareil [!include[pn-hololens](../includes/pn-hololens.md)] doit être étalonné correctement afin que le guide s'aligne comme il faut dans le monde réel. Un étalonnage approprié est également nécessaire pour placer des objets holographiques en mode Créer dans [!include[pn-hololens](../includes/pn-hololens.md)]. [!include[pn-hololens](../includes/pn-hololens.md)] inclut une application d'étalonnage pouvant être utilisée par les auteurs et les opérateurs à cet effet. 

## <a name="digital-anchor"></a>Point d'ancrage numérique
Représentation 3D utilisée pour ancrer des hologrammes dans le monde réel. Vous devez placer la représentation numérique (qui peut être un modèle de CAO ou un modèle numérisé) directement sur son homologue dans le monde réel, puis faire un mouvement pour aligner le guide sur le point d'ancrage numérique.

## <a name="dotted-line"></a>Trait en pointillé
Lien holographique qui associe visuellement une étape à la zone sur laquelle l'opérateur doit se concentrer. Cela aide l'opérateur à trouver du contenu ou à comprendre ce qu'il est censé observer dans le monde réel. Vous pouvez utiliser une ligne pointillée holographique avec un objet 3D, comme une flèche ou un chiffre holographique. 

## <a name="field-of-view-fov"></a>Champ de vision
Taille de l'affichage [!include[pn-hololens](../includes/pn-hololens.md)] où apparaissent les hologrammes. Il est important de conserver le champ de vision à l'esprit au moment de placer les hologrammes dans le monde réel.

## <a name="fit-box-setting"></a>Paramètres Ajuster la zone
Paramètre qui garantit que l'appareil [!include[pn-hololens](../includes/pn-hololens.md)] est correctement ajusté. Il est très important que l'alignement soit correct.

## <a name="gaze"></a>Pointer du regard
Action consistant à fixer un élément de l'interface utilisateur avec [!include[pn-hololens](../includes/pn-hololens.md)]. Dans certains cas, vous pouvez sélectionner un élément simplement en le regardant fixement. Dans d'autres cas, vous devez pointer du regard pour cibler un objet, puis agir sur votre sélection en faisant un mouvement.

## <a name="gesture"></a>Mouvement
Mouvement de la main permettant à un opérateur d'effectuer une action en réalité mixte. Pour plus d'informations, voir [Mouvements à connaître](authoring-gestures.md).

## <a name="interpupillary-distance-ipd"></a>Distance interpupillaire (DIP)
Distance entre les yeux d'un utilisateur. Tous les utilisateurs ont des DIP différents. Pour aligner correctement le contenu, [!include[pn-hololens](../includes/pn-hololens.md)] doit être étalonné pour le DIP de chaque utilisateur. 

## <a name="marker"></a>Marqueur
Visuel généré par ordinateur utilisé pour les points d'ancrage imprimés. Vous devez pointer du regard le marqueur imprimé pour aligner le guide avec ses coordonnées spatiales.

## <a name="operator"></a>Opérateur
Personne qui utilise un guide pour effectuer un ensemble de tâches. 

## <a name="outline-page"></a>Page Plan
Page de l'application de création du PC utilisée pour ajouter des tâches et des étapes. À partir de la page Plan, vous pouvez vous faire une idée du guide complet et restructurer des tâches en les déplaçant d'un document à un autre. Elle inclut également des instructions d'ancrage personnalisables et une étape spéciale appelée Étape de fin (également personnalisable).

## <a name="step"></a>Étape
Petite partie d'un travail qu'un opérateur doit effectuer pour réaliser une tâche. Les tâches se composent d'étapes. Les étapes constituent également le point de navigation central d'un guide.

## <a name="step-card"></a>Fiche étape
Bloc élémentaire fondamental dans [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. L'opérateur doit ajouter du texte et des ressources de prise en charge à une fiche étape dans l'application de création du PC, puis placer les hologrammes associés à chaque étape dans le monde réel en mode Créer [!include[pn-hololens](../includes/pn-hololens.md)]. L'opérateur doit ensuite passer par chaque étape pour terminer une tâche ou une série de tâches. Pour plus d'informations sur les fiches étape, voir [Guide sur la création](pc-authoring.md).

## <a name="style"></a>Style
Propriétés visuelles que vous pouvez ajouter à un objet 3D pour mettre l'accent sur ce que l'opérateur doit effectuer ou connaître. Parmi les exemples de styles on trouve : Choisir, Placer et Avertissement.

## <a name="task"></a>Tâche
Travail à effectuer ou à être entrepris. Une tâche comprend plusieurs étapes que l'opérateur doit suivre. 



### <a name="see-also"></a>Voir aussi

[Présentation de la création d'un guide](authoring-overview.md)<br>
[Manuel de l'opérateur](operator-guide.md)<br>
[Analyser les guides](analytics-guide.md)
