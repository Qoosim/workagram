<!--
*** Thanks for checking out this README Template. If you have a suggestion that would
*** make this better, please fork the repo and create a pull request or simply open
*** an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
![Hireable](https://cdn.rawgit.com/hiendv/hireable/master/styles/default/yes.svg)

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/euqueme/workagram">
    <img src="https://raw.githubusercontent.com/euqueme/toy-app/master/app/assets/images/mLogo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Workagram RoR Capstone project</h3>

  <p align="center">
    This project is part of the Microverse Ruby on Rails curriculum!
    <br />
    <a href="https://github.com/euqueme/workagram"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/euqueme/workagram/issues">Report Bug</a>
    ·
    <a href="https://github.com/euqueme/workagram/issues">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Live Demo](#live-demo)
  * [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Setup](#setup)
  * [Usage](#usage)
  * [Run Test](#run-test)
  * [Deployment](#deployment)
  * [Built With](#built-with)
* [Authors](#authors)
* [Contributing](#contributing)
* [Show your support](#show-support)
* [Acknowledgements](#acknowledgements)
* [License](#license)

<!-- ABOUT THE PROJECT -->
## About The Project

[![asciicast][product-screenshot]](https://www.loom.com/share/b8568a718f344026ab156c3cd6fe24c2)

This project is based on Twitter, and has been given an individual theme created from work environment-related photos.

This is the Capstone project of the Microverse Ruby on Rails Curriculum

### Live Demo

Watch the walkthrough video first

https://www.loom.com/share/b8568a718f344026ab156c3cd6fe24c2

Now go to the [Live Demo](https://maru-workagram.herokuapp.com/)

### Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

Ruby: 2.7.0
Rails: 5.2.4

### Setup

Install gems with:

```
bundle install
```

Setup database with:

```
rails db:migrate
```

### Usage

Start server with:

```
rails server
```

Open `http://localhost:3000/` in your browser.

#### Create User

Fill the sign up form to create a user. The pictures are optional.

![screenshot](app/assets/images/workagram_sign_up.png)

#### Login

Use only the username to login

![screenshot](app/assets/images/workagram_log_in.png)

#### Post a work related pic

You must choose a file but the text is optional

![screenshot](app/assets/images/workagram_post.png)

#### Follow another user

Click on the blue follow button of any user to follow them

![screenshot](app/assets/images/workagram_follow.png)

#### Edit profile picture

Choose file and click on the Update photo button

![screenshot](app/assets/images/workagram_photo.png)

#### Edit cover image 

Choose file and click on the update coverimage button

![screenshot](app/assets/images/workagram_cover.png)

### Run tests

```
rpsec --format documentation
```

### Deployment

The project was deployed in [Heroku](https://maru-workagram.herokuapp.com/) 

### Built With
This project was built using these technologies.
* Ruby 2.6.3
* Rails 6.0.2.1
* Rspec
* Capybara
* Rubocop
* Ubuntu 18.4+
* Stickler
* VsCode

<!-- CONTACT -->
## Authors

María Eugenia Quemé - [@MaruKK](https://twitter.com/MaruKK) - [@euqueme](https://github.com/euqueme) - euqueme@gmail.com

Project [Link](https://github.com/euqueme/workagram/)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](issues/).

## Show your support

Give a ⭐️ if you like this project!

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Microverse](https://www.microverse.org/)
* [Heroku](https://www.heroku.com/)
* [The Best readme Template](https://github.com/othneildrew/Best-README-Template)
* [Gregoire Vella on Behance](https://www.behance.net/gregoirevella)


<!-- LICENSE -->
## 📝 License

This project is [MIT](https://opensource.org/licenses/MIT) licensed.

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/euqueme/workagram.svg?style=flat-square
[contributors-url]: https://github.com/euqueme/workagram/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/euqueme/workagram.svg?style=flat-square
[forks-url]: https://github.com/euqueme/workagram/network/members
[stars-shield]: https://img.shields.io/github/stars/euqueme/workagram.svg?style=flat-square
[stars-url]: https://github.com/euqueme/workagram/stargazers
[issues-shield]: https://img.shields.io/github/issues/euqueme/workagram.svg?style=flat-square
[issues-url]: https://github.com/euqueme/workagram/issues
[product-screenshot]: /app/assets/images/screenshot.png


