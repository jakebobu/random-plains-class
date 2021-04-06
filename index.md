# Random-plains-class: Introducing a repo used to analyze land change in northeastern Colorado from 1984 to 2019
<p align="center">
  <img src="https://github.com/jakebobu/random-plains-class/blob/16e50ddbabb6279f974414e882f0e87a5efcb8cc/data/face.png" width="50"><br>
  <b><sub>Jake Bobula</sub></b><br>
  <b><sub>April 5, 2021</sub></b><br>
  <img src="https://github.com/jakebobu/random-plains-class/blob/16e50ddbabb6279f974414e882f0e87a5efcb8cc/data/cultivated_transition_larimer.png"><br>
</p>


### Random-plains-class
Our random-plains-class repo found here contains the scripts to create a random forest land classification model. Our research team used the repo to analyze 36 years of satellite imagery to investigate land cover trends. This repo serves two purposes: 1) as the collection of scripts to reproduce the data found in our research article "A social-ecological land-use change model: a multi-method examination of change on working rangelands in northeastern Colorado from 1984 to 2019" and 2) as a contribution to and inspiration for connecting open source libraries in geospatial, satellite imagery, and machine learning, among others. I designed this repo to examine land cover change in northeastern Colorado within a more extensive research study that I discuss below. Thus, this is not a coherent library but one approach to building a land classification model that met our collaborative teams' needs. This is a work in progress of a collection of scripts (not a coherent library), and there are many better ways, better algorithms in this area of study. Lastly, this repo is a work in progress, so please follow and fork.


### A multi-method land change research study
Cattle ranchers identify rapid social and ecological change as a threat to rangeland ecosystems and their natural resource-dependent communities. Therefore, our research team applied a multi-method approach, integrating qualitative and quantitative data, to examine the causes and consequences of land-use change on land cover in two agricultural communities in Larimer and Weld Counties, northeastern (NE) Colorado.

<img src="https://github.com/jakebobu/random-plains-class/blob/16e50ddbabb6279f974414e882f0e87a5efcb8cc/data/methodology.png" width="400"/><br>
<sub>The multi-method research process used to examine social-ecological land change in northeastern Colorado.</sub>


I developed and applied the random-plains-class repo for the study's quantitative component to analyze land cover changes for the two study sites. _This repo is intended to help the qualitative methods by matching the spatial and temporal aspects.  This wasn't possible with just NLCD with its limited temporal set of 7 years none before 2001.  These days with more public satilite data its possible to create a psudo nlcd for every year and going further back in time._

<img src="https://github.com/jakebobu/random-plains-class/blob/16e50ddbabb6279f974414e882f0e87a5efcb8cc/data/study_sites.png" width="700"/><br>
<sub>The two adjacent study sites, one centered in northeastern (NE) Larimer County and the other in northcentral (NC) Weld County, Colorado (ESRI 2011).</sub>


One of our findings is that both study sites experienced a decline in cultivated cropland from 1984-2019, with 16.0% and 18.7% of total land areas transitioning out of cultivated cover in the Larimer and Weld sites, respectively. Most of the cultivated land transitioned to herbaceous/grassland cover, with 10.3% and 18.4% of total land area transitioning to herbaceous/grassland cover from 1984-2019 in Larimer and Weld, respectively.

<img src="https://github.com/jakebobu/random-plains-class/blob/16e50ddbabb6279f974414e882f0e87a5efcb8cc/data/54ip1y.gif" width="700"/><br>
<sub>Change over time: 2019 and 1984 model outputs show the decrease in cultivated crops (yellow).</sub>


I designed this repo to collaboratively address an applied research question in northeastern Colorado. Yet, others can use the repo to replicate this process with minor adaptions in locations with NLCD coverage, such as Arizona's Sonoran Desert or Tennessee's Great Smokey Mountains. Moreover, this repo provides an illustrative model of integrating diverse geospatial libraries in python/bash. I built this repo by drawing inspiration and elements from other public projects, so please adapt and share. Our research team is already starting to modify this repo to train against new classification systems in East Africa's rangelands. Thus, check back in for updates on our next adventure in East Africa!

<img src="https://github.com/jakebobu/random-plains-class/blob/16e50ddbabb6279f974414e882f0e87a5efcb8cc/data/bands.png" width="700"/><br>
<sub>Satellite imagery inputs</sub>


<img src="https://github.com/jakebobu/random-plains-class/blob/16e50ddbabb6279f974414e882f0e87a5efcb8cc/data/full_process.png" width="700"/><br>
<sub>Flow chart of repo</sub>


<img src="https://github.com/jakebobu/random-plains-class/blob/16e50ddbabb6279f974414e882f0e87a5efcb8cc/data/performance.png" width="700"/><br>
<sub>Model performance metrics</sub>
