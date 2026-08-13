# ❤️ Heart Disease Prediction Using Neural Networks

A machine learning project that uses a neural network built with TensorFlow/Keras to predict the presence of heart disease from clinical features.

## 📌 Project Overview

This project implements an end-to-end binary classification workflow for heart disease prediction.

The project includes:

- Loading and exploring the dataset
- Data preprocessing
- Handling categorical features using one-hot encoding
- Splitting data into training and testing sets
- Feature standardization
- Building a neural network using TensorFlow/Keras
- Training and validation
- Analyzing training and validation performance
- Evaluating the model on unseen test data

## 🎯 Objective

The objective of this project is to develop a neural network model that can classify whether a patient is likely to have heart disease based on the available clinical features.

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- TensorFlow
- Keras
- Google Colab

## 🧠 Model Architecture

The neural network consists of:

Input Features  
↓  
Dense Layer — 16 neurons — ReLU activation  
↓  
Output Layer — 1 neuron — Sigmoid activation  
↓  
Binary Classification

The sigmoid activation is used in the output layer because this is a binary classification problem.

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Exploration
   ↓
Data Preprocessing
   ↓
One-Hot Encoding
   ↓
Train-Test Split
   ↓
Feature Standardization
   ↓
Neural Network
   ↓
Model Training
   ↓
Validation
   ↓
Test Evaluation
