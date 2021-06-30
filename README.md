# 📌Introduction
This data science project deals with <b>Delhi house price prediction</b>  dataset as we walks through we see step by step process of how to build a House price prediction website. So dataset was downloaded from kaggle.com (also uploaded dataset in same repositary), during model building i covered most of data science concepts (Check contents below).
For now just  made a optimized model in jupyter notebook, saved it and also exported .pickle and .json files.

Now the main aim is to built a website so the next step would be to write a python flask server that uses the saved model to serve http requests. Then will build the website in html, css and javascript that allows user to enter Area, bedrooms, BHK etc and it will call python flask server to retrieve the predicted price.
Then finally will deploy the model.
(will update everything as soon as possible)

## Contents

*  **Importing important libraries**
*  **EDA(Exploratory Data Analysis)**
*  **Data cleaning & Handling null values**
*  **Label encoding**
*  **Dimension reduction**
*  **One hot encoding**
*  **Model training & testing**
     * Hyperparameter tunning using GridsearchCV
     * Testing
*  **Export tested model to pickle file**
*  **Export location and column information in .json file**
     * .json file useful for later on application(Website building)
