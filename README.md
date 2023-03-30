# k-Nearest Neighbor Classifier Based On The Bonferroni Mean

BM-FKNN is a new generalized form of the fuzzy k-nearest neighbor (FKNN) classifier that uses local mean vectors and the Bonferroni mean. Because the parametric Bonferroni mean allows for problem-based parameter value fitting, the BM-FKNN classifier is easy to fit to different situations and uses. The BM-FKNN algorithm works well even when there are clear imbalances in how the data is distributed by class.


There are BM-FKNN algorithm functions (BM_FKNN.m) and Bonferroni mean computation functions (Bonferrni_mean.m) in Matlab. In addition to these files, there is also an example (Example.m) of how to use the BM_FKNN algorithm. Bonferroni_mean.m is needed to figure out the Bonferroni mean vectors of each class's set of closest neighbors.