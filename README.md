# IPL-Score-Prediction


**Goal of the Project --->**
         To predict the 1st Innnig Score in IPL matches based on the prior macth results
         
         
         
**Data Collection --->**
         Kaggle - https://www.kaggle.com/lazycoder00/ipl-dataset-20082019
         
         
**Exploring Data & Data Pre-processing & EDA --->**
         Checking Null Values
         Finding out and dropping the less significant Columns in Dataset
         Removing the Teams which are not playing and keeping the consistant ones only
         To get a flow of the match , taking scores after Powerplay ( Overs > 5 ) only
         Used **OneHotEncoding** to convert Categorical Features
         Re-arranging the columns - putting the predictable Variable ( Total ) in last
         Splitting the data into Train & Test sets
         
         
**Model Building ---->**
        used **Linear Regression** to build a model
        
        
**Visualization --->**
        Used **Seaborn** to plot the predicted Values against the Real values in Test data
        
        
**Evaluation --->**
        Imports **Evaluation Matrices ( MAE, MSE & RSME ) from ScikitLearn** and found out the accuracy
         
         
