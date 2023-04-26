# AdEase_Time-Series

Forecasting future traffic to Wikipedia pages using AR MA ARIMA : Removing trend and seasonality with decomposition

Introduction
This project involves analyzing and forecasting time series data using ARIMA and SARIMAX models. We will use Python programming language and several libraries such as Pandas, NumPy, Matplotlib, and Statsmodels.

Dataset
We will be using a time series dataset that contains sales data for a company from January 2017 to December 2021. The dataset is in CSV format, and we will import it into our Python environment using Pandas library.

Exploratory Data Analysis
We will start by importing the dataset and doing exploratory analysis steps like checking the structure and characteristics of the dataset. We will use Pandas and Matplotlib libraries to visualize and analyze the data.

Separating the Data
We will separate the data into training and testing datasets. We will use the training dataset to train our models and the testing dataset to evaluate their performance.

Analyzing and Visualizing the Data
We will analyze and visualize the data to get insights into its characteristics and behavior. We will use various statistical methods and visualizations such as line charts, scatter plots, and histograms.

Getting Inferences
We will draw inferences from the data and use them to develop hypotheses about the future behavior of the data.

Checking Stationarity
We will check if the data is stationary using statistical tests such as the Augmented Dickey-Fuller (ADF) test. If the data is not stationary, we will use differencing to make it stationary.

Formatting the Data for the Model
We will format the data to prepare it for the model. We will use Pandas library to convert the data into a time series format.

Dickey Fuller Test
We will use the ADF test to determine the order of differencing required to make the data stationary.

Decomposition
We will decompose the data into its trend, seasonality, and residual components using the decomposition method.

Differencing
We will use differencing to make the data stationary. We will apply differencing to the data based on the order of differencing determined by the ADF test.

Creating Model Training and Forecasting with ARIMA, SARIMAX
We will create ARIMA and SARIMAX models to train and forecast the data. We will use the Statsmodels library to create the models.

ACF and PACF Plot
We will use the ACF and PACF plots to determine the order of the AR and MA terms in the ARIMA and SARIMAX models.

Training the Model
We will train the ARIMA and SARIMAX models using the training dataset.

Forecasting for Different Languages/Regions
We will use the trained models to forecast sales for different languages and regions.

Plotting the Final Results
We will use Matplotlib library to plot the final results of the forecasted sales data.

Conclusion
In conclusion, this project involves analyzing and forecasting time series data using ARIMA and SARIMAX models. We will use various Python libraries and statistical methods to explore, analyze, and visualize the data, create and train the models, and forecast future sales for different languages and regions.
