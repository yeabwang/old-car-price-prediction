# old-car-price-prediction
This is the first ever model I have built, the aim is to take a dataset from kaggle and pridict the price of old cars. I have tried my best to document each process in the actual model.

Life cycle
Understanding the task
Preparing the data and defining error function for the process
Developing our model
Error measurement based on the set scale
Training and optimization
Performance Measurement
Validation and Testing
Taking a corrective measurement

Used dataset
https://www.kaggle.com/datasets/mayankpatel14/second-hand-used-cars-data-set-linear-regression

Model
Sequential, 3 hidden layers with 32 params each, 1 normalizer with 8
Activation Function = ReLU
Learning rate = 0.001
Optimizer = Adam optimizer
Loss = Mean Absolute Error
Metrics = RootMeanSquaredError

Data plot
![image](https://github.com/user-attachments/assets/4144ce79-b435-4ecd-9780-3c27df587833)

Model
![image](https://github.com/user-attachments/assets/8a73c373-2948-4643-87b4-4215b6fa9683)

Model Loss graph
![image](https://github.com/user-attachments/assets/6b6d1fa0-c9bb-4e45-8d12-795b4622b45b)

Model Performance graph
![image](https://github.com/user-attachments/assets/9d99fd5c-41be-47b0-9175-c844a216d6af)

Actual predictions
![image](https://github.com/user-attachments/assets/8cb928d5-443d-47e9-9a55-954b6844b13c)
