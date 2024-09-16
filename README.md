# ImageClassifierPro
Learning image classification through ands-on projects using various machine and deep learning models and techniques.
 ### Objective
This repository explores various models we can use for image classification from, the famous machine learning models to deep learning models

-To start we explore machine learning models, like RandomForestClassifier, KNN, Decision Tree Classifier and NaiveBayes Classifier
-Also, this repository utizes the  CIFAR-10 dataset - which includes ten classes (airplane, automobile,bird,cat,deer,dog,frog, horse,ship and truck) which makes the problem a multi-class problem.

![image](https://github.com/user-attachments/assets/ffdaeb9c-3c8c-4dc3-b727-9cb71b2e79ab)

### Steps
#### Data Preprocessing
1. Normalizing of teh images by simply dividing the x_train of the train datset by 255.0 and x_test by 255 for teh test dataset.
   
2. Reshaping the images of the dataset to a tow-dimensional array this is because sklearn expects a 2D array as input to the fit() function
   -This process is very essential when using machine learning for image classification

#### Implementing the Machine Learning models
 - The models used include
   1. RandomForestClassifier
   2. KNN
   3. DeciionTreeClassifier
   4. NaiveBayesClassifier

The above models all perform very pooryly with an average accuracy 30%, hyperparameter tuning improve the performances of the models but first let's try deep learning models.

### Implementing ANN Model
Fort this , data preprocessing is done ( Normalization) as the image data has to be normalized, in this unlike the Machine Learning models, there is no reshaping of theimages of teh dataset since the deep learning models are more flexible.

The model performs slightly better than the machine learning models with an accuracy of 48%.


  

