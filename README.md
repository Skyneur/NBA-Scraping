# NBA Player Stats Scraper

Ce programme permet de collecter les statistiques des joueurs de la NBA pour chaque saison dans une plage d'années spécifiée par l'utilisateur. Il extrait les données du site web de Basketball Reference, puis calcule et sauvegarde les moyennes annuelles des différentes statistiques des joueurs dans des fichiers Excel. De plus, il génère des graphiques montrant l'évolution de ces moyennes au fil du temps.

## Prérequis

Avant d'exécuter ce programme, assurez-vous d'avoir installé les bibliothèques Python suivantes :

- requests
- BeautifulSoup
- pandas
- openpyxl
- matplotlib
- colorama

Vous pouvez les installer en exécutant la commande suivante :

```
pip install requests beautifulsoup4 pandas openpyxl matplotlib colorama
```

## Utilisation

1. Clonez ce dépôt sur votre machine.

2. Ouvrez un terminal et accédez au répertoire du projet.

3. Exécutez le script Python `nba_stats_scraper.py`.

4. Suivez les instructions à l'écran pour spécifier l'année de début et de fin de la plage d'années pour lesquelles vous souhaitez collecter les statistiques des joueurs de la NBA.

5. Les fichiers Excel contenant les statistiques par année seront sauvegardés dans le dossier `Statistiques`, et les graphiques seront sauvegardés dans le dossier `Graphiques`.

## Exemple

```
$ python nba_stats_scraper.py
Entrez l'année de début : 2010
Entrez l'année de fin : 2015

[🚧] Créations des fichiers excel en cours.

[+] Les statistiques des joueurs de l'année 2009_2010 ont été sauvegardées dans Statistiques/Stats_Joueurs_Nba_Année_2009_2010.xlsx
[+] Les statistiques des joueurs de l'année 2010_2011 ont été sauvegardées dans Statistiques/Stats_Joueurs_Nba_Année_2010_2011.xlsx
[+] Les statistiques des joueurs de l'année 2011_2012 ont été sauvegardées dans Statistiques/Stats_Joueurs_Nba_Année_2011_2012.xlsx
[+] Les statistiques des joueurs de l'année 2012_2013 ont été sauvegardées dans Statistiques/Stats_Joueurs_Nba_Année_2012_2013.xlsx
[+] Les statistiques des joueurs de l'année 2013_2014 ont été sauvegardées dans Statistiques/Stats_Joueurs_Nba_Année_2013_2014.xlsx
[+] Les statistiques des joueurs de l'année 2014_2015 ont été sauvegardées dans Statistiques/Stats_Joueurs_Nba_Année_2014_2015.xlsx

[🚧] Sauvegarde du graphique en cours.

[+] Graphique sauvegardé dans Graphiques/Moyenne_points_par_annee.png
[+] Graphique sauvegardé dans Graphiques/Moyenne_age_par_annee.png
[+] Graphique sauvegardé dans Graphiques/Moyenne_blocks_par_annee.png
[+] Graphique sauvegardé dans Graphiques/Moyenne_passeD_par_annee.png
[+] Graphique sauvegardé dans Graphiques/Moyenne_2P_par_annee.png
[+] Graphique sauvegardé dans Graphiques/Moyenne_3P_par_annee.png
[+] Graphique sauvegardé dans Graphiques/Moyenne_interception_par_annee.png
[+] Graphique sauvegardé dans Graphiques/Moyenne_fautesP_par_annee.png
[+] Graphique sauvegardé dans Graphiques/Moyenne_rebonds_par_annee.png
[+] Graphique sauvegardé dans Graphiques/Moyenne_matchs_par_annee.png
```

## Auteur

Ce programme a été créé par [Skyneur](https://github.com/Skyneur)
