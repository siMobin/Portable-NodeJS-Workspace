# Creating a Portable Node.js Template Repository

## Introduction

This repository serves as a template for quickly setting up a portable Node.js development environment. Whether you're starting a new project or need a clean, consistent development environment across multiple machines, this template will help you get up and running in no time.

### Features

- Pre-configured Node.js environment
- Portable setup for use on **windows** machines
- Easy-to-follow setup instructions

## Getting Started

Follow these steps to set up your portable Node.js development environment using this template repository:

### Prerequisites

- **Git:** Install Git on your system if it's not already installed. You can download Git from [git-scm.com](https://git-scm.com/).

### Cloning the Repository

Clone this repository to your local machine:

```shell
git clone git@github.com:siMobin/Portable-NodeJS-Workspace.git
```

> [!WARNING]
> You may need a `ssh` key for that. You can try `HTTPS` then.

> [!IMPORTANT]  
> Delete `.git` folder before create a new repository using **this** template.

<h1 align="center">OR</h1>

<h4>Use <img src="https://img.shields.io/badge/Use this template-2ea043?logo=drop-down&logoColor=white&style=for-the-badge" height="25"/> to create an instant repository.</h4>

##

##

##

### Setting Up Your Project

1. Change the working directory to your project folder:

2. Install project dependencies:

```shell
npm init
npm install `xxx` -save-dev
```

### Usage

Now you're all set to start your Node.js project within this portable environment. Use the following npm scripts to get started:

- **Start the development server:**

```shell
npm start
```

- **Multi-Dev:**

```shell
npm install npm-run-all
```

_settings:_

```json
{
  "dependencies": {
    "npm-run-all": "^4.1.5"
  },
  "name": "name",
  "version": "0.0.1-beta",
  "description": "",
  "main": "index.php",
  "scripts": {
    "start-admin": "php -S localhost:8000 -t x/",
    "start-user": "php -S localhost:8001 -t y/",
    "start-driver": "php -S localhost:8002 -t z/",
    "start": "npm-run-all --parallel start-x start-y start-z"
  },
  "author": "",
  "license": ""
}
```

> [!IMPORTANT]  
> After start your project check/setup `.gitignore` file.
