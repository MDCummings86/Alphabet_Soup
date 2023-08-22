# deep-learning-challenge

•	Attempt 1: For attempt 1, I used 8 nodes in hidden layer 1 and 5 in hidden layer 2 with 100 epochs of iteration. Both hidden laters were using the relu activation method while the output layer used the sigmoid method. From that arrangement, I only achieved a 72.58% accuracy with 55.3% loss. With only 72.58% of the models predictions matching the correct data, I will need to modify other parameters for more optimal performance.
     
•	Attempt 2: For attempt 2, I increased the amount of neurons with 15 in later 1 and 20 in layer 2. I also changed the activation method to sigmoid for all three layers. Sigmoid is beneficial when trying to predict the probability as an output. This attempt yielded worse performance at only 72.57% accuracy and 55.2% model loss.
    
268/268 - 0s - loss: 0.5547 - accuracy: 0.7247 - 430ms/epoch - 2ms/step
Loss: 0.5546526312828064, Accuracy: 0.7246647477149963
       
•	Attempt 3: As I notice the first three epochs present the biggest increase in accuracy, attempt 3 starts 3 hidden layers using the relu activation method ended with a sigmoid activation layer for output. Adding back the ‘name’ feature produced too many parameters which would clog up my run time, so I removed the ‘status’ feature and increased to 150 epochs instead. I also increased the cutoff for the binning of the classification and application features and increased the neurons to 10, 20 and 40, respectively for the three hidden layers. 
        
268/268 - 0s - loss: 0.5624 - accuracy: 0.7250 - 473ms/epoch - 2ms/step
Loss: 0.5624184608459473, Accuracy: 0.7250145673751831

