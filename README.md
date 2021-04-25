# Deep-Learning-Food-Classification
Jupyter Notebook, Tensorflow GPU 2.4.1, CUDA

### For reader information
The notebook has been shut down around 3 times a day,mostly due to problems in hardware, models are saved when need and loaded when needed, also the numbers of the cells final document is NOT the actual path of execution. The Notebook was not restarted at any time so the output of the cells can be kept.

1. The data is not included - 5.45 GB
2. There is no cached data - 115 GB (only indexes are kept)
3. The saved models are not included 19 models are 5.33 GB (best model CNN-16 315 MB)
4. The logs are not included 171 MB of data for 21 models.
5. The documet is done for about 290h of PC working time and 120h - 130h work done by me and I have to apologize for typos.
*Enjoy.*

#### The goal of our with is to try make a model that will succsesfully tell the food type based on an image. That model can be used for example an android app on your phone. Imagine you are somewere far from home looking at some dish like it and you would like to know what is it, so you just take a picture and the app tell you... Well that the idea at least.

#### With the vast veriety of dishes and how any different person cooks it the classification can become a nightmare so we will "only" try to classify 101 type of food. We will use a very popular Data Set in Kaggle Food 101, and hopefully create a good Convolutional neural network model, after that comape to others work on this Data set and one Trained working model (VGG19) and finaly we will try tranfer learning with it.

### Our goal is to predict corectly at least every 2 of 3 Dishes.

### 101 Classes - 101000 images

Content:

1. Introduction 
2. Get Data
3. Pepair the data for modeling.
4. Hardware and Model Choosing.
    1. Hardware
    2. Model Choosing
4. Crating a Convolutional neural network model.
    1. CNN-1
    2. CNN-2
    3. CNN-3
    4. CNN-4
    5. CNN-5
    6. CNN-6
    7. CNN-7
    8. CNN-8
    9. CNN-9
6. Adding Test Dataset
7. Continue with Convolutional neural network model
    1. CNN-10
    2. CNN-11
    3. CNN-12
    4. CNN-13
    5. CNN-14
    6. CNN-15
    7. CNN-16
8. Impoving Training
9. Tuning the best models  
    1. CNN-10
    2. CNN-15
    3. CNN-16
10. Tranfer Learning
    1. TL model 1
    2. TL model 2
    3. VGG19 TL model
        1. Create VGG19 transfer model 
        2. Data VGG19 transfer model 
        3. Train VGG19 transfer model
11. Use the base VGG-19 Model
12. Test he best model
13. Compare results
14. Conclusion
15. References
