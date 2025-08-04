# 🔐 Cybersecurity Intrusion Detection - Machine Learning Analysis

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0%2B-orange)](https://scikit-learn.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## Overview

This project implements machine learning models to detect cybersecurity threats using network traffic and user behavior data. The analysis compares different classification algorithms to identify the most effective approach for automated intrusion detection systems.

## Dataset

The cybersecurity dataset contains network-based features (packet size, protocol type, encryption) and user behavior features (login attempts, session duration, IP reputation scores). The goal is to classify network activity as normal or attack using supervised learning techniques.

## Models & Results

Two primary models were evaluated: Logistic Regression and Random Forest. The Random Forest model achieved superior performance with 88% accuracy and 99% precision, making it suitable for production cybersecurity applications. Feature importance analysis revealed that authentication-related features (failed logins, login attempts) are the strongest predictors of cyber attacks.

## Key Findings

The analysis demonstrates that user behavior patterns are more predictive of attacks than network-level indicators. Failed login attempts emerged as the most important feature, followed by IP reputation scores and login attempt patterns. The Random Forest model's high precision (99%) significantly reduces false positive alerts, making it practical for automated threat detection.

## Implementation

The project includes comprehensive data exploration, preprocessing, model training, and evaluation. Visualization components cover feature distributions, correlation analysis, model performance comparisons, and prediction confidence assessments. The final model provides probability-based threat scoring suitable for operational cybersecurity environments.

## Usage

Clone the repository and run the Jupyter notebook to reproduce the analysis. The code is organized into clear sections covering data exploration, preprocessing, model training, and evaluation. All visualizations and performance metrics are included to demonstrate the effectiveness of the machine learning approach for cybersecurity applications.

---

**Technologies**: Python, Pandas, Scikit-learn, Matplotlib, Seaborn
