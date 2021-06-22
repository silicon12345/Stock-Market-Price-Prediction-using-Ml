# Stock-Market-Price-Prediction-using-Ml
In this project we predict the value and the price of the Reliance NSE Stock dynamically by the help of Machine learning Algorithim
First step:-
1)Data Preprocessing:-
   i)In the data preprocessing step we generally remove the highly corelated features using Pearson corelation
   ii)In the second step as the stock price are highly changeable data so for that we change only 30 to 50 data so that we can handle the situation in future
2)Prediction:-
     i)For prediction we firstly applied Linear Regresssion as it is a continous labled data.
     ii)But here there is a problem of Overfitting
     Resolve from Overfiting 😢:-
                    To overcome from overfiting we applied some Regularization tech like Ridge Regression,Lasso Regression,Elastic Regression.
     But further the results are not acceptable....
     Then go to some of the good algorithim 😎:-
     1)Decession tree
     2)Logistic Regression:-
     In the decession tree we are using gini index for our spliting factor and here we got an accuracy of 80% and thats quite good than the previous one...
     so by that now we can predict the price of the stock and now it is a time for the value prediction 👍:-
     Value of the Stock Prediction:-
     As we have some less amount of data that so we for the Ensemble method:-
     In Ensemble method we are used some Bagging and Boosting Tech:-
     Bagging Tech:-
     1)Random Forest
     Boosting Tech:-
     1)Ada Boosting
     2)Gradient Boosting
     3)XG Boosting
     Finally by Normalizeed our data we conclude with a great accuracy of 90%.
3)Time For Pickle 😎:-
     We create a pickle file and save our model there .Now we create a web interface and from there we take the necessary input 
     and then doing some feature engeering tech we passed it through the model and then it can predict the value and price of the stock...

Thank you
Author-Shaswat Ranjan Nath
