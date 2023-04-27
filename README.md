# Paper-Title: Integration of CNN and GAF for Monitoring/Predicting Cloudburst Events in Uttarakhand, India

This repository contains data and code for the research paper **"Integration of CNN and GAF for Monitoring/Predicting Cloudburst Events in Uttarakhand, India"**. The aim of this research is to develop an accurate and efficient method for monitoring and predicting cloudburst events in Uttarakhand, India using a combination of Convolutional Neural Network (CNN) and Gramian Angular Field (GAF).

The uploaded data includes several files that are used for model training, testing, and validation. The files and their descriptions are as follows:

**Training.ipynb**: This file contains the code used for model training.

**Testing.ipynb**: This file contains the code used for model evaluation.

**API.ipynb**: This file contains the code for an API that is used for continuous monitoring and predicting cloudburst events on the latest data retrieved from IMD using a pre-trained model.

**CB12.npy**: This file contains Cloudburst Training-Testing Data for 12-Hour Early Prediction.

**CB6.npy**: This file contains Cloudburst Training-Testing Data for 6-Hour Early Prediction.

**Model12.h5**: This file contains the pre-trained 12-Hour Early Prediction model.

**Model6.h5**: This file contains the pre-trained 6-Hour Early Prediction model.

| Model-Feature  | 6H Value | 12H Value |
| ------------- | ------------- | ------------- |
| Optimizer | Adam | rmsprop  |
| Kernel Size  | 2,2  | 1,1  |
| Pooling Size  | 3,3  | 3,3  |
| Learning rate | 0.0005  | 0.0005  |
| Epoch | 50  | 50  |

**NB.npy**: This file contains Non-Cloudburst Training-Testing data.

**TEST12.npy**: This file contains Cloudburst Validation Data for 12-Hour Early Prediction.

**TEST6.npy**: This file contains Cloudburst Validation Data for 6-Hour Early Prediction.

These files can be used to reproduce the results reported in the research paper. The code is written in Python and uses popular libraries such as TensorFlow and Keras. The repository can be easily cloned and the code can be run on any machine with the required dependencies installed.

We hope that this research will contribute to the development of more accurate and efficient methods for monitoring and predicting cloudburst events, which can help to mitigate the impact of these natural disasters on the communities in Uttarakhand, India.

Note:- Since, The Training code shuffles the data. The result may vary for the newly trained model.
