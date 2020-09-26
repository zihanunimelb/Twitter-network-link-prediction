# COMP90051 Statistical Machine Learning - Project 1 

In this project, we do link prediction based on data of a partial crawl of the Twitter Social Network from several years ago.

## Data Set
The training network is a partial crawl of the Twitter social network from several years ago. The nodes in the network—Twitter users—have been given randomly assigned IDs, and a directed edge from node A to B represents that user A follows B. The training network is a subgraph of the entire network.
The test data is a list of 2,000 edges, and your task is to predict if each of those test edges are really edges in the Twitter network or are fake ones. 1,000 of these test edges are real and withheld from the training network, while the other 1,000 do not actually exist.

## Run Order

Generate positive samples and negative samples and the undirected features of trainset, testset we own generated and testset in kaggle
```
Sample&Feature1.ipynb
```

Generate the directed features of trainset, testset we own generated and testset in kaggle
```
feature2.ipynb
```

Append the data of undirected and directed features to a single csv file
```
finalsets.ipynb
```

Use different models to train the data and get prediction result
```
model.ipynb
```

