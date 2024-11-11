# Clustering-Analysis
Overview
The task involves generating sequences, permutating and perturbing them, and then using these sequences to create data clusters. The following functions are developed:

Sequence Permutation: Randomly permutes a given sequence of characters, changing the order but preserving the characters.

Master Sequence Generation: Creates a sequence of a specified length and alphabet size, acting as the base for generating clusters.

Sequence Perturbation: Alters the master sequence by swapping elements based on a specified noise level, used to create variations.

Random Length Adjustment: Trims characters from the sequence’s endpoints by a random amount, giving sequences of varied lengths.

Cluster Data Creation: Generates a list of sequences representing inliers and outliers derived from a master sequence. Inliers have minimal perturbation, while outliers have significant alteration.

Clustered Data Generation: Produces clusters by creating multiple perturbed versions of the master sequence and using these as cluster centers, from which inliers and outliers are generated. Labels are assigned to each sequence based on the cluster they belong to.

Key Points
The project relies on controlled sequence manipulation to simulate clusters, valuable for clustering and classification model testing.
Libraries like numpy and random are used for sequence manipulation, while cvxopt supports optimization tasks.
The generated sequences follow specified noise levels to ensure differentiation between inliers and outliers, providing a diverse and realistic dataset for clustering models.
In essence, this project offers a structured approach to data generation for clustering analysis, simulating clusters through sequence perturbations and length variations. ​
