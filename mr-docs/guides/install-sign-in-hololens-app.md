---
author: Mamaylya
description: Découvrez comment installer et vous connecter à l'application Microsoft Dynamics 365 Guides HoloLens et étalonner votre HoloLens.
ms.author: mamaylya
ms.date: 01/28/2020
ms.service: crm-online
ms.topic: article
title: Installer et se connecter à l'application Dynamics 365 Guides HoloLens
ms.reviewer: v-brycho
ms.openlocfilehash: 9426a0f21c150f37de84a16ac20ab9688d1b5741
ms.sourcegitcommit: 217d31bb34e67a6b8823d5ddac7ef8d56d054139
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/29/2020
ms.locfileid: "2995245"
---
# <a name="install-and-sign-in-to-the-dynamics-365-guides-hololens-app"></a>Installer et se connecter à l'application Dynamics 365 Guides HoloLens

Si vous n'avez pas encore installé l'application [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-hololens](../includes/pn-hololens.md)] sur votre appareil [!include[pn-hololens](../includes/pn-hololens.md)] (ou si elle n'a pas encore été installée pour vous), vous pouvez l'installer à partir du [!include[cc-microsoft](../includes/cc-microsoft.md)] Store pour les consommateurs.

> [!NOTE]
> Vous devez disposer d'une licence pour installer l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)][!include[pn-hololens](../includes/pn-hololens.md)]. Vous pouvez également vous inscrire à une évaluation gratuite. Pour plus d'informations, voir [Présentation de la configuration](setup.md).

## <a name="install-the-app"></a>Installer l'application

1. Vérifiez que la version 10.0.14393.0 ou ultérieure [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-hololens](../includes/pn-hololens.md)] est bien installée sur votre appareil [!include[pn-hololens](../includes/pn-hololens.md)]. Nous vous recommandons d'effectuer une mise à jour vers des versions plus récentes quand elles sont disponibles. Pour plus d'informations sur l'utilisation de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Update pour Entreprise, voir [Gérer les mises à jour vers HoloLens](https://docs.microsoft.com/HoloLens/hololens-updates).

2. Sur votre [!include[pn-hololens](../includes/pn-hololens.md)], utilisez l'[écartement des doigts paume vers le haut](authoring-gestures.md) pour ouvrir le menu **Accueil**. Ouvrez ensuite [!include[cc-microsoft](../includes/cc-microsoft.md)] Store, et recherchez « [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] ».

3. Sélectionnez **Installer** pour télécharger et installer l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

## <a name="sign-in"></a>Se connecter

Si vous vous connectez à un tout nouvel appareil [!include[pn-hololens](../includes/pn-hololens.md)], vous serez invité à parcourir l'assistant **Installation**. Dans l'assistant **Installation**, vous pouvez soit vous connecter avec un compte existant soit en créer un nouveau, en fonction de la version de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] que vous exécutez. L'assistant **Installation** vous guide également via des étapes pour étalonner et préparer votre [!include[pn-hololens](../includes/pn-hololens.md)] en vue de son utilisation.

## <a name="calibrate-your-hololens"></a>Étalonner HoloLens

Pour afficher des hologrammes dans les emplacements corrects, vous devez définir la distance interpupillaire (DIP). Cette étape doit être effectuée pour chaque utilisateur [!include[pn-hololens](../includes/pn-hololens.md)], qu'il soit auteur ou opérateur. Dans un contexte industriel où les hologrammes servent à diriger l'opérateur dans l'exécution de ses tâches, il est essentiel que les hologrammes soient correctement alignés. Cela risque sinon de provoquer de la confusion chez l'opérateur et d'engendrer des dommages onéreux.

Voici ce qui va se passer si vous ne configurez pas le DIP pour chaque utilisateur :

- Les hologrammes seront décalés de 1 à 2 cm.

- Les hologrammes vont s'afficher comme s'ils étaient enfoncés ou comme s'ils flottaient au-dessus des surfaces sur lesquelles ils reposent.

- Les hologrammes ne seront pas stables. Vous remarquerez qu'ils bougent quand vous vous déplacez.

> [!IMPORTANT]
> Il est particulièrement important que les auteurs s'assurent que leur DIP est définie correctement. Sinon, tous les opérateurs qui utilisent le guide verront des hologrammes mal alignés.

Pour définir votre DIP, utilisez l'application d'étalonnage incluse dans [!include[pn-hololens](../includes/pn-hololens.md)] et procédez comme suit :

1. Écartez les doigts paume vers le haut pour ouvrir le menu **Démarrer**.

2. Cliquez dans l'air sur **Étalonnage** pour commencer à étalonner votre [!include[pn-hololens](../includes/pn-hololens.md)].

    ![Bouton d'étalonnage](media/hololens-calibration.PNG "Bouton d'étalonnage")

3. Suivez les instructions affichées dans [!include[pn-hololens](../includes/pn-hololens.md)].

Tous les utilisateurs doivent effectuer cet étalonnage après s'être connectés à l'appareil. Si [!include[pn-hololens](../includes/pn-hololens.md)] exécute [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Holographic for Business edition, le paramètre DIP sera enregistré sur l'appareil. Par conséquent, lorsque vous vous connectez au même [!include[pn-hololens](../includes/pn-hololens.md)], vos paramètres DIP sont automatiquement appliqués, même après avoir changé d'utilisateur. Vous n'avez pas besoin d'étalonner à nouveau l'appareil. Toutefois, si [!include[pn-hololens](../includes/pn-hololens.md)] exécute l'édition [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Holographic, les paramètres utilisateur ne sont pas enregistrés, car cette version de votre système d'exploitation est conçue pour un seul utilisateur. Chaque fois que vous changez d'utilisateur, vous devez donc étalonner à nouveau l'appareil.

Pour déterminer la version utilisée par votre système d'exploitation dans [!include[pn-hololens](../includes/pn-hololens.md)], procédez comme suit :

1. Écartez les doigts paume vers le haut pour ouvrir le menu **Démarrer**.

2. Cliquez dans l'air sur **Paramètres \> Système**.

3. Cliquez dans l'air sur **À propos**.

## <a name="open-and-sign-in-for-the-first-time"></a>Ouvrir et se connecter pour la première fois

Après avoir vérifié que [!include[pn-hololens](../includes/pn-hololens.md)] est correctement étalonné, vous pouvez ouvrir l'application [!include[pn-hololens](../includes/pn-hololens.md)].

> [!NOTE]
> Si vous êtes administrateur [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous pouvez attribuer les rôles **Auteur** et **Opérateur** pour limiter les fonctionnalités disponibles. Pour plus d'informations, voir [Attribuer un rôle d'auteur ou d'opérateur à un utilisateur](assign-role.md).

1. Sélectionnez **Toutes les applications**.

    ![Bouton Toutes les applications](media/hololens-apps.PNG "Bouton Toutes les applications")

2. Sélectionnez le bouton flèche vers le bas.

    ![Bouton flèche vers le bas](media/hololens-down-arrow.PNG "Bouton flèche vers le bas")

3. Ouvrez l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

    ![Bouton Dynamics 365 Guides](media/open-guides-application.PNG "Bouton Dynamics 365 Guides")

4. Sur la page d'**accueil**, sélectionnez **Se connecter**.

5. Sur la page **E-mail et comptes**, sélectionnez **Compte professionnel ou scolaire**, puis sélectionnez **Continuer**.

6. Sur la page **Compte professionnel ou scolaire**, entrez les informations d'identification que vous avez créées lors de l'abonnement d’essai ou celles fournies par l'administrateur qui a installé l'application fournie.

    ![Page Compte professionnel ou scolaire](media/sign-in-hololens.PNG "Page Compte professionnel ou scolaire")

7. Sélectionnez l'instance à utiliser si vous en avez plusieurs. Sélectionnez ensuite **Continuer**.

8. Sur la page **Sélectionner un guide**, pointez du regard le guide que vous souhaitez ouvrir jusqu'à ce que le cercle se remplisse. Lorsque le cercle est rempli, le guide est sélectionné.

    ![Page Sélectionner un guide](media/select-guide.png "Page Sélectionner un guide")

9. Dans la boîte de dialogue **Sélectionner un mode**, pointez du regard le cercle à gauche d'**Auteur** pour le sélectionner.

    ![Boîte de dialogue Sélectionner un mode](media/select-mode.png "Boîte de dialogue Sélectionner un mode")

> [!TIP]
> [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] contient un guide illustratif que vous pouvez utiliser pour obtenir des idées pour vos propres guides. Découvrez-le !
>
> ![Guide illustratif](media/example-guide-hololens.png "Guide illustratif")

## <a name="whats-next"></a>Étapes suivantes

[Ancrer le guide](hololens-app-anchor.md)<br>
[Placer des hologrammes, ajouter des styles, etc.](hololens-app-orientation.md)
