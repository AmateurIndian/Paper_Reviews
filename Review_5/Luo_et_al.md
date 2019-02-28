# An Efficient Non-Negative Matrix-Factorization-Based Approach to Collaborative Filtering for Recommender Systems

## Review by Sarjeel Yusuf: Luo et al.

_Find full article [here](https://ieeexplore.ieee.org/document/6748996)._

### Main Contributions of the paper

- The paper introduces an enhanced concept of Non-Negative Matrix Factorization with regards to
  collaborative filtering in the domain of recommender systems.
- Considering the features that Recommender Systems consist of, the aim is to find patterns based on
  item, user, and item-user interactions, and matrix factorization aims at finding the latent patterns.
- Current MF approaches are not fit for the sparsity in user/item data, hence the focus on a CF model
  with a single element grounded method. This aims to increase both accuracy and reduce computation
- This approach involves the introduction of the SNMF, which is equivalent to some extent to WNMF,
  except that since the computation is performed on the known ratings, ‘W’ is no longer required.
- Also modifies the integration of Tikhonov’s Regularization technique in an attempt to increase accuracy,
  dealing with sparse datasets.

### Paper’s significant contributions and potential use

- As the paper itself mentions in the introduction, recommender systems are becoming a large part of the
  society, and hence implementing efficient and accurate recommender systems would prove to be a
  huge asset to any industry.
- The paper’s proposed method could potentially do away with traditional MF methods that are not
  adequate for the industry.
- Working with SNMF and Tikhonov's Regularization, powerful lightweight recommender tools developed.

### Technical soundness of paper

- The paper presents the math necessary to support the claim in Section III.
- Theoretically the paper does illustrate how the ‘novel’ idea proposed is more accurate and
  computationally less demanding.
- However, considering how long recommender systems and CF methods are discussed in literature,
  there are similar ideas proposed [1]. Nevertheless, the aim to solve the sparsity problem should be
  appreciated always.
- Experimental results make use of error measures such as RMSE which is a common error measure in
  this domain, and hence provides a clear standing of the method.

### Adequateness of experimental results and proposed improvements

Section IV demonstrates the practical use applications on several datasets. One of the datasets is the MovieLens dataset which is commonly used for testing CF models. Hence it provides a clear understanding for those who worked with recommender systems of the impact of the proposed model.

### Quality of the paper and how comprehensible it is

- The paper first introduces the current NMF systems, and highlights their shortfalls, and then introduces
  the proposed method.
- The math supporting the idea is splurged all over the paper, and it makes difficult in reading the paper.
- Visualization of results in Section 4 clearly presents the intended results and ideas of the authors.

### Further Comments

I feel that with recommender systems being around for as long as they have, the ideas proposed may resemble other methods in the literature. These methods can be analogous to methods in Computer Vision.

```
References:
1. Lin, Chih-Jen. "Projected gradient methods for nonnegative matrix factorization." Neural computation 19.10 (2007): 2756-2779.
```

For more short reviews on machine learning and data mining scientific papers, please follow me on twitter [@SarjeelY](https://twitter.com/SarjeelY).
