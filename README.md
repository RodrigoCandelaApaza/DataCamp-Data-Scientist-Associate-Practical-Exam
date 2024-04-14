In this repository I show the process I followed to successfully approve the DataCamp's Data Scientist Associate Practical Exam. 
Here I list some recommendations:
1. Write your code in just one cell, the one they ask you to. If you need to view some outputs, you can use more cells, but after you've got your desired result, move your code to the required cell.
2. Watch for undercovered missing values. While practising, I got the first item in the rubric (about missing values correction) not marked as completed. While searching, I found that in some columns there where values as '.', '-' or '--', which where not recognized as missing.
3. In one of the activities you may be required to create a DataFrame with a numeric variable grouped by a categorical variable, and compute its mean and variance. Don't forget to use the reset_index() method so your first column is actually a column and not an index.
4. In the modelling part, use it is not necessary to split the train.csv data in train and test. Splitting it in X and y is enough. Fit your model in that X and y, and then use the validation.csv to get predictions on the model.
5. In the modelling part, the transformation you do to the train.csv data should be the same you do to the validation.csv data.
