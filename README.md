# House-Rent-Prediction-with-LSTM

* I used house rent dataset from Kaggle in this project.  
* There are 12 columns. Details can be seen in the notebook.

# Preprocessing the dataset 

* There are no missing values. 
* Area Type, City, Furniture Status, Tenant Preferred fields convert string to integer using map function. 

# Build the Model 

* I used LSTM in this project. 
* This model has 4 layers 2 of them LSTM layers, 1 hidden layer and 1 output layer. 
* I used Adam as an optimizer and Mean Squarred Error as an Loss Function. 
* I used 1 batch size and 21 epochs. 

# Evaluate the model 

* After training the model, Loss value was 4774934016. 
* According to the Mean Squared Error, the minimum loss value is the best. 
* It can be build another model and it can be compared loss values.
