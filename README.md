

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="#">
    <img src="IMAGES/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Projet de Data Engineering</h3>

  <p align="center">
    <br />
    <a href="https://github.com/guypi001<strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/guypi001> Koman ABOI</a>
    ·
    <a href="https://github.com/github_username/repo_name/issues">Mamadou BARRY</a>
  </p>
</div>





<!-- ABOUT THE PROJECT -->
## Présentation

Le football est l'un des sports les plus populaires au monde, suivi par des millions de fans passionnés. Le marché des transferts dans le football est également un domaine passionnant qui attire beaucoup d'attention, car il implique des millions de dollars de transactions chaque année. En tant que tel, l'analyse de ces transferts peut fournir des informations précieuses sur les tendances et les comportements du marché, qui peuvent être utilisées pour prendre des décisions commerciales éclairées.

Dans ce projet, nous avons analysé les données des transferts dans le football depuis la professionnalisation du sport jusqu'à aujourd'hui. Nous avons utilisé des techniques de data engineering pour nettoyer, transformer et intégrer les données provenant de diverses sources pour faciliter l'analyse. Nous avons également utilisé des méthodes d'apprentissage automatique pour modéliser les tendances du marché et prédire les transferts futurs.

Le but de ce projet est de fournir une analyse complète et détaillée du marché des transferts dans le football, qui peut être utilisée pour informer les décisions commerciales et les stratégies de gestion des clubs. Nous avons également inclus des visualisations claires pour aider à comprendre les tendances et les relations entre les différentes variables.

Dans les sections suivantes, nous allons décrire les données que nous avons utilisées, l'architecture technique que nous avons mise en place, les résultats de notre analyse, les enseignements que nous avons tirés de notre étude et les implications pour l'industrie du football. Nous espérons que cette analyse sera utile pour tous ceux qui s'intéressent au marché des transferts dans le football et qui cherchent à en savoir plus sur les tendances et les comportements du marché.

<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- GETTING STARTED -->
## Analyse

Les données utilisées pour ce projet ont été recueillies auprès de diverses sources, la source principale étant le site Web Transfermarkt.com, qui est l'un des plus grands sites Web de données sur le football au monde. De plus, nous avons également utilisé les données d'opdata, quoique dans une moindre mesure. Le site Internet Transfermarkt.com contient une mine d'informations sur les joueurs, les clubs, les transferts, les contrats, les statistiques des matchs et de nombreuses autres données liées au football. Les données sont présentées sous forme de tableaux sur un grand nombre de pages Web. Certaines informations, telles que les valeurs de transfert, étaient situées dans des zones spécifiques de la page et nécessitaient une technique de grattage pour extraire les données.

Pour extraire les données, nous avons utilisé le langage de programmation Python, en utilisant le module BeautifulSoup pour extraire les données HTML et le module Selenium pour naviguer et extraire les données des pages Web dynamiques. Les données extraites ont été nettoyées, transformées et stockées dans des fichiers CSV. Nous avons effectué trois mises à jour des données au cours du projet, la mise à jour finale étant effectuée avant l'analyse finale.

Les données collectées incluent des informations sur les joueurs, telles que leur nom, leur âge, leur position, leur nationalité et leur historique de transfert. Nous avons également collecté des informations sur les clubs, telles que leur nom, leur ligue, leur historique de transfert et leur budget. Enfin, nous avons recueilli des informations sur les transferts, telles que les montants des transferts, les dates de transfert et les clubs impliqués. Nous avons effectué des traitements de données spécifiques, tels que la gestion des données manquantes et des valeurs aberrantes, pour garantir la qualité des données utilisées dans notre analyse.

En résumé, les données utilisées pour ce projet ont été collectées à partir de plusieurs sources, le site Web Transfermarkt.com étant la source principale. Nous avons utilisé des techniques de grattage pour extraire les données et stocké les données extraites dans une base de données PostgreSQL. Les données collectées comprenaient des informations sur les joueurs, les clubs et les transferts. Nous avons également effectué des traitements de données spécifiques pour garantir la qualité des données utilisées dans notre analyse.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* numpy
  ```python
  import numpy as np
  ```
* pandas
  ```python
  import pandas as pd
  ```
* matplotlib
  ```python
  import matplotlib.pyplot as plt
  ```
* requests
  ```python
  import requests
  ```
* BeautifulSoup
  ```python
  from bs4 import BeautifulSoup
  ```
* webdriver
  ```python
  from selenium import webdriver
  ```
* Options
  ```python
  from selenium.webdriver.chrome.options import Options
  ```
* folium
  ```python
  import folium
  ```
* colormap
  ```python
  import branca.colormap as cm
  ```

### Architecture

La collecte et la gestion des données ont été au cœur de notre projet de data engineering sur le marché des transferts dans le football. Nous avons utilisé une architecture de données distribuée pour gérer le volume important de données collectées à partir de plusieurs sources, principalement le site Transfermarkt.com et dans une moindre mesure opdata.

L'architecture de notre projet est la suivante :

Collecte de données : Nous avons utilisé des scripts Python pour extraire les données des sites web Transfermarkt.com et opdata en utilisant la technique de scrapping. Les données ont été stockées dans des fichiers CSV puis enregistrées sur le cloud.

Stockage de données : Nous avons utilisé Google drive pour la persistance de données..

Traitement de données : Les données ont été nettoyées et traitées en utilisant Python et la bibliothèque Pandas. Les données ont été nettoyées pour éliminer les données manquantes, les valeurs aberrantes et les doublons. Les données ont été transformées pour être prêtes pour l'analyse.

Analyse de données : Nous avons utilisé la bibliothèque Pandas pour effectuer une analyse exploratoire des données. Nous avons utilisé des graphiques et des tableaux pour visualiser les données et comprendre les tendances du marché des transferts.

Stockage des résultats : Les résultats de l'analyse ont été stockés dans google Drive. Cela facilite la collaboration et garantit que tout le monde a accès aux mêmes données. De plus, le stockage des résultats dans Google Drive fournit une sauvegarde sécurisée en cas de perte de données ou de problèmes techniques.

Notre architecture de données distribuée nous a permis de gérer efficacement un volume important de données collectées à partir de plusieurs sources. Les données ont été stockées dans une base de données PostgreSQL, ce qui nous a permis d'effectuer des opérations de traitement de données et d'analyse de données en utilisant Python et la bibliothèque Pandas. Les résultats de l'analyse ont été stockés dans des tables séparées pour faciliter l'accès et l'analyse ultérieure.

En résumé, notre architecture de données distribuée a été conçue pour gérer efficacement les données collectées à partir de plusieurs sources, principalement le site Transfermarkt.com et dans une moindre mesure opdata. Nous avons utilisé Google Drive pour stocker les données, Python et la bibliothèque Pandas pour le traitement et l'analyse de données, et nous avons stocké les résultats de l'analyse dans des tables séparées pour faciliter l'accès et l'analyse ultérieure.



<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Conclusion

Notre projet de data engineering sur le marché des transferts dans le football nous a permis de collecter, stocker, traiter et analyser un volume important de données à partir de plusieurs sources, principalement le site Transfermarkt.com et dans une moindre mesure opdata. Grâce à notre architecture de données distribuée, nous avons pu gérer efficacement les données collectées et les analyser pour comprendre les tendances du marché des transferts.

L'analyse exploratoire des données que nous avons effectuée nous a permis de comprendre les tendances du marché des transferts dans le football depuis sa professionnalisation jusqu'à aujourd'hui. Nous avons pu identifier les équipes qui ont dépensé le plus d'argent pour les transferts de joueurs, les joueurs les plus chers, les ligues les plus actives sur le marché des transferts et les tendances des prix des transferts au fil du temps.

Nous avons également identifié des défis dans la collecte et la gestion des données, notamment la variabilité dans la qualité des données collectées et la nécessité de maintenir les données à jour pour obtenir des résultats précis.

Notre projet a également souligné l'importance de la collaboration interdisciplinaire pour mener à bien un projet de data engineering. Nous avons travaillé en étroite collaboration avec des experts en football pour comprendre les concepts clés et les tendances du marché des transferts dans le football, et avec des ingénieurs de données pour mettre en place une architecture de données distribuée efficace pour gérer les données collectées.

En conclusion, notre projet de data engineering sur le marché des transferts dans le football nous a permis de collecter, stocker, traiter et analyser un volume important de données pour comprendre les tendances du marché des transferts. Nous avons identifié les équipes qui ont dépensé le plus d'argent pour les transferts de joueurs, les joueurs les plus chers, les ligues les plus actives sur le marché des transferts et les tendances des prix des transferts au fil du temps. Nous avons également souligné l'importance de la collaboration interdisciplinaire pour mener à bien un projet de data engineering.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - email@email_client.com

Project Link: [https://github.com/guypi001/DE](https://github.com/guypi001/DE)

<p align="right">(<a href="#readme-top">back to top</a>)</p>




