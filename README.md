# 🌦️ Présentation du projet : Création d'histogrammes de précipitations ☔

## 🚀 Contexte :

💧Sur mon site personnel, je fournis des visualisations détaillées des précipitations à La Tessoualle, pour que mes visiteurs puissent facilement comprendre les tendances pluviométries au fil du temps. <br />
L'objectif de ce projet est de créer des histogrammes informatifs pour illustrer les variations des précipitations sur une période donnée.

<br />

## 🔭 Objectifs :
    • Afficher des histogrammes des précipitations pour des périodes variées (par jour, mois, année).
    • Permettre à l'utilisateur de sélectionner une période spécifique à analyser.
    • Offrir une interface visuelle agréable pour la consultation des données.

<br />

## 🛠️ Technologies utilisées :

###    • Python <img style="margin: 10px" src="images/python.png" alt="Python" title="Python" height="20" />: 
    Langage de programmation pour le traitement des données et la création des graphiques.

###    • Pandas <img style="margin: 10px" src="images/pandas.png" alt="Pandas" title="Pandas" height="20" />: 
    Bibliothèque Python pour la manipulation et l'analyse des données.

###    • Matplotlib <img style="margin: 10px" src="images/matplotlib.png" alt="Matplotlib" title="Matplotlib" height="20" />: 
    Bibliothèque pour la création des histogrammes et des visualisations graphiques.
    
###    • Numpy <img style="margin: 10px" src="images/numpy.png" alt="Numpy" title="Numpy" height="20" />: 
    Bibliothèque pour langage de programmation Python, destinée à manipuler des matrices ou tableaux multidimensionnels ainsi que des fonctions mathématiques opérant sur ces tableaux. 

<br />

## 📝 Description du processus :

    1. Collecte des données : <br />
        Les données de précipitation sont collectées et ajoutées chaque mois au fichier Python.

    2. Création des histogrammes :<br />
        ◦ Les histogrammes sont générés à l'aide de Matplotlib. Chaque barre de l'histogramme représente la quantité de précipitation pendant une période définie.
        ◦ Les utilisateurs peuvent choisir différentes périodes (jour, mois, année) pour observer l'évolution des précipitations.
          
    3. Intégration des visualisations dans le site web :<br />
        ◦ Les graphiques sont ensuite intégrés dans le site web sous le format image. 
        ◦ L'utilisateur peut ajuster les filtres (par exemple, sélectionner une période) et obtenir le graphique de la période choisie.
          
    4. Améliorations possibles :<br />
        ◦ Intégrer ces visualisations directement dans le site web pour une consultation fluide  avec Flask.
        ◦ Inclure les données de précipitation sont collectées dans la base de données MySQL du site.

<br />

## 🔍 Résultat attendu :
A voir sur mon site ici : <a href="http://nelly.babin.free.fr/meteo/index.php" target="_blank" title="Météo sur mon site perso">Météo sur mon site perso</a><br />
L'utilisateur voit un graphique avec des barres représentant la somme des précipitations du jour pour chaque mois et les cumules des mois de l'année.<br /> 
Il peut sélectionner le mois ou l’année pour explorer les différentes périodes.

<br />

## 🎯Conclusion :

Ce projet offre une manière simple et efficace de créer des graphiques des précipitations au fil du temps pour mon site web.
<br /><br />

## 🌧️ Evolution : Graphiques dynamiques avec Chart.js

- Découverte de `Chart.js` <a href="https://www.chartjs.org/" target="_blank"><img style="margin: 10px" src="images/Chartjs.png" alt="Chartjs" title="Chartjs" height="25" /></a>
- Ajouter de fonctions `Python` pour générer un fichier `sql` avec la requête pour insérer les données dans la base de données.
- Créer des graphiques interactifs
- Ajout de nouveaux graphiques ...
<br />

| 📄 Page                         | 🔗 Lien                                                                 | 📝 Description                                             |
| ------------------------------- | ----------------------------------------------------------------------- | ---------------------------------------------------------- |
| Histogramme d’un mois           | <a href="http://nelly.babin.free.fr/meteo/dynamique.php" target="_blank">Voir la page</a>          | Histogramme pluie/neige pour un mois donné                 |
| Courbes mensuelles comparatives | <a href="http://nelly.babin.free.fr/meteo/comparaison.php" target="_blank">Voir la page</a>        | Comparaison de la pluie sur un mois entre plusieurs années |
| Cumuls mensuels                 | <a href="http://nelly.babin.free.fr/meteo/cumuls_mensuels.php" target="_blank">Voir la page</a>    | Cumuls pluie/neige par mois sur une année                  |
| Cumuls annuels                  | <a href="http://nelly.babin.free.fr/meteo/cumuls_annuels.php" target="_blank">Voir la page</a>     | Cumuls pluie/neige par année sur une période               |
| Courbes annuelles comparatives  | <a href="http://nelly.babin.free.fr/meteo/comparaison-annuel.php" target="_blank">Voir la page</a> | Comparaison annuelle de la pluie sur 12 mois               |

<br />
📝 Dépôt du projet
<a href="https://github.com/nelbab/python-histogrammes/blob/main/graphes-precipitation.md" target="_blank" title="Détail du développement en Chart.js">Détail du développement `Chart.js` </a>  <br/>
