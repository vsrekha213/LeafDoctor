# LeafDoctor - Detect Diseases in Plant Leaf
#### The objective of this project is to identify the type of diseases in the plants, so that it can be treated as soon as they appear.

#### Data Set can be found here : https://www.kaggle.com/emmarex/plantdisease

# Data Set Description
#### The data set consists of 14 different diseases of the plants like **pepper bell bacterial, pepper bell healthy, toamato late blight, early blight** etc...

# Model Training
#### Model architecture used is as follows :
## 1. Feature Extraction
1. Convolution(32 -> 3 X 3)
2. Normalization
3. Pooling(Max)
4. Dropout
5. Convolution(32 -> 3 X 3)
6. Normalization
7. Pooling(Max)
8. Dropout

## 2. Classification
1. Dense Layer (1024)
2. Activation used here is # Softmax


# How to Use this Source Code
1. clone this repo
2. First install required tf packages and before that ensure to create separate conda environment and make sure tf version is 2.2
3. Run app.py file
5. To do prediction download 'model.h5' {you can directly uses this file for prediction}
