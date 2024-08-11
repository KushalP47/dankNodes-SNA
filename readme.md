# Analysis of Social Media Bots vs Humans

This project analyzes the behavior of bots and humans on social media platforms. The analysis is based on the `dankNodes.ipynb` Jupyter notebook.

## Data

The data used in this project consists of social media posts from both bots and humans. Each post is associated with a user, and each user is labeled as either a bot or a human.

## Analysis

The analysis is divided into several parts:

1. **Data Loading**: The data is loaded from a CSV file into a pandas DataFrame.

2. **Graph Creation**: Three separate graphs are created using the NetworkX library, where each node represents a user and each edge represents a connection between two users. The three graphs represent different subsets of the data.

3. **Degree Distribution**: The degree distribution of the bot and human nodes is calculated and plotted for each graph. The degree of a node is the number of connections it has.

4. **Clustering Coefficient**: The clustering coefficient of the bot and human nodes is calculated and plotted for each graph. The clustering coefficient measures the extent to which the neighbors of a node are also neighbors of each other.

5. **Connected Components**: The number of connected components in each graph is calculated for both bot and human nodes. A connected component is a subgraph in which any two nodes are connected to each other by a path.

6. **K-Core Analysis**: The k-core of each graph is calculated for different values of k. A k-core is a subgraph in which each node is connected to at least k other nodes.

## Results

The results of the analysis provide insights into the behavior of bots and humans on social media platforms. For example, the degree distribution can show whether bots or humans tend to have more connections, and the clustering coefficient can show whether bots or humans tend to form more tightly-knit communities. The analysis of three separate graphs allows for a comparison of these metrics across different subsets of the data.

## Colab Link
[dankNodes - Colab Link](https://colab.research.google.com/github/KushalP47/dankNodes-SNA/blob/main/dankNodes.ipynb)
