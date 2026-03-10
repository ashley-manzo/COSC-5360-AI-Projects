# COSC-5360-AI-Projects
# The Audio Formula: Predicting Hit Songs Using Machine Learning

**Authors:** Ashley Manzo & Nylah Jackson

**Course:** COSC 5360 Midterm Project

### Overview
This repository contains our machine learning pipeline designed to predict whether a Spotify track will become a commercial hit based on its raw audio features (such as Danceability, Energy, and Valence). Because hit songs respresent a tiny fraction of all music, our core challenge was handling a highly imbalanced dataset to minimize false positives for industry application.

### Methodology & Models
We cleaned and analyzed a dataset of over 113,000 Spotify tracks.
- **Baseline:** Established using a Logistic Regression model with a standard scaler.
- **Primary Model:** Implemented an optimized Random Forest Classifier using Grid Search hyperparameter tuning.
- To handle the severe class imbalance, we utilized stratified train/test splits and balanced class weights.

### Repository Contents & How to Run
- **AshleyManzoMidterm.ipynb:** ***[FINAL SUBMISSION]*** The finalized Jupyter Notebook containing our completely merged machine learning pipeline and custom presentation visualizations.
- **AI_Midterm.ipynb:** An earlier development notebook showcasing the initial machine learning architecture. Kept in the repository to highlight our collaborative workflow.
- **dataset.csv:** The Spotify tracks dataset required to run the code.
  https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset
- **TheAudioFile.pdf:** Our final presentation slide deck.

**Instructions:** To run the final code, simply open **AshleyManzoMidterm.ipynb** and ensure **dataset.csv** is uploaded to the root directory of your environment before running the cells.
