# Quantum-reservoir-computing-model

This is a quantum reservior computing model which is used for time series predcitions 
This model iteratively applies a set of quantum gates on the sequential data so that the data evolves 
from this evolved data new features are extracted and are used for training the model 

The data set used is the  Statlog German Credit Data

The model outperformed the classical counter parts which are SVM , gradient boost and random forest

The metrics used to compare the quantum model and the classical ones are : MSE and R -squared (R²) 

The lower the Mean Squared Error (MSE), the better the model’s performance. MSE measures the average squared difference between predicted and actual values, so a smaller MSE indicates that the model’s predictions are closer to the true values. Similarly, the closer the R-squared (R²) value is to 1, the better the model. R² indicates how well the model explains the variance in the data. A higher R² means the model explains most of the variance, whereas a lower R² suggests the model is not capturing much of the data’s variation. Therefore, a lower MSE and a higher R² reflect better model performance

In the comparison graphs we can see that there is a equal distribution of data points above and below the mean line in the case of quantum model which indicated that the model is not over estimating or underestimating whereas we can see unbalnce distribtuion of data points in the graphs of its classical counter parts



