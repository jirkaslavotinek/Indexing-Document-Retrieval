# Indexing-Document-Retrieval
Homework for MI-DDW FIT CTU

Implementation in MI-DDW Indexing & Document Retrieval.ipynb.

CSV file description:
- cos_sim_binary.csv
- cos_sim_tf.csv
- cos_sim_tfidf.csv
- euc_sim_binary.csv
- euc_sim_tf.csv
- euc_sim_tfidf.csv

These files contains similarity between each query and all documents.
- Queries - Rows
- Document numbers - Columns



results.csv:

- Contains results of F-measure, precision and recall.
- Each row represents query.

Header:
- Col1:  F-measure Cosine similarity Binary vectorizer
- Col2:  F-measure Cosine similarity Term frequency vectorizer
- Col3:  F-measure Cosine similarity TF-IDF vectorizer
- Col4:  F-measure Euclidean similarity Binary vectorizer
- Col5:  F-measure Euclidean similarity Term frequency vectorizer
- Col6:  F-measure Euclidean similarity TF-IDF vectorizer
- Col7:  Precision Cosine similarity Binary vectorizer
- Col8:  Precision Cosine similarity Term frequency vectorizer
- Col9:  Precision Cosine similarity TF-IDF vectorizer
- Col10: Precision Euclidean similarity Binary vectorizer
- Col11: Precision Euclidean similarity Term frequency vectorizer
- Col12: Precision Euclidean similarity TF-IDF vectorizer
- Col13: Recall Cosine similarity Binary vectorizer
- Col14: Recall Cosine similarity Term frequency vectorizer
- Col15: Recall Cosine similarity TF-IDF vectorizer
- Col16: Recall Euclidean similarity Binary vectorizer
- Col17: Recall Euclidean similarity Term frequency vectorizer
- Col18: Recall Euclidean similarity TF-IDF vectorizer
