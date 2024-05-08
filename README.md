# EEG-Seizure-Detection-Model

This repository contains the work for an EEG Classification Model designed to analyze EEG data and distinguish between different categories. Utilizing the CHB-MIT EEG Database and the Bonn EEG Dataset, this project aims to aid in the diagnosis of epilepsy through effective classification of EEG signals.

## Project Overview

The objective of this project is to develop a robust classification model to effectively analyze and categorize EEG data, with a specific focus on identifying epileptic seizures. This involves comprehensive data preprocessing, feature extraction, and the deployment of machine learning or deep learning models tailored for EEG data analysis.

### Dataset Overview
The project utilizes two major EEG datasets:
- **CHB-MIT EEG Database**: Contains EEG recordings from individuals with epilepsy, including both seizure and non-seizure data.
- **Bonn EEG Dataset**: Focuses exclusively on epileptic seizure recordings.

### Methodology
The project follows a systematic approach:
1. **Data Preprocessing**: Using libraries like MNE to calculate statistical measures and prepare data for analysis.
2. **Feature Extraction**: Time and frequency domain features are extracted to capture distinctive EEG signal patterns.
3. **Model Selection and Training**: A Convolutional Neural Network (CNN) is used, leveraging TensorFlow and Keras for implementation.
4. **Evaluation**: The model is evaluated using accuracy metrics, and its performance is validated on unseen test data.

## Results
The final model demonstrates a promising accuracy of 85.71% on the test set, indicating its effectiveness in classifying EEG data and identifying epileptic seizures.

## Files in the Repository
- `FDA Project 3 Group 5.ipynb`: Jupyter notebook containing all the code for the model's development and evaluation.
- `Project_3_report.pdf`: Detailed project report that outlines the methodology, results, and discussions around the EEG classification model.

## How to Use
1. Clone this repository to your local machine.
2. Ensure you have Python and necessary libraries installed, such as TensorFlow, Keras, and MNE.
3. Run the `FDA Project 3 Group 5.ipynb` notebook to view the workflow and experiment with the EEG data and model.

## Visualizations
Visual representations of EEG data and model predictions are included in the Jupyter notebook to aid in understanding the model's performance and the underlying data patterns.

## Conclusion and Future Work
While the current model performs robustly, future improvements could involve exploring more complex neural network architectures, expanding the dataset, and refining feature extraction techniques to enhance accuracy and reliability further.

## License
This project is released under an MIT License.

## Contact
For any queries or discussions regarding this project, please contact any of the team members via LinkedIn.
