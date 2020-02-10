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
# <a name="add-additional-user-accounts-to-dynamics-365-guides"></a><span data-ttu-id="058bf-103">Ajouter des comptes d'utilisateur supplémentaires à Dynamics 365 Guides</span><span class="sxs-lookup"><span data-stu-id="058bf-103">Add additional user accounts to Dynamics 365 Guides</span></span>

<span data-ttu-id="058bf-104">Pour ajouter des utilisateurs supplémentaires à [!include[cc-microsoft](../includes/cc-microsoft.md)][!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous devez d'abord leur attribuer une licence [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] dans le Centre d'administration Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="058bf-104">To add additional users to [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], you must first assign the [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] license to them in the Microsoft 365 admin center.</span></span> <span data-ttu-id="058bf-105">Ensuite, dans le centre d'administration Power Platform, configurez les rôles auxquels les utilisateurs auront accès (Auteur, Opérateur ou Administrateur).</span><span class="sxs-lookup"><span data-stu-id="058bf-105">Then, in the Power Platform admin center, configure the roles that the users will have access to (Author, Operator, or Admin).</span></span>

## <a name="add-a-user-account"></a><span data-ttu-id="058bf-106">Ajouter un compte d'utilisateur</span><span class="sxs-lookup"><span data-stu-id="058bf-106">Add a user account</span></span>

1. <span data-ttu-id="058bf-107">Ouvrez le [Centre d'administration Microsoft 365](https://admin.microsoft.com/AdminPortal/Home).</span><span class="sxs-lookup"><span data-stu-id="058bf-107">Open the [Microsoft 365 admin center](https://admin.microsoft.com/AdminPortal/Home).</span></span>

2. <span data-ttu-id="058bf-108">Dans le volet gauche, sélectionnez **Utilisateurs**, puis **Utilisateurs actifs**.</span><span class="sxs-lookup"><span data-stu-id="058bf-108">In the left pane, select **Users**, and then select **Active users**.</span></span>

3. <span data-ttu-id="058bf-109">Sur la page **Utilisateurs actifs**, sélectionnez **Ajouter un utilisateur**.</span><span class="sxs-lookup"><span data-stu-id="058bf-109">On the **Active users** page, select **Add a user**.</span></span>

    <span data-ttu-id="058bf-110">![Commande Ajouter un utilisateur](media/add-additional-user.png "Commande Ajouter un utilisateur")</span><span class="sxs-lookup"><span data-stu-id="058bf-110">![Add a user command](media/add-additional-user.png "Add a user command")</span></span>

4. <span data-ttu-id="058bf-111">Sur la page **Configurer les bases**, renseignez les informations pour le nouvel utilisateur.</span><span class="sxs-lookup"><span data-stu-id="058bf-111">On the **Set up the basics** page, fill in the information for the new user.</span></span> <span data-ttu-id="058bf-112">Sélectionnez **Suivant** une fois terminé.</span><span class="sxs-lookup"><span data-stu-id="058bf-112">When you've finished, select **Next**.</span></span>

    <span data-ttu-id="058bf-113">![Page Configurer les bases](media/setup-basics.png "Page Configurer les bases")</span><span class="sxs-lookup"><span data-stu-id="058bf-113">![Set up the basics page](media/setup-basics.png "Set up the basics page")</span></span>

    > [!NOTE]
    > <span data-ttu-id="058bf-114">Par défaut, un mot de passe est généré automatiquement pour les nouveaux comptes d'utilisateur.</span><span class="sxs-lookup"><span data-stu-id="058bf-114">By default, a password is automatically generated for new user accounts.</span></span> <span data-ttu-id="058bf-115">Les utilisateurs doivent modifier ce mot de passe la première fois qu'ils se connectent à leur nouveau compte.</span><span class="sxs-lookup"><span data-stu-id="058bf-115">Users must change this password the first time that they sign in by using their new account.</span></span> <span data-ttu-id="058bf-116">Pour définir un mot de passe permanent au lieu d'utiliser celui généré automatiquement, cochez l'option **Mot de passe généré automatiquement** et désactivez l'option **Demander à cet utilisateur de modifier son mot de passe lorsqu'il se connecte pour la première fois.**</span><span class="sxs-lookup"><span data-stu-id="058bf-116">If you want to set a permanent password instead of using an automatically generated password, select the **Let me create the password** option, and clear the **Require this user to change their password when they first sign in** check box.</span></span>

5. <span data-ttu-id="058bf-117">Sur la page **Attribuer des licences de produits**, sélectionnez l'emplacement de cet utilisateur, puis sous **Licences**, activez la case à cocher en regard de **[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]**.</span><span class="sxs-lookup"><span data-stu-id="058bf-117">On the **Assign product licenses** page, select the location for the user, and then, under **Licenses**, select the **[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]** check box.</span></span> <span data-ttu-id="058bf-118">Sélectionnez **Suivant** une fois terminé.</span><span class="sxs-lookup"><span data-stu-id="058bf-118">When you've finished, select **Next**.</span></span>

    <span data-ttu-id="058bf-119">![Page Attribuer des licences de produits](media/assign-license-user.png "Page Attribuer des licences de produits")</span><span class="sxs-lookup"><span data-stu-id="058bf-119">![Assign product licenses page](media/assign-license-user.png "Assign product licenses page")</span></span>

6. <span data-ttu-id="058bf-120">Sur la page **Paramètres facultatifs**, laissez la zone **Utilisateur (aucun accès Administrateur)** sélectionnée à moins que ce nouvel utilisateur soit un administrateur. Dans ce cas, activez la case à cocher **Administrateur global**.</span><span class="sxs-lookup"><span data-stu-id="058bf-120">On the **Optional settings** page, leave the **User (no administrator access)** check box selected unless the user will be an admin. In that case, select the **Global administrator** check box.</span></span>

    <span data-ttu-id="058bf-121">![Page Paramètres facultatifs](media/user-optional-settings.png "Page Paramètres facultatifs")</span><span class="sxs-lookup"><span data-stu-id="058bf-121">![Optional settings page](media/user-optional-settings.png "Optional settings page")</span></span>

7. <span data-ttu-id="058bf-122">Pour renseigner les informations de profil du nouvel utilisateur, faites défiler et développez la section **Informations de profil**.</span><span class="sxs-lookup"><span data-stu-id="058bf-122">Scroll down, expand the **Profile info** section, and fill in the user's profile information.</span></span> <span data-ttu-id="058bf-123">Sélectionnez **Suivant** une fois terminé.</span><span class="sxs-lookup"><span data-stu-id="058bf-123">When you've finished, select **Next**.</span></span>

    <span data-ttu-id="058bf-124">![Section Informations de profil](media/expanded-profile-info.png "Section Informations de profil")</span><span class="sxs-lookup"><span data-stu-id="058bf-124">![Profile info section](media/expanded-profile-info.png "Profile info section")</span></span>

8. <span data-ttu-id="058bf-125">Vérifiez les informations de cette dernière page.</span><span class="sxs-lookup"><span data-stu-id="058bf-125">Review the information on the last page.</span></span> <span data-ttu-id="058bf-126">Pour apporter des modifications, sélectionnez le bouton **Modifier** sous les sections appropriées.</span><span class="sxs-lookup"><span data-stu-id="058bf-126">To make changes, select the **Edit** button below the relevant sections.</span></span> <span data-ttu-id="058bf-127">Une fois terminé, sélectionnez **Terminé l'ajout**.</span><span class="sxs-lookup"><span data-stu-id="058bf-127">When you've finished, select **Finish Adding**.</span></span>

    <span data-ttu-id="058bf-128">![Page de vérification avec les boutons Modifier](media/review-page.png "Page de vérification avec les boutons Modifier")</span><span class="sxs-lookup"><span data-stu-id="058bf-128">![Review page with Edit buttons](media/review-page.png "Review page with Edit buttons")</span></span>

8. <span data-ttu-id="058bf-129">Si vous avez sélectionné l'option **Mot de passe généré automatiquement** à l'étape 4, notez le mot de passe.</span><span class="sxs-lookup"><span data-stu-id="058bf-129">If you selected the **Auto-generate password** option in step 4, make a note of the password.</span></span> <span data-ttu-id="058bf-130">L'utilisateur a besoin de ce mot de passe pour se connecter.</span><span class="sxs-lookup"><span data-stu-id="058bf-130">The user will need this password to sign in.</span></span>

    <span data-ttu-id="058bf-131">![Mot de passé généré automatiquement](media/review-user-settings.png "Mot de passé généré automatiquement")</span><span class="sxs-lookup"><span data-stu-id="058bf-131">![Automatically generated password](media/review-user-settings.png "Automatically generated password")</span></span>

9. <span data-ttu-id="058bf-132">Sélectionnez **Fermer**.</span><span class="sxs-lookup"><span data-stu-id="058bf-132">Select **Close**.</span></span>

<span data-ttu-id="058bf-133">Après avoir ajouté des comptes d'utilisateur, l'étape suivante consiste à attribuer le rôle d'utilisateur **Auteur**, **Opérateur** ou **Administrateur** pour la solution.</span><span class="sxs-lookup"><span data-stu-id="058bf-133">After you add user accounts, the next step is to assign the **Author**, **Operator**, or **Admin** user role for the solution.</span></span> <span data-ttu-id="058bf-134">Pour plus d'informations, voir [Affecter des rôles utilisateur](assign-role.md).</span><span class="sxs-lookup"><span data-stu-id="058bf-134">For more information, see [Assign user roles](assign-role.md).</span></span>

## <a name="whats-next"></a><span data-ttu-id="058bf-135">Étapes suivantes</span><span class="sxs-lookup"><span data-stu-id="058bf-135">What's next?</span></span>

[<span data-ttu-id="058bf-136">Attribuer des rôles d'utilisateur</span><span class="sxs-lookup"><span data-stu-id="058bf-136">Assign user roles</span></span>](assign-role.md)
