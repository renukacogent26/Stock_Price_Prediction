# Stock_Price_Prediction

![image](https://user-images.githubusercontent.com/110614719/188698892-10a44c79-1bce-4513-83e2-9083e2da438b.png)

The lowest closing price of stock is on 24 December 2018 with price 233.880005

![image](https://user-images.githubusercontent.com/110614719/188706368-b83d7d59-c503-4e03-bb6a-14ebdd5c10b0.png)

The highest closing price of stock is on 24 December 2018 with price 691.690002

![image](https://user-images.githubusercontent.com/110614719/188707121-1d6742a3-afe5-48c4-80e8-c9fc5690a0e3.png)

The dependent variable (DV) is "Close" and from the plot it is understood that the DV has some trend

![image](https://user-images.githubusercontent.com/110614719/188707373-ea3cbcf5-1142-4094-9ab9-23250fa2e136.png)

There is very small degree of difference in stock between opening price and closing price

![image](https://user-images.githubusercontent.com/110614719/188710022-7ffd4c04-9336-47a1-8912-7513fa85a7ea.png)

From the pairplot, we could see that all independent variables have linear relationship with each other

![image](https://user-images.githubusercontent.com/110614719/188710620-3e376c4e-941b-4db9-8239-c82d90582b8c.png)

The variables "Adj Close" and "Close" are identical and so we are dropping "Adj Close" from independent variable. 
Hence, "Open, High, Low, Volume" are set as IDV and "Close" as DV

![image](https://user-images.githubusercontent.com/110614719/188712900-37858dde-93d8-44d0-a565-b7e5617cf521.png)

Splitting the data and training the model using Random Forest algorithm. And the closing price was prdicted for the 
test variables

![image](https://user-images.githubusercontent.com/110614719/188715162-51663174-79b8-4b42-8497-b67c0af99dbc.png)

These are the calculated errors

![image](https://user-images.githubusercontent.com/110614719/188715369-94d2f0ed-b8ce-478e-83d8-b7d66b09c65a.png)

DataFrame has been created using the predicted values

![image](https://user-images.githubusercontent.com/110614719/188715676-906a540a-9487-469c-b25f-c2a7fc1cb022.png)

One year prediction plot

![image](https://user-images.githubusercontent.com/110614719/188715795-5bda99d4-b020-40b3-be30-39c671f9b571.png)

Hundred days prediction plt

![image](https://user-images.githubusercontent.com/110614719/188715926-186ce6ce-0930-4450-a175-a0ea5d48e055.png)

One month prediction plot

