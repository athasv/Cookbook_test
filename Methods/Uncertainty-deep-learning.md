<ins>Title</ins>: A review of uncertainty quantification in deep learning: Techniques, applications and challenges

<ins>Year</ins>: 2021

<ins>Keywords</ins>: Uncertainty quantification; Deep learning; Machine learning; Bayesian statistics; Ensemble learning

<ins>DOI</ins>: [LINK](https://doi.org/10.1016/j.inffus.2021.05.008)

<ins>Variables (Input/Output)</ins>: 

<ins>Method Details</ins>: 

Two main types of uncertainty:
* epistemic (model uncertainty) and 
* aleatoric (data uncertainty)

Quantification methods:
* Bayesian techniques
	* Monte Carlo (MC) dropout
	* Markov chain Monte Carlo (MCMC
	* Variational inference (VI)
	* Bayesian Active Learning (BAL)
	* Bayes By Backprop (BBB)
	* Variational autoencoders
	* Laplacian approximations
	* Uncertainty quantification in reinforcement learning
* Ensemble techniques
	- Deep NNs (DNNs)
	- Deep ensemble Bayesian/Bayesian deep ensemble
	- Uncertainty in Dirichlet deep networks

Others:
* Neural Architecture Distribution Search (NADs)
* Single-model estimates for DNNs of epistemic and aleatoric uncertainty
* Method to find and reject distribution data points for training a deterministic deep model with a single forward pass at test time
* MC-DropConnect
* Gradient-based optimization techniques
* Noise contrastive priors (NCPs) to estimate consistent uncertainty
* Uncertainty-based class imbalance learning
* Variational approximation, termed Bayes by hypernet (BbH), deducting hypernetworks as implicit distributions
* I Do not Know (IDK) prediction cascade approach
* models inspired by the nonlinear differential equations utilized by physics-informed neural networks
* ProbDepthNet
* DNNs trained with mixup
* Local interpretable model-agnostic explanations
(LIME)
* Randomized approach sampling from the hidden layers during the DNN interference period
* Certainty-driven consistency loss (CCL) method
* Modified knowledge distillation method
* Models based on kernel techniques
* Stochastic quantized activation distributions (SQUAD)
* Probabilistic DL method (approximate Bayesian inference + heteroscedastic noise technique)
* Gaussian Processes (GP)
* Stochastic, low-rank, approximate natural gradient (SLANG) technique
* Dubbed prior networks (PNs)
* DVERGE
* Direct epistemic uncertainty prediction (DEUP)
* Subjective Bayesian GNN (S-BGNN)
* Doubly stochastic variational neural process (DSVNP)
* non-Bayesian NN models
* Uncertainty-aware deep Dirichlet neural networks
* Deep Gaussian processes (DGPs):
	- in combination with stochastic weight averaging (SWA)
	- SWA-Gaussian
	- GPDNNs: a hybrid model of GP and DNNs
	- GPs + YOLOv3
	- A natural gradient-based algorithm for Gaussian mean-field
	- Matrix variate Gaussian (MVG)
	- Introduction of a variety of stochastic layers

A variety of other techniques uniquely specified and tailored for desired applications is listed within the last subsections of the paper.

<ins>Models</ins>:

Three (3) uncertainly models were considered:
* the MC dropout
* the Bootstrap model
* the GMM

<ins>General Comments</ins>: 

Gaps and methods to approach them:
* Fusion-based methods
* Ensemble methods
* Decision making
* Active learning
* Transfer learning
* Neural architecture search (NAS) methods
• Self supervised learning (SSL) methods
* Hypernetworks
* Continual learning
* GNNs: Graph Neural Networks
* BO: global optimization method for optimizing time-consuming black-box objective functions
* Uncertainty calibration

<ins>Tag</ins>: DL; ML; Uncertainty; Review;

<ins>Relevant Projects</ins>: 

<ins>Suggestions \& Relevant resources</ins>: 

<ins>Other relevant documents/sources</ins>: 

<ins>Type (Based on GA, p.8)</ins>: Deep learning methods; Machine learning methods; Uncertainty-related paper; Review article
