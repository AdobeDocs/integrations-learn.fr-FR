---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '305'
ht-degree: 0%

---


# Intégrer l&#39;Adobe [!DNL Analytics] aux données client en temps réel [!DNL Platform]

{{analytics-description}}

{{real-time-cdp-description}}

L’intégration de l’Adobe [!DNL Analytics] avec les données client en temps réel Adobe [!DNL Platform] (Real-Time CDP) peut offrir plusieurs avantages aux entreprises qui souhaitent améliorer leurs expériences client et leurs efforts marketing. Voici quelques-uns des avantages clés :

+ **Ciblage et personnalisation d’audience optimisés** : marketing précis sur les appareils et canaux, messages personnalisés pour un engagement optimisé.
+ **Optimisation améliorée de la page d’entrée** : expériences personnalisées basées sur l’appareil et le comportement, ce qui améliore la satisfaction et la conversion des utilisateurs.
+ **Activation de l’audience transparente** : utilisez les profils client pour un ciblage efficace par le biais de canaux préférés, en fournissant des messages pertinents.

En combinant Adobe [!DNL Analytics] et Real-Time CDP, les entreprises peuvent passer leurs efforts marketing au niveau supérieur, en proposant des expériences personnalisées, en augmentant l’engagement des clients et en optimisant les conversions sur différents points de contact numériques.

<table>
    <thead>
        <tr>
            <th>Applications Experience Cloud</th>
            <th>Intégrer à l’aide de</th>
            <th>Quand utiliser</th>
            <th>Cas d'utilisation courants</th>
        </tr>
    </thead>
    <tr>
        <td rowspan="2">[!DNL Analytics] avec Real-Time CDP</td>
        <td><a href="../../integrations/tutorials/analytics-rtcdp/experience-platform-source-connector.md" target="_blank" rel="noreferrer">Connecteur source Experience [!DNL Platform]</a></td>
        <td>
            <ul style="margin-top: 0;">
                <li>Approche recommandée pour les clients qui ont déjà mis en oeuvre l’Adobe [!DNL Analytics] et qui souhaitent ingérer plus rapidement ces données dans Experience [!DNL Platform] afin de les utiliser dans Real-time Customer Profile.</li>
                <li>Lorsque la disponibilité des données pour Real-time Customer Profile peut se situer entre 2 et 30 minutes à compter du moment de la collecte des données, et la disponibilité pour le lac de données peut atteindre 90 minutes.</li>
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
       <td><a href="../../integrations/tutorials/analytics-rtcdp/experience-platform-edge.md" target="_blank" rel="noreferrer">Experience [!DNL Platform] Edge</a></td>
        <td>
            <ul style="margin-top: 0;">
                <li>Approche recommandée pour les nouvelles implémentations de [!DNL Analytics] ou lorsque vous souhaitez mettre en oeuvre une stratégie à long terme.</li>
                <li>Envoie directement des données d’un appareil à l’expérience [!DNL Platform] à l’aide du SDK Web AEP, du SDK AEP Mobile ou de l’API serveur Edge Network.</li>
                <li>Clients nouveaux ou existants qui ont besoin de [!DNL Analytics] disponibilité de données dans Real-Time Customer Profile pour prendre en charge les cas d’utilisation de personnalisation de la même page et de la page suivante.</li>
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
</table>
