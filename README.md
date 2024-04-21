### Warehouse Construction Progress Prediction for CBRE (https://www.cbre.com/) as part of NYUxCBRE (https://nyudscdatathon2024.com/)
This project aims to predict the stage of progress of unseen warehouses using convolutional neural network (CNN) models and linear regression algorithms. The goal is to achieve between 70% to 60% accuracy in predicting warehouse progress stages and to estimate the number of quarters required for warehouse completion.

Link to slides - https://docs.google.com/presentation/d/1S7SLj6zBwFhO1dV_DiJdLs02rH5djUAqbaNpyj-mwJY/edit?usp=sharing


### Objective
The main objective of this project is to understand and predict the progress of warehouse construction over time. By analyzing satellite imagery of warehouses and utilizing relevant data such as square footage and progress stages, the project seeks to provide insights into when warehouses are expected to be completed.

### Approach
### CNN Model Training:
Train CNN models to predict warehouse progress stages from satellite imagery.
Evaluate model performance using ground truth data.
Linear Regression Modeling:
Train linear regression algorithms to predict the number of quarters required for warehouse completion.
Use input parameters such as progress stages and square footage to predict completion timelines.
Integration and Prediction:
Combine predictions from CNN models and linear regression algorithms to estimate the total number of warehouses completed within a specific timeframe.
Provide insights into the progress of warehouse construction projects.

### Usage
Data Collection:
Gather satellite imagery of warehouses and relevant data such as square footage and progress stages.
Model Training:
Train CNN models using the collected data to predict progress stages.
Train linear regression algorithms to estimate the number of quarters required for completion.
Prediction:
Use trained models to predict warehouse progress stages and completion timelines.
Aggregate predictions to estimate the total number of completed warehouses within a given timeframe.

### Repository Contents:

### BingAPI_.ipynb: 

Bing Maps API code to extract aerial satellite imagery of specific locations using latitude and longitude coordinates.
### Models(1).ipynb:
Contains code for Implementation of Model 1: Simple CNN Model
and 
code for implementation of the Final CNN model

### README.md: Updated documentation and project overview.

### dsproject.ipynb: 

Contains implementation of CNN model with Tensorflow
### dsproject_excelmungingANDlinearsolution.ipynb: 

project notebook containing Linear model solution using Stochastic Gradient Descent with Momentum.

### Data Source and Tools:

Data: Aerial satellite imagery from Bing Maps; Atlanta supply data related to UC buildings.

Image Specifications: 500x500 pixels; Zoom ratio used: 18.

API: Microsoft Bing Maps (Virtual Earth).

### Requirements
Python 3.x
Libraries: TensorFlow, PyTorch, Scikit-learn, Pandas, NumPy
Access to satellite imagery data (e.g., Bing Maps API)

### Contributors
Chandana Srinivasa Yatisha (cs7074@nyu.edu) - New York University

Srikar Iyer (smi6065@nyu.edu) - New York University

Unce Shahid (us2056@nyu.edu) - New York University

Anya Kondamani (ak8699@nyu.edu) - New York University

### Please Note: The final model is not the simple CNN model with accuracy 67% as mentioned in the video; we updated it to a different model (ref slides) 
