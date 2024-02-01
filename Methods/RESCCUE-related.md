<ins>Title</ins>: RESCCUE Project related data

<ins>Year</ins>: 

<ins>Keywords</ins>: Weather observations; Homogenization techniques; 

<ins>DOI</ins>: [CORDIS](https://cordis.europa.eu/project/id/700174) 

<ins>Variables (Input/Output)</ins>:
* Raw weather observations
* Quality-treated weather observations

<ins>Method Details</ins>: 

A two-way quality control methodology is applied generally to all weather data sources prior to their use.
1. Basic consistency. Direct rejection of self-evident wrong values: for example,
negative values for precipitation.
2. Atypical values or ‘outliers’. Unusual values within a data set: values that could come from different sources of data or values that could have been generated in a different way from the rest of the data. In this case, the theoretical difficulty of their recognition depends on our definition of “atypical”. In practice, the recognition is generally referred to values whose absolute magnitude is unusually high.

The way to proceed of the homogeneity test that we have used is based on the method
developed by [Monjo et al.(2013)](https://zenodo.org/records/6525733):
1. To measure how similar is data belonging to one year to data belonging to another year, it is used a distribution comparison test based on the Kolmogorov-Smirnov (KS) test. The KS test is a non-parametric statistical test (it does not presuppose distributions of the studied variable) which provides a p-value that can be used as a measurement of the similarity between two years. Values which are close to 0 show that two years have a value distribution very similar and we can infer that there is not an inhomogeneity between them. The lower value for Log(KS), the greater is the probability of inhomogeneity between two consecutive values.

2. If one year has been selected as possible indicator of inhomogeneity, then it is subjected to another test (“Similarity between years”). Once we select the year that possibly presents an inhomogeneity and the following one, we figure out the p-value of every year of the series respect those two years. If a jump or a break shows up between all those p-values in the years that we are considering, then we can infer that there is a true inhomogeneity for all the series.

<ins>Models</ins>:

<ins>General Comments</ins>: 
* Quality checking performed by FIC in ICARIA for all the weather data gathered
* Homogeisation techniques performed by FIC in ICARIA for all the weather data gathered

<ins>Tag</ins>: Gap-filling

<ins>Relevant Projects</ins>: 

<ins>Suggestions \& Relevant resources</ins>: [Detection of inhomogeneities in daily data: a test based on the Kolmogorov-Smirnov goodness-of-fit test](https://zenodo.org/records/6525733)

<ins>Other relevant documents/sources</ins>: 

<ins>Type (Based on GA, p.8)</ins>: Gap-filling method