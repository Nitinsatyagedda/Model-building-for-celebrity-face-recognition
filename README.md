# Model-building-for-celebrity-face-recognition
This is an open-source project repo deals with extracting the pictures of the celebrity from the google as a sample dataset, preprocesssing like cleaning the image using openCV.
Technologies used in this project,

1. Python
2. Numpy and OpenCV for data cleaning
3. Matplotlib & Seaborn for data visualization
4. Sklearn for model building
5. Jupyter notebook as IDE

We have done the preprocessing in the following steps
1. Detect face and eyes
2. Crop the facial region of the image
3. Use wavelet transform as a feature for traning our model
4. Load image, detect face. If eyes >=2, then save and crop the face region
