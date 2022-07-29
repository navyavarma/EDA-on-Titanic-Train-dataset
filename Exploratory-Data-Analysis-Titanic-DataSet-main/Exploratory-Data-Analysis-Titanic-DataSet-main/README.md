# Exploratory-Data-Analysis-Titanic-DataSet

<img src="https://camo.githubusercontent.com/51fe0e93862af83c7b5ae6d3c4c266c701d52917363ab9bc9d111adda275de66/68747470733a2f2f696d61676573382e616c706861636f646572732e636f6d2f3430352f3430353032392e6a7067" data-canonical-src="https://images8.alphacoders.com/405/405029.jpg" style="max-width: 100%;">

<h2 dir="auto"><a id="user-content-data-analysis-and-prediction-of-survivors-on-the-titanic-dataset:" class="anchor" aria-hidden="true" href="#data-analysis-and-prediction-of-survivors-on-the-titanic-dataset"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Data Analysis and Prediction of Survivors on the Titanic Dataset</h2>

<p dir="auto">Dependencies:</p><pre class="notranslate"><code>Python3
Numpy
Pandas
Matplotlib
Seaborn 
sklearn
</code></pre>

<p dir="auto">This project addresses the following Data Analysis topics:</p>
<pre class="notranslate">
Data Exploration and Preparation
Data Representation and Transformation
Data Visualization and Presentation
</code></pre>

## Note:
Data analysis is a statistical method used to describe variability among observed, correlated variables. The goal of performing factor analysis is to search for some unobserved variables called factors.

This dataset has passenger information who boarded the Titanic along with other information like survival status, Class, Fare, and other variables. The unfortunate event which was occurred on 15 April 1912, the Titanic sank after colliding with an iceberg, aboard 2224 peoples.

## Data Analysis:
Data Exploration and Preparation Learn about data: Are there missing data? Is it categorical? if not, min , max, avg values? if yes, what are the categories? distribution of variables Duplicate entry.
Data Representation and Transformation Few Passengers didn't pay for the ticket, so there may be a possibility that they didn't purchase a ticket or it was "complimentary" (ticket No. 112050,112059). After checking sample entries, i found out some of the passengers did get a complimentary ticket. This may also help to analyze whom(Important figure in society) to distribute the promotion ticket.
Transformation on dataframe: Droping some of the columns which many not contribute much to our machine learning model such as Name, Ticket, Cabin etc.

## Data prepocessing: 
It is a process to convert raw data into meaningful data using different techniques.
Data preprocessing techinques are: 1. Data Cleaning
                                   2. Data Integration
                                   3. Data Reduction
                                   4. Data Transformation
                                   5. Data Discretization

- Data Cleaning: It is a technique for identifying the missing values, smooth out noise while identifying outliers, correcting inconsistencies in the data.
- Data Integration: It is a techinque to merges data from multiple sources into a coherent data store, such asa data warehouse.
- Data Reduction: It is a technique use to reduce the data size by aggregating, eliminating redundant features, or clustering, for instance.
- Data Transformation: It is a technique, data are transformed into appropriate forms for ML model training, such as normalization, may be applied where
  data are scaled to fall within a range 0 to 1 or -1 to 1.
- Data Discretization: It is a technique tranforms numeric data by mapping values to interval or concept labels.

## Missing value/data: 
There are the best 6 methods to handle missing data or values. It is the part of Data Preprocessing and this is the most important step to build Machine Learning/Data Science project. The following are the most popular methods to handle missing data.

- Ignore missing values row / Delete row
- Fill missing value manually
- Use global constant
- Measure of central tendency (Mean, Median & Mode)
- Measure of central tendency for each class
- Most probable value ( ML Algorithms) #!pip install scikit-learn

## Feature Scaling: 
It is a method to scale numeric features in the same scale or range (-1 to 1, 0 to 1). This step is involved in data prepocessing and before ML model training. It is also called Data Normalization.
- we apply feature scaling on independent variables.
- those algorithms calculate distance and gradient descent based algorithms required Feature Scaling.
- tree based algorithms not required FS.

### Standardization: 
rescales the feature such as mean=0 and standard deviation=1. The result of Standardization is Z called as Z-score normalization.
### Normalization: 
rescales the feature in fixed range between 0 to 1, also called as Min-Max Scaling.
