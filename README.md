# Intelligent Sensing and Sense Making Group Project Readme
---

## SECTION 1 : PROJECT TITLE
## Exploring Feature Engineering and Various Machine Learning Models for Human Action Recognition on the UTD-MHAD
  
---
## SECTION 2 : EXECUTIVE SUMMARY
This project sets out to explore sensor-based machine learning approaches to human activity recognition. Through studying the human anatomy and how the human body moves to perform various actions, feature engineering was carried out to extract distinctive information from the dataset and to remove variances that distracts the classification of human actions. The feature engineered dataset was fed into various machine learning and deep learning models and two of the models has outperformed the benchmark accuracy set by the collaborative representation classifier. A new graph machine learning model was conceptualised and implemented from scratch and has achieved high accuracy in classifying a subset of the 27 actions. Lastly, an image classification approach was explored by encoding the dataset into images and leveraging transferred learning model to perform the classification.

---
## SECTION 3 : TEAM & MEMBERS
Team Name: A22G  
Members  : Alfred Tay Wenjie, Wang Zilong, Wong Yoke Keong

---
## SECTION 4 : USAGE GUIDE

### Running notebooks on Google Colab

The team has provided notebooks that are ready to run in Google Colab. Please see below for instructions.

1. Navigate to the [Notebooks](/Notebooks) folder
2. Within the folder, there is a Notebook Description file listing the each notebook file, a brief description for that notebook and a link to open the notebook in Google Colab
3. Click on the 'Open in Colab' icon [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)] to view the Notebook in Google Colab Playground Mode
4. To execute the notebook, you need to make a copy of it by clicking on the Copy to Drive icon and subsequently from the menu, click `Runtime > Run all`. Please note that you will need to have a Google Account to execute the notebook

### Offline install

The notebooks have been validated on Google Colab. For local run, please refer to the requirements below.  

#### System Requirements
1. OS: Ubuntu 18.04.3 LTS
2. Python: 3.6.8
3. graphviz is required to be installed - please use command `sudo apt-get -qq install -y graphviz`

#### Python package requirements

To install them, please use command `pip install -r requirements.txt` using the accompanying requirements.txt


#### Note on running on Windows
To run on Windows, python packages need to be installed. The path names within the notebooks will need to be modified accordingly.

### Project Report
The project report can be downloaded from the Report folder.

---