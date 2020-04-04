[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![License: CC BY-NC-SA 4.0][license-shield]][license-url]

<br />
<p align="center">
  <h3 align="center">COVID-19 Database</h3>

  <p align="center">
    Collection of automatically prepared COVID-19 datasets.
    <br />
    <a href="https://coronavirus-bulgaria.org/"><strong>Live Demo</strong></a>
    <br />
    <br />
    <a href="https://github.com/COVID-19-Bulgaria/covid-database/issues">Report Bug</a>
    ·
    <a href="https://github.com/COVID-19-Bulgaria/covid-database/issues">Request Feature</a>
  </p>
</p>

## Table of Contents

* [About the Project](#about-the-project)
* [Getting Started](#getting-started)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)

## About The Project

This project is a collection of automatically prepared COVID-19 datasets. Currently there are datasets only for Bulgaria, but soon datasets for other countries will be added as well.

## Getting Started

To get a local copy follow these simple example steps.

### Installation

1. Clone the repo
```sh
git clone https://github.com/COVID-19-Bulgaria/covid-database.git
```
2. Use the data as you wish

## Usage

For each country the following datasets might be available:
* `TotalsDataset.json` - includes the latest known information about the infected, cured, fatal totals in the specified country
* `DateCasesDataset.json` - includes historical data about how the infected, cured, fatal cases were changing for each date since the beginning of the disease in the specified country
* `DateDiffCasesDataset.json` - includes historical data about the delta infected, cured, fatal cases for each date since the beginning of the disease in the specified country
* `GeoDataset.json` - includes infected, cured, fatal totals and coordinates per geographic location for the specified country

## Roadmap

See the [open issues](https://github.com/COVID-19-Bulgaria/covid-database/issues) for a list of proposed features (and known issues).

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

[![Creative Commons License](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)
Project is distributed under [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

## Contact

Veselin Stoyanov:
[![LinkedIn][linkedin-shield]][linkedin-url]

[contributors-shield]: https://img.shields.io/github/contributors/COVID-19-Bulgaria/covid-database.svg?style=flat-square
[contributors-url]: https://github.com/COVID-19-Bulgaria/covid-database/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/COVID-19-Bulgaria/covid-database.svg?style=flat-square
[forks-url]: https://github.com/COVID-19-Bulgaria/covid-database/network/members
[stars-shield]: https://img.shields.io/github/stars/COVID-19-Bulgaria/covid-database.svg?style=flat-square
[stars-url]: https://github.com/COVID-19-Bulgaria/covid-database/stargazers
[issues-shield]: https://img.shields.io/github/issues/COVID-19-Bulgaria/covid-database.svg?style=flat-square
[issues-url]: https://github.com/COVID-19-Bulgaria/covid-database/issues
[license-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg?style=flat-square
[license-url]: https://creativecommons.org/licenses/by-nc-sa/4.0/
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?logo=linkedin&color=blue
[linkedin-url]: https://www.linkedin.com/in/stoyanovv/
