# Experiments-on-Word-Perception-by-Human-Brain

### Project Overview
**Introduction**
This project investigates the relationship between phonetic and semantic word embeddings and their correlation with mean reading time. The aim is to reimplement methods from the paper "Phonetic Word Embeddings" to generate phonetic word embeddings and analyze them alongside semantic embeddings in predicting mean response times.


**Datasets Used**
Simvecs dataset: contains phonetic word embeddings.
Glove embeddings: semantic word embeddings.
Natural stories corpus: provides mean reading times.
**Methodology**
Clustering Method: Analyzes cosine similarity between word pairs within clusters based on embeddings.
Regression using Embeddings: Predicts target variable using phonetic and semantic embeddings.
Regression using Word Length: Predicts target variable using word length and embeddings.
Regression using Word Length and Log Probabilities: Predicts target variable using additional features.
Manual Classification of Word Pairs: Classifies word pairs based on mean reading time differences.
Binary Classification: Trains neural network for classification using embeddings.
Continuous Classification: Trains neural network for continuous classification using embeddings.

**Results**
K-Means Clustering: Provided insights into semantic similarities.
Regression Analysis: Semantic embeddings showed better fit for mean reading times.
Manual Comparison: Semantic similarities correlated better with mean reading times.
Binary Classification: Semantic embeddings outperformed phonetic embeddings.
Continuous Classification: Semantic embeddings demonstrated higher accuracy.
Conclusion and Future Work
Semantic embeddings proved more effective in predicting mean response times. Future work could involve using richer datasets and advanced models like transformers for better performance.

**Deliverables**
Research Report
Detailed methodology, findings, and implications.
Description of datasets used.
Analysis of clustering, regression, manual classification, and neural network performance.
Conclusion and suggestions for future research.
Visualization and Graphs
Visual representations of clustering results.
Graphs illustrating regression analysis outputs.
Visualizations of manual classification results.
Plots depicting neural network classification accuracy.
Statistical Analysis
Detailed documentation of statistical tests conducted.
Summary of statistical significance and interpretation.
**Code**
Code for data preprocessing, clustering, regression, classification, and neural network modeling.
Documentation and comments for reproducibility.
Instructions for running the code.
Stakeholder Briefing
Executive summary tailored for stakeholders.
Key findings and implications presented concisely.
Recommendations for applications or further research.
Data and Model Availability
Provision of datasets used.
Sharing of trained models and relevant artifacts for reproducibility.
This summary captures the project's essence, methodologies, results, and deliverables. It provides a concise overview of the research conducted and its implications.
