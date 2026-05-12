---
title: Intégrer  [!DNL Analytics] et le Parcours client [!DNL Analytics] avec le tutoriel Experience [!DNL Platform] Edge
description: Découvrez comment intégrer Adobe  [!DNL Analytics]  au Parcours client  [!DNL Analytics]  l’aide d’AEP Web SDK, d’AEP Mobile SDK ou de l’API Edge Network Server.
solution: Customer Journey Analytics, Analytics
feature: Integrations
topic: Integrations
role: Developer
level: Experienced
index: true
kt: null
thumbnail: 13728
last-substantial-update: 2023-04-11T00:00:00.000Z
badgeIntegration: label="Intégration" type="positive"
exl-id: e39dac5d-6ad5-47c8-94e8-070011233161
TQID: https://experienceleague.adobe.com/ClZddWXeWp51gWTBjRDQBZ2xNiO1bTRq-AoAdmucNEg
product_v2:
  - id: e55547f1-a1ff-40c6-8978-026e40ab7fa4
  - id: e98b7246-966c-4318-9e95-cad2f7a17dc7
feature_v2:
  - id: b3f03848-ae12-48b2-8aab-cad18567eb32
  - id: e75a4a9c-d354-4ca4-9b02-1afeca73fa5e
  - id: eb9732ab-8232-4b21-bc4c-89de86dbe4d7
  - id: fd307ce7-56f5-4ee3-af68-a7833ff6e85e
subfeature_v2:
  - id: e6c28e30-8689-4bf4-8fa8-561343d308a9
role_v2:
  - id: ff6a42d2-313e-452e-93a6-792e4fad9ff8
topic_v2:
  - id: b5ce8718-c3af-4fdb-a1a9-fca32f83a87c
source-git-commit: 2a324011b3d235db3d4642c2797c4fa107267e6a
workflow-type: tm+mt
source-wordcount: 413
ht-degree: 16%

---

# Intégrer Adobe [!DNL Analytics] et Customer Parcours [!DNL Analytics] au tutoriel Experience [!DNL Platform] Edge

<ol>
    <li><a href="https://experienceleague.adobe.com/fr?lang=fr#dashboard/learning" _target="_blank" rel="noopener noreferrer">Créer des schémas</a> pour les données à ingérer.</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/create-datasets-and-ingest-data.html?lang=fr" _target="_blank" rel="noopener noreferrer">Créer des jeux de données</a> pour les données à ingérer.</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/label-ingest-and-verify-identity-data.html?lang=fr" _target="_blank" rel="noopener noreferrer">Configurez les identités et les espaces de noms d’identité corrects sur le schéma</a> pour vous assurer que les données ingérées peuvent être regroupées en un profil unifié.</li> 
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html?lang=fr" _target="_blank" rel="noopener noreferrer">Activez les schémas et les jeux de données pour le profil</a>.</li>
    <li>Ingérez des données dans Experience [!DNL Platform] à l’aide de l’une des méthodes suivantes :</li>
        <ul>
            <li>SDK Web Experience [!DNL Platform] :</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/implement-web-sdk/overview.html?lang=fr" _target="_blank" rel="noopener noreferrer">Tutoriel</a></li>
                    <li><a href="https://experienceleague.adobe.com/docs/analytics/implementation/aep-edge/web-sdk/overview.html?lang=fr" _target="_blank" rel="noopener noreferrer">Checklist</a></li>
                </ul>
            <li>SDK Mobile Experience [!DNL Platform] :</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/data-collection/mobile-sdk/create-mobile-properties.html?lang=fr" _target="_blank" rel="noopener noreferrer">Tutoriel</a></li>
                    <li><a href="https://experienceleague.adobe.com/docs/analytics/implementation/aep-edge/mobile-sdk/overview.html?lang=fr" _target="_blank" rel="noopener noreferrer">Checklist</a></li>
                </ul></li>
            <li>API du serveur Edge Network :</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/experience-platform/edge-network-server-api/interacting-other-adobe-solutions/interacting-adobe-analytics.html?lang=fr" _target="_blank" rel="noopener noreferrer">Tutoriel</a></li>
                </ul>
       </ul>
    <li><i>(facultatif)</i>. Si vous utilisez plusieurs jeux de données, rassemblez les ID de personne pour <a href="https://experienceleague.adobe.com/docs/analytics-platform/using/cja-connections/combined-dataset.html?lang=fr" _target="_blank" rel="noopener noreferrer">générer un jeu de données combiné</a>. Si vous utilisez un seul jeu de données [!DNL Analytics] ou s’il existe un identifiant commun à tous les jeux de données que vous prévoyez d’utiliser dans les [!DNL Analytics] de Parcours client, ignorez cette étape.</li>
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections/connecting-customer-journey-analytics-to-data-sources-in-platform.html?lang=fr" _target="_blank" rel="noopener noreferrer">Créer une connexion</a> dans Customer Parcours [!DNL Analytics].</li>
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/basic-configuration-for-data-views.html?lang=fr" _target="_blank" rel="noopener noreferrer">Créer une vue de données</a>, <a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/configuring-component-settings-in-data-views.html?lang=fr" _target="_blank" rel="noopener noreferrer">configurer les paramètres du composant</a> et <a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/formatting-metrics-in-data-views.html?lang=fr" _target="_blank" rel="noopener noreferrer">formater les mesures</a> dans les [!DNL Analytics] du Parcours client.
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/analysis-workspace/workspace-projects/build-a-new-project.html?lang=fr" _target="_blank" rel="noopener noreferrer">Créez un projet dans Customer Parcours [!DNL Analytics].</a></li>
</ol>

>[!NOTE]
>
>Les étapes de workflow standard du connecteur source [!DNL Analytics] Adobe créent le schéma et le jeu de données utilisés pour ingérer les données de [!DNL Analytics] « en l’état ». Par conséquent, les deux premières étapes sont gérées par le système. Le workflow de mappage nécessite la création d’attributs personnalisés. Par conséquent, suivez entièrement la séquence d’étapes.
