---
author: Mamaylya
description: Attribuez un rôle d'auteur ou d'opérateur aux utilisateurs dans Microsoft Dynamics 365 Guides pour contrôler s'ils peuvent modifier et afficher des guides (rôle Auteur) ou simplement afficher des guides (rôle Opérateur).
ms.author: mamaylya
ms.date: 01/28/2020
ms.service: crm-online
ms.topic: article
title: Attribuer un rôle d'auteur ou d'opérateur à un utilisateur pour contrôler s'il peut créer un guide ou simplement l'afficher
ms.reviewer: v-brycho
ms.openlocfilehash: d1db043c83785d3fbdd5b0f667a72272aa68a515
ms.sourcegitcommit: 217d31bb34e67a6b8823d5ddac7ef8d56d054139
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/29/2020
ms.locfileid: "2995251"
---
# <a name="assign-an-author-or-operator-role-to-a-user-in-dynamics-365-guides"></a>Attribuer un rôle d'auteur ou d'opérateur à un utilisateur dans Dynamics 365 Guides

Si vous êtes administrateur Microsoft Dynamics 365 Guides, vous pouvez attribuer un rôle **Auteur** ou **Opérateur** aux utilisateurs pour limiter ce qu'ils peuvent faire dans les applications. Le tableau suivant décrit les privilèges accordés à chaque rôle.

| Rôle | Description |
|---|---|
| Auteur | Utilisez l'application du PC et l'application HoloLens pour créer, modifier et utiliser des guides. Les utilisateurs qui ont le rôle **Auteur** peuvent également renommer et désactiver les guides existants. |
| Opérateur | Utilisez l'application HoloLens pour afficher et utiliser un guide. Les utilisateurs qui ont le rôle **Opérateur** peuvent également gagner du temps en ignorant la boîte de dialogue **Sélectionner un mode** lorsqu'ils ouvrent un guide. |

> [!IMPORTANT]
> Si vous avez suivi les instructions de la rubrique [Essayer ou acheter et déployer Dynamics 365 Guides](setup.md) lorsque vous configurez Dynamics 365 Guides, tous les utilisateurs que vous avez ajoutés se voyaient automatiquement attribuer le rôle **Auteur**. Vous devez explicitement attribuer le rôle **Opérateur** à des utilisateurs spécifiques si vous ne voulez pas qu'ils aient les privilèges du rôle **Auteur**.

## <a name="prerequisites"></a>Conditions préalables

Avant de pouvoir modifier les rôles d'utilisateur, les conditions préalables suivantes doivent être réunies :

- Disposer d'une licence Dynamics 365 Guides active. Pour plus d'informations, voir [Essayer ou acheter et déployer Dynamics 365 Guides](setup.md).

- La dernière solution Dynamics 365 Guides doit être installée. Pour plus d'informations, voir [Mettre à niveau vers la solution la plus récente](upgrade.md).

- Avoir accès au centre d'administration Power Platform et disposer des privilèges d'administrateur complets.

## <a name="assign-user-roles"></a>Affecter des rôles utilisateur

1. Ouvrez le [centre d'administration Power Platform](https://admin.powerplatform.microsoft.com/environments) et connectez-vous à l'aide de vos informations d'identification d'administrateur.

2. Si la page **Environnements** n'apparaît pas, sélectionnez **Environnements** dans le volet gauche pour l'ouvrir.

3. Sélectionnez l'environnement souhaité, sélectionnez le bouton **Autres actions d'environnement** (**...**), puis sélectionnez **Paramètres**.

    ![Commande Paramètres](media/environment-settings.PNG "Commande Paramètres")

4. Sélectionnez **Utilisateurs + autorisations** pour développer la liste des options, puis sélectionnez **Utilisateurs**. Si vous êtes invité à vous connecter à Dynamics 365, assurez-vous d'utiliser vos informations d'identification d'administrateur.

    ![Utilisateurs sélectionnés](media/users-setting.PNG "Utilisateurs sélectionnés")

5. Sélectionnez un ou plusieurs utilisateurs, puis sélectionnez **Gérer les rôles** en haut de la page.

    ![Bouton Gérer les rôles](media/select-manage-roles.PNG "Bouton Gérer les rôles")

6. Dans la boîte de dialogue **Gérer les rôles d'utilisateurs**, assurez-vous que la case à cocher **Utilisateur Common Data Service** est cochée.

    ![Case à cocher Utilisateur Common Data Service](media/common-data-service-user.PNG "Case à cocher Utilisateur Common Data Service")

7. Cochez la case en regard du rôle approprié pour les utilisateurs sélectionnés, puis sélectionnez **OK**.

    ![Cases à cocher Auteur et opérateur](media/select-role.PNG "Cases à cocher Auteur et opérateur")

## <a name="see-also"></a>Voir aussi

[Ajouter des comptes d'utilisateur supplémentaires à Dynamics 365 Guides](add-users.md)<br>
[Présentation de la création d'un guide](authoring-overview.md)<br>
[Présentation de l'utilisation d'un guide](operator-overview.md)
