# Movie Recommendation System
The purpose of the current project is to train and test a Machine Learning model able to recommend a movie to users according to their preferences.

Other projects can be found in the following repositories:

- [Fashion MNIST](https://github.com/UribeAlejandro/ComputerVision_FashionMNIST)
- [CIFAR10](https://github.com/UribeAlejandro/ComputerVision_CIFAR10)
- [Cats vs Dogs](https://github.com/UribeAlejandro/ComputerVision_Cats_vs_Dogs)
- [Rock Paper &amp; Scissors](https://github.com/UribeAlejandro/ComputerVision_Rock_Paper_or_Scissors)
- [The Street View house Numbers](https://github.com/UribeAlejandro/ComputerVision_SVHN)

## Acknowledgements
This hands-on experience with Machine Learning common projects was one the Capstone Projects to receive the certification as Data Scientist - Acámica and the concepts explained in Hands-On Machine Learning with Scikit-Learn, Keras & Tensorflow by Aureélien Géron - O'Reily.

Sections of code were taken from both sources stated above.  
All the datasets used along this notebook are open sourced.

# Code Structure

The notebook is structured as follows:
- Data Overview
- Exploration
- Modelling
- Testing

## Data Overview
The data is stored in a subdirectory which contains multiple sub-datasets. However, the most relevant ones are listed below:

```
Ratings   (u.data)
Users     (u.user)
Movies    (u.item)
```

## Exploration
This phase includes a brief exploration of the sub-datasets' variables listed above. 

## Collaborative Filtering ~ Modelling
_Singular Value Decomposition_ `SVD` was used as the technique to build the Recommender System. As `SVD` relies on the _Number of Factors_ chosen, the analysis carried out measured the variation of _Root Mean Square Deviation_ `RMSE` vs _Number of Factors_.

On the other hand, a _Hyperparameter Optimization_ along with _Cross Validation_ had been carried out in order to find the best model.

## Testing
Predictions over random users have been carried out in this section.