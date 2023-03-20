## Project Definition: Bike rent prediction

![dataset-cover](https://user-images.githubusercontent.com/108892135/226379292-69638d46-d5ea-499c-8cc0-b880e54ab9ef.jpg)

The aim of this project is to help a bike sharing service to predict the hourly number of rented bikes for the following week. The dataset is made by train and test files, where one can find for each hour the amount of bikes rented by customers of a bike sharing service in Washington DC, together with other features such as whether a certain day was a national holiday, and which day of the week was it.

---

## Project scheme
We inspired by [Kaggle Competitions](https://www.kaggle.com/competitions), so we will use the same format.

### Inputs

Data are provided in the `DataProject` folder.
The idea is to use such data to solve a problem.

We will use the following data structures:

- **DataProject**: a directory containing one or more csv files.
  - `train.csv`: training data with labels.
  - `test.csv`: test data with no labels.
  - `sample_submission.csv`: sample submission.
  - `VariableDefinitions.csv`: a csv file containing a description of the data.

### Outputs

These are the expected outputs of the project.

- **Bike rent prediction Submission.csv**: a csv file containing the results of the project, according to the sample submission format.
- **Bike rent prediction.ipynb**: a notebook file containing analysis, relevant choices and results comments and explanations.
- **Bike rent prediction model.joblib**: a file containing the trained model in the form of a pipeline.

## Evaluation

The evaluation metric for this challenge is the Mean Absolute Percentage Error, **MAPE** on a test set (not provided).

The values can be between $0$ and $+\infty$.

Your `submission` file should look like:

|       date       |      hour         |      count        |
| ---------------- | ----------------- | ----------------- |
|     2012-12-01   |        00         |       15          |
|        ...       |       ...         |      ...          |

---
