Fish Species Prediction using KNN 

Overview
This project predicts the species of a fish based on its physical characteristics such as weight, length, height, and width using the **K-Nearest Neighbors (KNN)** classification algorithm.


 Dataset
Dataset Source: Kaggle - Fish Market Dataset  

Columns:
- Species  
- Weight  
- Length1, Length2, Length3  
- Height  
- Width  

 Steps Performed
1. Imported and explored the dataset  
2. Checked for missing values and cleaned the data  
3. Converted all numeric columns to integers  
4. Trained a KNN model (`n_neighbors=15`, `metric='manhattan'`)  
5. Tested prediction on sample input  
6. Evaluated model accuracy using `.score()`  

