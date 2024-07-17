---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '219'
ht-degree: 1%

---


# Intégrer l&#39;Adobe [!DNL Analytics] au Parcours client [!DNL Analytics]

{{analytics-description}}

{{customer-journey-analytics-description}}

L&#39;intégration de l&#39;Adobe [!DNL Analytics] avec le Parcours client [!DNL Analytics] offre des avantages clés :

+ **Informations complètes** sur les comportements et les préférences des clients.
+ **Suivi cross-canal transparent** pour une vue holistique.
+ **Données unifiées et création de rapports** pour une analyse exacte.
+ **Personnalisation améliorée** et engagement client amélioré.
+ **Informations sur les données en temps réel** pour une prise de décision agile.

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
            <td rowspan="2">[!DNL Analytics] et Parcours client [!DNL Analytics]</td>
            <td><a href="../../integrations/tutorials/analytics-cja/experience-platform-source-connector.md" target="_blank" rel="noreferrer">Connecteur source Experience [!DNL Platform]</a></td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Approche recommandée pour les clients qui ont déjà implémenté l’Adobe [!DNL Analytics] et qui souhaitent ingérer plus rapidement ces données dans Experience [!DNL Platform] à utiliser dans le Parcours client [!DNL Analytics].</li>
                    <li>Lorsque la disponibilité des données pour Customer Profile peut se situer entre 2 et 30 minutes à compter du moment de la collecte des données, et la disponibilité pour le lac de données peut atteindre 90 minutes.</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Workflow directement initié par l’interface utilisateur.</li>
                    <li>Mappage de l’interface utilisateur pour copier [!DNL Analytics] props et eVars vers de nouveaux champs XDM.</li>
                    <li>Méthode la plus rapide pour obtenir de la valeur à partir de Real-time Customer Profile et du Parcours client [!DNL Analytics].</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><a href="../../integrations/tutorials/analytics-cja/experience-platform-edge.md" target="_blank" rel="noreferrer">Experience [!DNL Platform] Edge</a></td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Approche recommandée pour les nouvelles implémentations de [!DNL Analytics] ou lorsque vous souhaitez mettre en oeuvre une stratégie à long terme.</li>
                    <li>Envoie directement des données d’un appareil à l’expérience [!DNL Platform] à l’aide du SDK Web AEP, du SDK AEP Mobile ou de l’API serveur Edge Network.</li>
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
