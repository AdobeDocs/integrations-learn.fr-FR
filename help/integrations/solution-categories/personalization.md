---
title: Intégrations d’applications pour une personnalisation à grande échelle
description: Intégrez des expériences personnalisées à chaque moment.
exl-id: 6d18813d-950c-40ae-8d5b-80bf389358fc
source-git-commit: 132c892723d29d415d07093ef8514ff8c9b7b1db
workflow-type: tm+mt
source-wordcount: '533'
ht-degree: 1%

---

# Personalization à grande échelle

Dans le paysage hautement concurrentiel et numérique d&#39;aujourd&#39;hui, les clients en sont venus à s&#39;attendre à des expériences adaptées à leurs préférences et besoins uniques. L’exploitation des fonctionnalités de Adobe Experience Cloud nous permet de collecter et d’analyser des données client complètes, ce qui nous permet d’obtenir des informations précieuses sur les comportements, les intérêts et les préférences. Cette compréhension approfondie facilite la diffusion d’expériences personnalisées entre divers points de contact, assurant des interactions significatives et attrayantes. Tirer parti de la puissance de Adobe Experience Cloud libère tout le potentiel de la personnalisation, ce qui permet de renforcer les connexions client, de fidéliser les clients et de stimuler la croissance de l’entreprise.

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
      <td><strong>Création de documents PDF personnalisés</strong></td>
      <td>
        Générer des documents de communication à signer en fonction de l’utilisateur
        sélections/préférences.
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>
            Présentation d’un AND généré dynamiquement à partir des données d’un AEM
            Envoi de Forms pour signature
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
      <td rowspan="2"><strong>Analyse des données et rapports</strong></td>
      <td>
        Analyse des données comportementales à partir d’expériences digitales <br />Utilisation d’Adobe
        [!DNL Analytics] des données comportementales dans Analysis Workspace dans le Parcours client
        [!DNL Analytics].
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>Analyse des chemins de conversion supérieur/inférieur</li>
          <li>Analyse de l’engagement et de la conversion des canaux</li>
          <li>Comprendre le contenu le plus consulté</li>
          <li>Comprendre les principales catégories de produits et les principaux produits</li>
          <li>
            Analyse de l’utilisation des outils pour optimiser les expériences en libre-service
          </li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/analytics/analytics-customer-journey-analytics.md"
          target="_blank"
          rel="noopener noreferrer"
          >[!DNL Analytics] de Parcours [!DNL Analytics]</a
        > et client
      </td>
    </tr>
    <tr>
      <td>
        Création de rapports pour les activités de personnalisation<br />Analyse de l’optimisation
        en testant les résultats, y compris les tests A/B, à l’aide d’Adobe [!DNL Target] et
        la génération de rapports complets via Adobe [!DNL Analytics].
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>Afficher les résultats des tests A/B dans des rapports d’analyse riches</li>
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
      <td><strong>Personnaliser les diffusions e-mail</strong></td>
      <td>
        Personnalisez les diffusions e-mail avec du contenu dynamique en tirant parti du
        fonctionnalités d’Adobe [!DNL Target].
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
        <strong>Développer les audiences pour les plateformes de personnalisation et de publicité</strong>
      </td>
      <td>
        Utilisez les segments Audience Manager pour créer des audiences dans Real-Time CDP afin de :
        à utiliser dans les tactiques de personnalisation et de remarketing.
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>
            Effectuer le ciblage et la personnalisation anonymes des audiences numériques sur
            le site web, l’application mobile ou sur les canaux publicitaires pris en charge
          </li>
          <li>
            Optimisez les expériences de page de destination et de pré-authentification en fonction de
            caractéristiques comportementales et de dispositif connues
          </li>
          <li>
            Tirez parti du réseau de données tiers d’Audience Manager pour
            affiner et développer vos audiences pour le ciblage
          </li>
          <li>Partage de segments Audience Manager vers RTCDP</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/aam/aam-rtcdp.md"
          target="_blank"
          rel="noopener noreferrer"
          >Audience Manager et Real-Time Customer Data [!DNL Platform]</a
        >
      </td>
    </tr>
    <tr>
      <td>
        Utilisez des données [!DNL Analytics] pour créer des audiences à utiliser dans la personnalisation ou
        les tactiques de remarketing.
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>
            Effectuer le ciblage et la personnalisation des audiences numériques sur des appareils ou des
            canaux publicitaires pris en charge.
          </li>
          <li>
            Optimiser les pages de destination connues des clients et clientes et les expériences anonymes
            en fonction des attributs d’appareil et de comportement.
          </li>
          <li>Activez les audiences vers des canaux connus, tels que les e-mails et les SMS.</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/analytics/analytics-customer-journey-analytics.md"
          target="_blank"
          rel="noopener noreferrer"
          >[!DNL Analytics] de données clients en temps [!DNL Platform]</a
        > et en temps réel
      </td>
    </tr>
    <tr>
      <td rowspan="2"><strong>Personnaliser les expériences web</strong></td>
      <td>
        Personnaliser efficacement les expériences d’applications d’une seule page (SPA) en
        l’utilisation d’AEM Headless conjointement avec Adobe [!DNL Target].
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>Personnalisation des SPA et des applications mobiles</li>
          <li>Réponses d’API personnalisées.</li>
          <li>[!DNL Target]diffusion de contenu de fin.</li>
          <li>Variantes des tests A/B.</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/experience-manager/experience-manager-target.md"
          target="_blank"
          rel="noopener noreferrer"
          >AEM découplé et [!DNL Target]</a
        >
      </td>
    </tr>
    <tr>
      <td>
        Proposer des expériences de site web personnalisées en utilisant efficacement AEM Sites
        et Adobe [!DNL Target] pour la personnalisation.
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>Personnalisation du site web AEM.</li>
          <li>Variantes des tests A/B.</li>
          <li>Ciblage comportemental basé sur le comportement de l'utilisateur.</li>
          <li>Personnalisation d’utilisateurs connus en assemblant les données utilisateur des différents systèmes, offrant ainsi une vue à 360 degrés du client.</li>
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
      <td><strong>Personnaliser les expériences digitales</strong></td>
      <td>
        Utiliser les profils clients en temps réel et les segments de [!DNL Platform] gérés de manière centralisée
        pour personnaliser la messagerie sur les canaux web, mobiles et autres canaux numériques :
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>Personnalisation du contenu pour les visiteurs connus</li>
          <li>Augmenter la fidélité, l’inscription et la participation</li>
          <li>Identifier et impliquer les clients présentant un risque de perte de clientèle</li>
          <li>Personnalisation des offres en temps réel</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/rtcdp/rtcdp-target.md"
          target="_blank"
          rel="noopener noreferrer"
          >Real-Time Customer Data [!DNL Platform] and [!DNL Target]</a
        >
      </td>
    </tr>
    <tr>
      <td><strong>Améliorer la génération de leads</strong></td>
      <td>
        Utiliser les profils clients en temps réel et les segments de [!DNL Platform] gérés de manière centralisée
        pour personnaliser la messagerie sur les canaux web, mobiles et autres canaux numériques :
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
          >Real-Time Customer Data [!DNL Platform] and [!DNL Target]</a
        >
      </td>
    </tr>
  </tbody>
</table>
