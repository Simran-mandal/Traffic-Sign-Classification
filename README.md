# Traffic-Sign-Classification

**********************************************
The German Traffic Sign Recognition Benchmark
**********************************************
-- For this project we have used The German Traffic Sign dataset.
-- In the Training dataset, there are a total of 43 categories (classes) and 39,209 .ppm images
-- The Test set consists of 12,630 .ppm images.
-- All of the code i.e. Exploratory Analysis, Data Pre-Processing and Model Implementation have been executed in one single .ipynb file.
-- The .zip file contains one ML_CW2 folder and one .ipynb file.
-- The ML_CW2 folder contains five files in total -- Training Set, Testing Set, PictureOutput, Tmp file and a Test .csv file

**********************************************
Accessing The Dataset
**********************************************
-- In order to run the .ipynb file directly, please upload the ML_CW2 file in your Google Drive. 
-- If the first suggestion is not an option, then necessary changes will have to be made in the code (change directories)

**********************************************
About the Project
**********************************************
Below are the steps that are covered in the code section of the project:
1. Loading the datasets.
2. Carrying out exploratory analysis and visualisation of the training set.
3. Images are then converted to Greyscale for the model to be trained efficiently.
4. Loading and preprocessing includes Normalisation, Histogram Equalisation, Scaling, Reshaping, Resizing of images.
5. Converting the image to a numpy array to process the images.
6. A Sequential ConV2D model has been used for classification.
7. The trained model is then used to make predicitions on GTSRB_Final_Test_Images.
8. Predicitons are then eveluated and visualised with the actual labels (Category Names)
