# Personalized Cancer Diagnosis Analysis

## Objective
The objective of this project is to classify cancer classes based on genetic variations/mutations and text-based clinical literature. The dataset contains information about genes, variations, and text associated with different cancer classes. Various machine learning models were applied to classify the genetic variations and the results were compared.

## Business Constraints
1. Errors can be costly: Misclassifying cancer classes can have serious implications for patient treatment and outcomes. Therefore, the model's accuracy and reliability are crucial.
2. Interpretability is very important: Understanding the reasoning behind the model's predictions is vital for gaining trust from healthcare professionals and making informed decisions.
3. No low latency is required: Since low latency is not a requirement, the focus can be on building accurate and interpretable models rather than real-time predictions.

## Data Overview
The data consists of two main datasets:
1. `training_variants`: Contains the following columns:
   - ID: Unique identifier for each data point.
   - Gene: The gene associated with the genetic variation.
   - Variations: The type of genetic variation.
   - Class: The target variable representing the cancer class.

2. `training_text`: Contains the following columns:
   - ID: Unique identifier, matching the ID in `training_variants`.
   - Text: Text-based clinical literature associated with each data point.

## Performance Metrics
1. Multi-Class Log-Loss: The log-loss metric measures the performance of a classification model by penalizing incorrect predictions. Lower log-loss values indicate better model performance.

2. Confusion Matrix: A confusion matrix provides insights into the classification accuracy of the model for each cancer class. It helps visualize true positives, true negatives, false positives, and false negatives.

## Project Files
The project includes the following files:
- `models_comparison.ipynb`: Jupyter Notebook containing the implementation of various machine learning models and the comparison of their results.
- `data_preprocessing.py`: Python script for data preprocessing and feature engineering.
- `model_evaluation.py`: Python script for evaluating the performance of the models.
- `requirements.txt`: Text file listing the required dependencies and their versions.
- `README.md`: This README file providing an overview of the project.

## Getting Started
To reproduce the results and analysis of this project, follow these steps:

1. Install the required dependencies listed in `requirements.txt`.
2. Run the `data_preprocessing.py` script to preprocess the data and engineer relevant features.
3. Open and execute the `models_comparison.ipynb` Jupyter Notebook to see the implementation of various machine learning models and their results.
4. Review the model evaluations and compare the performance using the multi-class log-loss and confusion matrix.

## Conclusion
The project aims to accurately classify cancer classes based on genetic variations and text-based clinical literature. By evaluating multiple machine learning models and analyzing their results, we aim to identify the best-performing model that meets the business constraints of accuracy and interpretability. The project emphasizes the importance of reliable and explainable models in the domain of personalized cancer diagnosis.

*(Note: This project was completed as part of an assignment for the machine learning course at appliedaicourse.com.)*

**Author:** [Rutik_parab]  
**Contact:** [rutikparab6@gmail.com]  
**License:** This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
