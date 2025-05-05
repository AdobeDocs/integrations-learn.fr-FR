---
title: Intégration de  [!DNL Analytics]  et de données client en temps réel  [!DNL Platform]  avec le tutoriel d’Edge  [!DNL Platform]
description: Découvrez comment intégrer Adobe [!DNL Analytics]  avec les données client en temps réel  [!DNL Platform]  à l’aide du SDK Web AEP, du SDK mobile AEP ou de l’API du serveur Edge Network.
solution: Real-Time Customer Data [!DNL Platform], [!DNL Analytics]
feature: Integrations
topic: Integrations
role: Developer
level: Experienced
index: true
hidefromtoc: true
kt: 13732
thumbnail: null
last-substantial-update: 2023-04-11T00:00:00Z
badgeIntegration: label="Intégration" type="positive"
exl-id: 07c2c329-0810-4f66-a91a-e315695f3fb4
source-git-commit: d35dc06c56c117cffe70542b6713f275877e4879
workflow-type: tm+mt
source-wordcount: '202'
ht-degree: 3%

---

# Intégration de l’Adobe [!DNL Analytics] et des données client en temps réel [!DNL Platform] avec le tutoriel Edge d’Experience [!DNL Platform]

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
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/create-segments.html?lang=fr" _target="_blank" rel="noopener noreferrer">Créez des segments dans l’expérience [!DNL Platform].</a> Le système détermine automatiquement si le segment est évalué en tant que lot (connecteur de données) ou en flux continu (réseau Edge).</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/create-destinations-and-activate-data.html?lang=fr" _target="_blank" rel="noopener noreferrer">Configurez les destinations pour le partage des attributs de profil et des appartenances à l’audience vers les destinations souhaitées.</a></li>
</ol>

>[!NOTE]
>
>Les étapes de workflow standard pour le connecteur source d’Adobe [!DNL Analytics] créent le schéma et le jeu de données utilisés pour ingérer les données de [!DNL Analytics] &quot;en l’état&quot;. Par conséquent, les deux premières étapes sont gérées par le système. Le workflow de mappage nécessite la création d’attributs personnalisés. Par conséquent, suivez entièrement la séquence d’étapes.
