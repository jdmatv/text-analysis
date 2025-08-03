# text-analysis

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains Jupyter notebooks created for the RAND School of Public Policy course, "420: Text Analytics."

## Course Description

Text analysis is a research strategy associated with a variety of methods that cross a variety of disciplines. Generally, text analysis involves computer-assisted analysis of large collections of purposefully collected text (corpora). It is computer-assisted in that it does not mean push-button results where an algorithm is meant to replace the researchers’ analytical insights. Rather, it means augmenting researchers’ insights and skills through machine reading of text collections too large for human reading and coding, e.g., large collections of interview transcripts, collections of doctrine and regulations, and collections of speeches/press releases.

This is a method-oriented class meant to give students the skills to conduct text analysis as part of public policy research. Students will ground themselves in text analysis theory; learn considerations for data selection and methods; develop proficiency in a variety of text analysis methods; and learn to present their findings to a general policy audience.

## Project Notebooks

This repository includes the following notebooks, each demonstrating different text analysis techniques:

-   **hw1.ipynb**: Demonstrates foundational text analysis techniques including data cleaning, tokenization, frequency analysis, and keyness testing. It compares a corpus of Kazakh poetry to the Kazakh civil code and visualizes their distinctiveness using TF-IDF and t-SNE, concluding with K-means clustering to identify thematic groups within the poetry.

-   **hw2.ipynb**: Focuses on computational sentiment and emotion analysis. This notebook uses the NRCLex library to compare the emotional content of English-translated poetry and legal text, employing statistical methods like ANOVA and Tukey's HSD test to identify significant differences.

-   **aboutness.ipynb**: Explores methods for determining the "aboutness" of a text corpus. It applies keyness analysis and n-gram extraction to compare political language and uses Latent Dirichlet Allocation (LDA) for topic modeling to uncover latent themes in political and research documents.

-   **embed_eda.ipynb**: Introduces advanced analysis using text embeddings. This notebook conducts exploratory data analysis on numerical representations of text from various research divisions, using dimensionality reduction techniques (PCA, t-SNE, UMAP) and cosine similarity to visualize and quantify the semantic relationships between different corpora.

## Methods and Techniques Covered

Across these notebooks, the following methods are applied:

-   Text Preprocessing (Cleaning, Tokenization, Stopword Removal)
-   Lexical Analysis (Frequency Distributions, Word Clouds)
-   Lexicogrammatical Analysis (N-grams, Collocations)
-   Keyness Analysis (Log-Likelihood)
-   Sentiment and Emotion Analysis (NRCLex)
-   Statistical Comparison (ANOVA, Tukey's HSD)
-   Topic Modeling (Latent Dirichlet Allocation - LDA)
-   Vector Space Models (TF-IDF)
-   Text Embeddings and Semantic Similarity (Cosine Distance)
-   Dimensionality Reduction and Visualization (t-SNE, PCA, UMAP)
-   Unsupervised Clustering (K-Means)

## Requirements

To run these notebooks, you will need a Python environment with Jupyter Notebook or JupyterLab installed. The core libraries used are:

-   `NLTK`
-   `scikit-learn`
-   `pandas`
-   `matplotlib` & `seaborn`
-   `wordcloud`
-   `umap-learn`
-   `NRCLex`

You can install these packages using pip:
`pip install nltk scikit-learn pandas matplotlib seaborn wordcloud umap-learn nrclex`

## Usage

1.  Clone this repository to your local machine.
2.  Ensure you have the required libraries installed.
3.  Launch Jupyter Notebook or JupyterLab from your terminal.
4.  Navigate to the cloned repository's directory and open any of the `.ipynb` files to view and run the analysis. Note that you may need to adjust file paths to the data corpora depending on your local setup.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
