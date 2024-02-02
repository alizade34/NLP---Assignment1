# Wikipedia Text Classification Project

## Overview

This project aims to classify texts retrieved from Wikipedia into two categories: geographic and non-geographic. The classification is performed using Natural Language Processing (NLP) techniques and machine learning algorithms.

## Project Structure

- `wikipedia_text_classification.py`: Python script containing the implementation for text classification.

## Setup and Usage

1. **Python Environment Setup:**
   - Ensure you have Python 3.x installed on your system.
   - Install the required libraries using pip:
     ```bash
     pip install nltk beautifulsoup4 pandas scikit-learn
     ```

2. **Run the Script:**
   - Execute the `wikipedia_text_classification.py` script in your preferred Python environment.

## Implementation Details

- The script retrieves Wikipedia articles from specified categories using the Wikipedia API.
- Text preprocessing is performed to clean and prepare the retrieved text data for classification. This includes tokenization, stop word removal, lemmatization, and stemming.
- Feature extraction is done using CountVectorizer from scikit-learn to convert the preprocessed text into a bag-of-words representation.
- Two classification models, Naive Bayes and Logistic Regression, are trained using the extracted features.
- The trained models are evaluated using accuracy scores and classification reports to assess their performance.

## Data Retrieval and Preprocessing

- Wikipedia articles are retrieved based on specified categories, including geographic and non-geographic topics.
- Text preprocessing techniques such as tokenization, stop word removal, lemmatization, and stemming are applied to clean the text data.

## Model Training and Evaluation

- The dataset is split into training and testing sets using train_test_split from scikit-learn.
- Multinomial Naive Bayes and Logistic Regression classifiers are trained using the training data.
- Model performance is evaluated using accuracy scores and classification reports on the testing data.

## Contributions and License

Contributions to the project are welcome! If you encounter any issues, have suggestions for improvements, or would like to contribute new features, feel free to submit a pull request or open an issue on the GitHub repository.

This project is licensed under the MIT License.

"# NLP---Assignment1" 
