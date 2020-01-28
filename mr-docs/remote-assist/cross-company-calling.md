---
author: sophiasysun
description: Paramétrez les appels interentreprises pour Dynamics 365 Remote Assist en activant l'accès externe dans le Centre d'administration de Microsoft Teams.
ms.author: sopsun
ms.date: 05/06/2019
ms.service: crm-online
ms.topic: article
title: Paramétrer les appels interentreprises pour Dynamics 365 Remote Assist
ms.reviewer: v-brycho
ms.openlocfilehash: 186796612bac3f5395cf01ca432982204e9c70a2
ms.sourcegitcommit: 56579384c418edd4f37cd750751fc8e4d8883a65
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 12/20/2019
ms.locfileid: "2921093"
---
# <a name="set-up-cross-company-calling-for-dynamics-365-remote-assist-for-admins"></a><span data-ttu-id="345fa-103">Paramétrer les appels interentreprises pour Dynamics 365 Remote Assist (pour les administrateurs)</span><span class="sxs-lookup"><span data-stu-id="345fa-103">Set up cross-company calling for Dynamics 365 Remote Assist (for admins)</span></span>

<span data-ttu-id="345fa-104">Les utilisateurs de votre organisation peuvent effectuer ou recevoir un appel à deux avec un utilisateur de [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] d'une autre société (domaine) si l'accès externe est activé dans [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] pour chaque domaine.</span><span class="sxs-lookup"><span data-stu-id="345fa-104">Users in your organization can make or receive a one-on-one call with a [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] user from another company (domain) if external access is enabled in [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] for each domain.</span></span> 

> [!NOTE]
> <span data-ttu-id="345fa-105">Actuellement, l'appel de groupe et le partage de fichier ne sont pas disponibles pour les appels interentreprises.</span><span class="sxs-lookup"><span data-stu-id="345fa-105">At this time, group calling and file sharing is not available for cross-company calling.</span></span>

1.  <span data-ttu-id="345fa-106">[Activez l'accès externe](https://docs.microsoft.com/microsoftteams/manage-external-access) à votre centre d'administration [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)].</span><span class="sxs-lookup"><span data-stu-id="345fa-106">[Enable external access](https://docs.microsoft.com/microsoftteams/manage-external-access) in your [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] admin center.</span></span> <span data-ttu-id="345fa-107">Cela permet aux utilisateurs de votre organisation d'effectuer des appels et de converser avec des utilisateurs en dehors de votre domaine.</span><span class="sxs-lookup"><span data-stu-id="345fa-107">This allows users in your organization to make calls and chat with users outside your domain.</span></span>

    <span data-ttu-id="345fa-108">![Activer l'accès externe](media/enable-external-access.PNG "Activer l'accès externe")</span><span class="sxs-lookup"><span data-stu-id="345fa-108">![Enable external access](media/enable-external-access.PNG "Enable external access")</span></span>
 
    <span data-ttu-id="345fa-109">Par défaut, les utilisateurs peuvent communiquer avec des utilisateurs dans n'importe quel autre domaine doté d'un accès externe actif et ayant autorisé l'accès externe avec votre domaine.</span><span class="sxs-lookup"><span data-stu-id="345fa-109">By default, users can communicate with users in any other domain that has external access turned on and that has allowed external access with your domain.</span></span> <span data-ttu-id="345fa-110">Si vous souhaitez limiter ce comportement, vous pouvez ajouter des domaines autorisés ou bloqués.</span><span class="sxs-lookup"><span data-stu-id="345fa-110">If you want to restrict this behavior, you can add allowed or blocked domains.</span></span> <span data-ttu-id="345fa-111">Pour plus d'informations, voir [Gérer l'accès externe (fédération) dans Microsoft Teams](https://docs.microsoft.com/microsoftteams/manage-external-access).</span><span class="sxs-lookup"><span data-stu-id="345fa-111">For more information, see [Manage external access (federation) in Microsoft Teams](https://docs.microsoft.com/microsoftteams/manage-external-access).</span></span>

2.  <span data-ttu-id="345fa-112">Pour vérifier si un contact dans un autre domaine dispose d'un accès externe activé au Centre d'administration de [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] de sa société, essayez entrer l'adresse e-mail complète de ce contact dans le bureau de Teams.</span><span class="sxs-lookup"><span data-stu-id="345fa-112">To check to see if a contact in another domain has external access enabled in their company’s [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] admin center, try typing the contact's full email address in Teams Desktop.</span></span> <span data-ttu-id="345fa-113">Si un accès externe est autorisé entre les deux domaines, [!include[pn-teams](../includes/pn-teams.md)] affiche le message suivant :</span><span class="sxs-lookup"><span data-stu-id="345fa-113">When external access is allowed between both domains, [!include[pn-teams](../includes/pn-teams.md)] shows the following message:</span></span>

    <span data-ttu-id="345fa-114">![Message de confirmation](media/access-enabled-confirmation.PNG "Message de confirmation")</span><span class="sxs-lookup"><span data-stu-id="345fa-114">![Confirmation message](media/access-enabled-confirmation.PNG "Confirmation message")</span></span>
 
### <a name="see-also"></a><span data-ttu-id="345fa-115">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="345fa-115">See also</span></span>

[<span data-ttu-id="345fa-116">Guide de l'utilisateur de Dynamics 365 Remote Assist</span><span class="sxs-lookup"><span data-stu-id="345fa-116">Dynamics 365 Remote Assist user guide</span></span>](https://docs.microsoft.com/dynamics365/mixed-reality/remote-assist/user-guide#make-and-receive-calls)
