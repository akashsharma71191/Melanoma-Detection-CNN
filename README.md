# Project Name
> Melanoma Detection


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
- Problem Statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Conclusions
- Model 1:
 Training Accuracy: 87.11
 Validation Accuracy: 52.12
 The accuracy is just around 85-90% because there are enough features to remember the pattern.
 From the graph we can see training accuracy is very high as compared to validation accuracy. We can also see difference in loss functions in training and validation data around 19th and 20th epochs. This is a clear case of overfitting where model has learned too much from training dataset and it is not able to perform well on the validation dataset.

- Model 2:
 Training Accuracy: 58.37
 Validation Accuracy: 53.69
 There is no improvement in accuracy but we can definitely see the overfitting problem has solved due to data augmentation
 We can increase the epochs to increase the accuracy so it's too early for judgement

- Model 3:
 Training Accuracy: 95.14
 Validation Accuracy: 81.51
 Accuracy on training data has increased by using Augmentor library
 The model is not overfitting. This model can be used as final model.
 It ca be further improved by add more layer,neurons or adding dropout layers.


## Technologies Used
- matplotlib
- tensorflow
- Keras
- pandas
- os


## Contact
Created by Akash Sharma


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->