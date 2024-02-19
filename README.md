# Effects of Inflation on the Stock Market 

Predicting the stock market trend has always been challenging since its movement is affected by many factors. 
Here, we analyse how the inflation rates affect the stock price of listed companies. 
We focus mainly on FMCG (Fast Moving Consumer Goods) Companies which are highly dependent on the interest rates. We approach this problem by analysing the fundamentals of the company and we factor in sentimental data (i.e., news about the company) Different features are given to help the machine learning model to predict the label of a given day; whether it is an uptrend or downtrend, those features are technical indicators generated from the stock’s price history. 
In addition, as financial news plays a vital role in changing the investor’s behaviour, the overall sentiment score on a given day is created from all news released on that day and added to the model as another feature. Finally compare its price volatility with the inflation rate. Three different machine learning models are tested in Spark (big-data computing platform), Logistic Regression, Random Forest, and Gradient Boosting Machine.


## Tools used

Apache Spark

Apache Spark is an open-source, distributed processing system used for big data workloads. It utilizes in-memory caching, and optimized query execution for fast analytic queries against data of any size Spark's analytics engine processes data 10 to 100 times faster than alternatives. It scales by distributing processing work across large clusters of computers, with built-in parallelism and fault tolerance. It is an open-source data-processing engine for large data sets. It is designed to deliver the computational speed, scalability, and programmability required for Big Data—specifically for streaming data, graph data, machine learning, and artificial intelligence (AI) applications.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install necessary packages.

```bash
pip install pyspark
pip install nltk
```

## Usage
Create separate environment
Install necessary packages
Extract data and modify path

```python
py '.\Effects of Inflation on Stock Market.py'
py '.\NEWS SENTIMENT.py'
py '.\PREDICTIONS.py'
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Status

Working on establishing relation between market volatity due to inflation and GDP variation and unemployment rates.