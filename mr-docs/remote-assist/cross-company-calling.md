---
author: bencorn
description: Paramétrez les appels interentreprises pour Dynamics 365 Remote Assist en activant l'accès externe dans le Centre d'administration de Microsoft Teams.
ms.author: becorn
ms.date: 05/06/2019
ms.service: crm-online
ms.topic: article
title: Paramétrer les appels interentreprises pour Dynamics 365 Remote Assist
ms.reviewer: v-brycho
ms.openlocfilehash: 843f403d330e349a85816f260de2a669976712bb
ms.sourcegitcommit: 8999bfecc2b117135aa9a1077044f678341c33ad
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/06/2019
ms.locfileid: "1575534"
---
# <a name="set-up-cross-company-calling-for-dynamics-365-remote-assist-for-admins"></a>Paramétrer les appels interentreprises pour Dynamics 365 Remote Assist (pour les administrateurs)

Les utilisateurs de votre organisation peuvent effectuer ou recevoir un appel à deux avec un utilisateur de Microsoft Teams d'une autre société (domaine) si l'accès externe est activé dans Microsoft Teams pour chaque domaine. 

> [!NOTE]
> Actuellement, l'appel de groupe et le partage de fichier ne sont pas disponibles pour les appels interentreprises.

1.  [Activez l'accès externe](https://docs.microsoft.com/microsoftteams/manage-external-access) à votre centre d'administration Microsoft Teams. Cela permet aux utilisateurs de votre organisation d'effectuer des appels et de converser avec des utilisateurs en dehors de votre domaine.

    ![Activer l'accès externe](media/enable-external-access.PNG "Activer l'accès externe")
 
    Par défaut, les utilisateurs peuvent communiquer avec des utilisateurs dans n'importe quel autre domaine doté d'un accès externe actif et ayant autorisé l'accès externe avec votre domaine. Si vous souhaitez limiter ce comportement, vous pouvez ajouter des domaines autorisés ou bloqués. Pour plus d'informations, voir [Gérer l'accès externe (fédération) dans Microsoft Teams](https://docs.microsoft.com/microsoftteams/manage-external-access).

2.  Pour vérifier si un contact dans un autre domaine dispose d'un accès externe activé au Centre d'administration de Microsoft Teams de sa société, essayez entrer l'adresse e-mail complète de ce contact dans le bureau de Teams. Si un accès externe est autorisé entre les deux domaines, Teams affiche le message suivant :

    ![Message de confirmation](media/access-enabled-confirmation.PNG "Message de confirmation")
 
### <a name="see-also"></a>Voir aussi

[Guide de l'utilisateur de Dynamics 365 Remote Assist](https://docs.microsoft.com/dynamics365/mixed-reality/remote-assist/user-guide#make-and-receive-calls)
