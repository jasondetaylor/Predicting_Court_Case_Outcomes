Welcome to Jason Taylor's BrainStation Capstone Project.

See below for a list of the documents contained and associated suggestions.
Note that the bulk of the information is contained within 4 jupyter notebooks, sequentially labelled with each proceeding notebook leading to the next.

Data Dictionaries and Codebooks for Reference:
	'Data Dictionary - Custom': sheet 2 contains definitions of the variables used in the project, sheet 1 is an edited copy of 'Data Dictionary - JUSTFAIR'
	'Data Dictionary - JUSTFAIR': The data dictionary provided by the research group that collated the dataset used for this project, link with details: https://qsideinstitute.org/research/criminal-justice/justfair/
	'FJCID - Criminal Code Book 1996 Forward': Code book from the Federal Judicial Center Criminal Integrated Database (one of the sources used to create the justfair dataset)
	'USSCD - Variable_Codebook_for_Individual_Offenders': Code book from the UNITED STATES SENTENCING COMMISSION (one of the sources used to create the justfair dataset)

Reports and Notebooks:
	Capstone Report.pdf: A 3 page pdf executive summary of the efforts. This is a good place to start to famliliarize yourself with the project.
	Jupyter Notebook 1 - Data Cleaning.ipynb: Reads is our raw dataset and outputs a cleaned dataframe.
	Jupyter Notebook 2 - Exploratory Data Analysis (EDA).ipynb: Our first investigation into the data, analyzing patterns and creating new features to be used in our models.
	Juputer Notebook 3 - Multiclass Modeling.ipynb: An exploratory notebook attempting to resolve patterns in a minority target class.
	Juputer Notebook 4 - Binary Modeling.ipynb: The main modeling effort for this project.

Data Files:
	FinalDataset.csv: Dataset provided by JUSTFAIR group, the original dataset for the project.
	cleaned_df2.csv: Cleaned dataframe outputted from our 'Jupyter Notebook 1 - Data Cleaning'.
	cleaned_df3.csv: Cleaned datframe including feature engineered variables from our 'Jupyter Notebook 2 - Exploratory Data Analysis (EDA)'.
	States.xlsx: Additonal file linking US states to their abbreviated form, used to generate maps in our Tableau Workbook.

Additonal Files:
	Workbook.twb: Tableau workbook containing some EDA visualizations
	environment.yml: File containing package information required to run the jupyter notebooks.
			 Use the following command in anaconda prompt to recreate this enviroment: conda env create -f environment.yml
	