# CEAMEC beta

Demostration with distance sampling dataset of pigeons in Singapore

## Installation

```R
list.of.packages <- c("shiny","rgdal","leaflet","shinycssloaders","shinythemes","tibble","unmarked","DT","data.table","xlsx","rgenoud","htmltools","bsplus")
req.packages <- list.of.packages[!(list.of.packages %in% installed.packages()[,"Package"])]
if(length(req.packages)) install.packages(req.packages, dependencies = TRUE)
shiny::runGitHub('CEAMEC_beta', 'qt37t247')
```

## How to use

1. Download the repository, unzip to aquire example files.

2. Follow the user manual to complete the CEAMEC run (for the demo with distance sampling, you could use the default parameters that already at place in the text boxes). 

3. Acomplished the run and download the results. 

4. Raise issues and provide feedbacks.

## What have changed from main version

1. Added function "parboot" from R package "unmarked" to examine the adequacy of model fit.

2. Removed placeholder in the distance sampling input session for easier access to the default value of parameters in demo runs.

3. Allow spaces to be typed in the text boxes.

4. Tooltips are now available.   

## Contact author

tangqiannus@gmail.com
