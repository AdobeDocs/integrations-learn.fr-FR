---
title: 'Tutoriel sur l [!DNL Analytics] intégration  [!DNL Commerce] '
description: Découvrez comment intégrer  [!DNL Analytics]  à  [!DNL Commerce].
solution: Analytics, Commerce
feature: Integrations
topic: Integrations
role: Leader, Admin, Developer
level: Beginner
index: true
kt: null
thumbnail: null
last-substantial-update: 2023-04-11T00:00:00.000Z
badgeIntegration: label="Intégration" type="positive"
exl-id: ef50b6b3-1e2b-4fe9-98d5-555bc14ae8d6
TQID: https://experienceleague.adobe.com/yG4EZoiPmm3-HnjD6lZCyBDpaeseNuGb5wRhnCWqRuk
product_v2:
  - id: e55547f1-a1ff-40c6-8978-026e40ab7fa4
  - id: eadea719-cf89-469b-a6fd-a236a7138047
feature_v2:
  - id: c153fd90-23e1-4614-81d3-3cc7571227f7
  - id: c32adafa-ed01-4b31-997e-2413013911b0
  - id: dac87252-6066-4d6e-a9d2-f6d84c323de7
  - id: eb9732ab-8232-4b21-bc4c-89de86dbe4d7
subfeature_v2:
  - id: dcae653e-62c6-4cc8-84e6-ee110b848296
  - id: e318d41c-1d01-4c1e-9b18-1f61d435ceee
  - id: e38cbddc-1633-4cd5-bed5-9f289f2a6029
  - id: e6c28e30-8689-4bf4-8fa8-561343d308a9
  - id: ef60b66e-5984-4336-ba72-6d978b1b6f87
  - id: f236e2a1-90d4-477d-92e1-5996b5e92bff
role_v2:
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
  - id: f8a45b24-4be7-4f1b-909b-60d06b483a20
  - id: ff6a42d2-313e-452e-93a6-792e4fad9ff8
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
topic_v2:
  - id: d3cdead0-685a-4489-9250-4bb709942f66
  - id: ebde5b41-29c9-4f5e-9ef6-1197e85409e3
source-git-commit: 2a324011b3d235db3d4642c2797c4fa107267e6a
workflow-type: tm+mt
source-wordcount: 932
ht-degree: 2%

---

# Intégration de [!DNL Analytics] à [!DNL Commerce]

## Intégration initiale

Ces instructions s’appliquent aux projets hébergés dans Adobe [!DNL Commerce] Cloud. L’auto-hébergement peut varier dans une certaine mesure, mais le processus global doit être similaire.

1. Consultez le code dans votre environnement local
1. Utilisation du compositeur et installation du module
1. Suivez les instructions individuelles ici et revenez une fois l’opération terminée pour terminer les étapes restantes
   [Installation et configuration du connecteur  [!DNL Platform] ’expérience](https://experienceleague.adobe.com/docs/commerce-merchant-services/experience-platform-connector/fundamentals/install.html){target="_blank"}


1. Validez le fichier composer.json et, sur le cloud, les fichiers composer.lock.
1. Vérifiez que le module se trouve dans les environnements d’évaluation et/ou de production
Pour ce faire, connectez-vous à la section admin d’Adobe [!DNL Commerce] et recherchez ces nouvelles sections sous Système > Services
   ![Extension du connecteur Experience [!DNL Platform]](./assets/analytics-commerce/admin-view-experience-platform-commector-extension.png)

1. Configurez le module avec vos informations d’identification depuis le back-office Adobe [!DNL Commerce].
   * Commencez par les configurations du connecteur [!DNL Commerce] Services , comme illustré ci-dessous.
     Configuration du connecteur ![[!DNL Commerce] services &#x200B;](./assets/analytics-commerce/commerce-services-connector-setup.png)
   * Définissez ensuite les paramètres du connecteur Experience [!DNL Platform], comme illustré ci-dessous.
     ![&#x200B; Connecteur Experience [!DNL Platform] &#x200B;](./assets/analytics-commerce/experience-platform-connector.png)

Pour plus d’informations sur chaque phase et étape du processus d’intégration, suivez les instructions de la section Présentation du connecteur [Experience [!DNL Platform] &#x200B;](https://experienceleague.adobe.com/docs/commerce-merchant-services/experience-platform-connector/overview.html){target="_blank"}. Le tutoriel sur le connecteur Experience [!DNL Platform] couvre chaque section en profondeur et répond à toutes vos questions. Suivez ce tutoriel pour le reste des étapes de configuration rapide.

## Configuration des [!DNL Analytics] Experience Edge et Adobe

1. Vérifiez que votre organisation a (et que vous avez) accès à Adobe [!DNL Analytics]. Pour le confirmer, accédez à la page d’accueil de [&#128279;](https://experience.adobe.com/) puis cliquez sur le sélecteur d’applications (neuf points) dans le volet de navigation supérieur.

1. Créez une suite de rapports dans Adobe [!DNL Analytics] ou identifiez l’identifiant de la suite de rapports dans laquelle vous transmettrez [!DNL Commerce] données. Pour plus d’informations, regardez un tutoriel sur [la création d’une suite de rapports](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/intro-to-analytics/analytics-basics/understanding-and-creating-report-suites.html). Vous aurez besoin de cet identifiant de suite de rapports à l’étape du flux de données ci-dessous.

1. Accédez à l’[interface d’Adobe Experience [!DNL Platform] interface](https://platform.adobe.com) si vous avez accès à Experience [!DNL Platform]. Si vous n’avez pas accès à cette interface, vous pouvez effectuer toutes les étapes nécessaires répertoriées ci-dessous dans la section [!DNL Platform] d’Adobe [interface de collecte de données](https://experience.adobe.com/#/data-collection).

1. Créez ou mettez à jour votre schéma XDM avec des groupes de champs spécifiques à [!DNL Commerce]. Pour plus d’informations sur la création d’un schéma, consultez le tutoriel [&#x200B; « Créer des schémas »](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-schemas.html?lang=fr)
   * Vous devrez sélectionner ce schéma parmi les options de l’étape du flux de données ci-dessous. Pour créer un schéma, recherchez **Schémas** dans la colonne de gauche sous **Gestion des données**. À présent, dans le coin supérieur droit de l’interface, cliquez sur **Créer un schéma**. Sélectionnez XDM ExperienceEvent.
   * Après avoir créé un nouveau schéma, vous allez ajouter les groupes de champs [!DNL Commerce]. Sur le côté gauche de l’interface utilisateur, recherchez Groupes de champs, puis cliquez sur **Ajouter**
      * Dans la recherche, vous pouvez filtrer en saisissant `ExperienceEvent Commerce`
      * Cochez la case **[!DNL Commerce]** Adobe [!DNL Analytics] ExperienceEvent
      * Cliquez ensuite sur **Ajouter des groupes de champs** en haut à droite pour enregistrer et continuer

1. Facultatif (et uniquement si vous vous trouvez dans l’interface d’Experience [!DNL Platform]) - Créez un jeu de données
   * Cette étape vous permet d’importer les données [!DNL Commerce] dans Experience [!DNL Platform] (séparément de l’importation des données dans Adobe [!DNL Analytics]). Effectuez cette étape si vous avez accès à Experience [!DNL Platform] et prévoyez d’utiliser les données [!DNL Commerce] dans les applications prises en charge par Experience [!DNL Platform], telles que Real-Time Customer Data [!DNL Platform], Customer Parcours [!DNL Analytics] ou Journey Optimizer.
   * Vous devrez sélectionner ce jeu de données parmi les options de l’étape du flux de données ci-dessous.
   * Sous l’en-tête de la colonne de gauche **Gestion des données** dans le volet de navigation de gauche, sélectionnez **Jeux de données**.
   * Cliquez sur **Créer un jeu de données** en haut à droite. Sélectionnez l’option **Créer un jeu de données à partir d’un schéma**.
   * Recherchez et utilisez le schéma que vous avez créé à l’étape précédente

1. Créer le flux de données pour envoyer les données [!DNL Commerce] à Adobe [!DNL Analytics]
   * Sous l’en-tête **Collecte de données** dans la colonne de gauche, sélectionnez **Flux de données**.
   * Cliquez sur **Nouveau flux de données** en haut à droite de l’interface.
   * Indiquez un nom et une description facultative.
   * Recherchez et sélectionnez le schéma que vous avez créé/identifié à l’étape précédente.
   * Ajoutez les options avancées de votre choix. Pour plus d’informations sur les options avancées, consultez la [&#x200B; documentation &#x200B;](https://experienceleague.adobe.com/docs/experience-platform/datastreams/configure.html?lang=fr).
   * Cliquez sur **Enregistrer** pour continuer.
   * Cliquez sur **Ajouter un service** et choisissez **Adobe[!DNL Analytics]** dans le champ déroulant.
   * Cliquez sur **Ajouter une suite de rapports** et saisissez l’identifiant de suite de rapports que vous avez créé/identifié à l’étape précédente. Vous pouvez ajouter plusieurs suites de rapports si vous souhaitez que les données soient transmises à plusieurs suites de rapports.
   * Si vous le souhaitez, et si vous avez créé un jeu de données à l’étape précédente, cliquez de nouveau sur **Ajouter un service** en choisissant **Adobe Experience[!DNL Platform]** dans le champ déroulant. Dans le champ Jeu de données d’événement , sélectionnez le jeu de données que vous avez précédemment créé.
   * Enregistrez le flux de données.

1. Enfin, pour afficher vos données [!DNL Commerce], vous devez accéder à Analysis Workspace dans Adobe [!DNL Analytics], créer un projet, choisir votre suite de rapports et ajouter des tableaux à structure libre et d’autres visualisations pour créer des rapports et analyser vos données [!DNL Commerce]. L’illustration suivante présente un exemple de tableau que vous pouvez créer dans Analysis Workspace.

   ![[!DNL Analytics] d’écran de certaines données commerciales](./assets/analytics-commerce/analytics-screenshot-commerce-items.png)

   Voici quelques ressources supplémentaires pour vous aider à travailler dans Analysis Workspace :

   * [Présentation d’Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/analysis-workspace-overview.html)
   * [Création d’un projet Workspace à partir de zéro](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/building-a-workspace-project-from-scratch.html)
   * [Utilisation des tableaux, visualisations et panneaux dans Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/using-panels/using-tables-visualizations-and-panels.html)
   * [Cas d’utilisation des visualisations](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/visualization-use-cases.html)

   En outre, des cours gratuits sont disponibles sur Experience League. Voir [!DNL Analytics] cours disponibles [ICI](https://experienceleague.adobe.com/?lang=en&Solution=Analytics#courses).
