# DHL-Sentiment-and-Topic-modelling
Customer Feedback Analysis: Sentiment & Topic Modeling
This project aims to help DHL (or any similar company) understand customer pain points and areas for improvement by analyzing customer feedback through Sentiment Analysis and Topic Modeling. The solution processes feedback from multiple sources (e.g., surveys, complaints, social media) to categorize sentiments and extract actionable insights.

The project consists of two key components:

Sentiment Analysis - Determines whether the customer feedback is positive, negative, or neutral.

Topic Modeling - Identifies the main topics and themes within the customer feedback.

Description
The project uses Natural Language Processing (NLP) techniques to analyze large volumes of unstructured text data. It provides a way to automate the process of categorizing feedback, identifying key issues, and understanding customer sentiment, allowing companies to respond more effectively.

Key Features
Sentiment Analysis: Classifies feedback into three sentiment categories: Positive, Negative, and Neutral.

Topic Modeling: Identifies and extracts key topics within feedback data (e.g., delivery issues, customer service).

Data Visualization: Visualize sentiment distribution and topic trends.

Files Overview
1. sentiment_analysis.ipynb
This script performs sentiment analysis on the customer feedback. It processes the input text and classifies the feedback into one of the following sentiments:

Positive

Negative

Neutral

Key Steps:

Preprocesses the text (tokenization, stopword removal, etc.).

Uses a sentiment analysis model or library (e.g., VADER, TextBlob) to analyze the text.

2. topic_modelling.py
This script uses Topic Modeling techniques, such as Latent Dirichlet Allocation (LDA), to identify the main topics in the feedback. The goal is to uncover hidden topics that customers are discussing, such as issues with delivery, customer service, or pricing.

Key Steps:

Tokenizes and preprocesses the text data.

Applies topic modeling algorithms to discover common themes in the feedback.

Outputs the top topics and their related keywords.

Installation
Prerequisites
Ensure that you have Python 3.x installed along with pip (Python package installer).



Install dependencies: Create a virtual environment (optional but recommended) and install required libraries from the requirements.txt file.
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt




