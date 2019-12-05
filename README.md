# Croissance des coraux

## Module 5 

### Etat d'avancement

Réalisez la suite d'opérations demandée sur le jeu de données coral_growth 

- Créez votre projet à partir du dépôt GitHub Classroom fournit

- Organisez votre projet en un ensemble de sections. La théorie liée à l'organisation d'un projet se situe dans l'annexe dédié aux [projets dans RStudio](http://biodatascience-course.sciviews.org/sdd-umons/rs.html#rs-projet) 

- Dans un **script R**, importez vos données depuis l'url suivant :

<https://docs.google.com/spreadsheets/d/e/2PACX-1vSxqegwJVjO0PxIs7mObr0syeYwNdpvd25AWUoWkwocQexYUqQUK0hC57NwsypQQUDnsJLiR-hxzSFA/pub?output=csv>

La théorie liée à l'importation des données depuis un url se situe dans la section relative à l'[imporation des données depuis Internet](http://biodatascience-course.sciviews.org/sdd-umons/importation-des-donnees.html#donnees-depuis-internet)

- Enregistrez un copie en local de ce jeu de données.

- Dans un fichier au format Rmd, importez les données à partir de la copie enregistrée précédement. 

Ce jeu de données comprend 8 variables :

Ce jeu de données reprend des mesures de croissance de différentes espèces de coraux. La masse est mesurée en t0 puis une seconde fois après 7 jours de suivi. 

- localisation : aquarium dans lequel la bouture est placée. Les installations sont composées de deux unités (A et B)et de plusieurs bacs par unité.
- species : espèce étudiée
- id : code de l'individu
- salinity : salinité mesurée en t7
- temperature : température mesurée en t7
- date : date de la mesure en t7
- time : nombre de jour entre la mesure initiale et finale
- gain : gain de masse en g entre le jour t0 et t7
- gain_std : gain/masse initiale

### Remaniement des données 

- Transformez la variable **localisation** et la variable **species** en variable facteur.

- Dans votre fichier Rmd, réalisez un tableau réduit en retirant du tableau principal la variable **salinity**, **temperature** et **date**. Affichez votre nouveau tableau dans votre rapport. 

- Dans votre fichier Rmd, réalisez un tableau réduit qui utilise le tableau réalisé ci-dessus qui filtre les valeurs négatives dans la variable **gain**. Affichez votre nouveau tableau dans votre rapport. 

- Dans votre fichier Rmd, Calculez de nouvelles variables que vous ajoutez au tableau de base.
    +  Divisez le gain de masse par le nombre de jour d'expérience. 
    + Divisez le gain de masse standardisé par le nombre de jour d'expérience et multipliez cette nouvelle variable par 100 pour obtenir la croissance en pourcent par jour. 

- Réalisez au minimum 2 tableaux résumant les données par aquarium et par espèce. Ce tableau doit contenir le nombre d'observation, la valeur minimale, la valeur maximale, la valeur médiane et la moyenne. 

*note:* Chaque tableau doit être commenté dans le texte de votre fichier Rmd.





