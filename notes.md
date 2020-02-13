# Introduction to Machine Learning Notes
## Lecture 1
First lecture of the class. Mostly contains Statistics, Data Science, and Data Mining basics.
### 1.1. The Place of Machine Learning, Data Science, and Artificial Intelligence
- Different Parts in Data Science
- The Fields of Data Science
- **Source**: https://dimensionless.in/understanding-different-components-roles-in-data-science/

### 1.2. Data Science Fundamental Steps
- Data steps and a few details
- **Source**: https://dimensionless.in/understanding-different-components-roles-in-data-science/

### 1.3. The Terms: "Learning" and "Machine Learning"
- What is "Learning" and Why we call it "Learning"
- What is Machine Learning
- **Source**: https://www.cmpe.boun.edu.tr/~ethem/i2ml2e/2e_v1-0/i2ml2e-chap1-v1-0.pdf

### 1.4. Data Types
- Categorical (Qualitative) Data
- Numerical (Quantitative) Data
- **Source**: https://databasetown.com/statistics-for-data-science-descriptive-inferential-statistics/

### 1.5. Data Representation in Computer World
- Main Data Formats: Csv, arff, office formats
- Other Data Formats: Database table, JSON, XML, image, sound, video, ...
- Unstructured vs. Structured Data
- **Source**: https://www.geeksforgeeks.org/difference-between-structured-semi-structured-and-unstructured-data/

## Sources:
- [SCRAPED] Statistics for Data Science (Descriptive & Inferential Statistics, https://databasetown.com/statistics-for-data-science-descriptive-inferential-statistics/
- [NOT-SCRAPED] Statistics Review For Data Scientists And Management, https://www.theseattledataguy.com/statistics-data-scientist-review/

## Outlier Analysis
- For multi-dimensional example: 
```bash
+-------+------------+-----+------------+
| Gender| isPregnant | Age | isSmoking? |
+-------+------------+-----+------------+
| Male  |  	Yes		 |  25 |   Yes		| ---> Outlier & Wrong data!
+-------+------------+-----+------------+
| Female|   Yes		 |  25 |   Yes		|
+-------+------------+-----+------------+
| Male  |   No 	     |  25 |   No		|
+-------+------------+-----+------------+
```


## Statistics for Data Science


### PDF Document:
![Alt text](/sources/docs/databasetown-com-statistics-for-data-science-descriptive-inferential-statistics-.pdf)

### A. DESCRIPTIVE STATISTICS
- Data, Types of Data
- Population/Sample Data
- Graphical Representation of variables in form of Graph & Tables: Bar/ Pie Chart
- Frequency Distribution Table:  
	- Relative frequency = frequency / total frequency
- Measures of central tendency: Mean, mode, median
- Measure of Asymmetry: Skewness -> Right (Positive) Skewness, Left (Negative) Skewness
- Dispersion of a set of data points around its means value: Sample/Population VAR Formula, Sample/Population STD Formula
- Coefficient of Variation
- Covariance & Correlation

### B. INFERENTIAL STATISTICS
- Probability distribution: Normal Distribution, Standard Normal Distribution, Central Limit Theorem
- Estimators and Estimates: Estimators, Estimates, Confidence Interval, Margin of Error
- Student’s T Distribution

### HYPOTHESIS TESTING
- Scientific Method
- Null Hypothesis (H_0), Alternative Hypothesis (H_1 or H_A)
- Decisions: Level of Significance, Confidence Level, Rejection region, Non rejection region
- Statistical Errors: Type-I Error (False Positive), Type-I Error (False Negative)
- P-value: A small/large p-value