# Covid 19 Prediction for Machine Learning Project

## Description of the Project

The data used in this project will help to identify whether a person is going to recover from coronavirus symptoms or not based on some pre-defined standard symptoms. These symptoms are based on guidelines given by the World Health Organization (WHO).</br> </br>
This dataset has daily level information on the number of affected cases, deaths and recovery from 2019 novel coronavirus. Please note that this is a time series data and so the number of cases on any given day is the cumulative number.</br> </br>
The data is available from 22 Jan, 2020. Data is in “data.csv”. The data is cleaned and preprocessed. </br> </br>
The dataset contains 14 major variables that will be having an impact on whether someone has recovered or not, the description of each variable are as follows: </br>

<li> Country: where the person resides
<li> Location: which part in the Country
<li> Age: Classification of the age group for each person, based on WHO Age Group Standard
<li> Gender: Male or Female
<li> Visited_Wuhan: whether the person has visited Wuhan, China or not
<li> From_Wuhan: whether the person is from Wuhan, China or not
<li> Symptoms: there are six families of symptoms that are coded in six fields.
<li> Diff_Sym_Hos
<li> Result: death (1) or recovered (0)
</br> </br>

## Project Task
The Project Goal was to design different classifiers to the predict the outcome (death/recovered) when a new person is admitted to the hospital. </br>

I divided the data into three partitions: training, validation, and testing then I designed the following classifiers: </br>

<li> K-Nearest Neighbors
<li> Logistic Regression
<li> Naïve Bayes 
<li> Decision Trees
<li> Support Vector Machines 

For each classifier, I got the optimal hyperparameters as well as comparing the performance of all classifiers using different metrics such as the precision, recall, F1-score, and ROC/AUC curves.
