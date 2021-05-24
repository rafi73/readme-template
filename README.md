
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
    ·
    <a href="https://github.com/github_username/repo_name/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
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
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

![screenshot](https://user-images.githubusercontent.com/9848528/119367873-5e484e00-bced-11eb-87a1-7d4e0d56f19b.png)



Here's a blank template to get started:
**To avoid retyping too much info. Do a search and replace with your text editor for the following:**
`github_username`, `repo_name`, `twitter_handle`, `email`, `project_title`, `project_description`


### Built With

* []()
* []()
* []()


### Project Structure

```
📦go-clean-arch
 ┣ 📂app
 ┃ ┗ 📜main.go
 ┣ 📂article
 ┃ ┣ 📂delivery
 ┃ ┃ ┗ 📂http
 ┃ ┃ ┃ ┣ 📂middleware
 ┃ ┃ ┃ ┃ ┣ 📜middleware.go
 ┃ ┃ ┃ ┃ ┗ 📜middleware_test.go
 ┃ ┃ ┃ ┣ 📜article_handler.go
 ┃ ┃ ┃ ┗ 📜article_test.go
 ┃ ┣ 📂repository
 ┃ ┃ ┣ 📂mysql
 ┃ ┃ ┃ ┣ 📜mysqlarticle_test.go
 ┃ ┃ ┃ ┗ 📜mysql_article.go
 ┃ ┃ ┗ 📜helper.go
 ┃ ┗ 📂usecase
 ┃ ┃ ┣ 📜article_ucase.go
 ┃ ┃ ┗ 📜article_ucase_test.go
 ┣ 📂author
 ┃ ┗ 📂repository
 ┃ ┃ ┗ 📂mysql
 ┃ ┃ ┃ ┣ 📜mysql_repository.go
 ┃ ┃ ┃ ┗ 📜mysql_test.go
 ┣ 📂domain
 ┃ ┣ 📂mocks
 ┃ ┃ ┣ 📜ArticleRepository.go
 ┃ ┃ ┣ 📜ArticleUsecase.go
 ┃ ┃ ┗ 📜AuthorRepository.go
 ┃ ┣ 📜article.go
 ┃ ┣ 📜author.go
 ┃ ┗ 📜errors.go
 ┣ 📂user
 ┃ ┣ 📂delivery
 ┃ ┃ ┗ 📂http
 ┃ ┃ ┃ ┣ 📂middleware
 ┃ ┃ ┃ ┃ ┣ 📜middleware.go
 ┃ ┃ ┃ ┃ ┗ 📜middleware_test.go
 ┃ ┃ ┃ ┣ 📜article_test.go
 ┃ ┃ ┃ ┗ 📜user_handler.go
 ┃ ┣ 📂repository
 ┃ ┃ ┣ 📂mysql
 ┃ ┃ ┃ ┣ 📜mysqlarticle_test.go
 ┃ ┃ ┃ ┗ 📜mysql_article.go
 ┃ ┃ ┗ 📜helper.go
 ┃ ┗ 📂usecase
 ┃ ┃ ┣ 📜article_ucase.go
 ┃ ┃ ┗ 📜article_ucase_test.go
 ┣ 📜article.sql
 ┣ 📜clean-arch.png
 ┣ 📜config.json
 ┣ 📜docker-compose.yaml
 ┣ 📜Dockerfile
 ┣ 📜go.mod
 ┣ 📜go.sum
 ┣ 📜LICENSE
 ┣ 📜Makefile
 ┗ 📜README.md
 ```


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/github_username/repo_name.git
   ```
2. Install NPM packages
   ```sh
   npm install
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

See the [open issues](https://github.com/github_username/repo_name/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* []()
* []()
* []()





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
