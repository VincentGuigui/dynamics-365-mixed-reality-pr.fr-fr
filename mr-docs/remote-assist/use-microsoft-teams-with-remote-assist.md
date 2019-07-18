---
author: bencorn
description: Paramétrer et utiliser Microsoft Teams avec Remote Assist pour collaborer à un appel
ms.author: bencorn
ms.date: 06/04/2019
ms.service: crm-online
ms.topic: article
title: Configurer et utiliser Microsoft Teams avec Remote Assist
ms.reviewer: v-brycho
ms.openlocfilehash: 2964049fad93daffca716a447c9ece9420b21f95
ms.sourcegitcommit: 80c2a9dc71cab3914d3a96d37904bd1e16e4b450
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 06/03/2019
ms.locfileid: "1617253"
---
# <a name="set-up-and-use-microsoft-teams-with-remote-assist-to-collaborate-on-a-call"></a><span data-ttu-id="f581f-103">Paramétrer et utiliser Microsoft Teams avec Remote Assist pour collaborer à un appel</span><span class="sxs-lookup"><span data-stu-id="f581f-103">Set up and use Microsoft Teams with Remote Assist to collaborate on a call</span></span>

<span data-ttu-id="f581f-104">Un utilisateur de [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] sur [!include[pn-hololens](../includes/pn-hololens.md)] peut travailler en collaboration avec un collègue (généralement un expert d'un domaine spécifique) lors d'un appel vidéo en utilisant [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)].</span><span class="sxs-lookup"><span data-stu-id="f581f-104">A [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] user on [!include[pn-hololens](../includes/pn-hololens.md)] can work collaboratively with a colleague (typically an expert in a particular field) during a video call by using [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)].</span></span> <span data-ttu-id="f581f-105">L'expert peut consulter tout ce que l'utilisateur de [!include[pn-remote-assist](../includes/pn-remote-assist.md)] voit et ensemble, ils peuvent dessiner et annoter holographiquement.</span><span class="sxs-lookup"><span data-stu-id="f581f-105">The expert can see everything that the [!include[pn-remote-assist](../includes/pn-remote-assist.md)] user sees, and they can holographically draw and annotate together.</span></span> <span data-ttu-id="f581f-106">Par exemple, imaginons qu'un collaborateur de première ligne procède à la maintenance d'une machine très complexe et a des doutes quant à la manière de résoudre un problème.</span><span class="sxs-lookup"><span data-stu-id="f581f-106">For example, let’s say a first-line worker is servicing a very complex machine and isn’t sure how to solve a problem.</span></span> <span data-ttu-id="f581f-107">Le collaborateur de première ligne peut appeler un expert n'importe où dans le monde et lui demander son appui pour la maintenance à l'aide d'annotations ou de fichiers.</span><span class="sxs-lookup"><span data-stu-id="f581f-107">The first-line worker can call an expert anywhere in the world and have the expert assist with the servicing using annotations or files.</span></span>

<span data-ttu-id="f581f-108">Le paramétrage de cette collaboration en utilisant [!include[pn-teams](../includes/pn-teams.md)] est simple et gratuit pour l'expert.</span><span class="sxs-lookup"><span data-stu-id="f581f-108">Setting up this collaboration using [!include[pn-teams](../includes/pn-teams.md)] is simple and it’s free for the expert.</span></span>

<span data-ttu-id="f581f-109">Besoin d'aide complémentaire ?</span><span class="sxs-lookup"><span data-stu-id="f581f-109">Need more help?</span></span> <span data-ttu-id="f581f-110">[Consultez la FAQ de Remote Assist](faq.md) pour obtenir des réponses aux questions fréquentes.</span><span class="sxs-lookup"><span data-stu-id="f581f-110">[Check out Remote Assist FAQ](faq.md) for answers to common questions.</span></span>

<span data-ttu-id="f581f-111">[Consultez des vidéos pratiques](videos.md) concernant [!include[pn-remote-assist](../includes/pn-remote-assist.md)].</span><span class="sxs-lookup"><span data-stu-id="f581f-111">[Watch how-to videos](videos.md) about [!include[pn-remote-assist](../includes/pn-remote-assist.md)].</span></span>

## <a name="what-youll-need"></a><span data-ttu-id="f581f-112">Ce dont vous aurez besoin</span><span class="sxs-lookup"><span data-stu-id="f581f-112">What you’ll need</span></span>


<span data-ttu-id="f581f-113">L'utilisateur de [!include[pn-remote-assist](../includes/pn-remote-assist.md)] (collaborateur de première ligne) sur [!include[pn-HoloLens](../includes/pn-HoloLens.md)] a besoin des éléments suivants :</span><span class="sxs-lookup"><span data-stu-id="f581f-113">The [!include[pn-remote-assist](../includes/pn-remote-assist.md)] user (first-line worker) on [!include[pn-HoloLens](../includes/pn-HoloLens.md)] needs:</span></span>

-   [<span data-ttu-id="f581f-114">Un abonnement à Remote Assist.</span><span class="sxs-lookup"><span data-stu-id="f581f-114">A subscription to Remote Assist.</span></span>](../licensing/buy-and-deploy.md) <span data-ttu-id="f581f-115">L'abonnement à [!include[pn-remote-assist](../includes/pn-remote-assist.md)] inclut un abonnement à [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)].</span><span class="sxs-lookup"><span data-stu-id="f581f-115">The [!include[pn-remote-assist](../includes/pn-remote-assist.md)] subscription includes a subscription to [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)].</span></span>

-   <span data-ttu-id="f581f-116">Un [!include[pn-hololens](../includes/pn-hololens.md)] exécutant [Windows 10 April 2018 Update](https://support.microsoft.com/en-us/help/12643) (ou une version ultérieure).</span><span class="sxs-lookup"><span data-stu-id="f581f-116">A [!include[pn-hololens](../includes/pn-hololens.md)] running the [Windows 10 April 2018 Update](https://support.microsoft.com/en-us/help/12643) (or later).</span></span>

-   <span data-ttu-id="f581f-117">Un compte [!include[pn-azure-active-directory](../includes/pn-azure-active-directory.md)].</span><span class="sxs-lookup"><span data-stu-id="f581f-117">An [!include[pn-azure-active-directory](../includes/pn-azure-active-directory.md)] account.</span></span>

<span data-ttu-id="f581f-118">Le spécialiste a besoin des éléments suivants :</span><span class="sxs-lookup"><span data-stu-id="f581f-118">The expert needs:</span></span>

-   <span data-ttu-id="f581f-119">Un PC exécutant [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 avec la dernière version de [Microsoft Teams](https://products.office.com/microsoft-teams/group-chat-software) ou un appareil mobile exécutant [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] Mobile.</span><span class="sxs-lookup"><span data-stu-id="f581f-119">A PC running [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 with the latest version of [Microsoft Teams](https://products.office.com/microsoft-teams/group-chat-software) or a mobile device running [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] Mobile.</span></span> <span data-ttu-id="f581f-120">Le spécialiste utilise [!include[pn-teams](../includes/pn-teams.md)] pour communiquer avec l'utilisateur de [!include[pn-remote-assist](../includes/pn-remote-assist.md)] dans [!include[pn-HoloLens](../includes/pn-HoloLens.md)].</span><span class="sxs-lookup"><span data-stu-id="f581f-120">The expert uses [!include[pn-teams](../includes/pn-teams.md)] to communicate with the [!include[pn-remote-assist](../includes/pn-remote-assist.md)] user on [!include[pn-HoloLens](../includes/pn-HoloLens.md)].</span></span> [!include[pn-teams](../includes/pn-teams.md)] <span data-ttu-id="f581f-121">peut être disponible [en téléchargement gratuit](https://teams.microsoft.com/downloads).</span><span class="sxs-lookup"><span data-stu-id="f581f-121">may be available [as a free download](https://teams.microsoft.com/downloads).</span></span>

-   <span data-ttu-id="f581f-122">Un compte [!include[cc-microsoft](../includes/cc-microsoft.md)] gratuit.</span><span class="sxs-lookup"><span data-stu-id="f581f-122">A free [!include[cc-microsoft](../includes/cc-microsoft.md)] account.</span></span> <span data-ttu-id="f581f-123">Le spécialiste peut déjà avoir un compte [!include[cc-microsoft](../includes/cc-microsoft.md)] s'il s'est inscrit pour [!include[cc-microsoft](../includes/cc-microsoft.md)] App Store, Skype, Xbox, Hotmail ou Outlook.com.</span><span class="sxs-lookup"><span data-stu-id="f581f-123">The expert might already have a [!include[cc-microsoft](../includes/cc-microsoft.md)] account if they signed up for the [!include[cc-microsoft](../includes/cc-microsoft.md)] App Store, Skype, Xbox, Hotmail, or Outlook.com.</span></span> <span data-ttu-id="f581f-124">Si l'expert n'a pas encore de compte [!include[cc-microsoft](../includes/cc-microsoft.md)], il peut s'inscrire sur [https://account.microsoft.com/account](https://account.microsoft.com/account).</span><span class="sxs-lookup"><span data-stu-id="f581f-124">If the expert doesn’t already have a [!include[cc-microsoft](../includes/cc-microsoft.md)] account, they can sign up for one by going to [https://account.microsoft.com/account](https://account.microsoft.com/account).</span></span>

## <a name="setup"></a><span data-ttu-id="f581f-125">Configurer</span><span class="sxs-lookup"><span data-stu-id="f581f-125">Setup</span></span>

<span data-ttu-id="f581f-126">Vous pouvez intégrer un expert pour collaborer en utilisant [!include[pn-teams](../includes/pn-teams.md)] en trois étapes faciles :</span><span class="sxs-lookup"><span data-stu-id="f581f-126">You can onboard an expert and collaborate using [!include[pn-teams](../includes/pn-teams.md)] in three easy steps:</span></span>

| <span data-ttu-id="f581f-127">**Étape**</span><span class="sxs-lookup"><span data-stu-id="f581f-127">**Step**</span></span> | <span data-ttu-id="f581f-128">**Description**</span><span class="sxs-lookup"><span data-stu-id="f581f-128">**Description**</span></span>                                                                  | <span data-ttu-id="f581f-129">**Qui effectue cette étape ?**</span><span class="sxs-lookup"><span data-stu-id="f581f-129">**Who does this step?**</span></span>           |
|----------|----------------------------------------------------------------------------------|-----------------------------------|
|    <span data-ttu-id="f581f-130">1.</span><span class="sxs-lookup"><span data-stu-id="f581f-130">1.</span></span>      | <span data-ttu-id="f581f-131">Activer l'accès invité pour [!include[pn-teams](../includes/pn-teams.md)]</span><span class="sxs-lookup"><span data-stu-id="f581f-131">Enable guest access for [!include[pn-teams](../includes/pn-teams.md)]</span></span>                                                    | <span data-ttu-id="f581f-132">Administrateur</span><span class="sxs-lookup"><span data-stu-id="f581f-132">Administrator</span></span>                     |
|    <span data-ttu-id="f581f-133">2.</span><span class="sxs-lookup"><span data-stu-id="f581f-133">2.</span></span>      | <span data-ttu-id="f581f-134">Inviter l'expert à rejoindre une équipe en tant qu'invité en utilisant le compte [!include[cc-microsoft](../includes/cc-microsoft.md)] de l'expert</span><span class="sxs-lookup"><span data-stu-id="f581f-134">Invite the expert to join a team as a guest using the expert’s [!include[cc-microsoft](../includes/cc-microsoft.md)] account</span></span> | <span data-ttu-id="f581f-135">Administrateur ou expert et utilisateur [!include[pn-remote-assist](../includes/pn-remote-assist.md)] (pour télécharger [!include[pn-teams](../includes/pn-teams.md)])</span><span class="sxs-lookup"><span data-stu-id="f581f-135">Administrator or [!include[pn-remote-assist](../includes/pn-remote-assist.md)] user and expert (to download [!include[pn-teams](../includes/pn-teams.md)])</span></span> |
|    <span data-ttu-id="f581f-136">3.</span><span class="sxs-lookup"><span data-stu-id="f581f-136">3.</span></span>      | <span data-ttu-id="f581f-137">Passer un appel</span><span class="sxs-lookup"><span data-stu-id="f581f-137">Place a call</span></span>                                                                     | <span data-ttu-id="f581f-138">Expert ou utilisateur [!include[pn-remote-assist](../includes/pn-remote-assist.md)]</span><span class="sxs-lookup"><span data-stu-id="f581f-138">[!include[pn-remote-assist](../includes/pn-remote-assist.md)] user or expert</span></span>     |

### <a name="step-1-enable-guest-access-for-teams"></a><span data-ttu-id="f581f-139">Étape 1 : activez l'accès Invité pour les équipes</span><span class="sxs-lookup"><span data-stu-id="f581f-139">Step 1: Enable guest access for teams</span></span>

1.  <span data-ttu-id="f581f-140">Si vous êtes l'administrateur du tenant [!include[pn-azure](../includes/pn-azure.md)] principal, allez à <https://admin.microsoft.com/adminportal/> pour ouvrir le portail administrateur d'Office, puis connectez-vous.</span><span class="sxs-lookup"><span data-stu-id="f581f-140">If you’re the admin for the main [!include[pn-azure](../includes/pn-azure.md)] tenant, go to <https://admin.microsoft.com/adminportal/> to open the Office Admin portal, and then sign in.</span></span>

2.  <span data-ttu-id="f581f-141">Dans le menu sur la gauche, sélectionnez **Afficher plus** \> **Paramètres** \> **Services et compléments**.</span><span class="sxs-lookup"><span data-stu-id="f581f-141">From the menu on the left, select **Show More** \> **Settings** \> **Services & add-ins**.</span></span>

    <span data-ttu-id="f581f-142">![Services et compléments](media/bf81ea48e3ccd560b6f44dbc72a73eb5.png "Services et compléments")</span><span class="sxs-lookup"><span data-stu-id="f581f-142">![Service & add-ins](media/bf81ea48e3ccd560b6f44dbc72a73eb5.png "Service & add-ins")</span></span>

1.  <span data-ttu-id="f581f-143">Sélectionnez **[!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)]** dans la liste de candidatures.</span><span class="sxs-lookup"><span data-stu-id="f581f-143">Select **[!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)]** from the list of applications.</span></span>

    <span data-ttu-id="f581f-144">![Microsoft Teams](media/ad846431f181b1c6df362bc2e0e03167.png "Microsoft Teams")</span><span class="sxs-lookup"><span data-stu-id="f581f-144">![Microsoft Teams](media/ad846431f181b1c6df362bc2e0e03167.png "Microsoft Teams")</span></span>

1.  <span data-ttu-id="f581f-145">Sélectionnez **Paramètres par type d'utilisateur/de licence**.</span><span class="sxs-lookup"><span data-stu-id="f581f-145">Select **Settings by user/license type**.</span></span>

2.  <span data-ttu-id="f581f-146">Dans la liste déroulante en regard de **Sélectionner le type d'utilisateur/licence à configurer**, sélectionnez **Invité**.</span><span class="sxs-lookup"><span data-stu-id="f581f-146">In the drop-down list next to **Select the user/license type you want to configure**, select **Guest**.</span></span>

3.  <span data-ttu-id="f581f-147">Définissez **Activer/Désactiver [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)] pour tous les utilisateurs de ce type** sur **Activé**, puis sélectionnez **Enregistrer**.</span><span class="sxs-lookup"><span data-stu-id="f581f-147">Set **Turn [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)] on or off for all users of this type** to **On**, and then choose **Save**.</span></span>

    <span data-ttu-id="f581f-148">![Enregistrer](media/9f095e7553a4af03ff13ea6a29a9343a.png "Enregistrer")</span><span class="sxs-lookup"><span data-stu-id="f581f-148">![Save](media/9f095e7553a4af03ff13ea6a29a9343a.png "Save")</span></span>

4.  <span data-ttu-id="f581f-149">Attendez une heure que les paramètres se propagent.</span><span class="sxs-lookup"><span data-stu-id="f581f-149">Wait an hour for the settings to propagate.</span></span>

### <a name="step-2-invite-the-expert-to-join-a-team"></a><span data-ttu-id="f581f-150">Étape 2 : invitez l'expert à rejoindre une équipe</span><span class="sxs-lookup"><span data-stu-id="f581f-150">Step 2: Invite the expert to join a team</span></span>

1.  <span data-ttu-id="f581f-151">Dans [!include[pn-teams](../includes/pn-teams.md)], sélectionnez **Rejoindre ou créer une équipe** pour créer une équipe si elle n'existe pas déjà.</span><span class="sxs-lookup"><span data-stu-id="f581f-151">In [!include[pn-teams](../includes/pn-teams.md)], select **Join or create a team** to create a team if it doesn’t already exist.</span></span> <span data-ttu-id="f581f-152">L'expert et l'utilisateur de [!include[pn-remote-assist](../includes/pn-remote-assist.md)] doivent être dans la même équipe pour communiquer.</span><span class="sxs-lookup"><span data-stu-id="f581f-152">The [!include[pn-remote-assist](../includes/pn-remote-assist.md)] user and the expert must be on the same team to communicate.</span></span>

    <span data-ttu-id="f581f-153">![Rejoindre ou créer une équipe](media/16e00f809d210dcb3b1e8c8e859b73da.png "Rejoindre ou créer une équipe")</span><span class="sxs-lookup"><span data-stu-id="f581f-153">![Join or create a team](media/16e00f809d210dcb3b1e8c8e859b73da.png "Join or create a team")</span></span>

1.  <span data-ttu-id="f581f-154">Lorsqu'il vous est demandé d'ajouter des membres, accédez au compte [!include[cc-microsoft](../includes/cc-microsoft.md)] de l'expert.</span><span class="sxs-lookup"><span data-stu-id="f581f-154">When asked to add members, enter the expert’s [!include[cc-microsoft](../includes/cc-microsoft.md)] account.</span></span>

    <span data-ttu-id="f581f-155">![Compte Microsoft](media/71e9276273f8f47b786f743416a2cb64.png "Compte Microsoft")</span><span class="sxs-lookup"><span data-stu-id="f581f-155">![Microsoft account](media/71e9276273f8f47b786f743416a2cb64.png "Microsoft account")</span></span>

    > [!NOTE]
    > <span data-ttu-id="f581f-156">Si vous ne voyez pas l'option pour ajouter un invité en tapant une adresse e-mail, il est probable que l'accès Invité ne soit pas activé pour le tenant [!include[pn-azure](../includes/pn-azure.md)] de votre société pour [!include[pn-teams](../includes/pn-teams.md)].</span><span class="sxs-lookup"><span data-stu-id="f581f-156">If you don’t see the option to add a guest by typing an email address, it’s likely that guest access isn’t enabled on your company’s [!include[pn-azure](../includes/pn-azure.md)] tenant for [!include[pn-teams](../includes/pn-teams.md)].</span></span> <span data-ttu-id="f581f-157">Activez l'accès Invité comme décrit précédemment dans cette rubrique.</span><span class="sxs-lookup"><span data-stu-id="f581f-157">Enable guest access as described earlier in this topic.</span></span>

1.  <span data-ttu-id="f581f-158">L'expert recevra immédiatement un message électronique et peut cliquer sur le lien dans le message pour ouvrir (ou télécharger) [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)].</span><span class="sxs-lookup"><span data-stu-id="f581f-158">The expert will immediately receive an email message and can click the link in the message to open (or download) [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)].</span></span> <span data-ttu-id="f581f-159">Cette version de [!include[pn-teams](../includes/pn-teams.md)] est gratuite et n'est pas une version d'essai.</span><span class="sxs-lookup"><span data-stu-id="f581f-159">This version of [!include[pn-teams](../includes/pn-teams.md)] is free and is not a trial version.</span></span>

### <a name="step-3-place-a-call"></a><span data-ttu-id="f581f-160">Étape 3.</span><span class="sxs-lookup"><span data-stu-id="f581f-160">Step 3.</span></span> <span data-ttu-id="f581f-161">Passer un appel</span><span class="sxs-lookup"><span data-stu-id="f581f-161">Place a call</span></span>

1.  <span data-ttu-id="f581f-162">L'expert lance l'application [!include[pn-teams](../includes/pn-teams.md)] et l'utilisateur de [!include[pn-remote-assist](../includes/pn-remote-assist.md)] sur [!include[pn-hololens](../includes/pn-hololens.md)] se connecte à son compte comme d'habitude.</span><span class="sxs-lookup"><span data-stu-id="f581f-162">The expert launches the [!include[pn-teams](../includes/pn-teams.md)] app and the [!include[pn-remote-assist](../includes/pn-remote-assist.md)] user on the [!include[pn-hololens](../includes/pn-hololens.md)] signs in to their account as usual.</span></span>

    > [!IMPORTANT]
    > <span data-ttu-id="f581f-163">Si c'est la première fois que l'expert a lancé [!include[pn-teams](../includes/pn-teams.md)] et qu'il n'a été invité à aucune autre équipe, [!include[pn-teams](../includes/pn-teams.md)] guidera automatiquement l'expert vers l'espace correct.</span><span class="sxs-lookup"><span data-stu-id="f581f-163">If this is the first time the expert has launched [!include[pn-teams](../includes/pn-teams.md)] and the expert has not been invited to any other teams, [!include[pn-teams](../includes/pn-teams.md)] will automatically take the expert to the correct place.</span></span> <span data-ttu-id="f581f-164">Si l'expert a été invité à d'autres équipes, il pourra devoir basculer vers le tenant approprié.</span><span class="sxs-lookup"><span data-stu-id="f581f-164">If the expert has been invited to other teams, the expert might need to switch to the appropriate tenant.</span></span>  
    >     
    > <span data-ttu-id="f581f-165">Pour changer de tenant, dans le menu déroulant dans le coin supérieur droit de la fenêtre, sélectionnez le tenant invité approprié :</span><span class="sxs-lookup"><span data-stu-id="f581f-165">To switch tenants, in the drop-down menu in the upper-right corner of the window, select the appropriate guest tenant:</span></span>
    
    <span data-ttu-id="f581f-166">![Tenant invité](media/55237a5359fb66daf7bbb9413adab6b9.png "Tenant invité")</span><span class="sxs-lookup"><span data-stu-id="f581f-166">![Guest tenant](media/55237a5359fb66daf7bbb9413adab6b9.png "Guest tenant")</span></span>
       
    > [!NOTE]
    > [!include[pn-teams](../includes/pn-teams.md)] <span data-ttu-id="f581f-167">peut nécessiter quelques secondes pour recharger.</span><span class="sxs-lookup"><span data-stu-id="f581f-167">might take a few seconds to reload.</span></span>
    
1.  <span data-ttu-id="f581f-168">L'une ou l'autre des parties peut être à l'origine de l'appel.</span><span class="sxs-lookup"><span data-stu-id="f581f-168">Either party can make the call.</span></span> <span data-ttu-id="f581f-169">Vous devrez peut-être rechercher dans les contacts pour trouver la bonne personne.</span><span class="sxs-lookup"><span data-stu-id="f581f-169">You might need to search contacts to find the right person.</span></span>

    > [!NOTE]
    > <span data-ttu-id="f581f-170">L'invité peut appeler n'importe quel membre de la même équipe.</span><span class="sxs-lookup"><span data-stu-id="f581f-170">The guest can call any member on the same team.</span></span> <span data-ttu-id="f581f-171">Pour étendre cette fonctionnalité, invitez tous les autres membres au sein de votre société qui pourraient tirer profit d'être en mesure d'accéder à ce nouvel expert.</span><span class="sxs-lookup"><span data-stu-id="f581f-171">To extend this functionality, invite any other members within your company who would benefit from being able to access this new expert.</span></span>

## <a name="working-with-annotations"></a><span data-ttu-id="f581f-172">Utilisation des annotations</span><span class="sxs-lookup"><span data-stu-id="f581f-172">Working with annotations</span></span>

<span data-ttu-id="f581f-173">Une fois que [!include[pn-teams](../includes/pn-teams.md)] est installé, l'expert peut effectuer des appels vidéo à l'adresse de contacts (et en recevoir de ces derniers) en utilisant [!include[pn-remote-assist](../includes/pn-remote-assist.md)] sur un [!include[pn-hololens](../includes/pn-hololens.md)].</span><span class="sxs-lookup"><span data-stu-id="f581f-173">Once [!include[pn-teams](../includes/pn-teams.md)] is installed, the expert can make video calls to (and receive them from) contacts using [!include[pn-remote-assist](../includes/pn-remote-assist.md)] on a [!include[pn-hololens](../includes/pn-hololens.md)].</span></span>

<span data-ttu-id="f581f-174">Au cours d'un appel, l'expert voit l'espace du contact, hologrammes inclus, peut utiliser la barre d'outils de réalité mixte dans la fenêtre de l'appel vidéo pour ajouter des hologrammes.</span><span class="sxs-lookup"><span data-stu-id="f581f-174">When in a call, the expert will see the contact’s space—including the holograms—and can use the Mixed Reality toolbar in the video call window to add holograms.</span></span>

<span data-ttu-id="f581f-175">![Barre d'outils de réalité mixte](media/071f358ab6bbf7c2072b15d9203a1593.png "Barre d'outils de réalité mixte")</span><span class="sxs-lookup"><span data-stu-id="f581f-175">![Mixed Reality toolbar](media/071f358ab6bbf7c2072b15d9203a1593.png "Mixed Reality toolbar")</span></span>

## <a name="draw-and-annotate"></a><span data-ttu-id="f581f-176">Dessiner et annoter</span><span class="sxs-lookup"><span data-stu-id="f581f-176">Draw and annotate</span></span>

### <a name="edit-mode"></a><span data-ttu-id="f581f-177">Mode d'édition</span><span class="sxs-lookup"><span data-stu-id="f581f-177">Edit mode</span></span>

<span data-ttu-id="f581f-178">Pour commencer à annoter l'espace d'un contact, effectuez d'abord une des actions suivantes pour interrompre le flux vidéo et entrer en mode d'édition :</span><span class="sxs-lookup"><span data-stu-id="f581f-178">To start annotating a contact’s space, first do one of the following to pause the video stream and enter edit mode:</span></span>

-   <span data-ttu-id="f581f-179">Sélectionnez n'importe où dans la fenêtre d'appel.</span><span class="sxs-lookup"><span data-stu-id="f581f-179">Select anywhere in the call window.</span></span>

-   <span data-ttu-id="f581f-180">Sélectionnez l'un des articles dans la barre d'outils de réalité mixte.</span><span class="sxs-lookup"><span data-stu-id="f581f-180">Select one of the items on the Mixed Reality toolbar.</span></span>

-   <span data-ttu-id="f581f-181">Sélectionnez **Commencer l'édition**.</span><span class="sxs-lookup"><span data-stu-id="f581f-181">Select **Start editing**.</span></span>

<span data-ttu-id="f581f-182">En mode d'édition, l'expert verra toujours un stream en direct de l'appel dans le coin de la fenêtre d'application.</span><span class="sxs-lookup"><span data-stu-id="f581f-182">In edit mode, the expert will still see a live stream of the call in the corner of the app window.</span></span>

### <a name="add-arrows-ink-and-files"></a><span data-ttu-id="f581f-183">Ajouter des flèches, de l'encre et des fichiers</span><span class="sxs-lookup"><span data-stu-id="f581f-183">Add arrows, ink, and files</span></span>

<span data-ttu-id="f581f-184">Utilisez la barre d'outils de réalité mixte pour placer les flèches, dessiner ou ajouter des fichiers :</span><span class="sxs-lookup"><span data-stu-id="f581f-184">Use the Mixed Reality toolbar to place arrows, draw, or add files:</span></span>

-   <span data-ttu-id="f581f-185">Pour ajouter des flèches, sélectionnez **Insérer une flèche** ![Insérer une flèche](media/6584f4b7932378aa23f6efbf460b304c.png "Insérer une flèche").</span><span class="sxs-lookup"><span data-stu-id="f581f-185">To add arrows, select **Place arrow** ![Place arrow](media/6584f4b7932378aa23f6efbf460b304c.png "Place arrow") .</span></span>

-   <span data-ttu-id="f581f-186">Pour ajouter de l'encre, sélectionnez **Encre** ![Encre](media/187307e30fd713f5ae67aba854b78bc4.png "Encre").</span><span class="sxs-lookup"><span data-stu-id="f581f-186">To add ink, select **Ink** ![Ink](media/187307e30fd713f5ae67aba854b78bc4.png "Ink") .</span></span>

-   <span data-ttu-id="f581f-187">Pour modifier la couleur de flèche ou d'encre, sélectionnez **Choisir une couleur** ![Choisir une couleur](media/5d9d3c70cf19ed175a8dc1ad71a60fc5.png "Choisir une couleur").</span><span class="sxs-lookup"><span data-stu-id="f581f-187">To change the arrow or ink color, select **Pick a color** ![Pick a color](media/5d9d3c70cf19ed175a8dc1ad71a60fc5.png "Pick a color") .</span></span>

-   <span data-ttu-id="f581f-188">Pour ajouter un fichier, sélectionnez **Insérer des fichiers** ![Insérer des fichiers](media/41aa538d3be8e163215f7d9374abe90e.png "Insérer des fichiers"), puis ajouter un fichier image ou un fichier PDF.</span><span class="sxs-lookup"><span data-stu-id="f581f-188">To add a file, select **Insert files** ![Insert files](media/41aa538d3be8e163215f7d9374abe90e.png "Insert files"), and then add an image file or a PDF file.</span></span>

    > [!NOTE]
    > <span data-ttu-id="f581f-189">Une fois ajoutées, les images ne peuvent pas être déplacées, supprimées ou redimensionnées par l'expert.</span><span class="sxs-lookup"><span data-stu-id="f581f-189">After adding them, images can’t be moved, deleted, or resized by the expert.</span></span>

### <a name="finish-editing"></a><span data-ttu-id="f581f-190">Terminer l'édition</span><span class="sxs-lookup"><span data-stu-id="f581f-190">Finish editing</span></span>

<span data-ttu-id="f581f-191">Une fois l'annotation terminée, effectuez l'une des opérations suivantes pour terminer l'édition et revenir au mode réel :</span><span class="sxs-lookup"><span data-stu-id="f581f-191">When done annotating, do one of the following to finish editing and return to live mode:</span></span>

-   <span data-ttu-id="f581f-192">Sélectionnez **Arrêter la modification**.</span><span class="sxs-lookup"><span data-stu-id="f581f-192">Select **Stop editing**.</span></span>

-   <span data-ttu-id="f581f-193">Sélectionnez le flux vidéo en direct dans le coin droit de votre écran.</span><span class="sxs-lookup"><span data-stu-id="f581f-193">Select the live video feed in the corner of your screen.</span></span>

### <a name="make-changes-to-edits"></a><span data-ttu-id="f581f-194">Apporter des modifications aux éditions</span><span class="sxs-lookup"><span data-stu-id="f581f-194">Make changes to edits</span></span>

<span data-ttu-id="f581f-195">Pour apporter des modifications aux éditions, procédez d'une des façons suivantes :</span><span class="sxs-lookup"><span data-stu-id="f581f-195">To make changes to edits, do one of the following:</span></span>

-   <span data-ttu-id="f581f-196">En mode d'édition, sélectionnez **Annuler** pour annuler la dernière action.</span><span class="sxs-lookup"><span data-stu-id="f581f-196">While in edit mode, select **Undo** to undo the last action.</span></span>

-   <span data-ttu-id="f581f-197">En mode d'édition, sélectionnez **Effacer tout** ![Effacer tout](media/3aab547aa81003ad181eceadc2c83a47.png "Effacer tout") pour effacer toutes les annotations effectuées pendant cette session d'édition.</span><span class="sxs-lookup"><span data-stu-id="f581f-197">While in edit mode, select **Erase all** ![Erase all](media/3aab547aa81003ad181eceadc2c83a47.png "Erase all") to erase all of the annotations made during that editing session.</span></span>

-   <span data-ttu-id="f581f-198">En mode réel, sélectionnez **Effacer tout** ![Effacer tout](media/3aab547aa81003ad181eceadc2c83a47.png "Effacer tout") pour effacer toutes les annotations effectuées pendant cet appel.</span><span class="sxs-lookup"><span data-stu-id="f581f-198">While in live mode, select **Erase all** ![Erase all](media/3aab547aa81003ad181eceadc2c83a47.png "Erase all") to erase all of the annotations made during that call.</span></span>

> [!NOTE]
> <span data-ttu-id="f581f-199">Les dessins ou les flèches spécifiques ne peuvent pas être supprimés.</span><span class="sxs-lookup"><span data-stu-id="f581f-199">Specific drawings or arrows can’t be removed.</span></span> <span data-ttu-id="f581f-200">Seul l'utilisateur d'[!include[pn-hololens](../includes/pn-hololens.md)] peut apporter des modifications à des images ajoutées par un expert, ou les supprimer.</span><span class="sxs-lookup"><span data-stu-id="f581f-200">Only the [!include[pn-hololens](../includes/pn-hololens.md)] user can make changes to or delete pictures added by an expert.</span></span>

## <a name="share-your-desktop-or-a-running-application-with-a-remote-assist-user"></a><span data-ttu-id="f581f-201">Partager votre ordinateur de bureau ou une application en cours d'exécution avec un utilisateur de Remote Assist</span><span class="sxs-lookup"><span data-stu-id="f581f-201">Share your desktop or a running application with a Remote Assist user</span></span>

<span data-ttu-id="f581f-202">Lorsque vous partagez votre bureau ou une application en cours d'exécution avec un utilisateur de [!include[pn-remote-assist](../includes/pn-remote-assist.md)], le flux vidéo de l'utilisateur passe à une couleur unie.</span><span class="sxs-lookup"><span data-stu-id="f581f-202">When you share your desktop or running application with a [!include[pn-remote-assist](../includes/pn-remote-assist.md)] user, the user's video feed will change to a solid color.</span></span> <span data-ttu-id="f581f-203">Tous les outils de la barre d'outils demeureront utilisables, même si le flux vidéo ne sera plus affiché.</span><span class="sxs-lookup"><span data-stu-id="f581f-203">They'll still be able to use all the tools in the toolbar even though their video feed will no longer be displayed.</span></span>

<span data-ttu-id="f581f-204">Pour partager votre bureau ou une application en cours d'exécution :</span><span class="sxs-lookup"><span data-stu-id="f581f-204">To share your desktop or a running application:</span></span>

1. <span data-ttu-id="f581f-205">Dans [!include[pn-teams](../includes/pn-teams.md)], sélectionnez le bouton **Ouvrir le bac de partage**.</span><span class="sxs-lookup"><span data-stu-id="f581f-205">In [!include[pn-teams](../includes/pn-teams.md)], select the **Open share tray** button.</span></span>

   <span data-ttu-id="f581f-206">![Bouton Bac de partage](media/share-tray.PNG "Bouton Bac de partage")</span><span class="sxs-lookup"><span data-stu-id="f581f-206">![Share tray button](media/share-tray.PNG "Share tray button")</span></span>
   
2. <span data-ttu-id="f581f-207">Sélectionnez l'écran que vous souhaitez partager.</span><span class="sxs-lookup"><span data-stu-id="f581f-207">Select the screen you want to share.</span></span>

> [!NOTE]
> <span data-ttu-id="f581f-208">Vous ne pouvez partager qu'une seule application ou qu'un seul écran à la fois.</span><span class="sxs-lookup"><span data-stu-id="f581f-208">You can only share one application or screen at a time.</span></span> <span data-ttu-id="f581f-209">Si vous souhaitez partager un écran différent, sélectionnez le bouton **Fermer le bac de partage** pour arrêter le partage, sélectionnez un autre écran, puis redémarrez le partage.</span><span class="sxs-lookup"><span data-stu-id="f581f-209">If you want to share a different screen, select the **Close share tray** button to stop sharing, select a different screen, and then start sharing again.</span></span>

### <a name="see-also"></a><span data-ttu-id="f581f-210">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="f581f-210">See also</span></span>
[<span data-ttu-id="f581f-211">Guide de l'utilisateur</span><span class="sxs-lookup"><span data-stu-id="f581f-211">User Guide</span></span>](user-guide.md)<br/>
[<span data-ttu-id="f581f-212">Vidéos pratiques</span><span class="sxs-lookup"><span data-stu-id="f581f-212">How-to videos</span></span>](videos.md)<br/>
[<span data-ttu-id="f581f-213">FAQ</span><span class="sxs-lookup"><span data-stu-id="f581f-213">FAQ</span></span>](faq.md)<br/>