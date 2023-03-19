# Amazon Apparel Recommendations

This Jupyter Notebook demonstrates how to generate product recommendations for Amazon apparels using content-based recommendation techniques. We explore different text-based approaches to create meaningful recommendations for users based on the textual data associated with each product. The following approaches are covered:

1. Bag of Words (BoW)
2. Term Frequency - Inverse Document Frequency (TF-IDF)
3. Word2Vec
4. Weighted Word2Vec

## Dataset

The dataset used in this project consists of Amazon apparel product information, including features such as ASIN, brand, color, image URL, product type, title, and formatted price. The dataset is available in the form of a JSON file.

## Prerequisites

To run this Jupyter Notebook, you need to have the following Python libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- nltk
- gensim
- PIL

## Structure

The notebook is divided into the following sections:

1. Data Loading: Load the dataset using pandas and explore the features.
2. Data Preprocessing: Clean and preprocess the data by removing duplicates, handling missing values, and reducing the dataset size.
3. Feature Engineering: Extract useful features from the data and create a clean and structured dataset.
4. Recommendation Techniques: Implement and compare different recommendation techniques based on textual data, such as BoW, TF-IDF, Word2Vec, and Weighted Word2Vec.

## Usage

To use this notebook, download the dataset and update the file path in the notebook accordingly. Follow the steps in each section and execute the code cells to generate recommendations for Amazon apparel products using the various techniques.

## Acknowledgements

This project is inspired by the "Amazon Fine Food Reviews" dataset from Kaggle and the "Applied AI Course" by Applied Roots.