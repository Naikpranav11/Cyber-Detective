# Twitter Cyberbullying Detection App
## Overview
The Twitter Cyberbullying Detection App is a machine learning application that analyzes tweets to determine whether they contain instances of cyberbullying. If cyberbullying is detected, the app further classifies it into one of five categories: race, gender, age, religion, or ethnicity. The app features user-friendly options for dataset selection and offers exploratory data analysis (EDA) capabilities to help understand the data better.

## Features
- *Tweet Classification:* Analyze tweets to determine if they contain cyberbullying content.
- *Cyberbullying Categories:* Classify cyberbullying into five categories: race, gender, age, religion, and ethnicity.
- *Dataset Selection:* Choose different datasets for training and testing the model.
- *Exploratory Data Analysis (EDA):* Perform EDA on the chosen dataset to gain insights and visualize data patterns.
- *User-Friendly Interface:* Intuitive interface for seamless interaction and analysis.

## Technology Stack
Python: Core programming language for building the app.
NLP: Natural Language Processing techniques for text analysis and feature extraction.
Machine Learning: Scikit-learn for training and deploying classification models.
Streamlit: Web application framework for creating the user interface.
Libraries: NumPy, Pandas, Matplotlib, Seaborn for data manipulation and visualization.
Getting Started

## Prerequisites
Ensure you have the following installed:
Python 3.7 or later
Required Python libraries listed in requirements.txt

## Installation
Clone the repository:

bash
git clone https://github.com/yourusername/twitter-cyberbullying-detection.git
cd twitter-cyberbullying-detection
Install dependencies:

bash
pip install -r requirements.txt
Run the app:

bash
streamlit run app.py
## Usage
1. Upload Dataset: Choose a dataset for analysis and model training. The app supports CSV files.

2. Perform EDA: Explore the dataset with built-in visualization tools to understand the distribution and characteristics of data.

3. Classify Tweets: Use the trained model to classify tweets into cyberbullying or non-cyberbullying categories. Further classify detected cyberbullying into specific categories.

4. Review Results: Analyze the results and classification metrics displayed in the app.

