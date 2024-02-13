<ins>Title</ins>: High-resolution downscaling with interpretable deep learning: Rainfall extremes over New Zealand

<ins>Year</ins>: 2022

<ins>Keywords</ins>: Statistical downscaling; Deep learning; Machine learning; Precipitation extremes

<ins>DOI</ins>: [Link](https://doi.org/10.1016/j.wace.2022.100525)

<ins>Variables (Input/Output)</ins>: 

* Gridded rainfall from Virtual Climate Station Network (VSCN)

Variables (Table 1 in text)
* convective available potential energy
* mean sea level pressure
* humidity
* air temperature
* zonal wind
* meridional wind
* vertical wind
* geopotential height
* total precipitation

Time periods
* Training period: 1980-2012
* Validation period: 2013–2016
* Testing period: 2017–2020

<ins>Method Details</ins>:

* Deep learning framework aiming to improve rainfall downscaling
* Reanalysis and surface weather parameters
* Prediction of rainfall and extreme rainfall events (downscaling rainfall)
* VCSN is know to have rainfall biases when observation network is sparse
* Best CNN model outperforms existing statistical approaches (temporal variability and mean & extreme rainfall)

<ins>Models</ins>:

Deep learning models
* CNNs
	- "Relatively simple CNN architectures with a more traditional encoder-decoder structure tended to give superior results"
	- "Relatively simple CNN architectures enables greater flexibility for implementing non-conventional loss functions and hyperparameter tuning of models"
* Evaluated models
	- Non-linear CNN
	- Linear CNN
	- Non-linear Gamma
	- Linear Gamma
* Interpretable deep learning
	- Grad-CAM
	- Able to target most relevant meteorological feature for predicting extreme rainfall events

<ins>General Comments</ins>: 

* Potential applicability of cGANs

<ins>Tag</ins>: Extreme; Rainfall; Deep learning

<ins>Relevant Projects</ins>: 

<ins>Suggestions \& Relevant resources</ins>: 

* [The Grad-CAM interpretable deep learning code](https://github.com/sicara/tf-explain)
* [ERA5 analysus, C3S](https://cds.climate.copernicus.eu/cdsapp#!/dataset/reanalysis-era5-pressure-levels)  
* "The VCSN data is developed and maintained by NIWA and can be
obtained through a data access agreement through correspondence with
the authors"

<ins>Other relevant documents/sources</ins>: 

<ins>Type (Based on GA, p.8)</ins>: Deep learning methods; Downscaling methods;
