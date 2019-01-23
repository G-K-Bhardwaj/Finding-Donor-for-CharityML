# Data Scientist Nanodegree
# Supervised Learning
## Project: Finding Donor for CharityML

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

This project requires **Python 3** and **Jupyter Notebook** the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [Matplotlib](https://pypi.org/project/times/)
- [time](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

## Project Motivation<a name="motivation"></a>

This is the first project of the Data Scientist Nanodegree. In this project we will find the supervised learning technique and Analytical mind on the data collected from 1994 US Census. 

CharityML determined that every donation they received came from someone that was making more than $50,000 annually. 
Here our objective is to build an algorithm to best identify potential donors. In the process we will be evaluate and optimize several different supervised learners to determine which algorithm will provide the highest donation.

Filter: income > 50K


## File Descriptions <a name="files"></a>

There are 2 files available here to showcase work related to the above questions. 
1. finding_donors.ipynb: This file contains the steps followed and code.
2. README.md: This file gives an overview about the project, data used and the packages or libraries used in this project.
3. census.csv: data file is not uploaded but you can download the census file from [here](https://www.kaggle.com/c/udacity-mlcharity-competition/data)


## Results<a name="results"></a>

The main findings of the code is:
* The most important features to find potential donors are 'capital-gain', 'capital-loss', 'age', 'education_num' and 'hours-per-week' (in assending order). 

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to CharityML and Udacity for the data.  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/c/udacity-mlcharity-competition/data).


