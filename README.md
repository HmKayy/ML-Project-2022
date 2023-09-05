#Introduction
Apex Legends is one of the most popular games on the Internet. As an Apex Enjoyer myself, I decided to apply various machine learning models to predict the concurrent ingame players based on Steam's concurrent users
The reasoning behind this project besides my love for the game is that the in-game player count might fluctuate drastically, impacting the server performance, thus, predicting when these fluctuations happen will help manage the server better.

#Data
The data used in this project was collected from steamDB, and Steam's game page tab. The dataset includes information on the concurrent users and concurrent in-game players by date.

#Methodology
I used various machine learning techniques, including Linear Regression and Polynomial Regression to build a model that predicts in-game players based on Steam user count. I also performed various data cleaning and feature selection to improve the model's performance.

#Result
The chosen model achieved errors of roughly 15% for both training and validation, thus, the model can accurately predict with more than 80% accuracy.

#Conclusion
My model try to predict the in-game players for Apex Legends based on Steam's concurrent users. The model achieved just that with a relatively hight accuracy level, but this does not means that it cannot be improved further with more data and techniques.

#Requirements
The code for this project was written in Python 3.8 and requires the following libraries:

- Numpy
- Pandas
- Matplotlib
- Sklearn

#Usage
To run the code for this project, clone the repository and run the Jupyter Notebook file.
