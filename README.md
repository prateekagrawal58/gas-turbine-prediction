# gas-turbine-prediction

#### Problem statement:
Predicting Gas Turbine plant's decay state coefficient, two outputs: GT Compressor decay state coefficient and GT Turbine decay state coefficient. Correlation between Decay state coefficients and other parameters is performed.

### Dataset link - http://archive.ics.uci.edu/ml/datasets/condition+based+maintenance+of+naval+propulsion+plants

#### Phases of the project are as follows:

1.Data Preprocessing

2.Exploratory Data Analysis

3.Data Visualization

4.Feature Selection

5.Regression Models

6.Comparative Study



### Results :

#### 1. For Compressor Decay:

Linear Regression - Training Accuracy : 0.843676, Testing Accuracy :  0.840362, Error : 0.163777

KNN -  Training Accuracy : 0.955039, Testing Accuracy : 0.918073, Error : 0.084051

Decision -  Training Accuracy : 1.000000, Testing Accuracy : 0.984062, Error : 0.016351

Random Forest -  Training Accuracy : 0.999092, Testing Accuracy : 0.994253, Error : 0.005896

#### 2. For Turbine Decay:

Linear Regression - Training Accuracy : 0.911244, Testing Accuracy : 0.910862, Error : 0.005896

KNN - Training Accuracy : 0.914175, Testing Accuracy : 0.860251, Error : 0.005896

Decision - Training Accuracy : 1.000000, Testing Accuracy -  0.958500, Error : 0.005896

Random Forest - Training Accuracy : 0.998257, Testing Accuracy : 0.988999, Error : 0.005896
