---
title: Intégrer [!DNL Analytics] et Parcours client [!DNL Analytics] avec expérience [!DNL Platform] tutoriel sur le connecteur source
description: Découvrez comment intégrer Adobe [!DNL Analytics] avec le Parcours client [!DNL Analytics] utilisation de l’expérience [!DNL Platform] connecteur source.
solution: Customer Journey [!DNL Analytics], [!DNL Target]
feature: Integrations
topic: Integrations
role: Leader, Architect, Admin, Developer
level: Beginner
index: true
hidefromtoc: true
kt: 13727
thumbnail: null
last-substantial-update: 2023-04-11T00:00:00Z
badgeIntegration: label="Intégration" type="positive"
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '274'
ht-degree: 18%

---


# Intégrer l’Adobe [!DNL Analytics] et Parcours client [!DNL Analytics] avec expérience [!DNL Platform] connecteur source

<ol>
    <li><a href="https://experienceleague.adobe.com/?lang=fr#dashboard/learning" _target="_blank" rel="noopener noreferrer">Créez des schémas</a> pour les données à ingérer.</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/create-datasets-and-ingest-data.html?lang=fr" _target="_blank" rel="noopener noreferrer">Créez des jeux de données</a> pour les données à ingérer.</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/label-ingest-and-verify-identity-data.html?lang=en" _target="_blank" rel="noopener noreferrer">Configuration des identités et des espaces de noms d’identité corrects sur le schéma</a> pour vous assurer que les données ingérées peuvent correspondre à un profil unifié.</li> 
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html?lang=fr" _target="_blank" rel="noopener noreferrer">Activation des schémas et des jeux de données pour le profil</a>.</li>
    <li>Ingestion de données dans Experience [!DNL Platform] en utilisant la variable <a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/ingest-data-from-adobe-analytics.html?lang=fr" _target="_blank" rel="noopener noreferrer">Adobe [!DNL Analytics] connecteur source</a></li>
    <li><i>(Facultatif)</i>. Si vous utilisez plusieurs jeux de données, assemblez les identifiants de personne avec <a href="https://experienceleague.adobe.com/docs/analytics-platform/using/cja-connections/combined-dataset.html" _target="_blank" rel="noopener noreferrer">générer un jeu de données combiné ;</a>. Si vous utilisez une seule [!DNL Analytics] jeu de données ou s’il existe un identifiant commun à tous les jeux de données que vous prévoyez d’utiliser dans le Parcours client [!DNL Analytics], ignorez cette étape.</li>
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections/connecting-customer-journey-analytics-to-data-sources-in-platform.html?lang=fr" _target="_blank" rel="noopener noreferrer">Création d’une connexion</a> dans le Parcours client [!DNL Analytics].</li>
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/basic-configuration-for-data-views.html" _target="_blank" rel="noopener noreferrer">Création d’une vue de données</a>, <a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/configuring-component-settings-in-data-views.html" _target="_blank" rel="noopener noreferrer">configuration des paramètres du composant</a>, et <a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/formatting-metrics-in-data-views.html" _target="_blank" rel="noopener noreferrer">mesures de format</a> dans le Parcours client [!DNL Analytics].
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/analysis-workspace/workspace-projects/build-a-new-project.html" _target="_blank" rel="noopener noreferrer">Création d’un projet dans le Parcours client [!DNL Analytics].</a></li>
</ol>

>[!NOTE]
>
>Étapes standard du workflow pour l’Adobe [!DNL Analytics] le connecteur source crée le schéma et le jeu de données utilisés pour ingérer les données à partir de [!DNL Analytics] &quot;en l’état&quot;. Par conséquent, les deux premières étapes sont gérées par le système. Le workflow de mappage nécessite la création d’attributs personnalisés. Par conséquent, suivez entièrement la séquence d’étapes.
