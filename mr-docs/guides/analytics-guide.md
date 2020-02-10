---
author: BryceHo
description: Décrit les états d'Analyses de Guides--Power BI que vous pouvez utiliser dans Dynamics 365 Guides pour améliorer l'efficacité des processus.
ms.author: cynielse
ms.date: 01/28/2020
ms.service: crm-online
ms.topic: article
title: Présentation des états d'Analyses de Guides, Power BI pour Dynamics 365 Guides
ms.reviewer: v-brycho
ms.openlocfilehash: 3fc55233e91fe63ce96e3f3e7e889d2c0826b4be
ms.sourcegitcommit: 217d31bb34e67a6b8823d5ddac7ef8d56d054139
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/29/2020
ms.locfileid: "2994516"
---
# <a name="analyze-guides-created-with-dynamics-365-guides"></a>Analyser des guides créés avec Dynamics 365 Guides
 
Les Analyses de Guides font partie de la suite d'applications [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] qui comprend l'application de création sur PC [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] [!include[pn-hololens](../includes/pn-hololens.md)]. Utilisez les Analyses de Guides pour analyser l'utilisation des guides dans votre organisation. Les Analyses de Guides se composent d'états visuels [!include[pn-power-bi](../includes/pn-power-bi.md)], renseignés à l'aide des données d'utilisation [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] enregistrées de manière sécurisée dans votre environnement [!include[pn-dyn-365](../includes/pn-dyn-365.md)]. 

## <a name="what-data-is-collected-and-used-in-guides-analytics"></a>Quelles sont les données collectées et utilisées dans les Analyses de Guides ? 

Lorsqu'un opérateur utilise l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] [!include[pn-hololens](../includes/pn-hololens.md)] en mode Créer, chaque interaction de type pointage du regard et validation des boutons **Étape suivante** et **Retour** est enregistrée avec la date et l'heure. Chaque opération d'un guide en mode Créer [!include[pn-hololens](../includes/pn-hololens.md)], qu'elle soit effectuée de A à Z à partir du guide ou qu'elle implique seulement certaines étapes, s'appelle *une exécution*. Les informations sur le guide, comme le numéro d'étape, le numéro de tâche et le nom du guide sont également enregistrées. Ces données sont stockées dans votre environnement [!include[pn-dyn-365](../includes/pn-dyn-365.md)] privé et sécurisé.  

## <a name="what-can-you-do-with-the-data"></a>Comment utiliser les données ? 

Les états d'Analyses de Guides sont conçus pour vous aider à répondre à des questions pointues sur l'utilisation des instructions. Par exemple : 

- Combien de guides ont été utilisés jusqu'à présent ? 
 
- Le nombre d'exécutions d'un guide par jour est-il en augmentation, en diminution ou stable dans le temps ? 

- Quelles sont les instructions qui prennent le plus de temps à parcourir ? 

Vous pouvez également utiliser les Analyses de Guides pour explorer les informations de suivi du temps détaillées à propos des tâches et des étapes. Vous devrez par exemple répondre à des questions comme celles-ci : 

- Quelle étape d'un guide prend le plus de temps ? 

- Quelle étape d'un guide a la durée d'exécution la plus variable ? 

Ces états fournissent des informations sur la façon de faire des opérateurs et permettent ensuite aux auteurs d'améliorer leurs instructions. Par exemple, un auteur peut concentrer ses efforts sur la modification des étapes qui mettent du temps à s'exécuter ou qui indiquent un niveau élevé de variabilité entre les opérateurs. Ces états sont également précieux dans le cadre de formation, pour les formateurs et les stagiaires, afin de mieux comprendre les performances et les améliorations dans le temps.  

## <a name="open-guides-analytics"></a>Ouvrir les Analyses de Guides 

### <a name="set-up-your-reports-for-the-first-time"></a>Paramétrer les états pour la première fois 

Vous pouvez paramétrer les Analyses de Guides pour la première fois via l'application de création sur PC [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)].

> [!NOTE]
> Les Analyses de Guides nécessitent l'application [Power BI Desktop gratuite](https://powerbi.microsoft.com/get-started/). Contactez votre administrateur si vous ne disposez pas d'une autorisation pour installer [!include[pn-power-bi](../includes/pn-power-bi.md)] Desktop sur votre ordinateur. 

Pour configurer vos états :
 
1.  Dans l'application de création sur PC [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)], sélectionnez l'onglet **Analyser**, copiez le texte de l'URL d'instance en surbrillance, puis sélectionnez **Continuer** pour accéder au [Centre de téléchargement Microsoft](https://aka.ms/guidesreport). 
   
    ![Onglet Analyser](media/get-started-analytics.PNG "Onglet Analyser")      
 
2.  Dans le centre de téléchargement [!include[cc-microsoft](../includes/cc-microsoft.md)], sélectionnez **Télécharger**. 

    ![Centre de téléchargement Microsoft](media/microsoft-download-center.PNG "Centre de téléchargement Microsoft") 

    Vous serez invité à sélectionner les fichiers à télécharger : 

     - **Modèle d'Analyses de Guides.** Vous pouvez configurer ce fichier modèle [!include[pn-power-bi](../includes/pn-power-bi.md)] pour afficher les données de suivi du temps [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] au sein de votre organisation. Il s'agit du composant principal d'Analyses de Guides. 
   
     - **Démonstration d'Analyses de Guides.** Vous pouvez utiliser ce fichier [!include[pn-power-bi](../includes/pn-power-bi.md)] pour afficher un exemple de jeu de données. Il ne requiert aucune configuration et vous permet d'obtenir une vue d'ensemble d'Analyses de Guides avant même de créer votre premier guide.  

     Nous vous recommandons de télécharger les deux fichiers. 

     ![Fichiers à télécharger](media/download-files.PNG "Fichiers à télécharger")   
  
3.  Ouvrez le fichier Modèle d'Analyses de Guides.pbit téléchargé avec [!include[pn-power-bi](../includes/pn-power-bi.md)] Desktop. Utilisez votre nom d'utilisateur et votre mot de passe [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] si vous êtes invité à vous connecter à [!include[pn-power-bi](../includes/pn-power-bi.md)].  
 
4.  Lorsque vous y êtes invité, collez l'URL d'instance dans la zone de texte comme indiqué ici. Il s'agit de la même URL d'instance que celle copiée à partir de l'onglet **Analyser** dans l'application de création sur PC à l'étape 1. 

     ![Modèle d'Analyses de Guides](media/guides-analytics-template.PNG "Modèle d'Analyses de Guides")
 
     Il est possible que le message d'erreur suivant s'affiche et vous indique que vous n'êtes pas connecté : 
  
     ![Erreur de connexion](media/sign-in-error.PNG "Erreur de connexion")

     Dans ce cas, sélectionnez **Connexion**, puis entrez votre nom d'utilisateur et votre mot de passe [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] pour connecter le modèle à l'environnement [!include[pn-dyn-365](../includes/pn-dyn-365.md)] sécurisé de votre organisation. 

5.  Vous devriez à présent voir le modèle renseigné avec les données de vos propres instructions. Si vous n'avez pas encore suivi d'instructions, il est possible que vos états soient vides. Les états sont décrits en détail dans « Apprendre à utiliser les états » plus loin dans cette rubrique. 
 
     ![Exemple d'état](media/example-report.PNG "Exemple d'état")
 
6.  Enregistrez les états configurés à un endroit pratique sur votre ordinateur en vue de les utiliser ultérieurement. 

7.  Sélectionnez **Actualiser** dans le ruban **Accueil** pour mettre vos rapports à jour avec les données [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] les plus récentes. 
 
### <a name="open-your-reports"></a>Ouvrir les états 

Une fois que vous avez paramétré et enregistré le Modèle d'Analyses de Guides sur votre ordinateur, ouvrez [!include[pn-power-bi](../includes/pn-power-bi.md)] Desktop et ouvrez l'état enregistré. [!include[pn-power-bi](../includes/pn-power-bi.md)] Desktop contient une liste d'éléments dans **Fichier – Ouvrir – Documents récents** qui est utile pour trouver les états ouverts précédemment.  

## <a name="take-a-tour-of-reports"></a>Apprendre à utiliser les états 

Les fichiers Modèle d'Analyses de Guides et Démonstration d'Analyses de Guides contiennent deux états : Utilisation de guides et Suivi du temps de traitement.

### <a name="guides-usage-report"></a>État Utilisation des guides

L'état Utilisation des guides fournit une vue d'ensemble de tous les guides utilisés dans votre organisation. Le graphique suivant illustre le contenu de l'état.

![État Utilisation des guides](media/guides-usage-report.PNG "État Utilisation des guides") 
 
1.  Quels sont les guides inclus dans l'état ?

    Utilisez le menu déroulant pour sélectionner les instructions utilisées pour générer les visuels et les statistiques dans l'état. Le fait de modifier la sélection dans ce menu déroulant a également un impact sur toutes les parties de l'état. Par défaut, l'option **Tous** est sélectionnée pour vous donner une vue d'ensemble de toutes les instructions de l'organisation.
   
2.  Utilisez les statistiques récapitulatives pour répondre rapidement aux questions suivantes :

    - **Guides.** Combien de guides ont été utilisés par au moins un opérateur jusqu'à présent ? 
   
    - **Utilisateurs.** Combien d'utilisateurs ont travaillé avec au moins un guide jusqu'à présent ? 
   
    - **Appareils.** Combien d'appareils ont été utilisés pour exploiter au moins un guide jusqu'à présent ? 
   
    - **Exécutions.** Combien d'exécutions complètes ont eu lieu jusqu'à présent ? 
   
3.  L'utilisation quotidienne des guides est-elle en train de changer ? 

    Le graphique à barres du nombre d'exécutions (axe Y) par jour (axe X) permet de visualiser les tendances, telles que l'augmentation, la réduction ou la stabilité en matière d'utilisation quotidienne des instructions.  

    **Monter/Développer jusqu'au niveau suivant.** Dans [!include[pn-power-bi](../includes/pn-power-bi.md)], les dates ont une hiérarchie en termes d'année, de trimestre, de mois, de jour. Par défaut, ce graphique à barres affiche le nombre d'exécutions par jour. Pour afficher le nombre total d'exécutions par mois, commencez par sélectionner le graphique, puis sélectionnez **Monter**.
   
    ![Bouton Monter](media/drill-up-button.PNG "Bouton Monter")
  
    Pour revenir à la vue journalière, sélectionnez **Mode Exploration**, puis sélectionnez la barre des mois à explorer.  

    ![Bouton Mode Exploration](media/drill-mode-button.PNG "Bouton Mode Exploration")

    Vous pouvez aussi sélectionner le bouton **Développer jusqu'au niveau suivant** pour explorer à nouveau en profondeur.  
  
    ![Développer jusqu'au niveau suivant](media/expand-to-next-level.PNG "Développer jusqu'au niveau suivant")
 
    **Filtrer par date.** Modifiez la plage de dates à l'aide du segment Filtrer par date. Sélectionnez les dates de début et de fin pour les définir manuellement, ou déplacez le curseur.
   
     >[!NOTE]
     >Le filtre date s'applique à tous les visuels et statistiques de l'état. 

4.  Quel est le guide le plus utilisé ? 

    Le graphique à barres du nombre d'exécutions (axe X) par guide (axe Y) permet d'identifier rapidement les guides les plus utilisés dans votre organisation (partie supérieure et inférieure du graphique respectivement). Si vous avez beaucoup de guides, vous devrez peut-être faire défiler ce graphique. 
   
5.  Quel est le temps d'exécution moyen par guide ? 

    Le graphique à barres du temps d'exécution moyen en minutes (axe X) par guide (axe Y) permet d'identifier rapidement les guides dont l'exécution prend le plus ou le moins de temps (partie supérieure et inférieure du graphique respectivement). Si vous avez beaucoup de guides, vous devrez peut-être faire défiler ce graphique. 

### <a name="process-time-tracking-report"></a>État Suivi du temps de traitement

Utilisez l'état Suivi du temps de traitement pour explorer l'utilisation et le temps de traitement des données d'un guide. Le graphique suivant illustre le contenu de l'état.

![État Suivi du temps de traitement](media/process-time-tracking-report.PNG "État Suivi du temps de traitement")
 
1.  Quels sont les guides inclus dans l'état ?

    Utilisez le menu déroulant pour sélectionner un guide. Le fait de modifier la sélection dans le menu déroulant modifie les valeurs dans tout l'état pour correspondre aux données de ce guide. 
   
2.  Utilisez les statistiques récapitulatives pour répondre rapidement aux questions suivantes : 

    - **Utilisateurs.** Combien d'utilisateurs ont exécuté ce guide au moins une fois ? 
   
    - **Appareils.** Combien d'appareils ont été utilisés pour exploiter ce guide au moins une fois jusqu'à présent ? 
   
    - **Exécutions.** Combien d'exécutions complètes de ce guide ont eu lieu jusqu'à présent ? 
   
3.  L'utilisation quotidienne des guides est-elle en train de changer ? 

    Il s'agit du même graphique que celui affiché dans l'état Utilisation de guides décrit précédemment. 
   
4.  Quelle est la durée d'exécution d'un guide en minutes ? 

    Vous pouvez afficher le temps d'exécution moyen de ce guide, en plus du temps d'exécution le plus long (maximum) et du temps d'exécution le plus court (minimum) en minutes pour obtenir une vue d'ensemble de la durée d'exécution de ce guide.  
   
5.  Combien de temps a duré chaque tâche ou chaque étape ? 

    Ce graphique en courbes affiche la durée en minutes (axe Y) de chaque étape d'un guide (axe X) pour vous indiquer les étapes qui prennent le plus de temps et celles dont la durée d'exécution varie le plus. Chaque exécution du guide est affichée sous la forme d'une ligne colorée distincte. 
   La légende du graphique fournit la liste de toutes les exécutions triées par heure de début. 
   
    **Monter/Descendre/Développer jusqu'au niveau suivant.** Par défaut, ce graphique indique le temps d'exécution en minutes par étape. L'axe des X indique les numéros d'étape (étiquettes supérieures) et les étiquettes de tâche parente (étiquettes inférieures). Les tâches et les étapes du guide sont organisées en hiérarchie. 

    Pour faire passer l'affichage du niveau des étapes au niveau des tâches, commencez par sélectionner le graphique, puis sélectionnez **Monter**.  

    ![Bouton Monter](media/drill-up-2.PNG "Bouton Monter")
   
    Pour revenir à l'affichage des étapes, sélectionnez **Mode Exploration**, puis sélectionnez la tâche à explorer.
  
    ![Bouton Mode Exploration](media/step-to-task-drill-down.PNG "Bouton Mode Exploration")
 
     Vous pouvez aussi sélectionner le bouton **Développer jusqu'au niveau suivant** pour explorer à nouveau en profondeur. Cette option va développer toutes les tâches au niveau de l'étape, tandis que le **Mode Exploration** explore uniquement l'élément de données sélectionné. 
   
    ![Hiérarchie Niveau suivant](media/expand-to-next-level.PNG "Hiérarchie Niveau suivant")
  
6.  Sélectionnez une exécution récente : 

    Pour afficher des données pour une seule exécution récente, sélectionnez-la à partir de la table d'exécution. Par défaut, cette table est triée selon l'heure de **Début d'exécution**, l'exécution la plus récente apparaissant en premier. Vous pouvez également sélectionner les en-têtes de colonne pour trier selon le **Temps d'exécution**. Si vous sélectionnez une seule ligne dans cette table, tous les visuels et les statistiques sont filtrés selon cette exécution uniquement. 
   
7.  Filtrer par Date ou Durée d'étape (minutes) : 

    Vous pouvez parfois souhaiter filtrer l'état pour afficher uniquement les exécutions générées dans une plage de dates particulière ou comprises dans un certain intervalle de temps. Par exemple : 
   
     - **Comparer des versions d'un guide.** Le filtre date est particulièrement utile si vous avez effectué une révision dans votre guide (par exemple, pour ajouter ou supprimer une étape) et si vous souhaitez afficher des données pour une version donnée du guide qui peut être identifiée en fonction de la date à laquelle il a été créé ou modifié. 

     - **Filtrer les valeurs hors norme.** Des durées d'étape exceptionnellement longues risquent d'allonger l'axe des Y du graphique en courbes, ce qui risque de masquer la plupart de données. Utilisez ce curseur pour définir la plage des durées d'étape que vous souhaitez visualiser dans l'ensemble de l'état pour pouvoir ignorer les valeurs hors norme.  

## <a name="share-the-guides-analytics-reports"></a>Partager les états d'Analyses de Guides 

Si vous disposez d'une licence [!include[pn-power-bi](../includes/pn-power-bi.md)] Pro, vous pouvez partager vos états d'Analyses de Guides [!include[pn-power-bi](../includes/pn-power-bi.md)] au sein de votre organisation en les publiant dans le service [!include[pn-power-bi](../includes/pn-power-bi.md)]. Cela permet à toute personne de votre organisation ayant une licence [!include[pn-power-bi](../includes/pn-power-bi.md)] Pro d'accéder à l'état via l'interface Web du service [!include[pn-power-bi](../includes/pn-power-bi.md)] accessible sur https://powerbi.microsoft.com.

Une fois que vous disposez d'une licence [!include[pn-power-bi](../includes/pn-power-bi.md)] Pro, plusieurs systèmes pour partager des états avec d'autres personnes de votre organisation sont disponibles. Nous vous recommandons de lire [Comment partager votre travail dans Power BI](https://docs.microsoft.com/power-bi/service-how-to-collaborate-distribute-dashboards-reports) pour obtenir une vue d'ensemble. Pour partager facilement vos états dans votre organisation en lecture seule, publiez-les sous forme d'application [!include[pn-power-bi](../includes/pn-power-bi.md)]. Cela implique de suivre les étapes bien documentées suivantes :

1.  [Créer un espace de travail dans le service Power BI](https://docs.microsoft.com/power-bi/service-create-workspaces). 

2.  [Publier les états d'Analyses de Guides dans cet espace de travail via Power BI Desktop](https://docs.microsoft.com/power-bi/desktop-upload-desktop-files). 

3.  [Publier le contenu de l'espace de travail en tant qu'application dans le service Power BI](https://docs.microsoft.com/power-bi/service-create-distribute-apps).  
 
## <a name="see-also"></a>Voir aussi

![Graphique de la caméra vidéo](media/video-camera.PNG "Graphique de la caméra vidéo") [Analyser les guides](https://aka.ms/guidesanalyze)<br>
![Graphique du document](media/doc-icon.PNG "Graphique du document") [Présentation de la création d'un guide](authoring-overview.md)</br>
![Graphique du document](media/doc-icon.PNG "Graphique du document") [Présentation de l'utilisation d'un guide](operator-overview.md)</br>
![Graphique du document ](media/doc-icon.PNG "Graphique du document")[FAQ](faq.md)



