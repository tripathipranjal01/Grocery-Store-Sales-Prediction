# Grocery-Store-Sales-Prediction
The objective is to develop a predictive model for forecasting the sales of individual products at specific retail stores. This project aims to create a model that enables stores to analyse and predict the sales of their outlets. It serves as an ideal project for gaining practical experience in data analytics and applying machine learning techniques, including linear regression, random forest regression, and XG Boost, to make accurate predictions regarding the sales of store products at their various outlets.

# Dataset-Description
Grocery Star has collected sales data from the year 2013 for 1559 products across 10 stores in different cities. The dataset consists of 12 attributes like Item Fat, Item Type, Item MRP, Outlet Type, Item Visibility, Item Weight, Outlet Identifier, Outlet Size, Outlet Establishment Year, Outlet Location Type, Item Identifier, and Item Outlet Sales. Out of these attributes, the response variable is the item outlet sales attribute, and the remaining attributes are used as the predictor variables.

The data set is also based on hypotheses of store level and product level. The store level hypotheses involve attributes like:- city, population density, store capacity, location, etc and the product level hypotheses involve attributes like:- brand, advertisement, promotional offer, etc.

# Dataset-Details
The data has 8523 rows of 12 variables.

# Variable-Details
    Item_Identifier: Unique product ID
    Item_Weight: Weight of product
    Item_Fat_Content - Whether the product is low fat or not
    Item_Visibility: The percentage of total display area of all products in a store allocated to the particular product
    Item_Type: The category to which the product belongs
    Item_MRP: Maximum Retail Price (list price) of the product
    Outlet_Identifier: Unique store ID
    Outlet_Establishment_Year: The year in which store was established
    Outlet_Size: The size of the store in terms of ground area covered
    Outlet_Location_Type: The type of city in which the store is located
    Outlet Type: Whether the outlet is just a grocery store or some sort of supermarket
    Item_Outlet_Sales - Sales of the product in the particular store. This is the outcome variable to be predicted.

# Setup
1. Install jupyter Notebook:
 pip install jupyter notebook

2. Install Pycharm -
https://www.jetbrains.com/pycharm/download/download-thanks.html?platform=windows&code=PCC

3. Install Python libraries.
 pip install pandas,  pip install numpy,  pip install matplotlib,  pip install klib,  pip install seaborn,  pip install Sklearn,  pip install joblib,  pip install xgboost  pip install flask

# Project-Workflow

# We will handle this problem in a structured way.
    Loading Packages and Data
    Data Structure and Content
    Exploratory Data Analysis
    Missing Value Treatment
    Feature Engineering
    Encoding Categorical Variables
    Label Encoding
    PreProcessing Data
    Modeling
    Linear Regression
    RandomForest Regressor
    XGBoost
