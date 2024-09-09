# GPP-CVAE and Active Learning for Suspension Plasma Spraying Optimization
This repository contains the implementation of the Gaussian Process Prior Conditional Variational Autoencoder (GPP-CVAE) model and active learning framework used for optimizing the Suspension Plasma Spraying (SPS) process. This project was completed as part of my Master’s thesis in Machine Learning in Science at the University of Nottingham.

## Overview
Suspension Plasma Spraying (SPS) is a cutting-edge technology used to create high-performance coatings in industries like aerospace and automotive. However, optimizing the SPS process is challenging due to the complex interactions between process parameters such as gas flow rates, particle size, temperature, and other material properties.

In my thesis, I developed a novel machine learning framework that leverages GPP-CVAE and active learning to predict optimal gas flow rates while quantifying uncertainty. The model significantly outperforms traditional methods such as Random Forest, XGBoost, and Gaussian Process Regression.

## Key Features
GPP-CVAE Model: A hybrid model combining a Conditional Variational Autoencoder (CVAE) with Gaussian Process Priors to handle high-dimensional, non-linear interactions and quantify uncertainty in predictions.
Active Learning: A Bayesian optimization framework using Expected Improvement (EI) to iteratively select the most informative data points for further experimentation, improving efficiency and accuracy.
Ridge Regression: Used for predicting velocity and enthalpy based on input features and optimized gas flows.
## Repository Components:
#### Code for GPP-CVAE: Python scripts implementing the GPP-CVAE model, using PyTorch for the variational autoencoder and Gaussian process modules.
#### Active Learning: Scripts to implement Bayesian optimization with active learning, focusing on reducing uncertainty in the SPS process.
#### Ridge Regression Model: A model to predict velocity and enthalpy based on optimized parameters from GPP-CVAE.
