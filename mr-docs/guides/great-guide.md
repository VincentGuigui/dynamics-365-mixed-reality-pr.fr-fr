---
author: Mamaylya
description: En savoir plus sur ce qu'il faut faire et ne pas faire pour créer avec succès un guide de réalité mixte dans Dynamics 365 Guides
ms.author: mamaylya
ms.date: 10/01/2019
ms.service: crm-online
ms.topic: article
title: Création d'un bon guide de réalité mixte dans Dynamics 365 Guides
ms.reviewer: v-brycho
ms.openlocfilehash: bb075579c058b8e30393506aae70f0d75bc101fd
ms.sourcegitcommit: f37698eb33fd4d198b054e73ce3d9ec680c56e21
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/02/2019
ms.locfileid: "2537249"
---
# <a name="how-to-make-a-great-mixed-reality-guide"></a>Création d'un excellent guide de réalité mixte

D'autres documents en ligne dans [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] visent à vous apprendre à utiliser les applications [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et leurs diverses fonctionnalités. Ce document décrit comment créer le contenu d'un guide pour transmettre au mieux des instructions à vos opérateurs. Nous vous conseillons de lire d'abord tous les autres documents pour bien comprendre comment utiliser les applications [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], puis de vous reporter à cette documentation pour commencer à créer des guides de qualité.

## <a name="get-started"></a>Mise en route

### <a name="gather-content"></a>Collecter du contenu

Collectez autant de contenu que vous pouvez avant de commencer à créer votre guide. Cela inclut des images, des vidéos, et du contenu 3D (si vous en avez) et les objets physiques eux-mêmes (si possible). Ne vous inquiétez pas si vous n'avez pas de contenu 3D. Guides inclut une boîte à outils 3D (contenant des modèles simples comme des flèches, des mains, des zones, etc.) que vous pouvez utiliser pour commencer.

### <a name="understand-the-space"></a>Comprendre l'espace

Vous devez bien connaître l'espace, la procédure, ainsi que le flux de travail faisant l'objet de votre création. Assurez-vous d'avoir suffisamment d'espace pour bien comprendre l'environnement du monde réel. Vous aurez également besoin d'avoir de l'espace pour aligner le guide et placer des hologrammes ultérieurement.

### <a name="build-references"></a>Créer des références

Une bonne manière de commencer consiste à créer une vidéo de la procédure que vous souhaitez montrer, ou de demander à quelqu'un (un expert en la matière, par exemple) d'en créer une pour vous. Vous pouvez vous reporter à la vidéo à mesure que vous créez votre guide. Si vous utilisez une vidéo comme point de départ, assurez-vous qu'elle soit bien représentative du guide que vous voulez créer. Est-ce que vous créez un guide pour un expert ou un novice, par exemple ?

### <a name="understand-your-lesson-objectives-and-target-audience"></a>Comprendre les objectifs de la leçon et le public cible

Il est important de comprendre les objectifs de la leçon et le public cible avant de développer votre guide. Les objectifs de la leçon comprennent plusieurs sous-objectifs nécessaires pour atteindre un objectif [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] global. En outre, comprendre votre public cible vous aidera à personnaliser votre guide pour fournir le degré de complexité nécessaire pour transmettre des informations à vos opérateurs. Par exemple, votre public comprendra-t-il comment utiliser des outils spécifiques ou les noms de machine spécifique ?

## <a name="authoring-features-you-can-you-use-to-make-a-great-guide"></a>Fonctionnalités de création permettant de créer un bon guide

### <a name="guide-structure"></a>Structure du guide

#### <a name="tasks"></a>Tâches

- Lorsque vous organisez la structure d'un guide pour la première fois, décomposez le processus d'assemblage en objectifs logiques clés (tâches).

  – Considérez les tâches comme des points de contrôle clés tout au long du guide.
  
  – À la fin de chaque tâche, l'opérateur doit atteindre un objectif important.
  
- Les tâches ne doivent contenir qu'un seul objectif principal. Si une tâche contient plusieurs objectifs principaux, décomposez-la en deux tâches ou plus. Cela permettra à l'opérateur de conserver l'organisation du guide, et donc d'améliorer la rétention.

- Les tâches doivent suivre une séquence logique d'actions.

- Lorsque vous commencez à créer un guide, parlez du processus d'assemblage à haute voix : comment communiqueriez-vous verbalement ce processus à quelqu'un en personne ?

- Pour fournir un contexte général, ajoutez une tâche de présentation et/ou de bienvenue au début du guide. 

  ![Exemple de présentation](media/overview.PNG "Exemple de présentation")

  Cette tâche peut contenir les étapes suivantes :

  - Une étape qui décrit l'objet du guide.

  - Une étape avec une liste de toutes les tâches du guide. Cela permettra de créer une feuille de route du processus d'assemblage pour l'opérateur, et donc d'améliorer la rétention.

  - Si la sécurité est une préoccupation majeure, vous pouvez ajouter une étape supplémentaire axée sur des mesures de sécurité spécifiques que les opérateurs doivent prendre avant de commencer le guide.

- Les tâches ne doivent pas contenir plus de 30 étapes. Si une tâche contient plus de 30 étapes, décomposez-la en deux tâches ou plus. Notre étude montre qu'un trop grand nombre d'étapes dans une tâche risque de submerger un opérateur, surtout s'il apprend la procédure pour la première fois.

#### <a name="steps"></a>Étapes

- Contrairement aux instructions traditionnelles, le texte d'une étape dans [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] n'est pas censé tout décrire, car vous avez des aides visuelles supplémentaires comme des images, des vidéos et des hologrammes 3D.

   –    Lorsque vous rédigez une étape, tenez compte des différentes formes de communication que vous utilisez.
   
   –    Essayez de vous limiter à un type de ressource (image, vidéo ou hologramme 3D) par étape. S'il y a trop de support ou de contenu 3D, cela peut assommer l'opérateur et être trop long à intégrer. Réfléchissez au type de contenu qui est le plus percutant.
   
   –    En général, les opérateurs vont lire le texte, regarder les images ou les vidéos, suivre la ligne pointillée et observer les hologrammes 3D. 
   Gardez cet ordre d'opérations à l'esprit lorsque vous rédigez une étape.
   
- Il est primordial de garder votre public à l'esprit lorsque vous rédigez une étape. Votre public :

   –    Connaît-il les noms des outils spécifiques et leur fonction ?
   
     - Si oui, vous pouvez utiliser moins de détails, car vous n'avez pas besoin d'expliquer les outils ou les pièces.
      
     - Sinon, vous devez ajouter des descriptions et des visuels supplémentaires pour aider les opérateurs.
      
     - Pour le grand public, décrivez des objets uniques (pièces ou outils personnalisés), et non des objets génériques (outils génériques).
      
   –    Comprend-il les exigences de sécurité de base ?
   
   –    Comprend-il les différents indices et conditions environnementaux ?
   
- N'ayez pas peur d'avoir beaucoup d'étapes.

   –    Gardez à l'esprit que les étapes doivent être courtes pour de meilleurs résultats.
   
   –    Si une étape comporte plusieurs phrases, notre étude montre que les opérateurs vont souvent lire la première phrase, essayer d'effectuer l'action et ignorer le reste du contenu de l'étape.
   
     Exemple incorrect :
     
     ![Phrases multiples](media/bad-example.PNG "Phrases multiples")
     
     Exemple correct :
     
     ![Idée unique](media/good-example.PNG "Idée unique")     
       
     Dans cet exemple, de nombreux opérateurs risquent de manquer la deuxième phrase et de passer à l'étape suivante.

- Utilisez un langage simple et familier.

   –    Soyez concis.
   
   –    Rédigez le guide dans un langage familier pour des résultats optimaux. N'utilisez pas de jargon technique que personne ne comprend ou ne connaît.

   –    Essayez de supprimer les mots inutiles.

   –    Veillez à utiliser un langage que le public visé comprendra.

   –    Sur le PC, l'application vous avertit si votre texte dépasse la limite de 280 caractères. Si vous approchez de la limite de 280 caractères, cela montre que vous essayez d'ajouter trop d'informations dans une seule étape.

   –    [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] ne prend pas actuellement en charge la mise en forme du texte (comme la taille de police ou le style), mais vous pouvez utiliser des majuscules pour souligner des mots ou des phrases clés.

   –    L'ajout d'étapes numérotées ou de plusieurs petites étapes dans une seule étape peut souvent amener un opérateur à manquer des actions spécifiques. N'ayez pas peur de créer des étapes distinctes pour vous assurer que l'opérateur effectue les actions dans le bon ordre.

- Utilisez des verbes d'action descriptifs comme « trouver », « rechercher », « obtenir », « prendre », « poser », « insérer », « attacher » et « supprimer ».

- Utilisez un langage cohérent tout au long du guide. Les éléments qui sont particulièrement importants pour la cohérence du langage sont :

   –    Noms de pièces
   
   –    Verbes d'action
   
   –    Référence aux noms de tâches
   
- Pensez à ajouter des étapes distinctes supplémentaires qui contiennent des astuces. L'ajout d'astuces dans une étape d'action peut souvent amener l'opérateur à les manquer.
   
  - Il peut être utile d'ajouter des astuces en tant qu'étape distincte avant l'étape d'action.
       
  - Il est utile d'ajouter une étape **NOTE** à des fins de contrôles de la qualité. Ce type d'étape peut être placé avant ou après une autre étape, selon le contexte spécifique.
            
  - Ajoutez une étape **AVERTISSEMENT** pour les éléments susceptibles d'être dangereux ou de provoquer un problème qualitatif. Ce type d'étape peut être placé avant ou après une autre étape, selon le contexte spécifique. Sur HoloLens, vous pouvez ajouter un style d'avertissement sur un hologramme 3D pour renforcer le texte de l'étape d'avertissement.
       
     Exemple correct :
     
     ![Avertissement, exemple correct](media/good-example2.PNG "Avertissement, exemple correct")
     
     Exemple incorrect :
     
     ![Avertissement, exemple incorrect](media/bad-example2.PNG "Avertissement, exemple incorrect")
            
- Ajoutez une étape à la fin de chaque tâche pour informer l'opérateur de la fin de la tâche et pour lui présenter la tâche suivante. Cela permet à l'opérateur de créer un modèle mental de la structure du guide, et donc d'améliorer la rétention.
       
- S'il ne s'agit pas d'un outil/d'une pièce générique (par exemple, un tournevis, une clé à douilles ou une rondelle), veillez à identifier et définir l'outil/la pièce la première fois que vous le présentez à l'opérateur. Une fois que vous avez identifié et décrit l'outil/la pièce la première fois, il n'est pas nécessaire de le définir dans le reste du guide.
       
- Validation. Si certaines actions sont essentielles à la réussite des actions suivantes, veillez à ajouter une étape de validation. Voici quelques exemples de validation :

  – Validation visuelle
       
   - « Assurez-vous que le côté vert est orienté vers le haut ».
          
   - « Assurez-vous que le texte est à l'envers lorsque vous le fixez ».
          
   - « Assurez-vous que l'avant de la machine est face à vous et alignée sur le coin supérieur droit de la table avant de passer à l'étape suivante ».
          
  – Validation auditive
       
   - « Tournez le bouton vers la droite jusqu'à ce que vous entendiez 2 clics sonores ».
          
  – Validation de référence
       
   - « Référencez l'image pour une bonne orientation avant de passer à l'étape suivante. Les étapes suivantes reposent sur une bonne orientation du boîtier de circuits ».
          
- Mains :

  – Ne précisez pas la main à utiliser (gauche/droite) sauf dans les cas suivants :
  
   - L'utilisation d'une main spécifique est importante pour le processus (par exemple, « maintenez enfoncé le côté gauche avec votre main gauche, puis utilisez votre main droite pour tourner le bouton simultanément »)

   - L'usage de la force est nécessaire. Si l'usage de la force est nécessaire, veillez à spécifier la main dominante/non dominante dans les instructions de l'étape. Par exemple : « Tournez le bouton trois fois avec votre main dominante. L'usage de la force est nécessaire ».

## <a name="the-dotted-line-tether"></a>La ligne pointillée (attache)

- L'objectif principal de la ligne pointillée est de localiser dans l'espace où se déroulera le travail.

- Utilisez la ligne pointillée dans les cas suivants :

  – Vous commencez un guide. Cela permet d'orienter l'opérateur vers le bon emplacement général où se déroulera le travail.
  
  – Vous passez à une autre zone dans une nouvelle étape.
  
  – Vous recherchez une pièce.
  
  – Vous passez à une autre partie d'une grosse machine (par exemple, à plus de 60 cm de l'étape précédente).
  
- N'utilisez pas la ligne pointillée :

  – Dans chaque étape. L'utilisation de la ligne pointillée pour pointer vers le même emplacement dans plusieurs étapes peut créer un encombrement visuel qui empêche l'opérateur de se concentrer sur les hologrammes 3D ou la machine physique.
  
  – Pour pointer vers un emplacement spécifique (à moins de 10 mm). Utilisez la ligne pointillée pour orienter l'opérateur vers une zone générale, puis placez un hologramme 3D (une flèche, par exemple) à la fin de la ligne pointillée pour pointer vers un emplacement plus spécifique.

- Utilisez la ligne pointillée pour « prélever des pièces » comme suit :

  – Pour le prélèvement d'une pièce pour la première fois, utilisez la ligne pointillée pour indiquer à l'opérateur où elle se trouve.

  – Pour la deuxième fois, ou pour remettre un outil en place, il n'est pas nécessaire d'utiliser la ligne pointillée à nouveau (sauf s'il se trouve dans un autre emplacement).

## <a name="2d-images"></a>Images 2D

Nous vous recommandons d'utiliser des images 2D dans les scénarios suivants :

- Ce qu'il faut faire et ce qu'il ne faut pas faire. Lorsque les opérateurs ne cessent d'effectuer une action de manière incorrecte, il est utile d'avoir une image illustrant la manière correcte en regard d'une image illustrant la manière incorrecte. Souligner la principale différence.

  ![Exemple de ce qu'il faut faire et ne pas faire](media/to-do-and-not-to-do.PNG "Exemple de ce qu'il faut faire et ne pas faire") 

- Validation

  – Validation de l'orientation. L'utilisation d'une image permet de s'assurer que les pièces ou la machine ont la bonne orientation. Cela peut être particulièrement important si les étapes suivantes reposent sur la bonne orientation d'un composant ou d'une pièce spécifique. Veillez à fournir suffisamment de contexte environnemental pour communiquer visuellement aux opérateurs la bonne orientation dans l'environnement.
      
   ![Exemple de validation de l'orientation](media/orientation-validation.PNG "Exemple de validation de l'orientation")  

  – Validation des pièces. Utilisez des images pour l'identification des pièces si un poste de travail a plusieurs pièces qui peuvent être confondues visuellement. Cela est particulièrement utile lorsque deux ou plusieurs pièces sont très similaires, à quelques différences près.      

    Validez qu'un opérateur prélève la bonne pièce en la comparant à une image ou à un numéro de référence.

- Notes générales pour les images. Assurez-vous que les images :
     
  - Sont claires.
        
  - Sont de qualité supérieure. Une résolution de 1080p est recommandée. Les images 4K sont inutiles.
        
  - Capturez suffisamment de contexte pour orienter l'opérateur en contexte dans l'environnement.
              
  - Sont affichées du point de vue de l'opérateur.

  - Ne contiennent pas de bruit visuel supplémentaire qui peut perturber ou distraire l'opérateur de ce que vous essayez de communiquer.

  - Conservent un ratio de 16:9 pour remplir la totalité du panneau de support.

  - Affichent suffisamment de détails que vous essayez de communiquer. Ne prenez pas des images de trop loin. 

  - Assurez-vous d'afficher un aperçu de toutes les images sur HoloLens avant d'utiliser un guide. Les détails et la couleur des images peuvent être différents sur HoloLens.

- Si une image est primordiale, ajoutez les mots **Reportez-vous à l'image pour référence** avant tout texte d'action supplémentaire dans les instructions de l'étape. Si vous mettez la référence après une action, les opérateurs risquent ne pas la voir. Vous pouvez même créer une étape distincte à placer avant l'action pour s'assurer que l'opérateur voit l'image.

   Exemple correct :

   ![Exemple correct de référence à une image](media/good-example3.PNG "Exemple correct de référence à une image")  

   Exemple incorrect :

   ![Exemple incorrect de référence à une image](media/bad-example3.PNG "Exemple incorrect de référence à une image") 

## <a name="videos"></a>Vidéos

Nous recommandons les vidéos pour les interactions uniques, notamment :
   
– Les processus manuels détaillés.
     
–   Les étapes où la précision au millimètre est primordiale et les hologrammes 3D peuvent ne pas être suffisamment précis.
     
–   Les processus où les hologrammes standard sont trop abstraits, mais les hologrammes personnalisés sont trop complexes pour que votre équipe puisse les produire.

Montrez comment effectuer une étape d'une seule manière. Montrer plusieurs manières d'effectuer une étape risque de perturber les opérateurs. Choisissez la meilleure méthode pour effectuer l'étape.
     
### <a name="first-person-vs-third-person-videos"></a>Vidéos à la première personne et à la troisième personne

Faites des vidéos à la troisième personne ou à la première personne.
   
![Exemple de vidéo à la troisième personne et à la première personne](media/third-vs-first.PNG "Exemple de vidéo à la troisième personne et à la première personne") 

- Les vidéos à la troisième personne sont recommandées pour :
     
  - Montrer le contexte environnemental dans lequel effectuer le travail.

  - Comprendre comment l'opérateur et la machine interagissent.

- Lorsque vous filmez à la troisième personne, il convient de faire un gros plan (pour voir le contexte global), puis de faire un zoom pour comprendre les opérations détaillées.

- Vous pouvez facilement faire des vidéos à la troisième personne avec une caméra portative.

- Les vidéos à la première personne sont recommandées :

  - Pour les petits espaces confinés

  - Pour le travail manuel minutieux

  - Communiquer le travail du point de vue de l'opérateur est essentiel à la réussite de la procédure.

- Pour les vidéos à la première personne, il est recommandé de fixer une caméra sur la tête des personnes à l'aide d'un GoPro ou d'un appareil similaire.
    
## <a name="3d-toolkit"></a>Boîte à outils 3D

### <a name="3d-toolkit-categories"></a>Catégories de boîte à outils 3D :

#### <a name="arrows"></a>Flèches

- Utilisez des flèches :

  - Pour transmettre des informations spatiales simples comme une position, une direction, et une translation.

  - Lorsque l'opérateur doit insérer une pièce dans un objet :

    –   Les flèches sont utiles pour pointer vers un emplacement spécifique (dans une tolérance de +/- 2 mm)

    –   Les flèches peuvent être utilisées pour indiquer la direction. Exemple : « Tournez le levier jusqu'à ce qu'il soit serré à fond » avec la flèche en demi-cercle correspondante pour indiquer le sens du mouvement

    –   Vous pouvez utiliser une combinaison de plusieurs flèches pour indiquer une séquence de différentes actions (par exemple, « pivoter, puis tirer »). Vous pouvez combiner des flèches avec des chiffres.

    –   Vous pouvez utiliser des flèches en combinaison avec d'autres hologrammes 3D (par exemple, des coches et des croix) pour indiquer où placer et ne pas placer un objet.    
    
    ![Flèches combinées](media/arrows-combined.PNG "Flèches combinées") 

      
#### <a name="hands"></a>Mains

- Les mains sont utiles pour indiquer des orientations ou des mouvements spécifiques de la main.

- Utilisez les mains lorsque vous souhaitez que l'opérateur utilise ses mains d'une manière spécifique pour saisir ou manipuler un objet. Il existe de nombreuses postures pour des interactions spécifiques qui sont disponibles dans la boîte à outils 3D, comme tirer, pousser, pincer, saisir, etc. Combinez les mains avec des flèches et/ou des hologrammes 3D supplémentaires pour ajouter une signification supplémentaire.

- En général, les nuanceurs « Choisir » ou « Placer » fonctionnent mieux avec les mains pour permettre aux opérateurs d'aligner visuellement leurs mains sur l'hologramme.

#### <a name="numbers"></a>Chiffres

- Utilisez des chiffres pour le classement dans une étape. Exemple : « Tirez d'abord le levier (1), puis placez-le dans le trou (2) ».

- N'utilisez pas des chiffres pour identifier des pièces dans le monde. Exemple : « Prenez le tournevis (1) et la clé à douilles (2) ».

- N'utilisez pas des chiffres pour indiquer le nombre de pièces à récupérer. Exemple : « Prenez 3 vis » où le chiffre holographique 3 se trouve à côté de « vis ».

#### <a name="zones"></a>Zones

- Les zones sont recommandées pour indiquer où placer des objets.

   ![Exemple de zones](media/zones-example.PNG "Exemple de zones")

- Les zones peuvent être utilisées pour indiquer l'orientation et l'emplacement des objets.

- Les zones animées sont efficaces pour attirer l'attention des opérateurs.

- Si vous utilisez des zones pour indiquer une orientation, il convient de les combiner avec une image de référence.

#### <a name="generic-tools"></a>Outils génériques

- Les outils génériques peuvent être utilisés de deux manières :

   –    Symboles. Utilisez la version réduite d'un outil générique (par exemple, un tournevis) en regard d'une pièce du monde réel pour indiquer à l'opérateur le type d'outil à choisir ou utiliser.

   –    Modèles. Utilisez une version à grande échelle d'un outil générique pour indiquer à l'opérateur l'échelle réelle d'un outil spécifique à choisir ou utiliser.

#### <a name="symbols"></a>Symboles

- Les symboles Coche et Croix sont recommandés pour indiquer :

  - Où placer et ne pas placer des objets

  - Où exécuter et ne pas exécuter des objets

  - Zones d'enlèvement

  - Quelle pièce de machine ou quel outil choisir dans un tableau d'options

- Le point d'exclamation est recommandé pour transmettre des informations critiques ou alarmantes.

  - Nous vous recommandons d'utiliser le point d'exclamation avec le style Mise en garde ou Avertissement.

  - N'abusez pas du point d'exclamation, car il perdra de son urgence après un usage répété.

- Le symbole Éclair est recommandé pour indiquer des risques électriques potentiels.

 - Nous vous recommandons d'utiliser le symbole Éclair avec le style Mise en garde ou Avertissement.

## <a name="custom-3d-holograms"></a>Hologrammes 3D personnalisés

- En général, essayez d'effectuer une étape à l'aide de la boîte à outils 3D. Si vous ne parvenez pas à obtenir le résultat souhaité avec les ressources de la boîte à outils 3D, vous pouvez utiliser une ressource, image ou vidéo personnalisée à la place.

- Utilisez des ressources haute-fidélité personnalisées quand les détails ont de l'importance, et des ressources basse fidélité personnalisées pour connaître les principes essentiels quand les détails ont peu d'importance. Par exemple, si la précision détaillée est importante, comme référencer un port ou un levier spécifique, des ressources personnalisées très détaillées peuvent être nécessaires. D'autre part, si vous essayez d'indiquer comment aligner un objet, une forme générale permet d'obtenir l'effet souhaité.

- Les ressources personnalisées sont recommandées pour indiquer des pièces uniques ou des comportements d'animation inhabituels.

- Les hologrammes personnalisés animés sont recommandés pour indiquer les modèles de flux ou de mouvement dans une étape.

- Utilisez un hologramme personnalisé de l'objet entier pour les étapes d'orientation et d'alignement.

- Vous pouvez toujours utiliser une combinaison de ressources personnalisées avec la boîte à outils 3D dans n'importe quelle étape.

## <a name="hologram-styles"></a>Styles d'hologramme

- Les styles aident à créer une hiérarchie visuelle des hologrammes 3D.

- Utilisez des styles de manière cohérente pour indiquer des actions spécifiques. Si vous utilisez des styles de manière cohérente, à mesure que les opérateurs continuent d'utiliser [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], ils commenceront à comprendre ce que les styles sont censés exprimer, ce qui accélérera leur processus d'apprentissage.

### <a name="hologram-style-options"></a>Options de style d'hologramme

#### <a name="original"></a>Original

- Pour les ressources de la boîte à outils 3D, le nuanceur Original est un support blanc.

   –    Le support blanc Original est un bon style générique, car il n'a aucune forte connotation préexistante pour les opérateurs.

   –    Si vous mettez plus l'accent sur l'alignement ou le positionnement, le nuanceur Original est un choix judicieux, car il n'a aucune forte indication d'action pour l'opérateur.

- Pour les ressources personnalisées, le nuanceur Original représente tout ce qui est importé avec le modèle 3D.

  – Selon les besoins ou les exigences de l'auteur, vous pouvez importer un modèle personnalisé avec n'importe quel style. Voici quelques exemples pertinents :

    - Des couleurs spécifiques aux sections d'un modèle pour identifier des composants ou des pièces. Vous pouvez ensuite ajouter des instructions d'étape qui font référence aux sections colorées.

     - Un style réaliste pour indiquer à quoi ressemble l'objet réel.

#### <a name="pick-up"></a>Choisir

- Le style Choisir affiche un contour autour de l'hologramme.

- Nous vous recommandons d'utiliser le style Choisir pour :

  – Demander à l'opérateur de choisir un composant/une pièce. Cela convient particulièrement pour :
    
   - Les hologrammes de la boîte à outils 3D, car les opérateurs peuvent aligner leur main sur l'hologramme, en la positionnant dans l'orientation et la position appropriées.

   – Choisir des pièces, car le contour autour de l'objet du monde réel le distingue visuellement du reste de l'environnement.

#### <a name="place"></a>Placer

- Le style Placer est similaire au style Choisir, mais il a un contour en pointillés au lieu d'un contour uni.

- Nous vous recommandons d'utiliser le style Placer pour essayer d'aligner un objet du monde réel sur un hologramme, car les opérateurs peuvent placer l'objet réel dans l'hologramme pour valider sa correspondance visuelle.

#### <a name="see-through-includes-see-through-1-and-see-through-2"></a>Transparent (inclut le transparent 1 et le transparent 2)

- Le style Transparent est recommandé pour mettre moins l'accent sur les hologrammes dans le monde réel, car il rend l'hologramme semi-transparent et plus foncé.

- Lorsque vous créez une hiérarchie visuelle des hologrammes, utilisez le style Transparent pour atténuer les hologrammes moins importants dans la scène.

- Le transparent 1 est moins opaque que le transparent 2.

#### <a name="warning"></a>Avertissement

- Le style Avertissement est un symbole jaune avec des rayures noires, ce qui est synonyme d'avertissement.

- Utilisez le style Avertissement lorsqu'un hologramme représente quelque chose de potentiellement :

   –    Dangereux
   
   –    Électrique
   
   –    Risqué

#### <a name="avoid"></a>Mise en garde

- Le style Mise en garde est un symbole de pulsation rouge que vous pouvez utiliser pour indiquer à l'opérateur que :

   –    Il doit éviter de toucher une zone ou une pièce spécifique ou d'interagir avec elle.
   
   –    Il doit éviter une zone d'enlèvement.
   
   –    Un objet est dangereux ou électrique. Vous pouvez également utiliser le style Avertissement selon le contexte spécifique.

#### <a name="x-ray"></a>Rayon X

- Le rayon X ressemble à l'effet d'un balayage aux rayons X.

- Utilisez le style Rayon X lorsqu'un hologramme est placé dans un autre objet, ce qui permet à l'opérateur de comprendre l'ordre des pièces.

#### <a name="metal"></a>Métal

- Le style Métal représente un métal très brillant et peut être utilisé pour donner à un hologramme un aspect brillant réaliste.

## <a name="anchoring"></a>Ancrage

- Placez le point d'ancrage sur l'objet de base (au lieu d'un objet statique comme une table ou un chariot), de sorte que si l'orientation de l'objet de base est incorrecte, l'opérateur peut lancer une nouvelle analyse et corriger les positions des hologrammes.

  Exemple correct :

  ![Exemple correct d'ancrage](media/good-example-anchoring.PNG "Exemple correct d'ancrage")

  Exemple incorrect :

  ![Exemple incorrect d'ancrage](media/bad-example-anchoring.PNG "Exemple incorrect d'ancrage")

- Une orientation importante susceptible d'affecter l'alignement des étapes suivantes peut être couplée à des guides visuels via des photos ou des hologrammes personnalisés et des rappels textuels pour vérifier leur positionnement.

- Veillez à expliquer les notions fondamentales d'ancrage aux opérateurs, sinon ils risquent de ne pas savoir comment corriger l'alignement incorrect d'un objet du monde réel.

### <a name="see-also"></a>Voir aussi

[Créer un guide](authoring-overview.md)<br>
[Manuel de l'opérateur](operator-guide.md)<br>
[Analyser les guides](analytics-guide.md)<br>
[FAQ](faq.md)<br>
[Problèmes connus](known-issues.md)
