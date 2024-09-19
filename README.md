# Student-Performance-Predictor
Linear Regression

<h2> <i>Aim</i> </h2>		
<ul>
<li> To Develop a secondary school student performance prediction tool to identify various variables that affect educational success and failure in secondary education based on real-world data on two core subjects - mathematics and Portuguese, which provide fundamental knowledge for success in the remaining subjects - collected using school reports and questionnaires.<i>Techstack</i>: Python 3.7, numpy, pandas, matplotlib, sklearn, seaborn. </li>
<li> I Developed a Linear regression supervised machine learning classification model whose numerical predicted value output ranges from I to V: I-(excellent/very good), II-(good), III-(satisfactory), IV-(sufficient) and V-(fail) based on the Erasmus grade conversion system.</li>
<li> Math class had a <i>0.03548 variance score and 1.887629 root means squared error (RMSE). </i></li>
<li> Portuguese class had a <i>0.09151 variance score and 1.803660 root mean squared error (RMSE). </i></li>
</ul>

<h2> <i>Data</i> </h2>		
❖ Non-pre-processed dataset sourced from:
https://archive.ics.uci.edu/dataset/320/student+performance

❖ There are 33 features/attributes before data preprocessing for both Mathematics and Portuguese classes. The Mathematics class has 395 records while the Portuguese class has 649 records.

<h2> <i>Work Flow</i> </h2>		
STEPS 1
<ul><li>Import libraries</li></ul>
STEP 2
<ul><li>Fetch data and load both mathematics and Portuguese CSV files into separate pandas data frames</li></ul>
STEP 3
<ul><li>Data Wrangling: Transform and Analyse the data.</li></ul>
STEP 4
<ul><li>Determine the Target variable and create an Explanatory variable</li></ul>
<ul><li>Testing and Training data split</li></ul>
<ul><li>Build the Linear Regression model</li></ul>
<ul><li>Run Predictions</li></ul>
STEP 5
<ul><li>Evaluate the Model</li></ul>
<ul><li>Visualise results</li></ul>
