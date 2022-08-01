# Neural_Network_Charity_Analysis

## Overview

The purpose of this project is to analyze and classify the success of charitable donations using deep-learning neural networks and the TensorFlow platform in Python.

## Resources

  - Data Source: charity_data.csv
  - Software: Python 3, Anaconda Navigator, Conda, Jupyter Notebook.
  
## Results

### Data Preprocessing

  - Columns EIN and NAME contain identification information and have been removed.
  - Column IS_SUCCESSFUL holds binary dossier refering to weither a suggestion of correction the charity gift was secondhand effectively. This changeable is before considered as the aim for our deep education interconnected system.
  - The following columns APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT are the looks for our model. Encoding of the unconditional variables, spliting into preparation and experiment datasets and uniformity have happened used to the features.
  
### Compiling, Training, and Evaluating the Model
  
  - Initially, the model was devised accompanying the Relu Acitivation function, as we are handling a complex dataset that has abundant inputs/lineaments. Relu is mainly a good beginning for complex datasets. Additionally, we built two tiers. The first contained 18 neurons, as skilled 9 countenance inside the dataset (9x2). We additional an supplementary coating accompanying 9 neurons (half of the first tier).
  - We set a target performance of 75%, and our model fell just short (with an accuracy level of 72.6%).
  - In an attempt to increase accomplishment, we devised an automobile optimzer function to reckon highest in rank combination of tiers and neurons accompanying the optimum incitement function. This only a little raised the conduct of our model, still, happening in an accuracy of 72.7%.

## Summary

The deep learning neural network model did not reach the target of 75% accuracy.Given that this target level is pretty average, we could say that the model isn't outperforming. As we are dealing with a binary classification situation, a supervised machine learning model such as the Random Forest Classifier could be used to combine multiple decision trees and produce a classified output. With supervised machine learning, such as Random Forest Classifier, we can combine a multitude of decision trees into a classified output and compare it to our deep learning model.
