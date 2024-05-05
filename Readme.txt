Installation: This code can be directly run on google collab, please upload the ipynb files along with edgehistogram and images files provided by us

In this code, we attempt to train and evaluate various machine learning models for image classification. 

---->>>

NOTE: In the Edgehistogram.csv, we removed the number of rows from the image.csv and divided the data into columns because of the modification Use the given files use the given files.


-----------------------------------------------------------------------------------------------------------------------------
To accomplish this, the code goes through several steps, including reading and cleaning the data, splitting it into training and testing sets, and fine-tuning the model's hyperparameters to achieve the best performance. Finally, the models' performance is evaluated and saved in a dataframe for comparison.The code reads two datasets, "EdgeHistogram.csv" and "Images.csv", and concatenates them into a single dataframe "Concate DF".

The image features are contained in the "EdgeHistogram.csv" file, and the image labels are contained in the "Images.csv" file. 

The code also checks for missing values in the data and uses descriptive statistics to better understand the data.

The function "HyperparameterTuning" in the code performs random search hyperparameter optimization to find the best parameters for a given model. 

Another function, "get performance," in the code, trains the model with the best parameters and returns its performance in terms of accuracy, precision, and F1 score.

-------------------------------------------------------------------------------------------------------------------------------

Execution: Upon executing given in the .ipynb file, output can be seen generated in the ‘Performance Of Model with preprocessing.CSV’ and ‘Performance Of Model without preprocessing.CSV' files.