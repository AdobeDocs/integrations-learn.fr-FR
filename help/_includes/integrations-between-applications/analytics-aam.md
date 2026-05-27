---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '390'
ht-degree: 0%

---


# Intégration d’[!DNL Analytics] et d’Audience Manager

{{analytics-description}}

{{audience-manager-description}}

En activant cette intégration, en transmettant les données Adobe [!DNL Analytics] côté serveur à Audience Manager, Audience Manager dispose de l’une de ses principales sources de données, à savoir les données comportementales des clients en ligne. Ces données peuvent ensuite être combinées à d’autres données, telles que des données CRM propriétaires ou des données de partenaires tiers, pour créer des segments de clients riches. En outre, les segments Audience Manager sont ensuite renvoyés à la page web dans la réponse pour une analyse plus approfondie des visiteurs. Ces deux cas d’utilisation intéressants sont décrits ci-dessous.

Les principaux avantages de l’intégration d’Adobe [!DNL Analytics] et d’Audience Manager sont les suivants :

+ **Segmentation améliorée** : combinez les données Adobe [!DNL Analytics] et Audience Manager pour obtenir des segments d’audience précis et personnalisés dans les campagnes marketing.
+ **Profils clients unifiés** : intégrez des sources de données pour comprendre les interactions et les comportements, en créant des profils clients complets.
+ **Efficacité améliorée des annonces** : optimisez les annonces avec le ciblage piloté par les données à partir de l’intégration d’Adobe [!DNL Analytics] et d’Audience Manager.
+ **Décisions axées sur les données** : éclairez les choix au moyen d’informations détaillées, de la fusion des [!DNL Analytics] Adobe et des données Audience Manager.
+ **Expériences personnalisées** : personnalisez votre contenu et vos offres pour enrichir les interactions client entre les points de contact à l’aide des deux plateformes.

Dans l’ensemble, cette intégration rassemble des données précieuses et des informations sur l’audience. Il permet aux entreprises de créer des campagnes marketing plus ciblées et pertinentes, tout en comprenant mieux les préférences et les comportements de leurs clients.

## Intégrations courantes

<table>
    <thead>
        <tr>
            <th>Applications Experience Cloud</th>
            <th>Intégration à l’aide d’</th>
            <th>Quand l’utiliser</th>
            <th>Cas d’utilisation courants</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <a href="/docs/analytics-learn/tutorials/integrations/audience-manager/enable-server-side-forwarding-in-adobe-launch.html" target="_blank" rel="noreferrer">[!DNL Analytics] envoyer des données à Audience Manager</a>
            </td>
            <td>Extension Adobe [!DNL Analytics] tags pour AppMeasurement.js avec transfert côté serveur activé</td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Lorsque vous souhaitez envoyer des données Adobe [!DNL Analytics] à Audience Manager pour créer des segments qui peuvent être partagés avec d’autres destinations Adobe Experience Cloud, des destinations basées sur les personnes ou d’autres destinations basées sur des appareils et personnalisées prises en charge par Audience Manager.</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Partagez des segments avec les plateformes publicitaires qui incluent les attributs de comportement collectés dans [!DNL Analytics].</li>
                    <li>Enrichissez les segments avec des données [!DNL Analytics] pour créer des segments cross-canal à forte valeur ajoutée à utiliser dans le ciblage sur site.</li>
                    <li>Placez le calque dans [!DNL Analytics] données vers des segments dont les clés sont basées sur des identifiants hachés, tels que les e-mails, à utiliser sur les plateformes de médias sociaux.</li>
                </ul>
            </td>
        </tr>        
        <tr>
            <td>
                <a href="https://experienceleague.adobe.com/docs/analytics/integration/audience-analytics/mc-audiences-aam.html?lang=fr" target="_blank" rel="noreferrer">Audience Manager renvoie des données à [!DNL Analytics]</a>
            </td>
            <td>Extension Adobe [!DNL Analytics] tags pour AppMeasurement.js avec transfert côté serveur activé</td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Lorsque vous souhaitez partager des segments d’Audience Manager vers [!DNL Analytics] pour informer la découverte, la segmentation et l’optimisation des audiences.</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Utilisez des segments Audience Manager qui incluent des données démographiques provenant de fournisseurs tiers dans les rapports [!DNL Analytics].</li>
                    <li>Utilisez des segments Audience Manager qui incluent des données de campagne provenant des serveurs de publicités dans les rapports [!DNL Analytics].</li>
                    <li>Utilisez des segments Audience Manager qui incluent des données de gestion de la relation client intégrées dans les rapports [!DNL Analytics].</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>
