---
author: Mamaylya
description: Installez et connectez-vous à l'application Microsoft Dynamics 365 Guides HoloLens en tant qu'opérateur.
ms.author: mamaylya
ms.date: 01/28/2020
ms.service: crm-online
ms.topic: article
title: Installer et se connecter à l'application Dynamics 365 Guides HoloLens en tant qu'opérateur
ms.reviewer: v-brycho
ms.openlocfilehash: cd8cd893059ca469d2fa06e8fd0c8e61cd699a4a
ms.sourcegitcommit: 217d31bb34e67a6b8823d5ddac7ef8d56d054139
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/29/2020
ms.locfileid: "2995256"
---
# <a name="install-and-sign-in-to-the-dynamics-365-guides-hololens-app-operators"></a>Installer et se connecter à l'application Dynamics 365 Guides HoloLens (opérateurs)

1. Vérifiez que la version 10.0.14393.0 ou ultérieure [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-hololens](../includes/pn-hololens.md)] est bien installée sur votre appareil [!include[pn-hololens](../includes/pn-hololens.md)]. Nous vous recommandons d'effectuer une mise à jour vers des versions plus récentes quand elles sont disponibles. Pour plus d'informations sur l'utilisation de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Update pour Entreprise, voir [Gérer les mises à jour vers HoloLens](https://docs.microsoft.com/HoloLens/hololens-updates).

2. Sur votre appareil [!include[pn-hololens](../includes/pn-hololens.md)], utilisez l'[écartement des doigts paume vers le haut](authoring-gestures.md) pour ouvrir le menu **Accueil**. Ouvrez ensuite l'application [!include[cc-microsoft](../includes/cc-microsoft.md)] Store, et recherchez « [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] ».

3. Sélectionnez **Installer** pour télécharger et installer l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

## <a name="sign-in-to-the-hololens-app"></a>Se connecter à l'application HoloLens

Si vous vous connectez à un tout nouvel appareil [!include[pn-hololens](../includes/pn-hololens.md)], vous serez invité à parcourir l'assistant **Installation**. Dans l'assistant **Installation**, vous pouvez soit vous connecter avec un compte existant soit en créer un nouveau, en fonction de la version de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] que vous exécutez. L'assistant **Installation** vous guide également via des étapes pour étalonner et préparer votre [!include[pn-hololens](../includes/pn-hololens.md)] en vue de son utilisation. 
 
## <a name="open-and-sign-in-to-hololens-for-the-first-time"></a>Ouvrir et se connecter à HoloLens pour la première fois

1. Sélectionnez **Toutes les applications**.

    ![Bouton Toutes les applications](media/hololens-apps.PNG "Bouton Toutes les applications")

2. Sélectionnez le bouton flèche vers le bas.

    ![Bouton flèche vers le bas](media/hololens-down-arrow.PNG "Bouton flèche vers le bas")

3. Ouvrez l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

    ![Bouton Dynamics 365 Guides](media/open-guides-application.PNG "Bouton Dynamics 365 Guides")

4. Sur la page d'**accueil**, sélectionnez **Se connecter**. 

5. Sur la page **E-mail et comptes**, sélectionnez **Compte professionnel ou scolaire**, puis sélectionnez **Continuer**.

6. Sur la page **Compte professionnel ou scolaire**, entrez les informations d'identification fournies par votre administrateur. Pour les informations d'identification, le nom d'utilisateur sera semblable à `username@domain.com`. Par exemple, si votre nom est Laurao et que vous travaillez pour la société Contoso, votre nom d'utilisateur sera `laurao@contoso.com`.

    ![Page Compte professionnel ou scolaire](media/sign-in-hololens.PNG "Page Compte professionnel ou scolaire")

7. Sélectionnez l'instance à utiliser si vous en avez plusieurs. Sélectionnez ensuite **Continuer**.

8. Dans la boîte de dialogue **Guides**, pointez du regard le cadre de sélection du guide que vous souhaitez ouvrir.

9. Dans la boîte de dialogue **Sélectionner un mode**, pointez du regard le cercle à gauche de **Opérer** jusqu'à ce qu'il soit rempli. Lorsque le cercle est rempli, l'option est sélectionnée.

    ![Boîte de dialogue Sélectionner un mode](media/select-mode-operate.png "Boîte de dialogue Sélectionner un mode")

> [!NOTE]
> Si vous êtes administrateur Dynamics 365 Guides, vous pouvez affecter le rôle **Opérateur** aux opérateurs afin qu'ils puissent afficher les guides mais pas les modifier. Si vous attribuez le rôle **Opérateur** à un utilisateur, ce dernier peut également ignorer l'étape de la boîte de dialogue **Sélectionner un mode** et ouvrir directement un guide. Pour plus d'informations, voir [Attribuer un rôle d'auteur ou d'opérateur à un utilisateur](assign-role.md).

## <a name="whats-next"></a>Étapes suivantes

[Étalonner HoloLens](operator-calibrate.md)<br>
[Mouvements pour naviguer dans l'application](operator-gestures.md)<br>
[Ancrer le guide](operator-anchor.md)<br>
[Utiliser un guide](operator-orientation.md)
