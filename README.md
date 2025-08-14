# Cognitive-Sentiment-Explorer

## Project Motivation
The Cognitive Sentiment Explorer analyzes textual data to uncover sentiment trends and cognitive themes over time.
It demonstrates how data cleaning, text processing, sentiment scoring, and clustering can be combined into an end-to-end cognitive analytics pipeline.

## Architecture (Pipeline Diagram)
Data Ingestion → Data Preprocessing and Analysis (pandas) → Text Processing (tokenization, stopwords)
→ Sentiment Analysis (VADER + custom lexicon) → Clustering (KMeans) -> Insights

## Data
Files uploaded on GitHub (csv and txt format)

## Methods
Variables, control flow, functions, exception handling
Mini challenges: Fibonacci sequence generator 

Data Cleaning with Pandas
Data handling

Visualization of Data
Matplotlib

Text Processing

Custom tokenization without built-in split()
Stopword removal, term frequency calculation

Sentiment Analysis

VADER sentiment scoring (Positive / Neutral / Negative)
From-scratch lexicon-based scorer with negation handling


Clustering & Trends
KMeans clustering


## Tricky Problems Solved
KMeans Initialization Issues
Tuned parameters and standardized features to stabilize clustering results across runs.

Mixed Data Formats in Ingestion

Built preprocessing functions that adapt to both CSV and TXT file formats without separate pipelines.


## Key Findings
Used the elbow method to determine the optimal number of K clusters, which improved the quality and interpretability of the KMeans results.

Compared the population of two countries from the countries.csv dataset using Matplotlib, Pandas, and related data analysis features to visualize trends over time.

Performed sentiment analysis on text from the read.txt file, identifying the emotions present and quantifying their distribution.

## Limitations
Finding Learning Resources While Coding

Limited dataset size reduced statistical significance of some findings.

Language coverage restricted to English; non-English text was excluded.

Resource constraints made it challenging to quickly learn and implement advanced NLP techniques such as NLTK where I had to import more in Colab.


## Next Steps

Expand dataset to include more sources, more data and provide an in-depth analysis.

Integrate multilingual sentiment analysis to broaden applicability.

Experiment with other advanced NLP models (e.g., BERT) for deeper contextual understanding.
