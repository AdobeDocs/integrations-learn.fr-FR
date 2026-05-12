---
title: Tutoriel sur l [!DNL Analytics] intégration et les données client  [!DNL Platform]  temps réel au connecteur Experience [!DNL Platform] source
description: Découvrez comment intégrer  [!DNL Analytics] aux données client en temps réel  [!DNL Platform]  l’aide du connecteur Experience [!DNL Platform] source.
solution: Real-Time Customer Data Platform, Analytics
feature: Integrations
topic: Integrations
role: Leader, Admin, Developer
level: Beginner
index: true
kt: 13728
thumbnail: null
last-substantial-update: 2023-04-11T00:00:00.000Z
badgeIntegration: label="Intégration" type="positive"
exl-id: 1e27555d-e609-4a04-91ca-9518898ad699
TQID: https://experienceleague.adobe.com/Uct30-UadP-2Ocwslbk-dMAV0Y2unZlA339hThnofpA
product_v2:
  - id: e55547f1-a1ff-40c6-8978-026e40ab7fa4
  - id: fdddec33-c9cb-4459-b8b6-2664395a6f10
feature_v2:
  - id: eb9732ab-8232-4b21-bc4c-89de86dbe4d7
subfeature_v2:
  - id: e6c28e30-8689-4bf4-8fa8-561343d308a9
role_v2:
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
  - id: f8a45b24-4be7-4f1b-909b-60d06b483a20
  - id: ff6a42d2-313e-452e-93a6-792e4fad9ff8
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
source-git-commit: 2a324011b3d235db3d4642c2797c4fa107267e6a
workflow-type: tm+mt
source-wordcount: 248
ht-degree: 13%

---

# Intégrer Adobe [!DNL Analytics] et Real-Time Customer Data [!DNL Platform] au connecteur source Experience [!DNL Platform]

<ol>
    <li><a href="https://experienceleague.adobe.com/?lang=fr#dashboard/learning" _target="_blank" rel="noopener noreferrer">Créer des schémas</a> pour les données à ingérer.</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/create-datasets-and-ingest-data.html" _target="_blank" rel="noopener noreferrer">Créer des jeux de données</a> pour les données à ingérer.</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/label-ingest-and-verify-identity-data.html?lang=en" _target="_blank" rel="noopener noreferrer">Configurez les identités et les espaces de noms d’identité corrects sur le schéma</a> pour vous assurer que les données ingérées peuvent être regroupées en un profil unifié.</li> 
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html?lang=fr" _target="_blank" rel="noopener noreferrer">Activez les schémas et les jeux de données pour le profil</a>.</li>
    <li>Ingérez des données [!DNL Analytics] dans Experience Platform à l’aide du connecteur source Adobe [!DNL Analytics] <a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/ingest-data-from-adobe-analytics.html?lang=fr" _target="_blank" rel="noopener noreferrer"></a>.</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/audiences/create-audiences.html" _target="_blank" rel="noopener noreferrer">Création de segments dans Experience [!DNL Platform].</a> Le système détermine automatiquement si le segment est évalué en tant que lot (connecteur de données) ou diffusion en continu (réseau Edge).</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/create-destinations-and-activate-data.html" _target="_blank" rel="noopener noreferrer">Configurez les destinations pour le partage des attributs de profil et des appartenances aux audiences vers les destinations souhaitées.</a></li>   
</ol>

>[!NOTE]
>
>Les étapes de workflow standard du connecteur source [!DNL Analytics] Adobe créent le schéma et le jeu de données utilisés pour ingérer les données de [!DNL Analytics] « en l’état ». Par conséquent, les deux premières étapes sont gérées par le système. Le workflow de mappage nécessite la création d’attributs personnalisés. Par conséquent, suivez entièrement la séquence d’étapes.
