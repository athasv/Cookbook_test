<ins>Title</ins>: A three-dimensional gap filling method for large geophysical datasets: Application to global satellite soil moisture observations

<ins>Year</ins>: 2012

<ins>Keywords</ins>: Remote sensing; Soil moisture; Gap filling; Penalized least square regression; Discrete cosine transform

<ins>DOI</ins>: [Link](https://doi.org/10.1016/j.envsoft.2011.10.015)

<ins>Variables (Input/Output)</ins>: Works for large spatiotemporal datasets (both spatial & temporal variability)

<ins>Method Details</ins>: A penalized least square method based on three-dimensional discrete cosine transforms (DCT-PLS), for the purpose of filling data gaps in large spatio-temporal datasets (example: soil moisture satellite data) is introduced. This DCT-PLS method has some novel features with respect to other gap filling methods. It is a method of full three-dimensionality, and thus explicitly utilizes both spatial and temporal information of the dataset to derive the statistical model and predict the missing values. Instinctively, this strategy is preferable for spatio-temporal datasets rather than using only spatial or temporal modeling. The statistical modeling process is completely controlled by one smoothing parameter which is easy to specify and eliminates the need for complicated model parameterizations.

<ins>Models</ins>:

<ins>General Comments</ins>: 
* Penalized least-square method based on three-dimensional discrete cosine transforms
* Soil moisture datasets (affects drought and heat conditions in low atmosphere)
* VU University-NASA (VUA-NASA) global volumetric soil moisture product
* 2003--2009 period gridded at 0.50 degree resolution
* DCT-PLS, the approximation of the derived model to the existing values is completely controlled by the smoothing parameter's, which can be any positive value
* Geophysical datasets spatially have very large differences in magnitude, an over-ﬁtting might occur with an extremely small smoothing parameter, leading to poor prediction performance.
* Conventional methods: *the hardest part is to fill the continuous gaps*.
* Insert synthetic gaps: data-gaps which are temporally intermittent
* A post-validation by introducing synthetic gaps to ensure the reliability of the ﬁlled-in in values


<ins>Tag</ins>: Gap-filling; Remote Sensing

<ins>Relevant Projects</ins>: 

<ins>Suggestions \& Relevant resources</ins>: 

<ins>Other relevant documents/sources</ins>: [BiomeCardio](http://www.biomecardio.com/matlab/smoothn.html)

<ins>Type (Based on GA, p.8)</ins>: Gap-filling method