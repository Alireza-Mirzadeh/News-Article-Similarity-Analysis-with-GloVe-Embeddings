# **News Article Similarity Analysis with GloVe Embeddings**

## **Overview**

This project analyzes the similarity between news articles by leveraging **GloVe word embeddings**, **PCA** for dimensionality reduction, and **KMeans clustering** for grouping articles with similar topics. The project also generates **word clouds** for each cluster, providing visual insights into the most frequent terms in each group.

## Data Source
The news article dataset was sourced from Mage AI's public datasets repository:

`news_articles.csv` - Source: [Mage AI Datasets](https://github.com/mage-ai/datasets)

## **Key Features**

- **Preprocessing**: Lower casing, tokenization and cleaning of article texts (removal of stopwords and non-alphabetic tokens).
- **GloVe Embeddings**: Utilizes pre-trained GloVe word vectors to represent words in articles as dense vectors.
- **Dimensionality Reduction**: PCA is applied to reduce the high-dimensional word vectors to 2D for visualization.
- **Clustering**: K-Means with elbow method optimization is used to cluster news articles based on their GloVe embeddings.
- **Visualization**: Interactive scatter plots of the clusters and word clouds for each group.

## **Technologies Used**

- Python
- Pandas
- Numpy
- Scikit-learn (for PCA and KMeans)
- WordCloud
- Matplotlib, Seaborn (for plotting)

## 📊 Results and Interpretation

### 1. Dimensionality Reduction and Clustering
**PCA Projection with K-Means Clustering**  

![PCA_Projection_with_K-Means](./Results/most_in_demand_skills.png)

### 2. Cluster Analysis via Word Clouds
#### Cluster 0

![cluster0](./Results/y.png)

- **Dominant Terms**: "time", "life", "people", "love", 

#### Cluster 1

![cluster1](./Results/z.png)

- **Dominant Terms**: "state", "republican", "people", "president"

#### Cluster 2

![cluster2](./Results/p.png)

- **Dominant Terms**: "film", "star", "actor", "show"

## Acknowledgments
The inspiration for this project were derived from the **Natural Language Processing (NLP) Workshop** available on YouTube. Special thanks to the creators for their insightful content and practical demonstrations, which guided the development of this project.

**Course Title**: "Natural Language Processing Workshop"  
**Channel Name**: Reza Shokrzad - Data Science & AI  
**YouTube Link**: [NLP | Word Embedding](https://www.youtube.com/watch?v=mxDPm_P-ggU&list=PLIoM6vIerI9o76lRcFzoAd2XEufjEOT4V&index=2)


  
