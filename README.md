# Document Indexing and Retrieval Project

This project implements a search engine based on lemmatization and stemming techniques, as well as a Word2Vec model for query and document processing. It utilizes libraries like NLTK, SpaCy, and Gensim to perform linguistic analyses and similarity calculations.

## Project Contents

The project consists of three main files:

1. **Indexation_Lemmatisation+Stemmer.ipynb**:
   - This notebook performs the indexing of queries and documents using lemmatization and stemming techniques.
   - The steps include:
     - Importing and cleaning the queries and documents.
     - Creating a filtered dictionary.
     - Creating an inverted index file.
     - Exporting the results.

2. **Moteur_lemm+stem.ipynb**:
   - This notebook uses the inverted index files created in the first file to calculate cosine similarity between queries and documents.
   - The steps include:
     - Reading vectors from the inverted index files.
     - Calculating cosine distances.
     - Exporting similarity results to a file.

3. **Indexation_word2vec.ipynb**:
   - This notebook utilizes Word2Vec to generate document and query vectors.
   - The steps include:
     - Importing and preprocessing the data.
     - Creating Word2Vec and Doc2Vec models.
     - Searching for the most similar documents for each query.
     - Exporting the results.

## Prerequisites

To run this project, make sure to have the following libraries installed:

- pandas
- numpy
- nltk
- spacy
- gensim
- scipy

You should also download the necessary models for SpaCy and NLTK.

## Usage

1. Run the **Indexation_Lemmatisation+Stemmer(1).ipynb** file to index your documents and queries.
2. Next, run **Moteur_lemm+stem.ipynb** to calculate cosine similarities and export the results.
3. Finally, run **Indexation_word2vec.ipynb** to generate Word2Vec vectors and perform searches.

## Results

The search results will be exported to the following files:

- `RES_LemmStem.REL`: results based on lemmatization and stemming.
- `RES_word2vec.REL`: results based on the Word2Vec model.

## Conclusion

This project demonstrates the application of text processing techniques to build a search engine capable of indexing documents and accurately responding to queries. Lemmatization, stemming, and Word2Vec models are utilized to enhance the quality of results.
