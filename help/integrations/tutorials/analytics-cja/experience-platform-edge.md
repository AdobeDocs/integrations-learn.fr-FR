---
title: Intégrer l’Adobe  [!DNL Analytics]  et le Parcours client [!DNL Analytics]  au tutoriel d’Experience [!DNL Platform] Edge
description: Découvrez comment intégrer Adobe [!DNL Analytics]  avec le Parcours client [!DNL Analytics]  à l’aide du SDK Web AEP, du SDK mobile AEP ou de l’API du serveur Edge Network.
solution: Customer Journey [!DNL Analytics], [!DNL Analytics]
feature: Integrations
topic: Integrations
role: Developer
level: Experienced
index: true
hidefromtoc: true
kt: null
thumbnail: 13728
last-substantial-update: 2023-04-11T00:00:00Z
badgeIntegration: label="Intégration" type="positive"
exl-id: e39dac5d-6ad5-47c8-94e8-070011233161
source-git-commit: d35dc06c56c117cffe70542b6713f275877e4879
workflow-type: tm+mt
source-wordcount: '236'
ht-degree: 3%

---

# Intégrer l’Adobe [!DNL Analytics] et le Parcours client [!DNL Analytics] au tutoriel Edge d’ Experience [!DNL Platform]

<ol>
    <li><a href="https://experienceleague.adobe.com/fr?lang=fr#dashboard/learning" _target="_blank" rel="noopener noreferrer">Créez des schémas</a> pour que les données soient ingérées.</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/create-datasets-and-ingest-data.html?lang=fr" _target="_blank" rel="noopener noreferrer">Créez des jeux de données</a> pour que les données soient ingérées.</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/label-ingest-and-verify-identity-data.html?lang=fr" _target="_blank" rel="noopener noreferrer"> Configurez les identités et les espaces de noms d’identité corrects sur le schéma </a> pour vous assurer que les données ingérées peuvent correspondre à un profil unifié.</li> 
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html?lang=fr" _target="_blank" rel="noopener noreferrer">Activez les schémas et les jeux de données pour profile</a>.</li>
    <li>Ingérez des données dans l’expérience [!DNL Platform] à l’aide de l’une des méthodes suivantes :</li>
        <ul>
            <li>SDK Web d’Experience [!DNL Platform] :</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/implement-web-sdk/overview.html?lang=fr" _target="_blank" rel="noopener noreferrer">Tutoriel</a></li>
                    <li><a href="https://experienceleague.adobe.com/docs/analytics/implementation/aep-edge/web-sdk/overview.html?lang=fr" _target="_blank" rel="noopener noreferrer">Liste de contrôle</a></li>
                </ul>
            <li>Experience [!DNL Platform] Mobile SDK :</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/data-collection/mobile-sdk/create-mobile-properties.html?lang=fr" _target="_blank" rel="noopener noreferrer">Tutoriel</a></li>
                    <li><a href="https://experienceleague.adobe.com/docs/analytics/implementation/aep-edge/mobile-sdk/overview.html?lang=fr" _target="_blank" rel="noopener noreferrer">Liste de contrôle</a></li>
                </ul></li>
            <li>API du serveur Edge Network :</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/experience-platform/edge-network-server-api/interacting-other-adobe-solutions/interacting-adobe-analytics.html" _target="_blank" rel="noopener noreferrer">Tutoriel</a></li>
                </ul>
       </ul>
    <li><i>(Facultatif)</i>. Si vous utilisez plusieurs jeux de données, assemblez les ID de personne à <a href="https://experienceleague.adobe.com/docs/analytics-platform/using/cja-connections/combined-dataset.html?lang=fr" _target="_blank" rel="noopener noreferrer">pour générer un jeu de données combiné </a>. Si vous utilisez un seul jeu de données [!DNL Analytics] ou si un identifiant commun existe pour tous les jeux de données que vous prévoyez d’utiliser dans le Parcours client [!DNL Analytics], ignorez cette étape.</li>
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections/connecting-customer-journey-analytics-to-data-sources-in-platform.html?lang=fr" _target="_blank" rel="noopener noreferrer">Créez une connexion</a> dans le Parcours client [!DNL Analytics].</li>
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/basic-configuration-for-data-views.html?lang=fr" _target="_blank" rel="noopener noreferrer"> Créez une vue de données </a>, <a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/configuring-component-settings-in-data-views.html?lang=fr" _target="_blank" rel="noopener noreferrer"> configurez les paramètres du composant </a> et <a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/formatting-metrics-in-data-views.html?lang=fr" _target="_blank" rel="noopener noreferrer">formater metrics</a> dans le Parcours client [!DNL Analytics].
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/analysis-workspace/workspace-projects/build-a-new-project.html?lang=fr" _target="_blank" rel="noopener noreferrer">Créez un projet dans le Parcours client [!DNL Analytics].</a></li>
</ol>

>[!NOTE]
>
>Les étapes de workflow standard pour le connecteur source d’Adobe [!DNL Analytics] créent le schéma et le jeu de données utilisés pour ingérer les données de [!DNL Analytics] &quot;en l’état&quot;. Par conséquent, les deux premières étapes sont gérées par le système. Le workflow de mappage nécessite la création d’attributs personnalisés. Par conséquent, suivez entièrement la séquence d’étapes.
