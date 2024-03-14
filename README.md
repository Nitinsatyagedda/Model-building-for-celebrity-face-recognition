# Model-building-for-celebrity-face-recognition
This is an open-source project repo deals with extracting the pictures of the celebrity from the google as a sample dataset, preprocesssing like cleaning the image using openCV, model building and model evaluation.

# objective
The goal of this project is to develop a model that can classify the picture of the celebrity. This involves preprocessing the picture and croping the picture. With the help of the cropped pictures we train the model along with the wavelet transform images.
# Task
1. Data Preprocessing: This task involves cleaning and preparing the image.
   The preprocessing is done in the following steps
     1. Detect face and eyes
     2. Crop the facial region of the image
     3. Use wavelet transform as a feature for traning our model
     4. Load image, detect face. If eyes >=2, then save and crop the face region
2. Model buliding: This task involves the images in cropped folder can be used for model training. We will use these raw images along with wavelet transformed images to train our classifier.
3. Model evaluation: Access the peroformance of the model using appropriate evaluation metrics. This step is crucial to ensure the model's accuracy and effectiveness.

# Model Building
Models used for comparison are listed below.
1. Logistic regression
2. SVM
3. Random Forest

# Technologies used in this project
1. Python
2. Numpy and OpenCV for data cleaning
3. Matplotlib & Seaborn for data visualization
4. Sklearn for model building
5. Jupyter notebook as IDE
