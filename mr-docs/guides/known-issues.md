---
author: BryceHo
description: Problèmes connus avec Dynamics 365 Guides
ms.author: makamat
ms.date: 10/01/2019
ms.service: crm-online
ms.topic: article
title: Problèmes connus avec Dynamics 365 Guides
ms.reviewer: v-brycho
ms.openlocfilehash: 2cc3203aa54b46878be4b2262560e86d3d3c9b13
ms.sourcegitcommit: f37698eb33fd4d198b054e73ce3d9ec680c56e21
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/02/2019
ms.locfileid: "2537280"
---
# <a name="known-issues-with-microsoft-dynamics-365-guides"></a>Problèmes connus avec Microsoft Dynamics 365 Guides

## <a name="october-1-release-improvements-for-3d-model-positioning-may-shift-models-in-existing-guides"></a>Les améliorations apportées au 1er octobre pour le positionnement de modèles 3D peuvent déplacer les modèles dans les guides existants

La version du 1er octobre inclut une refactorisation du code des positions d'hologramme afin d'améliorer les performances globales et de permettre des améliorations futures. Vous remarquerez peut-être que la position de certains modèles importés, auxquels une échelle a été appliquée, peut être modifiée. Vous devez replacer ces modèles 3D. Cela ne concerne pas la position des modèles de la boîte à outils 3D.
 
## <a name="keep-file-names-for-3d-models-and-media-short"></a>Donner des noms de fichiers courts aux modèles et aux supports 3D

Avant de charger des fichiers de support ou des modèles 3D personnalisés dans l'application du PC, assurez-vous que les noms de fichiers ne comportent pas plus de 60 caractères, et ne contiennent pas de caractères spéciaux (&, @, etc.). 

Les modèles 3D volumineux sont stockés dans la mémoire [!include[pn-hololens](../includes/pn-hololens.md)] quand ils sont utilisés. C'est pourquoi, l'expérience est sensiblement plus lente s'il y a un trop grand nombre de modèles dans un guide. **Pour une question de performance, il est préférable que les modèles 3 D ne dépassent pas 450 Mo dans un guide.** 

## <a name="editing-the-same-guide-on-two-different-pcs-is-not-fully-supported"></a>Il n'est pas possible de modifier le même guide sur deux PC différents

Même si vous pouvez créer le même guide sur PC et [!include[pn-hololens](../includes/pn-hololens.md)], nous déconseillons vivement de le modifier sur deux PC distincts. Cela peut entraîner des problèmes de synchronisation, et vous risquez de perdre les modifications apportées au cours de l'une des sessions sur PC.

## <a name="text-wrapping-on-pc-and-hololens-might-differ-in-rare-cases"></a>Il peut parfois arriver que le retour à la ligne du texte soit différent sur PC et HoloLens

Dans de rares cas, vous pouvez noter que le texte est renvoyé à la ligne dans la vue de la fiche étape dans [!include[pn-hololens](../includes/pn-hololens.md)] mais pas sur le PC. Cela est dû au fait que [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] affiche les polices à différentes tailles pour une question de lisibilité entre le PC et [!include[pn-hololens](../includes/pn-hololens.md)], et les différentes largeurs de caractères peuvent provoquer un retour à la ligne. Pour garantir que cela n'affecte pas l'expérience des opérateurs, vérifiez le texte à toutes les étapes de l'application [!include[pn-hololens](../includes/pn-hololens.md)] avant de partager vos guides.

## <a name="hololens-app-cant-refresh-when-you-edit-the-anchoring-step-on-a-pc-for-the-same-guide"></a>Impossible d'actualiser l'application HoloLens lorsque vous modifiez l'étape d'ancrage sur un PC pour le même guide

Nous vous recommandons de ne pas ouvrir un guide sur [!include[pn-hololens](../includes/pn-hololens.md)] si une étape d'alignement est en cours de modification pour ce même guide sur un PC. Dans ce cas, l'application [!include[pn-hololens](../includes/pn-hololens.md)] s'actualise automatiquement, mais elle ne peut pas ouvrir le guide.

## <a name="when-authoring-on-hololens-2-authors-need-to-air-tap-to-select-3d-models-before-editing"></a>Lors d'une création sur HoloLens 2, les auteurs doivent cliquer dans l'air pour sélectionner les modèles 3D avant de les modifier.

Sur HoloLens 2, le mode de sélection apparaît lorsque vous cliquez dans l'air des modèles 3D, plutôt que lorsque vous les pointez du regard. Après avoir cliqué dans l'air, vous pouvez cliquer longuement pour effectuer un déplacement, utiliser les gizmos pour effectuer une rotation, ou explorer les options de modification. HoloLens 1 continuera à prendre en charge l'ancien comportement où vous pointiez du regard les modèles 3D pour les sélectionner.

## <a name="recent-guides-list-isnt-scoped-to-user"></a>La liste des guides récents n'est pas disponible pour les utilisateurs
La liste des guides **récents** n'est pas actuellement disponible pour les utilisateurs. Elle sera prise en charge dans une version ultérieure.

## <a name="when-placing-large-assets-on-hololens-you-might-see-minor-loading-delays"></a>Lorsque vous placez des ressources volumineuses dans HoloLens, de petits retards de chargement peuvent se produire
L'application [!include[pn-hololens](../includes/pn-hololens.md)] charge actuellement le guide dès son ouverture, et en arrière-plan quand vous l'utilisez. Si votre guide contient des modèles 3D et des supports volumineux, vous risquez de rencontrer des retards de chargement de quelques secondes.

## <a name="guides-cant-be-renamed-or-deleted-from-the-pc-app"></a>Les guides ne peuvent pas être renommés ou supprimés de l'application sur PC

Pour le moment, il n'est pas possible de renommer ou de supprimer des guides.

## <a name="you-can-create-guides-with-the-same-name-without-overwriting-old-guides"></a>Vous pouvez créer des guides portant le même nom sans pour autant remplacer d'anciens guides

Vous pouvez créer plusieurs guides avec le même nom. Même si cette opération empêche d'écraser involontairement d'anciens fichiers, cela entraîne de la confusion lorsque vous sélectionnez un guide dans une liste. Lorsque vous créez un guide, veillez à utiliser un nom unique.

## <a name="3d-content-and-media-cannot-be-renamed-or-deleted-from-the-pc-app-after-uploading"></a>Le contenu et le support 3D ne peuvent pas être renommés ou supprimés de l'application sur PC une fois téléchargés

Pour le moment, nous ne prenons pas en charge le renommage ou la suppression de contenu et support 3D une fois qu'ils sont chargés sur le serveur. Bien qu'il soit possible de les renommer dans [!include[pn-dyn-365](../includes/pn-dyn-365.md)], cela peut avoir des conséquences imprévues sur tous les guides qui les utilisent.

## <a name="3d-content-and-media-will-be-overwritten-if-you-upload-new-content-with-the-same-name"></a>Le contenu et le support 3D seront écrasés si vous chargez un nouveau contenu portant le même nom

Nous ne prenons pas en charge plusieurs fichiers portant le même nom dans la version actuelle. Dans le cadre du chargement de nouveaux modèles ou support 3D, vérifiez qu'il n'existe pas de fichier portant le même nom dans la bibliothèque. Vous pouvez, cependant, avoir différents types de fichiers portant le même nom, par exemple, une image qui s'appelle bolt.png et un modèle 3D qui s'appelle bolt.glb.

## <a name="cant-use-the-same-name-for-3d-parts-that-you-upload-even-if-they-have-different-extensions"></a>Impossible d'utiliser le même nom pour des composants 3D qui vous chargez, même s'ils ont des extensions différentes

L'application recherche actuellement les supports par nom de fichier. Ainsi, par exemple, si un fichier se nomme picture.jpg et un autre picture.png, l'application ne sait pas lequel afficher pour l'étape. Il est donc recommandé d'utiliser systématiquement des noms de fichiers uniques pour les fichiers de support que vous chargez.

## <a name="how-do-i-address-hardware-offset-in-hololens-1-devices-to-ensure-accurate-placement-of-holograms-for-printed-anchor-alignment"></a>Comment résoudre le décalage du matériel dans les appareils HoloLens 1 afin de garantir le positionnement exact des hologrammes pour l'alignement du point d'ancrage imprimé
 
L'angle de chaque caméra PV [!include[pn-hololens](../includes/pn-hololens.md)] 1 (la caméra placée juste au-dessus de l'arête nasale) peut être légèrement différent selon les appareils en raison des spécificités de fabrication. Comme la caméra PV permet d'analyser le marqueur imprimé, cela signifie que les hologrammes peuvent être légèrement décalés si vous utilisez le même guide et le même marqueur imprimé sur plusieurs appareils.
 
Pour résoudre ce problème, l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] [!include[pn-hololens](../includes/pn-hololens.md)] fournit la capacité d'ajuster manuellement ce décalage et d'enregistrer les paramètres pour l'appareil afin que chaque utilisateur n'ait pas besoin de les définir à chaque fois. Nous recommandons que le personnel informatique parcourt les étapes suivantes avant de mettre en service les appareils pour les auteurs ou les opérateurs [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Il s'agit d'un paramétrage unique qui n'a pas besoin d'être répété, à moins que l'application soit désinstallée ou qu'un nouveau système d'exploitation soit installé.
 
### <a name="step-1--set-up-printed-anchor"></a>Étape 1 : Paramétrer un point d'ancrage imprimé

#### <a name="on-the-pc"></a>Sur le PC

1.  Créez un point d'ancrage imprimé selon les spécifications décrites dans [Créer dans l'application du PC](https://docs.microsoft.com/dynamics365/mixed-reality/guides/pc-authoring#choose-an-alignment-method).

2.  Ouvrez l'application de création sur le PC, puis créez un guide à l'aide de la méthode de point d'ancrage imprimé (vous pouvez aussi utiliser un guide existant qui utilise un point d'ancrage imprimé).

#### <a name="on-hololens"></a>Sur HoloLens

- Exécutez l'application d'étalonnage [!include[pn-hololens](../includes/pn-hololens.md)] pour vérifier vous-même l'alignement et le DIP.
 
### <a name="step-2--open-the-guide-and-align-it-on-hololens"></a>Étape 2 : Ouvrir le guide et l'aligner dans HoloLens

1.  Dans [!include[pn-hololens](../includes/pn-hololens.md)], ouvrez l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], sélectionnez le mode **Opérateur** ou **Créer**, puis ouvrez le guide utilisé dans l'étape 1.

2.  Sélectionnez **Analyser** pour démarrer le processus d'alignement. Acceptez les invites d'autorisation qui s'affichent. 

3. Recherchez votre marqueur imprimé, laissez l'appareil trouver le marqueur, puis attendez l'animation au contour bleu. Le contour bleu indique où se trouve le marqueur imprimé, tel que calculé par [!include[pn-hololens](../includes/pn-hololens.md)].

### <a name="step-3--adjust-the-offset"></a>Étape 3 : Ajuster le décalage

Le contour bleu est de la même taille que le marqueur. Vous pouvez le déplacer vers le haut ou vers le bas le long des rails positionnés à chaque angle. Regardez le marqueur imprimé par le dessus. Le contour bleu est-il trop à gauche ou à droite du marqueur imprimé ? Dans ce cas, ajustez l'appareil [!include[pn-hololens](../includes/pn-hololens.md)] pour être sûr qu'il soit bien positionné sur votre tête.

Appuyez longuement sur le contour bleu et déplacez-le vers le haut ou vers le bas jusqu'à ce qu'il chevauche exactement le marqueur. Assurez-vous que le contour est parfaitement aligné en regardant le marqueur depuis les côtés. 
 
Le panneau de support affiche l'image suivante pour indiquer visuellement ce que vous devez effectuer.

![Ajuster le décalage du marqueur imprimé](media/adjust-marker-offset.png "Ajuster le décalage du marqueur imprimé")  

Après vous être assuré que le contour bleu et le marqueur imprimé sont alignés, sélectionnez **Confirmer** pour terminer le processus. 

La prochaine fois que cet appareil sera utilisé pour charger un guide, l'opérateur/l'auteur n'aura plus qu'à analyser le marqueur ; il n'aura pas besoin d'ajuster de nouveau le contour bleu.

Si, à tout moment, vous devez rajuster ce paramètre, vous pouvez définir le processus d'ajustement du décalage à nouveau en sélectionnant le paramètre **Ajuster le décalage**. Lorsque vous activez ce paramètre, il doit déclencher le processus normal d'alignement, en commençant par l'analyse du marqueur imprimé.

## <a name="troubleshooting"></a>Dépannage

### <a name="pc-authoring-application-issues"></a>Problèmes avec l'application de création du PC

#### <a name="i-cant-sign-in"></a>Je ne peux pas me connecter

Pour vous connecter, vous devez utiliser les informations d'identification [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365](../includes/pn-dyn-365.md)] de votre organisation. Elles sont semblables à : johndoe@contoso.onmicrosoft.com. Vous ne pouvez pas utiliser de compte [!include[cc-microsoft](../includes/cc-microsoft.md)] (utilisé pour Outlook.com, [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Store, etc.) ou vos informations d'identification d'entreprise pour vous connecter. 

Si vous voyez l'une des erreurs suivantes, contactez votre administrateur informatique ou reportez-vous à notre documentation en libre-service dans http://aka.ms/guidesdocs. 

- [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] n'est pas paramétré correctement, ou vous ne disposez peut-être pas des autorisations nécessaires pour y accéder. Contactez votre administrateur ou reportez-vous à http://aka.ms/guidesdocs.

- Votre version d'application cliente ne prend pas en charge la version de la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Mettez à jour votre application cliente, contactez votre administrateur ou reportez-vous à la documentation en libre-service dans http://aka.ms/guidesdocs.

- Vous ne disposez pas de licence pour utiliser [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Contactez votre administrateur ou [inscrivez-vous à l’évaluation gratuite de l’abonnement]().

#### <a name="staying-on-the-account-picker-for-more-than-25-seconds-during-hololens-sign-in-will-make-it-unresponsive"></a>Le sélecteur de compte ne répond plus si vous restez dedans pendant plus de 25 secondes pendant la connexion à HoloLens

Lorsque vous accédez à l'écran afin de choisir entre différents comptes enregistrés dans [!include[pn-hololens](../includes/pn-hololens.md)], vous devez choisir une option dans les 25 secondes. Au bout de 25 secondes, l'écran se fige et vous devez redémarrer l'application. Ce problème a été résolu dans RS5 mais existe toujours dans RS4 si vous l'avez installée.

#### <a name="create-account-link-when-signing-in-with-a-new-account-doesnt-work"></a>Le lien « Créer le compte » ne fonctionne pas lors de la connexion à un nouveau compte
Lors de la connexion à un nouveau compte sur le PC et les applications [!include[pn-hololens](../includes/pn-hololens.md)], il existe un lien pour créer un compte :

![Écran de connexion](media/sign-in-screen.PNG "Écran de connexion")  
 
N'utilisez pas ce lien pour créer un compte : il ne fonctionne pas.

#### <a name="i-cant-see-guides-that-i-created-or-guides-created-by-my-teammates"></a>Je ne peux pas avoir accès aux guides que j'ai créés ou à ceux créés par mes collègues

Si aucun guide n'est répertorié, soit votre connexion Internet est instable, soit vous êtes connecté à une instance qui n'a aucun guide. Commencez par vérifier votre connexion Internet. Si vous êtes connecté, essayez de vous reconnecter, mais cette fois vérifiez que vous vous connectez bien à l'instance contenant les guides que vous recherchez. Si vous ne voyez toujours aucun guide, contactez votre administrateur.

#### <a name="i-dont-see-media-or-3d-content-that-i-uploaded-to-the-app"></a>Je ne vois pas le support ou le contenu 3D que j'ai téléchargé dans l'application

Lorsque vous chargez du contenu, à ce stade, l'application ne défile pas automatiquement jusqu'à l'endroit de la bibliothèque où le contenu est téléchargé. Pour trouver le contenu, allez dans la bibliothèque (à droite de l'écran), puis sélectionnez l'onglet approprié (**Composants 3D**, **Images**, **Vidéos** ou **Boîte à outils 3D**).

L'application du PC affiche des notifications (dans la barre de titre supérieure) s'il existe des erreurs pendant le chargement. Vérifiez que le format de fichier de votre contenu est correct, comme indiqué dans le tableau suivant. 

|Média|Formats pris en charge|
|--------------|--------------------------------------------|
|Contenu 3D|FBX, GLB, glTF|
|Images|PNG, JPG, JPEG, GIF, TIFF|
|Vidéos|MP4, MOV, WMV|

Si vous ne pouvez toujours pas trouver votre contenu, contactez votre administrateur.

#### <a name="i-have-an-issue-that-isnt-listed-in-these-troubleshooting-steps"></a>J'ai un problème qui n'est pas répertorié dans les étapes de résolution des problèmes

Contactez le service clientèle de [https://docs.microsoft.com/dynamics365/get-started/support/](https://docs.microsoft.com/dynamics365/get-started/support/). Cette page est également disponible en vous connectant à votre compte [!include[pn-dyn-365](../includes/pn-dyn-365.md)] et en sélectionnant le lien **Support**.

### <a name="hololens-application-issues"></a>Problèmes avec l'application HoloLens

#### <a name="i-cant-sign-in"></a>Je ne peux pas me connecter

Pour vous connecter, vous devez utiliser les informations d'identification [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365](../includes/pn-dyn-365.md)] de votre organisation. Elles sont semblables à : johndoe@contoso.onmicrosoft.com. Vous ne pouvez pas utiliser de compte [!include[cc-microsoft](../includes/cc-microsoft.md)] (utilisé pour Outlook.com, [!include[cc-microsoft](../includes/cc-microsoft.md)] Store, etc.) ou vos informations d'identification d'entreprise pour vous connecter. 

Si vous voyez l'une des erreurs suivantes, contactez votre administrateur informatique ou reportez-vous à notre documentation en libre-service dans http://aka.ms/guidesdocs. 

- [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] n'est pas paramétré correctement, ou vous ne disposez peut-être pas des autorisations nécessaires pour y accéder. Contactez l'administrateur ou utilisez le lien de documentation ci-dessous.

- Votre version d'application cliente ne prend pas en charge la version de la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Mettez à jour votre application cliente, contactez votre administrateur ou reportez-vous à la documentation en libre-service dans http://aka.ms/guidesdocs.

- Vous ne disposez pas de licence pour utiliser [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Contactez votre administrateur.

#### <a name="staying-on-the-account-picker-more-than-25-seconds-during-hololens-sign-in-will-make-it-unresponsive"></a>Le sélecteur de compte ne répond plus si vous restez dedans pendant plus de 25 secondes pendant la connexion à HoloLens

Lorsque vous accédez à l'écran afin de choisir entre différents comptes enregistrés dans [!include[pn-hololens](../includes/pn-hololens.md)], vous devez choisir une option dans les 25 secondes. Au bout de 25 secondes, il ne répond plus et vous devez redémarrer l'application. Ce bogue a été résolu dans RS5, mais existe toujours dans RS4 si vous l'avez installée.

#### <a name="printed-anchor-method-requires-users-consent-to-use-the-camera"></a>La méthode de point d'ancrage imprimé requiert le consentement de l'utilisateur pour utiliser la caméra

Lorsque l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] sur [!include[pn-hololens](../includes/pn-hololens.md)] est lancée pour la première fois, elle demande le consentement de l'utilisateur pour utiliser la caméra. Si vous envisagez d'utiliser des points d'ancrage imprimés dans vos guides, vous devez indiquer **Oui** dans cette invite. Vous devez le faire pour chaque appareil sur lequel vous utilisez l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Si cet accord n'a pas été fourni précédemment, vous pouvez accéder au menu **Paramètres** sur [!include[pn-hololens](../includes/pn-hololens.md)] (système d'exploitation) et fournir votre consentement à l'application. 

#### <a name="create-account-link-when-signing-in-with-a-new-account-doesnt-work"></a>Le lien « Créer le compte » ne fonctionne pas lors de la connexion à un nouveau compte

Lors de la connexion à un nouveau compte sur le PC et les applications [!include[pn-hololens](../includes/pn-hololens.md)], il existe un lien pour créer un compte :

![Écran de connexion](media/sign-in-screen.PNG "Écran de connexion") 
  
N'utilisez pas ce lien pour créer un compte : il ne fonctionne pas.

#### <a name="i-dont-see-any-guides-in-the-guides-list"></a>Je ne vois aucun guide dans la liste des guides

Si aucun guide n'est répertorié, soit votre connexion Internet est instable, soit vous êtes connecté à une instance qui n'a aucun guide. Commencez par vérifier votre connexion Internet. Si vous êtes connecté, essayez de vous reconnecter, mais cette fois vérifiez que vous vous connectez bien à l'instance contenant les guides que vous recherchez. Si vous ne voyez toujours aucun guide, contactez votre administrateur.

#### <a name="i-cant-find-the-guide-i-created"></a>Je n'arrive pas à trouver le guide que j'ai créé

Recherchez les guides récemment créés dans l'onglet **Tous** de la liste des guides. La liste **Récents** affiche uniquement les guides ouverts précédemment dans l'appareil et ne contient pas ceux récemment créés dans l'application de création du PC. 

#### <a name="the-profile-picture-shown-in-the-app-is-incorrect"></a>L'image de profil affichée dans l'application est incorrecte 

Vérifiez que vous êtes bien connecté. Pour ce faire, sélectionnez l'image de profil, puis déconnectez-vous et reconnectez-vous avec vos informations d'identification [!include[pn-dyn-365](../includes/pn-dyn-365.md)]. Votre image de profil doit alors s'afficher correctement.

En vous connectant avec des informations d'identification correctes, vous avez la garantie que l'avancement des travaux est correctement suivi dans [!include[pn-dyn-365](../includes/pn-dyn-365.md)].

#### <a name="the-video-preview-on-a-step-is-blurry"></a>L'aperçu visuel est flou sur une étape

L'application [!include[pn-hololens](../includes/pn-hololens.md)] convertit et redimensionne les vidéos lorsqu'elles sont téléchargées pour garantir des performances optimales dans [!include[pn-hololens](../includes/pn-hololens.md)]. Si votre vidéo a été enregistrée à une résolution très élevée ou si elle est extrêmement volumineuse, le processus de transcodage peut en avoir dégradé la qualité. Réenregistrez et chargez une nouvelle vidéo, en gardant la longueur et la résolution à l'esprit.

Il est recommandé de ne pas faire de clips vidéo trop longs (**2 minutes maximum**). Cela permet aux opérateurs de se concentrer sur une tâche significative à la fois et de ne pas trop les assommer. 

#### <a name="deleting-an-asset-from-a-step-from-the-bin-in-the-pc-app-will-remove-all-previously-placed-instances-on-hololens"></a>Le fait de supprimer une ressource d'une étape (à partir de l'emplacement) dans l'application du PC supprimera toutes les instances précédemment placées sur HoloLens

Si vous modifiez un guide existant, dans lequel une ressource a été placée dans un emplacement de l'application du PC et que les instances de cette ressource ont ensuite été placées dans le monde réel dans [!include[pn-hololens](../includes/pn-hololens.md)], le fait de supprimer la ressource de l'emplacement supprime toutes celles placées dans l'espace. Le fait d'ajouter de nouveau la ressource ne restaurera pas les instances publiées. Pour restaurer, appuyez sur le bouton **Annuler** dans l'application du PC pour rétablir la modification.

#### <a name="uploading-gltf-files-with-dependencies-across-different-folders-might-result-in-upload-errors"></a>Le fait de charger des fichiers glTF avec des dépendances entre différents répertoires peut entraîner des erreurs de chargement

Certains fichiers glTF peuvent avoir des dépendances dans d'autres dossiers pour lesquels l'application ne dispose pas forcément d'autorisations lors du chargement. Cela peut entraîner des erreurs ou endommager des modèles 3D dans la galerie. Assurez-vous de disposer d'autorisations pour toutes les dépendances, ou de les placer toutes dans le même dossier lors du chargement des modèles glTF. 

#### <a name="the-see-through-style-when-applied-to-a-3d-model-might-show-gray-areas-instead-of-rendering-textures-properly"></a>Quand le style transparent est appliqué à un modèle 3D, il comporte des zones grises au lieu des textures correctes

Il y a des problèmes lors de l'affichage du style « transparent » sur certains modèles 3D. Certaines surfaces de ces modèles sont grises. Utilisez un autre style si ce problème se produit ou contactez le service client si vous avez vraiment besoin de ce style et que vous avez besoin d'aide.

#### <a name="when-moving-a-3d-model-during-authoring-on-hololens-the-movement-of-the-model-may-seem-slow"></a>En déplaçant un modèle 3D lors de la création sur HoloLens, le mouvement du modèle peut être lent

Pour permettre aux auteurs de placer des modèles 3D soigneusement et précisément, le mouvement par défaut est défini sur lent. Pour indiquer ce paramétrage, la sphère de manipulation autour du modèle sera bleue. Vous pouvez déplacer votre main plus rapidement, ou remuer un peu le modèle pour qu'il se déplace plus rapidement. 

#### <a name="i-have-an-issue-that-isnt-listed-in-these-troubleshooting-steps"></a>J'ai un problème qui n'est pas répertorié dans les étapes de résolution des problèmes
Contactez le service clientèle de [https://docs.microsoft.com/dynamics365/get-started/support/](https://docs.microsoft.com/dynamics365/get-started/support/). Cette page est également disponible en vous connectant à votre compte [!include[pn-dyn-365](../includes/pn-dyn-365.md)] et en sélectionnant le lien **Support**.

### <a name="see-also"></a>Voir aussi

[FAQ Dynamics 365 Guides](faq.md)

