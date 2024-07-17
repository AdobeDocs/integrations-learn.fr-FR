---
title: Tutoriel Integrate [!DNL Analytics] avec [!DNL Target]
description: Découvrez comment intégrer Adobe [!DNL Analytics] à Adobe [!DNL Target].
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
exl-id: 4ab6c61f-f14e-408a-a700-53f7b3d0600a
source-git-commit: d35dc06c56c117cffe70542b6713f275877e4879
workflow-type: tm+mt
source-wordcount: '389'
ht-degree: 1%

---

# Intégrer [!DNL Analytics] avec [!DNL Target]


## Valeur d’intégration et configuration

Les vidéos ci-dessous montrent la valeur de l’utilisation de cette intégration, ainsi que des détails concernant la configuration de l’intégration.

>[!NOTE]
>
>Ces vidéos montrent l’implémentation et la validation de [!DNL Target] at.js et [!DNL Analytics] appMeasurement.js. Reportez-vous à la [documentation](https://experienceleague.adobe.com/docs/target/using/integrate/a4t/a4timplementation.html) pour connaître les versions de bibliothèque requises dans les deux outils.

### Configuration d’A4T ([!DNL Analytics] pour [!DNL Target])

Dans cette vidéo, destinée aux développeurs, vous apprenez à :

* Expliquer comment les requêtes [!DNL Analytics] et [!DNL Target] se lient à l’aide de SDID
* Décrire les exigences d’implémentation pour l’Adobe [!DNL Analytics] avec Adobe [!DNL Target] (A4T)

>[!VIDEO](https://video.tv.adobe.com/v/35146/?quality=12&learn=on)

### Utiliser [!DNL Analytics] comme Source de données pour [!DNL Target]

Dans cette vidéo, destinée aux professionnels, vous apprendrez :

* Qu’est-ce qu’A4T et pourquoi l’utiliser ?
* Comment fonctionne A4T ?
* Quelles sont les conditions préalables requises pour utiliser A4T ?

>[!VIDEO](https://video.tv.adobe.com/v/17384/?quality=12&learn=on)


## Cas d&#39;utilisation courants

Les vidéos ci-dessous présentent différentes fonctionnalités, types d’activité et avantages de l’intégration via A4T.

### [!DNL Analytics] pour le panneau [!DNL Target] (A4T) dans Analysis Workspace

Le panneau [!DNL Analytics] pour [!DNL Target] (A4T) vous permet d’analyser en toute confiance vos activités et expériences d’Adobe [!DNL Target] dans Analysis Workspace.

>[!VIDEO](https://video.tv.adobe.com/v/37247/?quality=12&learn=on)

### Analyse d’une activité [!DNL Target] à l’aide du panneau A4T

Dans cette vidéo, vous allez apprendre à utiliser le panneau [!DNL Analytics] pour [!DNL Target] pour visualiser les résultats d’un test Auto-[!DNL Target].

>[!VIDEO](https://video.tv.adobe.com/v/333270/?quality=12&learn=on)

Nous proposons également deux tutoriels détaillés qui vous montrent les détails de la configuration des rapports A4T dans Analysis Workspace pour les activités &quot;affectation automatique&quot; et &quot;ciblage automatique&quot; :

## Configuration de rapports A4T dans Analysis Workspace pour les activités d’affectation automatique {#a4t-auto-allocate}

Une activité d’affectation automatique identifie un gagnant parmi plusieurs expériences et réaffecte automatiquement du trafic supplémentaire vers le gagnant pendant que le test se poursuit et apprend. L’intégration [!DNL Analytics] pour [!DNL Target] (A4T) pour l’affectation automatique vous permet de voir vos données de rapport dans l’Adobe [!DNL Analytics], et vous pouvez même optimiser pour les événements personnalisés ou les mesures définies dans [!DNL Analytics].

<a href="https://experienceleague.adobe.com/docs/target-learn/tutorials/integrations/set-up-a4t-reports-in-analysis-workspace-for-auto-allocate-activities.html" class="spectrum-Button spectrum-Button--primary spectrum-Button--sizeM" target="_blank">
  <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">Configuration de rapports A4T pour les activités d’affectation automatique</span>
</a>

## Configuration de rapports A4T dans Analysis Workspace pour les activités [!DNL Target] automatiques {#a4t-auto-target}

L’intégration [!DNL Analytics] pour [!DNL Target] (A4T) pour les activités Auto-[!DNL Target] utilise les algorithmes d’apprentissage automatique d’ensemble (ML) d’Adobe [!DNL Target] pour choisir la meilleure expérience pour chaque visiteur en fonction de son profil, de son comportement et de son contexte, tout en utilisant une mesure d’objectif [!DNL Analytics] d’Adobe.

Bien que de riches fonctionnalités d&#39;analyse soient disponibles dans Adobe [!DNL Analytics] Analysis Workspace, quelques modifications du panneau par défaut [!DNL Analytics] pour [!DNL Target] sont nécessaires pour interpréter correctement les activités Auto-[!DNL Target], en raison des différences entre les activités d&#39;expérimentation (test A/B manuel et affectation automatique) et les activités de personnalisation (auto-[!DNL Target]).

<a href="https://experienceleague.adobe.com/docs/target-learn/tutorials/integrations/set-up-a4t-reports-in-analysis-workspace-for-auto-target-activities.html" class="spectrum-Button spectrum-Button--primary spectrum-Button--sizeM" target="_blank">
  <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">Configuration de rapports A4T pour les activités Auto-[!DNL Target]</span>
</a>
