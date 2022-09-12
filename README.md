# Income Prediction

This notebook aims to walk someone through the full Data Science pipeline from exploratory analysis all the way to model predictions. This notebook utilizes the `census.csv` data to make predictions on how much the person makes (<=50k or >50k). We go through and explain the data exploration process, what we are looking for, what we do in the case of duplicated data, visualizations, etc. Then we perform some feature creation for scaling and one hot encodings for predictions. Then we train multiple different models from the [sklearn api](https://scikit-learn.org/stable/modules/classes.html#module-sklearn.ensemble) and utilize grid search for hyperparameter optimization. Finally, once we train all of the models we analyze their performance. Further deatils of the actions that were taken and why they were taken is provided by the comments within each of the cells of the notebook. I also tried to make the code as user friendly as possible. If you have any questions feel free to open any issues, I will tend to them as soon as I see them. Thank you!!

## How to install and run the notebook
This project was made using [Pipenv](https://github.com/pypa/pipenv) for keeping track of dependencies. First you must have Pipenv installed:
```
pip install pipenv
```
After having Pipenv installed, you should create a virutalenv for the project. To do this, cd into the directory and run the command:
```
pipenv shell
```
Finally, to install the necessary dependencies run:
```
pipenv install
```
By calling ```pipenv install``` you install all of the necessary dependencies within the Pipfile.lock.

All that is needed to run the notebook now is just run the command below and check oyur browser instance for a new Jupyter Notebook tab:
```
jupyter notebook
```
