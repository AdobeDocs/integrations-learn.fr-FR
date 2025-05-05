---
title: Tutoriel Integrate [!DNL Analytics] avec [!DNL Commerce]
description: Découvrez comment intégrer  [!DNL Analytics] à [!DNL Commerce].
solution: Analytics, Commerce
feature: Integrations
topic: Integrations
role: Leader, Architect, Admin, Developer
level: Beginner
index: true
hidefromtoc: true
kt: null
thumbnail: null
last-substantial-update: 2023-04-11T00:00:00Z
badgeIntegration: label="Intégration" type="positive"
exl-id: ef50b6b3-1e2b-4fe9-98d5-555bc14ae8d6
source-git-commit: 46803595cf8e199e0c331ea8b82f7fe4a2afc801
workflow-type: tm+mt
source-wordcount: '821'
ht-degree: 0%

---

# Intégrer [!DNL Analytics] avec [!DNL Commerce]

## Intégration initiale

Ces instructions concernent les projets hébergés dans le cloud [!DNL Commerce] Adobe. L’auto-hébergement peut varier dans une certaine mesure, mais le processus global doit être similaire.

1. Extraction du code dans votre environnement local
1. Utilisation du compositeur et du module d’installation
1. Suivez les instructions individuelles ici et revenez une fois terminé pour terminer les étapes restantes.
   [ Installez et configurez Experience [!DNL Platform] connector](https://experienceleague.adobe.com/docs/commerce-merchant-services/experience-platform-connector/fundamentals/install.html){target="_blank"}


1. Validez le fichier compositeur.json et, si dans le cloud, les fichiers compositeur.lock
1. Vérifiez que le module se trouve dans les environnements d’évaluation et/ou de production.
Pour ce faire, connectez-vous à la section admin de l&#39;Adobe [!DNL Commerce] et recherchez ces nouvelles sections sous Système > Services .
   ![Extension du connecteur Experience [!DNL Platform]](./assets/analytics-commerce/admin-view-experience-platform-commector-extension.png)

1. Configurez le module avec vos informations d’identification depuis l’Adobe [!DNL Commerce] back office.
   * Commencez par les configurations du connecteur de services [!DNL Commerce], comme illustré ci-dessous.

     ![[!DNL Commerce] Configuration du connecteur de services](./assets/analytics-commerce/commerce-services-connector-setup.png)
   * Ensuite, les paramètres du connecteur Experience [!DNL Platform], comme illustré ci-dessous.

     ![ Connecteur [!DNL Platform] d’expérience](./assets/analytics-commerce/experience-platform-connector.png)

Pour plus d’informations sur chaque phase et étape du processus d’intégration, suivez les instructions de la [présentation du connecteur Experience [!DNL Platform] ](https://experienceleague.adobe.com/docs/commerce-merchant-services/experience-platform-connector/overview.html){target="_blank"}. Le tutoriel sur le connecteur Experience [!DNL Platform] aborde en détail chaque section et répond à toutes les questions que vous pouvez vous poser. Utilisez ce tutoriel pour le reste des étapes de configuration rapide.

## Configuration d’Experience Edge et de l’Adobe [!DNL Analytics]

1. Vérifiez que votre organisation a (et que vous avez) accès à l&#39;Adobe [!DNL Analytics]. Pour le confirmer, rendez-vous sur la [page d’accueil de Adobe Experience Cloud](https://experience.adobe.com/) et cliquez sur le sélecteur d’applications (neuf points) dans la barre de navigation supérieure.

1. Créez une suite de rapports dans l’Adobe [!DNL Analytics] ou identifiez l’identifiant de la suite de rapports dans laquelle vous allez transférer des données [!DNL Commerce]. Pour plus d’informations, regardez un tutoriel sur la [création d’une suite de rapports](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/intro-to-analytics/analytics-basics/understanding-and-creating-report-suites.html). Vous aurez besoin de cet identifiant de suite de rapports à l’étape de flux de données ci-dessous.

1. Accédez à l’ [ interface  [!DNL Platform] d’Adobe](https://platform.adobe.com) si vous avez accès à l’expérience [!DNL Platform]. Si vous n’avez pas accès à cette interface, vous pouvez effectuer toutes les étapes nécessaires répertoriées ci-dessous dans l’ [!DNL Platform] [interface de collecte de données](https://experience.adobe.com/#/data-collection) de l’expérience d’Adobe.

1. Créez ou mettez à jour votre schéma XDM avec des groupes de champs spécifiques à [!DNL Commerce]. Pour plus d’informations sur la création d’un schéma, consultez le tutoriel [&quot;Créer des schémas&quot;](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-schemas.html?lang=fr) .
   * Vous devrez sélectionner ce schéma parmi les options de l’étape de la flux de données ci-dessous. Pour créer un schéma, recherchez dans la colonne de gauche sous **Data Management** et recherchez **Schemas**. Maintenant, en haut à droite de l’interface, cliquez sur **Créer un schéma**. Sélectionnez XDM ExperienceEvent.
   * Après avoir créé un nouveau schéma, vous allez ajouter les groupes de champs [!DNL Commerce]. Sur le côté gauche de l’interface utilisateur, recherchez les groupes de champs, puis cliquez sur **Ajouter**
      * Dans la recherche, vous pouvez filtrer en entrant `ExperienceEvent Commerce`
      * Cochez la case **Adobe [!DNL Analytics] ExperienceEvent[!DNL Commerce]**
      * Cliquez ensuite sur **Ajouter des groupes de champs** en haut à droite pour enregistrer et continuer.

1. Éventuellement (et uniquement si vous vous trouvez dans l’interface Experience [!DNL Platform]) - Créez un nouveau jeu de données
   * Cette étape vous permet d’importer les données [!DNL Commerce] dans l’expérience [!DNL Platform] (séparément des données dans l’Adobe [!DNL Analytics]). Effectuez cette étape si vous avez accès à l’expérience [!DNL Platform] et envisagez d’utiliser les données [!DNL Commerce] dans les applications prises en charge par l’expérience [!DNL Platform], telles que les données client en temps réel [!DNL Platform], le Parcours client [!DNL Analytics] ou Journey Optimizer.
   * Vous devrez sélectionner ce jeu de données parmi les options de l’étape de flux de données ci-dessous.
   * Sous l’en-tête de colonne de gauche **Data Management** dans le volet de navigation de gauche, sélectionnez **Jeux de données**.
   * Cliquez sur **Créer un jeu de données** en haut à droite. Choisissez l’option **Créer un jeu de données à partir du schéma** .
   * Recherchez et utilisez le schéma créé à la dernière étape.

1. Créez le Datastream pour envoyer les données [!DNL Commerce] à l&#39;Adobe [!DNL Analytics]
   * Sous l’en-tête **Collecte de données** de la colonne de gauche, sélectionnez **Entonnoir de données**.
   * Cliquez sur **New Datastream** en haut à droite de l’interface.
   * Attribuez un nom et une description facultative.
   * Recherchez et sélectionnez le schéma que vous avez créé/identifié à l’étape précédente.
   * Ajoutez les options avancées souhaitées. Pour plus d’informations sur les options avancées, consultez la [documentation](https://experienceleague.adobe.com/docs/experience-platform/datastreams/configure.html?lang=fr).
   * Cliquez sur **Enregistrer** pour continuer.
   * Cliquez sur **Ajouter un service** et sélectionnez **Adobe[!DNL Analytics]** dans le champ de liste déroulante.
   * Cliquez sur **Ajouter une suite de rapports** et saisissez l’identifiant de suite de rapports que vous avez créé/identifié à l’étape précédente. Vous pouvez ajouter plusieurs suites de rapports si vous souhaitez que les données s’enchaînent dans plusieurs suites de rapports.
   * Si vous avez éventuellement créé un jeu de données à l’étape précédente, cliquez de nouveau sur **Ajouter un service**, en choisissant **Adobe l’expérience[!DNL Platform]** dans le champ déroulant. Dans le champ Jeu de données d’événement , sélectionnez le jeu de données que vous avez précédemment créé.
   * Enregistrez le Datastream.

1. Enfin, pour afficher vos données [!DNL Commerce], vous devez accéder à Analysis Workspace dans l’Adobe [!DNL Analytics], créer un projet, choisir votre suite de rapports et ajouter des tableaux à structure libre et d’autres visualisations pour générer des rapports et analyser vos données [!DNL Commerce]. L’illustration suivante présente un exemple de tableau que vous pouvez créer dans Analysis Workspace.

   ![[!DNL Analytics] Capture d&#39;écran de certaines données commerciales](./assets/analytics-commerce/analytics-screenshot-commerce-items.png)

   Voici quelques ressources supplémentaires pour vous aider à travailler dans Analysis Workspace :

   * [Vue d’ensemble d’Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/analysis-workspace-overview.html)
   * [Création d’un projet Workspace à partir de zéro](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/building-a-workspace-project-from-scratch.html)
   * [Utilisation de tableaux, de visualisations et de panneaux dans Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/using-panels/using-tables-visualizations-and-panels.html)
   * [Cas d’utilisation de la visualisation](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/visualization-use-cases.html)

   De plus, des cours gratuits sont disponibles sur Experience League. Voir [!DNL Analytics] cours disponibles [ICI](https://experienceleague.adobe.com/?lang=en&amp;Solution=Analytics#courses).
