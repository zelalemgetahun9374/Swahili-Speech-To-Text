# Swahili-Speech-To-Text

**Table of Contents**

- [Swahili-Speech-To-Text](#swahili-speech-to-text)
  - [Overview](#overview)
  - [Scenario](#scenario)
  - [Approach](#approach)
  - [Project Structure](#project-structure)
    - [data:](#data)
    - [models:](#models)
    - [notebooks:](#notebooks)
    - [scripts](#scripts)
    - [tests:](#tests)
    - [logs:](#logs)
    - [root folder](#root-folder)
  - [Installation guide](#installation-guide)

## Overview
This repository is used for week 4 challenge of 10Academy. The instructions for this project can be found in the challenge document.

## Scenario
The World Food Program wants to deploy an intelligent form that collects nutritional information of food bought and sold at markets in two different countries in Africa - Ethiopia and Kenya. The design of this intelligent form requires selected people to install an app on their mobile phone, and whenever they buy food, they use their voice to activate the app to register the list of items they just bought in their own language. The intelligent systems in the app are expected to live to transcribe the speech-to-text and organize the information in an easy-to-process way in a database.

You work for the Tenacious data science consultancy, which is chosen to deliver speech-to-text technology for Swahili. Your responsibility is to build a deep learning model that is capable of transcribing a speech to text. The model you produce should be accurate and is robust against background noise.


## Approach
The project is divided and implemented by the following phases
- Data pre-processing
- Modelling using deep learning
- Serving predictions on a web interface
- Interpretation & Reporting

## Project Structure
The repository has a number of files including python scripts, jupyter notebooks, pdfs and text files. Here is their structure with a brief explanation.

### data:
- the folder where the dataset csv files are stored

### models:
- the folder where models' pickle files are stored

### notebooks:
- [EDA.ipynb](https://github.com/10-Academy-Batch-4-Week-4/Swahili-Speech-To-Text/blob/main/notebooks/EDA.ipynb): a jupyter notebook for exploratory data analysis
- [Meta-data Generation.ipynb](https://github.com/10-Academy-Batch-4-Week-4/Swahili-Speech-To-Text/blob/main/notebooks/Meta-data%20Generation.ipynb): a jupyter notebook for extracting the metadata from the transription and audio files
- [Audio preprocessing.ipynb](https://github.com/10-Academy-Batch-4-Week-4/Swahili-Speech-To-Text/blob/main/notebooks/Audio%20preprocessing.ipynb): a jupyter notebook for preprocessing the audio data

### scripts
- [app_logger.py](https://github.com/10-Academy-Batch-4-Week-4/Swahili-Speech-To-Text/blob/main/scripts/app_logger.py): a python script for logging
- [file_handler.py](https://github.com/10-Academy-Batch-4-Week-4/Swahili-Speech-To-Text/blob/main/scripts/file_handler.py): a python script for handling reading and writing of csv, pickle and other files

### tests:
- the folder containing unit tests for components in the scripts

### logs:
- the folder containing log files (if it doesn't exist it will be created once logging starts)

### root folder
- [10 Academy Batch 4 - Week 3 Challenge.pdf](https://github.com/10-Academy-Batch-4-Week-4/Swahili-Speech-To-Text/blob/main/10%20Academy%20Batch%204%20-%20Week%204%20Challenge.pdf): the challenge document
- [requirements.txt](https://github.com/10-Academy-Batch-4-Week-4/Swahili-Speech-To-Text/blob/main/requirements.txt): a text file lsiting the projet's dependancies
- [README.md](https://github.com/10-Academy-Batch-4-Week-4/Swahili-Speech-To-Text/blob/main/README.md): Markdown text with a brief explanation of the project and the repository structure.

## Installation guide
```
git clone https://github.com/10-Academy-Batch-4-Week-4/Swahili-Speech-To-Text
cd Swahili-Speech-To-Text
pip install -r requirements.txt
```
