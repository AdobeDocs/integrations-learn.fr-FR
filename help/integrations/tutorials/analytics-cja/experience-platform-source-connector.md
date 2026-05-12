---
title: Tutoriel sur l [!DNL Analytics] intégration et le Parcours client  [!DNL Analytics]  connecteur Experience [!DNL Platform] source
description: Découvrez comment intégrer  [!DNL Analytics] à Customer Parcours [!DNL Analytics] à l’aide du connecteur Experience [!DNL Platform] source.
solution: Customer Journey Analytics, Target
feature: Integrations
topic: Integrations
role: Leader, Admin, Developer
level: Beginner
index: true
kt: 13727
thumbnail: null
last-substantial-update: 2023-04-11T00:00:00.000Z
badgeIntegration: label="Intégration" type="positive"
exl-id: f0dbd59d-d5e5-40e6-b4a4-e4789e7dd7e3
TQID: https://experienceleague.adobe.com/o3HCX8vz8ZKn2j1Hl3W4XWMOudx7MBZCMNRWxO-eKbw
product_v2:
  - id: e43347a8-f2c5-4aa4-8623-6f13875d7e3a
  - id: e98b7246-966c-4318-9e95-cad2f7a17dc7
feature_v2:
  - id: e75a4a9c-d354-4ca4-9b02-1afeca73fa5e
  - id: f7c7de77-382f-4f48-8b36-61a170f06d3d
role_v2:
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
  - id: f8a45b24-4be7-4f1b-909b-60d06b483a20
  - id: ff6a42d2-313e-452e-93a6-792e4fad9ff8
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
source-git-commit: 2a324011b3d235db3d4642c2797c4fa107267e6a
workflow-type: tm+mt
source-wordcount: 341
ht-degree: 19%

---

# Intégrer Adobe [!DNL Analytics] et Customer Parcours [!DNL Analytics] au connecteur source Experience [!DNL Platform]

<ol>
    <li><a href="https://experienceleague.adobe.com/fr?lang=fr#dashboard/learning" _target="_blank" rel="noopener noreferrer">Créer des schémas</a> pour les données à ingérer.</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/create-datasets-and-ingest-data.html?lang=fr" _target="_blank" rel="noopener noreferrer">Créer des jeux de données</a> pour les données à ingérer.</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/label-ingest-and-verify-identity-data.html?lang=fr" _target="_blank" rel="noopener noreferrer">Configurez les identités et les espaces de noms d’identité corrects sur le schéma</a> pour vous assurer que les données ingérées peuvent être regroupées en un profil unifié.</li> 
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html?lang=fr" _target="_blank" rel="noopener noreferrer">Activez les schémas et les jeux de données pour le profil</a>.</li>
    <li>Ingérez des données dans Experience [!DNL Platform] à l’aide du connecteur source Adobe [!DNL Analytics] <a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/ingest-data-from-adobe-analytics.html?lang=fr" _target="_blank" rel="noopener noreferrer"></a></li>
    <li><i>(facultatif)</i>. Si vous utilisez plusieurs jeux de données, rassemblez les ID de personne pour <a href="https://experienceleague.adobe.com/docs/analytics-platform/using/cja-connections/combined-dataset.html?lang=fr" _target="_blank" rel="noopener noreferrer">générer un jeu de données combiné</a>. Si vous utilisez un seul jeu de données [!DNL Analytics] ou s’il existe un identifiant commun à tous les jeux de données que vous prévoyez d’utiliser dans les [!DNL Analytics] de Parcours client, ignorez cette étape.</li>
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections/connecting-customer-journey-analytics-to-data-sources-in-platform.html?lang=fr" _target="_blank" rel="noopener noreferrer">Créer une connexion</a> dans Customer Parcours [!DNL Analytics].</li>
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/basic-configuration-for-data-views.html?lang=fr" _target="_blank" rel="noopener noreferrer">Créer une vue de données</a>, <a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/configuring-component-settings-in-data-views.html?lang=fr" _target="_blank" rel="noopener noreferrer">configurer les paramètres du composant</a> et <a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/formatting-metrics-in-data-views.html?lang=fr" _target="_blank" rel="noopener noreferrer">formater les mesures</a> dans les [!DNL Analytics] du Parcours client.
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/analysis-workspace/workspace-projects/build-a-new-project.html?lang=fr" _target="_blank" rel="noopener noreferrer">Créez un projet dans Customer Parcours [!DNL Analytics].</a></li>
</ol>

>[!NOTE]
>
>Les étapes de workflow standard du connecteur source [!DNL Analytics] Adobe créent le schéma et le jeu de données utilisés pour ingérer les données de [!DNL Analytics] « en l’état ». Par conséquent, les deux premières étapes sont gérées par le système. Le workflow de mappage nécessite la création d’attributs personnalisés. Par conséquent, suivez entièrement la séquence d’étapes.
