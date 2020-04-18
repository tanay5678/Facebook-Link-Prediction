# Facebook-Link-Prediction

Data - Facebook Recruiting Competition.
train.csv contains the directed social graph, represented in a 2-column CSV (source_node, destination_node)
test.csv contains a list of nodes to recommend other nodes to in a 1-column CSV (source_node)
Problem Statement - Predicting Links 

The things I've learned from this problem -
  1.How to handle the cold start problem? - In the dataset, there were only two columns and no labels(target variables). It was                                             unsupervised data which I converted into supervised data.
  2.Graph Data - I never worked on graph data so it was challenging to extract information from the data. I used libraries to                    visualize the graph to understand the data.
  3.Feature Engineering - I have created a lot of features from scratch and for some feature I used libraries. I searched for                             some papers to create some features.

In the end, I plotted feature importance to check how which feature helps to model to predict the links.
