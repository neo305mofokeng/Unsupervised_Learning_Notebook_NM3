# Recommender Systems Notebook

![Picture1](https://github.com/Unsupervised-Learning-Team-NM3/Unsupervised-Learning-Notebook-Team-NM3/assets/112989195/5080f356-e9a8-4662-a706-5b15f90a4b5b)

## 1) Overview
This repository forms part of a three part series of solutions architecture, namely, **Notebook, Streamlit application and a Presentation**. The three parts were devised to tailor a solution towards **Tyler Perry Studios**, a client to Tech-Analytics. 

This notebook houses an analysis of the data provided to Tech-Analytics by Tyler Perry Studios. The aim of requesting the data was so that Tech-Analytics could clean the data, visualise it and produce high performing models on the data that would form the basis of the application encompassing the Recommender system that is going to be built for Tyler Perry Studios.
## 2) Prerequisites
**Modules:**

      pip install scikit-surprise

**Datasets:**
* Please use the contact details as the bottom of the readme file to request the datasets, or;
* Find them here: <a href="https://www.kaggle.com/t/9e26b99278a24be08f272af1f07a6817">Kaggle</a>

## 3) Table of Content description
### 1. Importing Packages
   In this section of the notebook we import packages that we are going to use for:
   * Preprocessing
   * Visualisation
   * Styling the visuals
   * Modeling
   * Model evaluation
   * Surpassing warnings
   * Saving models
   * Randomisation

### 2. Loading Data
   In this section we load the datasets provided by Tyler Perry Studios.
   
   Information on the datasets:
   * genome_scores.csv - a score mapping the strength between movies and tag-related properties.
   * genome_tags.csv - user assigned tags for genome-related scores.
   * imdb_data.csv - Additional movie metadata scraped from IMDB using the links.csv file.
   * links.csv - File providing a mapping between a MovieLens ID and associated IMDB and TMDB IDs.
   * tags.csv - User assigned for the movies within the dataset.
   * test.csv - The test split of the dataset. Contains user and movie IDs with no rating data.
   * train.csv - The training split of the dataset. Contains user and movie IDs with associated rating data.

### 3. Exploratory Data Analysis (EDA)
   In this section we study and analyse the data to uncover intresting insights about the data as well as to understand the necessity of some attributes of the data and establish whether or not their presence enhances model performance.

### 4. Modelling
   In this section we utilise the insights recovered from the EDA as well as data preprocessing to get the data in a state that it is ready to train models. We first take the data and split it into data we utilise for training the models and data we will use for validation to assess model performance.

### 5. Performance Evaluation
   Here we introduce the validation set to the models to evaluate their perfomance. We then choose the better performing model (in terms of prediction ability and computation time).

### 6. Data Engineering
   This section we utilised to alter the structure of the dataset in a way as to maximise model performance. In particular, we utilised the EDA to identify outliers and assessed it discarding them led to better performance of the model we chose.

### 7. Model Predictions on Unseen data
   We then went ahead, in this section, and produced predictions on totally unseen data that did not have any ratings.

### 8. Conclusion
   We explained interesting points from the analysis as well as insights about our model of choice.

## 4) Common Bugs
Over the cause of the project most of the team had a problem with installing the surprise module; this is coincidentally caused by a clash with an older version of Anaconda. This is mainly the case for people that use Anaconda as their default python path. To Troubleshoot this, fun the below lines of code.

Try one of these two ways:

Run the below lines of code on your anaconda command prompt:

      conda update -n base -c defaults conda #updates conda to latest version as well as updates all the other packages

   
      conda install -c conda-forge scikit-surprise #for installing surprise

Uninstall anaconda and reinstall it (after installation, if it prompts you to update the navigator version do agree to do so), then install surprise:

      conda install -c conda-forge scikit-surprise #for installing surprise


After these run successfully, it should allow you to import surprise on your notebook without any problems. I hope it helps :).

## 5) Support team
   Neo Mofokeng neo305mofokeng@gmail.com
   
   Prayer Lungile Nkuna nkuna.lprayer@gmail.com
   
   Busiswa Machi busiswa.machi@gmail.com
   
   Musa Mabika musamabika4@gmail.com
   
   Olwethu Bhengu olwethubhengu45@gmail.com
   
   Lehakoe Precious Lerara lplerara@gmail.com
   
   Madimetja Laudwin Mojela laudwinmadimetja@gmail.com
