# Spam Detection AI

## Contributors
- Furkan Ataç - 150210304
- Ragib Guliyev - 150210920

## Project Overview
This project aims to develop an AI-driven spam detector to identify and block spam emails, thus protecting end users and saving costs for companies.

## Data Cleaning
- `data_merge.ipynb`: Merges various data sources for a comprehensive dataset.
- `lemmatize.ipynb`: Removes unnecessary punctuations and shortens texts for clearer insights.

## Clustering
- `clustering.ipynb`: Performs clustering on the Enron email dataset, which lacks labels, to identify correlations and groupings.

## Machine Learning
- `classifiers.ipynb`: Implements Naive Bayes, SVM, and Random Forest classifiers in an Ensemble Voting Classifier. Also includes a wordcloud analysis for spam and non-spam emails.

## Deep Learning
- `deeplearning.ipynb`: Utilizes a BERT Classifier, achieving a 0.97 accuracy in spam detection, surpassing traditional ML models.

## YouTube and SMS Spam Detection
- Adapts the DL model for YouTube and SMS spam detection.

## Demo
- `test_work.ipynb`: Demonstrates the model's application on a single email.

## Academic Report
For an in-depth understanding of the project's methodologies, results, and analyses, refer to our academic report: [Spam Detection AI Academic Report](https://drive.google.com/file/d/1VMs-fUmVVaZq5cwYbiBupQ_bE5apO9fm/view?usp=share_link)

## Requirements
- A `requirements.txt` file is included for necessary library installations.

## Execution Order
1. `data_merge.ipynb`
2. `lemmatize.ipynb`
3. `clustering.ipynb`
4. `classifiers.ipynb`
5. `deeplearning.ipynb`
6. `youtube_and_sms.ipynb`
7. `test_work.ipynb`
