<!-- Used for back to top link -->
<div id="top"></div>

<!-- Insert badges here. See https://shields.io/ -->
![GitHub](https://img.shields.io/github/v/tag/Fonze81/GIT-repository-template?style=flat&logo=github)
![GitHub](https://img.shields.io/github/release-date/Fonze81/GIT-repository-template?style=flat&logo=github)
![GitHub](https://img.shields.io/github/last-commit/Fonze81/GIT-repository-template?style=flat&logo=github)
![GitHub](https://img.shields.io/github/commit-activity/m/Fonze81/GIT-repository-template?style=flat&logo=github)
![GitHub](https://img.shields.io/github/repo-size/Fonze81/GIT-repository-template?style=flat&logo=github)
![GitHub](https://img.shields.io/github/license/Fonze81/GIT-repository-template?style=flat)

![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)

# GIT Repository Template

<details>
    <summary>Table of Contents</summary>
    <ol>
        <li><a href="#about-the-project"> 📝 About The Project</a></li>
        <li><a href="#project-status"> 🚧 Project Status</a></li>
        <li><a href="#technologies"> 🔰 Technologies</a></li>
        <li><a href="#prerequisites"> 💻 Prerequisites</a></li>
        <li><a href="#installation"> 🚀 Installation</a></li>
        <li><a href="#step-by-step"> 🚶 Step by step</a></li>
        <ul>
            <li><a href="#create-local-repository">Create a local repository</a></li>
            <li><a href="#create-remote-repository">Create a remote repository</a></li>
        </ul>
        <li><a href="#license"> 📝 License</a></li>
    </ol>
</details>

<!-- Used for Table of Contents link -->
<div id="about-the-project"></div>

## 📝 About The Project

Repository template to be used as a base for other projects

<!-- Link to top -->
<p align="right"><a href="#top">back to top</a></p>

<!-- Used for Table of Contents link -->
<div id="project-status"></div>

## 🚧 Project Status

**v0.1.0**  Initial release. [Full Changelog](https://github.com/Fonze81/GIT-repository-template/commits/0.1.0)

<!-- Link to top -->
<p align="right"><a href="#top">back to top</a></p>

<!-- Used for Table of Contents link -->
<div id="technologies"></div>

## 🔰 Technologies

The following tools were used in building the project.

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

<!-- Link to top -->
<p align="right"><a href="#top">back to top</a></p>

<!-- Used for Table of Contents link -->
<div id="prerequisites"></div>

## 💻 Prerequisites

Before starting, you will need to have the following tools installed on your machine:

![Git](https://img.shields.io/static/v1?label=Git&message=^v2.33.1.windows.1&color=blue&style=flat-square&logo=git)

![GitHub](https://img.shields.io/static/v1?label=GitHub%20Desktop&message=^v2.9.14%20(x64)&color=blue&style=flat-square&logo=github)

<!-- Link to top -->
<p align="right"><a href="#top">back to top</a></p>

<!-- Used for Table of Contents link -->
<div id="installation"></div>

## 🚀 Installation

Clone the Github remote repository by running the command

```bash
git clone https://github.com/Fonze81/GIT-repository-template
```

<!-- Link to top -->
<p align="right"><a href="#top">back to top</a></p>

<!-- Used for Table of Contents link -->
<div id="step-by-step"></div>

## 🚶 Step by step

<!-- Used for Table of Contents link -->
<div id="create-local-repository"></div>

### Create a local repository

<details>

Open a terminal window and run the command `git --version` to verify that it is installed.
If an error is returned, there are a few ways to install Git on Windows. The most official build is available for download on the Git website. Just go to https://git-scm.com/download/win and the download will start automatically.

> ![Git](./images/git-icon_14px.svg) [**Git**](https://git-scm.com/) is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

To update Git to the latest version run the command

```bash
git update-git-for-windows
```

Git comes with a tool called git config that lets you get and set configuration variables that control all aspects of how Git looks and operates. See [First-Time Git Setup](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)

```bash
git config --global user.name '<your-username>'
git config --global user.email <your-email>
```

Go to that project's directory. In the terminal window run the command:

```bash
cd C:/Users/user/my_project
```

Create a new subdirectory named .git that contains all of your necessary repository files \- a Git repository skeleton. Run the command:

```bash
git init
git status
```

Added the following files to the directory:

* **README.md** - A guide that gives a detailed description of the project.
* **./images** - A folder with the images that are used in the project
* **LICENSE** - A file with the project license

Start tracking these files and do an initial commit.

```bash
git add README.md
git add images/*
git add LICENSE
git commit -m 'Initial commit'
git branch -M main
```

<!-- Link to top -->
<p align="right"><a href="#top">back to top</a></p>

</details>

<!-- Used for Table of Contents link -->
<div id="create-remote-repository"></div>

### Create a remote repository

<details>

Go to [Github](https://github.com/) and create a new remote repository.
Download [GitHub Desktop](https://central.github.com/deployments/desktop/desktop/latest/win32) and install it

Open the Github Desktop software, log in, select your local repository (File > Add local repository...) and then upload it to the remote repository (Repository > Push).

> ⚠️ Cannot upload directly from Git due to token authentication requirement. See [token authentication requirements for git operations](https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/)

<!-- Link to top -->
<!-- <p align="right"><a href="#top">back to top</a></p> -->

</details>

<!-- Link to top -->
<p align="right"><a href="#top">back to top</a></p>

<!-- Used for Table of Contents link -->
<div id="license"></div>

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- Link to top -->
<p align="right"><a href="#top">back to top</a></p>
