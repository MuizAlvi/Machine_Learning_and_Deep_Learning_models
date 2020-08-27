# Machine_Learning_and_Deep_Learning_models

Repository containing models based on ideas of Machine learning and Deep learning. List of files:

1. Simple Sequential Model
    - Uses randomly generated trainin set (10% of which is used in validation set) and test data
    - Shows final predictions in a confusion matrix
    

2. Cat and Dog Classifier - Convolution Neural Network
    - Uses a data set of 1300 images (1000 for training set, 200 for validation set, 100 for test set) randomly picked out of a larger data set of 25000 images
    - Image Data: https://www.kaggle.com/c/dogs-vs-cats/data (25000 images of cats and dogs)
    - Model experiences overfitting and needs to be improved
    - Model has not been tested for now due to overfitting on the training set
    

3. Cat and Dog Classifier 2.0 [using existing model] - Convolution Neural Network
    - Trains existing model VGG16 (with some alterations)
    - Uses data prepeartion used in the previous upload (Cat and Dog Classifier - Convolution Neural Network)
    - Highly accurate model with no overfitting
    
    
4. Image Classification [using existing model] - MobileNet
    - Importing a pre-trained model and testing its ability of identify sample images
    - This model is broader than the Cat and Dog Classifiers previously uploaded
    - It tells percentage of possible assumptions of an object present in an image provided to it

5. Sign Language Digits Classification [using fine tuned existing model] - MobileNet 
    - Uses dataset https://github.com/ardamavi/Sign-Language-Digits-Dataset
    - Makes use of pre-existing model 

6. Data Augmentation
    - Creates data from a single image to be processed by a neural network
    - Image is rotated, flipped, shifted e.t.c to produce a set of more images
