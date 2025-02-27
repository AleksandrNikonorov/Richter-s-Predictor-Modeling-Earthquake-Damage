# Project: Predicting Damage to Buildings in Nepal from the 2015 Earthquake

## Project Description

This project is aimed at predicting the degree of damage to buildings in Nepal following the 2015 earthquake. It utilizes data from the [DrivenData](https://www.drivendata.org/competitions/57/nepal-earthquake/) competition, which provides detailed information about the buildings, their structural characteristics, and encoded locations.

## Key Project Stages

1. **Data Preprocessing:**
   - Processing encoded building locations using automated feature engineering methods.
   - Working with both categorical and numerical features to prepare the data for model training.

2. **Automated Feature Engineering:**
   - Employing techniques to automatically generate new features, which enhances prediction quality, especially when dealing with encoded building location data.

3. **Modeling:**
   - Implementation of a custom class for selecting and testing various machine learning models.
   - Incorporation of functionality for automatically evaluating different models and hyperparameters using cross-validation.
   - Model performance is assessed using accuracy metrics and the F1-score.

4. **Results:**
   - The final model was selected based on its prediction accuracy on the test set.
   - Predictions were generated for the final submission to DrivenData.

## Libraries Used

The project is implemented using the following libraries:

- `pandas` — for data processing.
- `numpy` — for numerical computations.
- `scikit-learn` — for machine learning model implementation and hyperparameter tuning.
- `catboost` — for handling categorical features and effective modeling.
- `keras` — for automated feature generation.

## Project Structure

- `Initial analysis. Report.pdf` — An analytical report on the domain, including graphs and descriptions of some features along with the main ideas.
- `Preprocessing and model selection class` — The source code of the project, including the class for selecting and testing models.
- `README.md` — A description of the project.

