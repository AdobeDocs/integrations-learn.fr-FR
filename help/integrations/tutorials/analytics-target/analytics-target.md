---
title: Intégrer [!DNL Analytics] avec [!DNL Target] tutoriel
description: Découvrez comment intégrer Adobe [!DNL Analytics] avec Adobe [!DNL Target].
solution: Analytics, Target
feature: Integrations
topic: Integrations
role: Leader, Architect, Admin, Developer
level: Beginner
index: true
hidefromtoc: true
kt: null
thumbnail: null
last-substantial-update: 2023-04-11T00:00:00Z
badgeIntegration: label="Intégration" type="positive"
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '428'
ht-degree: 9%

---


# Intégration d’[!DNL Analytics] à [!DNL Target]


## Valeur d’intégration et configuration

Les vidéos ci-dessous montrent la valeur de l’utilisation de cette intégration, ainsi que des détails concernant la configuration de l’intégration.

>[!NOTE]
>
>Ces vidéos montrent l’implémentation et la validation pour [!DNL Target] at.js et [!DNL Analytics] appMeasurement.js. Reportez-vous à [documentation](https://experienceleague.adobe.com/docs/target/using/integrate/a4t/a4timplementation.html) pour les versions de bibliothèque requises dans les deux outils.

### Configuration d’A4T ([!DNL Analytics] pour [!DNL Target])

Dans cette vidéo, destinée aux développeurs, vous apprenez à :

* Expliquer comment [!DNL Analytics] et [!DNL Target] liaison de requêtes à l’aide de SDID
* Description des exigences d’implémentation pour Adobe [!DNL Analytics] avec Adobe [!DNL Target] (A4T)

>[!VIDEO](https://video.tv.adobe.com/v/35146/?quality=12&learn=on)

### Utilisation [!DNL Analytics] comme source de données pour [!DNL Target]

Dans cette vidéo, destinée aux professionnels, vous apprendrez :

* Qu’est-ce qu’A4T et pourquoi l’utiliser ?
* Comment fonctionne A4T ?
* Quelles sont les conditions préalables requises pour utiliser A4T ?

>[!VIDEO](https://video.tv.adobe.com/v/17384/?quality=12&learn=on)


## Cas d&#39;utilisation courants

Les vidéos ci-dessous présentent différentes fonctionnalités, types d’activité et avantages de l’intégration via A4T.

### [!DNL Analytics] pour [!DNL Target] (A4T) Panneau dans Analysis Workspace

Le panneau [!DNL Analytics] for [!DNL Target] (A4T) vous permet d’analyser en toute confiance vos activités et expériences Adobe  dans Analysis Workspace.[!DNL Target]

>[!VIDEO](https://video.tv.adobe.com/v/37247/?quality=12&learn=on)

### Analyse automatique[!DNL Target] Activité utilisant le panneau A4T

Dans cette vidéo, vous apprendrez à utiliser le [!DNL Analytics] pour [!DNL Target] pour visualiser les résultats d’une[!DNL Target] test.

>[!VIDEO](https://video.tv.adobe.com/v/333270/?quality=12&learn=on)

Nous proposons également deux tutoriels détaillés qui vous montrent les détails de la configuration des rapports A4T dans Analysis Workspace pour les activités &quot;affectation automatique&quot; et &quot;ciblage automatique&quot; :

## Configuration de rapports A4T dans Analysis Workspace pour les activités d’affectation automatique {#a4t-auto-allocate}

Une activité d’affectation automatique identifie un gagnant parmi plusieurs expériences et réaffecte automatiquement du trafic supplémentaire vers le gagnant pendant que le test se poursuit et apprend. La variable [!DNL Analytics] pour [!DNL Target] L’intégration (A4T) pour l’affectation automatique vous permet de voir vos données de création de rapports dans Adobe. [!DNL Analytics]et vous pouvez même optimiser les événements personnalisés ou les mesures définies dans [!DNL Analytics].

<a href="https://experienceleague.adobe.com/docs/target-learn/tutorials/integrations/set-up-a4t-reports-in-analysis-workspace-for-auto-allocate-activities.html?lang=fr" class="spectrum-Button spectrum-Button--primary spectrum-Button--sizeM" target="_blank">
  <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">Configuration de rapports A4T pour les activités d’affectation automatique</span>
</a>

## Configuration de rapports A4T dans Analysis Workspace pour l’automatisation[!DNL Target] activités {#a4t-auto-target}

La variable [!DNL Analytics] pour [!DNL Target] Intégration (A4T) pour Auto-[!DNL Target] Les activités utilisent l’Adobe [!DNL Target] algorithmes d’apprentissage automatique d’ensemble (ML) permettant de choisir la meilleure expérience pour chaque visiteur en fonction de son profil, de son comportement et de son contexte, tout en utilisant un Adobe [!DNL Analytics] mesure d’objectif.

Bien que des fonctionnalités d’analyse riches soient disponibles dans Adobe [!DNL Analytics] Analysis Workspace, quelques modifications apportées à la valeur par défaut [!DNL Analytics] pour [!DNL Target] sont requis pour interpréter correctement l’auto.[!DNL Target] des activités, en raison des différences entre les activités d’expérimentation (test A/B manuel et affectation automatique) et les activités de personnalisation (auto-affectation) ;[!DNL Target]).

<a href="https://experienceleague.adobe.com/docs/target-learn/tutorials/integrations/set-up-a4t-reports-in-analysis-workspace-for-auto-target-activities.html?lang=fr" class="spectrum-Button spectrum-Button--primary spectrum-Button--sizeM" target="_blank">
  <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">Configuration de rapports A4T pour l’auto-édition[!DNL Target] activités</span>
</a>