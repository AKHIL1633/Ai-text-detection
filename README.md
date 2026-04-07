# AI Text Detection System

## Overview

This project detects whether a given text is AI-generated or human-written using a hybrid machine learning and deep learning approach. It combines transformer-based embeddings with traditional ML and neural architectures to achieve high accuracy.

## Features

* Detect AI-generated vs human-written text
* Hybrid model: BERT + XGBoost + CNN + BiLSTM + Transformer
* Achieves ~94% accuracy on benchmark datasets
* Real-time prediction using Streamlit interface

## Tech Stack

* Python
* BERT (Transformers)
* XGBoost
* CNN, BiLSTM, Transformer
* Streamlit

## Architecture

1. Data preprocessing and cleaning
2. Feature extraction using BERT embeddings
3. Hybrid model training (ML + DL)
4. Prediction pipeline for classification

## Results

* Accuracy: ~94%
* Strong F1-score performance
* Robust detection across different datasets

## How to Run

1. Clone the repository
   git clone https://github.com/AKHIL1633/Ai-text-detection.git

2. Navigate to project directory
   cd Ai-text-detection

3. Install dependencies
   pip install -r requirements.txt

4. Run the application
   streamlit run app.py

## Demo

(Add your Streamlit or deployed link here)

## Future Improvements

* Improve generalization across unseen models
* Add explainability (SHAP / attention visualization)
* Deploy as web API

## Author

Akhil P
