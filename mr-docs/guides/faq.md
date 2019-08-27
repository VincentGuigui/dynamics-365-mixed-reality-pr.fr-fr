---
author: BryceHo
description: FAQ sur Dynamics 365 Guides (version préliminaire)
ms.author: makamat
ms.date: 05/30/2019
ms.service: crm-online
ms.topic: article
title: FAQ sur Dynamics 365 Guides (version préliminaire)
ms.reviewer: v-brycho
ms.openlocfilehash: b2f29a3269551adcf4bf188923f94893f0e25d23
ms.sourcegitcommit: 8770ec043776563f3f9e87ee89f241c68015f576
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/31/2019
ms.locfileid: "1797350"
---
# <a name="frequently-asked-questions-about-microsoft-dynamics-365-guides-preview"></a>Forum Aux Questions sur Microsoft Dynamics 365 Guides (version préliminaire)

[!INCLUDE [cc-beta-prerelease-disclaimer](../includes/cc-beta-prerelease-disclaimer.md)]
 
## <a name="how-do-i-contact-support-if-i-dont-find-an-answer-in-this-faq"></a>Comment contacter le support si je ne trouve pas de réponse dans ce FAQ ?

Si vous ne pouvez pas utiliser [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)] ou si votre problème n'est pas répertorié dans ce FAQ ou dans la documentation, contactez le support client comme suit :

1. Accédez à [https://dynamics.microsoft.com/en-us/support/](https://dynamics.microsoft.com/en-us/support/).

2. Sous **Aide + support pour Customer Engagement**, sélectionnez **ACCÉDER AU SUPPORT**.

3. Recherchez un numéro de téléphone ou envoyez une demande de support dans le Centre d'administration. 

## <a name="why-do-i-have-to-download-two-apps"></a>Pourquoi faut-il télécharger deux applications ?

[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] inclut deux applications :

- Application de création du PC

- Application [!include[pn-hololens](../includes/pn-hololens.md)], qui inclut des modes de création et d'exécution

Si vous envisagez de rédiger des instructions, vous devrez utiliser les deux applications. Sinon, vous aurez uniquement besoin de l'application [!include[pn-hololens](../includes/pn-hololens.md)].

## <a name="what-are-the-prerequisites-for-using-the-dynamics-365-guides-apps"></a>Quelles sont les conditions préalables pour utiliser les applications Dynamics 365 Guides ?

Le tableau suivant répertorie les exigences techniques pour le déploiement et l'utilisation de [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] dans toute votre organisation.

### <a name="device-requirements"></a>Configuration requise pour l'appareil
|Appareil|Configuration requise du SE|Détails|
|----------------------------------------|---------------------------------------------|-------------------------------------|
|[!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-hololens](../includes/pn-hololens.md)]|Version 10.0.14393.0 ou ultérieure. Nous vous recommandons de mettre à jour [!include[pn-hololens](../includes/pn-hololens.md)] vers des versions plus récentes quand elles sont disponibles.|Voir [Gérer les mises à jour vers HoloLens](https://docs.microsoft.com/en-us/HoloLens/hololens-updates) pour obtenir des instructions sur l'utilisation de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Update pour Entreprise, Gestion des périphériques mobiles (GPM) et [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Server Update Services (WSUS).|
|[!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC (requis pour créer un guide)|[!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC avec Fall Creators Update 1709 ou version ultérieure (version 10.0.16299 ou ultérieure)|Un [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC est utilisé pour créer et modifier les guides qui sont alors disponibles dans [!include[pn-hololens](../includes/pn-hololens.md)].</br><br>Résolution minimale d'écran suggérée : 1080 px de large|

### <a name="licensing-and-product-requirements"></a>Gestion des licences et configuration requise du produit

Une licence [!include[pn-dyn-365-guides-preview](../includes/pn-dyn-365-guides-preview.md)] est requise pour chaque utilisateur qui utilise l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Pour plus d'informations, voir la [rubrique Configurer](setup.md).

## <a name="is-there-an-out-of-the-box-integration-with-dynamics-365-for-field-service"></a>Existe-t-il une intégration prête à l'emploi avec Dynamics 365 for Field Service ?

Oui, la version préliminaire de l'intégration de [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)] a été ajoutée dans la version 104.1907.19001.

## <a name="i-get-an-error-message-when-i-try-to-sign-in-to-the-pc-app-or-includepn-hololensincludespn-hololensmd-app"></a>J'obtiens un message d'erreur lorsque j'essaie de me connecter à l'application du PC ou à l'application [!include[pn-hololens](../includes/pn-hololens.md)]

Le package de solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] (qui comprend une bibliothèque de contenu 3D intégrée) doit être installé sur votre compte [!include[pn-dyn-365](../includes/pn-dyn-365.md)]. Chaque utilisateur doit également disposer d'une licence pour utiliser le produit [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Si votre organisation est déjà abonnée aux [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], vous ou votre administrateur pouvez facilement fournir l'accès aux applications. Pour plus d'informations, voir la [rubrique Configurer](setup.md).

## <a name="where-is-the-data-stored-and-who-has-access-to-it"></a>Où sont stockées les données et qui y a accès ?

Les données sont stockées dans Common Data Service dans le client pour lequel vous disposez de privilèges Administrateur. Connectez-vous à [!include[pn-dyn-365](../includes/pn-dyn-365.md)] en utilisant les informations d'identification créées lors du processus d'inscription. Pour plus d'informations, voir la [rubrique Configurer](setup.md). 

## <a name="what-file-formats-are-supported"></a>Quels formats de fichier sont pris en charge ?

Le tableau suivant répertorie les formats de fichier pris en charge pour le contenu 3D, les images, et les vidéos.

|Support|Formats pris en charge|Conseil|
|----------|----------------------|-------------------------------------------------------------------------|
|Contenu 3D|FBX, GLB, glTF|Veillez à optimiser les modèles 3D autant que possible pour maintenir des performances optimales dans [!include[pn-hololens](../includes/pn-hololens.md)].|
|Images|PNG, JPG, JPEG, GIF, TIFF||
|Vidéos|MP4, MOV, WMV|Faites en sorte que vos vidéos durent moins de 2 minutes et se concentrent sur une étape à la fois.|

## <a name="will-i-lose-any-data-if-i-close-an-app-inadvertently"></a>Est-ce que je vais perdre des données si je ferme une application par inadvertance ?

Les deux applications enregistrent automatiquement vos modifications lorsque vous rédigez des instructions. Nous vous recommandons d'attendre quelques secondes une fois terminé avant de fermer l'application pour qu'elle ait le temps de se synchroniser avec le serveur.

Notez que dans l'application [!include[pn-hololens](../includes/pn-hololens.md)], si vous utilisez l'écartement des doigts paume vers le haut pour ouvrir le menu **Démarrer**, l'application passe en veille (elle ne se ferme pas). Lorsque vous sélectionnez la vignette de l'application, vous revenez là où vous étiez avant et aucune modification n'est perdue.

## <a name="what-if-the-app-crashes-while-authoring-do-i-lose-data"></a>Que se passe-t-il si l'application s'arrête lors de la création ? Est-ce que je vais perdre des données ?
Les deux applications enregistrent automatiquement vos modifications lorsque vous rédigez des instructions. En cas de plantage, très peu de données seront perdues.

## <a name="what-keyboard-shortcuts-are-available-in-the-pc-authoring-app"></a>Quels sont les raccourcis clavier disponibles dans l'application de création sur PC ?

Pour obtenir la liste des raccourcis clavier, voir le [Guide de création](pc-authoring.md).

## <a name="how-can-i-improve-visual-clarity-of-holograms-in-the-includepn-hololensincludespn-hololensmd-app"></a>Comment améliorer la clarté visuel des hologrammes dans l'application [!include[pn-hololens](../includes/pn-hololens.md)] ?

Si les hologrammes ne sont pas suffisamment clairs, il est possible que [!include[pn-hololens](../includes/pn-hololens.md)] ne soit pas correctement étalonné. L'étalonnage est primordial car [!include[pn-hololens](../includes/pn-hololens.md)] affiche les hologrammes en se basant sur l'écart entre vos pupilles (distance interpupillaire ou « DIP »). Si [!include[pn-hololens](../includes/pn-hololens.md)] n'est pas étalonné correctement, vos yeux ont des difficultés à voir les hologrammes dans le monde réel. 

Pour étalonner [!include[pn-hololens](../includes/pn-hololens.md)] :

1.  Écartez des doigts paume vers le haut pour ouvrir le menu **Démarrer**.

2.  Écartez de nouveau les doigts paume vers le haut pour afficher toutes les applications installées. 

3.  Sélectionnez l'application d'étalonnage, puis suivez ses instructions. 

4.  Après avoir étalonné, sélectionnez l'application [!include[pn-hololens](../includes/pn-hololens.md)] de nouveau.

Si les hologrammes sont visuellement clairs mais trop lumineux ou trop foncés, utilisez les boutons situés à gauche du casque [!include[pn-hololens](../includes/pn-hololens.md)] pour augmenter ou réduire la luminosité.

## <a name="what-should-i-do-if-the-holographic-instructions-arent-aligned-to-my-work-area"></a>Que dois-je faire si les instructions holographiques ne sont pas alignées sur ma zone de travail ?

Un alignement incorrect des hologrammes peut se produire pour deux motifs principaux :

- Le DIP n'a pas été défini correctement sur [!include[pn-hololens](../includes/pn-hololens.md)]. Consultez les instructions sur la définition du DIP ci-dessus pour corriger cela.

- Le guide doit être réaligné :

- Si le guide est aligné à l'aide d'un **point d'ancrage numérique**, la représentation numérique (représentation 3D placée sur la zone physique correspondante) n'est pas correctement alignée. Pour réaligner le guide, sélectionnez le bouton **Ancrer**, puis réalignez la représentation numérique pour recouvrir parfaitement la zone physique. 

- Si le guide est aligné à l'aide d'un **point d'ancrage imprimé**, il est possible que le marqueur du guide n'ait pas été imprimé correctement. Essayez de réaligner le guide en cliquant sur le bouton **Ancrer**. Vous pouvez aussi imprimer à nouveau le marqueur. Assurez-vous que le marqueur imprimé soit bien à plat dans la zone de travail avant de réaligner.

Pour plus d'informations sur les méthodes d'ancrage, voir le [Guide de création](pc-authoring.md).

## <a name="what-does-the-save-button-with-the-refresh-icon-mean-how-does-save-work"></a>Que signifie le bouton Enregistrer avec l'icône d'actualisation ? Comment fonctionne l'enregistrement ?

La fonctionnalité de sauvegarde automatique permet aux auteurs de synchroniser leurs modifications entre le PC et les applications [!include[pn-hololens](../includes/pn-hololens.md)] lorsqu'ils modifient un guide simultanément dans les deux applications. Les modifications sont automatiquement enregistrées et synchronisées sur le serveur à intervalles de quelques secondes. Les applications sont également actualisées automatiquement lorsqu'elles détectent que des modifications ont été apportées au guide d'un autre appareil. Vous pouvez également cliquer sur le bouton **Enregistrer** à tout moment pour vous assurer que vos modifications sont bien enregistrées.

## <a name="i-see-this-message-guide-out-of-sync-refreshing-with-a-loading-spinner-whats-going-on"></a>Le message suivant s'affiche : « Guide désynchronisé. Actualisation du contenu » avec un indicateur de chargement. Que se passe-t-il ?

Ce message s'affiche lorsque vous ou un autre utilisateur modifiez le même guide sur des appareils distincts. Ce guide est automatiquement enregistré dans l'autre appareil d'abord, puis il est mis à jour sur le serveur. Lorsque l'appareil actuel apprend la mise à jour, il recharge la dernière la version du guide à partir du serveur.

## <a name="i-see-this-message-save-failed-what-does-this-mean"></a>Le message suivant s'affiche : « Échec de l'enregistrement ». Qu'est-ce que cela signifie ?

Le PC et les applications [!include[pn-hololens](../includes/pn-hololens.md)] enregistrent vos modifications sur le serveur 2 secondes après chaque modification. Si l'une de ces tentatives de sauvegarde échoue, cette notification s'affiche.

Cela peut se produire si vous avez une connexion Internet médiocre ou si le serveur est en panne. La notification devrait disparaitre automatiquement une fois que la connexion au serveur est restaurée. Toutefois, si ce message reste affiché, nous vous conseillons de ne plus faire de modification au cours de cette session car elles risqueraient d'être perdues. Vérifiez la connexion Internet sur votre appareil ou contactez votre administrateur pour voir s'il existe des problèmes de connexion.

## <a name="can-i-add-more-than-eight-3d-models-to-a-step"></a>Est-ce que je peux ajouter plus de huit modèles 3D à une étape ?

Il n'y a que huit zones **composants 3D** dans l'emplacement, ce qui limite la variété de modèles 3D qu'il est possible d'ajouter au cours d'une étape. Lorsque vous placez des hologrammes dans [!include[pn-hololens](../includes/pn-hololens.md)], vous pouvez cependant en placer un nombre illimité à partir de l'emplacement. Par exemple, vous ne pouvez pas ajouter plus de huit modèles 3D différents (des flèches, des boîtes, des écrous, des forets, etc.) à l'emplacement, mais vous pouvez placer autant de flèches, de boîtes, d'écrous et de forets à partir de chaque zone de **Composant 3D** que vous souhaitez dans [!include[pn-hololens](../includes/pn-hololens.md)]. Pour ce faire, cliquez soit sur des emplacements de ressource pour engendrer des modèles 3D ou accédez au menu **Modifier** d'un modèle 3D et sélectionnez **Dupliquer**.

## <a name="i-see-a-triangle-shaped-hazard-sign-when-i-load-a-step-what-does-that-mean"></a>Un signe de danger en forme de triangle s'affiche lorsque je charge une étape. Qu'est-ce que cela signifie ?

Le signe de danger est un espace réservé pour les modèles 3D, les vidéos ou les images qui ne peuvent pas être correctement chargés dans l'application [!include[pn-hololens](../includes/pn-hololens.md)]. Parmi les raisons possibles on trouve :

- Des problèmes de connexion intermittents ou un fichier trop grand. Si c'est le cas, relancez l'application [!include[pn-hololens](../includes/pn-hololens.md)]. Si cela ne résout pas le problème, lancez l'application du PC, recherchez le fichier en question, et ouvrez-le en mode de prévisualisation. Si la prévisualisation se charge, réinstallez l'application [!include[pn-hololens](../includes/pn-hololens.md)] et lancez à nouveau le guide. 

- Si vous ne trouvez pas le fichier dans la bibliothèque d'applications du PC, c'est que la référence (l'entité) au modèle 3D/à la vidéo/à l'image est rompue. Chargez de nouveau le fichier et récréez le guide.

- Si le fichier existe dans la bibliothèque mais que la prévisualisation ne se charge pas, c'est qu'il y a un problème avec les informations du fichier dans [!include[pn-dyn-365](../includes/pn-dyn-365.md)]. Chargez de nouveau le fichier, puis modifiez le guide pour faire référence à cette nouvelle ressource, le cas échéant.

### <a name="see-also"></a>Voir aussi

[Problèmes connus avec Dynamics 365 Guides en version préliminaire](known-issues.md)
