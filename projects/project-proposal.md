# CSX460 Project Proposal

Team Member(s): Jennifer Borkowsky


## Model Objective

I will build models to predict the level of 2 blood biomarkers associated with asthma - periostin and eosinophils.  It is known that patients with high levels of one or both of these biomarkers respond best to a new drug.  Understanding predictors of higher levels of these biomarkers will help identify patients who could benefit most from treatment, without costly and time consuming blood assays to measure the biomarkers directly.

* What do you expect to achieve with the model?
I expect to build a model with high accuracy to predict biomarker level (high/low) given the independent variables 

* How will you measure its performance?
Performance will be measured by logistic model accuracy and sensitivity


## Data Source(s)

* What are the data sources for the model?
* How will you obtain the data?

Data will be obtained from a database of a clinical trial investigating a new drug on asthma patients.  Data will contain information on ~2000 patients.



## Response

* What it the response variables?
The response variable is blood periostin level (high/low)

* Are there any surrogate response variables?
I will also build a model to predict another blood biomarker level (eosinophil count).


## Expected Features

* What are some of the feature you expect to use?


## Models

* What modeling Techniques do you plan on trying?

I will build  a logistic model.

* How will you compare the models

Models will be compared using measures of preformance such as accuracy and sensitivity


## Deployment

* Who will use the model?

Physicians could use such a model to identify patients who would have a greater likelihood of benefiting from a particular immunotherapy currently under testing.  It would save much time and money if this identification could be accurately done using a patient's baseline characteristics rather than expensive lab testing of the biomarkers directly.

* How will the use it?

The model will be used to predict a patient's biomarker levels given a set of baseline data. 


## Miscellaneous

* What do you expect to learn from this Project?

I hope to:
1.  get more comforatable builing predictive models
2.  gain more experience using R
3.  explore different modeling techniques
4.  learn about model deployment