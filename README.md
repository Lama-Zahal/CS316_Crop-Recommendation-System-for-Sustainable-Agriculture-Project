# 🌱CS316_AI-Based-Crop-Recommendation-System-for-Sustainable-Agriculture-Project
# 1.Project Overview
The crop recommendation system is a machine learning model that predicts the most  suitable crop based on soil and environmental conditions. 

The system analyzes seven input features: nitrogen, phosphorus, potassium, temperature, humidity , pH, and rainfall to predict the most appropriate crop.

This project was developed with my team where we utilize the knowledge gained from the course CS316: Intro to AI and DS to work on this project.

# 2.Project Objectives
- Explore the crop recommendation dataset.
- Build classification models using soil and environmental features
- Optimize the model to achieve the best results
- Evaluate and compare the performance of different models
- Predict the most suitable crop for new input conditions
- Try rainfall sensitivity experiment to test with different climate conditions

# 3.Dataset 
The dataset used for this project is the Crop Recommendation Dataset, which is publicly available on Kaggle. 
Dataset link: https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset

# 4.Project Workflow 
The project is organized into four notebooks, each representing a different stage of development

**Notebook 1: Data Exploration**
This notebook focuses on preparing and understanding the dataset.
output: clean_crop.parquet

**Notebook 2: Model training and Evaluation**
This notebook we are going to build 4 models and train them on our crop type dataset and report their results. We will optimize our models to get the best results for comparison and to report.

**Required input file:**
clean_crop.parquet
**Important:** Before running this notebook, upload clean_crop.parquet into the Google Colab runtime.

**Notebook 3: Best Model Selection and PCA**
This notebook focuses on model optimization, dimensionality reduction experiment, and selecting the best-performing model. 

**Required Input File:**
best_model.csv
**Important:** Upload best_model.csv into the Google Colab runtime before executing this notebook

**Notebook 4: Crop recommendation system**
This notebook implements the final crop recommendation function to test the model on new unseen data.

**Required Input File:**
best_model.joblib
**Important:** Upload best_model.joblib into the Google Colab runtime before executing this notebook

# 5. How to run the project
Prerequisites:
- Access to Google Colab.
- Required Python libraries installed.

Run the notebooks in the following order:

- Step 1 – Data Exploration:
Open 01_data_exploration.ipynb and execute the cells to explore, clean, and prepare the original dataset.
The notebook generates clean_crop.parquet.

- Step 2 – Model Training and Evaluation
Open 02_model_training_and_evaluation_final.ipynb.
Before running the notebook:
Upload clean_crop.parquet into the runtime.
Execute the notebook cells.

- Step 3 – Best Model Selection and PCA
Open 03_Best_Model_After_PCA.ipynb.
Before running the notebook:
Upload best_model.csv into the runtime.
Execute the notebook cells.

- Step 4 – Crop Recommendation System
Open 04_recommendation_system.ipynb.
Before running the notebook:
Upload best_model.joblib into the runtime.
Execute the notebook cells.

Enter the required soil and environmental conditions to receive a crop recommendation.

# 6. Libraries and Tools
- Python
- Google Colab
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Sckit-Learn
- Joblib

# 7. Team Members
Nourah Aldhayan
Yara Alsharari
Leen Alhabdan
Lama Zahal

