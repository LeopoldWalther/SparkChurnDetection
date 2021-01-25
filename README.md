# SparkBigData_ChurnDetection

In this project I analysed user interactions of a streaming service using Spark
and created a machine learning model to predict user churn. The full description
of the project can be found in a blog post on [Medium](https://leopoldwalther.medium.com/predicting-user-churn-for-a-streaming-service-using-spark-6ef7379c7963).

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The project was created with Python 3.7.16.
Install the virtual environment using the requirements.txt of the project.
The follwing packages are mainly used:
- pyspark
- pandas
- matplotlib
- seaborn
- numpy
- re, time, datetime

## Project Motivation<a name="motivation"></a>

This is my capstone project of the Udactiy Nanodegree Data Scientist.

In this project I analysed user interactions of a streaming service using Spark.
After understanding the business importance of churn, I explored a small subset
of data to get a comprehension of the data and its quality. Then, I cleaned the
data from missing values and created features which allow a machine learning
model to find differences in the behaviour of users who stay with the service
versus those who churn. With the prepared data I trained different classifiers
and evaluated their performance with a suitable metric for imbalanced data.
The result of the project is a Gradient-Boosted Tree Classifier which can
identify users who will churn with high precision and high recall.

## File Descriptions <a name="files"></a>

The

```
SparkBigData_ChurnDetection/
│
├── README.md
├── requirements.txt
├── Sparkify.ipynb --> jupyter notebook with code for small local data subset
├── Sparkify.html
├── Sparkify_aws.ipynb --> jupyter notebook with code for aws cluster
├── Sparkify_aws.html
├── img/ --> png's created in jupyter notebook
├── models/ --> trained ML models
├── data/ --> input data JSON file

```


## Results<a name="results"></a>

The main findings of the code can be found at the post available
[here](https://leopoldwalther.medium.com/predicting-user-churn-for-a-streaming-service-using-spark-6ef7379c7963).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

I give credit to Udacity for the data (user_log).

Feel free to use my code as you please:

Copyright 2020 Leopold Walther

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
