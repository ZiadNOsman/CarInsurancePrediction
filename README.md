# CarInsurancePrediction
predicted customer interest in car insurance knowing they have health insurance from that same company. 
This project is structured into phases
# Phase 2
this aim of this project is to handle the data. As this was a learning experience, and the data was quite clean, Our team corrupted the data (so that we could re-clean it). afterwards, the following was performed on the data: cleaning outliers and erroneous data, featured selection, feature elimination, feature importance, data transform, feature engineering, dimentionality reduction (among other things).
Perhaps most importantly, this phase involved exploratory data analysis, where we derived insights from the data by creating useful graphs and analysing them.

# Phase 3
The aim of this phase was to see what difference our effort in phase 2 made. During phase 3, we trained the models on both the original data, and the data which was modified by us to see which method yields better results. Also during this phase, a major flaw in our data set was made apparent: data imbalance of 10:1. As you will see, we tried to miigate this by using a technique called SMOTE. But, as our overseeing professor pointed out to us, this kind of issue required more advanced techniques. The techniques that were proposed to us (that we did not have time to implement given the time constraints) are:   
1- Resort to probabilistic predictions and apply the threshold moving technique described in the imbalanced classification book.  
2- Incorporate a hybrid of under sampling and oversampling.  
3- Try cost sensitive ensembles.  
4- Cluster your data, train on the clusters and transfer the learning from the stronger clusters to the weaker ones.  
5- Try meta learning.    
6- Try Petri dish approach for designing your neural network architecture search.  

1-3 are easiest to do, followed by 4, then 5, then 6.  
We were informed that these advanced techniques require research and trial and error. We decided to learn about them on our own time, but chose to move forward with our original SMOTE plan as a technique.

Models used: Bagging Decision Tree - Random Forest - XBoost - CATBoost - Neural Network - kNN
Model evaluation matrices: Accuracy - Fscore - Receiver operating characteristic (ROC) and Area under the ROC Curve (AUC) - Confusion Matrix 

# Phase 4
given as an HTML file, Download and view on your own machine. at the End of this Phase, there is a summary of everything done along with the insights gotten from this project. Additionaly, we experimented with hypothesis testing in this phase, although this one is not as fleshed out. We also compared and evaluated our different models and their performance.

# Phase 5
this additional phase is for SHAP. from a google search : "SHapley Additive exPlanations — is probably the state of the art in Machine Learning explainability. This algorithm was first published in 2017 by Lundberg and Lee (here is the original paper) and it is a brilliant way to reverse-engineer the output of any predictive algorithm."
