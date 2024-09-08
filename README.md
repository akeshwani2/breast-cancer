# Breast Cancer Prediction using Logistic Regression

## Project Overview
This project implements a machine learning model to predict whether a breast tumor is malignant or benign based on various features extracted from medical images. It uses logistic regression to classify tumors and evaluates the model's performance.

## Dataset
The dataset used is the Breast Cancer Wisconsin (Diagnostic) Dataset, which includes features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. Features include:

- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Concave points
- Symmetry
- Fractal dimension

Each feature is computed for the mean, standard error, and "worst" (mean of the three largest values) for each image, resulting in 30 features.

## Requirements
- Python 3.x
- pandas
- matplotlib
- seaborn
- scikit-learn

## Code Structure
The main script (`index.ipynb`) performs the following steps:

1. Data loading and preprocessing
2. Feature scaling
3. Model training (Logistic Regression)
4. Prediction and evaluation
5. Visualization of results

## Usage
1. Ensure the dataset (`breast_cancer_data.csv`) is in the correct path.
2. Run the Jupyter notebook `index.ipynb`.

## Model Performance
The model's performance is evaluated using:
- Accuracy score
- Confusion matrix
- Classification report (precision, recall, F1-score)

A confusion matrix heatmap is generated for visual interpretation of the results.

## Future Improvements
- Experiment with other classification algorithms (e.g., Random Forest, SVM)
- Perform feature selection to identify most important predictors
- Implement cross-validation for more robust performance estimation
- Try hyperparameter tuning to optimize model performance

## Ethical Considerations
This model is for educational purposes only and should not be used for actual medical diagnosis. Always consult with healthcare professionals for medical advice and diagnosis.

## License
Please view the LICENSE file.

## Contact
- Arhaan Keshwani
- akeshwanibusiness@gmail.com
