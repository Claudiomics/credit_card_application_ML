# credit_card_application_ML

# Table of Contents
1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Steps](#steps)
   1. [Data Loading and Exploration](#data-loading-and-exploration)
   2. [Data Preparation and Preprocessing](#data-preparation-and-preprocessing)
         1. [Splitting into Train and Test Sets](#splitting-into-train-and-test-sets)
         2. [Cleaning Missing Values](#cleaning-missing-values)
         3. [Feature Selection by Correlation Matrix](#feature-selection-by-correlation-matrix)
         4. [Scale Features](#scale-features)
   3. [Fitting the Model to the Train Set](#fitting-the-model-to-the-train-set)
   4. [Evaluate Model Accuracy](#evaluate-model-accuracy)
   5. [Improving the Model](#improving-the-model)
   7. [Conclusion](#conclusion)
7. [Licence Information](#licence-information)

## Introduction 

This is the first machine learning lab I've completed, as an automated service to predict whether a credit card application will be approved or denied. The code is outlined in 'Credit_Card_Lab.ipynb' with lots of notes for my own learning and development. The original lab document supplied by Peregrine is the 'notebook.ipynb'.

I will be typing up my project and what I've learned on this README.md document.

## Installation 

__Download the Jupyter Notebook File:__

Download the .ipynb file and add it to your project folder.

```
notebook.ipynb
```

__Download the Dataset:__

Download the file containing the credit card application information from the [UCI Machine Learning Repository](#https://archive.ics.uci.edu/dataset/27/credit+approval) and add the crx.data file to the same folder as your notebook. 

__Set Up Your Environment:__

Ensure you have [Python](https://www.python.org/downloads/) on your system, and create a project-specific environment for this project by following these steps:

1. Open your command line terminal and navigate to your project folder.
```
cd path/to/projectfolder
```

2. Create a virtual enviroment and activate it:

Still in the open folder of the project in the terminal, add the following:

```
python3 -m venv venv
```
to create it and:
```
source venv/bin/activate
```
to activate it (on macOS).

3. Install necessary packages:

```
pip install ipykernel pandas numpy
```
4. Connect via VSCode:

Open VSCode and install the Jupyter extension in VSCode by searching 'Jupyter' in _Extensions_ view and clicking install.

Open your project folder in VSCode and open your .ipynb file.

Open the command palette by using 

```
Ctrl+Shift+P
```

and selecting 'Python: Select Interpreter'.

Select the Python environment you just created (venv) within your kernel, and you should be able to run the notebook.

## Steps

### 1. Data Loading and Exploration

importance of visualising the data.

### 2. Data Preparation and Preprocessing

#### 1. Splitting into Train and Test Sets

#### 2. Cleaning Missing Values

#### 3. Feature Selection by Correlation Matrix

#### 4. Scale Features 

### 3. Fitting the Model to the Train Set

### 4. Evaluate Model Accuracy 

### 4. Improving the Model 

## Conclusion 

In conclusion, this project is a machine learning model to automate the process of credit card application approvals. When this task is performed manually by humans, it is a lengthy proecss which is prone to errors.
