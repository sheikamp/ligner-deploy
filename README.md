
<h3 align="center">Ligner: Deployment</h3>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This repository will contain everything related to deployment, like Helm charts, setup scripts etc.
For now, the application can only be run with docker compose.


### Built With

* Docker

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

The following tools are required for building the application:
* docker: Please check the [official installation instructions](https://docs.docker.com/get-docker/).
* docker-compose: Please check the [official installation instructions](https://docs.docker.com/compose/install/).


### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/sheikamp/ligner-deploy
   ```
2. Run docker compose
   ```sh
   docker-compose up
   ```


<!-- USAGE EXAMPLES -->
## Usage

All required dependencies like databases are started along with the Ligner components.
Once the startup is complete, the application can be accessed via http://localhost:3000.
