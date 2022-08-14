# StockPricePrediction_USING_LSTM

Importing the required models for analysis
![image](https://user-images.githubusercontent.com/104202659/184528597-1449551c-b1b9-428c-9ddf-d096ec52a52d.png)


Now we are setting the start and end date for the stock analysis for gathering the dataset
![image](https://user-images.githubusercontent.com/104202659/184528648-62ec187b-8fbe-41dd-85c5-18fc7f499c34.png)

NOW we have to download the data for our future prediction and have to check the shape and some headers of the dataset
![image](https://user-images.githubusercontent.com/104202659/184528686-ac516f5d-7baf-4a73-8220-a6bb75c1a5d3.png)


Setting the index column in the dataset according to the data given in the 'date' column of the data
![image](https://user-images.githubusercontent.com/104202659/184528717-d13bea9c-ac75-4964-8f6c-c5a0744fddee.png)


Checking for the head and the tail of the dataset
![image](https://user-images.githubusercontent.com/104202659/184528742-aa48132b-8179-4e9d-8b3a-6724c665d86f.png)

Now we are going to check for the increment and decrement of the stock price
![image](https://user-images.githubusercontent.com/104202659/184528786-453cc258-cd1f-4f62-a4dd-14e81cacdc58.png)

![image](https://user-images.githubusercontent.com/104202659/184528804-8c2030dd-a46f-4647-8c48-d70be21dc1b8.png)


Checking for the correlation between the features
![image](https://user-images.githubusercontent.com/104202659/184528834-3922a413-bdd7-4267-bde6-88ec4fcff9a4.png)


Extracting the features and the labels for the training of the model
![image](https://user-images.githubusercontent.com/104202659/184528862-cc400215-2183-4fe7-ba95-4e907d1de42a.png)


Preparing the LONG SHORT TERM MEMORY MODEL (i.e LSTM model) for our prediction
![image](https://user-images.githubusercontent.com/104202659/184528905-a37a4965-d1e7-46d5-8ab7-2a8eae20b6c4.png)


compiling the prepared model
![image](https://user-images.githubusercontent.com/104202659/184528919-bc6872b1-0949-4406-9f27-1e983281b9bc.png)


Now after going through all the above steps mentioned, now our model can be used for the prediction as shown below 
![image](https://user-images.githubusercontent.com/104202659/184528948-08062e9f-c132-4b0c-a099-87e4c088af5a.png)
