# Exploration de données du système Ford GoBike
## by Medi Vankembo


## Ensemble de données

> Ford GoBike est un système de données qui comprend des informations sur les trajets individuels effectués dans un système de partage de vélos couvrant la grande région de la baie de San Francisco. Avec environ 20 000 vélos et plus de 1 300 stations, Il a été conçu pour les déplacements rapides et pratiques, et constitue un moyen amusant et abordable de se déplacer en ville.
> 
> Les données à notre disposition se rapport aux durée de trajets parcourus, au stations de départ et d'arrivée(coordonnées géographiques, nom, id), aux vélo(type de velo, id), et aux utilisateurs(Date de naissance, sexe,...).
>
>Nous avons rencontré certains problèmes d'ordre et de de qualités, qui nous ont poussés à réaliser certains travaux de nettoyage entre-autre :
> - Supprimer les lignes contenant des valeurs nulles
> - Changer de types de données
> - Créer un autre ensembe(dataframe) qui contient les données des stations
> - Supprimer des colonnes non nécessaires pour notre cas d'analyse
> - Créer d'autres colonnes nécessaires.

## Résumé des résultats

> Nous avons exploré nos données afin de comprendre en profondeur de quelle manière les autres caractéristiques avaient de l'influence sur les durées de courses réalisées.
>
> Avant toute chose, il est clair que les stations(de départ et d'arrivée) avaient une influence majeure. Plus les deux stations sont éloignées, plus la durée du projet sera longues. De ce fait, notre étude n'a pas portée sur les caractéristiques liées aux stations.
>
> Sur ce, nous nous sommes concentrés sur les caractéristiques suivantes :
**le type d'utilisateur**, **les années de naissance des utilisateurs**, **le type de vélo**, **le genre d'utilisateurs**, **les jours semaine**, **les heures de la journées**, **les jours du mois**.
>
>Nous avons trouvé que certaines caratériques ont de l'influence, notamment **le type d'utilisateur**, **les années de naissance des utilisateurs**, **le type de vélo**, **le genre d'utilisateurs**, **les jours semaine**, **les heures de la journées**
>
>Par contre d'autres caractéristiques n'influencent pas les durées de courses, telle que **les jours du mois**


## Principales idées pour la présentation

> De quelle manière les jours de la semaine influencent-ils les durées des courses ?
>
> Comment pouvons-nous affirmer que les genres(sexes) et le types d'utilisateurs influent sur les durées de courses ?
>
>Quelle est l'influence des types de cyclistes et leurs sexes sur la durée des courses ?

Les réponses à ces éléments constituent les principales idées présentées à la deuxième partie ce projet.