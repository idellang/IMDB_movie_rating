# IMDB Movie Rating Prediction

The goal of this project is to predict whether a movie will have a weighted rating of greater than 7.

Dataset
- [IMDB dataset](https://www.imdb.com/interfaces/)
- [The movies dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)

Files from this repo
- [01_IMDB_initial_EDA_and_cleaning.ipynb : Notebook to understand the data](https://github.com/idellang/IMDB_movie_rating/blob/master/01_IMDB_initial_EDA_and_cleaning.ipynb)
- [02_combine_other_data.ipynb : Notebook to combine IMDB data with TMD data](https://github.com/idellang/IMDB_movie_rating/blob/master/02_combine_other_data.ipynb)
- [03_imdb_modeling_basic.ipynb: ML modeling to predict high rated movies based on basic movie information (e.g., budget, genre, etc)](https://github.com/idellang/IMDB_movie_rating/blob/master/03_imdb_modeling_basic.ipynb)
- [04_imdb_modeling_text: Used text features on prediction](https://github.com/idellang/IMDB_movie_rating/blob/master/04_imdb_modeling_text.ipynb)


**Feature Importance from the random forest model**
![](plots/RF_Importance.png?raw=true)

**Highest weighted words from linear regression and stochastic gradient descent models**

![](plots/text_coef.png?raw=true)

libraries used:
- numpy                  1.20.3
- pandas                 1.3.1
- scikit-learn           0.24.2
- matplotlib             3.4.2
seaborn                 0.11.2
- keybert                0.5.0
- multidict              5.1.0
- pycountry              22.1.10
- cpi                    0.1.16