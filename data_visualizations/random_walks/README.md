# Random Walks

[![MIT License][license-shield]][license-url]
[![Gmail][Gmail-shield]][Gmail-url]

A collection of projects focused on visualizing data using Matplotlib and Plotly. They explore the concept of random walks through simulations and visualizations. Each project demonstrates different aspects of random motion, from the behavior of pollen grains on water to the trails of fireflies.
Each project is housed within its own subdirectory. Feel free to explore the READMEs of these projects for detailed information. You will find code snippets and screenshots to help you understand the functionality of each project.

These projects were developed working through chapter 15 of Python Crash Course.

<!-- markdownlint-disable MD001 -->
### Table of Contents

[About this Project](#about-this-projects-collection) •
[Getting Started](#getting-started) •
[Contact](#contact) •
[License](#license)
<!-- markdownlint-enable MD001 -->

## About this Projects Collection

This collection includes projects that showcase various approaches to visualizing random movement using different Matplotlib and Plotly:

+ **[molecular_motion/][Molecular-Motion-url]**:
This project visualizes the random path of a pollen grain on water, using Matplotlib. It provides a representation of molecular motion through scatter plots that highlight the start and end points of each walk.

+ **[firefly_random_walk/][Firefly-Random-Walk-url]**:
This project uses Plotly to create an interactive visualization of the random movement patterns of fireflies.

### Built With

+ [![Python][Python-badge]][Python-url]
+ [![Visual Studio Code][VSCode-badge]][VSCode-url]
+ [![Plotly][Plotly-badge]][Plotly-url]
+ [![Matplotlib][Matplotlib-badge]][Matplotlib-url]
+ [![Mypy][Mypy-badge]][Mypy-url]
+ [![Black][Black-badge]][Black-url]
+ [![Pylint][Pylint-badge]][Pylint-url]
+ [![Flake8][Flake8-badge]][Flake8-url]
+ [![Ruff][Ruff-badge]][Ruff-url]
  
[back to top](#random-walks)

## Getting Started

Each project within this directory can be executed independently.
Follow the steps below to set up and run the projects locally.

> Note:
>
> If you wish to clone the entire repository, please refer to the "Getting Started" section of the README.md in the [first-solo-projects][First-Solo-Projects-url] repository.
>
> If you wish to clone the entire data visualizations subdirectory, please refer to the "Getting Started" section of the README.md in [data_visualizations][Data-Visualizations-url].

### Prerequisites

Ensure you have [Python][Python-download] and [Git][Git-download] installed on your computer.
Optionally, you may want to use a virtual environment to manage Python dependencies.

### Setup

From your command line:

#### Either Clone This Entire Directory

```bash
# Make a directory
$ mkdir <repo>
$ cd <repo>

# Initialize a new Git repository
$ git init

# Add the remote repository
$ git remote add origin https://github.com/E-Rinaudo/first-solo-projects.git

# Enable sparse checkout
$ git config core.sparseCheckout true

# Specify the subdirectory to include
$ echo "random_walks/" >> .git/info/sparse-checkout

# Pull the contents
$ git pull origin main
```

#### Or Clone Only a Specific Project Within this Directory

> Note:
>
> To see a list of available projects, refer to [About this Projects Collection](#about-this-projects-collection).

```bash
# Make a directory
$ mkdir <repo>
$ cd <repo>

# Initialize a new Git repository
$ git init

# Add the remote repository
$ git remote add origin https://github.com/E-Rinaudo/first-solo-projects.git

# Enable sparse checkout
$ git config core.sparseCheckout true

# Specify the project to include
$ echo "random_walks/project_name/" >> .git/info/sparse-checkout

# Pull the contents
$ git pull origin main
```

#### After Cloning

```bash
# Go to what you cloned
# Choose one of the following based on what you cloned

## If you cloned the entire directory
$ cd random_walks

## If you only cloned a project
$ cd project_name

# Create a virtual environment
$ python -m venv venv

# Activate the virtual environment

## On macOS/Linux
$ source venv/bin/activate

## On Windows with CMD
$ .\venv\Scripts\activate.bat

## On Windows With Power shell.
.\venv\Scripts\activate.ps1

## On Windows With Unix Like Shells (e.g. Git Bash CLI).
source venv/Scripts/activate

# Install dependencies
$ pip install -r requirements.txt
```

#### Finally

```bash
# Run the projects
# Choose one of the following based on what you cloned

## If you cloned the entire directory
$ cd project_name
$ python project_name.py

## If you cloned only a project
$ python project_name.py
```

[back to top](#random-walks)

## Contact

If you have any questions, feedback, or just want to get in touch, feel free to reach out to me via email at <enricorinaudo91@gmail.com>.
Your feedback is appreciated as it helps me to continue improving.

You can also explore my GitHub profile or the project repository for more information:

+ Profile Link: [https://github.com/E-Rinaudo](https://github.com/E-Rinaudo)
+ Project Link: [https://github.com/E-Rinaudo/first-solo-projects](https://github.com/E-Rinaudo/first-solo-projects/tree/main)

[back to top](#random-walks)

## License

These projects are distributed under the MIT License. See [`LICENSE.txt`][license-url] for more information.

[back to top](#random-walks)

---

**Happy coding!**

<!-- SHIELDS -->
[license-shield]: https://img.shields.io/github/license/E-Rinaudo/first-solo-projects.svg?style=flat
[license-url]: https://github.com/E-Rinaudo/first-solo-projects/blob/main/LICENSE.txt
[Gmail-shield]: https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white
[Gmail-url]: mailto:enricorinaudo91@gmail.com

<!-- BADGES -->
[Python-badge]: https://img.shields.io/badge/python-3670A0?logo=python&logoColor=ffdd54&style=flat
[Python-url]: https://docs.python.org/3/
[VSCode-badge]: https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?logo=visualstudiocode&logoColor=fff&style=flat
[VSCode-url]: https://code.visualstudio.com/docs
[Plotly-badge]: https://img.shields.io/badge/Plotly-3F4F75?logo=plotly&logoColor=white&style=flat
[Plotly-url]: https://plotly.com/python/
[Matplotlib-badge]: https://img.shields.io/badge/Matplotlib-3776AB?
[Matplotlib-url]: https://matplotlib.org/stable/users/index.html
[Mypy-badge]: https://img.shields.io/badge/mypy-checked-blue?style=flat
[Mypy-url]: https://mypy.readthedocs.io/
[Black-badge]: https://img.shields.io/badge/code%20style-black-000000.svg
[Black-url]: https://black.readthedocs.io/en/stable/
[Pylint-badge]: https://img.shields.io/badge/linting-pylint-yellowgreen?style=flat
[Pylint-url]: https://pylint.readthedocs.io/
[Ruff-badge]: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json
[Ruff-url]: https://docs.astral.sh/ruff/tutorial/
[Flake8-badge]: https://img.shields.io/badge/linting-flake8-blue?style=flat
[Flake8-url]: https://flake8.pycqa.org/en/latest/

<!-- PROJECTS LINKS -->
[Molecular-Motion-url]: https://github.com/E-Rinaudo/first-solo-projects/tree/main/data_visualizations/random_walks/molecular_motion
[Firefly-Random-Walk-url]: https://github.com/E-Rinaudo/first-solo-projects/tree/main/data_visualizations/random_walks/firefly_random_walk
[Data-Visualizations-url]: https://github.com/E-Rinaudo/first-solo-projects/tree/main/data_visualizations

<!-- MAIN README -->
[First-Solo-Projects-url]: https://github.com/E-Rinaudo/first-solo-projects/blob/main/README.md

<!-- PREREQUISITES LINKS -->
[Python-download]: https://www.python.org/downloads/
[Git-download]: https://git-scm.com
