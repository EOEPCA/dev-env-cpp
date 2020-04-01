<!--
***
*** To avoid retyping too much info. Do a search and replace for the following:
*** dev-env-cpp, twitter_handle, email
-->

<!-- PROJECT SHIELDS -->
<!--
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
![Build][build-shield]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/EOEPCA/dev-env-cpp">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">dev-env-cpp</h3>

  <p align="center">
    Tools and environment definitions for local EOEPCA service development activities for C++
    <br />
    <a href="https://github.com/EOEPCA/dev-env-cpp"><strong>Explore the docs »</strong></a>
    <br />
    <a href="https://github.com/EOEPCA/dev-env-cpp">View Demo</a>
    ·
    <a href="https://github.com/EOEPCA/dev-env-cpp/issues">Report Bug</a>
    ·
    <a href="https://github.com/EOEPCA/dev-env-cpp/issues">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Table of Contents](#table-of-contents)
- [About The Project](#about-the-project)
  - [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
- [License](#license)

<!-- ABOUT THE PROJECT -->

## About The Project

Tools and environment definitions for local EOEPCA service development activities for C++

### Built With

- [Vagrant](https://www.vagrantup.com/)


<!-- GETTING STARTED -->

## Getting Started

1. Download and install [VirtualBox](https://www.virtualbox.org/) 

2. Download and install the appropriate [Vagrant package for your OS](https://www.vagrantup.com/downloads.html).

3. Download EOEPCA development environment template for c++ 
    
    wget https://github.com/EOEPCA/dev-env-cpp/archive/develop.zip'

4. To build and instantiate the EOEPCA development environment run the following command:

    vagrant up --provision

5. To access the development environment via ssh

    vagrant ssh

6. To access the development environment with CentOs GUI open VirtualBox select the running the dev-env-cpp VM then click on the Show button.

### Prerequisites

Before you start, you should already have the following softwares installed:

- [Vagrant](https://www.vagrantup.com/docs/installation/)
- [VirtualBox](https://www.virtualbox.org/manual/ch02.html)


<!-- LICENSE -->

## License

Distributed under the Apache-2.0 License. See `LICENSE` for more information.

~~~~