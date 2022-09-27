# Analysis of education indicators

## Overview

The aim of this project is to **identify countries with a strong potential for online e-learning** for adults with a high level of education (at least a baccalaureat), through :

1. **selection of suitable indicators** from the world bank (explore at <https://datatopics.worldbank.org/education/>);
2. **exploratory data analysis** of these indicators

## Motivation

This is project 2 for the **Master in Data Science** (in French, BAC+5) from OpenClassrooms.

The project **demonstrates** the inital steps in a data science project :

- configuring a python environment, and using a jupyter notebook
- importing, joining and describing the files in a dataset
- validating, cleaning and selecting relevant data
- elementary exploratory data analysis (distributions, correlations, temporal evolutions)

## Requirements

The notebook includes a list of its own requirements, and a procedure for `pip install` of any missing libraries. It also contains procedures to download and unzip the data, if not already downloaded.

**Data** : The dataset of education indicators used in this analysis can be downloaded (37Mb) from the worldbank at <https://databank.worldbank.org/data/download/Edstats_csv.zip>. 

**Python libraries** : `numpy, pandas, matplotlib, seaborn, missingno, plotly, tqdm` 

## Files

- [P2_01_notebook.ipynb](./P2_01_notebook.ipynb) : import, cleaning, exploratory data analysis
- [P2_02_support.pdf](./P2_02_support.pdf) : a presentation of the project

_Note_ : Files are in French. _As requested by the jury, the notebook has not been cleaned up : the focus is on data manipulation and exploration_

## Approach

The net income for a company offering e-learning is assumed to depend on :

- The population selected for marketing (a country, a town, a field of study)
- The percentage of this population with access to e-learning
- The percentage of this population educated to at least baccalauréat
- The driving factors for e-learning (for example: unemployment, rurality, gender parity, availabilty of courses)
- The net price the students are willing and able to pay for e-learning

An indicator is selected for each of these factors.

The evolution of these indicators for different e-learning business models are explored :

- with / without expensive student accompanyment
- with / without reconversion of the workforce (academic vs professional courses)

Based on the selected indicators, the countries with the highest potential are found to depend strongly on the business model

## Keywords

- python, data-preprocessing, exploratory data analysis, data visualisation
- correlation heatmap, pairplot, barplot, lineplot, jointplot, chloropleth
- business model, performance indicator

## Skills acquired

- Set up a Python environment
- Use a Jupyter notebook to facilitate code writing and collaboration
- Manipulate data with specialized Python libraries
- Master the fundamental operations of the Python language for Data Science
- Perform a graphical representation using a suitable Python library
