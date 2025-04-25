# Cactus Identification | ResNet Transfer Learning 🌵
Please find the kaggle link in the sidebar.

## Project Overview 👀
This repository contains my solution to a Kaggle challenge related to the classification of columnar cacti in aerial imagery. The challenge is inspired by conservation efforts similar to Mexico's VIGIA project, which aims to develop autonomous surveillance systems for monitoring and protecting natural areas with rich biodiversity.

## Problem Statement 🎯
Human activity and agricultural expansion continue to threaten protected natural areas. This challenge addresses a specific aspect of environmental monitoring: automatically identifying columnar cacti from aerial photographs to support conservation efforts.

## Dataset 📊
The model is trained on a Kaggle dataset of 32x32px aerial images, each labeled to indicate the presence or absence of columnar cacti. This binary classification task enables automated detection of these distinctive plant species from surveillance imagery.

## Methodology 👨‍💻
My implementation uses transfer learning with ResNet-50, a proven convolutional neural network architecture for image classification tasks. The approach leverages pre-trained weights while addressing class imbalance to create a model that generalizes well to unseen data.

## Evaluation 📋
Model performance is evaluated using the Area Under the Curve (AUC) metric, which measures the relationship between predicted probabilities and actual labels. This metric was chosen for its robustness in handling imbalanced classification problems.

## Goals 🥅
- Develop a highly accurate columnar cacti classifier
- Create a model that generalizes well to new aerial imagery
- Demonstrate effective transfer learning techniques with ResNet-50
- Address class imbalance challenges in environmental image data
