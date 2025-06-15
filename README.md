# AirNet-AI: Air Quality Analysis and Forecasting

This repository hosts the code and documentation for our AirNet-AI project. The system leverages deep learning to detect and predict urban air quality conditions based on UCI Air Quality dataset, supporting both classification and regression tasks for CO and NOx levels.

## Introduction

Air pollution poses significant risks to public health and environmental sustainability. Manual monitoring methods are limited in scope and scalability. AirNet-AI aims to automate the classification of CO(GT) concentration and regression of NOx(GT) levels using neural networks, enabling more accurate and efficient pollution monitoring and response.

## Project Summary

- **Models Used**: Multilayer Perceptron (MLP)

- **Key Techniques**: Data Normalization, Polynomial Interpolation, Dropout Regularization, ReLU & Sigmoid Activation, MSE & Binary Crossentropy Loss

## Models and Performance

We implemented two models tailored for separate tasks:

- **Classification (CO(GT))**: A neural network with four hidden layers using ReLU and dropout. Achieved accuracy of 90.55% and precision of 84.57%.

- **Regression (NOx(GT))**: A similar network with linear output and MSE loss. Achieved RMSE of 105.07 and MAE of 86.53.

## Dataset

The dataset is sourced from the UCI Air Quality Dataset, containing hourly sensor measurements of gas concentrations and weather variables. Missing values (-200) were handled via deletion or interpolation.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Citation

If you use this system or the dataset in your research, please cite the relevant literature on air quality monitoring with machine learning.
