<p align="center">
  <a href="https://github.com/venkateshtantravahi/stat_exercises">
    <img src="https://static.vecteezy.com/system/resources/previews/000/143/608/non_2x/linear-icons-with-charts-and-statistics-vector.jpg" alt="Statistics Logo" />
  </a>
</p>

<div align="center">
  <h1 align="center">Statistical Exercises for Data Nerds</h1>
  <a>
    <img src="https://img.shields.io/github/languages/count/venkateshtantravahi/stat_exercises" />
  </a>
  <a href="https://github.com/venkateshtantravahi/stat_exercises/blob/main/LICENSE">
    <img alt="GitHub License" src="https://img.shields.io/github/license/venkateshtantravahi/stat_exercises">
  </a>
  <a>
    <img src="https://img.shields.io/github/repo-size/venkateshtantravahi/stat_exercises">
  </a>
  <br>
  <a href="https://github.com/venkateshtantravahi/stat_exercises/blob/main/CONTRIBUTING.md">
    <img src="https://img.shields.io/static/v1.svg?label=Contributions&message=Welcome&color=0059b3&style=flat-square" height="20" alt="Contributions Welcome">
  </a>
  <a>
    <img src="https://img.shields.io/github/forks/venkateshtantravahi/stat_exercises?style=social">
  </a>
  <a>
    <img src="https://img.shields.io/github/stars/venkateshtantravahi/stat_exercises?style=social">
  </a>
</div>

---

## 📖 Overview

Welcome to the **Statistical Exercises for Data Nerds** repository!
This project is designed to help learners and aspiring data scientists master **statistical concepts** that are crucial for data analysis and machine learning.

In this repository, you'll find:
- Well-structured **Jupyter Notebooks** covering essential statistical topics.
- Real-world **datasets** for hands-on practice.
- Exercises designed to build **statistical intuition**.
- Links to additional resources for further learning.

Whether you're preparing for a data science interview or just looking to improve your skills, this repository is for you!

---

## 🚀 To Get Started

### Clone or Download the Repository
You can get started by cloning the repository or downloading the zip file:

- **Clone the Repository**:
  ```bash
  git clone https://github.com/venkateshtantravahi/stat_exercises.git
  cd stat_exercises

- Download Zip File:
<a href="https://github.com/venkateshtantravahi/stat_exercises/archive/refs/heads/main.zip" target="_blank">Python.zip</a>

## ⚙️ Setup
- For windows gui's guided installation file will be available on following websites as python can be installed directly as a package or you can install with anaconda distribution

```
Python: https://www.python.org/downloads/
Anaconda: https://docs.anaconda.com/anaconda/install/windows/
```

- For Ubuntu distributions you need to install packages from the terminal as no guided gui will be available there

```
Python: sudo apt install python
Anaconda : https://docs.anaconda.com/anaconda/install/linux/
```

### Creating Environments
Once the installations is done you can create separate envs to work standalone with this repo, which means that's like a private space where you install packages specific
to this repo which doesn't effect the global packages, you can create env's in wo different ways
- Creating env using pipenv
  ```
  pip--install: pip install virtualenv
  create env : virtualenv <name>
  ```
- Activation and deactivation
 ```
 acivation(Wndows) : mypthon\Scripts\activate
 activation(Ubuntu) : Source mypython/bin/activate
 deactivation : deactivate
 ```
- Creating using conda
```
creation : conda create -n <env_name> <python_version>
activation : conda activate <env_name>
deactivation : conda deactivate
```

### Running scripts
- For windows open the shell at desired folder
   - for python file
      ```C:\devspace> jupyter-notebook```

- For Ubuntu open the terminal
  - for python file \
    ```xyz-PC:-$ jupyter-notebook```

 ### Packages Installation
 - For some modules to work with in the repo there might be usage of external modules which may lead to error when you directly run these files prior installation
 - to install these modules you can directly refer to pip[python package installer] or conda repo based on the installer on your machine
- If python is installed as standalone package in ubuntu or windows installer then pip should already be part of it, if not first install pip using following command:

``` python get-pip.py```
- or upgrade the current version using

``` python -m pip install --upgrade pip```
- If you have installed anaconda you would already been configured with conda base env so you can refer the below repo's as requirement

<a href="https://pypi.org/project/pip/" target="_blank">Pip Repo</a>
<a href="https://anaconda.org/anaconda/conda" target = "_blank">Conda Repo</a>

The only thing you have to do is go to that repo and search for package you wana install and it will give you the reuired information about it.

Once you have *pip* and *conda* please hit the following command to get all packages that are used in this repo:
```
pip install requirements.txt
```

## 🗂️ Repository Structure
    stat_exercises/
    ├── notebooks/                    # Folder containing topic-specific Jupyter Notebooks
    │   ├── descriptive_statistics.ipynb   # Exercises on descriptive statistics
    │   ├── visualization.ipynb             # Exercises on data visualization and EDA
    │   ├── hypothesis_testing.ipynb        # Exercises on hypothesis testing
    │   ├── probability_distributions.ipynb  # Exercises on probability distributions
    │   └── ...                       # Additional topics
    ├── solutions/                    # Folder containing topic-specific Jupyter Notebooks
    │   ├── descriptive_statistics.ipynb   # Exercise solution on descriptive statistics
    │   ├── visualization.ipynb             # Exercises solution on data visualization and EDA
    │   ├── hypothesis_testing.ipynb        # Exercises solution on hypothesis testing
    │   ├── probability_distributions.ipynb  # Exercises solution on probability distributions
    │   └── ... 
    ├── datasets/                     # Public datasets used in notebooks
    │   ├── dataset1.csv
    │   ├── dataset2.csv
    │   └── ...
    ├── intro.ipynb                   # Overview notebook with links to all other topics
    ├── requirements.txt              # Python dependencies
    ├── CONTRIBUTING.md               # Contribution guidelines
    ├── LICENSE                       # License for the project
    └── README.md                     # You're here!

## 📚 Topics Covered

| **Topic**                | **Description**                                                                                   |
|--------------------------|---------------------------------------------------------------------------------------------------|
| **Descriptive Statistics** | Learn about mean, median, mode, variance, standard deviation, percentiles, and skewness.         |
| **Visualization and EDA**   | Explore data with histograms, boxplots, scatterplots, heatmaps, and pairplots.                   |
| **Hypothesis Testing**      | Master t-tests, ANOVA, chi-square tests, and more.                                               |
| **Probability Distributions** | Understand discrete and continuous distributions like binomial, Poisson, and normal.             |
| **Regression Analysis**      | Delve into linear regression, logistic regression, and regularization techniques.                |
| **Time Series Analysis**     | Work with stationarity, ARIMA models, and seasonality.                                           |
| **Bayesian Statistics**      | Get introduced to Bayesian inference and prior/posterior distributions.                         |

----


### Contributions
---
Contributors please refer <a href="https://github.com/venkateshtantravahi/stat_exercises/blob/main/contribution_guidelines.md">Contribution guidelines</a> before making a PR.

### Liked Content

Please hit a star 🌟 and follow me on github for more like this.
