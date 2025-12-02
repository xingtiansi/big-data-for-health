# ME/CFS and Depression Diagnosis Prediction

This project involves the development of a machine learning model to predict the diagnosis of patients based on various features related to health, such as sleep quality, physical pain, stress level, depression score, and other relevant metrics. The model is trained to classify diagnoses into three categories: **ME/CFS**, **Depression**, and **Both**.

## Table of Contents
1. [Introduction](#introduction)
2. [Data Description](#data-description)
3. [Installation](#installation)
4. [Model Training](#model-training)
5. [Model Evaluation](#model-evaluation)
6. [Results](#results)
7. [Files](#files)
8. [License](#license)

## Introduction
The objective of this project is to classify individuals into three diagnosis categories:
- **ME/CFS (Myalgic Encephalomyelitis/Chronic Fatigue Syndrome)**
- **Depression**
- **Both**

The model uses various health-related features to predict the diagnosis, utilizing machine learning techniques such as Random Forest, Logistic Regression, Decision Trees, and K-Nearest Neighbors (KNN).

## Data Description
The dataset contains 1620 entries and 16 columns. The columns are as follows:

- **age**: Age of the individual
- **gender**: Gender of the individual
- **sleep_quality_index**: Sleep quality score
- **brain_fog_level**: Level of brain fog
- **physical_pain_score**: Score of physical pain
- **stress_level**: Stress level
- **depression_phq9_score**: Depression score
- **fatigue_severity_scale_score**: Fatigue severity score
- **pem_duration_hours**: Duration of PEM (Post-exertional malaise)
- **hours_of_sleep_per_night**: Number of hours of sleep per night
- **pem_present**: Whether PEM is present (binary)
- **work_status**: Work status (Not working, Working, Partially working)
- **social_activity_level**: Level of social activity
- **exercise_frequency**: Frequency of exercise
- **meditation_or_mindfulness**: Whether the individual practices meditation or mindfulness
- **diagnosis**: Diagnosis label (ME/CFS, Depression, Both)

### Missing Values
The dataset contains some missing values, which are handled during preprocessing using methods like imputation.

## Installation

To get started, clone this repository:

```bash
git clone https://github.com/yourusername/ME-CFS-Diagnosis-Prediction.git
