# A Fast Method of Statistical Assessment for Combinatorial Hypotheses Based on Frequent Itemset Enumeration

## Review by Sarjeel Yusuf: Minato et al.

_Find full article [here](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.649.1504)._

### Main Contributions of the paper

- The paper introduces an enhanced version of the LAMP technique that aims to solve the problems
  associated with analyzing null hypothesis using p-values
- Major issues with using p-values is as follows:
  - The computation burden of computing frq(X) in the BackTracking algorithm for finding frequent itemsets
  - False positive problems caused when dealing with multiple tests
  - The exponential complexity which is incurred when comparing j combinations out of n items
- LAMP developed as p-value correction to Bonferroni correction in regards to multiple tests.
- However LAMP calls LCM algorithm repeatedly which makes it highly time complex.
- New method introduces Support Increase Algorithm, finds all itemsets for value σ and re-starts backtracking for σ + 1.

### Paper’s significant contributions and potential use

- Throughout most of academia, the p-value as a measure for the significance of the hypothesis is imperative, but due to the cost of computation, calculating p-value is arduous
- Even the improved LAMP algorithm is not substantial to an extent as it calls LCM several times.
- Hence, any improvement to the ability to statistically analyse the validity of a hypothesis has effects in the entire scientific community, irrespective of what field of science and whal level of research.

### Technical soundness of paper

- New algorithm based on LAMP correctness procedure which has already been analysed and peer reviewed, and proved its worth through practical demonstrations[1].
- Mathematical foundations of algorithm are well demonstrated and correct to my best understanding.
- However, the scope of the algorithms effectiveness is limited to calculating p-value with Fisher’s test.
- The practical demonstration of the paper is also limited, and should have used various datasets to illustrate the general applicability of the algorithm.

### Adequateness of experimental results and proposed improvements

The paper does not provide a lot of practical experimental results, however the mathematical reasoning
and algorithm provided theoretically correct the shortcomings of the current LAMP algorithm.

### Quality of the paper and how comprehensible it is

- The paper systematically introduces concepts on which the new Support Increase Algorithm is based
- This provides all necessary background information to reader
- The paper then provides and explains all mathematical grounding in a clear manner, allowing the reader to fully understand the new method proposed. Also supported with experimental backing.

### Further Comments

I believe that the idea presented by the paper is profound and innovative, yet so simple. However, as even the writers agree, the new algorithm, may have higher memory complexity, which they aim to solve, as well as limited scope. The authors of the paper acknowledge this and mention hopes of applying the proposed algorithm with other forms of p-value tests.

```
References:
1. Terada, Aika, LAMP, (2015), GitHub repository, https://github.com/a-terada/lamp.
```

For more short reviews on machine learning and data mining scientific papers, please follow me on twitter [@SarjeelY](https://twitter.com/SarjeelY).
