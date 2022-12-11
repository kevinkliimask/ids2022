# Project D10: KAGGLE - Movie Ratings

This is the project repository for the Introduction to Data Science 2022 course.

### Authors:
- Kevin Kliimask
- Taavi Eistre
- Jens Jäger

### Our used datasets:
- movies_metadata.csv
- keywords.csv

Data retrieved from: https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset

### Our goals for the project:
- Train models using two different datasets (movies_metadata.csv and keywords.csv)
to predict movie ratings (vote averages)
- Analyze the data and find interesting facts

### To run our project:
- Clone our repository
- Install the following libraries:
  - Pandas
  - Numpy
  - Matplotlib
  - Sklearn
  - ast
  - Tensorflow
- Select the desired notebook to run and run it

### Summary
We created two different notebook files for our models.

In the first one, we used the movies metadata dataset and trained the models
using regression models that we had learned about during the course.

In the second file, we tried out tensorflow on the keywords dataset
with genres column from metadata in addition.

Our goal was to train a model that had an RMSE (Root mean squared error) of about 0.5 or under,
but unfortunately we weren't able to accomplish that. We did however manage to train models with an RMSE
of about 1, which is still pretty okay in our opinion.

