# Global-AI-Impact-Sentiment-Analysis-
This project explores the sentiment impact of AI-generated content across industries such as journalism, marketing, entertainment, and social media. We engineered sentiment labels based on adoption, regulation, trust, and job market effects — and trained a Logistic Regression model to predict sentiment trends.

📂 Dataset Details
File Name: Global_AI_Content_Impact_Dataset.csv
Size: Thousands of structured records
Sources: Public surveys, AI research reports, digital media analytics
Main Fields:
 Country
 Year
 Industry
 AI Adoption Rate (%)
 Consumer Trust in AI (%)
 Job Loss Due to AI (%)
 Regulation Status
 Top AI Tools Used
 Market Share of AI Companies (%)
 (and more)

🛠 Project Workflow
1. Load and Clean the Data
Loaded the CSV file.

Checked for missing values.

2. Feature Engineering
Created a new sentiment column based on:

High adoption + trust → Positive

High job loss + strict regulation → Negative

Otherwise → Neutral

3. Exploratory Data Analysis (EDA)
Visualized sentiment distribution.

Created WordClouds of AI tools for each sentiment class.

4. Text Preprocessing
Combined Top AI Tools Used and Industry columns for text feature creation.

5. Feature Extraction
Used TF-IDF Vectorization to convert text to numerical vectors.

6. Model Building
Trained a Logistic Regression model for multi-class classification.

7. Model Evaluation
Evaluated performance using:

Accuracy Score

Classification Report

Confusion Matrix

🧠 Key Techniques Used
Python Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, wordcloud

Machine Learning Model: Logistic Regression

Feature Extraction: TF-IDF Vectorizer

Visualization: Seaborn count plots, WordCloud generation

📈 Results
Successfully predicted overall AI sentiment trends across industries.

Built an explainable model based on real-world adoption, trust, and regulation metrics.
