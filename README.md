# Stress Detection using Wearable Sensors (WESAD Dataset)

## Project Overview
This project was developed as part of the **Ironhack Machine Learning Week**. The goal is to build a predictive model capable of detecting stress levels using physiological data from wearable devices. We utilized the **WESAD** (Wearable Stress and Affect Detection) dataset, a multi-modal dataset featuring physiological signals from chest-worn and wrist-worn devices.

## The Challenge
The objective was to explore supervised learning and feature engineering to classify emotional states (stress vs. non-stress). This project involved processing complex sensor data, extracting meaningful features, and training robust Machine Learning models.

## Repository Structure
The repository is organized into data preparation and modelling phases:

### Notebooks
* `01_chest_data_prep.ipynb`: Cleaning and feature extraction for chest-worn sensors.
* `02_chest_modelling.ipynb`: Training and evaluation using chest physiological signals.
* `03_wrist_data_prep.ipynb`: Processing and feature engineering for wrist-worn device data (BVP, EDA, TEMP).
* `04_wrist_modelling.ipynb`: Comparative analysis and model training for wrist-based detection.

### Saved Models (Pickle Files)
* `chest_model_rf.pkl`: Random Forest Classifier for chest data.
* `wrist_model_knn.pkl`: K-Nearest Neighbors for wrist-based prediction.
* `wrist_stress_model.pkl`: Optimized model for final stress detection.

### Extracted Features
* `features_chest.csv`, `features_wrist.csv`, `features_wrist_enriched.csv`, `features_wrist_final.csv`: Processed datasets used for training and testing.

## Dataset Access
The **WESAD** dataset used in this project is approximately 16GB and is **not included** in this repository due to size constraints.

To replicate this study, please download the dataset from the official source:
🔗 [WESAD Dataset - UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wesad+wearable+stress+and+affect+detection)

> **Note:** After downloading, place the files in a folder named `data/` in the root directory. This folder is ignored by Git to keep the repository lightweight.

## Presentation
For a detailed breakdown of the methodology, visualization of results, and final conclusions, please refer to the project presentation:
👉 [Google Slides Presentation](https://docs.google.com/presentation/d/1L5hN1-ujj5hbAmdQNI7SJKAluQ3XoQtt3RThC5Wx5ds/edit?slide=id.g3b9110d67be_0_61#slide=id.g3b9110d67be_0_61)

## 🛠️ Tech Stack
* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (Random Forest, KNN)
* **Version Control:** Git & GitHub

---
*Developed during the Ironhack Data Analytics Bootcamp by Antonio Gouveia.* 
