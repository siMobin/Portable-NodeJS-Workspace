<h5 align="center">Template Repository</h5>
<h1 align="center">A Portable Node.js workspace</h1>

## Introduction

This repository serves as a template for quickly setting up a portable Node.js development environment. Whether you're starting a new project or need a clean, consistent development environment across multiple machines, this template will help you get up and running in no time.

### Features

- Pre-configured Node.js environment
- Portable setup for use on **windows** machines
- Easy-to-follow setup instructions
- Other workspace settings:
  - PHP server
  - PHP
  - prettier
  - cSpell checker
  - liveserver
  - live sass compiler

[![Version](https://img.shields.io/badge/NODE%20Version-20.6.1-blue.svg)](https://your-project-url)
[![Version](https://img.shields.io/badge/npm%20Version-10.2.0-blue.svg)](https://your-project-url)

**ON** _[15/10/2023](https://github.com/siMobin/Portable-NodeJS-Workspace)_...

## Getting Started

Follow these steps to set up your portable Node.js development environment using this template repository:

### Prerequisites

- **Git:** Install `Git` on your system if it's not already installed. You can download Git from _[git-scm.com](https://git-scm.com/)_.

- **Visual Studio Code:** Install `Visual Studio Code` on your system if it's not already installed. You can download it from _[code.visualstudio.com](https://code.visualstudio.com/download)_.

> [!IMPORTANT]  
> This portable workspace works on **vs code** only.

### Cloning the Repository

Clone this repository to your local machine:

```shell
git clone git@github.com:siMobin/Portable-NodeJS-Workspace.git

git lfs install

git lfs pull
```

> [!WARNING]
> You may need a `ssh` key for that. You can try `HTTPS` then.

> [!IMPORTANT]  
> Delete `.git` folder before create a new repository using **_[this](https://github.com/siMobin/Portable-NodeJS-Workspace)_** template.

<h3 align="center">OR</h3>

<h4>Use <img src="https://img.shields.io/badge/Use this template-2ea043?logo=drop-down&logoColor=white&style=for-the-badge" height="25"/> to create an instant repository.</h4>

##

---

### Setting Up Your Project

check portable environment variable for **Node js** in `.vscode\settings.json`

```json
  "terminal.integrated.env.windows": {
    "PATH": "${env:PATH};${workspaceFolder}\\node"
  },
```

1. Change the working directory to your project folder:

2. Install project dependencies:

```shell
npm init
npm install `xxx` -save-dev
```

<!--
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
``` -->

> [!IMPORTANT]  
> Before start your project check/setup `.gitignore` file.

##

### **Extra**

**update node**

```shell
nvm install x.x.x
```

**update npm**

```shell
npm update -g
```

_OR_

```shell
npm install npm@latest -g
```

**Clear npm cache**

```shell
npm cache clean --force
```
