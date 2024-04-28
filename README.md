# Scientext: Streamlining Essay Analysis Using Natural Language Processing

Scientext is an Automated Essay Scoring (AES) system designed to reduce the burdensome and subjective task of essay grading for educators. By employing advanced natural language processing (NLP) techniques and machine learning algorithms, Scientext provides an objective, automated evaluation of student essays, ensuring consistency and immediacy in feedback.

## Abstract
In educational environments, essay grading is critical yet resource-intensive, requiring considerable time and effort to maintain consistency and objectivity. Scientext automates this process by analyzing essays and predicting scores using NLP and machine learning techniques such as Linear Regression and AdaBoost. The system shows high correlation with human assessments, thus significantly reducing grading time, enhancing evaluation consistency, and supporting dynamic learning processes.

## Features
- **Data Preprocessing:** Cleansing text, removing special characters, and tokenizing.
- **Feature Extraction:** Analyzing structural and lexical features like syntax complexity and orthographic accuracy.
- **Anonymization:** Employing Named Entity Recognition to replace personal identifiers with placeholders.
- **Model Training:** Utilizing various regression and classification models to predict essay scores.
- **Performance Evaluation:** Using metrics such as mean squared error and Cohen's kappa score for validation.

## Technologies Used
- **NLP Tools:** Advanced text processing including tokenization, lemmatization, and syntactic analysis.
- **Machine Learning Models:** Linear Regression, AdaBoost, among others for predictive modeling.
- **Data Handling:** Extensive use of Python libraries like NLTK for NLP operations, and Scikit-learn for machine learning workflows.

## Dataset
The system is trained on a comprehensive dataset from the 2012 Hewlett Foundation Automated Essay Scoring Kaggle competition, featuring essays from various educational levels and styles.

## Installation and Usage
Ensure you have Python installed with necessary libraries like `nltk`, `sklearn`, and `pandas`. Clone the repository from [GitHub](https://github.com/ayesha-mohsin/Scientext), navigate to the directory, and run the main script to process the essays through the Scientext system.

## Contributions
This project is co-developed by:
- **Shaik Ayesha Mohsin:** Focus on integrating Latent Semantic Analysis and feature engineering.
- **Areeba Hassan:** Responsible for incorporating Text Embeddings, model training, and performance evaluation.

## License
This project is open-source under the MIT license.

For detailed insights and methodology, refer to the extensive documentation within the repository or contact the contributors through the GitHub project page.

---
