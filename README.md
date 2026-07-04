Customer Survey Sentiment Analysis using NLP

An end-to-end Natural Language Processing (NLP) project that analyzes customer feedback and classifies sentiments as Positive, Negative, or Neutral using Python and TextBlob. The project demonstrates data preprocessing, sentiment analysis, polarity scoring, and visualization to help businesses understand customer opinions and improve decision-making.

📌 Project Overview

Customer feedback provides valuable insights into customer satisfaction and business performance. This project processes survey responses, cleans missing values, performs sentiment analysis using NLP, calculates sentiment polarity scores, and visualizes the overall sentiment distribution.

🎯 Project Objectives
Analyze customer survey feedback using NLP.
Clean and preprocess customer survey data.
Handle missing values.
Classify customer feedback into Positive, Negative, and Neutral sentiments.
Calculate sentiment polarity scores.
Visualize sentiment distribution.
🛠️ Technologies Used
Python
Pandas
NumPy
TextBlob
Matplotlib
Jupyter Notebook
📂 Dataset Features
Column	Description
Customer_ID	Unique Customer ID
Name	Customer Name
Age	Customer Age
Gender	Gender
City	Customer City
Satisfaction_Score	Customer Satisfaction Rating
Feedback	Customer Review
Purchase_Amount	Purchase Amount
Survey_Date	Survey Date
Preferred_Channel	Communication Channel

🔄 Project Workflow

1️⃣ Import Libraries
Pandas
NumPy
TextBlob
Matplotlib

2️⃣ Load Dataset
Read Excel dataset
Display sample records
Understand dataset structure

3️⃣ Data Cleaning
Check missing values
Replace missing values
Convert feedback into text format

4️⃣ Sentiment Classification

Using TextBlob Sentiment Polarity

Polarity	Sentiment
> 0	Positive
< 0	Negative
= 0	Neutral

Example:

Feedback	Sentiment
Good service	Positive
Poor packaging	Negative
Delayed response	Neutral

5️⃣ Polarity Score Calculation

Each customer review receives a sentiment polarity score between -1 and 1.

Example:

Feedback	Polarity
Excellent support	1.00
Good service	0.70
Poor packaging	-0.40
Delayed response	0.00

6️⃣ Data Visualization

Bar chart showing:

Positive Reviews
Negative Reviews
Neutral Reviews

📊 Sample Output
Feedback	Polarity	Sentiment
Good service	0.70	Positive
Excellent support	1.00	Positive
Average experience	-0.15	Negative
Fast delivery	0.20	Positive
Delayed response	0.00	Neutral

📈 Business Insights
Identify customer satisfaction trends.
Detect common customer complaints.
Measure customer experience.
Improve products and services using customer feedback.
Support data-driven business decisions.

📁 Project Structure
Customer-Survey-Sentiment-Analysis/

│

├── customer survey Sentiment Analysis.ipynb

├── customer survey data.xlsx

├── README.md

└── requirements.txt

▶️ Installation

Clone the repository

git clone https://github.com/Harshiniravi-20/Customer-Survey-Sentiment-Analysis.git

Move into the project folder

cd Customer-Survey-Sentiment-Analysis

Install dependencies

pip install -r requirements.txt

Run the notebook

jupyter notebook

📦 Requirements

pandas

numpy

matplotlib

textblob

openpyxl

jupyter

You can install them using:

pip install pandas numpy matplotlib textblob openpyxl jupyter
🚀 Future Enhancements
Perform advanced text preprocessing.
Implement TF-IDF Vectorization.
Train Machine Learning sentiment classification models.
Apply Deep Learning using LSTM/BERT.
Create an interactive Power BI dashboard.
Deploy the project using Streamlit.
📸 Project Screenshots

Include screenshots of:

Dataset Preview
Missing Value Analysis
Sentiment Classification Output
Polarity Score Output
Sentiment Distribution Chart
👩‍💻 Author

Harshini Ravi

GitHub: https://github.com/Harshiniravi-20
LinkedIn: https://www.linkedin.com/in/harshini-ravi-124150273
