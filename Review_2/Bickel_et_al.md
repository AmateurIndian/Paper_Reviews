# Detecting Novel Associations in Large Data Sets

## Review by Sarjeel Yusuf: Bickel et al.

_Find full article [here](http://science.sciencemag.org/content/187/4175/398)._

### Main Contributions of the paper

- The paper introduces the Simpson paradox that results in contradicting results in trends depending on how the dataset is grouped and dissected.
- The paper illustrates the dangers of the Simpson's Paradox by providing the Chi squared values determine whether there is a Bias in a university admitting women to its departments or not. Here contradicting results are concluded depending on the data handling
- Remedies are also illustrated and measured to avoid the Simpson’s paradox is documented well. Since the Simpson’s paradox in the biased decisions towards women arises due to pre-determined assumptions. These assumptions are tackled in the later half of the paper.

### Paper’s significant contributions and potential use

- The fact that the paper is still relevant even after more than 40 years since its publication manifests its importance.
- Its use highlights the dangers of handling data in any type of research that can lead to incorrect correlation conclusions.

### Technical soundness of paper

- Scores for biasness are procured using Chi Squared which is quite elementary in its statistical abilities.
- However, This only works well when your datasets are large enough. To deal with datasets smaller than the appropriate value Fisher’s method is to be used[1].
- The paper also compares the contingency tables using the Fisher’s tables.
- Overall the methodology of the paper acknowledges the shortcomings of the methods used, as it is the purpose of the paper.

### Adequateness of experimental results and proposed improvements

- All Chi Squared values for conclusions made have been mentioned. This is because th Chi Squared method is elementary to use and hence all conclusions have been supported.
- TThe paper discusses various statistical methods to analyse the data, and adequate presents the conclusions derived.
- The methodology in Approach B successfully tackles the wrong assumptions made in Apprach A. For example the method described to calculate the expected frequencies on p.401 successfully tackles the falsity of assumption 2.

### Quality of the paper and how comprehensible it is

- In the paper the Chi Squared values are mentioned directly after each conclusion is made. However, this results in several values being thrown around and thus makes it hard to reference the values later.
- The Simpson’s paradox is adequate introduced after the false assumptions are made, leading guiding the reader in a constructive manner.

### Further Comments

I believe that the paper presents the variations in conclusions reached due to the different assumptions really well. For example the paper adequately chooses 85 departments due to the problems of logistics, out of the total number of departments. It also lists various assumptions and reasons for the behaviour of the certain demographics, and tackles these assumptions statistically in the various contingency tables presented. The paper could explore additional reasons to explain the behaviour of the demographic of applicants, but this may move out of the scope of the goal to find biases in campus admissions.

```
References:
1. B. Deshpande, “Chi Square Test Assumptions - fullexams.com,” Simafore, 13-Apr-2013. [Online]. Available: https://www.bing.com/cr?IG=AA921A4AE0544BF7AC9374BABA2140E1&CID=03F51114C68E680E1FE71A81C7286953&rd=1&h=KWgH820s5 6c6qn4nXf4SqFr-nakx3M5eMEVGQSpJVh8&v=1&r=https%3a%2f%2ffullexams.com%2fexam%2fchi-square-test-assumptions&p=DevEx,5044.1. [Accessed: 1-Feb-2019].

```

For more short reviews on machine learning and data mining scientific papers, please follow me on twitter [@SarjeelY](https://twitter.com/SarjeelY).
