# Customer Acquisition Project for Arvato Financial Solutions

## Table of contents:

1. [Installation](#installation)
2. [Project Description](#description)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Authors and Acknowledgements](#author)

## Installation <a name="installation"></a>

There's no need to install any libraries to run this code on the Anaconda environment. The code should run with no issues using Python versions 3.*.


## Project Description <a name="description"></a>

This project's goal is to predict which individuals are most likely to convert into becoming customers for a company in Germany.

This is done based on an analysis of the demographics data for customers compared to demographics information for the general population of Germany.

Unsupervised learning techniques were used to perform customer segmentation and identify the parts of the population that best describe the core customer base of the company.

After that, a classification model was built to make predictions such as which individuals are most likely to respond to a marketing campaingn and become customers for the company.

The data used was provided by Bertelsmann Arvato Analytics, and represents a real-life data science task.

This project is composed of the following steps:

1. Data cleaning

    Preparation of the data provided.

2. Customer Segmentation Report

    Attribute analysis of established customers and the general population in order to create customers segments and be able to identify people of interest within the population.

3. Classification Model

    The previous analysis will be used to predict what individuals will respond to the marketing campaing so that the company can focus on them instead of the entire population.



## File Descriptions <a name="files"></a>

Below are additional details about the project structure:

* [0_data_sampling.ipynb](https://github.com/marinavillaschi/customer-acquisition/blob/main/0_data_sampling.ipynb) : notebook that takes in the full datasets and exports a sample version of them so it's a bit easier to work through all the other steps of the project.


* [1_data_preparation.ipynb](https://github.com/marinavillaschi/customer-acquisition/blob/main/1_data_preparation.ipynb) : notebook containing all the data preparation steps.


* [2_cluster_prep.ipynb](https://github.com/marinavillaschi/customer-acquisition/blob/main/2_cluster_prep.ipynb) : notebook containing approaches testing for the the unsupervised learning model.


* [3_customer_segmentation.ipynb](https://github.com/marinavillaschi/customer-acquisition/blob/main/3_customer_segmentation.ipynb) : notebook containing the unsupervised learning model for making customers segments.


* [4_classification_model.ipynb](https://github.com/marinavillaschi/customer-acquisition/blob/main/4_classification_model.ipynb) : notebook containing the classification model to predict which individuals to send the marketing campaing to.
 

* [/data](https://github.com/marinavillaschi/customer-acquisition/tree/main/data) : contains all the data files used on this project:

    - ~~both .csv full dataset files used on the `0_data_sampling` notebook to make a sample out of them.~~
    
        _these files were deleted from the repo as they're too large._

    - both .csv files (`sample_AZDIAS` and `sample_CUSTOMERS`) used on the `1_data_preparation` notebook
    
    - both .csv mail-out files (`Udacity_MAILOUT_052018_TRAIN.csv` and `Udacity_MAILOUT_052018_TEST.csv`) used for training and testing of the supervised model in the `4_classification_model` notebook.

    - all four .csv files (`clean_AZDIAS`, `clean_CUSTOMERS`, `clean_TRAIN` and `clean_TEST`) containing clean and prepped data exported at the end of the `1_data_preparation` notebook notebook.

    - [/data_description](https://github.com/marinavillaschi/customer-acquisition/tree/main/data/data_description) : contains two Excel spreadsheets that holds detailed information about the attributes of the datasets.

    - [/predictions](https://github.com/marinavillaschi/customer-acquisition/tree/main/data/predictions) : contains `pred` csv file which is the clean test dataset with predictions made by the model.



## Results<a name="results"></a>

Each notebook holds one step of the project. They were developed with markdown cells in such a way that it's easy to follow and the conclusions are drawn as it goes.

Also, a blog post of the finding is available [here](https://pandascouple.medium.com/).


## Authors, and Acknowledgements <a name="author"></a>

### Authors

[Marina Villaschi](https://www.linkedin.com/in/marinavillaschi/?locale=en_US)

### Acknowledgements:

[Arvato Financial Solutions](https://www.bertelsmann.com/divisions/arvato/) for providing the data.

[Udacity](https://www.udacity.com/) as this project was developed during the Data Science Nanodegree Program.
