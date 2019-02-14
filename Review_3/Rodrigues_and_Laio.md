# Clustering by Fast Search and Find of Density Peaks

## Review by Sarjeel Yusuf: Rodriguez and Laio

_Find full article [here](http://science.sciencemag.org/content/344/6191/1492)._

### Main Contributions of the paper

- The paper introduces a novel approach to clustering by using density peaks by defining clusters using two variables:
  - Local Density (ρ<sub>i</sub>)
  - Distance of center from other potential centers (d<sub>ij</sub>)
- Hence clusters are points for which δ<sub>i</sub> where δ<sub>i</sub> = max(d<sub>ij</sub>), is considerably high.
- Outliers identified by high δ and low ρ.
- Noise is determined as those points within d<sub>c</sub> which is the cluster border but have density lower than ρ<sub>b</sub>

### Paper’s significant contributions and potential use

- The clustering technique proposed by the paper can is short and efficient compared to the the traditional techniques present. This is because the manner in which points are associated to clusters, where traditional algorithms optimize an objective function iteratively.
- The new technique also allows Detection of non-spherical clusters, even for data not defined by set of coordinates. This covers the problems associated with other algorithms.
- Hence works for a more generalised distribution of data.

### Technical soundness of paper

- The paper does provide an innovative technique regarding clustering as it aims to uniformly define clusters and that too in an efficient manner.
- It utilizes the gaussian function to calculate the density of the clusters which is conventionally appropriate for the purpose[1].

### Adequateness of experimental results and proposed improvements

- The robustness of the algorithm is exemplified well through the various test runs conducted on real life data, and illustrated through the graphs used.
- The paper acknowledges the need for large sample data otherwise ρ is affected by noise. A solution is proposed on pg. 1495, and the algorithm is run on data with low amount of point using an exponential kernel based solution.
- The different domains to which the datasets pertain on page 1522 show that the ideas introduced by the authors are applicable in a wide range of industries.
- The plotting of rank illustrates the intuitive clustering method through finding maximum density. Thus supporting the concluding statements of the paper.

### Quality of the paper and how comprehensible it is

- The paper first introduces the shortfalls of traditional algorithms and then introduces its own technique. This thus reminds the reader of the traditional clustering techniques and their associated problems.
- Results are well illustrated such as that in Fig 4D which allows the reader to visualize the proposed technique on real life data.

### Further Comments

Since the clustering techniques are based on intuition, the algorithm works on the assumption that the center centers have high density of surrounding points. This assumption may not always hold. This is also acknowledged by the authors as low numbers of points may have degrading effects on the destiny. Moreover, the algorithm’s accuracy greatly relies on the value d<sub>c</sub> and the paper has not mentioned any effective way of deriving d<sub>c</sub>. This has been addressed by Dr. Wand and company[2].

```
References:
1. Shuliang Wang, Wenyan Gan, Deyi Li, Deren Li, Data Field for Hierarchical Clustering, International Journal of Data Warehousing and Mining,
7(4), 43-63
2. S. Wang, D. Wang, C. Li, and Y. Li, “Comment on "Clustering by fast search and find of density peaks",” arXiv.org, Jan. 2015.
```

For more short reviews on machine learning and data mining scientific reviews, please follow me on twitter [@SarjeelY](https://twitter.com/SarjeelY).
