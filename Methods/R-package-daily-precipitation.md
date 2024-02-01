<ins>Title</ins>: An R package for daily precipitation climate series reconstruction

<ins>Year</ins>: 2017

<ins>Keywords</ins>: reddPrec; Daily precipitation; Quality control; Missing values; Grid

<ins>DOI</ins>: [Link](https://doi.org/10.1016/j.envsoft.2016.11.005)

<ins>Variables (Input/Output)</ins>: Weather data with presence of data gaps

<ins>Method Details</ins>: 

* "For each observatory, the observatories located at a distance of less than 20 km and with a correlation of more than 0.7 are selected. In case there are less than 6 observatories that meet these requirements, the radius of proximity will be recursively extended by 5km until there are 6 nearby observatories". 

* "A multiple linear regression is performed with the data that the observatory to be filled and the 3 observatories selected above have in common. With the parameters of the linear regression, the gaps of the standard observatory that are empty and whose data from the 3 selected observatories are complete are filled in. No gaps are filled for a given day if any of the 3 observatories with which the linear regression has been performed have no data for that day".

<ins>Models</ins>:

<ins>General Comments</ins>: 

* "Closest-correlated neighbor" weather data gap-filling methodology"
* Data gap-filling for weather observations used by FIC in ICARIA

<ins>Tag</ins>: 

<ins>Relevant Projects</ins>: Junta de Andalucía SICMA Climate Change local scenarios 

<ins>Suggestions \& Relevant resources</ins>: 

<ins>Other relevant documents/sources</ins>: 

<ins>Type (Based on GA, p.8)</ins>: Gap-filling method