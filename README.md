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

###    • Python : 
    Langage de programmation pour le traitement des données et la création des graphiques.

###    • Pandas : 
    Bibliothèque Python pour la manipulation et l'analyse des données.

###    • Matplotlib  : 
    Bibliothèque pour la création des histogrammes et des visualisations graphiques.
    
###    • Numpy : 
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

L'utilisateur voit un graphique avec des barres représentant la somme des précipitations du jour pour chaque mois et les cumules des mois de l'année.<br /> 
Il peut sélectionner le mois ou l’année pour explorer les différentes périodes.

<br />

## 🎯Conclusion :

Ce projet offre une manière simple et efficace de créer des graphiques des précipitations au fil du temps pour mon site web.