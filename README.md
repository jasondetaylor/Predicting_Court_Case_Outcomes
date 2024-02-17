# Predicting Court Case Outcomes
## Motivation and Introduction
Welcome to Jason Taylor's BrainStation Capstone Project! This project leveraged data pertaining to US Federal Court Cases and was completed as the final project during my Diploma of Data Science course. The motivation behind choosing this project was my interest in human decision making and it's influences. I wanted to test the hypothesis that a judge, in an ideal world, is able to separate themselves from bias and hence would portray no patterns that could be identified and utilzed by an ML model to predict a sentence outcome. The project is divided into 4 separate notebooks:
- Notebook 1 - Cleaning
- Notebook 2 - Exploratory Data Analysis (EDA)
- Notebook 3 - Multi-class Classification Modeling
- Notebook 4 - Binary-Class Classification Modeling

## Findings
It was found that sentence harshness could be predicted with 69.0% accuracy using the variables in this study. Furthermore, isolating these variables down to the 8 most influential, a high accuracy on sentence harshness of 63.4% could still be achieved. This shows considerable bias in the system pertaining mainly to these 8 key variables, see Capstone_Report.pdf for a further breakdown of these findings.

## Files
See below for a list of the documents contained and associated descriptions. Note that the bulk of the information is contained within 4 jupyter notebooks, sequentially labelled with each preceeding notebook leading to the next.

### Data Dictionaries and Codebooks for Reference:
- 'Data Dictionary - JUSTFAIR': The data dictionary provided by the research group that collated the dataset used for this project, link with details: https://qsideinstitute.org/research/criminal-justice/justfair/
- 'Data Dictionary - Custom': 
    - Sheet 2 contains definitions of the variables used in the project
    - Sheet 1 is an edited copy of 'Data Dictionary - JUSTFAIR'
- 'FJCID - Criminal Code Book 1996 Forward': Code book from the Federal Judicial Center Criminal Integrated Database (one of the sources used to create the justfair dataset)
- 'USSCD - Variable_Codebook_for_Individual_Offenders': Code book from the UNITED STATES SENTENCING COMMISSION (one of the sources used to create the justfair dataset)

### Reports and Notebooks:
- Capstone Report.pdf: A 3 page pdf executive summary of the efforts. This is a good place to start to famliliarize yourself with the project or if you just want a quick overview.
- Jupyter Notebook 1 - Data Cleaning.ipynb: Reads is our raw dataset and outputs a cleaned dataframe.
- Jupyter Notebook 2 - Exploratory Data Analysis (EDA).ipynb: Our first investigation into the data, analyzing patterns and creating new features to be used in our models.
- Juputer Notebook 3 - Multiclass Modeling.ipynb: An exploratory notebook attempting to resolve patterns in a minority target class.
- Juputer Notebook 4 - Binary Modeling.ipynb: The main modeling effort for this project.

### Data Files:
- FinalDataset.csv: Dataset provided by JUSTFAIR group, the original dataset for the project.
- cleaned_df2.csv: Cleaned dataframe outputted from our 'Jupyter Notebook 1 - Data Cleaning'.
- cleaned_df3.csv: Cleaned datframe including feature engineered variables from our 'Jupyter Notebook 2 - Exploratory Data Analysis (EDA)'.
- States.xlsx: Additonal file linking US states to their abbreviated form, used to generate maps in our Tableau Workbook.

### Additonal Files:
- Workbook.twb: Tableau workbook containing some EDA visualizations
- environment.yml: File containing package information required to run the jupyter notebooks. Use the following command in anaconda prompt to recreate this enviroment: 
    conda env create -f environment.yml
	