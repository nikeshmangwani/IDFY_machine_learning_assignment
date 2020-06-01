# IDFY_machine_learning_assignment
This code is for the assignment given by IDfy . Number Recognition from NumberPlate Images 
IDFY given Training dataset contains 652 Number plate images , task is to identify accurately recognize Alphanumeric Characters 

Inside jupyter notebooks folder we have 3 Notebook files:

1.Data_Distribution.ipynb : To explore Data and frequency of Given Characters inside the Training Data
2.Image_Dataset_Preparation.ipynb: To make dataset for training from the given images using Character Segmentation
3.training_on_idfy_cropped_dataset.ipynb: Contains Deep CNN Neural Network training code 

Results :
1.We got 99.84% Accuracy on Validation Dataset

2.We Got 96.63% Accuracy on Test Dataset

Results are inside result_csv folder Where we have 4 Files

1. True_Prediction.csv : Correctly predicted Licence Numbers
2. test_df_idf.csv : Unseen testing Data Seperated from the Training Data contains 131 images location
3. distorted_images.csv : Because of poor Quality of Images . Character Segmentation cannot work on Blurred images
4.total_prediction: Unseen testing Data Seperated from the Training Data Prediction results

