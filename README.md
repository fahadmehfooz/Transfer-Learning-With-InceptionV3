# Transfer-Learning-With-InceptionV3: Project Overview 

* Classifying different images of cats into the following categories : Bombay, Calico, Burmese, Himalayan, Munchkin, Ragdoll, Siberian, British Shorthair, Russian Blue, and Dilute Calico.
* Trained the model on 11740 images.
* Dealt with class imbalance.
* Transfer learning is applied to train the model.

## Code and Resources Used 
**Python Version:** 3.9.0
**Packages:** pandas, numpy, sklearn, matplotlib, seaborn, tensorflow, keras  

## Data Used
** Data taken from kaggle : https://www.kaggle.com/ma7555/cat-breeds-dataset

## Data Wrangling and Data Visualization
** Preparing the image path and storing them in a dataframe along with their labels.
** Shuffling the data, so that a better split of train test data is made later on.
** Checking class imbalance.
** Visualizing the distribution of classes and the pictures of cats.
** Augmenting the data using an image data generator.

## Model Building 

First, I took a split on the data with training data as 75%. Then I chose the pretrained models to train on my data.
 
I tried different models of transfer learning like InceptionV3, mobilenet and resnet50. However, I was getting the best results for InceptionV3.

## Model performance

** Results:

** ROC- AUC score is 90.48826764106751
** F1 score is 63.3240142985375 %
** Test accuracy is :  65.844064950943 
