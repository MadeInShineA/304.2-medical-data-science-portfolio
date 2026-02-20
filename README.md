# 304.2-medical-data-science

[![Website olivier.amacker.dev/304.2-medical-data-science-portfolio/](https://img.shields.io/website-up-down-green-red/http/olivier.amacker.dev/304.2-medical-data-science-portfolio/src/index.html.svg)](https://olivier.amacker.dev/304.2-medical-data-science-portfolio/)

This repo contains the content of my portfolio done in the 304.2 - Semester project course

## Website

This project website is available [here](https://olivier.amacker.dev/304.2-medical-data-science/index.html) or locally at `_site/index.html`

The website contains the following sections:
 - TODO

## Local Setup

To build the project website locally, choose one of the following workflows:

### Option 1: Standard Setup

1. Install [Quarto](https://quarto.org/docs/get-started/)

2. Clone the repository
    ```bash
    git clone https://github.com/MadeInShineA/304.2-medical-data-science
    cd 304.2-medical-data-science
    ``` 
3. Render the site
    ```bash
    quarto render
    ``` 

### Option 2: Nix Setup

1. Ensure [Nix](https://nixos.org/download/) is installed

2. Clone the repository
    ```bash
    git clone https://github.com/MadeInShineA/304.2-medical-data-science
    cd 304.2-medical-data-science
    ``` 
3. Enter the development shell
    This provides Quarto and all project dependencies in an isolated environment:
    ```bash
    nix develop
    ``` 

4. Render the site
    ```bash
    quarto render
    ``` 

The site will be in the `_site/` directory.
