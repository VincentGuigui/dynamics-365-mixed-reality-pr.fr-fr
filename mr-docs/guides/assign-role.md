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
# <a name="assign-an-author-or-operator-role-to-a-user-in-dynamics-365-guides"></a><span data-ttu-id="f3ae5-103">Attribuer un rôle d'auteur ou d'opérateur à un utilisateur dans Dynamics 365 Guides</span><span class="sxs-lookup"><span data-stu-id="f3ae5-103">Assign an Author or Operator role to a user in Dynamics 365 Guides</span></span>

<span data-ttu-id="f3ae5-104">Si vous êtes administrateur Microsoft Dynamics 365 Guides, vous pouvez attribuer un rôle **Auteur** ou **Opérateur** aux utilisateurs pour limiter ce qu'ils peuvent faire dans les applications.</span><span class="sxs-lookup"><span data-stu-id="f3ae5-104">If you're a Microsoft Dynamics 365 Guides admin, you can assign an **Author** or **Operator** role to users to limit what they can do in the apps.</span></span> <span data-ttu-id="f3ae5-105">Le tableau suivant décrit les privilèges accordés à chaque rôle.</span><span class="sxs-lookup"><span data-stu-id="f3ae5-105">The following table describes the privileges that each role grants.</span></span>

| <span data-ttu-id="f3ae5-106">Rôle</span><span class="sxs-lookup"><span data-stu-id="f3ae5-106">Role</span></span> | <span data-ttu-id="f3ae5-107">Description</span><span class="sxs-lookup"><span data-stu-id="f3ae5-107">Description</span></span> |
|---|---|
| <span data-ttu-id="f3ae5-108">Auteur</span><span class="sxs-lookup"><span data-stu-id="f3ae5-108">Author</span></span> | <span data-ttu-id="f3ae5-109">Utilisez l'application du PC et l'application HoloLens pour créer, modifier et utiliser des guides.</span><span class="sxs-lookup"><span data-stu-id="f3ae5-109">Use the PC app and HoloLens app to create, edit, and operate guides.</span></span> <span data-ttu-id="f3ae5-110">Les utilisateurs qui ont le rôle **Auteur** peuvent également renommer et désactiver les guides existants.</span><span class="sxs-lookup"><span data-stu-id="f3ae5-110">Users who have the **Author** role can also rename and inactivate existing guides.</span></span> |
| <span data-ttu-id="f3ae5-111">Opérateur</span><span class="sxs-lookup"><span data-stu-id="f3ae5-111">Operator</span></span> | <span data-ttu-id="f3ae5-112">Utilisez l'application HoloLens pour afficher et utiliser un guide.</span><span class="sxs-lookup"><span data-stu-id="f3ae5-112">Use the HoloLens app to view and operate a guide.</span></span> <span data-ttu-id="f3ae5-113">Les utilisateurs qui ont le rôle **Opérateur** peuvent également gagner du temps en ignorant la boîte de dialogue **Sélectionner un mode** lorsqu'ils ouvrent un guide.</span><span class="sxs-lookup"><span data-stu-id="f3ae5-113">Users who have the **Operator** role can also save time by skipping the **Select Mode** dialog box when they open a guide.</span></span> |

> [!IMPORTANT]
> <span data-ttu-id="f3ae5-114">Si vous avez suivi les instructions de la rubrique [Essayer ou acheter et déployer Dynamics 365 Guides](setup.md) lorsque vous configurez Dynamics 365 Guides, tous les utilisateurs que vous avez ajoutés se voyaient automatiquement attribuer le rôle **Auteur**.</span><span class="sxs-lookup"><span data-stu-id="f3ae5-114">If you followed the instructions in the [Try or buy, and deploy Dynamics 365 Guides](setup.md) topic when you set up Dynamics 365 Guides, any users that you added were automatically assigned the **Author** role.</span></span> <span data-ttu-id="f3ae5-115">Vous devez explicitement attribuer le rôle **Opérateur** à des utilisateurs spécifiques si vous ne voulez pas qu'ils aient les privilèges du rôle **Auteur**.</span><span class="sxs-lookup"><span data-stu-id="f3ae5-115">You must explicitly assign the **Operator** role to specific users if you don't want them to have **Author** role privileges.</span></span>

## <a name="prerequisites"></a><span data-ttu-id="f3ae5-116">Conditions préalables</span><span class="sxs-lookup"><span data-stu-id="f3ae5-116">Prerequisites</span></span>

<span data-ttu-id="f3ae5-117">Avant de pouvoir modifier les rôles d'utilisateur, les conditions préalables suivantes doivent être réunies :</span><span class="sxs-lookup"><span data-stu-id="f3ae5-117">Before you can modify user roles, the following prerequisites must be in place:</span></span>

- <span data-ttu-id="f3ae5-118">Disposer d'une licence Dynamics 365 Guides active.</span><span class="sxs-lookup"><span data-stu-id="f3ae5-118">You have an active Dynamics 365 Guides license.</span></span> <span data-ttu-id="f3ae5-119">Pour plus d'informations, voir [Essayer ou acheter et déployer Dynamics 365 Guides](setup.md).</span><span class="sxs-lookup"><span data-stu-id="f3ae5-119">For more information, see [Try or buy, and deploy Dynamics 365 Guides](setup.md).</span></span>

- <span data-ttu-id="f3ae5-120">La dernière solution Dynamics 365 Guides doit être installée.</span><span class="sxs-lookup"><span data-stu-id="f3ae5-120">The latest Dynamics 365 Guides solution is installed.</span></span> <span data-ttu-id="f3ae5-121">Pour plus d'informations, voir [Mettre à niveau vers la solution la plus récente](upgrade.md).</span><span class="sxs-lookup"><span data-stu-id="f3ae5-121">For more information, see [Upgrade to the latest solution](upgrade.md).</span></span>

- <span data-ttu-id="f3ae5-122">Avoir accès au centre d'administration Power Platform et disposer des privilèges d'administrateur complets.</span><span class="sxs-lookup"><span data-stu-id="f3ae5-122">You have access to the Power Platform admin center and have full admin privileges.</span></span>

## <a name="assign-user-roles"></a><span data-ttu-id="f3ae5-123">Affecter des rôles utilisateur</span><span class="sxs-lookup"><span data-stu-id="f3ae5-123">Assign user roles</span></span>

1. <span data-ttu-id="f3ae5-124">Ouvrez le [centre d'administration Power Platform](https://admin.powerplatform.microsoft.com/environments) et connectez-vous à l'aide de vos informations d'identification d'administrateur.</span><span class="sxs-lookup"><span data-stu-id="f3ae5-124">Open the [Power Platform admin center](https://admin.powerplatform.microsoft.com/environments), and sign in by using your admin credentials.</span></span>

2. <span data-ttu-id="f3ae5-125">Si la page **Environnements** n'apparaît pas, sélectionnez **Environnements** dans le volet gauche pour l'ouvrir.</span><span class="sxs-lookup"><span data-stu-id="f3ae5-125">If the **Environments** page doesn't appear, select **Environments** in the left pane to open it.</span></span>

3. <span data-ttu-id="f3ae5-126">Sélectionnez l'environnement souhaité, sélectionnez le bouton **Autres actions d'environnement** (**...**), puis sélectionnez **Paramètres**.</span><span class="sxs-lookup"><span data-stu-id="f3ae5-126">Select the environment that you want to work with, select the **More environment actions** (**...**) button, and then select **Settings**.</span></span>

    <span data-ttu-id="f3ae5-127">![Commande Paramètres](media/environment-settings.PNG "Commande Paramètres")</span><span class="sxs-lookup"><span data-stu-id="f3ae5-127">![Settings command](media/environment-settings.PNG "Settings command")</span></span>

4. <span data-ttu-id="f3ae5-128">Sélectionnez **Utilisateurs + autorisations** pour développer la liste des options, puis sélectionnez **Utilisateurs**.</span><span class="sxs-lookup"><span data-stu-id="f3ae5-128">Select **Users + permissions** to expand the list of options, and then select **Users**.</span></span> <span data-ttu-id="f3ae5-129">Si vous êtes invité à vous connecter à Dynamics 365, assurez-vous d'utiliser vos informations d'identification d'administrateur.</span><span class="sxs-lookup"><span data-stu-id="f3ae5-129">If you're prompted to sign in to Dynamics 365, be sure to use your admin credentials.</span></span>

    <span data-ttu-id="f3ae5-130">![Utilisateurs sélectionnés](media/users-setting.PNG "Utilisateurs sélectionnés")</span><span class="sxs-lookup"><span data-stu-id="f3ae5-130">![Users selected](media/users-setting.PNG "Users selected")</span></span>

5. <span data-ttu-id="f3ae5-131">Sélectionnez un ou plusieurs utilisateurs, puis sélectionnez **Gérer les rôles** en haut de la page.</span><span class="sxs-lookup"><span data-stu-id="f3ae5-131">Select one or more users, and then select **Manage Roles** at the top of the page.</span></span>

    <span data-ttu-id="f3ae5-132">![Bouton Gérer les rôles](media/select-manage-roles.PNG "Bouton Gérer les rôles")</span><span class="sxs-lookup"><span data-stu-id="f3ae5-132">![Manage Roles button](media/select-manage-roles.PNG "Manage Roles button")</span></span>

6. <span data-ttu-id="f3ae5-133">Dans la boîte de dialogue **Gérer les rôles d'utilisateurs**, assurez-vous que la case à cocher **Utilisateur Common Data Service** est cochée.</span><span class="sxs-lookup"><span data-stu-id="f3ae5-133">In the **Manage User Roles** dialog box, make sure that the **Common Data Service User** check box is selected.</span></span>

    <span data-ttu-id="f3ae5-134">![Case à cocher Utilisateur Common Data Service](media/common-data-service-user.PNG "Case à cocher Utilisateur Common Data Service")</span><span class="sxs-lookup"><span data-stu-id="f3ae5-134">![Common Data Service User check box](media/common-data-service-user.PNG "Common Data Service User check box")</span></span>

7. <span data-ttu-id="f3ae5-135">Cochez la case en regard du rôle approprié pour les utilisateurs sélectionnés, puis sélectionnez **OK**.</span><span class="sxs-lookup"><span data-stu-id="f3ae5-135">Select the check box for the appropriate role for the selected users, and then select **OK**.</span></span>

    <span data-ttu-id="f3ae5-136">![Cases à cocher Auteur et opérateur](media/select-role.PNG "Cases à cocher Auteur et opérateur")</span><span class="sxs-lookup"><span data-stu-id="f3ae5-136">![Author and Operator check boxes](media/select-role.PNG "Author and Operator check boxes")</span></span>

## <a name="see-also"></a><span data-ttu-id="f3ae5-137">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="f3ae5-137">See also</span></span>

[<span data-ttu-id="f3ae5-138">Ajouter des comptes d'utilisateur supplémentaires à Dynamics 365 Guides</span><span class="sxs-lookup"><span data-stu-id="f3ae5-138">Add additional user accounts to Dynamics 365 Guides</span></span>](add-users.md)<br>
[<span data-ttu-id="f3ae5-139">Présentation de la création d'un guide</span><span class="sxs-lookup"><span data-stu-id="f3ae5-139">Overview of authoring a guide</span></span>](authoring-overview.md)<br>
[<span data-ttu-id="f3ae5-140">Présentation de l'utilisation d'un guide</span><span class="sxs-lookup"><span data-stu-id="f3ae5-140">Overview of operating a guide</span></span>](operator-overview.md)
