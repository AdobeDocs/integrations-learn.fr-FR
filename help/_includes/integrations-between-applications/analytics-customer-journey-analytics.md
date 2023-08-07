---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '216'
ht-degree: 2%

---


# Intégrer l’Adobe [!DNL Analytics] avec le Parcours client [!DNL Analytics]

{{analytics-description}}

{{customer-journey-analytics-description}}

Intégration de l’Adobe [!DNL Analytics] avec le Parcours client [!DNL Analytics] offre les avantages clés suivants :

+ **insights complets** en ce qui concerne les comportements et les préférences des clients.
+ **Suivi cross-canal transparent** pour une vision holistique.
+ **Données unifiées et création de rapports** pour une analyse précise.
+ **Personnalisation améliorée** et amélioration de l’engagement des clients.
+ **Informations sur les données en temps réel** pour une prise de décision agile.

## Intégrations courantes

<table>
    <thead>
        <tr>
            <th>Applications Experience Cloud</th>
            <th>Intégrer à l’aide de</th>
            <th>Conditions d’utilisation</th>
            <th>Cas d'utilisation courants</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="2">[!DNL Analytics] et Parcours client [!DNL Analytics]</td>
            <td><a href="../../integrations/tutorials/analytics-cja/experience-platform-source-connector.md" target="_blank" rel="noreferrer">Expérience [!DNL Platform] connecteur source</a></td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Approche recommandée pour les clients qui ont déjà mis en oeuvre Adobe [!DNL Analytics], et souhaitent obtenir le moyen le plus rapide d’ingérer ces données dans Experience [!DNL Platform] à utiliser dans le Parcours client [!DNL Analytics].</li>
                    <li>Lorsque la disponibilité des données pour Customer Profile peut se situer entre 2 et 30 minutes à compter du moment de la collecte des données, et la disponibilité pour le lac de données peut atteindre 90 minutes.</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Workflow directement initié par l’interface utilisateur.</li>
                    <li>Mappage de l’interface utilisateur à copier [!DNL Analytics] props et eVars aux nouveaux champs XDM.</li>
                    <li>Le moyen le plus rapide d’obtenir de la valeur à partir de Real-time Customer Profile et du Parcours client [!DNL Analytics].</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><a href="../../integrations/tutorials/analytics-cja/experience-platform-edge.md" target="_blank" rel="noreferrer">Expérience [!DNL Platform] Edge</a></td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Approche recommandée pour les nouvelles [!DNL Analytics] des mises en oeuvre ou lorsque vous souhaitez mettre en oeuvre une stratégie à long terme ;</li>
                    <li>Envoie directement des données d’un appareil à l’expérience [!DNL Platform] à l’aide du SDK Web AEP, du SDK mobile AEP ou de l’API Edge Network Server.</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Fournit le meilleur niveau de contrôle pour les données collectées à utiliser pour prendre en charge vos cas d’utilisation.</li>
                    <li>Les données côté client sont facilement mappées aux champs XDM.</li>
                    <li>Disponibilité des données la plus rapide pour Real-Time Customer Profile.</li>
                </ul>
            </td>
        </tr>  
    </tbody>          
</table>
