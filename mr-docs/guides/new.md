---
author: makamat
description: Décrit les nouvelles fonctionnalités de Dynamics 365 Guides, classées par date de parution
ms.author: makamat
ms.date: 10/01/2019
ms.service: crm-online
ms.topic: article
title: Nouveautés de Dynamics 365 Guides
ms.reviewer: v-brycho
ms.openlocfilehash: e8e7b3759d04a4aa3a508da7b9f5981fe715cbc4
ms.sourcegitcommit: 40992f99110d02b2120a930679c5f681b0a6227a
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/25/2019
ms.locfileid: "2050028"
---
## <a name="whats-new-in-dynamics-365-guides"></a>Nouveautés de Dynamics 365 Guides

Cette page fournit des détails sur les dernières versions de [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] classées par date de parution.  

### <a name="october-1-2019"></a>1er octobre 2019

[!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] est désormais mis à la disposition générale. Les mises à jour du 1er octobre 2019 pour l'application pour PC, l'application HoloLens et la solution Common Data Service devront être installées pour continuer à utiliser [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Les mises à niveau continueront à fonctionner avec votre licence de version préliminaire jusqu'à expiration. Pour vérifier la date d'expiration de la version préliminaire, accédez à https:<i></i>//admin.microsoft.com/, puis sélectionnez **Facturation** dans les paramètres pour assurer la continuité.

Les nouveaux clients doivent obtenir une licence de DG. Pour obtenir des informations sur les licences, l'installation et les mises à niveau, accédez à aka.ms/GetGuides.

La version d'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] 200.1909.XX et la version de solution 200.0.0.XX comprennent les mises à jour suivantes :

- **Essayez la démonstration.** Vous pouvez à présent essayer l'exemple de guide prêt à l'emploi sur l'application HoloLens sans devoir vous inscrire pour obtenir une licence ou créer un guide vous-même.

- **Enquêtes de satisfaction client.** Nous vous demanderons de temps en temps d'évaluer la satisfaction avec [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] pour nous permettre d'améliorer le produit.

- **Je n'accepte pas d'envoyer des données à Microsoft.** Sur les applications pour PC et HoloLens, pour des raisons de confidentialité, vous pouvez désactiver l'option d'envoi de données de télémétrie à Microsoft. 

- **Je n'accepte pas d'envoyer les données d'utilisation à votre organisation.** Pour empêcher l'affichage des données d'utilisation dans les tableaux de bord Power BI, les administrateurs peuvent désormais désactiver cette fonctionnalité pour des utilisateurs spécifiques.

La version du 1er octobre inclut également une refactorisation du code des positions d'hologramme afin d'améliorer les performances globales et de permettre des améliorations futures. Vous remarquerez peut-être que la position de certains modèles importés, auxquels une échelle a été appliquée, peut être modifiée. Vous devez replacer ces modèles 3D. Cela ne concerne pas la position des modèles de la boîte à outils 3D.

### <a name="august-27-2019"></a>27 août 2019
La version d'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] 104.1908.24001 et la version de solution 104.1908.0.117 comprennent les mises à jour suivantes :

- **Améliorations de l'accessibilité.** L'application PC offre un meilleur contraste des couleurs et prend en charge le mode contraste élevé pour les utilisateurs malvoyants. Utilisez le clavier pour passer par l'interface utilisateur tout en utilisant le Narrateur pour lire diverses options de création. En mode version préliminaire, vous pouvez manipuler des modèles 3D à l'aide du clavier.

- **Manipulation des hologrammes améliorée.** Les hologrammes se déplacent plus naturellement lorsque vous les placez dans l'espace, ce qui facilite l'alignement précis des hologrammes dans le monde réel.

- **Prise en charge de langues supplémentaires**. L'application PC et l'application HoloLens prennent désormais en charge les langues suivantes : anglais (États-Unis, Royaume-Uni), français (France, Canada), allemand, néerlandais (Pays-Bas), espagnol, italien, chinois (République populaire de Chine, Taïwan, Hong Kong), japonais et coréen.

> [!NOTE]
> Pour obtenir cette mise à jour, il suffit de mettre à jour l'application PC et l'application [!include[pn-hololens](../includes/pn-hololens.md)] à partir de [!include[cc-microsoft](../includes/cc-microsoft.md)] Store. La mise à jour de la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] n'est pas obligatoire, mais vous devez la mettre à jour si vous avez l'intention d'utiliser l'application dans les nouvelles langues prises en charge. 

### <a name="august-6-2019"></a>6 août 2019
La version 104.1908.2001.0 de l'application [!include[pn-hololens](../includes/pn-hololens.md)] permet de résoudre un problème dans la publication du 23 juillet de l'application [!include[pn-hololens](../includes/pn-hololens.md)] qui empêchait la liste des guides de s'afficher dans l'application [!include[pn-hololens](../includes/pn-hololens.md)] pour les clients d'Europe, du Moyen-Orient et d'Asie. Nous avons également publié une version mise à jour du modèle de génération d'états Power BI qui permet de corriger un bogue associé à des données manquantes qui provoquaient l'échec de l'état.

Pour obtenir cette mise à jour, il suffit de mettre à jour l'application [!include[pn-hololens](../includes/pn-hololens.md)] [!include[pn-hololens](../includes/pn-hololens.md)] à partir de [!include[cc-microsoft](../includes/cc-microsoft.md)] Store. Vous n'avez pas besoin de mettre à jour la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. Pour l'état Power BI, visitez le site https:<i></i>//aka.ms/guidesreport.

### <a name="july-23-2019"></a>23 juillet 2019

[!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)] est intégré dans la version 104.1907.19001 de l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] et dans la version 104.1907.0.33 de la solution CDS. Les clients **[!include[pn-field-service](../includes/pn-field-service.md)]** peuvent désormais associer des guides à des tâches de service dans [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)]. Lorsque des ordres de travail sont attribués aux techniciens, ils peuvent lancer le guide concerné dans un onglet **[!include[pn-field-service](../includes/pn-field-service.md)]** dédié dans l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] [!include[pn-hololens](../includes/pn-hololens.md)] et faire leur travail.

Les clients qui souhaitent prévisualiser l'intégration avec [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)] doivent disposer d'une instance existante de [!include[pn-dyn-365](../includes/pn-dyn-365.md)] Customer Engagement (CRM) avec [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)] version 8.6.0.183 ou ultérieure. 

Visitez aka.ms/getguides pour connaître les étapes de mise à niveau.

### <a name="july-9-2019"></a>9 juillet 2019

La version 103.1907.4001.0 de l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] donne un nouvel aspect visuel au PC et aux applications [!include[pn-hololens](../includes/pn-hololens.md)]. Nous avons amélioré l'expérience utilisateur et l'avons alignée avec la famille d'applications [!include[pn-dyn-365](../includes/pn-dyn-365.md)]. 
 
#### <a name="improvements-in-this-release"></a>Améliorations apportées dans cette version

- L'application du PC est désormais parfaitement réactive entre les différentes tailles d'écran. 

- Le menu de navigation sur la gauche et dans le coin inférieur droit de l'application du PC permet de naviguer beaucoup plus rapidement entre le contenu de guide et les paramètres du point d'ancrage du guide. 
 
- Les interactions de type « Pointer du regard » dans [!include[pn-hololens](../includes/pn-hololens.md)] sont placées uniformément à gauche des éléments de liste pour faciliter la sélection pendant la navigation. 

- Des modèles 3D sont chargés pour chaque étape pour améliorer les performances dans [!include[pn-hololens](../includes/pn-hololens.md)].
 
Ce volet **Nouveautés** continuera à vous informer des nouvelles fonctionnalités intéressantes dans chaque publication mensuelle.

### <a name="june-3-2019"></a>3 juin 2019

La version 103.1905.31001 de l'application [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] introduit une expérience d'ancrage (alignement) améliorée pour [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)]. L'application du PC ne vous demande pas de choisir une méthode d'ancrage avant de créer un guide, vous pouvez ainsi commencer à créer du contenu immédiatement. Vous pouvez également basculer entre les méthodes d'ancrage après la création d'un guide. L'application du PC fournit également des instructions plus détaillées pour choisir la méthode appropriée pour ancrer des instructions de réalité mixte dans votre espace de travail.

Si vous choisissez de créer un guide à l'aide d'un point d'ancrage numérique, vous pouvez désormais utiliser un modèle 3D prédéfini. Il n'est pas nécessaire de choisir un modèle 3D avant de continuer.

> [!NOTE]
> Pour tirer parti des nouvelles améliorations apportées à l'ancrage, vous devez mettre à jour la solution [!include[pn-dyn-365-guides](../includes/pn-dyn-365-guides.md)] dans le Centre d'administration [!include[pn-dyn-365](../includes/pn-dyn-365.md)]. Pour plus d'informations, consultez <a href="https://docs.microsoft.com/dynamics365/mixed-reality/guides/upgrade" target="_blank">Mettre à niveau votre solution Dynamics 365 Guides</a> ou contactez votre administrateur [!include[pn-dyn-365](../includes/pn-dyn-365.md)].

Pour plus d'informations sur la création d'un guide avec l'application du PC, voir <a href="https://docs.microsoft.com/dynamics365/mixed-reality/guides/pc-authoring" target="_blank">Utiliser l'application de création du PC pour créer un guide</a>.

