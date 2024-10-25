# WISDM Dataset: Data Analysis and Visualisation
## Project Overview
This project focuses on data analysis and visualisation using the WISDM dataset (Wireless Sensor Data Mining). The dataset contains accelerometer data collected from smartphones to recognise different human activities such as walking, jogging, sitting, and standing.

The objective of this project is to analyse the dataset to derive meaningful insights and visualise the patterns in the data. This project is carried out using Jupyter Notebook on Anaconda Navigator, with Python as the programming language for data processing, analysis, and visualisation.

## Dataset
The WISDM dataset contains accelerometer readings from smartphones used to monitor and recognise various human activities. It consists of time-stamped sensor data captured by accelerometers in mobile devices, tracking different actions like walking, jogging, sitting, and standing.

Dataset URL: https://archive.ics.uci.edu/dataset/507/wisdm+smartphone+and+smartwatch+activity+and+biometrics+dataset

## Project Structure
The project consists of the following key files:

Data Mining Cw2.ipynb: The Jupyter notebook that contains the code for data preprocessing, analysis, and visualisation.

Data Mining Cw2 - Classifier.ipynb: This notebook contain clustering and classification of the dataset


## Installation & Setup
Prerequisites:
Anaconda Navigator: Used to manage environments and launch Jupyter Notebooks.

Python 3.x: 

Jupyter Notebook: Used for writing and running code.


## Key Steps in the Project
1. Data Loading
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Data Visualisation
5. Clustering and Classification

## Results and Conclusion
A random forest classifier is applied to perform binary activity prediction. F1 score improved from 0.53 to 0.58 after applying SMOTE. This may be further improved by experimenting with other algorithms such as Gradient Boosting algorithm, but this experiment was limited by computational resources. The analysis provides insights into the sensor data and the characteristics of individuals in different activities. Visualisations demonstrate the patterns and relationships in the data, helping to understand how activities can be distinguished based on accelerometer/gyroscope readings. Identifying individual movement patterns would have useful applications in several industries. For example, Tracking individual movements helps trainers build personalised training regimes to improve performance or help healthcare professionals healthcare monitor the movement of elderly patients more closely. 
