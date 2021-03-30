# Starbucks Capstone Challenge
Project in Data Scientist Nanodegree of Udacity

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation<a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda 
distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

It is the Starbuck's Capstone Challenge of the Data Scientist Nanodegree in Udacity. 
We get the dataset from the program that creates the data simulates how people make purchasing decisions and how those decisions are influenced by promotional offers. We want to make a recommendation engine that recommends Starbucks which offer should be sent to a particular customer.

We are interested to answer the following two questions:
1. Which offer should be sent to a particular customer to let the customer buy more?
2. Which demographic groups respond best to which offer type?


## File Descriptions<a name="files"></a>

```
├── README.md
├── Starbucks_Capstone_notebook.ipynb
├── data
│         ├── portfolio.json
│         ├── profile.json
│         └── transcript.json
├── images
│         ├── aventura.jpg
│         ├── pic1.png
│         ├── pic2.png
│         └── science.png
├── test_df.p
├── train_df.p
└── user_item_matrix.p
```
The images folder have images to be used in notebook, or in any other file for future.

The data folder contained three files:
- `portfolio.json` - containing offer ids and meta data about each offer (duration, type, etc.)
- `profile.json` - demographic data for each customer
- `transcript.json` - records for transactions, offers received, offers viewed, and offers completed

In the root folder have the notebook (Starbucks_Capstone_notebook.ipynb) for the projetc. And have
a README for be used in git project. And tree files end with .p, for be used in notebook, 
with files you don't need run the correlation matrix, the process is so slow. 


## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Stakbucks for the data, and Acknowledgements for the project
