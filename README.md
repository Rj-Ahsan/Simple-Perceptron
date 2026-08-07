# Titanic Survival Prediction

This repository contains a Titanic survival prediction project using deep learning and interactive visualization.

## What’s included

- `Titanic_DL.ipynb` — a Jupyter notebook that:
  - loads and inspects the Titanic dataset
  - cleans and imputes missing values
  - encodes categorical features and creates engineered features like `FamilySize` and `IsAlone`
  - scales data with `StandardScaler`
  - trains a neural network with Keras
  - applies early stopping, L2 regularization, and dropout to reduce overfitting
  - evaluates performance on a test set
- `main.py` — a Streamlit app for:
  - uploading or loading the Titanic dataset
  - preprocessing data automatically
  - training the model with configurable parameters
  - displaying training history and evaluation metrics
  - predicting passenger survival probability from user inputs

## How to use

1. Place the Titanic dataset at `C:\Users\Ali\Downloads\Titanic_data\Titanic-Dataset.csv`, or upload a dataset in the Streamlit app.
2. Open `Titanic_DL.ipynb` to run the notebook workflow.
3. Start the Streamlit app with:
   ```bash
   streamlit run main.py
   ```

## Dependencies

- Python
- pandas
- numpy
- matplotlib
- scikit-learn
- tensorflow
- streamlit
- ydata-profiling

## Notes

- The notebook demonstrates a complete data science workflow from preprocessing to model tuning.
- The Streamlit app is designed for interactive training and survival predictions.
