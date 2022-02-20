# Write-A-Data -Science-Blog-Post
## Exploratory Data Analysis and Quality Prediction on Red Wine Data
  
### Table of Contents
- [Project Installation](#installation)
- [Project Motivation](#motivation)
- [File Description](#file_description)
- [Results](#results)
- [Acknowledgements](#acknowledgements)

### Project Installation <a name="installation"></a>
#### Create a python environment or a conda environment to run the code.
 -  Python Environment
    - Install Python 3.6.x version 
    - open command prompt and run following command to install required python dependencies
    ``` 
        pip install -r requirements.txt
    ``` 
 - Anaconda Environment
    - If you have anaconda installed on your machine, follow the steps to create conda environment
    ```
        conda create --name ds_project_env pip python=3.6.4 anaconda
        conda activate ds_project_env
        pip install -r requirements.txt
    ```
 
### Project Motivation <a name="motivation"></a>
This is a Udacity Data Scientist Nanodegree project. The motivation behind this project is to understand how the different physio-chemical properties make a good wine. 
It includes exploratory data analysis techniques to get insight from red wine data and analyses how different wine properties impact on the wine 'quality'. 
Further, it considers below questions to get insight from the data.
1. How different features are correlated with each other?
2. Which feature are affecting the quality of wine?
3. Are there any outliers present in the dataset?
4. Can we think of building a classification model for predicting the wine quality?

### File Description <a name="file_description"></a>
wine_quality_data_analysis.ipynb : A Jupyter notebook which contains exploratory data anlysis of red wine data.

requirements.txt: a text file containing python libraries to be installed for this project

winquality-red.csv : dataset in CSV format for this project 

### Results <a name="results"></a>
The main findings of the code can be found at the post available at medium [here](https://medium.com/@deshmukhps95/exploratory-data-analysis-and-quality-prediction-on-red-wine-data-55a6f5936a6b)

### Acknowledgements<a name="acknowledgements"></a>
Credits to P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. for the dataset. Modeling wine preferences by data mining from physicochemical properties. 
In Decision Support Systems, Elsevier, 47(4):547-553, 2009.
You can find the data here [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality).