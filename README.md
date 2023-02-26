
# Gradient-Boosting

![image](https://user-images.githubusercontent.com/92606737/221392708-620ab454-6c39-45a3-b37b-987bf9226ef2.png)

Gradient Boosting is a machine learning algorithm that is used for regression and classification problems. It is a type of ensemble learning method that combines several weak learners (also known as base models) to create a strong predictive model.

The basic idea behind Gradient Boosting is to sequentially add new models to the ensemble that attempt to correct the errors made by the previous models. Each new model is fitted to the residual errors of the previous models, with the goal of minimizing the overall error.

### The algorithm proceeds as follows:

- A simple model (such as a decision tree) is fitted to the data.
- The errors of the model are calculated by comparing the predicted values to the true values.
- A new model is then fitted to the errors of the previous model, with the goal of minimizing the error.
- The errors of the new model are added to the errors of the previous model, and the process is repeated until the overall error is minimized.

Gradient Boosting is known to be a powerful and versatile algorithm, and has been successfully applied to a wide range of problems in various fields, including finance, biology, and computer vision. However, it can be computationally expensive and prone to overfitting, so care must be taken when selecting the hyperparameters and training the model.

##  Math intuition behind the Gradient boosting algorithm

![image](https://user-images.githubusercontent.com/92606737/221392778-160df49d-8944-400e-bdd0-1f19b7d0cf55.png)


__Link__ : https://www.analyticsvidhya.com/blog/2021/09/gradient-boosting-algorithm-a-complete-guide-for-beginners/

# Advantages of Gradient Boosting:

- __High accuracy__ 
    
    Gradient Boosting is known for its high accuracy and performance, and it is often one of the top-performing algorithms in machine learning competitions.

- __Versatility__
  
  Gradient Boosting can be applied to a wide range of problems, including regression, classification, and ranking.

- __Handles missing data__
    
    Gradient Boosting can handle missing data by imputing missing values or ignoring them during training.

- __Feature importance__
      
     Gradient Boosting can provide a measure of feature importance, which can be useful for feature selection and understanding the underlying data.

- __Robustness to outliers__
      
     Gradient Boosting is less sensitive to outliers compared to other algorithms, such as SVMs.

# Disadvantages of Gradient Boosting:

- __Computationally expensive__
    Gradient Boosting can be computationally expensive, especially if a large number of weak learners are used or if the dataset is large.

- __Overfitting__
   
   Gradient Boosting is prone to overfitting, especially if the number of iterations or the complexity of the models is not properly tuned.

- __Sensitive to hyperparameters__

   Gradient Boosting has several hyperparameters that need to be carefully tuned to achieve optimal performance, and selecting the right hyperparameters can be a difficult and time-consuming process.

- __Not well-suited for online learning__ Gradient Boosting is not well-suited for online learning, as it requires retraining the entire model whenever new data becomes available.

Overall, Gradient Boosting is a powerful and flexible algorithm that can achieve high accuracy and handle a wide range of problems, but it requires careful tuning and can be computationally expensive and prone to overfitting.

# When to use This Algo?
Gradient Boosting is a powerful algorithm that can be used in a wide range of machine learning problems, including regression, classification, and ranking. It is particularly useful in the following situations:

- Gradient Boosting is known for its high accuracy and performance, and it is often one of the top-performing algorithms in machine learning competitions.

- Gradient Boosting can handle complex relationships between features and the target variable, making it suitable for problems with nonlinear dependencies.

- Gradient Boosting can handle large datasets, although it may be computationally expensive.

- Gradient Boosting can handle missing data by imputing missing values or ignoring them during training.

Importance of feature selection: Gradient Boosting can provide a measure of feature importance, which can be useful for feature selection and understanding the underlying data.

## However, Gradient Boosting may not be suitable in the following situations:

- Gradient Boosting can be computationally expensive, especially if a large number of weak learners are used or if the dataset is large.

- Gradient Boosting requires a sufficient amount of training data to achieve high accuracy.

- Gradient Boosting is not well-suited for online learning, as it requires retraining the entire model whenever new data becomes available.

- If a simple model is preferred over a complex one, then Gradient Boosting may not be the best choice.

Overall, Gradient Boosting is a versatile and powerful algorithm that can be used in a wide range of problems, but it requires careful tuning and may not be suitable in all situations.



