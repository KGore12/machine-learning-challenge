# Machine Learning Homework - Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

### Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, you will create machine learning models capable of classifying candidate exoplanets from the raw dataset.

### Assignment Requirements
1. Preprocess the raw data
2. Tune the models
3. Compare two or more model

### Preprocess the Data

* Preprocess the dataset prior to fitting the model.
* Perform feature selection and remove unnecessary features.
* Use `MinMaxScaler` to scale the numerical data.
* Separate the data into training and testing data.

### Tune Model Parameters

* Use `GridSearch` to tune model parameters.
* Tune and compare at least two different classifiers.

### Reporting

* Create a README that reports a comparison of each model's performance as well as a summary about your findings and any assumptions you can make based on your model (is your model good enough to predict new exoplanets? Why or why not? What would make your model be better at predicting new exoplanets?).

# Final Analysis
All models look showed good results for the data provided.  Since the Random Forest Model and the Deep Learning Model have the highest accuracy/scoring either of these would be the best method to use for further research.

* SVM (Support Vector Machine) Model: 
    * Training Data Score: 0.88651             
    * Testing Data Score: 0.87929
    
* Logistic Regressions Model: 
    * Training Data Score:  0.84589                  
    * Testing Data Score:  0.86156
    
* Random Forest Model: 
    * Training Data Score:   1.0                 
    * Testing Data Score:   .912471
    
* Deep Learning Model:
    * Loss:  0.24673                  
    * Accuracy: 0.89874
    




## Resources

* [Exoplanet Data Source](https://www.kaggle.com/nasa/kepler-exoplanet-search-results)

* [Scikit-Learn Tutorial Part 1](https://www.youtube.com/watch?v=4PXAztQtoTg)

* [Scikit-Learn Tutorial Part 2](https://www.youtube.com/watch?v=gK43gtGh49o&t=5858s)

* [Grid Search](https://scikit-learn.org/stable/modules/grid_search.html)
