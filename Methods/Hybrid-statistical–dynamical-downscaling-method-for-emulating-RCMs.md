<ins>Title</ins>: A simple hybrid statistical–dynamical downscaling method for emulating regional climate models over Western Europe. Evaluation, application, and role of added value?

<ins>Year</ins>: 2022

<ins>Keywords</ins>: RCMs; Hybrid statistical dynamical downscaling; Climate change; Emulation; RCms

<ins>DOI</ins>: [Link](https://doi.org/10.1007/s00382-022-06552-2)

<ins>Variables (Input/Output)</ins>: 

Variables
* Temperature
* Precipitation
Data
* RCMs from Euro-CORDEX at 12km resolution
* Scenario: RCP8.5
* Regional simulations:
	- CNRM-CM5 GCM from CMIP5 downscaled using three regional simulations with the GCM/RCM mode and the RCM/RCM mode 
	- RCM/RCM mode to downscale from CMIP6 
	- Historical and ssp5-8.5 simulations from the thirteen CMIP6 models


<ins>Method Details</ins>: 

* A hybrid statistical–dynamical downscaling method
	- Statistical model based on the results of RCMs
	- Applied to downscale GCMs
	- Aims to emulate regional climate models
	- It does not require the stationarity assumption of statistical downscaling
	- 
* Emulate RCM results, based on the constructed analogues approach
* Estimation method based on constructed analogues
	- Analogues of large-scale predictors from a low-resolution climate projection are considered
		- For high-resolution precipitation (temperature), the chosen predictor is low-resolution precipitation (temperature)

<ins>Models</ins>:

* Emulation models:
	- the GCM/RCM mode: "Fine-Scale Ref is a high-resolution regional climate simulation and Coarse-scale Ref its driving GCM"
	- the RCM/RCM mode: "Coarse-Scale Ref is simply the Fine-Scale Ref simulation aggregated on the low-resolution grid of the model to be downscaled (Mod)"
	
"In the RCM/RCM mode, the climate change signal at large scale of the original GCM is very well captured by the hybrid statistical downscaling method, independently of its magnitude"

<ins>General Comments</ins>: 

* Novelty: the analogues are searched within an RCM and therefore both in the past and the future climate
* The hybrid method is shown to reproduce climate change signals very well and to outperform a conventional statistical downscaling method
* "Emulation methods make it possible to downscale very large ensembles of global climate projections and therefore to fully explore the uncertainties involved in regional climate changes"

<ins>Tag</ins>: Downscaling;

<ins>Relevant Projects</ins>: 

<ins>Suggestions \& Relevant resources</ins>: 
* Euro-CORDEX regional climate projections: [Earth System Grid Federation](https://esgf.llnl.gov/)
* Constructed analogues method links:
	- [Searching for analogues, how long must we wait?
](https://doi.org/10.3402/tellusa.v46i3.15481)
	- [Utility of daily vs. monthly large-scale climate data: an intercomparison of two statistical downscaling methods
](https://doi.org/10.5194/hess-12-551-2008
)
	- [The utility of daily large-scale climate data in the assessment of climate change impacts on daily streamflow in California
](https://doi.org/10.5194/hess-14-1125-2010
)
	- [Hydrologic extremes – an intercomparison of multiple gridded statistical downscaling methods
](https://doi.org/10.5194/hess-20-1483-2016
)

<ins>Other relevant documents/sources</ins>: 

<ins>Type (Based on GA, p.8)</ins>: Statistical downscaling methods; Dynamical downscaling methods; Hybrid methods
