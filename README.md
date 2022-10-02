# LDA and KNN on Thyroid Data

#### The recorded 10 test values of KNN and LDA in two vectors are:  

<p align="center">
<img width="619" alt="Screenshot 2022-10-02 at 21 25 23" src="https://user-images.githubusercontent.com/66077662/193474753-d95e1af6-642b-41ac-a208-dfb4ad7410b6.png">
</p>
<h5 align="center">KNN & LDA AUC Values</h5>

The k value of 3 is found to be the best estimator while tuning the parameters of the KNN model by 5-fold cross validation.  

#### The plot below shows two boxplots of AUC values of LDA and KNN respectively.  

<p align="center">
<img width="619" alt="Screenshot 2022-10-02 at 21 26 12" src="https://user-images.githubusercontent.com/66077662/193474791-99386682-458e-477e-b982-c9f31ebf68fc.png">
</p>
<h5 align="center">Boxplots of AUC Values</h5>

From the boxplots shown above we can conclude that the KNN model is a better fit for the newthyroid.txt data because it has higher median AUC values when compared to the linear discriminant analysis (LDA)model 
