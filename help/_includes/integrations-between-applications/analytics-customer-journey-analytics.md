---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '228'
ht-degree: 1%

---


# Intégration d’Adobe [!DNL Analytics] à Customer Parcours [!DNL Analytics]

{{analytics-description}}

{{customer-journey-analytics-description}}

L’intégration d’Adobe [!DNL Analytics] à Customer Parcours [!DNL Analytics] offre les avantages principaux suivants :

+ **Informations complètes** sur les comportements et les préférences des clients.
+ **Suivi cross-canal transparent** pour une vue holistique.
+ **Données et rapports unifiés** pour une analyse précise.
+ **Personnalisation améliorée** et engagement amélioré des clients.
+ **Informations sur les données en temps réel** pour une prise de décision agile.

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
            <td rowspan="2">[!DNL Analytics] et Parcours client [!DNL Analytics]</td>
            <td><a href="../../integrations/tutorials/analytics-cja/experience-platform-source-connector.md" target="_blank" rel="noreferrer">Connecteur source Experience [!DNL Platform]</a></td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Approche recommandée pour les clients qui ont déjà mis en œuvre Adobe [!DNL Analytics] et qui souhaitent la méthode la plus rapide pour ingérer ces données dans Experience [!DNL Platform] afin de les utiliser dans Customer Parcours [!DNL Analytics].</li>
                    <li>Lorsque la disponibilité des données pour le profil client peut se situer entre 2 et 30 minutes à compter de la collecte de données, et la disponibilité du lac de données peut atteindre 90 minutes.</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Workflow simple et initié par l’interface utilisateur.</li>
                    <li>Mappage de l’interface utilisateur pour copier des props et des eVars [!DNL Analytics] vers de nouveaux champs XDM.</li>
                    <li>Moyen le plus rapide d’obtenir de la valeur grâce aux [!DNL Analytics] de profil client en temps réel et de Parcours client.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><a href="../../integrations/tutorials/analytics-cja/experience-platform-edge.md" target="_blank" rel="noreferrer">Experience [!DNL Platform] Edge</a></td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Approche recommandée pour les nouvelles mises en œuvre d’[!DNL Analytics] ou lorsque vous souhaitez mettre en œuvre une stratégie à long terme.</li>
                    <li>Envoie directement des données d’un appareil à Experience [!DNL Platform] à l’aide d’AEP Web SDK, d’AEP Mobile SDK ou de l’API Edge Network Server.</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Fournit le plus haut niveau de contrôle pour les données collectées à utiliser pour la prise en charge de vos cas d’utilisation.</li>
                    <li>Les données côté client sont facilement mappées aux champs XDM.</li>
                    <li>Disponibilité rapide des données pour le profil client en temps réel.</li>
                </ul>
            </td>
        </tr>  
    </tbody>          
</table>
