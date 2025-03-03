# NAPCORE Reference Architectures website

This repository contains a website for publication of browsable UML models of National Body and National Access Point Reference Architectures developed within the [NAPCORE (National Access Point Coordination Organisation for Europe)](https://napcore.eu/) project according the the [FRAME (FRamework Architecture Made for Europe)](https://frame-online.eu/) methodology.

Reference architectures that are included in the website are developed in separate GitHub repositories https://github.com/NAPCORE/NAP-Reference-Architecture/ and https://github.com/NAPCORE/NB-Reference-Architecture/

## Working with website

Content of the website is stored in the [doc](https://github.com/NAPCORE/Reference-Architectures-website/tree/main/docs) folder, available online as [website](https://napcore.github.io/Reference-Architectures-website/)

### Local Installation

Using Python 3.12 and pdm:

$ pdm install

Before using the installed mkdocs command, make sure you activate it's virtualenv.

### Local development

Edit files in the docs folder. See https://www.mkdocs.org/user-guide/writing-your-docs/ and https://squidfunk.github.io/mkdocs-material/getting-started/

Run from project root:

$ mkdocs serve

Then open http://localhost:8000

This shall update as soon as you save any content file.

### Deploying on GitHub Pages

Just push the repository to GitHub. It shall build the page on it's own.
See: https://napcore.github.io/NAP-Reference-Architecture/

## Acknowledgement
This Architecture represents the architecture of National Access Point harmonized by [NAPCORE](https://napcore.eu/)

![NAPCORE](https://napcore.eu/wp-content/themes/napcore/images/napcore-logo.png)

![Co founded by EU](https://napcore.eu/wp-content/themes/napcore/images/eu.png)
