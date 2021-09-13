# Mastering git : Zero to Hero

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->

<br />
<p align="center">
  <a href="https://github.com/KamrulSh/git-cookbook">
    <img src="images/git.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Git Cookbook</h3>

  <p align="center">
    Learning git from absolute beginning.
    <br />
    <a href="https://github.com/KamrulSh/git-cookbook"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/KamrulSh/git-cookbook/issues">Report Bug</a>
    ·
    <a href="https://github.com/KamrulSh/git-cookbook/pulls">Pull Requests</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->

<details open="open">
  <summary><h2>Table of Contents</h2></summary>
  <ol>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

<!-- INSTALLATION -->

## Installation

### Install Git on Ubuntu

* Install Git using apt-get:

  ```sh
  sudo apt-get update
  ```
  ```sh
  sudo apt-get install git
  ```
* Check git version: 
  ```sh
  git --version
  ```
  
### Configure your Git username and email: (Ubuntu/Windows/Mac)

* Show current configuration:

  ```sh
  git config --list
  ```
* Show repository configuration:
  ```sh
  git config --local --list
  ```
* Show global configuration:
  ```sh
  git config --global --list
  ```
* Show system configuration:
  ```sh
  git config --system --list
  ```
* Set a name that is identifiable for credit when review version history:
  ```sh
  git config --global user.name "firstname lastname"
  ```
* Set an email address that will be associated with each history marker:
  ```sh
  git config --global user.email "example@example.com"
  ```
* Set automatic command line coloring for Git for easy reviewing:
  ```sh
  git config --global color.ui auto
  ```
* Set global editor (Visual Studio Code) for commit
  ```sh
  git config --global core.editor "code --wait"
  ```

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AwesomeFeature`)
3. Commit your Changes (`git commit -m 'Add some AwesomeFeature'`)
4. Push to the Branch (`git push origin feature/AwesomeFeature`)
5. Open a Pull Request

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- MARKDOWN LINKS & IMAGES -->

[contributors-shield]: https://img.shields.io/github/contributors/kamrulSh/repo.svg?style=for-the-badge
[contributors-url]: https://github.com/KamrulSh/git-cookbook/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo.svg?style=for-the-badge
[forks-url]: https://github.com/KamrulSh/git-cookbook/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo.svg?style=for-the-badge
[stars-url]: https://github.com/KamrulSh/git-cookbook/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo.svg?style=for-the-badge
[issues-url]: https://github.com/KamrulSh/git-cookbook/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo.svg?style=for-the-badge
[license-url]: https://github.com/KamrulSh/git-cookbook/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/mdkamrulshahin
