# deep-learning-challenge
This assignment was done by myself, but with the aid of internet resources. 


## Analysis Objective

The objective of this study was to develop an advanced computational model capable of forecasting the prosperity of enterprises backed by Alphabet Soup. Utilizing a dataset encompassing diverse attributes of these enterprises, the aim was to categorize them as either likely to thrive or not. This document delineates the procedures for data preprocessing, the design of the artificial intelligence model, its efficacy, and avenues for enhancing its performance.

## Findings

## Data Preparation

Dependent Variable(s): The focal point for the model was a binary variable denoting the success status of the enterprise.

Independent Variable(s): The model integrated assorted attributes of the enterprises, such as their classification, revenue magnitude, application method, and others, post preparation.

Excluded Variables: The EIN and NAME fields were excluded from the dataset as they serve as identifiers and don't contribute to the model's predictive capacity.

## Model Compilation, Training, and Assessment

Neural Architecture and Activation Mechanisms: The neural network structure comprised multiple strata, encompassing input, covert, and output layers. The primary covert layer featured a substantial neuron count employing a relu activation mechanism to capture nonlinear correlations within the data. A secondary covert layer was introduced to deepen the model, potentially enhancing its prognostic prowess. The output layer employed a sigmoid activation mechanism suitable for binary classification scenarios.

Model Performance: The model registered a loss of 0.5588 and an accuracy of 0.7280. Though the accuracy surpasses 70%, there exists room for enhancement to attain the target predictive accuracy exceeding 75%.

Optimization Endeavors: Diverse tactics were implemented to bolster model performance, including adjustments to neuron counts in the layers, incorporation of additional covert layers, exploration of varied activation mechanisms, and modification of epoch counts during the training regimen.

## Synopsis
The deep learning model devised for Alphabet Soup exhibited a promising capability to forecast the success of funded enterprises with an accuracy rate of approximately 72.80%. Nonetheless, it fell short of achieving the target accuracy threshold of over 75%.

## Recommendations for Model Enhancement

Augmented Data Preparation: Further refinement of data could unveil supplementary insights or diminish noise, such as more assertive management of outliers or crafting of more illuminating variables.

Exploration of Model Architecture: Introducing additional covert layers or neurons might amplify the model's ability to glean insights from the data. However, caution must be exercised to avert overfitting.

Alternate Models: Exploring alternative models like Random Forest or Gradient Boosting could yield superior performance owing to their distinct learning methodologies. These models can decipher intricate patterns in the data sans the overfitting risk inherent in deep learning models.

In summary, although the neural network model exhibits promise, additional optimization efforts and exploration of alternative models are recommended to achieve heightened predictive accuracy.
