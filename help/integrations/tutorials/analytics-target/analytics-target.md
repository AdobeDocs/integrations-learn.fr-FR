---
title: 'Tutoriel sur l [!DNL Analytics] intégration  [!DNL Target] '
description: Découvrez comment intégrer Adobe  [!DNL Analytics]  Adobe [!DNL Target].
solution: Analytics, Target
feature: Integrations
topic: Integrations
role: Leader, Admin, Developer
level: Beginner
index: true
hidefromtoc: true
kt: null
thumbnail: null
last-substantial-update: 2023-04-11T00:00:00Z
badgeIntegration: label="Intégration" type="positive"
exl-id: 4ab6c61f-f14e-408a-a700-53f7b3d0600a
source-git-commit: 7fffc0b887164645ab16fe94d2f82a657fcc9d64
workflow-type: tm+mt
source-wordcount: '437'
ht-degree: 9%

---

# Intégration de [!DNL Analytics] à [!DNL Target]


## Valeur et configuration de l’intégration

Les vidéos ci-dessous montrent l’intérêt de cette intégration, ainsi que des détails sur sa configuration.

>[!NOTE]
>
>Ces vidéos présentent l’implémentation et la validation d’[!DNL Target] at.js et d’[!DNL Analytics] appMeasurement.js. Consultez la [documentation](https://experienceleague.adobe.com/docs/target/using/integrate/a4t/a4timplementation.html?lang=fr) pour connaître les versions de bibliothèque requises dans les deux outils.

### Configuration d’A4T ([!DNL Analytics] pour [!DNL Target])

Dans cette vidéo, destinée aux développeurs et développeuses, vous apprenez à :

* Expliquez comment les requêtes [!DNL Analytics] et [!DNL Target] se lient à l’aide du SDID.
* Décrire les exigences d’implémentation pour Adobe [!DNL Analytics] avec Adobe [!DNL Target] (A4T)

>[!VIDEO](https://video.tv.adobe.com/v/35146/?quality=12&learn=on)

### Utilisation de [!DNL Analytics] comme Source de données pour les [!DNL Target]

Dans cette vidéo destinée aux professionnels, vous apprendrez :

* Qu’est-ce qu’A4T et pourquoi l’utiliser ?
* Comment A4T fonctionne-t-il ?
* Quelles sont les conditions préalables à l’utilisation d’A4T ?

>[!VIDEO](https://video.tv.adobe.com/v/17384/?quality=12&learn=on)


## Cas d’utilisation courants

Les vidéos ci-dessous présentent les différentes fonctionnalités, les types d’activités et les avantages de l’intégration via A4T.

### Panneau [!DNL Analytics] pour [!DNL Target] (A4T) dans Analysis Workspace

Le panneau [!DNL Analytics] pour [!DNL Target] (A4T) vous permet d’analyser en toute confiance vos activités et expériences de [!DNL Target] Adobe dans Analysis Workspace.

>[!VIDEO](https://video.tv.adobe.com/v/37247/?quality=12&learn=on)

### Analyse d’une activité de [!DNL Target] automatique à l’aide du panneau A4T

Dans cette vidéo, vous apprendrez à utiliser le panneau [!DNL Analytics] pour [!DNL Target] pour visualiser les résultats d’un test d’[!DNL Target] automatique.

>[!VIDEO](https://video.tv.adobe.com/v/333270/?quality=12&learn=on)

Nous disposons également de deux tutoriels détaillés sur la configuration des rapports A4T dans Analysis Workspace pour les activités d’« affectation automatique » et de « ciblage automatique » :

## Configuration de rapports A4T dans Analysis Workspace pour les activités d’affectation automatique {#a4t-auto-allocate}

Une activité Affectation automatique identifie un gagnant parmi plusieurs expériences et réaffecte automatiquement davantage de trafic au gagnant pendant que le test continue à s’exécuter et à apprendre. L’intégration [!DNL Analytics] for [!DNL Target] (A4T) pour l’affectation automatique vous permet de voir vos données de rapports dans Adobe [!DNL Analytics]. Vous pouvez même les optimiser pour les événements ou mesures personnalisés définis dans [!DNL Analytics].

<a href="https://experienceleague.adobe.com/docs/target-learn/tutorials/integrations/set-up-a4t-reports-in-analysis-workspace-for-auto-allocate-activities.html?lang=fr" class="spectrum-Button spectrum-Button--primary spectrum-Button--sizeM" target="_blank">
  <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">Configurer des rapports A4T pour les activités d’affectation automatique</span>
</a>

## Configuration de rapports A4T dans Analysis Workspace pour les activités de [!DNL Target] automatique {#a4t-auto-target}

L’intégration [!DNL Analytics] for [!DNL Target] (A4T) pour les activités d’[!DNL Target] automatique utilise les algorithmes de machine learning (ML) d’ensemble d’Adobe [!DNL Target] pour choisir la meilleure expérience pour chaque visiteur en fonction de son profil, de son comportement et du contexte, tout en utilisant une mesure d’objectif d’Adobe [!DNL Analytics].

Bien que des fonctionnalités d’analyse riches soient disponibles dans Adobe [!DNL Analytics] Analysis Workspace, quelques modifications de la [!DNL Analytics] par défaut pour [!DNL Target] panneau sont nécessaires pour interpréter correctement les activités de [!DNL Target] automatique , en raison des différences entre les activités d’expérimentation (test A/B manuel et affectation automatique) et les activités de personnalisation ([!DNL Target] automatique).

<a href="https://experienceleague.adobe.com/docs/target-learn/tutorials/integrations/set-up-a4t-reports-in-analysis-workspace-for-auto-target-activities.html?lang=fr" class="spectrum-Button spectrum-Button--primary spectrum-Button--sizeM" target="_blank">
  <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">Configurer des rapports A4T pour les activités de [!DNL Target] automatique</span>
</a>
