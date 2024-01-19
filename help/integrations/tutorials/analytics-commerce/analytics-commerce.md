---
title: Intégrer [!DNL Analytics] avec [!DNL Commerce] tutoriel
description: Découvrez comment intégrer  [!DNL Analytics]  à  [!DNL Commerce].
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
ht-degree: 3%

---

# Intégration d’[!DNL Analytics] à [!DNL Commerce]

## Intégration initiale

Ces instructions concernent l’Adobe. [!DNL Commerce] Projets hébergés dans le cloud. L’auto-hébergement peut varier dans une certaine mesure, mais le processus global doit être similaire.

1. Extraction du code dans votre environnement local
1. Utilisation du compositeur et du module d’installation
1. Suivez les instructions individuelles ici et revenez une fois terminé pour terminer les étapes restantes.
   [Installation et configuration de l’expérience [!DNL Platform] connector](https://experienceleague.adobe.com/docs/commerce-merchant-services/experience-platform-connector/fundamentals/install.html){target="_blank"}


1. Validez le fichier compositeur.json et, si dans le cloud, les fichiers compositeur.lock
1. Vérifiez que le module se trouve dans les environnements d’évaluation et/ou de production. Pour ce faire, connectez-vous à la section admin de Adobe. [!DNL Commerce] et recherchez ces nouvelles sections sous Système > Services .
   ![Expérience [!DNL Platform] extension de connecteur](./assets/analytics-commerce/admin-view-experience-platform-commector-extension.png)

1. Configuration du module avec vos informations d’identification depuis l’Adobe [!DNL Commerce] back office.
   * Commencez par [!DNL Commerce] Configurations du connecteur Services, comme illustré ci-dessous.
     ![[!DNL Commerce] Configuration du connecteur de services](./assets/analytics-commerce/commerce-services-connector-setup.png)
   * Ensuite, l’expérience [!DNL Platform] les paramètres du connecteur, comme illustré ci-dessous.
     ![Expérience [!DNL Platform] connector](./assets/analytics-commerce/experience-platform-connector.png)

Pour plus d’informations sur chaque phase et étape du processus d’intégration, suivez les instructions de la section [Expérience [!DNL Platform] présentation du connecteur](https://experienceleague.adobe.com/docs/commerce-merchant-services/experience-platform-connector/overview.html?lang=fr){target="_blank"}. L&#39;expérience [!DNL Platform] le tutoriel sur le connecteur couvre chaque section en détail et répond à toutes les questions que vous pouvez vous poser. Utilisez ce tutoriel pour le reste des étapes de configuration rapide.

## Configuration d’Experience Edge et de Adobe [!DNL Analytics]

1. Vérifiez que votre entreprise a (et que vous avez) accès à Adobe [!DNL Analytics]. Cela peut être confirmé en accédant à la variable [Page d’accueil de Adobe Experience Cloud](https://experience.adobe.com/) et cliquez sur le sélecteur d’applications (neuf points) dans la barre de navigation supérieure.

1. Création d’une suite de rapports dans Adobe [!DNL Analytics]ou identifier l’identifiant de la suite de rapports que vous allez envoyer. [!DNL Commerce] dans . Pour plus d’informations, visionnez un tutoriel sur [création d’une suite de rapports](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/intro-to-analytics/analytics-basics/understanding-and-creating-report-suites.html?lang=fr). Vous aurez besoin de cet identifiant de suite de rapports à l’étape de flux de données ci-dessous.

1. Accédez au [Expérience Adobe [!DNL Platform] interface](https://platform.adobe.com) si vous avez accès à Experience [!DNL Platform]. Si vous n’avez pas accès à cette interface, vous pouvez effectuer toutes les étapes nécessaires répertoriées ci-dessous dans l’expérience Adobe. [!DNL Platform] [Interface de collecte de données](https://experience.adobe.com/#/data-collection).

1. Créez ou mettez à jour votre schéma XDM avec [!DNL Commerce]groupes de champs spécifiques. Pour plus d’informations sur la création d’un schéma, reportez-vous à la section [&quot;Créer des schémas&quot;](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-schemas.html?lang=fr) tutoriel .
   * Vous devrez sélectionner ce schéma parmi les options de l’étape de la flux de données ci-dessous. Pour créer un schéma, reportez-vous à la colonne de gauche sous **Data Management** et rechercher **Schémas**. Maintenant, en haut à droite de l’interface, cliquez sur **Créer un schéma**. Sélectionnez XDM ExperienceEvent.
   * Après avoir créé un nouveau schéma, vous allez ajouter le [!DNL Commerce] groupes de champs. Dans la partie gauche de l’interface utilisateur, recherchez les groupes de champs, puis cliquez sur **Ajouter**
      * Dans la recherche, vous pouvez filtrer en saisissant `ExperienceEvent Commerce`
      * Sélectionnez la variable **Adobe [!DNL Analytics] ExperienceEvent[!DNL Commerce]** en cochant la case
      * Cliquez ensuite sur **Ajouter des groupes de champs** en haut à droite pour enregistrer et continuer

1. Facultatif (et uniquement si vous êtes dans l’expérience) [!DNL Platform] ) - Création d’un jeu de données
   * Cette étape vous permet d’importer la variable [!DNL Commerce] données dans l’expérience [!DNL Platform] (séparément de l’importation des données dans Adobe) [!DNL Analytics]). Effectuez cette étape si vous avez accès à Experience [!DNL Platform], et prévoient d’utiliser la variable [!DNL Commerce] données dans l’expérience [!DNL Platform]Applications prises en charge, telles que les données client en temps réel [!DNL Platform], Parcours client [!DNL Analytics]ou Journey Optimizer.
   * Vous devrez sélectionner ce jeu de données parmi les options de l’étape de flux de données ci-dessous.
   * Sous la colonne de gauche **Data Management** dans le volet de navigation de gauche, sélectionnez **Jeux de données**.
   * Cliquez sur **Création d’un jeu de données** en haut à droite. Choisissez la **Création d’un jeu de données à partir d’un schéma** .
   * Recherchez et utilisez le schéma créé à la dernière étape.

1. Créez le flux de données pour envoyer le [!DNL Commerce] données à Adobe [!DNL Analytics]
   * Sous , **Collecte de données** dans la colonne de gauche, sélectionnez **Datastreams**.
   * Cliquez sur **Nouvelle structure de données** en haut à droite de l’interface.
   * Attribuez un nom et une description facultative.
   * Recherchez et sélectionnez le schéma que vous avez créé/identifié à l’étape précédente.
   * Ajoutez les options avancées souhaitées. Pour plus d’informations sur les options avancées, consultez la section [documentation](https://experienceleague.adobe.com/docs/experience-platform/datastreams/configure.html?lang=fr).
   * Cliquez sur **Enregistrer** pour continuer.
   * Cliquez sur **Ajouter un service** et choisissez **Adobe[!DNL Analytics]** dans le champ déroulant.
   * Cliquez sur **Ajouter une suite de rapports** et saisissez l’identifiant de la suite de rapports que vous avez créée/identifiée à l’étape précédente. Vous pouvez ajouter plusieurs suites de rapports si vous souhaitez que les données s’enchaînent dans plusieurs suites de rapports.
   * Si vous avez éventuellement créé un jeu de données à l’étape précédente, cliquez sur **Ajouter un service** encore une fois, choix **Expérience Adobe[!DNL Platform]** dans le champ déroulant. Dans le champ Jeu de données d’événement , sélectionnez le jeu de données que vous avez précédemment créé.
   * Enregistrez le Datastream.

1. Enfin, pour afficher [!DNL Commerce] données, vous devrez accéder à Analysis Workspace dans Adobe. [!DNL Analytics], créez un projet, choisissez votre suite de rapports, puis ajoutez des tableaux à structure libre et d’autres visualisations pour générer des rapports et analyser vos [!DNL Commerce] data. L’illustration suivante présente un exemple de tableau que vous pouvez créer dans Analysis Workspace.

   ![[!DNL Analytics] Capture d&#39;écran de certaines données commerciales](./assets/analytics-commerce/analytics-screenshot-commerce-items.png)

   Voici quelques ressources supplémentaires pour vous aider à travailler dans Analysis Workspace :

   * [Vue d’ensemble d’Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/analysis-workspace-overview.html)
   * [Création d’un projet Workspace à partir de zéro](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/building-a-workspace-project-from-scratch.html)
   * [Utilisation des tableaux, visualisations et panneaux dans Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/using-panels/using-tables-visualizations-and-panels.html)
   * [Cas d’utilisation de la visualisation](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/visualization-use-cases.html)

   De plus, des cours gratuits sont disponibles sur Experience League. Voir [!DNL Analytics] cours [ICI](https://experienceleague.adobe.com/?lang=en&amp;Solution=Analytics#courses).
