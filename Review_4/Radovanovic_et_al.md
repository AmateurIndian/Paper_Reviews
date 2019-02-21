# Reverse Nearest Neighbors in Unsupervised Distance-Based Outlier Detection

## Review by Sarjeel Yusuf: Radovanovic et al.

_Find full article [here](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.699.9559&rep=rep1&type=pdf)._

### Main Contributions of the paper

- The paper challenges the view that high dimensionality results in distances measures used for outlier detection to become indiscernible. Hence hampering performance.
- The paper introduces the concept of anti-hubes and draws a relation between hubness and outliers.
- The idea is applied to show that the role of reverse nearest neighbours in unsupervised outlier detection. Hence contradicting the popular belief.

### Paper’s significant contributions and potential use

- The paper tackles the conventional belief that high dimensionality hinders outlier detection. The topic of outlier detection itself is a great number of applications as stated on pg. 1369.
- The ability to demonstrate the possibility of outlier detection in high dimensions increases the scope of the application. Hence its contribution is quite significant.

### Technical soundness of paper

- The paper proposes the ODIN method to illustrate the relationship between antibes and outliers. This method is already established by peers[1] and is appropriate in this case.
- Moreover the paper explores the idea of high dimensionality on the general idea of K-NN and makes use of conventional euclidean distance as stated on pg. 1377.
- Also, the paper takes into account Spearman and other correlation statistics to measure the relation between antihubs and outliers.
- The improved Algorithm eliminates need of determining arbitrary threshold values for the ODIN method.

### Adequateness of experimental results and proposed improvements

- The proposed methodology is implemented on both ‘low’ dimensions and ‘high’ dimensions and the results obtained, ie results on pg. 1375, add to the papers validity.
- Moreover, the correlation measures obtained using Spearman and Kendall show the relation between antihubs and outliers.
- Results on real data, pg 1378 are executed correctly and the graphs shown support the paper’s claim.

### Quality of the paper and how comprehensible it is

- The paper is divided into well constructed sections.
- The paper introduces the idea in parts, which allows the reader to digest information.
- Values are stated erratically, and hence it is hard for user to go back to refer to procured results.
- The paper also introduces related works, signifying the gravity of the work and the issues that have rises up in the past, highlighting the need for the proposed method.

### Further Comments

One of the greatest assumptions made is that the data has low noise. This restricts the applicability of the method on real life datasets. The algorithm could be coupled with conventional noise elimination algorithms. Moreover, the possibility of dimension reduction using concepts such PCA and Auto-Encoders should be compared with the proposed method. This will allow a better analysis of how effective RNN in unsupervised distance based outlier detection is, and whether it is worth preserving the high dimensionality of the data. It will also allow the comparison of complexity of algorithms and hence the audience can perform forms of cost-benefit analysis to decide what method to implement.

```
References:
1. S. Priya and M. Srinivasan, “RNN (Reverse Nearest Neighbour) in Unproven Reserve Based Outlier Discovery,” Global Research and
Development Journal for Engineering, vol. 1, no. 2, Jan. 2016.
```

For more short reviews on machine learning and data mining scientific reviews, please follow me on twitter [@SarjeelY](https://twitter.com/SarjeelY).
