---
title: Intégrations d’applications pour la personnalisation à grande échelle
description: Faites en sorte que les expériences personnalisées soient prises en compte à chaque instant.
exl-id: 6d18813d-950c-40ae-8d5b-80bf389358fc
source-git-commit: 509b227f360718e81fb19d3a4d30aebf9de49e5a
workflow-type: tm+mt
source-wordcount: '516'
ht-degree: 1%

---

# Personalization à grande échelle

Dans un paysage actuel hautement compétitif et axé sur le numérique, les clients en sont venus à s’attendre à des expériences adaptées à leurs préférences et à leurs besoins uniques. L’exploitation des fonctionnalités de Adobe Experience Cloud nous permet de collecter et d’analyser des données client complètes, ce qui nous permet de disposer d’informations précieuses sur les comportements, les intérêts et les préférences. Cette compréhension profonde facilite la diffusion d’expériences personnalisées sur différents points de contact, assurant des interactions significatives et attrayantes. L’exploitation de la puissance de Adobe Experience Cloud libère tout le potentiel de la personnalisation, favorise des relations plus étroites avec les clients, favorise la fidélité et favorise la croissance des entreprises.

<table>
 <thead>
    <tr>
      <th>Cas d’utilisation</th>
      <th>Description</th>
      <th>Exemples</th>
      <th>Applications</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Créer des documents de PDF personnalisés</strong></td>
      <td>
        Générer des documents de communication pour la signature en fonction de l’utilisateur
        sélections/préférences.
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>
            Présenter un NDA généré dynamiquement en fonction des données d’une AEM
            Envoi Forms pour signature
          </li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/experience-manager/experience-manager-acrobat-sign.md"
          target="_blank"
          rel="noopener noreferrer"
          >AEM Forms et Sign</a
        >
      </td>
    </tr>
    <tr>
      <td rowspan="2"><strong>Analyse et reporting des données</strong></td>
      <td>
        Analyser les données comportementales à partir d’expériences numériques <br />Utiliser l’Adobe
        [!DNL Analytics] données comportementales dans Analysis Workspace dans le Parcours client
        [!DNL Analytics].
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>Analyse des chemins de conversion haut/bas</li>
          <li>Analyse de l’engagement et de la conversion des canaux</li>
          <li>Présentation du contenu le plus consulté</li>
          <li>Présentation des catégories et produits les plus courants</li>
          <li>
            Exécution d’une analyse de l’utilisation des outils pour optimiser les expériences en libre-service
          </li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/analytics/analytics-customer-journey-analytics.md"
          target="_blank"
          rel="noopener noreferrer"
          >[!DNL Analytics] et Parcours client [!DNL Analytics]</a
        >
      </td>
    </tr>
    <tr>
      <td>
        Reporting pour les activités de personnalisation<br />Analyse de l'optimisation
        tester les résultats, y compris les tests A/B, en utilisant l’Adobe [!DNL Target] et
        génération de rapports complets par Adobe [!DNL Analytics].
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>Afficher les résultats du test A/B dans les rapports d’analyse riches</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/analytics/analytics-target.md"
          target="_blank"
          rel="noopener noreferrer"
          >[!DNL Analytics] et [!DNL Target]</a
        >
      </td>
    </tr>
    <tr>
      <td><strong>Personnaliser des diffusions email</strong></td>
      <td>
        Personnalisez des diffusions email avec du contenu dynamique en utilisant la méthode
        fonctionnalités de l’Adobe [!DNL Target].
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>Ajout d’offres personnalisées aux e-mails des clients</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/campaign//campaign-target.md"
          target="_blank"
          rel="noopener noreferrer"
          >[!DNL Campaign] et [!DNL Target]</a
        >
      </td>
    </tr>
    <tr>
      <td rowspan="2">
        <strong>Développer les audiences pour la personnalisation et les plateformes publicitaires</strong>
      </td>
      <td>
        Utilisation des segments d’Audience Manager pour créer des audiences dans Real-Time CDP vers
        à utiliser dans les tactiques de personnalisation et de remarketing.
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>
            Effectuez un ciblage et une personnalisation anonymes d’audience numérique sur
            le site web, l’application mobile ou sur les canaux publicitaires pris en charge ;
          </li>
          <li>
            Optimiser les expériences de page d’entrée et de pré-authentification en fonction de
            appareil connu et caractéristiques comportementales
          </li>
          <li>
            Tirer parti du réseau de données tiers de l’Audience Manager pour continuer
            affiner et développer vos audiences pour le ciblage
          </li>
          <li>Partage des segments d’Audience Manager sur la plateforme RTCDP</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/aam/aam-rtcdp.md"
          target="_blank"
          rel="noopener noreferrer"
          > Audience Manager et données client en temps réel [!DNL Platform]</a
        >
      </td>
    </tr>
    <tr>
      <td>
        Utiliser les données [!DNL Analytics] pour créer des audiences à utiliser dans la personnalisation ou
        tactiques de remarketing.
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>
            Effectuer un ciblage et une personnalisation d’audience numérique sur des appareils ou
            prise en charge des canaux publicitaires.
          </li>
          <li>
            Optimiser les landing pages des clients connus et les expériences anonymes
            en fonction des attributs de périphérique et de comportement.
          </li>
          <li>Activez les audiences sur les canaux connus, tels que les emails et les SMS.</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/analytics/analytics-customer-journey-analytics.md"
          target="_blank"
          rel="noopener noreferrer"
          >[!DNL Analytics] et données client en temps réel [!DNL Platform]</a
        >
      </td>
    </tr>
    <tr>
      <td rowspan="2"><strong>Personnalisation des expériences web</strong></td>
      <td>
        Personnalisez des expériences d’application d’une seule page (SPA) en
        Utilisation d'AEM sans affichage conjointement avec l'Adobe [!DNL Target].
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>Personnalisation des SPA et des applications mobiles</li>
          <li>Réponses d’API personnalisées.</li>
          <li>[!DNL Target]de la diffusion de contenu.</li>
          <li>Variations de test A/B.</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/experience-manager/experience-manager-target.md"
          target="_blank"
          rel="noopener noreferrer"
          >AEM sans affichage et [!DNL Target]</a
        >
      </td>
    </tr>
    <tr>
      <td>
        Proposer des expériences web personnalisées en utilisant efficacement AEM Sites
        et Adobe [!DNL Target] pour la personnalisation.
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>AEM personnalisation du site web.</li>
          <li>Personnalisez le contenu du site web.</li>
          <li>Optimisez les expériences utilisateur.</li>
          <li>Variations de test A/B.</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/experience-manager/experience-manager-target.md"
          target="_blank"
          rel="noopener noreferrer"
          >AEM Sites et [!DNL Target]</a
        >
      </td>
    </tr>
    <tr>
      <td><strong>Personnalisation des expériences numériques</strong></td>
      <td>
        Utilisation de profils client en temps réel et de segments [!DNL Platform] gérés de manière centralisée
        pour personnaliser les messages sur les canaux web, mobiles et autres canaux numériques
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>Personnalisation du contenu pour les visiteurs connus</li>
          <li>Augmenter l’inscription et la participation au programme de fidélité</li>
          <li>Identifier et impliquer les clients à risque d’attrition</li>
          <li>Personnalisation des offres en temps réel</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/rtcdp/rtcdp-target.md"
          target="_blank"
          rel="noopener noreferrer"
          >Données client en temps réel [!DNL Platform] et [!DNL Target]</a
        >
      </td>
    </tr>
    <tr>
      <td><strong>Amélioration de la génération de pistes</strong></td>
      <td>
        Utilisation de profils client en temps réel et de segments [!DNL Platform] gérés de manière centralisée
        pour personnaliser les messages sur les canaux web, mobiles et autres canaux numériques
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>Personnalisation du contenu pour les visiteurs connus</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/rtcdp/rtcdp-target.md"
          target="_blank"
          rel="noopener noreferrer"
          >Données client en temps réel [!DNL Platform] et [!DNL Target]</a
        >
      </td>
    </tr>
  </tbody>
</table>
