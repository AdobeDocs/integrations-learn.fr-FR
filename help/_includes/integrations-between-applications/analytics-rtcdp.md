---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '302'
ht-degree: 1%

---


# Intégrer l’Adobe [!DNL Analytics] avec données client en temps réel [!DNL Platform]

{{analytics-description}}

{{real-time-cdp-description}}

Intégration de l’Adobe [!DNL Analytics] avec des données client en temps réel Adobe [!DNL Platform] (Real-Time CDP) peut offrir plusieurs avantages aux entreprises qui souhaitent améliorer leurs expériences client et leurs efforts marketing. Voici quelques-uns des avantages clés :

+ **Amélioration du ciblage et de la personnalisation des audiences**: marketing précis sur les appareils et canaux, messages personnalisés pour un engagement optimisé.
+ **Optimisation améliorée des landing pages**: expériences personnalisées basées sur l’appareil et le comportement, ce qui améliore la satisfaction et la conversion des utilisateurs.
+ **Activation transparente de l’audience**: utilisez les profils client pour un ciblage efficace par le biais de canaux privilégiés, en fournissant des messages pertinents.

En combinant l’Adobe [!DNL Analytics] et Real-Time CDP, les entreprises peuvent passer leurs efforts marketing au niveau supérieur, en proposant des expériences personnalisées, en augmentant l’engagement des clients et en optimisant les conversions sur divers points de contact numériques.

<table>
    <thead>
        <tr>
            <th>Applications Experience Cloud</th>
            <th>Intégrer à l’aide de</th>
            <th>Conditions d’utilisation</th>
            <th>Cas d'utilisation courants</th>
        </tr>
    </thead>
    <tr>
        <td rowspan="2">[!DNL Analytics] avec Real-Time CDP</td>
        <td><a href="../../integrations/tutorials/analytics-rtcdp/experience-platform-source-connector.md" target="_blank" rel="noreferrer">Expérience [!DNL Platform] connecteur source</a></td>
        <td>
            <ul style="margin-top: 0;">
                <li>Approche recommandée pour les clients qui ont déjà mis en oeuvre Adobe [!DNL Analytics], et souhaitent obtenir le moyen le plus rapide d’ingérer ces données dans Experience [!DNL Platform] à utiliser dans Real-time Customer Profile.</li>
                <li>Lorsque la disponibilité des données pour Real-time Customer Profile peut se situer entre 2 et 30 minutes à compter du moment de la collecte des données, et la disponibilité pour le lac de données peut atteindre 90 minutes.</li>
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
       <td><a href="../../integrations/tutorials/analytics-rtcdp/experience-platform-edge.md" target="_blank" rel="noreferrer">Expérience [!DNL Platform] Edge</a></td>
        <td>
            <ul style="margin-top: 0;">
                <li>Approche recommandée pour les nouvelles [!DNL Analytics] des mises en oeuvre ou lorsque vous souhaitez mettre en oeuvre une stratégie à long terme ;</li>
                <li>Envoie directement des données d’un appareil à l’expérience [!DNL Platform] à l’aide du SDK Web AEP, du SDK mobile AEP ou de l’API Edge Network Server.</li>
                <li>Clients nouveaux ou existants ayant besoin de [!DNL Analytics] Disponibilité des données pour Real-time Customer Profile afin de prendre en charge les cas d’utilisation de la personnalisation de la même page et de la page suivante.</li>
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
