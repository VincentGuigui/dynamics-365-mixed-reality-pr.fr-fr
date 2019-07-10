---
author: ornellaalt
description: Guide de l'utilisateur de Dynamics 365 Layout
ms.author: ornella
ms.date: 05/15/2019
ms.service: crm-online
ms.topic: article
title: Guide de l'utilisateur de Dynamics 365 Layout
ms.reviewer: v-brycho
ms.openlocfilehash: 15d9117e892a7d4d9c61b28b4510d1b4b874465f
ms.sourcegitcommit: a9ae3e613938a7c53b2de2ce787fae6a3499c9ae
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/21/2019
ms.locfileid: "1593578"
---
# <a name="dynamics-365-layout-user-guide"></a>Guide de l'utilisateur de Dynamics 365 Layout

Utilisez [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-layout](../includes/pn-dyn-365-layout.md)] pour créer et concevoir des plans d'aménagement d'espace dans Microsoft [!include[pn-hololens](../includes/pn-hololens.md)] ou un casque immersif [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Mixed Reality. Importez des modèles 3D puis concevez, modifiez et collaborez pratiquement dans une échelle à taille réelle.

Besoin d'aide complémentaire ? [Consultez la FAQ](faq.md) Dynamics 365 Layout pour obtenir des réponses aux questions fréquentes.

[Consultez des vidéos pratiques concernant Dynamics 365 Layout.](videos.md)

## <a name="what-youll-need"></a>Ce dont vous aurez besoin

-   [Un abonnement à Dynamics 365 Layout.](../licensing/buy-and-deploy.md) L'abonnement [!include[pn-layout](../includes/pn-layout.md)] inclut également [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-import-tool](../includes/pn-dyn-365-import-tool.md)] pour PC.
    
    > [!TIP]
    > Vous pouvez essayer [!include[pn-layout](../includes/pn-layout.md)] gratuitement jusqu'à 90 jours. [En savoir plus sur l'essai gratuit de Dynamics 365 Layout de 90 jours](try-layout-free.md).

-   Un appareil [HoloLens](https://www.microsoft.com/hololens) exécutant la [Windows 10 April 2018 Update](https://support.microsoft.com/en-us/help/12643) et/ou un casque immersif [Windows Mixed Reality](https://www.microsoft.com/en-us/windows/windows-mixed-reality). 

-   Un PC prêt pour [Windows Mixed Reality](https://www.microsoft.com/en-us/windows/windows-mixed-reality-devices#wmrpcs) exécutant la [Windows 10 April 2018 Update](https://support.microsoft.com/en-us/help/4028685).

-   Une connexion Internet.

## <a name="install-the-apps"></a>Installer les applications

La manière dont vous installez [!include[pn-layout](../includes/pn-layout.md)] et [!include[pn-import-tool](../includes/pn-import-tool.md)] dépend du mode de distribution des applications choisi par votre administrateur. Votre administrateur peut vous demander d'installer l'application depuis [!include[cc-microsoft](../includes/cc-microsoft.md)] Store pour les consommateurs, depuis le magasin privé de votre organisation, via un lien de courrier électronique, ou par un autre biais. 

Le tableau suivant décrit l'application/outil, et son installation depuis le magasin public.

| **Application**     | **Appareil**            | **Utilisation**                            | **Installation depuis le [!include[cc-microsoft](../includes/cc-microsoft.md)] Store** |
|-------------|-----------------------|---------------------------------------------|-------------------------------------|
| [!include[pn-layout](../includes/pn-layout.md)]      | [!include[pn-hololens](../includes/pn-hololens.md)]              | <ul><li>Créer des dispositions en analysant les environs. </li><li>Placer des modèles dans vos dispositions. </li></ul>     | Dans votre [!include[pn-hololens](../includes/pn-hololens.md)], allez à **Démarrer** ![Démarrer](media/d2a2ae5e90bdd0e0642abb5458af1016.png "Démarrer") \> **[!include[cc-microsoft](../includes/cc-microsoft.md)] Store** ![Microsoft Store](media/2ac602b5a7855d312f3e7d924732acca.png "Microsoft Store"), recherchez « [!include[pn-dyn-365-layout](../includes/pn-dyn-365-layout.md)] », puis [installez l'application](https://www.microsoft.com/store/apps/9N20MQ2V3XCW). <br>    |
| [!include[pn-layout](../includes/pn-layout.md)]      | Casque de réalité mixte |<ul><li>Placer des modèles dans des dispositions importées depuis [!include[pn-hololens](../includes/pn-hololens.md)] ou [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-visio](../includes/pn-visio.md)]. </ul>| 1. Sur votre PC, allez à **Démarrer** ![Démarrer](media/d2a2ae5e90bdd0e0642abb5458af1016.png "Démarrer") \> **[!include[cc-microsoft](../includes/cc-microsoft.md)] Store** ![Microsoft Store](media/2ac602b5a7855d312f3e7d924732acca.png "Microsoft Store"), recherchez « [!include[pn-dyn-365-layout](../includes/pn-dyn-365-layout.md)] », puis [installez l'application](https://www.microsoft.com/store/apps/9N20MQ2V3XCW). <br> 2. Connectez votre casque de réalité mixte au PC, puis recherchez l'application dans le menu **Démarrer** de réalité mixte. <br>   |
| [!include[pn-import-tool](../includes/pn-import-tool.md)] | PC                    | <ul><li>Transférer les plans d'étage depuis [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-visio](../includes/pn-visio.md)] vers [!include[pn-hololens](../includes/pn-hololens.md)] ou [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Mixed Reality.</li><li>Transférer les dispositions entre [!include[pn-hololens](../includes/pn-hololens.md)] et [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Mixed Reality. </li><li>Traiter les modèles 3D à utiliser dans [!include[pn-hololens](../includes/pn-hololens.md)]. </ul>| Dans votre PC, allez à **Démarrer** ![Démarrer](media/d2a2ae5e90bdd0e0642abb5458af1016.png "Démarrer") \> **[!include[cc-microsoft](../includes/cc-microsoft.md)] Store** ![Microsoft Store](media/2ac602b5a7855d312f3e7d924732acca.png "Microsoft Store"), recherchez « [!include[pn-dyn-365-import-tool](../includes/pn-dyn-365-import-tool.md)] », puis [installez l'application](https://www.microsoft.com/store/apps/9NBF1CGB7KHX). <br>    |

## <a name="get-started-with-dynamics-365-layout-take-advantage-of-learning-tools"></a>Mise en route de Dynamics 365 Layout : tirer profit des outils d'apprentissage

[!include[pn-layout](../includes/pn-layout.md)] inclut deux outils (moments d'information et démonstrations de dispositions) que vous pouvez utiliser pour vous aider à savoir comment effectuer des tâches courantes telles que la mesure, la copie, le regroupement, le redimensionnement et l'accès aux paramètres.

### <a name="teaching-moments"></a>Moments d'information

Les moments d'information fournissent diverses images qui permettent de comprendre facilement des tâches courantes. Pour accéder aux moments d'information, appuyez sur **Aide**, puis sur la zone pour laquelle vous avez besoin d'aide.

![Moments d'information](media/teaching-moments.PNG "Moments d'information")

### <a name="demo-layouts"></a>Démonstrations de dispositions

Les démonstrations de dispositions utilisent des dispositions prédéfinies pour montrer comment développer différentes parties d'une usine de fabrication. Vous avez le choix entre trois démonstrations :
- Copier/coller et collision
- Grouper et mesurer
- Ajuster et redimensionner

![Démonstrations de dispositions](media/demo-layouts.PNG "Démonstrations de dispositions")

Par exemple, dans la démonstration Copier/coller et collision, découvrez comment compléter un tapis de convoyeur en copiant et en positionnant des sections.

Pour accéder à des démonstrations de dispositions, sélectionnez la démonstration de votre choix dans le menu **Dispositions**.

![Accédez aux démonstrations de dispositions](media/access-demo-layouts.PNG "Accédez aux démonstrations de dispositions")

## <a name="use-dynamics-365-layout"></a>Utiliser Dynamics 365 Layout

Pour utiliser [!include[pn-layout](../includes/pn-layout.md)], vous créez des dispositions d'espace sur votre [!include[pn-hololens](../includes/pn-hololens.md)] ou PC, puis vous utilisez [!include[pn-hololens](../includes/pn-hololens.md)] ou un casque immersif [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Mixed Reality pour placer des modèles 3D dans les dispositions. L'application [!include[pn-layout](../includes/pn-layout.md)] est fournie avec des modèles préinstallés, et vous pouvez également ajouter les vôtres.

### <a name="create-a-layout"></a>Créer une disposition

Il existe deux façons de créer une disposition :

-   Utilisez [Microsoft Visio](https://products.office.com/en-us/visio/) pour concevoir un plan d'étage, puis exportez-le vers [!include[pn-hololens](../includes/pn-hololens.md)] ou [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Mixed Reality.

-   Utilisez [!include[pn-layout](../includes/pn-layout.md)] sur votre [!include[pn-hololens](../includes/pn-hololens.md)] pour analyser un espace.

#### <a name="create-a-layout-with-microsoft-visio"></a>Créer une disposition avec Microsoft Visio

**Étape 1 : téléchargez et installez le complément [!include[pn-visio](../includes/pn-visio.md)] pour [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-layout](../includes/pn-dyn-365-layout.md)]**

1.  Ouvrez [!include[pn-import-tool](../includes/pn-import-tool.md)].

2.  Sélectionnez **À propos**, puis sélectionnez le téléchargement 32 bits ou 64 bits (choisissez celui qui correspond à votre version de [!include[pn-visio](../includes/pn-visio.md)]).
    
    > [!div class="mx-imgBorder"]
    > ![Télécharger le complément Visio](media/visio-download.PNG "Télécharger le complément Visio") 

3.  Ouvrez [!include[pn-visio](../includes/pn-visio.md)], puis sélectionnez **Fichier** \> **Options** \> **Compléments**.

4.  À côté de **Gérer**, sélectionnez **Compléments COM**, puis **Atteindre**.

5.  Sélectionnez **Complément [!include[pn-visio](../includes/pn-visio.md)] pour [!include[pn-dyn-365-layout](../includes/pn-dyn-365-layout.md)]**, puis **Ajouter**.

**Étape 2 : créez votre plan d'étage avec [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-visio](../includes/pn-visio.md)]**

-   Lorsque le plan d'étage est prêt, sélectionnez l'onglet **[!include[pn-layout](../includes/pn-layout.md)]** et **Exporter**, puis enregistrez votre plan d'étage.

**Étape 3 : importez votre plan d'étage au moyen de l'[!include[pn-import-tool](../includes/pn-import-tool.md)]**

1.  Dans l'[!include[pn-import-tool](../includes/pn-import-tool.md)], sélectionnez **Ce PC** \> **Ajouter une disposition**, puis accédez au plan d'étage.

2.  Sélectionnez le plan d'étage, puis **Ouvrir**.

    Le plan d'étage s'affiche automatiquement dans [!include[pn-layout](../includes/pn-layout.md)] sur un casque immersif de réalité mixte connecté au même PC.

Pour utiliser la disposition dans [!include[pn-hololens](../includes/pn-hololens.md)], vous devez la déplacer ici :

1.  Connectez votre [!include[pn-hololens](../includes/pn-hololens.md)] à votre PC à l'aide du câble USB.

2.  Ouvrez [!include[pn-import-tool](../includes/pn-import-tool.md)] sur le PC, puis sélectionnez **Ce PC** \> **Dispositions**.

3.  Cochez la case sur les dispositions que vous souhaitez copier, puis sélectionnez **Envoyer**.
    
    > [!div class="mx-imgBorder"]
    > ![Déplacez la disposition dans HoloLens](media/selected-layouts-hololens.PNG "Déplacez la disposition dans HoloLens")

4.  Dans [!include[pn-hololens](../includes/pn-hololens.md)], ouvrez l'application [!include[pn-layout](../includes/pn-layout.md)]. Vous trouverez votre disposition dans l'onglet **Dispositions**.

#### <a name="create-a-layout-with-hololens"></a>Créer une disposition avec HoloLens

1.  Dans votre appareil [!include[pn-hololens](../includes/pn-hololens.md)], ouvrez l'application [!include[pn-layout](../includes/pn-layout.md)].

2.  Sélectionnez **Nouvelle disposition**, puis suivez les instructions pour analyser votre espace et créer une disposition.

Pour déplacer la disposition vers votre PC afin de pouvoir l'ouvrir dans un casque immersif de réalité mixte : 

1.  Connectez l'[!include[pn-hololens](../includes/pn-hololens.md)] au PC à l'aide du câble USB.

2.  Ouvrez l'[!include[pn-import-tool](../includes/pn-import-tool.md)], puis sélectionnez le nom de l'[!include[pn-hololens](../includes/pn-hololens.md)].

3.  Cochez la case sur la disposition que vous souhaitez envoyer vers votre PC, puis sélectionnez **Envoyer**.
    
    > [!div class="mx-imgBorder"]
    > ![Déplacez la disposition depuis HoloLens](media/selected-layouts-pc.PNG "Déplacez la disposition depuis HoloLens")


## <a name="place-copy-resize-rotate-and-select-3d-models"></a>Placer, copier, redimensionner, faire pivoter et sélectionner des modèles 3D

Dans [!include[pn-hololens](../includes/pn-hololens.md)] et dans [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Mixed Reality, vous pouvez placer, déplacer, copier, redimensionner et faire pivoter des modèles 3D.

### <a name="on-hololens"></a>Sur HoloLens

| **Pour**       | **Effectuez l'opération suivante**                                                                                                                                                                                                              |
|--------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Placer        | Sélectionnez **Modèles**, puis pointez du regard et appuyez pour sélectionner le modèle que vous souhaitez placer. Utilisez le pointage du regard pour déplacer le modèle, puis appuyez à nouveau pour le placer.                                                                      |
| Déplacer         | Pointez du regard un modèle, puis appuyez longuement dessus. Déplacez votre main pour repositionner le modèle, puis relâchez.                                                                                                                         |
| Copier         | Pointez du regard et appuyez pour sélectionner le modèle, puis choisissez **Copier**. Déplacez le modèle où vous le souhaitez, puis appuyez pour le placer. Sélectionnez **Terminé**.                                                                         |
| Redimensionner       | Pointez du regard et appuyez pour sélectionner un modèle, puis choisissez **Redimensionner**. Appuyez longuement sur n'importe quel bord du modèle, puis déplacez votre main vers l'intérieur et vers l'extérieur.                                                                                   |
| Faire pivoter       | Pointez du regard et appuyez pour sélectionner le modèle. Sélectionnez une des flèches de rotation pour faire pivoter sur 90 degrés. Pour une rotation plus précise, appuyez longuement sur la commande ronde de rotation, puis déplacez votre main pour faire pivoter.                     |
| Sélection multiple | Pointez du regard un emplacement vide. Appuyez longuement puis déplacez votre main en diagonale pour former un rectangle autour de tous les modèles que vous voulez sélectionner. Pointez du regard les modèles sélectionnés pour voir ce que vous pouvez faire avec tous. |

### <a name="on-an-immersive-headset"></a>**Sur un casque immersif**

| **Pour**       | **Effectuez l'opération suivante**                                                                                                                                                                                                                                                                          |
|--------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Placer        | Sélectionnez **Modèles** dans le menu d'application. Pointez votre contrôleur sur le modèle souhaité, puis tirez sur la gâchette et retenez-la pour faire votre choix. Pointez l'emplacement souhaité pour placer le modèle, puis relâchez la gâchette.                                                                        |
| Déplacer         | Pointez le modèle puis tirez sur la gâchette et retenez-la. Déplacez votre contrôleur, puis relâchez la gâchette pour procéder au placement.                                                                                                                                                                  |
| Copier         | Sélectionnez le modèle, puis choisissez **Copier**. Pointez votre contrôleur sur l'emplacement souhaité pour la copie, puis tirez à nouveau sur la gâchette pour procéder au placement. Pour placer plusieurs copies, il suffit de pointer puis de renouveler la sélection (inutile de revenir à l'original). Sélectionnez **Terminé** sur la dernière copie.      |
| Redimensionner       | Sélectionnez le modèle, puis choisissez **Redimensionner**. Pointez un bord de l'objet, puis tirez sur la gâchette et retenez-la. Faites glisser le bord, puis relâchez la gâchette.                                                                                                                      |
| Faire pivoter       | Pointez puis tirez sur la gâchette pour sélectionner le modèle. Pointez ensuite une des flèches de rotation et tirez sur la gâchette pour faire pivoter le modèle sur 90 degrés. Pour une rotation plus précise, utilisez la commande ronde de rotation : pointez, tirez sur la gâchette et retenez-la, puis déplacez votre contrôleur pour faire pivoter. |
| Sélection multiple | Pointez votre contrôleur sur un emplacement vide. Tirez sur la gâchette et retenez-la, puis faites glisser pour former un rectangle autour des modèles que vous souhaitez sélectionner. Pointez les modèles sélectionnés pour voir ce que vous pouvez faire avec tous. |

## <a name="improve-performance-when-your-models-dont-require-texture-or-multiple-colors"></a>Améliorer les performances lorsque vos modèles n'ont pas besoin de texture ou de plusieurs couleurs

Dans certains cas, des textures ou des couleurs multiples peuvent n'avoir aucune importance pour la visualisation des modèles 3D. Vous pouvez alors, pour améliorer les performances, désactiver les textures et utiliser une seule couleur. Vous pouvez pour cela utiliser le paramètre **Performance**. 

Pour activer ou désactiver le paramètre **Performance** :

- Sélectionnez **Paramètres**, **Performance**, puis **Simplifier les objets en utilisant une seule couleur**.

> [!div class="mx-imgBorder"]
> ![Paramètre du mode de performance](media/performance-mode-setting.PNG "Paramètre du mode de performance")

## <a name="turn-off-fading-of-holograms"></a>Désactiver l'atténuation des hologrammes

Par défaut, les hologrammes s'atténuent lorsque vous approchez à environ 45 centimètres d'eux. Vous pouvez utiliser le paramètre **Atténuer les hologrammes** si vous souhaitez désactiver cet effet d'atténuation des hologrammes et les observer de près.

![Paramètre Atténuer les hologrammes](media/hologram-fade.PNG "Paramètre Atténuer les hologrammes")

Réactivez l'atténuation des hologrammes à tout moment en remettant le paramètre sur **Activé**.

### <a name="see-also"></a>Voir aussi
[Vidéos pratiques](videos.md)<br/>
[FAQ](faq.md)<br/>
[Essayez Dynamics 365 Layout gratuitement jusqu'à 90 jours](try-layout-free.md)
