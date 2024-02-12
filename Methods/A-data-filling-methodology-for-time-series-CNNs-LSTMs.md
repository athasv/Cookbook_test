<ins>Title</ins>: A data filling methodology for time series based on CNN and (Bi)LSTM neural networks

<ins>Year</ins>: 2022

<ins>Keywords</ins>: Neural Networks; Data filling; Time series; Sensor data

<ins>DOI</ins>: [Link](https://doi.org/10.48550/arXiv.2204.09994)

<ins>Variables (Input/Output)</ins>: 

* Data from monitored apartments
* Data from sensors that could be of the following kinds:
	* stem moisture
	* air humidity
	* photo-synthetically active radiation
	* internal and external temperature
	* indoor relateive humidity 
	* CO<sub>2</sub> concentration
	* energy consumption for space heating
	* electricity
	* opening and closure of home windows

<ins>Method Details</ins>: 

* Data filling and time series forecasting
	- Combination of forward and backwards predictions in a single data filling model
* "The CNN-LSTM and the CNN-BiLSTM make use of external data in order to predict the target time series"
* "For the case of shorter time scales it would be worth comparing this kind of LSTM-based models with classical statistical methods"
* The model selection phase could be strengthened by following automated procedures(e.g. Grid-Search, Hyper-parameters Optimization Algorithms)

Results
* CNN-BiLSTM has the best performing approximation of the time series
* CNN-LSTM model performs better in generalizing its predictions
* "Both CNN-BiLSTM and CNN-LSTM models achieve good results, showing a promising ability of generalizing to unseen data"
* Both models outperform purely LSTM networks

<ins>Models</ins>:

* CNNs, LSTMs and BiLSTMs
	* CNN-LSTM (256, 128 and 64 neurons)
	* CNN-BiLSTM (32,and 16 neurons) | most promising model
* Use both in pre- and post-gap data

<ins>General Comments</ins>: 

* Reconstructing time-series

<ins>Tag</ins>: Deep learning; Time series; Data-filling

<ins>Relevant Projects</ins>: [SINFONIA project](http://www.sinfonia-smartcities.eu/)

<ins>Suggestions \& Relevant resources</ins>: 

* [Feedforward and LSTM Neural Networks, Gap filling](https://doi.org/10.3389/fmars.2021.637759)
* [Deep learning and time series forecasting, Review paper](https://doi.org/10.1142/S0129065721300011)

<ins>Other relevant documents/sources</ins>: 

<ins>Type (Based on GA, p.8)</ins>: Data-gap methods; Deep learning methods
