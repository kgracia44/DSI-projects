# Capstone Project Methodology
### Last Update: September 2016

## Project: Factors That Impact Educational Attainment Among Foster Youth

This repo folder contains the jupyter notebooks that document the steps and rationale for the project analysis. These notebooks contain the python code I used to complete my capstone project. For a high-level summary (an overview without code) of project background, aims, methodology, results and conclusions, please visit my capstone project blog post: https://kgracia44.github.io/capstone_post/

##### Raw Data Source:

<img src="imgs_for_readme/sources.png">


**Note: In order to uphold confidentiality standards, no identifying data is ever displayed. 



## Approach and Table of Contents----------------------------- 

1) Data: Folder with 2 jupyter notebooks and data dictionary csv file
    
    Jupyter Notebook 1: CleanData_MungeData_4Sets
    
    - In this notebook:
        
        - Raw data reviewed, described, and cleaned.
        - Data wrangled into 4 data sets for analysis and saved in local postgreSQL database and as CSV files.
        - 4 Data sets: Cohort 1 Baseline Population, Cohort 1 Baseline Pop excluding 7 states*, Cohort 1 Wave 2 Population, 
        and Cohort 2 Baseline Population
        
        * Please Note: In order to address data quality issue, data sets used for analysis exclude data from the following   
        states: HI, IN, KY, MS, OR, TX, TN.
        
    --
    
    Jupyter Notebook 2: DataDict_Risks_and_Assumps
    
    - In this notebook:
        
        - Data Dictionary (csv file is provided in this folder as well)
        - Risks and Assumptions of Data 
____________________________________________________    


2) EDA_and_HypothesisTesting: Folder with 1 jupyter notebook and 3 csv files
    
    - Jupyter notebook: EDA_cohort1_sample
    
    - In this notebook:
        
        - Exploratory Data Analysis of cohort 1 sample
        - Univariate and Bivariate Analysis of Demographics, Features, and Targets
        - Hypothesis Testing: Chi Squared Test of Association
        - 3 Data sets: cohort1_demographics_all.csv, cohort1_features_all.csv, cohort1_targets_all.csv
        
____________________________________________________    


3) capstone_part3: Folder with several jupyter notebooks
    
    - Jupyter notebook: several
    
    - In these notebooks:
        
        - Unsupervised Machine Learning techniques (PCA Analysis) to determine best target variable
        
____________________________________________________    


4) capstone_part4: Folder with several jupyter notebooks
    
    - Jupyter notebook: several
    
    - In these notebooks:
        
    - Supervised Machine Learning techniques (to build various models including logistic regression and tree-based models) in 
      order to determine if there are any particular services, and if so what are they, that lead to higher educational 
      attainment.
