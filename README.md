## A test for Data Science candidates 

(to be done within a week, should not take more than 5-6 hours)

Your task is to use the data in train.csv file to build a model (or several alternative models) to **predict shop visitor flows**. 

And then build predictions and test predictions for the month of 2021-06 using test.csv file. You can use only data in train.csv for training you model. No external data can be used.

The data set columns are the following:

- **sales** - total gross sales minus discounts per hour (sales at 10th hour means sales from 10am to 10:59am)
- **customers** - number of transactions per hour
- **visitors** - number of visitors per hour
- **opening_hour** - shop official opening hour that day
- **closing_hour** - shop official closing hour that day
During the interview we will discuss the following questions:

Do you have any noteworthy comments about the visitor data you are predicting?
- How good is your model?
- What is the prediction accuracy in test period?
- What are the shortcommings of your current model?
- How could you improve the model given more time?

Some initial code is provided below to help you get started. 

### Requirements

- Do an exploratory data analysis of the provided dataset.
- Build a data preprocessing pipeline, which can be used for your machine learning models.
- Build a machine learning model that predicts shop visitor flows `visitors` column
- Use the above models to predict shop visitor flows in the test.csv file. Export these predictions to predictions.csv file.
- You should have a single Jupyter notebook, which shows all of your work. You should put helper functions, classes, etc. in separate Python modules and import them in this notebook. Submit this notebook with the output cells present.
- You should have Pickle (or similar) files for each of your trained models. There should be a clear and easy way to load these files to your Jupyter notebook and use them for predictions.
- Use Python 3 in this project. This requirement doesn't apply to libraries written in a different language.
- Don't use your name, Github alias or other information, which may identify you anywhere in the homework.
- Commit your solution to a private Github repository (they are free) and invite `linas-samesystem` Github user as a collaborator.

### Evaluation Criteria

The solution is evaluated based on these criteria (in order):
- The demonstration of your data analysis skills.
- The demonstration of your machine learning skills.
- Your knowledge of software engineering best practices.
- The RMSE of the visitor model measured on test.csv.
- The inference speed of your models.


