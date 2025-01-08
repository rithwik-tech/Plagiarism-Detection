"""
# Plagiarism Detection and Text Analysis

This project performs text analysis and plagiarism detection on a collection of text documents. It leverages **TF-IDF** (Term Frequency-Inverse Document Frequency) for vectorizing the text data, and **cosine similarity** to detect potential plagiarism between documents. Additionally, it includes text classification using **Logistic Regression** and document clustering with **K-Means**.

## Features

- **Text Classification**: Classifies documents into predefined categories using **Logistic Regression**.
- **Document Clustering**: Groups documents into clusters using **K-Means**.
- **Plagiarism Detection**: Calculates cosine similarity between documents to detect potential plagiarism based on a similarity threshold.
  
## Technologies Used

- **Python**
- **scikit-learn** (for TF-IDF, Logistic Regression, K-Means, and Cosine Similarity)
- **matplotlib** (for visualizing clusters)
- **Google Colab** (for executing the code and uploading files)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/plagiarism-detection.git
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Upload your text files in the input directory and run the notebook in Google Colab.

Usage
Upload your text files (in .txt format) using Google Colab's file upload feature.
Run the notebook to:
Preprocess the text data.
Vectorize the documents using TF-IDF.
Apply Logistic Regression for text classification.
Cluster documents using K-Means.
Detect plagiarism by calculating cosine similarity between documents.
View the results to analyze potential plagiarism and document groupings.
Results
The output includes:

Cosine similarity scores between documents.
Clustered documents visualized in 2D.
Classification accuracy of the text classifier.
License
This project is licensed under the MIT License 
