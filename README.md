# Fiche descriptif de TesoHelper

## Introduction

Le projet consiste à faire une application web destinée aux joueurs de The Elder Scrolls Online, visant à simplifier le processus de création des personnages et de builds.
<br>
Conçue pour offrir une expérience agréable dans le jeu, cette application permettra aux utilisateurs de visualiser les statistiques de leurs personnages en fonction des équipements et compétences sélectionnés, tout en fournissant des informations détaillées sur les ressources nécessaires pour optimiser leurs builds.

## Desription du projet : 

L'application se divise en plusieurs fonctionnalités clés :
- **Création de personnage** : Les utilisateurs pourront créer des personnages en spécifiant leur niveau, leur attributs, leurs points champion et leurs compétences. Cette fonctionnalité offre la base des premières statistiques pour expérimenter les différents builds.
- **Prévisualisation des équipements** : Les utilisateurs pourront sélectionner plusieurs ensembles d'équipements et observer l'impact de ces choix sur les statistique du personnage. Cela permet donc d'évaluer et d'affiner leurs builds selon leurs besoins.
- **Récapitulatif des ressources** : Pour chaque ensemble d'équipements, l'application fournira un récapitulatif des ressources nécessaires pour le craft ou l'améliorer au maximumu. De plus, elle proposera des liens vers des ressources externes (telles que ESOAZ) pour obtenir des ensembles d'équipements spécifiques, facilitant ainsi l'accessibilité aux informations cruciales pour obtenir le set.

## Architecture système :

L'architecture de l'application repose sur une approche modulaire, avec des applications Django distinctes pour chaque fonctionnalités.
<br>
Les calculs des statistiques des personnages seront effectués côtés serveur pour garantir la précision des données, tandis que les interactions utilisateur seront gérées côté client.
<br>
Les informations relatives aux personnages, aux builds et aux ensembles d'équipements seront stockées dans une base de données relationnelle, assurant ainsi une meilleure gesion des données.

## Fonctionnalités :

1. **Création de personnages** :
    - Interface pour spécifier les attributs, les compétences et les points champion du personnage.
    - Possibilité de sauvegarder et de charger plusieurs personnages pour une meilleure gestion

2. **Prévisualisation des équipements** :
    - Sélection intuitive des ensembles d'équipements pour observer en temps réel l'impact sur les statistiques du personnage.
    - Fonctionnalité de comparaison pour évaluer les avantages et inconvénients de différents builds.
3. **Récapitulatif des ressources** :
    - Affichage détaillé des ressources nécessaires pour améliorer chaque ensemble d'équipements (ressources en fonction de la catégorie et du type de l'équipement).
    - Liens directs vers des ressources externes (telles que ESOAZ) pour obtenir des ensemble d'équipements spécifiques (obtenable via donjon, raid, quêtes, etc). Offrant ainsi un accès rapides à des informations complémentaires.

## Utilisateurs et rôles :

- **Administrateur** : Gère l'ajout de nouveaux ensemble d'équipements via une interface d'administration dédiée.
- **Utilisateur avec un compte** : Peut créer, sauvegarder et charger plusieurs personnages avec différents builds.
- **Utilisateur invité (sans compte)** : Peut créer un nouveau personnage à chaque utilisation de l'application, sans possibilité de sauvegarde.

## Conclusion

L'application vise à simplifier et à enrichir l'expérience des joueurs de The Elder Scrolls Online en leur offrant un outil complet pour créer et visualiser des personnages avec précision. Bien que les évolutions futures ne soient pas encore prévues pour le moment, l'application reste flexible pour intégrer de nouvelles fonctionnalités en fonction des retours des utilisateurs et de l'évolution du jeu.
<br>
Cette fiche descriptif détaille les fonctionnalités et objectifs du projet, mettant en avant son potentiel à répondre aux besoins des joueurs, tout en offrant une expérience utilisateur optimale (je l'espère).
<br>
<hr>
Cette fiche de descriptif reste ouverte aux critiques et différentes propositions qui seront faites par les joueurs eux-mêmes.

