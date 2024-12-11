# Heart Disease Prediction using Neural Networks

## Overview
This project aims to predict the presence of heart disease in individuals using a **Neural Network** model. It leverages patient health metrics to perform binary classification, identifying whether a patient is at risk of heart disease.

## Features
- **Data Preprocessing**: Includes cleaning, normalization, and handling missing values in health metrics.
- **Model Architecture**: Utilizes a feedforward neural network with multiple hidden layers.
- **Performance Evaluation**: Metrics include accuracy, precision, recall, and AUC-ROC.
- **Visualization**: Features plots of model performance and key metrics.

## Dataset
- The dataset includes patient health metrics, such as:
  - Age
  - Sex
  - Chest pain type
  - Resting blood pressure
  - Cholesterol levels
  - Fasting blood sugar
  - Resting electrocardiographic results
  - Maximum heart rate achieved
  - Exercise-induced angina
  - ST depression induced by exercise
  - Slope of the peak exercise ST segment
  - Number of major vessels colored by fluoroscopy
  - Thalassemia status
- The dataset is stored in CSV format in the `data/` directory.
- Preprocessing steps ensure normalization and handle missing values to prepare the data for modeling.

## Technologies Used
- **Programming Language**: Python
- **Machine Learning Framework**: TensorFlow/Keras
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Prerequisites
- Python 3.8+
- TensorFlow 2.x

## Setup Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/Bhavya-Arora-1/heart-disease-prediction.git
   cd heart-disease-prediction
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Prepare the dataset:
   - Place the heart disease dataset in the `data/` directory.
   - Ensure the dataset is in CSV format with appropriate headers.

4. Train the model:
   ```bash
   python train.py
   ```

5. Evaluate the model:
   ```bash
   python evaluate.py
   ```

## Results
- Model demonstrates robust performance in predicting heart disease.
- Includes AUC-ROC and confusion matrix visualizations.

## Contributions
Feel free to fork this repository, submit issues, or open pull requests for enhancements.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
