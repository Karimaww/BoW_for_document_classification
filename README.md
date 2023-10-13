# BoW_for_document_classification
Bag of Words Models for Document Classification
The aim of this project is to equip us to design, train, evaluate, and utilize language processing models on two datasets:

- Extracts of dialogues between former presidents Chirac and Mitterrand. The task involves predicting, based on a sentence, whether it was spoken by one of these politicians. The data is imbalanced, with 86.9% of examples labeled Chirac and only 13.10% for Mitterand.
- Extracts of English film comments from the IMDB database, classified into two polarity classes, negative and positive. The goal is to analyze and predict the polarity of new comments. The data is balanced.

Throughout this work, we use the bag of words representation to extract vectors from the text data. What sets our implementation apart is the absence of manually defined strategies in the processing chain. Instead, we consider these strategies as hyperparameters within a model where raw input data is preserved.
