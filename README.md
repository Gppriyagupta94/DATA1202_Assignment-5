# DATA1202_Assignment-5
**Project Title** 
Clustering 
**Description of the Project** 
We have collected data of cancer patients and using the Elbow and Silhouette methods of clustering we will optimize our K -means model to segment homogeneous symptoms found in one set of patients through all variables and differentiate them from heterogeneous symptoms found in other patients in order to further identify which patients can be treated using the similar medical treatment and which patients must be treated differently.
**Prerequisites and Installing**: 
Python (Anaconda) Install Procedure
Python Program Install
1) Go to the Anaconda website for downloads - https://www.anaconda.com/products/individual (the
Anaconda installers will be near the bottom of the page)
2) Download the appropriate latest version of Anaconda (64-bit graphical installer for Python 3.8 version)
3) After your install is complete, verify it by opening Anaconda Navigator:
From the start menu, select Anaconda3(64-bit), then select Anaconda
Navigator. If Navigator opens, you have successfully installed Anaconda.
4) Now close the Anaconda Navigator application
Python Libraries Install
5) Launch Command Prompt
Open the Anaconda Prompt (start menu under Anaconda3(64-bit))
6) Enter the following commands one at time and wait for each install to complete running.
 pip install plotly
 pip install imbalanced-learn
 pip install mlxtend
 pip install pandas-profiling
 pip install Boruta
7) Close the Anaconda Prompt/Terminal App
Final Step
Create a folder under Documents
**Running the Test**: 
To run the test the first step is to load the libraries:
1) Import pandas as pd
2) Import numpy as np
3) Import matplotlib as plt
Then we have to load the dataset 
leuanalysisNewdata = pd.read_csv('./leuanalysisNew.csv')
