# DataMining_TorontoSocioeconomicClassification
Jupyter Notebook | Scikit-learn | Weka | ArcGIS

   The objective of this study is to explore the existing relationships between people's residential locations and
their socio-economic characteristics to attempt to make suitable residential location predictions or recommendations 
on GTA census subdivisions based on individual's or household's socio-economic status. The case study will implement 
various data mining classification techniques for area prediction along with the support use of ArcGIS software for 
raw spatial database development.

The overall workflow of GTA residential location suitability classification study is illustrated as follows:
1. Identify useful socio-economic characteristics dataset at the largest available geographic scale (Census Tract - CT)
2. Identify available smaller scale boundary dataset at the largest useful scale (Census Subdivision - CSD)
3. Each unique Census Tract with selected socio-economic characteristics is acted as a data instance with attributes where its               agglomerated Census Subdivision is acted as a classification.
4. Census Tract socio-economic datasets are collected and joined with matching Census Subdivision boundary dataset using ArcGIS spatial       software as raw database.
5. The raw spatial database is then exported as a CSV file for further data preprocessing dealing with missing values, feature               selection and data transformation.
6. Once the database is normalized, the database is split into training and testing instances and implemented through various data           mining classification models including decision tree, Naive Bayes, linear perceptron, logistic regression and ensemble boosting for       further classification performance evaluations.
