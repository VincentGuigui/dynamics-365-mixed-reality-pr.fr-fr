---
author: Mamaylya
description: Utilisez l'application du PC dans Microsoft Dynamics 365 Guides comme première étape de la création d'un guide.
ms.author: mamaylya
ms.date: 01/28/2020
ms.service: crm-online
ms.topic: article
title: Créez un guide à l'aide de l'application du PC Dynamics 365 Guides.
ms.reviewer: v-brycho
ms.openlocfilehash: 88d727b8e209a23e0d84ca4d6e913db3f6e3638f
ms.sourcegitcommit: 217d31bb34e67a6b8823d5ddac7ef8d56d054139
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/29/2020
ms.locfileid: "2995252"
---
# <a name="create-a-guide-by-using-the-dynamics-365-guides-pc-app"></a><span data-ttu-id="ea199-103">Créez un guide à l'aide de l'application du PC Dynamics 365 Guides.</span><span class="sxs-lookup"><span data-stu-id="ea199-103">Create a guide by using the Dynamics 365 Guides PC app</span></span>

1. <span data-ttu-id="ea199-104">[Ouvrez l'application du PC Microsoft Dynamics 365 Guides](install-sign-in-pc-app.md).</span><span class="sxs-lookup"><span data-stu-id="ea199-104">[Open the Microsoft Dynamics 365 Guides PC app](install-sign-in-pc-app.md).</span></span>

2. <span data-ttu-id="ea199-105">Sélectionnez **Créer un nouveau guide**.</span><span class="sxs-lookup"><span data-stu-id="ea199-105">Select **Create new guide**.</span></span>

    <span data-ttu-id="ea199-106">![Bouton Créer un nouveau guide](media/create-guide.PNG "Bouton Créer un nouveau guide")</span><span class="sxs-lookup"><span data-stu-id="ea199-106">![Create new guide button](media/create-guide.PNG "Create new guide button")</span></span>

3. <span data-ttu-id="ea199-107">Saisissez un nom pour le guide, puis sélectionnez **Créer**.</span><span class="sxs-lookup"><span data-stu-id="ea199-107">Enter a name for the guide, and then select **Create**.</span></span>

    > [!TIP]
    > <span data-ttu-id="ea199-108">Si vous voulez créer plusieurs versions du guide, vous pouvez ajouter **\_v2**, **\_v3** etc. dans le nom.</span><span class="sxs-lookup"><span data-stu-id="ea199-108">If you're planning to create multiple versions of the guide, you might want to add **\_v2**, **\_v3**, and so on, as part of the name.</span></span> <span data-ttu-id="ea199-109">Vous pouvez aussi utiliser la commande **Enregistrer une copie** du menu **Fichier** si vous créez plusieurs versions du même guide.</span><span class="sxs-lookup"><span data-stu-id="ea199-109">You can also use the **Save a Copy** command on the **File** menu if you're creating multiple versions of the same guide.</span></span>

    <span data-ttu-id="ea199-110">![Nommer le guide](media/name-guide.PNG "Nommer le guide")</span><span class="sxs-lookup"><span data-stu-id="ea199-110">![Naming the guide](media/name-guide.PNG "Naming the guide")</span></span>

    > [!NOTE]
    > <span data-ttu-id="ea199-111">Lorsque vous créez un guide à l'aide de l'application du PC, un fichier de données JSON est automatiquement créé dans Common Data Service.</span><span class="sxs-lookup"><span data-stu-id="ea199-111">When you create a guide by using the PC app, a JavaScript Object Notation (JSON) data file is automatically created in Common Data Service.</span></span> <span data-ttu-id="ea199-112">Ce fichier est destiné à une utilisation interne uniquement.</span><span class="sxs-lookup"><span data-stu-id="ea199-112">This file is for internal use only.</span></span> <span data-ttu-id="ea199-113">Il est déconseillé de créer des fonctionnalités au-dessus de ce fichier car elles peuvent changer avec le temps.</span><span class="sxs-lookup"><span data-stu-id="ea199-113">We don't recommend that you build functionality on top of this file, because it might change over time.</span></span>

<span data-ttu-id="ea199-114">Après avoir créé votre guide, la page **Plan** apparaît.</span><span class="sxs-lookup"><span data-stu-id="ea199-114">After you create your guide, the **Outline** page appears.</span></span> <span data-ttu-id="ea199-115">Pour en savoir plus sur la façon de travailler sur la page **Plan**, voir [Structurer votre guide dans la page Plan](structure-guide.md).</span><span class="sxs-lookup"><span data-stu-id="ea199-115">To learn more about how to work on the **Outline** page, see [Structure your guide in the Outline page](structure-guide.md).</span></span>

## <a name="how-changes-are-synced-between-the-pc-app-and-the-hololens-app"></a><span data-ttu-id="ea199-116">Manière dont les modifications sont synchronisées entre l'application du PC et l'application HoloLens</span><span class="sxs-lookup"><span data-stu-id="ea199-116">How changes are synced between the PC app and the HoloLens app</span></span>

<span data-ttu-id="ea199-117">L'application de création sur PC et l'application [!include[pn-hololens](../includes/pn-hololens.md)] sont connectées via le cloud, où les fichiers et le contenu [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] sont stockés.</span><span class="sxs-lookup"><span data-stu-id="ea199-117">The PC authoring app and the [!include[pn-hololens](../includes/pn-hololens.md)] app are connected through the cloud, where your [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] files and content are stored.</span></span>

<span data-ttu-id="ea199-118">Lorsque vous créez un guide, les modifications sont enregistrées sur l'ordinateur et sur [!include[pn-hololens](../includes/pn-hololens.md)].</span><span class="sxs-lookup"><span data-stu-id="ea199-118">When you author a guide, all changes are saved on both the computer and the [!include[pn-hololens](../includes/pn-hololens.md)].</span></span> <span data-ttu-id="ea199-119">Il est ainsi très facile de passer d'un appareil à un autre.</span><span class="sxs-lookup"><span data-stu-id="ea199-119">Therefore, it's easy to switch between devices.</span></span> <span data-ttu-id="ea199-120">L'enregistrement automatique permet de vérifier les nouvelles modifications toutes les quatre secondes.</span><span class="sxs-lookup"><span data-stu-id="ea199-120">Autosave checks for changes every four seconds.</span></span>

<span data-ttu-id="ea199-121">Vous devez être en ligne pour utiliser [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span><span class="sxs-lookup"><span data-stu-id="ea199-121">You must be online to use [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].</span></span>

> [!NOTE]
> <span data-ttu-id="ea199-122">Lorsque vous basculez d'un appareil à l'autre, il est préférable de fermer le guide pour ne pas perdre votre travail.</span><span class="sxs-lookup"><span data-stu-id="ea199-122">When you switch from one device to the other, it's a good idea to close the guide, to make sure that you don't lose any work.</span></span>

## <a name="whats-next"></a><span data-ttu-id="ea199-123">Étapes suivantes</span><span class="sxs-lookup"><span data-stu-id="ea199-123">What's next?</span></span>

[<span data-ttu-id="ea199-124">Ancrer votre guide dans le monde réel</span><span class="sxs-lookup"><span data-stu-id="ea199-124">Anchor your guide to the real world</span></span>](anchor.md)<br>
[<span data-ttu-id="ea199-125">Structurer votre guide dans la page Plan</span><span class="sxs-lookup"><span data-stu-id="ea199-125">Structure your guide in the Outline page</span></span>](structure-guide.md)<br>
[<span data-ttu-id="ea199-126">Créer des étapes et ajouter du contenu 3D ou des supports 2D</span><span class="sxs-lookup"><span data-stu-id="ea199-126">Create steps and add 3D content or 2D media</span></span>](create-steps-assign-media.md)<br>
[<span data-ttu-id="ea199-127">En savoir plus sur les raccourcis clavier</span><span class="sxs-lookup"><span data-stu-id="ea199-127">Learn about keyboard shortcuts</span></span>](keyboard-shortcuts-pc-app.md)
