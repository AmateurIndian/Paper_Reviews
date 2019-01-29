# Detecting Novel Associations in Large Data Sets

## Review by Sarjeel Yusuf: Reshef et al.

_Find full article [here](http://science.sciencemag.org/content/334/6062/1518)._

### Main Contributions of the paper

● The paper introduces the MIC which is aimed at finding relations between features that do not necessarily follow any linear pattern.
● Usually aimed at high dimensional dataset with fewer observations than variables.
● Utilizes two heuristics:
○ Generality: Ability to detect a large range of relationships
○ Equitability: Similar scoring of noisy relationships

### Paper’s significant contributions and potential use

● The paper is significant as it introduces an alternative measure to the conventional ones already present such as the Pearson correlation.
● MIC is meant to work on a broader range of relationships with noise, even though recent tests have disproven its efficiency[1].

### Technical soundness of paper

● The paper is definitely innovative in its attempt to provide an alternative to the MIC
● The paper manages to prove the generality of MIC and other associated properties on page 1520.
● The properties of the MIC are not shared by the other methodologies that are mentioned and compared in pages 1520 through 1522, and in cases of Splines and Regression, MIC is much more effective in detecting the relations. However, the authors do acknowledge this fact ever so subtly.

### Adequateness of experimental results and proposed improvements

● A wide variety of relationships are shown, with varying levels of noise and this strengthens the validity of MIC in both generality and equitability, both the heuristics.
● The level of noise tested on though is limited, and later tests conducted by R. Tibshirani at Stanford University shows a breakdown of MIC when compared to Pearson Correlation[2].
● The different domains to which the datasets pertain on page 1522 show that the ideas introduced by the authors are applicable in a wide range of industries.
● The demonstration of MINE on real data allows the reader to see the importance of the idea’s application.

### Quality of the paper and how comprehensible it is

● The paper is well written and easy to follow, especially considering the fact that many results are to be visualized and the paper organizes the results well.
● The paper introduces the MIC in a structure that allows the reader to follow the constructs of MIC all the way to how MIC transforms into MINE and then the application of MINE on real datasets.

### Further Comments

As already seen, MIC does not perform better than the Pearson correlation when large amounts of noise are present in the dataset and often provides misleading results. This reduces the significance of the equitability heuristic since the method itself cant handle large amounts of noise. Nevertheless, on an adequate dataset, the MIC works quite well. The only issue may be that of computation power required, due to the algorithm that would be implemented. There are some scripts in R which attempt to provide the MIC service but are not that well implemented[3].

```
References:
1. N. Simon and R. Tibshirani, “COMMENT ON “DETECTING NOVEL ASSOCIATIONS IN LARGE DATA SETS” BY RESHEF ET AL,
SCIENCE DEC 16, 2011,” sciencemag, vol. 334. pp. 1518–1524, 16-Dec-2011.
2. 2 R. Tibshirani, “MIC to Pearson comparison.” 08-Jan-2012, http://statweb.stanford.edu/~tibs/reshef/script.R.
3. Marc, “Maximal Information Coefficient (Part II),” R-bloggers, 17-Sep-2014. [Online]. Available: https://www.r-bloggers.com/maximal
-information-coefficient-part-ii/. [Accessed: 20-Jan-2019].
```

For more short reviews on machine learning and data mining scientific reviews, please follow me on twitter [@SarjeelY](https://twitter.com/SarjeelY).
