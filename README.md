# NLP-Assignment-on-Text-Analysis-and-Topic-Discovery
NLP Assignment on Text Analysis & Topic Discovery using TF-IDF, Word2Vec, and LDA. Includes text preprocessing, feature extraction, word embeddings, and topic modeling with visualizations. Covers diverse data: earthquakes, e-commerce reviews, and watch brands.
## Dataset Used
- Mixed short texts: earthquakes in India, e-commerce reviews (Amazon/Flipkart), and watch brands (Japanese/Australian).
- Each line is treated as a document, cleaned and tokenized.

## Analysis Steps (Brief)
1. **Preprocessing**: lowercase, remove punctuation/numbers, stopwords; tokenize.
2. **TF-IDF**: compute corpus TF-IDF; extract top 10 words per document.
3. **Word2Vec**: train embeddings; find 5 most similar words; visualize with PCA.
4. **Topic Modeling (LDA)**: 4 topics; list top 5 words; assign topic per doc.
5. **Visualization**: PCA scatter for embeddings; `pyLDAvis` for LDA topics.

## Files
- `notebook.ipynb` — full code & outputs
- `README.md` — this file
-  saved `pyLDAvis` output

## How to Run
- Python 3.x; install: `pip install nltk gensim scikit-learn pyLDAvis matplotlib`
- Open notebook and run cells in order.
