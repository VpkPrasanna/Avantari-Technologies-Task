# Avantari-Technologies-Task
Technology Task

Build on top of keras using Transfer Learning 

Pre trained model like VGG16 or Xcetption net can be used to extract features form the images

Steps Followed 

* Read all the images and convert to numpy array
* Initialize the pre-trained Model 
* Extract Features using the pre-trained Model
* Save the features in a confortable way i have save the extracted features in a dataframe with image Name as index and features as the columns
* Extract features from the query image
* Define the similarity function to find the similarity between two features 
* Compute similarity between all the features with the given query image
* Fetch the top 10 similar values based on the similarity (10 is for just demo choose any number you want)



To run for now run all the cells with required changes 
Changes: Change the query image and run the cells 
