# Cognitive Sentiment Explorer

## Project Motivation

The Cognitive Sentiment Explorer analyzes textual data to uncover sentiment, insights and cognitive themes over time.
It demonstrates how data and text processing, sentiment scoring, and clustering can be combined to provide valuable information.

## Architecture (Pipeline Diagram)

Data Ingestion → Data Analysis (pandas) → Text Processing (tokenization, stopwords)
→ Sentiment Analysis (VADER + custom lexicon) → Clustering (KMeans) -> Insights

## Data

Files uploaded on GitHub (csv and txt format)

## Methods

Variables, control flow, loops and functions
Mini challenges: Fibonacci sequence generator

Data Cleaning with Pandas
Data handling

Visualization of Data
Matplotlib

Text Processing

Tokenization
Stopword removal 
Lemmatization

Sentiment Analysis

VADER sentiment scoring (Positive / Neutral / Negative)
From-scratch lexicon-based scorer with negation handling

Clustering & Trends
KMeans clustering
Anomaly detection through pandas module


## Tricky Problems Solved

Figuring out the ideal k value for K Means clustering.

Anomaly detection done through pandas and simple math.

Implementing advanced NLP techniques such as NLTK where I had to import more in Colab.



## Key Findings

Used the elbow method to determine the optimal number of K clusters, which improved the quality and interpretability of the KMeans results.

Compared the population of two countries from the countries.csv dataset using Matplotlib, Pandas, and related data analysis features to visualize trends over time.

Performed sentiment analysis on text from the read.txt file, identifying the emotions present and quantifying their distribution.

## Limitations

Finding Learning Resources While Coding

Limited dataset size reduced statistical significance of some findings.

Language coverage restricted to English; non-English text was excluded. (In text processing)



## Next Steps

Expand dataset to include more sources, more data and provide an in-depth analysis.

Integrate multilingual sentiment analysis to broaden applicability.

Experiment with other advanced NLP models (e.g., BERT) for deeper contextual understanding.

