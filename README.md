# Driver-Distraction-Detection


  
Repository contains CNN model and script for detecting and uploading driver violations to cloud
Thingspeak Channel ID: 1040543 
Channel has 4 fields ,field1: Driver ID 
              field2: GPS COORDS 
              field3: Offence 
              field4:Image data
flip horizontal horizontally flips and writes back all the images in a folder
LHS_drive and RHS_drive contains script for training the model on dataset from state farm data set in kaggle
main_with_cloud_LHS_Drive & main_with_cloud_RHS_Drive contains driver code for loading,predicting on a video file and uploading to cloud
