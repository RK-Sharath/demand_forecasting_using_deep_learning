# Demand forecasting using deep learning

This pattern demonstrated how to forecast the demand for cash vending machines using Deep Learning. It is important for financial institutions to ensure there are no cashouts in the cash vending machines which can increase the revenue and enhance customer experience. The Long Short-Term Memory, or LSTM, network is a type of Recurrent Neural Network. Recurrent Neural Networks, or RNNs for short, are a special type of neural network designed for sequence problems. We will be creating a sequence prediction LSTM model which can predict the next value given an input sequence.

After completing this pattern, the developer will understand how to :

* Create a Deep Learning model using LSTM.
* Tuning the hyper parameters of the model.
* Transfer learning using LSTM.

# Architecture Diagram







## Included components

* [IBM Watson Studio](https://www.ibm.com/cloud/watson-studio): Analyze data using RStudio, Jupyter, and Python in a configured, collaborative environment that includes IBM value-adds, such as managed Spark.

* [IBM Cloud Object Storage](https://console.ng.bluemix.net/catalog/services/object-storage/?cm_sp=dw-bluemix-_-code-_-devcenter): An IBM Cloud service that provides an unstructured cloud data store to build and deliver cost effective apps and services with high reliability and fast speed to market. This code pattern uses Object Storage (Swift API).

* [Jupyter Notebooks](http://jupyter.org/): An open-source web application that allows you to create and share documents that contain live code, equations, visualizations and explanatory text.

## Featured technologies

* [Data Science](https://developer.ibm.com/code/technologies/data-science/): Systems and scientific methods to analyze structured and unstructured data in order to extract knowledge and insights.
* [Analytics](https://developer.ibm.com/code/technologies/analytics/): Analytics delivers the value of data for the enterprise.
* [Python](https://www.python.org/): Python is a programming language that lets you work more quickly and integrate your systems more effectively.
* [Jupyter Notebooks](http://jupyter.org/): An open-source web application that allows you to create and share documents that contain live code, equations, visualizations and explanatory text.

# Watch the Video

NA

# Steps

Follow these steps to setup and run this code pattern. The steps are
described in detail below.

1. [Sign up for IBM Cloud](#1-sign-up-for-ibm-cloud)
1. [Sign up for Watson Studio](#2-sign-up-for-watson-studio)
1. [Create the notebook](#3-create-the-notebook)
1. [Add the data](#4-add-the-data)
1. [Insert the dataframe](#5-insert-the-dataframe)
1. [Run the notebook](#6-run-the-notebook)
1. [Analyze the results](#7-analyze-the-results)

## 1. Sign up for IBM Cloud

Sign up for IBM [**Cloud**](https://console.bluemix.net/). By clicking on create a free account you will get 30 days trial account.

## 2. Sign up for Watson Studio

Sign up for IBM's [Watson Studio](http://dataplatform.ibm.com/). By creating a project in Watson Studio a free tier ``Object Storage`` service will be created in your IBM Cloud account. Choose the storage type as Object Storage (Swift API) for this code pattern.

## 3. Create the notebook

* Open [IBM Watson Studio](https://dataplatform.ibm.com).
* Click on `Create notebook` to create a notebook.
* Select the `From URL` tab.
* Enter a name for the notebook.
* Optionally, enter a description for the notebook.
* Enter this Notebook URL: https://github.ibm.com/sharrkum/fraud_prediction_using_imbalanced_data/blob/master/notebook/Fraud_Detection.ipynb
* Select the free Anaconda runtime.
* Click the `Create` button.

![](https://github.ibm.com/sharrkum/fraud_prediction_using_imbalanced_data/blob/master/image/create_notebook.PNG)

## 4. Add the data

Use `Find and Add Data` (look for the `10/01` icon)
and its `Files` tab. From there you can click
`browse` and add data files from your computer.

![](https://github.ibm.com/sharrkum/fraud_prediction_using_imbalanced_data/blob/master/image/add_file.png)

Note: The data file is in the `data` directory

## 5. Insert the DataFrame

Select the cell below `2. Read the Data & convert it into Dataframe` section in the notebook.

Use `Find and Add Data` (look for the `10/01` icon) and its `Files` tab. You should see the file names uploaded earlier. Make sure your active cell is the empty one created earlier. Select `Insert to code` (below your file name). Click `Insert pandas DataFrame` from drop down menu.

![](https://github.ibm.com/sharrkum/fraud_prediction_using_imbalanced_data/blob/master/image/insert%20df.PNG)

## 6. Run the notebook

When a notebook is executed, what is actually happening is that each code cell in
the notebook is executed, in order, from top to bottom.

Each code cell is selectable and is preceded by a tag in the left margin. The tag
format is `In [x]:`. Depending on the state of the notebook, the `x` can be:

* A blank, this indicates that the cell has never been executed.
* A number, this number represents the relative order this code step was executed.
* A `*`, this indicates that the cell is currently executing.

There are several ways to execute the code cells in your notebook:

* One cell at a time.
  * Select the cell, and then press the `Play` button in the toolbar.
* Batch mode, in sequential order.
  * From the `Cell` menu bar, there are several options available. For example, you
    can `Run All` cells in your notebook, or you can `Run All Below`, that will
    start executing from the first cell under the currently selected cell, and then
    continue executing all cells that follow.
    
## 7. Analyze the results

# Troubleshooting

[See DEBUGGING.md.](DEBUGGING.md)

# Useful Links:

[Watson Data Studio](https://www.ibm.com/cloud/watson-studio)
[Watson Knowledge Catalog](https://www.ibm.com/cloud/watson-knowledge-catalog)
[Watson Machine Learning](https://www.ibm.com/cloud/machine-learning)
[Deep Learning](https://www.ibm.com/cloud/deep-learning)
[Analytics Engine](https://www.ibm.com/cloud/analytics-engine)

# License

[Apache 2.0](LICENSE)



