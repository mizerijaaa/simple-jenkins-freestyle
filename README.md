# Jenkins and Docker Setup

This repository contains the setup instructions and configuration files for Jenkins and Docker integration. It demonstrates how to set up Jenkins using Docker, integrate it with GitHub for CI/CD, and push Docker images to DockerHub.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Setup](#setup)
  - [Step 1: Clone the Repository](#step-1-clone-the-repository)
  - [Step 2: Set up Jenkins with Docker](#step-2-set-up-jenkins-with-docker)
  - [Step 3: Install Required Plugins in Jenkins](#step-3-install-required-plugins-in-jenkins)
  - [Step 4: Set up GitHub and DockerHub Credentials in Jenkins](#step-4-set-up-github-and-dockerhub-credentials-in-jenkins)
- [Jenkins Setup](#jenkins-setup)
  - [Step 1: Unlock Jenkins](#step-1-unlock-jenkins)
  - [Step 2: Install Plugins](#step-2-install-plugins)
  - [Step 3: Add Credentials](#step-3-add-credentials)
- [GitHub Integration](#github-integration)
- [DockerHub Integration](#dockerhub-integration)
- [Usage](#usage)
- [Running the Project](#running-the-project)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before you begin, make sure you have the following installed:

- **Docker**: To run Jenkins in a container.
- **Docker Compose**: To manage multiple containers.
- **GitHub Account**: To connect Jenkins with GitHub.
- **DockerHub Account**: To push and pull Docker images.

## Setup

### Step 1: Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/mizerijaaa/simple-jenkins-freestyle.git
cd your-repository
