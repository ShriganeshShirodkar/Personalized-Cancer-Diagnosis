# Personalized-Cancer-Diagnosis

 Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/

![15227808895bf7a8d712006fe5e629f46c05bb72e6](https://user-images.githubusercontent.com/36497538/54810792-00eb8900-4cad-11e9-8609-d0cc0810fab4.jpg)

Data: Memorial Sloan Kettering Cancer Center (MSKCC)

Download training_variants.zip and training_text.zip from Kaggle.

Context:
Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/discussion/35336#198462

## Problem statement : 
Classify the given genetic variations/mutations based on evidence from text-based clinical literature.

## Real-world/Business objectives and constraints.
No low-latency requirement.
Interpretability is important.
Errors can be very costly.
Probability of a data-point belonging to each class is needed.

### Machine Learning Problem Formulation
We have two data files: one conatins the information about the genetic mutations and the other contains the clinical evidence (text) that human experts/pathologists use to classify the genetic mutations.
Both these data files are have a common column called ID

### Data file's information:
training_variants (ID , Gene, Variations, Class)
training_text (ID, Text)

### Performance Metric
Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment#evaluation

Metric(s):
Multi class log-loss
Confusion matrix
