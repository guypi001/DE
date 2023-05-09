

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/github_username/repo_name">
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



<!-- TABLE OF CONTENTS -->

  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>




<!-- ABOUT THE PROJECT -->
## About The Project

Le football est l'un des sports les plus populaires au monde, suivi par des millions de fans passionnés. Le marché des transferts dans le football est également un domaine passionnant qui attire beaucoup d'attention, car il implique des millions de dollars de transactions chaque année. En tant que tel, l'analyse de ces transferts peut fournir des informations précieuses sur les tendances et les comportements du marché, qui peuvent être utilisées pour prendre des décisions commerciales éclairées.

Dans ce projet, nous avons analysé les données des transferts dans le football depuis la professionnalisation du sport jusqu'à aujourd'hui. Nous avons utilisé des techniques de data engineering pour nettoyer, transformer et intégrer les données provenant de diverses sources pour faciliter l'analyse. Nous avons également utilisé des méthodes d'apprentissage automatique pour modéliser les tendances du marché et prédire les transferts futurs.

Le but de ce projet est de fournir une analyse complète et détaillée du marché des transferts dans le football, qui peut être utilisée pour informer les décisions commerciales et les stratégies de gestion des clubs. Nous avons également inclus des visualisations claires pour aider à comprendre les tendances et les relations entre les différentes variables.

Dans les sections suivantes, nous allons décrire les données que nous avons utilisées, l'architecture technique que nous avons mise en place, les résultats de notre analyse, les enseignements que nous avons tirés de notre étude et les implications pour l'industrie du football. Nous espérons que cette analyse sera utile pour tous ceux qui s'intéressent au marché des transferts dans le football et qui cherchent à en savoir plus sur les tendances et les comportements du marché.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![Next][Next.js]][Next-url]
* [![React][React.js]][React-url]
* [![Vue][Vue.js]][Vue-url]
* [![Angular][Angular.io]][Angular-url]
* [![Svelte][Svelte.dev]][Svelte-url]
* [![Laravel][Laravel.com]][Laravel-url]
* [![Bootstrap][Bootstrap.com]][Bootstrap-url]
* [![JQuery][JQuery.com]][JQuery-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Les données utilisées pour ce projet ont été recueillies auprès de diverses sources, la source principale étant le site Web Transfermarkt.com, qui est l'un des plus grands sites Web de données sur le football au monde. De plus, nous avons également utilisé les données d'opdata, quoique dans une moindre mesure. Le site Internet Transfermarkt.com contient une mine d'informations sur les joueurs, les clubs, les transferts, les contrats, les statistiques des matchs et de nombreuses autres données liées au football. Les données sont présentées sous forme de tableaux sur un grand nombre de pages Web. Certaines informations, telles que les valeurs de transfert, étaient situées dans des zones spécifiques de la page et nécessitaient une technique de grattage pour extraire les données.

Pour extraire les données, nous avons utilisé le langage de programmation Python, en utilisant le module BeautifulSoup pour extraire les données HTML et le module Selenium pour naviguer et extraire les données des pages Web dynamiques. Les données extraites ont été nettoyées, transformées et stockées dans des fichiers CSV. Nous avons effectué trois mises à jour des données au cours du projet, la mise à jour finale étant effectuée avant l'analyse finale.

Les données collectées incluent des informations sur les joueurs, telles que leur nom, leur âge, leur position, leur nationalité et leur historique de transfert. Nous avons également collecté des informations sur les clubs, telles que leur nom, leur ligue, leur historique de transfert et leur budget. Enfin, nous avons recueilli des informations sur les transferts, telles que les montants des transferts, les dates de transfert et les clubs impliqués. Nous avons effectué des traitements de données spécifiques, tels que la gestion des données manquantes et des valeurs aberrantes, pour garantir la qualité des données utilisées dans notre analyse.

En résumé, les données utilisées pour ce projet ont été collectées à partir de plusieurs sources, le site Web Transfermarkt.com étant la source principale. Nous avons utilisé des techniques de grattage pour extraire les données et stocké les données extraites dans une base de données PostgreSQL. Les données collectées comprenaient des informations sur les joueurs, les clubs et les transferts. Nous avons également effectué des traitements de données spécifiques pour garantir la qualité des données utilisées dans notre analyse.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/github_username/repo_name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3
    - [ ] Nested Feature

See the [open issues](https://github.com/github_username/repo_name/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - email@email_client.com

Project Link: [https://github.com/github_username/repo_name](https://github.com/github_username/repo_name)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#readme-top">back to top</a>)</p>


