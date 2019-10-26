## Data cleaning, Exploratory Analysis, and Hypothesis Testing with Python

**Project description:** Telco is  a telecommunications company that offers internet, phone, streaming movie and streaming television services. The purpose of this project was to explore data that was collected by Telco to find customer insights. The analysis of this project was conducted using Python Programming within a Kaggle kernel. Below you will find a high level detail of the analysis. The full project including code can be found by opening this link [Kaggle Telco Project](https://www.kaggle.com/seekcoherence/telcom-python)

### 1. Loading and cleaning the dataset

The dataset was read in using pandas and stored in a dataframe as a variable named "Telco_data. The resulting dataframe is composed of 21 columns and 7,042 rows. 18 columns are in an object format while 3 are stored as integers.

<img src="images/datadesc2.png?raw=true"/>


After previewing the data in a table it becomes apparent the TotalCharges and MonthlyCharges columns are the same numerical format, however only MonthlyCharges is in a numerical format. Converting TotalCharges to a float is preformed in order to conduct proper analysis. Searching for null values shows there are 11. Rows containing null values are dropped. Lastly a column containing CustomerID is of no value to the analysis and is dropped.

<img src="images/table.png?raw=true"/>

Code for cleaning steps

<img src="images/cleaning.png?raw=true"/>


### 2. Assess assumptions on which statistical inference will be based

```javascript
if (isAwesome){
  return true
}
```

### 3. Support the selection of appropriate statistical tools and techniques

<img src="images/dummy_thumbnail.jpg?raw=true"/>

### 4. Provide a basis for further data collection through surveys or experiments

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
