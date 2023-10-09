# Syntactic Processing Assignment 

> ‘BeHealthy’ has a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organise appointments, track past medical records and provide e-prescriptions.

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

- In this assignment, you need to perform the following broad steps:

  - You need to process and modify the data into sentence format. This step has to be done for the 'train_sent' and ‘train_label’ datasets and for test datasets as well.
  - After that, you need to define the features to build the CRF model.
  - Then, you need to apply these features in each sentence of the train and the test dataset to get the feature values.
  - Once the features are computed, you need to define the target variable and then build the CRF model.
  - Then, you need to perform the evaluation using a test data set.
  - After that, you need to create a dictionary in which diseases are keys and treatments are values.

## Conclusions

- Predicted F1-score is: 91.53 % for custom NER(Named entity recognition) with CFR(Conditional random fields) model.


## Technologies Used

- spacy
- pandas
- sklearn_crfsuite


## Contact

Created by [@pulkitgangwar](https://github.com/pulkitgangwar) - feel free to contact me!
