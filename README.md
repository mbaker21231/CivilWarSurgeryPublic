# CivilWarSurgery

This repository contains materials and explanation in support of my research project "Was Civil War Surgery Effective?". In a sequence of workbooks, one can explore the results, use the data, extend results, etc. as desired. 

One should very easily be able to run all these workbooks by first installing a python distribution that supports `Jupyter` notebooks, such as the great [Anaconda](https://www.anaconda.com/download/) system. 

The workbooks use Python within `Jupyter` really just as a way of interacting with `Stata`, so one needs to have a version of `Stata` installed, and then one needs to install the excellent `ipystata` module, which can be [found here](https://github.com/TiesdeKok/ipystata), along with installation instructions. The workbooks in the repository are as follows:



1. [Data Preparation](Data%20Preparation.ipynb) - workbook that takes the raw data from Andrews's monograph and renders it into useable data for analysis.
2. [Group Lasso Programs](Developing%20Group%20Lasso%20Programs%20In%20Stata.ipynb) - some work in programming group lassos in Stata with a few examples.
3. [Lassoing Treatment and Outcome Models](Lassoing%20Treatment%20and%20Outcome%20Models.ipynb) - using the programs developed in Stata for the problem at hand - reducing the number of explanatory variables to an essential set.
4. [Presenting Treatment Models](Presenting%20Treatment%20Models.ipynb) - takes the pared-down models obtained in the previous set, re-estimates them, and calculates treatment effects. 
5. [Summary Tables and Figures for Presentation](Summary%20Tables%20and%20Figures%20for%20Presentation.ipynb) - Creates graphs, summary statistics, Manski bounds, etc. for use in the paper. 
6. [Census Sample](Census%20Sample.ipynb) - Last but not least, presents the evidence on the 1% sample from the census for use in developing the "Longnames" variable.
