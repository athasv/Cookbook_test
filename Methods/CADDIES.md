<ins>Title</ins>: CADDIES Framework, a two-dimensional cellular automata based model, called Weighted Cellular Automata 2D (WCA2D)

<ins>Year</ins>: 2016

<ins>Keywords</ins>: Shallow water equations; Overland flow; Flood modelling; Cellular automata; Weight-based model; GPU computing


<ins>DOI</ins>: [Link](https://engineering.exeter.ac.uk/research/cws/resources/caddies/)

<ins>Variables (Input/Output)</ins>: Raster data

<ins>Method Details</ins>: 

The WCA2D model adopts simple transition rules rather than the complex Shallow Water Equations to simulate overland flow. Furthermore, the complexity of these transition rules are further streamlined by a weight-based system that reduces the computating cost of using physically based equations and complex mathematical operations. The WCA2D is a diffusive-like model that ignores the inertia terms and conservation of momentum and it improves the methodology used in the previous CADDIES CA2D model.

<ins>Models</ins>: "The WCA2D model has been designed to work with various general grids, (e.g., rectangular, hexagonal or triangular grid) with different neighbourhood types (e.g., the five cells of the von-Neumann (VN) neighbourhood or the nine cells of the Moore neighbourhood). The major features of this new model are:
- The ratios of water transferred from the central cell to the downstream neighbour cells (intercellular-volume) are calculated using a minimalistic and quick weight-based system.
- The volume of water transferred between the central cell and the neighbour cells is limited by a single equation, which comprises a simplified Manning’s formula and the critical flow condition.
- The model can be implemented easily in parallel computing environments due to features of the cellular automata technique."

<ins>General Comments</ins>: 

<ins>Tag</ins>: Floods

<ins>Relevant Projects</ins>: 

<ins>Suggestions \& Relevant resources</ins>: [A weighted cellular automata 2D inundation model for rapid flood analysis](https://www.sciencedirect.com/science/article/pii/S1364815216303243?via%3Dihub), [Formulation of a fast 2D urban pluvial flood model using a cellular automata approach ](https://iwaponline.com/jh/article/15/3/676/3279/Formulation-of-a-fast-2D-urban-pluvial-flood-model), [Mapping urban infrastructure interdependencies and fuzzy risks](https://www.sciencedirect.com/science/article/pii/S1877705818301280?via%3Dihub), [CADDIES: A New Framework for Rapid Development of Parallel Cellular Automata ALgorithms for Flood Simulations](https://core.ac.uk/download/pdf/12825248.pdf)

<ins>Other relevant documents/sources</ins>: 

<ins>Type (Based on GA, p.8)</ins>: Tool/Model
