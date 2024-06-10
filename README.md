# capstone_project
Capstone Project
This project proves statistical significance using datasets from Kaggle.com (https://www.kaggle.com/datasets/emirhanai/social-media-usage-and-emotional-well-being)
The research question was "Is there a significant relationship between a users social media usage and their reported dominant emotion"
The data sets were checked for null values of which there was 1. This value was dropped.
Various visualizations were used to showcase the distribution of the data as well as any relationships between the variables.
The Dominant_Emotion column was encoded because it was the categorical variable that was targeted and was not binary in nature.
The train dataset was split to use as a training and test set for Logistic Regression and Random Forest Classifier.
Both the Logistic Regression and the Random Forest models were evaluated with confusion matrices and classification reports. The Logistic Regression model had moderate performance but was able to showcase statistical significance with p-values less that 0.05 for different variables (this was further split by the dominant emotion encoded. There is a portion of code that shows a map between the dominant emotion and the encoded value used). The Random Forest model had a much higher overal accuracy of 97% with the prediction of a users dominant emotion.
The models were then cross validated to ensure accuracy and the relevant information was saved back as CSV files to be used for further visualization in Tableau.
