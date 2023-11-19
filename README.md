# DEEP LEARNING
## Team information

 - Team name: node0 
 - Team members:
   - El-Ali Maya - BHI5LF
    - Simkó Máté - O3BMRX
  
## Project structure
 
The code can be found in jupyter notebooks in the *notebooks* folder, with the *{ego_user}.ipynb* format. Each notebook contains the complete pipeline for a given graph, which includes data loading, hyperparameter optimisation, training, training data visualisation and evaluation. These notebooks where designed to be run in [Google Colab]() and install all dependencies not in the base environment.

The best model for each ego graph can be found in the *models/{ego_user}* folders. These models also include the hyperparameters for the model and the training, as well as the training history.

The results of the hyperparameter optimasition are in the *hyperopt* folder with the *{ego_user}.csv* naming convention.
 

## Project description

The goal of this project is to develop a personalized friend recommendation system by using Graph Neural Networks (GNNs). You have to analyze data from social networks to suggest meaningful connections based on user profiles and interactions. 

## Related materials

- https://snap.stanford.edu/data/ego-Facebook.html
- https://docs.dgl.ai/
- https://medium.com/social-media-theories-ethics-and-analytics/facebook-graph-analysis-using-networkx-1e0741138a37
- https://medium.com/stanford-cs224w/friend-recommendation-using-graphsage-ffcda2aaf8d6

