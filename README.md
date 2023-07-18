# Recommender Systems Notebook

![Picture1](https://github.com/Unsupervised-Learning-Team-NM3/Unsupervised-Learning-Notebook-Team-NM3/assets/112989195/5080f356-e9a8-4662-a706-5b15f90a4b5b)

## 1) Overview
This repository forms part of a three part series of solutions architecture, namely, **Notebook, Streamlit application and a Presentation**. The three parts were devised to tailor a solution towards **Tyler Perry Studios**, a client to Tech-Analytics. 

This notebook houses an analysis of the data provided to Tech-Analytics by Tyler Perry Studios. The aim of requesting the data was so that Tech-Analytics could clean the data, visualise it and produce high performing models on the data that would form the basis of the application encompassing the Recommender system that is going to be built for Tyler Perry Studios.

## 2) Table of Content description
1. Importing Packages
   In this section of the notebook we import packages that we are going to use for:
   * Preprocessing
   * Visualisation
   * Styling the visuals
   * Modeling
   * Model evaluation
   * Surpassing warnings
   * Saving models
   * Randomisation

2. Loading Data
   In this section we load the datasets provided by Tyler Perry Studios.
   
   Information on the datasets:
   * genome_scores.csv - a score mapping the strength between movies and tag-related properties.
   * genome_tags.csv - user assigned tags for genome-related scores.
   * imdb_data.csv - Additional movie metadata scraped from IMDB using the links.csv file.
   * links.csv - File providing a mapping between a MovieLens ID and associated IMDB and TMDB IDs.
   * sample_submission.csv - Sample of the submission format for the hackathon.
   * tags.csv - User assigned for the movies within the dataset.
   * test.csv - The test split of the dataset. Contains user and movie IDs with no rating data.
   * train.csv - The training split of the dataset. Contains user and movie IDs with associated rating data.

3. Exploratory Data Analysis (EDA)
   In this section we study and analyse the data to uncover intresting insights about the data as well as to understand the necessity of some attributes of the data and establish whether or not their presence enhances model performance.

4. Modelling
   In this section we utilise the insights recovered from the EDA as well as data preprocessing to get the data in a state that it is ready to train models. We first take the data and split it into data we utilise for training the models and data we will use for validation to assess model performance.

5. Performance Evaluation
   Here we introduce the validation set to the models to evaluate their perfomance. We then choose the better performing model (in terms of prediction ability and computation time).

9. Data Engineering
    This section we utilised to alter the structure of the dataset in a way as to maximise model performance. In particular, we utilised the EDA to identify outliers and assessed it discarding them led to better performance of the model we chose.

11. Model Predictions on Unseen data
    We then went ahead, in this section, and produced predictions on totally unseen data that did not have any ratings.

13. Conclusion
    We explained interesting points from the analysis as well as insights about our model of choice.
