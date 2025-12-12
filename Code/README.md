# Clustering-enhanced Local D-optimality

Users are encouraged to apply any clustering method to partition the dataset. Our approach was as follows:

1. **Partition:** We used PRM2020 labels to divide the dataset into 15 subsets.
2. **Train:** We trained 15 different ACE potentials (one for each subset).
3. **Evaluate:** We calculated 15 $\gamma$ values for each atom and selected the minimum value.
