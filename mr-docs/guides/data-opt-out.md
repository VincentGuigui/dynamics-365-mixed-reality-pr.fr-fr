---
author: Makamat
description: Découvrez comment désactiver le stockage des données d'utilisation Microsoft Dynamics 365 Guides dans Common Data Service, pour des raisons de confidentialité.
ms.author: makamat
ms.date: 01/28/2020
ms.service: crm-online
ms.topic: article
title: Désactiver le stockage des données d'utilisation Dynamics 365 Guides dans Common Data Service
ms.reviewer: v-brycho
ms.openlocfilehash: e55ee2841cfa57b842615cdffa3b3db027b56f4b
ms.sourcegitcommit: 217d31bb34e67a6b8823d5ddac7ef8d56d054139
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/29/2020
ms.locfileid: "2994795"
---
# <a name="opt-out-of-storing-dynamics-365-guides-usage-data-in-common-data-service"></a><span data-ttu-id="c3280-103">Désactiver le stockage des données d'utilisation Dynamics 365 Guides dans Common Data Service</span><span class="sxs-lookup"><span data-stu-id="c3280-103">Opt out of storing Dynamics 365 Guides usage data in Common Data Service</span></span>

<span data-ttu-id="c3280-104">Les applications Dynamics 365 Guides permettent aux équipes de capturer des statistiques d'utilisation et des informations de suivi du temps détaillées.</span><span class="sxs-lookup"><span data-stu-id="c3280-104">Dynamics 365 Guides apps enable teams to capture usage statistics and detailed time-tracking information.</span></span> <span data-ttu-id="c3280-105">Ces données sont utilisées pour fournir des mesures de performances des opérateurs et pour vous aider à identifier les opportunités d'optimisation des processus.</span><span class="sxs-lookup"><span data-stu-id="c3280-105">This data is used to provide metrics for operator performance and help you identify opportunities for process optimization.</span></span> <span data-ttu-id="c3280-106">Les administrateurs peuvent désactiver la collecte de données pour des utilisateurs spécifiques s'ils le souhaitent.</span><span class="sxs-lookup"><span data-stu-id="c3280-106">Administrators can turn off data collection for specific users if they like.</span></span> 

<span data-ttu-id="c3280-107">Pour ce faire :</span><span class="sxs-lookup"><span data-stu-id="c3280-107">To do this:</span></span>

1.  <span data-ttu-id="c3280-108">Accédez à powerapps.microsoft.com et connectez-vous avec votre compte d'administrateur.</span><span class="sxs-lookup"><span data-stu-id="c3280-108">Go to powerapps.microsoft.com and sign in with your admin account.</span></span>

2.  <span data-ttu-id="c3280-109">Dans le menu déroulant du client/de l'instance, sélectionnez l'instance où Dynamics 365 Guides est installé.</span><span class="sxs-lookup"><span data-stu-id="c3280-109">In the tenant/instance drop-down, select the instance that has Dynamics 365 Guides installed.</span></span>

3.  <span data-ttu-id="c3280-110">Sélectionnez l'application Guides dans la liste.</span><span class="sxs-lookup"><span data-stu-id="c3280-110">Select the Guides app in the list.</span></span> <span data-ttu-id="c3280-111">Un nouvel onglet s'ouvre pour le portail Guides.</span><span class="sxs-lookup"><span data-stu-id="c3280-111">This opens a new tab for the Guides portal.</span></span>

4.  <span data-ttu-id="c3280-112">Dans le volet de navigation de gauche, accédez à **Paramètres utilisateur**.</span><span class="sxs-lookup"><span data-stu-id="c3280-112">In the left navigation, go to **User Settings.**</span></span>

    <span data-ttu-id="c3280-113">![Paramètres utilisateur](media/data-opt-out-user-setting.PNG "Paramètres utilisateur")</span><span class="sxs-lookup"><span data-stu-id="c3280-113">![User Settings](media/data-opt-out-user-setting.PNG "User Settings")</span></span>
 
5.  <span data-ttu-id="c3280-114">Sélectionnez **Nouveau**.</span><span class="sxs-lookup"><span data-stu-id="c3280-114">Select **New**.</span></span>

    <span data-ttu-id="c3280-115">![Sélectionner Nouveau](media/data-opt-out-new.PNG "Sélectionner Nouveau")</span><span class="sxs-lookup"><span data-stu-id="c3280-115">![Select New](media/data-opt-out-new.PNG "Select New")</span></span>
 
6.  <span data-ttu-id="c3280-116">Complétez le formulaire comme suit :</span><span class="sxs-lookup"><span data-stu-id="c3280-116">Fill out the form as follows:</span></span>

    - <span data-ttu-id="c3280-117">**Nom :** désactivez l'*ajout d'un nom d'utilisateur ici*.</span><span class="sxs-lookup"><span data-stu-id="c3280-117">**Name:** Opt out for *add user name here*.</span></span>

    - <span data-ttu-id="c3280-118">**Enregistrer l'utilisation des guides :** oui.</span><span class="sxs-lookup"><span data-stu-id="c3280-118">**Record Guide Usage:** Yes.</span></span>

    - <span data-ttu-id="c3280-119">**Appartient à :** nom d'utilisateur.</span><span class="sxs-lookup"><span data-stu-id="c3280-119">**Belongs To:** User's name.</span></span> 

7.  <span data-ttu-id="c3280-120">Sélectionnez **Enregistrer**.</span><span class="sxs-lookup"><span data-stu-id="c3280-120">Select **Save**.</span></span>

    <span data-ttu-id="c3280-121">![Formulaire complété](media/data-opt-out-filled-out-form.PNG "Formulaire complété")</span><span class="sxs-lookup"><span data-stu-id="c3280-121">![Filled-out form](media/data-opt-out-filled-out-form.PNG "Filled-out-form")</span></span>
 
## <a name="see-also"></a><span data-ttu-id="c3280-122">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="c3280-122">See also</span></span>

[<span data-ttu-id="c3280-123">Analyser l'utilisation des guides</span><span class="sxs-lookup"><span data-stu-id="c3280-123">Analyze guides usage</span></span>](analytics-guide.md)
