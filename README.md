# churn-modelling
Analysis on bank account data to predict customer churn.  Originally run using [Floydhub deep learning infrastructure](https://www.floydhub.com/), and run on a Kaggle kernel [here](https://www.kaggle.com/lauriermantel/using-basic-neural-networks-to-predict-churn).

This exploration uses cross-validation to check the accuracy.  The Jupyter notebook has some annotations, but the biggest observation is that standardizing the input data was able to increase the accuracy of the classification algorithms, as we would expect.  As well, the more accurate results from algorithms included _more_ input dimensions into the neural networks.  
