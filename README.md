Algorithmic_Trading_CH14
Algorithmic_Trading
# Technology 
 These are the technologies the user can use to run the solution -- Jupyter notebook  -- Python -- Github -- To download the solution file. It's saved in githun as public
Test Data 
emerging_markets_ohlcv.csv
 # Contributors 
 The solution is developed by Eyasu Alemu LinkdIn account -- https://www.linkedin.com/in/eyasu-a-684854112 Email -- Bekaqa01@gmail.com Phone Number -- 202 344 0733


Using the starter code file and the provided csv complete the following steps.
	Establish a Baseline Performance
	Tune the Baseline Trading Algorithm
	Evaluate a New Machine Learning Classifier
	Create an Evaluation Report

1. Establish a Baseline Performance

	Import the OHLCV dataset into a Pandas DataFrame.
	Generate trading signals using short- and long-window SMA values.
![image](https://github.com/Eyasualemu/Algorithmic_Trading_CH14/assets/44585226/32617a83-e4ec-43eb-9c37-b078f6b93a3d)

	Split the data into training and testing datasets.
	Use the SVC classifier model from SKLearn's support vector machine (SVM) learning method to fit the training data and make predictions based on the testing data. Review the predictions.
	Review the classification report associated with the SVC model predictions.
	Create a predictions DataFrame that contains columns for “Predicted” values, “Actual Returns”, and “Strategy Returns”.
	Run and save a PNG image of this plot. This will serve as a baseline against which to compare the effects of tuning the trading algorithm.
![image](https://github.com/Eyasualemu/Algorithmic_Trading_CH14/assets/44585226/29326e93-ec7a-4b3a-bca9-41a9ad3d2828)

 

2.	Tune the Baseline Trading Algorithm

Step 1 When tune the training algorithm by adjusting the size of the training dataset to 12 the following result returned.
![image](https://github.com/Eyasualemu/Algorithmic_Trading_CH14/assets/44585226/1f2586f8-c799-4d3b-83b1-2473a9024b2d)


Step 2  When tune the training algorithm by adjusting the size of the training dataset to 12 the following result returned.

The signal value count affected and returned the following 
![image](https://github.com/Eyasualemu/Algorithmic_Trading_CH14/assets/44585226/f9aaf811-f664-49aa-bf2e-2f74deda9cb9)


Strategy Returns to examine performance is not affected
![image](https://github.com/Eyasualemu/Algorithmic_Trading_CH14/assets/44585226/3fd9ca9a-0cd8-4b7c-9d23-96a503a0c4b3)

Target set value count is affected and returned the following
![image](https://github.com/Eyasualemu/Algorithmic_Trading_CH14/assets/44585226/1c44aa27-10c3-47f8-9f61-476c1361a233)

Classification report to evaluate the model using the predictions and testing data is affected and returned the following
![image](https://github.com/Eyasualemu/Algorithmic_Trading_CH14/assets/44585226/8be0262c-0485-4701-acaf-7eba8b94dbff)


Cumulative return plot that shows the actual returns vs. the strategy returns is affected and returned the following 
![image](https://github.com/Eyasualemu/Algorithmic_Trading_CH14/assets/44585226/ae1dc049-c22c-4bd9-ba42-86e71f417f95)

Step 3 -- Choose the set of parameters Short window = 12 and long window = 70 that best improved the trading algorithm returns. The PNG image of the cumulative product of the actual returns vs. the strategy return saved as New_figuer.png

3.	Evaluate a New Machine Learning Classifier
![image](https://github.com/Eyasualemu/Algorithmic_Trading_CH14/assets/44585226/6428d8ce-926d-4af1-bb3e-e179ddb80d23)

![image](https://github.com/Eyasualemu/Algorithmic_Trading_CH14/assets/44585226/00e0bd7e-3ed8-41c3-8201-15e95e3fc822)



4. Create an Evaluation Report
