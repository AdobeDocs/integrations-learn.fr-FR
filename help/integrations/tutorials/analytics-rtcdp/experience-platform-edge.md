---
title: Intégrer [!DNL Analytics] et Real-Time Customer Data [!DNL Platform] au tutoriel Experience [!DNL Platform] Edge
description: Découvrez comment intégrer Adobe [!DNL Analytics] à Real-Time Customer Data [!DNL Platform] à l’aide d’AEP Web SDK, d’AEP Mobile SDK ou de l’API Edge Network Server.
solution: Real-Time Customer Data Platform, Analytics
feature: Integrations
topic: Integrations
role: Developer
level: Experienced
index: true
kt: 13732
thumbnail:
last-substantial-update: 2023-04-11T00:00:00.000Z
badgeIntegration: label="Intégration" type="positive"
exl-id: 07c2c329-0810-4f66-a91a-e315695f3fb4
TQID: 'https://experienceleague.adobe.com/K1CpRtUekl5jQNDMGswJpexC9fv9uVmgraLlNFXUIr8'
product_v2:
  - id: e55547f1-a1ff-40c6-8978-026e40ab7fa4
    internal-label: Analytics
  - id: fdddec33-c9cb-4459-b8b6-2664395a6f10
    internal-label: Real-Time Customer Data Platform
feature_v2:
  - id: eb9732ab-8232-4b21-bc4c-89de86dbe4d7
    internal-label: Integrations
  - id: fd307ce7-56f5-4ee3-af68-a7833ff6e85e
    internal-label: API
subfeature_v2:
  - id: e6c28e30-8689-4bf4-8fa8-561343d308a9
    internal-label: Experience Cloud integration
role_v2:
  - id: ff6a42d2-313e-452e-93a6-792e4fad9ff8
    internal-label: Developer
level_v2:
  - id: d378ca77-2da1-4f39-ad92-1917fe974a38
    internal-label: Experienced
topic_v2:
  - id: b5ce8718-c3af-4fdb-a1a9-fca32f83a87c
    internal-label: Implementation
source-git-commit: 4c51eef6f89060dc633dede5ea23e0f3ab445d0b
workflow-type: tm+mt
source-wordcount: '322'
ht-degree: 10%
---
# Tutoriel sur l’intégration d’Adobe [!DNL Analytics] et de Real-Time Customer Data [!DNL Platform] à Experience [!DNL Platform] Edge

<ol>
    <li><a href="https://experienceleague.adobe.com/?lang=fr#dashboard/learning" _target="_blank" rel="noopener noreferrer">Créer des schémas</a> pour les données à ingérer.</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/create-datasets-and-ingest-data.html" _target="_blank" rel="noopener noreferrer">Créer des jeux de données</a> pour les données à ingérer.</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/label-ingest-and-verify-identity-data.html?lang=en" _target="_blank" rel="noopener noreferrer">Configurez les identités et les espaces de noms d’identité corrects sur le schéma</a> pour vous assurer que les données ingérées peuvent être regroupées en un profil unifié.</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html?lang=fr" _target="_blank" rel="noopener noreferrer">Activez les schémas et les jeux de données pour le profil</a>.</li>
    <li>Ingérez des données dans Experience [!DNL Platform] à l’aide de l’une des méthodes suivantes :</li>
        <ul>
           <li>SDK Web Experience [!DNL Platform] :</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/implement-web-sdk/overview.html?lang=fr" _target="_blank" rel="noopener noreferrer">Tutoriel</a></li>
                    <li><a href="https://experienceleague.adobe.com/docs/analytics/implementation/aep-edge/web-sdk/overview.html" _target="_blank" rel="noopener noreferrer">Checklist</a></li>
                </ul>
            <li>SDK Mobile Experience [!DNL Platform] :</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/data-collection/mobile-sdk/create-mobile-properties.html" _target="_blank" rel="noopener noreferrer">Tutoriel</a></li>
                    <li><a href="https://experienceleague.adobe.com/docs/analytics/implementation/aep-edge/mobile-sdk/overview.html" _target="_blank" rel="noopener noreferrer">Checklist</a></li>
                </ul></li>
            <li>API du serveur Edge Network :</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/experience-platform/edge-network-server-api/interacting-other-adobe-solutions/interacting-adobe-analytics.html" _target="_blank" rel="noopener noreferrer">Tutoriel</a></li>
                </ul>
       </ul>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/create-segments.html" _target="_blank" rel="noopener noreferrer">Création de segments dans Experience [!DNL Platform].</a> Le système détermine automatiquement si le segment est évalué en tant que lot (connecteur de données) ou diffusion en continu (réseau Edge).</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/create-destinations-and-activate-data.html" _target="_blank" rel="noopener noreferrer">Configurez les destinations pour le partage des attributs de profil et des appartenances aux audiences vers les destinations souhaitées.</a></li>
</ol>

>[!NOTE]
>
>Les étapes de workflow standard du connecteur source [!DNL Analytics] Adobe créent le schéma et le jeu de données utilisés pour ingérer les données de [!DNL Analytics] « en l’état ». Par conséquent, les deux premières étapes sont gérées par le système. Le workflow de mappage nécessite la création d’attributs personnalisés. Par conséquent, suivez entièrement la séquence d’étapes.
