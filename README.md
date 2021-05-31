
<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">project_title</h3>

  <p align="center">
    project_description
    <br />
    <a href="https://github.com/github_username/repo_name"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/github_username/repo_name">View Demo</a>
    ·
    <a href="https://github.com/github_username/repo_name/issues">Report Bug</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#project-structure">Project Structure</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#migration">Migration</a></li>
        <li><a href="#testing">Testing</a></li>
        <li><a href="#lint">Lint</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

An architectural diagram is a diagram of a system that is used to abstract the overall outline of the software system and the relationships, constraints, and boundaries between components. It is an important tool as it provides an overall view of the physical deployment of the software system and its evolution roadmap

**A diagram of the proposed system architecture for the Content Persistence Project is presented**

![screenshot](https://upload.wikimedia.org/wikipedia/commons/f/f2/Content_persistence.system_architecture.diagram.svg)



### Project Structure

```
📦go-clean-arch
 ┣ 📂app
 ┃ ┗ 📜main.go
 ┣ 📂domain
 ┃ ┣ 📂mocks
 ┣ 📂article
 ┃ ┣ 📂delivery
 ┃ ┃ ┗ 📂http
 ┃ ┃ ┃ ┗ 📂middleware
 ┃ ┣ 📂repository
 ┃ ┗ 📂usecase
 ┣ 📂author
 ┃ ┗ 📂repository
 ┣ 📂user
 ┃ ┣ 📂delivery
 ┃ ┃ ┗ 📂http
 ┃ ┃ ┃ ┣ 📂middleware
 ┃ ┣ 📂repository
 ┃ ┗ 📂usecase
 ```


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them on MacOS using Homebrew.

* Homebrew
  ```sh
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)" brew doctor
  ```

* Git
  ```sh
  brew install git
  ```
* GO
  ```sh
  brew install go
  ```
* PostgreSQL
  ```sh
  brew install postgresql
  ```
* Make 
  ```sh
  brew install make
  ```
* Docker
  ```sh
  brew cask install docker
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/github_username/repo_name.git
   ```
2. Install NPM packages
   ```sh
   make all
   ```


### Migration

To migrate the Database
   ```sh
   db migrate
   ```

### Testing

To migrate the Database
   ```sh
   make test
   ```


### Lint

To check lint
   ```sh
   make lint
   ```

<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_



<!-- ROADMAP -->
## Roadmap

Roadmaps useful for planning large pieces of work several months in advance at the Epic level within a single project. Simple planning and dependency management features help teams visualize and manage work better together. 


See the [open issues](https://github.com/github_username/repo_name/issues) for a list of proposed features (and known issues).



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [Gin](https://gin-gonic.com)
* [Gorm](https://gorm.io)
* [Docker](https://www.docker.com)
* [PostgreSQL](https://www.postgresql.org)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/github_username
