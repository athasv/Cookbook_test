<ins>Title</ins>: Regional climate model emulator based on deep learning: concept and first evaluation of a novel hybrid downscaling approach

<ins>Year</ins>: 2023

<ins>Keywords</ins>: Emulator; Hybrid downscaling; RCMs; Statistical downscaling; Deep neural network; Machine Learning; EURO-CORDEX

<ins>DOI</ins>: [Link](https://doi.org/10.1007/s00382-022-06343-9)

<ins>Variables (Input/Output)</ins>: 

* Daily near-surface temperature from EUR11-CORDEX simulations based on the CNRM-ALADIN63 regional climate model driven by the CNRM-CM5 global climate model used in CMIP5
* Historical period runs from 1951-2005
* Scenarios (2006-2100) are based on RCP4.5 and RCP8.5

<ins>Method Details</ins>: 

* The RCM-emulator is based on a fully convolutional neural network algorithm, called UNet 
	* Evaluation both on perfect model and GCM worlds
	* Reproduces the high resolution spatial structure and daily variability of the RCM
	* Issues reproducing accurate simulations of extreme events
	* Issues reproducing the complete climate change magnitude
* "The general functioning of a RCM can be broken down into a large scale transformation and a downscaling function"
* A novel hybrid downscaling approach that emulates the downscaling function of a RCM

<ins>Models</ins>:

<ins>General Comments</ins>: 

* Transformation from low resolution information to the high resolution near surface temperature
* Aiming at the feasibility to emulate the RCM complexity at high-frequency and high-resolution
* RCM-GCM inconsistencies at large scales
* "The emulator provides a high-resolution simulation that is corrected from the GCM-RCM large-scale inconsistencies"

<ins>Tag</ins>: Downscaling; Deep Learning

<ins>Relevant Projects</ins>: [EUCP European Climate Prediction System](https://www.eucp-project.eu/)

<ins>Suggestions \& Relevant resources</ins>: [RCM-Emulator](https://github.com/antoinedoury/RCM-Emulator): Code and data to build and train the emulator

<ins>Other relevant documents/sources</ins>: Supplementary information: summary tables of the different tests performed with the UNet-based emulators 

<ins>Type (Based on GA, p.8)</ins>: Statistical downscaling method; Data-driven methods
