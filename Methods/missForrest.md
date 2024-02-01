<ins>Title</ins>: Assessing automated gap imputation of regional scale groundwater level data sets with typical gap patterns

<ins>Year</ins>: 2023

<ins>Keywords</ins>: Time series; Missing values; Gap filling; Droughts; Abstraction


<ins>DOI</ins>: [Link](https://doi.org/10.1016/j.jhydrol.2023.129424)

<ins>Variables (Input/Output)</ins>: 

<ins>Method Details</ins>: 
* missForrest 
	* non-parametric
	* iterative
	* random forrest algorithm
	* automatic
	* unsupervised missing imputations
	* no assumptions about data distribution
	* no need for tuning parameters 
* imputePCA
	* principal components methods on incomplete datasets

*  Metrics
	* NSE (Nash-Stucliffe efficiency)
	* NRMSE(normalized root mean square error)

<ins>Models</ins>:

<ins>General Comments</ins>: missForrest, imputePCA | Materials (hierarchical cluster analysis with a binary measure (R package, Agnes function)) 

<ins>Tag</ins>: Method; Water; Data-gaps

<ins>Relevant Projects</ins>: 

<ins>Suggestions \& Relevant resources</ins>: 

<ins>Other relevant documents/sources</ins>: 

<ins>Type (Based on GA, p.8)</ins>: Data-gap method(s)
