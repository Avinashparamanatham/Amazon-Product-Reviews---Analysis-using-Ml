# Amazon-Product-Reviews---Analysis-using-Ml

# **Amazon Reviews Sentiment Analysis**  

This project performs sentiment analysis on Amazon product reviews using **Natural Language Processing (NLP)** and **Machine Learning**. It utilizes data preprocessing, TF-IDF feature extraction, and Logistic Regression for classification.  

## **Table of Contents**  
- [Introduction](#introduction)  
- [Dataset](#dataset)  
- [Features](#features)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Results](#results)  
- [Visualization](#visualization)  
- [Contributing](#contributing)  
- [License](#license)  

## **Introduction**  
This repository contains a Python-based **sentiment analysis** project that classifies Amazon reviews into **positive, negative, or neutral** sentiments. The project includes data preprocessing, text cleaning, feature extraction using **TF-IDF**, and model training using **Logistic Regression**.  

## **Dataset**  
The dataset used is `amazon_reviews.csv`, containing customer reviews with fields such as:  
- **Id** – Unique identifier  
- **ProductId** – Product identifier  
- **UserId** – User identifier  
- **ProfileName** – Name of the reviewer  
- **HelpfulnessNumerator/Denominator** – Review helpfulness metrics  
- **Score** – Rating (1–5)  
- **Time** – Timestamp of review  
- **Summary** – Short summary of the review  
- **Text** – Full review text  

## **Features**  
- **Data Cleaning**: Handles missing values and preprocesses text  
- **Sentiment Labeling**: Assigns labels (`positive`, `negative`, `neutral`) based on review scores  
- **Feature Extraction**: Uses **TF-IDF Vectorization**  
- **Model Training**: Implements **Logistic Regression**  
- **Performance Evaluation**: Generates accuracy, confusion matrix, and classification report  

## **Installation**  

### **1. Clone the repository**  
```sh  
git clone https://github.com/your-username/amazon-reviews-sentiment-analysis.git  
cd amazon-reviews-sentiment-analysis  
```  

### **2. Install dependencies**  
Create a virtual environment (optional but recommended):  
```sh  
python -m venv env  
source env/bin/activate  # On Windows use: env\Scripts\activate  
```  

Install required packages:  
```sh  
pip install -r requirements.txt  
```  

## **Usage**  

### **1. Run the analysis script**  
```sh  
python sentiment_analysis.py  
```  

### **2. Expected Output**  
- Model Accuracy  
- Sentiment Distribution  
- Classification Report  
- Confusion Matrix  
- Missing Value Statistics  
- Sentiment Trends Over Years  

## **Results**  
- **Achieved Accuracy**: ~85-90% using Logistic Regression  
- **Sentiment Breakdown**: Positive, Negative, and Neutral reviews  
- **Feature Importance**: Key words influencing sentiment  

## **Visualization**  
The project includes various plots for analysis:  
- **Missing Values Heatmap**  
- **Sentiment Distribution Over Time**  
- **Confusion Matrix**  

## **Contributing**  
Contributions are welcome! If you’d like to improve the project, follow these steps:  
1. Fork the repository  
2. Create a new branch (`feature-branch`)  
3. Commit your changes  
4. Submit a pull request  

## Contact
For questions, feedback, or contributions, please contact Avinash at paramanathamavinash@gmail.com.
