# Customer-behavior-predictions
Udemy - ML with TensorFlow
### Problem:   
* Each customer in the database has made a purchase at least once
* Create a machine learning algorithm based on given data that can predict if a customer will buy again from the Audiobook company
* We want to focus on customers who are likely to come back and buy again
* This model can identify the most important metrics for a customer to come back again  

After creating the model, I could achieve test accuracy of 84.60%. The dataset is not sufficient, therefore achieving higher accuracy is highly unlikely; however the model still gives a good insight about whether a customer will buy again or not.   
Here are my results from playing with the hyperparameters:

hidden_layer_size= 50; test accur = 81.70  
hidden_layer_size = 80; test accur = 84.38  
hidden_layer_size = 95; test accur = 84.60  
hidden_layer_size = 80; sigmoid both output; test_accur= 81.47 (more epochs)  
hidden_layer_size = 80; learning rate = 0.002; test_accur = 84.15  
hidden_layer_size = 80; learning rate = 0.002; batch size=1000; test acc= 81.70  
hidden_layer_size = 100; learning rate = 0.002; batch size=100; test acc = 84.38  

