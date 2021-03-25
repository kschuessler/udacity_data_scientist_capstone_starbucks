# Udacity Data Scientist Nanodegree: Starbucks Capstone Project
Capstone project for the Udacity Data Scientist Nanodegree

## Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

To run the notebook and scripts, Jupyter notebook, Python 3.9 and the following libraries are neccessary:

* json
* datetime
* math
* matplotlib
* numpy
* pandas
* seaborn (version 0.11.0 or higher)
* sklearn

## Project Motivation<a name="motivation"></a>

This is the Capstone project for the Udacity Data Science Nanodegree. The basis or this project is simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks. In particular, the data consists of information on the different offers, on customer demographics, and on offer and transaction events.

Utilizing this data, my goal is to answer the following questions:

1. Can we classify if an offer is going to be successful based on demographic and offer information?
2. Which factors are most important for predicting offer success?

## File Descriptions <a name="files"></a>

The project contains the following files

```
- \data
    - portfolio.json: offer information data set
    - profile.json: customer information data set
    - transcript.json: event data set
- Starbucks_Capstone_notebook.ipynb: Jupyter notebook project report
```

The main analysis is contained in the [Starbucks_Capstone_notebook](Starbucks_Capstone_notebook.ipynb) Jupyter notebook. The notebook includes all functions and code used to answer the project questions as well as the rationale behind the analyses in Markdown cells.

## Results<a name="results"></a>

The main findings of the code can be found at the Medium post available [here](https://medium.com/@schuessler.katharina/predicting-starbucks-promotional-offer-success-230d21205b86).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Credit must be given to Starbucks for the data. 
