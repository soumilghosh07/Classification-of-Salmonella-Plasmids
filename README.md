# SVM Classification of Salmonella Plasmids

This project implements a Support Vector Machine (SVM) for the classification of Salmonella plasmids into two classes: virulent and non-virulent. The classification is based on features extracted from the plasmid sequences and associated gene ontology (GO) terms.

## Introduction

The classification of Salmonella plasmids into virulent and non-virulent classes is crucial in understanding the pathogenicity of different strains. This project aims to classify plasmids using machine learning techniques like SVM, leveraging features derived from both plasmid sequences and GO terms.

## Installation

To run the SVM classification experiment, follow these steps:

1. **Clone or Download:** Clone or download the repository to your local machine.
2. **Python Installation:** Ensure that you have Python installed on your system.
3. **Install Dependencies:** Install the required Python packages listed in the `requirements.txt` file using `pip install -r requirements.txt`.
4. **Download Dataset:** Obtain the dataset file `sal.xlsx` containing the plasmid sequences and gene ontology terms.
5. **Execute the Notebook:** Run the provided Python notebook `SALvp.ipynb` to execute the SVM classification experiment.

## How to Use

1. **Data Preprocessing:** The script will preprocess the dataset by reading the plasmid sequences and associated GO terms from the `sal.xlsx` file.
2. **Feature Extraction:** Features are extracted from the sequences using n-grams and from the GO terms using TF-IDF vectorization.
3. **Model Training:** The SVM model is trained using the extracted features and the virulence labels.
4. **Model Evaluation:** The trained model is evaluated on a test set, and classification performance metrics such as precision, recall, and accuracy are calculated.
5. **Result Analysis:** Analyze the classification results to understand the effectiveness of the SVM classifier in distinguishing between virulent and non-virulent plasmids.

## File Structure

The project directory contains the following files:

- `SALvp.ipynb`: Python notebook implementing the SVM classification experiment.
- `sal.xlsx`: Dataset file containing plasmid sequences and gene ontology terms.
- `README.md`: Markdown file containing detailed instructions and explanations.

## Experiment Details

The SVM classification experiment consists of the following steps:

1. **Data Loading:** The plasmid sequences and GO terms are loaded from the dataset file.
2. **Feature Extraction:** N-gram frequencies are calculated for the sequences, and TF-IDF vectors are generated for the GO terms.
3. **Feature Engineering:** Features are combined into a feature vector for each plasmid sample.
4. **Model Training:** The SVM model is trained using the feature vectors and corresponding virulence labels.
5. **Model Evaluation:** The trained model is evaluated on a test set to assess its classification performance.

## Results

The results of the SVM classification experiment include:

- **Classification Metrics:** Precision, recall, accuracy, and other classification metrics are calculated to evaluate the performance of the SVM model.
- **Confusion Matrix:** A confusion matrix may be generated to visualize the classification results and identify any misclassifications.


