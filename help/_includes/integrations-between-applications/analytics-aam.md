---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '367'
ht-degree: 0%

---


# [!DNL Analytics] et intégration des Audiences Manager

{{analytics-description}}

{{audience-manager-description}}

L’activation de cette intégration, en transférant l’Adobe de données [!DNL Analytics] côté serveur vers l’Audience Manager, donne à l’Audience Manager l’une de ses principales sources de données, à savoir les données comportementales des clients en ligne. Ces données peuvent ensuite être combinées à d’autres données, telles que des données CRM propriétaires ou des données de partenaire tiers, afin de créer des segments client riches. En outre, les segments d’Audience Manager sont renvoyés à la page web dans la réponse pour une analyse plus approfondie des visiteurs. Ces deux cas pratiques sont décrits ci-dessous.

Les principaux avantages de l&#39;intégration de l&#39;Adobe [!DNL Analytics] et de l&#39;Audience Manager sont les suivants :

+ **Segmentation améliorée** : combinez des données d’Adobe [!DNL Analytics] et d’Audience Manager pour des segments d’audience précis et personnalisés dans des campagnes marketing.
+ **Profils client unifiés** : intégrez des sources de données pour comprendre les interactions et les comportements, en créant des profils client complets.
+ **Amélioration de l’efficacité des publicités** : optimisez les publicités grâce au ciblage piloté par les données à partir de l’intégration d’Adobe [!DNL Analytics] et d’Audience Manager.
+ **Décisions pilotées par les données** : informez les choix grâce à des informations détaillées, à la fusion des données d’Adobe [!DNL Analytics] et d’Audience Manager.
+ **Expériences personnalisées** : personnalisez votre contenu et vos offres, en enrichissant les interactions client sur plusieurs points de contact à l’aide des deux plateformes.

Dans l’ensemble, cette intégration rassemble des données et des informations précieuses sur l’audience. Il permet aux entreprises de créer des campagnes marketing plus ciblées et plus pertinentes tout en acquérant une meilleure compréhension des préférences et des comportements de leurs clients.

## Intégrations courantes

<table>
    <thead>
        <tr>
            <th>Applications Experience Cloud</th>
            <th>Intégrer à l’aide de</th>
            <th>Quand utiliser</th>
            <th>Cas d'utilisation courants</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <a href="/docs/analytics-learn/tutorials/integrations/audience-manager/enable-server-side-forwarding-in-adobe-launch.html" target="_blank" rel="noreferrer">[!DNL Analytics] envoi de données à l'Audience Manager</a>
            </td>
            <td>Adobe l’extension de balises [!DNL Analytics] ou AppMeasurement.js avec le transfert côté serveur activé</td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Lorsque vous souhaitez envoyer des données d’Adobe [!DNL Analytics] à l’Audience Manager afin de créer des segments qui peuvent être partagés avec d’autres destinations Adobe Experience Cloud, des destinations basées sur des personnes ou d’autres destinations basées sur des appareils et personnalisées prises en charge par l’Audience Manager.</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Partagez des segments sur des plateformes publicitaires qui incluent des attributs comportementaux collectés dans [!DNL Analytics].</li>
                    <li>Enrichissez les segments avec des données [!DNL Analytics] pour créer des segments cross-canal à forte valeur ajoutée à utiliser dans le ciblage sur site.</li>
                    <li>Calculez les données de [!DNL Analytics] vers des segments masqués sur des identifiants hachés, tels que le courrier électronique, à utiliser dans les plateformes de médias sociaux.</li>
                </ul>
            </td>
        </tr>        
        <tr>
            <td>
                <a href="https://experienceleague.adobe.com/docs/analytics/integration/audience-analytics/mc-audiences-aam.html?lang=fr" target="_blank" rel="noreferrer">Audience Manager de l’envoi de données à [!DNL Analytics]</a>
            </td>
            <td>Adobe l’extension de balises [!DNL Analytics] ou AppMeasurement.js avec le transfert côté serveur activé</td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Lorsque vous souhaitez partager des segments d’Audience Manager vers [!DNL Analytics] afin d’informer la découverte d’audiences, la segmentation et l’optimisation.</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Utilisez des segments d’Audience Manager qui incluent des données démographiques de fournisseurs tiers dans les rapports [!DNL Analytics].</li>
                    <li>Utilisez des segments d’Audience Manager qui incluent des données de campagne provenant de serveurs d’annonces dans des rapports [!DNL Analytics].</li>
                    <li>Utilisez des segments d’Audience Manager qui incluent des données de gestion de la relation client intégrées dans des rapports [!DNL Analytics].</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>
