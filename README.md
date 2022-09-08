# Linear Regression Model

This is a linear regression model trained to predict the PremiumPrice of a preson's insurance. The project was carried out as a University project therfore the dataset was provided by Our Instructor which include about 1000 obeservations. This project was done as a learning project in jupyter notebooks using numpy, matplotlib, pandas, keras and Tensorflow.


## Traning the model

Before training the dataset, sample the 80% of the data into train dataset and rest is as the test dataset. Then normalized the train dataset using keras preprocessing layer. After that build the model using keras sequentail model passing one dense layer as this a linear regression model. Then compile the model passing parameters of mean absolute error as the loss and the keras Adam optimizer as the optimizer. Then train the model using 30000 epochs and allocate 0.2 for validation split

## Results

Error reducing rate become consistent around 12000 epoch and was able to reduced the error to around 2500. When compared to the data values of the premium price, I think this model is not that much accurate, and I think we need more data in our dataset or we have to use more layers when building the model.

Please update me if I did something wrong or If I didn't understood any concept properly. :innocent:

## Tech 

Python, keras and Tensorflow







