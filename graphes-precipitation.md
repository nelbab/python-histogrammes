# 🌧️ Graphiques dynamiques avec Chart.js ❄️ #

## 1. 📊 Objectifs de ce projet

Améliorations de mes graphiques de précipitations.<br>
- Dynamique et responsif.
- Données à partir de la base de données.
- Découverte de la librairie `Chart.js`.
<br /><br />

## 2. 👩‍💻 Conception

- Ajout d'une table pour le relevé journalier des jours avec pluie et/ou neige avec possibilité de saisir un commentaire (orage, grêle,...).
- Ajouter d'un graphique comparatif d'un mois entre différentes années.
- Ajouter d'un graphique comparatif entre différentes années.
- Curseur interactif avec relevé de pluie et/ou de neige, commentaire.
- Téléchargement du graphique au format PNG ou en PDF.
- Export en PNG du graphique.
- Export en PDF du graphique avec les statistique.
- Ajout de statistiques (moyenne, maximun, minimun).
- Ajout de tableaux statistiques.

## 3. 🛠️ Technologies utilisées : 
<a href="https://en.wikipedia.org/wiki/HTML5" target="_blank"><img style="margin: 10px" src="images/html5.png" alt="HTML5" title="HTML5" height="50" /></a>
<a href="https://www.w3schools.com/css/" target="_blank"><img style="margin: 10px" src="images/css3.png" alt="CSS3" title="CSS3" height="50" /></a>
<a href="https://www.php.net/" target="_blank"><img style="margin: 10px" src="images/php.png" alt="PHP" title="PHP" height="50" /></a>
<a href="https://www.mysql.com/" target="_blank"><img style="margin: 10px" src="images/mysql.png" alt="MySQL" title="MySQL" height="50" /></a>
<a href="https://www.javascript.com/" target="_blank"><img style="margin: 10px" src="images/js.png" alt="JavaScript" title="JavaScript" height="50" /></a>
<a href="https://www.chartjs.org/" target="_blank"><img style="margin: 10px" src="images/Chartjs.png" alt="Chartjs" title="Chartjs" height="50" /></a>
<a href="https://code.visualstudio.com/" target="_blank"><img style="margin: 10px" src="images/visualStudiocode.png" alt="Visual Studio Code" title="Visual Studio Code" height="50" /></a>
<a href="https://httpd.apache.org" target="_blank"><img style="margin: 10px" src="images/apache.png" alt="Apache" title="Apache" height="50" /></a>  

## 4. Détail des pages :

### a. Histogramme d'un mois
- Histogramme avec 2 barres du mois sélectionné de pluie et de neige
- Statistiques : 
  - 🌧️ Total pluie (mm)
  - 📊 🌧️ Moyenne quotidienne pluie (mm)
  - 📈 Pluie max (mm)
  - 📉 Pluie min (mm)
  - ❄️ Total neige (cm)
  - 📊 ❄️ Moyenne neige (cm)
  - 📈 Neige max (cm)
  - 📉 Neige min (cm)
  
### b. Courbes mensuelles comparatives de pluie
- Courbes d'un mois pour plusieurs années
- Courbes pour chaque année
- Limitation de l'affichage à 7 années
- Conseil : Sélectionnez 3-5 années pour une meilleure lisibilité
- Statistiques : 
  - Cumul moyen mensuel (mm)
  - Médiane journalière (mm)
- Records :
  - Année la plus pluvieuse et (mm)
  - Année la plus sèche et (mm)
  - Record journalier (mm)
  - Date du record
- Tableau de détails par Année
  - Cumul (mm)
  - Moyenne/jour (mm)
  - Jours de pluie
  - Maximum (mm)
  - % du mois pluvieux

### c. Cumuls mensuels
- Histogramme avec 2 barres du mois sélectionné de pluie et de neige
- Statistiques : 
  - 🌧️ Total annuel (mm)
  - 📊 🌧️ Moyenne mensuelle (mm)
  - 🌧️ Maximum (mm) (mois)
  - 🌧️ Minimum (mm) (mois)
  - ❄️ Total annuel (cm)
  - 📊 ❄️ Moyenne mensuelle (cm)
  - ❄️ Maximum (cm) (mois)
  - ❄️ Minimum (cm) (mois)

### d. Cumuls annuels
- Histogramme avec 2 barres par années sélectionnées de pluie et de neige
- Statistiques : 
  - 🌧️ Total période (mm)
  - 📊 🌧️ Moyenne annuelle (mm)
  - 🌧️ Maximum (mm) (mois)
  - 🌧️ Minimum (mm) (mois)
  - ❄️ Total période (cm)
  - 📊 ❄️ Moyenne annuelle (cm)
  - ❄️ Maximum (cm) (mois)
  - ❄️ Minimum (cm) (mois) 

### e. Courbes annuelles comparatives de pluie
- Courbes sur 12 mois pour plusieurs années
- Courbes pour chaque année
- Limitation de l'affichage à 7 années
- Conseil : Sélectionnez 3-5 années pour une meilleure lisibilité
- Statistiques : 
  - Cumul moyen annuel (mm)
- Records :
  - Année la plus pluvieuse et (mm)
  - Année la plus sèche et (mm)
  - Ecart (mm)
- Tableau de détails par Année
  - Total annuel (mm)
  - Moyenne mensuelle (mm)
  - Jours de pluie
  - Maximum journalier (mm)
  - Ecart à la moyenne
- Moyennes Mensuelles sur la Période
  - Mois
  - Différentes années (mm)
  - Moyenne (mm)
<br /><br />

## 5. Voici les liens :

<a href="http://nelly.babin.free.fr/meteo/dynamique.php" target="_blank" title="Histogramme d'un mois">Histogramme d'un mois </a>
<br /><br />
<a href="http://nelly.babin.free.fr/meteo/comparaison.php" target="_blank" title="Courbes mensuelles comparatives de pluie">Courbes mensuelles comparatives de pluie </a>
<br /><br />
<a href="http://nelly.babin.free.fr/meteo/cumuls_mensuels.php" target="_blank" title="Cumuls mensuels">Cumuls mensuels</a>
<br /><br />
<a href="http://nelly.babin.free.fr/meteo/cumuls_annuels.php" target="_blank" title="Cumuls annuels">Cumuls annuels</a>
<br /><br />
<a href="http://nelly.babin.free.fr/meteo/comparaison-annuel.php" target="_blank" title="Courbes annuelles comparatives de pluie">Courbes annuelles comparatives de pluie</a>
<br /><br />

## 6. 🖥️ Captures d'écrans : 

🎴Ecran des nouveaux graphiques :<br />
- Histogramme d'un mois
<img style="margin: 10px" src="images/dynamique.png" alt="Histogramme d'un mois" title="Histogramme d'un mois" height="200px" />
- Cumuls mensuels
<img style="margin: 10px" src="images/cumuls_mensuels.png" alt="Cumuls mensuels" title="Cumuls mensuels" height="200px" />  
- Courbes mensuelles comparatives de pluie de plusieurs années
<img style="margin: 10px" src="images/comparaison.png" alt="Courbes comparatives de pluie" title="Courbes comparatives de pluie" height="200px" />
- Cumuls annuels
<img style="margin: 10px" src="images/cumuls_annuels.png" alt="Cumuls annuels" title="Cumuls annuels" height="200px" />
- Courbes annuelles comparatives de pluie de plusieurs années
<img style="margin: 10px" src="images/comparaison_annuelle.png" alt="Cumuls annuels" title="Cumuls annuels" height="200px" />
<br /><br />

## 7. 📝 Conclusion

Ce projet m’a permis d’explorer en profondeur les possibilités offertes par `Chart.js` pour créer des <b>graphiques de précipitations dynamiques, interactifs et esthétiques</b>. Grâce à l’intégration des <b>données issues d’une base de données</b>, les visualisations sont désormais <b>actualisées en temps réel</b>. L’ajout d’un <b>graphique comparatif, d’un curseur interactif</b> ainsi que de les <b>fonctions de téléchargement au format PNG et en PDF</b> enrichissent l’expérience utilisateur et améliorent la lisibilité des données.

En somme, ce projet a été une excellente opportunité pour :

- Apprendre à manipuler `Chart.js` de manière avancée.

- Rendre mes visualisations plus attractives et fonctionnelles.

- Manipuler les données de ma base `MySQL`.

- Manipuler des statistiques.