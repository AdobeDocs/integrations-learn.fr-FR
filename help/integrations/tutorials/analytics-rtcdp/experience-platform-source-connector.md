---
title: Tutoriel sur l’intégration de  [!DNL Analytics]  et de données client en temps réel  [!DNL Platform]  avec Experience [!DNL Platform] source connector
description: Découvrez comment intégrer Adobe [!DNL Analytics]  avec les données client en temps réel  [!DNL Platform]  à l’aide du connecteur source Experience [!DNL Platform] .
solution: Real-Time Customer Data [!DNL Platform], [!DNL Analytics]
feature: Integrations
topic: Integrations
role: Leader, Architect, Admin, Developer
level: Beginner
index: true
hidefromtoc: true
kt: 13728
thumbnail: null
last-substantial-update: 2023-04-11T00:00:00Z
badgeIntegration: label="Intégration" type="positive"
exl-id: 1e27555d-e609-4a04-91ca-9518898ad699
source-git-commit: d35dc06c56c117cffe70542b6713f275877e4879
workflow-type: tm+mt
source-wordcount: '175'
ht-degree: 2%

---

# Intégrer l’Adobe [!DNL Analytics] et les données client en temps réel [!DNL Platform] avec le connecteur source Experience [!DNL Platform]

<ol>
    <li><a href="https://experienceleague.adobe.com/?lang=fr#dashboard/learning" _target="_blank" rel="noopener noreferrer">Créez des schémas</a> pour que les données soient ingérées.</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/create-datasets-and-ingest-data.html" _target="_blank" rel="noopener noreferrer">Créez des jeux de données</a> pour que les données soient ingérées.</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/label-ingest-and-verify-identity-data.html?lang=en" _target="_blank" rel="noopener noreferrer"> Configurez les identités et les espaces de noms d’identité corrects sur le schéma </a> pour vous assurer que les données ingérées peuvent correspondre à un profil unifié.</li> 
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html?lang=fr" _target="_blank" rel="noopener noreferrer">Activez les schémas et les jeux de données pour profile</a>.</li>
    <li>Ingérez des données [!DNL Analytics] dans Experience Platform à l’aide du <a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/ingest-data-from-adobe-analytics.html?lang=fr" _target="_blank" rel="noopener noreferrer">connecteur source d’Adobe [!DNL Analytics]</a>.</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/audiences/create-audiences.html" _target="_blank" rel="noopener noreferrer">Créez des segments dans l’expérience [!DNL Platform].</a> Le système détermine automatiquement si le segment est évalué en tant que lot (connecteur de données) ou en flux continu (réseau Edge).</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/create-destinations-and-activate-data.html" _target="_blank" rel="noopener noreferrer">Configurez les destinations pour le partage des attributs de profil et des appartenances à l’audience vers les destinations souhaitées.</a></li>   
</ol>

>[!NOTE]
>
>Les étapes de workflow standard pour le connecteur source d’Adobe [!DNL Analytics] créent le schéma et le jeu de données utilisés pour ingérer les données de [!DNL Analytics] &quot;en l’état&quot;. Par conséquent, les deux premières étapes sont gérées par le système. Le workflow de mappage nécessite la création d’attributs personnalisés. Par conséquent, suivez entièrement la séquence d’étapes.
