# Python-Star-Wars-Survey-Analysis

## Introduction

A survey was given by FiveThirtyEight that utilized SurveyMonkey. This survey sought to capture respondent data regarding the Star Wars Film Series franchise. The purpose of this project will be to clean the dataset and analyze it to determine the most popular film out of the original 6 Star Wars films. 

## Usage

To see the raw dataset with all the responses, you can download it [here](https://github.com/fivethirtyeight/data). Click on the green button that says `Code` near the top right of the page. Once completed, click `Download ZIP`. After the ZIP file has been downloaded, open the file and navigate to the `data-master` folder. In the `data-master` folder scroll down to the bottom to find `star-wars-survey`. Open this folder and download the `StarWars` CSV file.

The dataset will be read into a pandas dataframe using Jupyter Notebook.  The dataset will need an encoding to be read in. It is “ISO-8859-1”. 
To run the project you will want to install Jupyter Notebook. The easiest way to do this is by installing Anaconda Navigator. This [link](https://docs.anaconda.com/free/anaconda/install/index.html) will direct you on how to install for your appropriate operating system: Windows, Mac OS, Linux, etc. Once installed, you should have access to several applications, one of them being Jupyter Notebook.

## Brief Overview

Here are some important columns to note:

* `RespondentID` –An anonymized ID for the respondent (person taking the survey)
* `Gender` –the respondent’s gender
*	`Age`—the respondent’s age
* `Household Income`—the respondent’s income
* `Education`—the respondent’s education level
* `Location (Census Region)`—the respondent’s location
*	`Have you seen any of the 6 films in the Star Wars franchise?`—a Yes or No response
*	`Do you consider yourself to be a fan of the Star Wars film franchise?`—a Yes or No response


The analysis explores several aspects regarding film popularity among the following: whether or not the respondent was a Star Wars fan, Age, and Gender. Patterns were observed on whether the least favorite and most favorite films remained consistent across the board or changed drastically based on the above factors.
