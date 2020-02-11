---
author: Mamaylya
description: Ajoutez des comptes d'utilisateur supplémentaires à une licence Microsoft Dynamics 365 Guides.
ms.author: mamaylya
ms.date: 01/28/2020
ms.service: crm-online
ms.topic: article
title: Ajouter des comptes d'utilisateur supplémentaires à Dynamics 365 Guides
ms.reviewer: v-brycho
ms.openlocfilehash: 4ed81272d0e0a5a6dd18f6cd08ef93aaca436352
ms.sourcegitcommit: 217d31bb34e67a6b8823d5ddac7ef8d56d054139
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/29/2020
ms.locfileid: "2995243"
---
# <a name="add-additional-user-accounts-to-dynamics-365-guides"></a>Ajouter des comptes d'utilisateur supplémentaires à Dynamics 365 Guides

Pour ajouter des utilisateurs supplémentaires à [!include[cc-microsoft](../includes/cc-microsoft.md)][!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous devez d'abord leur attribuer une licence [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] dans le Centre d'administration Microsoft 365. Ensuite, dans le centre d'administration Power Platform, configurez les rôles auxquels les utilisateurs auront accès (Auteur, Opérateur ou Administrateur).

## <a name="add-a-user-account"></a>Ajouter un compte d'utilisateur

1. Ouvrez le [Centre d'administration Microsoft 365](https://admin.microsoft.com/AdminPortal/Home).

2. Dans le volet gauche, sélectionnez **Utilisateurs**, puis **Utilisateurs actifs**.

3. Sur la page **Utilisateurs actifs**, sélectionnez **Ajouter un utilisateur**.

    ![Commande Ajouter un utilisateur](media/add-additional-user.png "Commande Ajouter un utilisateur")

4. Sur la page **Configurer les bases**, renseignez les informations pour le nouvel utilisateur. Sélectionnez **Suivant** une fois terminé.

    ![Page Configurer les bases](media/setup-basics.png "Page Configurer les bases")

    > [!NOTE]
    > Par défaut, un mot de passe est généré automatiquement pour les nouveaux comptes d'utilisateur. Les utilisateurs doivent modifier ce mot de passe la première fois qu'ils se connectent à leur nouveau compte. Pour définir un mot de passe permanent au lieu d'utiliser celui généré automatiquement, cochez l'option **Mot de passe généré automatiquement** et désactivez l'option **Demander à cet utilisateur de modifier son mot de passe lorsqu'il se connecte pour la première fois.**

5. Sur la page **Attribuer des licences de produits**, sélectionnez l'emplacement de cet utilisateur, puis sous **Licences**, activez la case à cocher en regard de **[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]**. Sélectionnez **Suivant** une fois terminé.

    ![Page Attribuer des licences de produits](media/assign-license-user.png "Page Attribuer des licences de produits")

6. Sur la page **Paramètres facultatifs**, laissez la zone **Utilisateur (aucun accès Administrateur)** sélectionnée à moins que ce nouvel utilisateur soit un administrateur. Dans ce cas, activez la case à cocher **Administrateur global**.

    ![Page Paramètres facultatifs](media/user-optional-settings.png "Page Paramètres facultatifs")

7. Pour renseigner les informations de profil du nouvel utilisateur, faites défiler et développez la section **Informations de profil**. Sélectionnez **Suivant** une fois terminé.

    ![Section Informations de profil](media/expanded-profile-info.png "Section Informations de profil")

8. Vérifiez les informations de cette dernière page. Pour apporter des modifications, sélectionnez le bouton **Modifier** sous les sections appropriées. Une fois terminé, sélectionnez **Terminé l'ajout**.

    ![Page de vérification avec les boutons Modifier](media/review-page.png "Page de vérification avec les boutons Modifier")

8. Si vous avez sélectionné l'option **Mot de passe généré automatiquement** à l'étape 4, notez le mot de passe. L'utilisateur a besoin de ce mot de passe pour se connecter.

    ![Mot de passé généré automatiquement](media/review-user-settings.png "Mot de passé généré automatiquement")

9. Sélectionnez **Fermer**.

Après avoir ajouté des comptes d'utilisateur, l'étape suivante consiste à attribuer le rôle d'utilisateur **Auteur**, **Opérateur** ou **Administrateur** pour la solution. Pour plus d'informations, voir [Affecter des rôles utilisateur](assign-role.md).

## <a name="whats-next"></a>Étapes suivantes

[Attribuer des rôles d'utilisateur](assign-role.md)
