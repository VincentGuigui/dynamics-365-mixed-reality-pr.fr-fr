---
author: Mamaylya
description: Tester et placer des hologrammes à l'aide de l'application Dynamics 365 Guides HoloLens en mode Créer
ms.author: mamaylya
ms.date: 10/29/2019
ms.service: crm-online
ms.topic: article
title: Créer dans l'application HoloLens
ms.reviewer: v-brycho
ms.openlocfilehash: 0d8969c5a7a55fd4c8ddd4b328a2db8f533d61b0
ms.sourcegitcommit: 5d57bc15af21d18e21b1ec8db0ec046aea997917
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/30/2019
ms.locfileid: "2692096"
---
# <a name="author-in-the-hololens-application-for-dynamics-365-guides"></a>Créer dans l'application HoloLens pour Dynamics 365 Guides

[Visionner une vidéo sur la création sur HoloLens](https://aka.ms/hololensauthor)

La deuxième étape importante de la création d'un guide dans [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] se déroule dans l'application [!include[pn-hololens](../includes/pn-hololens.md)]. En mode Créer [!include[pn-hololens](../includes/pn-hololens.md)], vous pouvez effectuer ce qui suit :

- Ancrer le guide.

- Placer le contenu 3D holographique dans l'espace approprié dans le monde réel.

- Ajouter des lignes pointillées pour joindre visuellement les étapes aux objets physiques du monde réel.

- Ajouter des styles (facultatif) au contenu 3D pour ajouter des indications, comme un avertissement ou une mise en garde.

- Tester la fluidité du guide.

  ![Tester votre guide](media/test-your-guide.PNG "Tester votre guide")

## <a name="install-the-hololens-app"></a>Installer l'application HoloLens

Si vous n'avez pas encore installé l'application [!include[pn-hololens](../includes/pn-hololens.md)] sur votre appareil [!include[pn-hololens](../includes/pn-hololens.md)] (ou si elle n'a pas encore été installée pour vous), installez-la à partir du [!include[cc-microsoft](../includes/cc-microsoft.md)] Store pour les consommateurs.

Pour installer l'application HoloLens :

1.  Vérifiez que la version 10.0.14393.0 ou ultérieure [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-hololens](../includes/pn-hololens.md)] est bien installée sur votre appareil [!include[pn-hololens](../includes/pn-hololens.md)]. Nous vous recommandons de mettre à jour vers des versions plus récentes quand elles sont disponibles. Voir [Gérer les mises à jour vers HoloLens](https://docs.microsoft.com/HoloLens/hololens-updates) pour obtenir des instructions sur l'utilisation de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Update pour Entreprise.

2.  Dans [!include[pn-hololens](../includes/pn-hololens.md)], utilisez l'[écartement des doigts paume vers le haut](authoring-gestures.md) pour ouvrir le menu **Accueil**, puis ouvrez [!include[cc-microsoft](../includes/cc-microsoft.md)] Store et recherchez [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

3.  Sélectionnez **Installer** pour télécharger et installer l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

### <a name="sign-in-to-the-hololens-app"></a>Se connecter à l'application HoloLens
Si vous vous connectez à un tout nouvel appareil [!include[pn-hololens](../includes/pn-hololens.md)], vous serez invité à parcourir l'Assistant Installation. Dans l'Assistant Installation, vous pouvez vous connecter avec un compte existant ou en créer un nouveau, en fonction de la version de [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] que vous exécutez. L'Assistant Installation vous guide également via des étapes pour étalonner et préparer votre [!include[pn-hololens](../includes/pn-hololens.md)] en vue de son utilisation.

#### <a name="calibrate-your-hololens"></a>Étalonner HoloLens

Pour afficher des hologrammes dans les emplacements corrects, la distance interpupillaire (DIP) doit être définie. Ceci s'applique à tous les utilisateurs [!include[pn-hololens](../includes/pn-hololens.md)], qu'ils soient auteur ou opérateur. Dans un contexte industriel où les hologrammes servent à diriger l'opérateur dans l'exécution de ses tâches, il est essentiel que les hologrammes soient alignés correctement. Cela peut sinon provoquer de la confusion chez l'opérateur et engendrer des dommages onéreux.

Si vous ne configurez pas le DIP pour chaque utilisateur : 

- Les hologrammes seront décalés de 1 ou 2 cm. 

- Les hologrammes vont s'afficher comme s'ils étaient enfoncés ou comme s'ils flottaient au-dessus des surfaces sur lesquelles ils reposent.

- Les hologrammes ne seront pas stables. Vous remarquerez qu'ils bougent quand vous vous déplacez.

> [!IMPORTANT] 
> Il est particulièrement important que les auteurs s'assurent que leur DIP est défini correctement. Sinon, tous les opérateurs qui utilisent le guide verront des hologrammes mal alignés. 

Pour définir votre DIP, utilisez l'application d'étalonnage incluse dans [!include[pn-hololens](../includes/pn-hololens.md)] et procédez comme suit : 

1.  Écartez les doigts paume vers le haut pour lancer le menu **Démarrer**.

2.  Cliquez dans l'air sur **Étalonnage** pour commencer à étalonner votre [!include[pn-hololens](../includes/pn-hololens.md)].

    ![Application d'étalonnage](media/hololens-calibration.PNG "Application d'étalonnage")
 
3.  Suivez les instructions affichées dans [!include[pn-hololens](../includes/pn-hololens.md)].

Chaque utilisateur doit effectuer cet étalonnage une fois connecté à l'appareil. Si [!include[pn-hololens](../includes/pn-hololens.md)] exécute [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Holographic for Business edition, le paramètre DIP sera enregistré sur l'appareil. Lorsque les utilisateurs se connectent dans le même [!include[pn-hololens](../includes/pn-hololens.md)], leur paramètre DIP est appliqué automatiquement même après avoir changé d'utilisateur, ils n'ont pas besoin d'étalonner à nouveau. Toutefois, si [!include[pn-hololens](../includes/pn-hololens.md)] exécute l'édition [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Holographic, les paramètres utilisateur ne sont pas enregistrés, car cette version de votre système d'exploitation est conçue pour un seul utilisateur. Chaque fois que vous changez d'utilisateur, vous devez étalonner à nouveau l'appareil. 

Pour déterminer la version utilisée par votre système d'exploitation dans [!include[pn-hololens](../includes/pn-hololens.md)]: 

1.  Écartez les doigts paume vers le haut pour lancer le menu **Démarrer**.

2.  Cliquez dans l'air sur **Paramètres > Système**.
 
3.  Cliquez dans l'air sur **À propos**.
 
### <a name="open-and-sign-in-to-hololens-for-the-first-time"></a>Ouvrir et se connecter à HoloLens pour la première fois

Après avoir vérifié que [!include[pn-hololens](../includes/pn-hololens.md)] est correctement étalonné, vous pouvez ouvrir l'application [!include[pn-hololens](../includes/pn-hololens.md)].
1.  Accédez à **Toutes les applications**.

    ![Sélection d'applications HoloLens](media/hololens-apps.PNG "Sélection d'applications HoloLens")

2.  Sélectionnez la flèche vers le bas.

    ![Flèche vers le bas HoloLens en surbrillance](media/hololens-down-arrow.PNG "Flèche vers le bas HoloLens en surbrillance")

3.  Ouvrez l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

    ![Lancer Guides](media/open-guides-application.PNG "Lancer Guides")
 
4.  Dans l'écran de **Bienvenue**, sélectionnez **Se connecter**. 

5.  Dans l'écran **E-mail et comptes**, sélectionnez **Compte professionnel ou scolaire**, puis sélectionnez **Continuer**. 

6.  Dans l'écran **Compte professionnel ou scolaire**, entrez les informations d'identification que vous avez créées lors de l'abonnement d’essai ou celles fournies par l'administrateur qui a installé l'application. 

    ![Connectez-vous à HoloLens](media/sign-in-hololens.PNG "Se connecter à HoloLens")
 
7.  Sélectionnez l'instance à utiliser si vous en avez plusieurs, puis sélectionnez **Continuer**.

8. Dans l'écran **Sélectionner un guide**, pointez du regard le guide que vous souhaitez ouvrir jusqu'à ce que le cercle se remplisse, ce qui sélectionne ce guide.

    ![Écran Sélectionner un guide](media/select-guide.png "Écran Sélectionner un guide")

9.  Dans la boîte de dialogue **Sélectionner un mode**, pointez du regard la zone à gauche d'**Auteur** pour la sélectionner. 

    ![Sélectionner le mode Créer](media/select-mode.png "Sélectionner le mode Créer")
    
> [!TIP]
> [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] est fourni avec un guide illustratif que vous pouvez utiliser pour obtenir des idées pour vos propres guides. Découvrez-le !</br><br>![Guide illustratif](media/example-guide-hololens.png "Guide illustratif")

## <a name="anchor-your-guide"></a>Ancrer le guide
La première chose qui s'affiche lorsque vous ouvrez un guide ce sont les instructions d'ancrage de l'application de création du PC. 

### <a name="to-anchor-a-guide-using-a-printed-anchor"></a>Pour ancrer un guide à l'aide d'un point d'ancrage imprimé

1. Tenez-vous à environ deux mètres du point d'ancrage imprimé.

2. Dans l'écran **Analyser le point d'ancrage imprimé**, sélectionnez **Lancer l'analyse**.

   ![Écran Analyser le point d'ancrage imprimé avec le bouton Lancer l'analyse](media/scan-printed-anchor.png "Écran Analyser le point d'ancrage imprimé avec le bouton Lancer l'analyse")

   Dans [!include[pn-hololens](../includes/pn-hololens.md)], un hologramme de point d'ancrage semblable à celui-ci s'affiche :

   ![Image d'un marqueur holographique](media/scanning.PNG "Image d'un marqueur holographique")
   
3. Fixez le point d'ancrage imprimé avec votre [!include[pn-hololens](../includes/pn-hololens.md)] jusqu'à ce qu'un contour vert apparaisse. Effectuez un pointage du regard pour aligner la zone verte à cocher sur le marqueur, puis sélectionnez **Confirmer**.

   ![Aligner le marqueur](media/align-marker.PNG "Aligner le marqueur")

   Lorsque le guide est correctement aligné, vous verrez l'écran **Point d'ancrage imprimé trouvé**. 
   
   ![Marqueur holographique trouvé](media/printed-anchor-found.png "Marqueur holographique trouvé")
   
### <a name="to-anchor-a-guide-using-a-digital-anchor"></a>Pour ancrer un guide à l'aide d'un point d'ancrage numérique

- Cliquez longuement dans l’air pour déplacer et aligner le point d'ancrage numérique à ses équivalents du monde réel. Pour faire pivoter l'ancre, appuyez longuement sur les sphères bleues.

   ![Faire pivoter le point d'ancrage numérique](media/rotate-digital-anchor.PNG "Faire pivoter le point d'ancrage numérique")

### <a name="re-anchor-a-guide"></a>Ancrer à nouveau un guide

Lorsque vous ancrez votre guide, les informations d'ancrage sont enregistrées dans votre [!include[pn-hololens](../includes/pn-hololens.md)], vous n'avez donc pas à ancrer à nouveau le guide chaque fois que vous l'ouvrez. Vous pouvez toutefois ancrer à nouveau un guide à tout moment, si vous estimez que les hologrammes ne sont pas bien alignés. Pour plus d'informations, consultez les informations sur le bouton **Ancrer** dans la section suivante.

> [!NOTE]
> Vous devrez peut-être ajuster le décalage du matériel dans les appareils [!include[pn-hololens](../includes/pn-hololens.md)] 1 pour garantir le positionnement exact du contenu 3D. [En savoir plus sur l'ajustement du décalage du matériel](https://docs.microsoft.com/dynamics365/mixed-reality/guides/known-issues#uploading-new-3d-models-with-names-matching-any-of-the-pre-packaged-models-in-the-3d-toolkit-will-overwrite-the-files-in-the-3d-toolkit).

## <a name="get-oriented-on-hololens"></a>Se repérer dans HoloLens
Après avoir ancré votre guide, la fiche étape s'affiche. Elle rassemble tout ce que vous effectuez avec votre guide et la manière dont vous parcourez l'application. Elle s'affiche également pour votre opérateur lorsqu'il utilise le guide. La fiche étape suit l'opérateur afin qu'il puisse avoir les instructions nécessaires lorsqu'il se déplace dans sa zone de travail.

Parcourez le guide en pointant du regard les flèches **Étape suivante** et **Retour**. Vous pouvez également faire des mouvements comme cliquer dans l'air pour parcourir un guide. 

![Accéder à un guide](media/navigate-example.PNG "Accéder à un guide")

Il y a trois boutons en haut de l'écran de la fiche étape : **Enregistrer**, **Annuler** et **Rétablir**.

![Écran de la fiche étape HoloLens](media/save-undo-redo.png "Écran de la fiche étape HoloLens")
 
Les boutons **Annuler** et **Rétablir** fonctionnent comme **Annuler** et **Rétablir** dans n'importe quel programme Microsoft Office. Vous pouvez annuler 100 modifications ou rétablir 100 modifications.  

> [!NOTE]
> Les modifications sont enregistrées automatiquement dans le cloud lorsque vous travaillez dans [!include[pn-hololens](../includes/pn-hololens.md)]. Vous devez simplement sélectionner **Actualiser** lorsque vous revenez sur le PC pour être sûr d'avoir la dernière version du guide.

La fiche étape inclut également plusieurs autres boutons et éléments de l'IU :

![Boutons HoloLens](media/step-card-orientation-2.PNG "Boutons HoloLens")
 
Voici à quoi sert chaque bouton ou élément d'IU :

|Nombre|Bouton/Exemple|Nom|Objectif|
|--|---|------------|----------------------------------------------------------------------------------------------------------------|
|1|![Bouton Accueil](media/home-button.png "Bouton Accueil")|Accueil|Choisissez un autre guide.|
|2|![Bouton Mode suivi](media/follow-button.png "Bouton Mode suivi")|Mode suivi|Faites en sorte que la fiche étape vous suive ou verrouillez-la à un emplacement.<br><br>Guides contient une fonctionnalité appelée Mode suivi. Où que vous regardiez, la fiche étape suit votre regard, ainsi vous savez toujours où se trouvent les instructions. Lorsque vous désactivez le Mode suivi, la fiche reste où elle est. Vous pouvez saisir la fiche à tout moment à l'aide de la barre de navigation et la déplacer où vous voulez. |
|3|![Bouton Ancrer](media/anchor-button.PNG "Bouton Ancrer")|Ancrer|Ancrez à nouveau (réalignez) votre guide.<br><br>Il arrive qu'[!include[pn-hololens](../includes/pn-hololens.md)] ne puisse plus se repérer. Pour résoudre ce problème, vous devez ancrer à nouveau le guide en pointant du regard le point d'ancrage imprimé (marquer) ou le point d'ancrage numérique.|
|4|![Bouton Paramètres](media/settings-button.png "Bouton Paramètres")|Paramètres|Accédez aux paramètres suivants :</br><br>- **Ajuster la zone**. Utilisez ce paramètre pour vous assurer que vous tenez correctement l'appareil [!include[pn-hololens](../includes/pn-hololens.md)].<br>- **Numéro de version**. Affiche la version que vous utilisez.|
|5|![Bouton Profil](media/profile-button.png "Bouton Profil")|Profil|Connexion et déconnexion.|
|6|![Progression d'étape](media/step-progress.PNG "Progression d'étape")|Progression d'étape|Indique où vous êtes dans l'étape.|
|7|![Bouton Plan](media/outline-button.png "Bouton Plan")|Plan|Allez à la page **Plan**.<br><br>Utilisez la page **Plan** pour parcourir rapidement votre guide.|
|8|![Nom de la tâche](media/task-name-table.PNG "Nom de la tâche")|Nom de la tâche|Le nom de la tâche.|
|9|![Progression de la tâche](media/task-progress.PNG "Progression de la tâche")|Progression de la tâche  |Indique où vous êtes dans la tâche en cours.|

## <a name="test-the-flow-of-your-guide"></a>Tester la fluidité du guide
Une fois que vous vous êtes repéré(e) dans [!include[pn-hololens](../includes/pn-hololens.md)], nous vous recommandons de parcourir le guide en entier en mode Opérer pour en tester la fluidité. Lorsque vous parcourez le guide, notez ce que vous souhaitez modifier dans l'application du PC. Vous pouvez par exemple avoir à déplacer certaines étapes, ajouter des tâches ou des opérations, ou ajouter des ressources de prise en charge. Il est généralement préférable d'effectuer ces modifications dans l'application du PC avant de commencer à placer des hologrammes, des attaches et d'appliquer des styles. 
 
## <a name="add-a-dotted-line-to-link-a-step-card-to-a-focus-area"></a>Ajouter une ligne pointillée pour associer une fiche étape dans une zone ciblée

Vous pouvez ajouter des lignes pointillées (*attaches*) pour lier vos fiches étape aux zones où le travail est effectué. Ces lignes pointillées affichent l'opérateur sur lequel vous concentrer. 

![Lignes pointillées holographiques](media/tether-example.png "Lignes pointillées holographiques")

Pour placer une ligne pointillée :

1.  Appuyez longuement sur la gemme sous la fiche étape.

2.  Faites-la glisser vers l'emplacement du monde réel que vous souhaitez.

    ![Placer une ligne pointillée](media/place-tether.PNG "Placer une ligne pointillée")

### <a name="best-practices-for-dotted-lines"></a>Pratiques recommandées pour les lignes pointillées

- Le placement n'est pas précis, donc si vous connectez une ligne pointillée à un objet 3D à partir de la boîte à outils 3D, vous devez placer la ligne pointillée dans la zone générale, puis placer l'objet 3D (un numéro, par exemple) à la fin de la ligne pointillée. 

## <a name="place-your-holograms"></a>Placer des hologrammes

À ce stade du processus, vous devez parcourir chaque étape de votre guide et placer toutes les ressources que vous avez associées à cette étape lorsque vous l'avez créée dans l'application du PC. Par exemple, si vous avez ajouté un composant 3D pour prendre en charge une étape, vous devez placer ce composant par-dessus son homologue physique dans le monde réel. Si vous avez ajouté un objet 3D à partir de la boîte à outils 3D (une flèche ou un chiffre, par exemple), vous devez placer cet objet dans un emplacement approprié dans le monde réel pour attirer l'attention de l'utilisateur. Vous pouvez placer le même composant 3D ou le même objet 3D autant de fois que vous voulez.

Vous n'avez rien à faire pour placer une image ou une vidéo associée à une étape. Elles s'affichent automatiquement lorsque l'opérateur arrive à l'étape.

Les ressources 3D associées à chaque étape s'affichent sous la fiche étape dans l'emplacement :

![Ressources 3D sous une fiche étape](media/step-card-bin.png "Ressources 3D sous une fiche étape")

### <a name="place-a-3d-part"></a>Placer un composant 3D 

1. Dans l'emplacement, cliquez dans l'air sur le composant 3D que vous souhaitez placer.

2. Utilisez le pointage du regard et les mouvements pour placer l'hologramme du composant 3D par dessus son homologue physique dans le monde réel. Reportez-vous à la section suivante pour obtenir des informations sur la manipulation des hologrammes avec le pointage du regard et les mouvements.

### <a name="place-a-3d-model-from-the-3d-toolkit"></a>Placer un modèle 3D à partir de la boîte à outils 3D

Vous pouvez placer un modèle 3D à partir de la boîte à outils 3D de la même manière que vous placez un composant 3D si vous avez ajouté ce modèle 3D à l'emplacement dans l'application du PC. Si vous n'avez pas ajouté le modèle 3D dans l'application du PC, vous pouvez le faire directement à partir de l'application [!include[pn-hololens](../includes/pn-hololens.md)] : 

1.  Cliquez dans l'air sur une zone vide de l'emplacement (sous **Composants 3D**).

2.  Cliquez dans l'air sur une catégorie (une flèche ou une main, par exemple), puis sur le modèle 3D spécifique que vous souhaitez ajouter.

    ![Cliquer dans l'air sur une catégorie](media/step-card-hands.png "Cliquer dans l'air sur une catégorie")

    L'élément est alors ajouté à votre emplacement et vous pouvez ensuite le placer comme vous le feriez pour un composant 3D.

### <a name="manipulating-holograms"></a>Manipuler des hologrammes

Pour placer un modèle 3D à partir de l'un de vos emplacements :

1.  Cliquez dans l'air sur un modèle 3D pour l'ajouter à votre monde réel. Il apparaît dans votre monde réel devant la fiche étape.

2.  Levez la main pour indiquer que vous êtes prêt et pointez du regard le modèle pour en afficher l'aperçu. Les contrôles 3D apparaissent autour de la ressource et indiquent ainsi qu'elle est à l'état Aperçu.

    Si vous baissez la main, les contrôles 3D disparaissent. Ainsi, si vous regardez des hologrammes, les contrôles ne vous gênent pas. Vous devez regarder la pièce tout en levant la main pour indiquer que vous êtes prêt.

3. Avec les contrôles visibles, cliquez longuement dans l'air n'importe où sur le contrôle de mouvement pour sélectionner le modèle. Déplacez le modèle vers l'emplacement souhaité, puis relâchez pour le placer.

> [!NOTE]
> Lorsque vous appuyez sur un composant 3D pour le déplacer, vous le sélectionnez en même temps. Une fois sélectionné, lorsque vous baissez la main, les contrôles 3D restent jusqu'à ce que vous prévisualisiez ou sélectionniez un autre composant, ou que vous cliquez dans l'air n'importe où dans l'espace vide.
 
#### <a name="rotate-a-hologram"></a>Faire pivoter un hologramme

Il n'est peu probable qu'une ressource soit orientée correctement lorsque vous la placez ou la déplacez pour la première fois. Utilisez les contrôles de rotation pour la faire pivoter comme vous le souhaitez.

Pour faire pivoter un hologramme :

- Cliquez longuement dans l'air sur un contrôle de rotation, puis effectuez l'une des opérations suivantes :

  - Utilisez la sphère haut/bas pour faire pivoter verticalement.
  
  - Utilisez la sphère gauche/droite pour faire pivoter horizontalement.
  
  - Utilisez la sphère main libre pour faire pivoter dans n'importe quelle direction.

>[!Tip]
> Pointez du regard les sphères pour savoir dans quelle direction elles vont pivoter.

Lors d'une rotation, vous avez alors l'impression d'attraper physiquement la sphère et de tourner autour de l'objet, comme une roue.
Les graphiques suivants montrent comment utiliser les différents contrôles de rotation :

Rotation libre

![Rotation libre](media/free-rotation.PNG "Rotation libre")

Rotation gauche/droite

![Rotation gauche/droite](media/left-right-rotation.PNG "Rotation gauche/droite")

Rotation haut/bas

![Rotation haut/bas](media/up-down-rotation.PNG "Rotation haut/bas")
 
> [!Important]
> Pour manipuler les hologrammes efficacement, vérifiez que votre [!include[pn-hololens](../includes/pn-hololens.md)] est étalonné correctement. 

#### <a name="change-the-size-of-a-hologram-after-placing-it"></a>Modifier la taille d'un hologramme après l'avoir placé

- Cliquez longuement dans l'air sur le contrôle **Mettre à l'échelle un hologramme**, puis déplacez votre main vers le haut ou le bas.  

   ![Changer la taille des hologrammes](media/scale-hologram.PNG "Changer la taille des hologrammes")

### <a name="best-practices-for-working-with-3d-content"></a>Pratiques recommandées pour utiliser le contenu 3D

- Assurez-vous que le contenu 3D ne gêne pas l'opérateur qui effectue la tâche. 

- Gardez le champ de vision à l'esprit quand vous placez des ressources. Si vous placez un hologramme derrière quelqu'un, il sera très difficile à trouver.

- Utilisez le contenu 3D avec parcimonie et en ayant une objectif clair en tête. Trop de contenu risque de parasiter les instructions et les rendre plus difficiles à suivre.

- N'oubliez pas que vous pouvez lier une attache au contenu 3D pour le rendre facile à détecter. Consultez la section suivante pour en savoir plus sur les attaches.

## <a name="turn-off-animations"></a>Désactiver les animations

Si vous utilisez des modèles 3D animés dans le guide, vous pouvez désactiver les animations si vous envisagez de les afficher dans une étape et de ne pas les afficher dans un autre. Cette option est disponible dans le menu **Modifier** lorsque vous sélectionnez le modèle.

![Désactiver les animations](media/edit-animations.png "Désactiver les animations")

Vous pouvez également utiliser cette option lorsque vous appliquez des modèles animés dans l'espace. Arrêtez l'animation, placez le modèle, puis activez de nouveau l'animation. Ainsi l'animation ne vous empêchera pas de placer le modèle.

## <a name="add-styles-for-emphasis"></a>Ajouter des styles pour souligner l'importance
Utilisez les styles pour fournir des repères visuels pour donner plus d'importance. Par exemple, ajoutez le style Avertissement pour faire preuve de prudence ou le style Mise en garde pour garantir qu'un opérateur ne fasse rien qui pourrait causer un dommage. Une fois les opérateurs habitués au langage visuel fourni par les styles, ils verront leur processus d'apprentissage s'accélérer.

> [!Note]
> Pour le moment, vous ne pouvez pas ajouter de styles à partir de l'application du PC. Ils se trouvent uniquement dans [!include[pn-hololens](../includes/pn-hololens.md)]. 

Pour placer un style :

1.  Cliquez dans l'air sur un hologramme que vous avez déjà placé dans le monde réel pour le sélectionner.

2.  Cliquez dans l'air sur le bouton **Modifier l'hologramme**.

    ![Bouton Modifier l'hologramme](media/edit-hologram.PNG "Bouton Modifier l'hologramme")

3.  Cliquez dans l'air sur **Styles**. 

    ![Modifier les styles](media/edit-styles.PNG "Modifier les styles")
 
4.  Sélectionnez le style à utiliser.

    ![Liste des styles](media/styles.PNG "Liste des styles")
 
Voici la liste des styles inclus dans [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et quand les utiliser :

|Style  |Objectif    |Comment cela apparaît pour l'opérateur|
|---------------|-------------------|--------------------------------------------|
|Original|Restauration à l'apparence d'origine.   |Apparence par défaut|
|Choisir    |Indique à l'opérateur de choisir un élément.    |Plan|
|Placer  |Indique à l'opérateur où placer un élément.    |Trait en pointillé|
|Transparent 1  |Affiche un élément sans masquer ce que voit l'opérateur.  |Transparent à 50 %|
|Transparent 2  |Superpose un élément sur un autre pour que l'opérateur puisse afficher deux couches.  |Transparent à 75 %|
|Avertissement    |Avertit d'un problème de sécurité ou de qualité.    |Rayé jaune et noir|
|Éviter  |Indique des zones ou des éléments à éviter. |Voyant rouge clignotant|
|Rayon X  |Indique des choses qui se produisent à l'intérieur d'un élément.  |Affiche une impulsion par son biais|
|Métal  |Donne une finition réaliste en métal à un objet.    |Métallique|

![Tous les styles](media/all-styles.PNG "Tous les styles")
 
### <a name="best-practices-for-styles"></a>Meilleures pratiques pour les styles

- Appliquez des styles pour renforcer les actions.

- Appliquez des styles uniquement pour l'objectif visé. Lorsque les opérateurs apprennent le langage visuel des styles, ils savent qu'un style particulier veut dire une certaine chose, ce qui accélère le processus d'apprentissage. 

## <a name="duplicate-a-3d-model-to-use-for-similar-items"></a>Dupliquer un modèle 3D pour l'utiliser pour des éléments similaires

Vous avez parfois besoin de plusieurs copies des mêmes modèles 3D pour indiquer des éléments similaires dans la zone de travail. Plutôt que d'ajouter de nouvelles instances d'un modèle 3D à partir de l'emplacement de la ressource et de devoir définir la position et le style à chaque fois, vous pouvez gagner du temps en dupliquant le modèle 3D. La duplication conserve les paramètres de style et de rotation d'origine.

Pour dupliquer un modèle :

1.  Cliquez dans l'air sur un hologramme que vous avez déjà placé dans le monde réel pour le sélectionner.

2.  Cliquez dans l'air sur le bouton **Modifier l'hologramme**.

    ![Bouton Modifier l'hologramme](media/edit-hologram.PNG "Bouton Modifier l'hologramme")
    
3. Sélectionnez **Dupliquer**.

    ![Bouton Dupliquer](media/edit-duplicate.PNG "Bouton Dupliquer")
    
## <a name="opt-out-of-sending-telemetry-data-to-microsoft"></a>Je n'accepte pas d'envoyer de données de télémétrie à Microsoft.

Pour des raisons de confidentialité, vous pouvez désactiver l'option d'envoi de données de télémétrie à Microsoft. Microsoft utilise ces données pour améliorer le produit. La désactivation empêche Microsoft de collecter des données d'activité.

Pour désactiver des données de télémétrie pour HoloLens :

- Dans **Paramètres**, désactivez le curseur **Envoyer les données d'utilisation**.

    ![Paramètre Envoyer les données d'utilisation](media/send-usage-data.PNG "Paramètre Envoyer les données d'utilisation")
    
> [!NOTE]
> Cette option s'applique uniquement au périphérique pour lequel elle est définie. Si vous utilisez Dynamics 365 Guides sur plusieurs périphériques, vous devez modifier le paramètre dans ces autres périphériques. Pour désactiver ce paramètre pour l'application du PC, voir [Créer un guide dans l'application du PC](pc-authoring.md). 

## <a name="whats-next"></a>Étapes suivantes

Voici quelques liens utiles pour en savoir plus sur [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] :

- [Utiliser un guide comme opérateur](operator-guide.md)
- [Analyser les instructions pour améliorer l'efficacité](analytics-guide.md)
- [FAQ](faq.md)

Pour en savoir plus sur les applications de réalité mixte [!include[pn-hololens](../includes/pn-hololens.md)] et [!include[cc-microsoft](../includes/cc-microsoft.md)], cliquez sur les liens suivants : 

- [Qu'est-ce que la réalité mixte](https://docs.microsoft.com/windows/mixed-reality/mixed-reality) ?
- [Microsoft Dynamics 365 Layout](https://dynamics.microsoft.com/mixed-reality/layout/)
- [Microsoft Dynamics 365 Remote Assist](https://dynamics.microsoft.com/mixed-reality/remote-assist/)
- [Se connecter au WiFi sur HoloLens](https://docs.microsoft.com/windows/mixed-reality/connecting-to-wi-fi-on-hololens)
- [Étalonner HoloLens](https://docs.microsoft.com/windows/mixed-reality/calibration)
