<ins>Title</ins>: Spatio-Temporal Downscaling of Climate Data Using Convolutional and Error-Predicting Neural Networks

<ins>Year</ins>: 2021

<ins>Keywords</ins>: Machine Learning; Climate Data; Super-resolution; Convolutional Neural Networks

<ins>DOI</ins>: [Link](https://doi.org/10.3389/fclim.2021.656479)

<ins>Variables (Input/Output)</ins>: Raster data. Models used: ERA-Interim and EC-Earth 

<ins>Method Details</ins>: 

* General Details
    * Capabilities of neural networks to reconstruct high-resolution data from given low-resolution simulations
	* legacy low-resolution simulations can be downscaled to reconstruct high-resolution detail
	* past observations that have been taken at lower resolutions can be increased to higher resolutions, opening new analysis possibilities
	* Networks
		* Low-Frequent Data: Residual-Predicting Network(RPN)
		* High-Frequent Data: Deconvolutional Network(DCN)
	* Downscaling of high-frequent precipitation fields: Precipitation

* Conclusions
	* Suitability of deep learning for the reconstruction of numerically-simulated and observed low-resolution data in both space and time
	* Slowly-changing information, such as temperature can be adequately predicted through an error-predicting network
	* Larger variations in both space and time, such as precipitation, require a different approach and cannot profit from residual learning
	* Developed: convolutional architecture with residual skip connections in order to extract features at different scales and to combine them in the subsequent deconvolution
	* Future potential:
	 	 * Optimal downscaling parameters
		 * PointNet-like convolutions
		 * Weighting individual samples
		 * Inclusion of additional regularizers into the loss function to utilize physical conservation laws that need to hold during the simulations
	 * Apply residual predictions to dynamical downscaling models
	
<ins>Models</ins>:

<ins>General Comments</ins>: Supervised Deep learning CNN1 and CNN10 | [
VALUE: COST Action ES1102 (2012-2015)	]("http://www.value-cost.eu/data#netcdf") | [ECAD]("https://www.ecad.eu/download/ensembles/download.php")

<ins>Tag</ins>: Generic

<ins>Relevant Projects</ins>: 

<ins>Suggestions \& Relevant resources</ins>: [Configuration and Intercomparison of Deep Learning Neural Models for Statistical Downscaling](https://gmd.copernicus.org/preprints/gmd-2019-278/gmd-2019-278.pdf)

<ins>Other relevant documents/sources</ins>: [GitHub - Convolutional Downscaling Package](http://github.com/aserifi/convolutional-downscaling)

<ins>Type (Based on GA, p.8)</ins>: Deep Learning-based spatio-temporal downscaling