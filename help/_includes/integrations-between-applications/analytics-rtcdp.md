---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '319'
ht-degree: 0%

---


# Intégration d’Adobe [!DNL Analytics] à Real-Time Customer Data [!DNL Platform]

{{analytics-description}}

{{real-time-cdp-description}}

L’intégration d’Adobe [!DNL Analytics] à Adobe Real-time Customer Data [!DNL Platform] (Real-Time CDP) peut offrir plusieurs avantages aux entreprises qui cherchent à améliorer leurs expériences client et leurs efforts marketing. Voici quelques-uns des principaux avantages :

+ **Ciblage et personnalisation des audiences améliorés** : marketing précis sur les appareils et les canaux, messages personnalisés pour une interaction optimisée.
+ **Optimisation améliorée des pages de destination** : expériences personnalisées basées sur l’appareil et le comportement, ce qui améliore la satisfaction et la conversion des utilisateurs.
+ **Activation transparente des audiences** : utilisez les profils client pour un ciblage efficace par le biais de canaux préférés, en diffusant des messages pertinents.

En combinant Adobe [!DNL Analytics] et Real-Time CDP, les entreprises peuvent faire passer leurs efforts marketing au niveau supérieur, en offrant des expériences personnalisées, en augmentant l’engagement des clients et en optimisant les conversions sur différents points de contact numériques.

<table>
    <thead>
        <tr>
            <th>Applications Experience Cloud</th>
            <th>Intégration à l’aide d’</th>
            <th>Quand l’utiliser</th>
            <th>Cas d’utilisation courants</th>
        </tr>
    </thead>
    <tr>
        <td rowspan="2">[!DNL Analytics] avec Real-Time CDP</td>
        <td><a href="../../integrations/tutorials/analytics-rtcdp/experience-platform-source-connector.md" target="_blank" rel="noreferrer">Connecteur source Experience [!DNL Platform]</a></td>
        <td>
            <ul style="margin-top: 0;">
                <li>Approche recommandée pour les clients qui ont déjà mis en œuvre Adobe [!DNL Analytics] et qui souhaitent la méthode la plus rapide pour ingérer ces données dans Experience [!DNL Platform] afin de les utiliser dans le profil client en temps réel.</li>
                <li>Lorsque la disponibilité des données pour le profil client en temps réel peut se situer entre 2 et 30 minutes à partir du moment de la collecte de données, et la disponibilité du lac de données peut atteindre 90 minutes.</li>
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
       <td><a href="../../integrations/tutorials/analytics-rtcdp/experience-platform-edge.md" target="_blank" rel="noreferrer">Experience [!DNL Platform] Edge</a></td>
        <td>
            <ul style="margin-top: 0;">
                <li>Approche recommandée pour les nouvelles mises en œuvre d’[!DNL Analytics] ou lorsque vous souhaitez mettre en œuvre une stratégie à long terme.</li>
                <li>Envoie directement des données d’un appareil à Experience [!DNL Platform] à l’aide d’AEP Web SDK, d’AEP Mobile SDK ou de l’API Edge Network Server.</li>
                <li>Clients nouveaux ou existants qui ont besoin d’une disponibilité [!DNL Analytics] des données dans le profil client en temps réel pour prendre en charge les cas d’utilisation de la personnalisation de la même page et de la page suivante.</li>
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
</table>
