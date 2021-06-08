# Reading-Handwritten-Numbers-Letters
Building a keras sequential model to read from EMNIST data to be able to decipher Handwritten Numbers and Letters.
The EMNIST file data was downloaded from https://www.kaggle.com/crawford/emnist and the specified files that are
being used is mentioned below.

Numbers

	Data
	
		Copy files emnist-digits-test.csv and emnist-digits-train.csv into this folder.
		Omitted in this post due to the extremely large file size.
	HandWrittenNumbers.ipynb 
		Builds, and trains a keras sequential deep neural network with approximately 97% accuracy
		User can see the some pictures of certain test number and compare it to the predicted value by the model
		User can edit the number.png file and the code will attempt to predict the number written by the user
		Creates a Confusion Matrix to see the results of the test data
	number.png
		This image is used for the user to edit and the model to predict the written number
		
Numbers and Letters

	Data
		Copy files emnist-bymerge-test.csv, emnist-bymerge-train.csv, and emnist-bymerge-mapping.txt into this folder.
		Omitted in this post due to the extremely large file size.
	HandWrittenNumbers.ipynb 
		Builds, and trains a keras sequential deep neural network with approximately 97% accuracy
		User can see the some pictures of certain test number and compare it to the predicted value by the model
		User can edit the number.png file and the code will attempt to predict the number written by the user
		Saves and loads the model including the architecture, weights, training configurations, state of optimizer.
	picture.png
		This image is used for the user to edit and the model to predict the written number
