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
# <a name="create-a-guide-by-using-the-dynamics-365-guides-pc-app"></a>Créez un guide à l'aide de l'application du PC Dynamics 365 Guides.

1. [Ouvrez l'application du PC Microsoft Dynamics 365 Guides](install-sign-in-pc-app.md).

2. Sélectionnez **Créer un nouveau guide**.

    ![Bouton Créer un nouveau guide](media/create-guide.PNG "Bouton Créer un nouveau guide")

3. Saisissez un nom pour le guide, puis sélectionnez **Créer**.

    > [!TIP]
    > Si vous voulez créer plusieurs versions du guide, vous pouvez ajouter **\_v2**, **\_v3** etc. dans le nom. Vous pouvez aussi utiliser la commande **Enregistrer une copie** du menu **Fichier** si vous créez plusieurs versions du même guide.

    ![Nommer le guide](media/name-guide.PNG "Nommer le guide")

    > [!NOTE]
    > Lorsque vous créez un guide à l'aide de l'application du PC, un fichier de données JSON est automatiquement créé dans Common Data Service. Ce fichier est destiné à une utilisation interne uniquement. Il est déconseillé de créer des fonctionnalités au-dessus de ce fichier car elles peuvent changer avec le temps.

Après avoir créé votre guide, la page **Plan** apparaît. Pour en savoir plus sur la façon de travailler sur la page **Plan**, voir [Structurer votre guide dans la page Plan](structure-guide.md).

## <a name="how-changes-are-synced-between-the-pc-app-and-the-hololens-app"></a>Manière dont les modifications sont synchronisées entre l'application du PC et l'application HoloLens

L'application de création sur PC et l'application [!include[pn-hololens](../includes/pn-hololens.md)] sont connectées via le cloud, où les fichiers et le contenu [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] sont stockés.

Lorsque vous créez un guide, les modifications sont enregistrées sur l'ordinateur et sur [!include[pn-hololens](../includes/pn-hololens.md)]. Il est ainsi très facile de passer d'un appareil à un autre. L'enregistrement automatique permet de vérifier les nouvelles modifications toutes les quatre secondes.

Vous devez être en ligne pour utiliser [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

> [!NOTE]
> Lorsque vous basculez d'un appareil à l'autre, il est préférable de fermer le guide pour ne pas perdre votre travail.

## <a name="whats-next"></a>Étapes suivantes

[Ancrer votre guide dans le monde réel](anchor.md)<br>
[Structurer votre guide dans la page Plan](structure-guide.md)<br>
[Créer des étapes et ajouter du contenu 3D ou des supports 2D](create-steps-assign-media.md)<br>
[En savoir plus sur les raccourcis clavier](keyboard-shortcuts-pc-app.md)
