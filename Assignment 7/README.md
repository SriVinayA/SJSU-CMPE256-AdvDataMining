# TF-IDF Calculation Project

This repository contains the implementation and results of the Term Frequency-Inverse Document Frequency (TF-IDF) calculation on a given corpus of text documents.

## Overview

TF-IDF is a statistical measure used to evaluate the importance of a word to a document in a collection or corpus of documents. The importance increases proportionally to the number of times a word appears in the document but is offset by the frequency of the word in the corpus.

This project includes a term frequency matrix and scripts to calculate the TF-IDF for each term-document pair in the matrix.

## Files

- `term_frequency_matrix.png`: An image containing the term frequency matrix used as the input data.
- `TF_IDF_of_a_Document_matrix_.ipynb`: A Jupyter notebook with the complete code and explanation for the TF-IDF calculation.

## Calculation

The calculation of TF-IDF was performed in two steps:

1. **Term Frequency (TF)**: The frequency of each term in a document was divided by the total number of terms in the document.

2. **Inverse Document Frequency (IDF)**: The log of the number of documents divided by the number of documents that contain the term was calculated.

The final TF-IDF score for a term in a document was obtained by multiplying its TF with its IDF.

## Usage

To replicate the calculations or to apply the methodology to a new set of documents, follow these steps:

1. Replace the `term_frequency_matrix.png` with your term frequency matrix image.
2. Run the Google Colab `tfidf_calculation.ipynb` to perform the calculations.
3. View the results in the notebook or export them to a CSV file as demonstrated.

## Requirements

- Python 3.x
- Google Colab
- Libraries: pandas, numpy

## Contribute

Contributions to this project are welcome. To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Commit your changes.
4. Push to your branch.
5. Submit a pull request.

## Contact

For any further queries or discussions regarding this project, please open an issue in this repository.

Thank you for checking out this TF-IDF calculation project!
