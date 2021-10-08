# devenv

[![MIT license](http://img.shields.io/badge/license-MIT-brightgreen.svg)](http://opensource.org/licenses/MIT) 

template for the VS Code with the Dev Container plugin installed

## Table of Contents

* [Settings](#settings)
* [Requirements](#requirements)
* [Installation](#installation)
* [Usage](#usage)
* [Author](#author)
* [License](#license)

## Settings
- default folder inside container for the work: **/workspace/APP**
- default working directory: **/workspace**
- based system: **debian** with typescript

## Requirements

- Git (Of course)
- VS Code
- Remote-Containers extension to VS Code
- Docker (Docker Desktop with Docker should be triggered to install by Remote-Containers extension)
- Having positive energy to work with containers

## Installation

- clone https://github.com/tgorka/docenv

OR

- click `template` button on the GitHub https://github.com/tgorka/docenv to create your GitHub repository based on devenv

AND

- replace in the `.devcontainer/Dockerfile` / `.devcontainer/docker-compose.yml` / `.devcontainer/devcontainer.json` word `APP` with your name of the project.

## Usage

- Once repository is created open VS Code 
- VS Code will ask for opening project inside the container
- If not: click on the Dev-Container button (bottom left corner) and use option Rebuild Container
- It's done! You should shuld have VS Code open in the container
- You can open terminal and go to the project folder starting your work

## Author
Tomasz Górka <http://tomasz.gorka.org.pl>

## License
&copy; 2021 Tomasz Górka

MIT licensed.

Have fun with using `devenv` ;).
