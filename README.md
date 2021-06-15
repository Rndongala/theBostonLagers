theBostonLagers
Analysis of Ride-Sharing Data in Boston, MA 🚕 🚷
Main Contents:
Data Cleaning.ipynb
Data Analysis.ipynb
Project Conclusions.docx
Tools Used:
Jupyter Notebook
Pandas
Matplotlib
SciPy Linear Regression
DatetimePy Library
Description
This project leverages Python's Pandas, Matplotlib, and SciPy libraries to analyze and draw conslusions from Uber and Lyft data collected in Boston, MA between November and December 2018. The original dataset was published by the Kaggle user RaviMunde, and can be found here. The process of importing and cleaning the dataset can be found in the Data Cleaning.ipynb file, while the process of analyzing and visualizing the dataset can be found in the Data Analysis.ipynb file. A full analysis can be seen by viewing and downloading the Project Conclusions.docx file.

Data Cleaning.ipynb
Components of the data_cleaning.ipynb file include:

Importation of a ride-sharing data set (cab_rides.csv) published by Kaggle user RaviMunde.
Use of the DatetimePy library to convert the 13-digit UNIX timestamp in order to determine the day of the week on which each data point was recovered.
Removal of extraneous columns not significant to the analysis.
Use of the DropNa function to remove about 60,000 columns missing essential data values.
Exportation of the cleaned data file for use in the analysis portion.
Data Analysis.ipynb
Components of the data_analysis.ipynb file include:

Importation of cleaned data file (cleaned_Kaggle_data.csv) created in the Data Cleaning.ipynb procedure.
Use of Pandas GroupBy, Matplotlib, and SciPy Linear Regression functionality to determine how ride distance and ride price compare accross the various ride sources and destinations.
