# Amazon Electronics Reviews Analysis

This project aims to extract insights from the Amazon Electronics Reviews dataset. The analysis includes product and rating insights, machine learning models for review classification, and collaborative filtering for recommendations.

## Instructions to Run the Code

1. **Download the Dataset:**
   - Obtain the dataset from [UCSD's Amazon Dataset](https://cseweb.ucsd.edu/~jmcauley/datasets/amazon_v2/).
   - Download the `Electronics` subset (5-core) and the `metadata` JSON file.

2. **Load and Preprocess the Dataset:**
   - Run `Dataset_load.ipynb` to load and preprocess the dataset.
   - Note: If you prefer, you can skip this step and use the preprocessed dataset `merged_df.pkl` directly for the other notebooks.

3. **Run the Following Notebooks:**

   3.1 **HeadPhone Analysis.ipynb**
   - Analyzes products and ratings given by users.

   3.2 **Analysis Machine Learning Models.ipynb**
   - Utilizes Word2Vec to create embeddings of the reviews.
   - Applies various machine learning models to classify reviews based on ratings (Good, Average, Bad).

   3.3 **Collaborative Filtering.ipynb**
   - Builds User-User and Item-Item recommender systems using collaborative filtering.
