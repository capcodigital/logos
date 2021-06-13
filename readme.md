[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/capcodigital/logos">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Presentation Logos</h3>

  <p align="center">
    Standardised logos of technologies and financial services organisations.
    <br />
    <br />
    <a href="https://github.com/capcodigital/logos/issues">Report Bug</a>
    ·
    <a href="https://github.com/capcodigital/logos/issues">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
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
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

This repo contains a set of standardised png files for easy use in presentations.  The logos cover both financial services companies and technologies.

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

### Python Virtual Environment

A Python virtual environment called _.venv-logos_ is required to use pre-commit and detect-secrets from git hooks.

This example shows the use of `pyenv` but other tools can be used to configure the virtual environment if preferred.

```shell
# create a python virtual env
pyenv virtualenv 3.9.1 .venv-engineering-framework
```

### Installation

```shell
# clone the repo
git clone https://github.com/capcodigital/logos.git

# installs the tooling requirements
pip install -r requirements.txt
pre-commit install
```

<!-- USAGE EXAMPLES -->
## Usage

### Logo Types

All files are _.png_ file format so that they have a transparent background and can be overlaid on other content.

### Square Logos

The square logos are suffixed as __square.png_.  The logos are sized as 200px x 200px.

### Full Logos

The full logos are suffixed as __full.png_.  The logos are sized at a height of 200px.

### Cloud

This project only contains the public cloud logos.  It is not intended to replace the cloud providers provided artefacts, links to these can be found below:

* [Google Cloud Platform](https://cloud.google.com/icons/)

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/capcodigital/logos/issues) for a list of proposed features (and known issues).

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

If you would like to contribute to any Capco Digital OSS projects please read:

* [Code of Conduct](https://github.com/capcodigital/.github/blob/master/CODE_OF_CONDUCT.md)
* [Contributing Guidelines](https://github.com/capcodigital/.github/blob/master/CONTRIBUTING.md)

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [Best README Template](https://github.com/othneildrew/Best-README-Template/blob/master/README.md)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/capcodigital/logos.svg?style=for-the-badge
[contributors-url]: https://github.com/capcodigital/logos/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/capcodigital/logos.svg?style=for-the-badge
[forks-url]: https://github.com/capcodigital/logos/network/members
[stars-shield]: https://img.shields.io/github/stars/capcodigital/logos.svg?style=for-the-badge
[stars-url]: https://github.com/capcodigital/logos/stargazers
[issues-shield]: https://img.shields.io/github/issues/capcodigital/logos.svg?style=for-the-badge
[issues-url]: https://github.com/capcodigital/logos/issues
[license-shield]: https://img.shields.io/github/license/capcodigital/logos.svg?style=for-the-badge
[license-url]: https://github.com/capcodigital/logos/blob/master/LICENSE
