### An alternative & better model than the CNN-based model in the paper https://doi.org/10.1109/TEM.2020.3021698 

The CNN-model in the corresponding paper overfits the data (check the distributions in the paper) and classify poorly when the training data is unbalanced. In this repository, I trained a simpler SVM classifier without using GloVE embeddings or parameter search.

The point is there might be simpler solutions, diving into complex models do not always return the best results. Here I should note that the main contribution of the paper does not lie with the success of the model, but possible applications of such an architecture in likewise tasks.

Here is the confusion matrix of the simple solution (details in the notebook). Cannot share paper's because of copyright issues.
![confusion matrix](https://github.com/SerhadS/alternative-solution/blob/main/github_alt_sol.PNG)


The corresponding model and data files are in TEM's GitHub repository: https://github.com/yw57721/IEEE-TEM-semantic-gap-2020
