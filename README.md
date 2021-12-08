# Credit-Card-Fraud-Detector
Has a GUI which provides an intuitive way to detect fraudulent transactions to help understand the patterns of fraud and thereby predict if a fraud is likely to happen

Go to my repository and download the following files:
		
		1. main.ipynb
		2. main_feature.ipynb
		3. creditcard1.csv
		4. creditcard2.csv
		
#--------------------------------------------------------------------------------------------------------------------------#
After downloading all the files, make sure that you have anaconda - jupyter installed on your laptop.
Now, there are two ways this code can be executed. 
		1. Run main_feature.ipynb file in jupyter. (Note : change the directory to the one where you have your creditcard2.csv)
		2. Run main.ipynb

#--------------------------------------------------------------------------------------------------------------------------#

Running main_feature.ipynb gives you a direct classification accuracies without any interface to see.
Running main.ipynb gives you a Graphical-User-Interface where we can do all sorts of operations like uploading data, testing fraudulent transactions and plots.

Note: In main.ipynb, there is usage of 'tkinter' which might need additional installation from console ~ (USE pip install tkinter) in conda command prompt
			In main_feature.ipynb there is usage of 'xgboost' and 'termcolor' libraries which need additionnal installation from console ~ (USE pip install xgboost and pip install 																																																																					termcolor) in conda command prompt
                                        #-------------------------------------------------------------------------------------------------------------------------#

DataSet can be downloaded from the below address:
https://www.kaggle.com/radhauppuganti/credit-card-transactions-train-set
