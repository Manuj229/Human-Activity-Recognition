# Human-Activity-Recognition
STEPS TO BUILD THE MACHINE LEARNING MODEL
Step 1:
Importing NumPy and Pandas. Setting up the directory to the folder name in which the data is stored.
Step 2:
Importing SciKitLearn and Keras using Tensorflow Backend.
Step 3:
Setting up the attributes using an array. Importing and reading the data from Phone Accelometer.
Step 4:
Importing and reading the data from Phone Gyroscope, Watch gyroscope and Watch accelometer respectively. 
Step 5:
o	Replacing “;” by “ “  in the 6th column. 
o	Setting the type of ‘x’ , ‘y’, ‘z’ to float integers
o	Obtaining the info of the dataset so formed. 
Step 6:
Combining the data from Phone Gyroscope and Phone Accelometer.
Step 7:
Combining the data from watch gyroscope and watch accelometer.
Step 8:
Combining the data of phone and watch both.
Step 9:
Defining all the activity of the dataset with a function.
Step 10:
o	Data Preprocessing
o	Using LabelEncoder doing feature scaling
Step 11:
Forming a frame using scipy.stats
Step 12:
Splitting Training and Test set and determining the shape of Training set and Test set

Step 13:
Reshaping the Training and test set using reshape function.
Step 14:
Applying a convolutional 2D network. With activation fuction as Rectified Linear Unit (ReLU)
Step 15:
Compiling the model using model.fit method with 8 epochs.


Result: Achieved an accuracy of 71% in 8 Epochs.
