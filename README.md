# Traffic-Sign-Classification

Link for the data -  https://sid.erda.dk/public/archives/daaeac0d7ce1152aea9b61d9f1e19370/published-archive.html
**********************************************
The German Traffic Sign Recognition Benchmark
**********************************************
-- For this project we have used The German Traffic Sign dataset.
-- Download files (GTSRB_Final_Test_Images.zip) and (GTSRB_Final_Training_Images.zip)
-- In the Training dataset, there are a total of 43 categories (classes) and 39,209 .ppm images
-- The Test set consists of 12,630 .ppm images.
-- All of the code i.e. Exploratory Analysis, Data Pre-Processing and Model Implementation have been executed in one single .ipynb file.

**********************************************
Accessing The Dataset
**********************************************
-- In order to run the .ipynb file, download the above GT_final_test.csv in the folder which contains unzipped GTSRB_Final_Test_Images and GTSRB_Final_Training_Images
-- Make 2 empty folders in the same folder which now has the training images, testing images and .csv file, which are "Tmp_Data" and "pictureOutput" 

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
