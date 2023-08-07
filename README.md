# Diabetes Prediction

This project aims to predict whether a person has diabetes or not using machine learning techniques. It uses the [diabetes dataset](https://www.kaggle.com/johndasilva/diabetes) available on Kaggle.

## Data Exploration

- The dataset has been explored to understand its structure and data types.
- Columns in the dataset include: 'Pregnancies', 'Glucose', 'BloodPressure', 'SkinThickness', 'Insulin', 'BMI', 'DPF', 'Age', and 'Outcome'.

## Data Cleaning

- Data cleaning involved replacing 0 values with NaN in certain columns to identify missing values.
- The missing values were filled with the mean or median based on the distribution of each column.

## Model Building

- The dataset was split into training and testing sets for model building and evaluation.
- Various machine learning algorithms were tested using GridSearchCV for hyperparameter tuning.
- The Random Forest Classifier was found to have the highest accuracy among the tested algorithms.

## Model Evaluation

- The trained Random Forest Classifier was evaluated on both the training and testing sets.
- Evaluation metrics used include confusion matrix, accuracy, and classification report.

## Making Predictions

- A function was created to make predictions on new data using the trained Random Forest model.
- Example predictions for diabetes were shown using sample input sequences.

## Usage

- To use this code, simply call the `predict_diabetes()` function with appropriate input values for 'Pregnancies', 'Glucose', 'BloodPressure', 'SkinThickness', 'Insulin', 'BMI', 'DPF', and 'Age'.
- The function will return a prediction of whether the person has diabetes or not.

## Dependencies

- The following Python libraries are required to run the code:
  - numpy
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn

- Install the dependencies using pip:
```bash
  pip install numpy pandas matplotlib seaborn scikit-learn
  ```

## Credits

- The dataset used in this project is available on Kaggle: [diabetes dataset](https://www.kaggle.com/johndasilva/diabetes).

- If you find this project useful, consider giving it a star on GitHub!

--- 

