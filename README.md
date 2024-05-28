# ADHD Classification Using Resting-State fMRI Data

## Overview
This repository contains code and resources for a neuroimaging analysis project focused on classifying Attention Deficit Hyperactivity Disorder (ADHD) using functional connectivity patterns derived from resting-state fMRI (rs-fMRI) data. The analysis employs machine learning techniques, specifically Support Vector Machines (SVMs), to differentiate individuals with ADHD from typically developing controls based on their brain connectivity profiles.

## Table of Contents
1. [Introduction](#introduction)
2. [Setup](#setup)
3. [Usage](#usage)
4. [Data](#data)
5. [Analysis](#analysis)
6. [Results](#results)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction
Attention Deficit Hyperactivity Disorder (ADHD) is one of the most common neurodevelopmental disorders, affecting millions of children and adolescents worldwide. Diagnosing ADHD is challenging due to its multifaceted nature, which includes symptoms such as inattention, hyperactivity, and impulsivity. Traditional diagnostic methods rely on subjective assessments and behavioral observations, leading to variability in diagnosis accuracy.

This study aims to leverage machine learning techniques to improve ADHD diagnosis by analyzing functional connectivity patterns derived from resting-state functional MRI (rs-fMRI) data. Resting-state fMRI captures spontaneous brain activity in the absence of explicit tasks, providing insights into the intrinsic functional organization of the brain. By analyzing connectivity patterns between different brain regions, we can identify biomarkers that distinguish individuals with ADHD from typically developing controls.

## Setup
To run the code in this repository, follow these steps:
1. Clone this repository to your local machine.
2. Install the required libraries.
3. Download the ADHD-200 dataset from the provided link and place it in the designated directory.

## Usage
The analysis pipeline involves several steps:
1. **Data Preprocessing:** Remove noise and artifacts from rs-fMRI data using standard preprocessing techniques such as motion correction, slice timing correction, and spatial normalization.
2. **Feature Extraction:** Extract connectivity features from preprocessed rs-fMRI data. This can involve computing correlation matrices between brain regions, extracting graph theory metrics, or applying dimensionality reduction techniques.
3. **Model Training:** Train a Support Vector Machine (SVM) classifier using the extracted features to differentiate between individuals with ADHD and typically developing controls.
4. **Model Evaluation:** Evaluate the classification performance of the SVM model using appropriate metrics such as accuracy, sensitivity, specificity, and area under the receiver operating characteristic curve (ROC-AUC).
5. **Optimization:** Explore advanced machine learning algorithms and feature selection techniques to improve classification accuracy and generalization performance.

## Data
The dataset used in this project is the ADHD-200 dataset, a publicly available collection of rs-fMRI data from individuals with ADHD and typically developing controls. The dataset includes preprocessed functional MRI scans and accompanying phenotypic information, such as age, gender, and diagnostic labels.


## Results
The SVM model achieved moderate accuracy in differentiating individuals with ADHD from typically developing controls, demonstrating the potential of machine learning-based approaches for computational diagnosis. However, further research is needed to explore advanced algorithms and feature selection techniques to enhance classification performance and generalizability.

## Contributing
Contributions to this project are welcome! If you find any bugs, have suggestions for improvement, or want to contribute new features, please open an issue or submit a pull request.


