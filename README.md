# Case_Study_SVM
all python project
#Problem Statement:-
Based on the dataset where we have to classify the cellular localization sites of proteins. Here we are working on the dataset with various features which are the dimensions and singles given by the business we have to create the classification algorithm using support vector machine

#Data Dictionary:-\

Sequence Name - Accession number for the SWISS-PROT database\

mcg - McGeoch's method for signal sequence recognition\

gvh - von Heijne's method for signal sequence recognition\

alm - Score of the ALOM membrane spanning region prediction program\

mit - Score of discriminant analysis of the amino acid content of the N-terminal region (20 residues long) of mitochondrial and non-mitochondrial proteins\

erl - Presence of "HDEL" substring (thought to act as a signal for retention in the endoplasmic reticulum lumen). Binary attribute\

pox - Peroxisomal targeting signal in the C-terminus.\

vac - Score of discriminant analysis of the amino acid content of vacuolar and extracellular proteins.\

nuc - Score of discriminant analysis of nuclear localization signals of nuclear and non-nuclear proteins.\

YeastType - This is the dependent variable

Table of Content
Import Libraries\
Data Preparation\
2.1 - Understand the Data\
2.2 - Exploratory Data Analysis\
2.3 - Missing Value Treatment\
2.4 - Encoding and Feature Scaling\
What is Support Vector Machine\
3.1 - Types of Kernel\
3.2 - Where to use which kernel\
3.3 - Different Hyper parameters for different kernels\
3.4 - How the value of C, Gamma will impact the model (Overfitting and Underfitting)\
Splitting the data into Train and Test\
Creating the model on training dataset\
Run the model on the Test Dataset\
Check the accuracy of the model\
7.1 - Accuracy Score\
7.2 - Confusion Matrix\
7.3 - ROC Curve\
7.4 - F1 Score\
7.5 - Log Loss\
Comparing the Training and Testing Accuracies\
Applying Grid Search Cross Validation to find the best value of Hyper Parameters
