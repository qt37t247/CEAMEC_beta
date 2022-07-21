# CEAMEC beta

Demostration with distance sampling dataset of pigeons in Singapore

In the beta, we removed some placeholder in the input textboxes for easier access to the default values of parameters in demo runs.

Changes during peer-review process will reflect in the beta repository before we permanently apply the changes to the CEAMEC master repository and Shiny Cloud.  

## Installation

```R
list.of.packages <- c("shiny","rgdal","leaflet","shinycssloaders","shinythemes","tibble","unmarked","DT","data.table","xlsx","rgenoud","htmltools","bsplus","dplyr","shinycssloaders","rgeos","plyr")
req.packages <- list.of.packages[!(list.of.packages %in% installed.packages()[,"Package"])]
if(length(req.packages)) install.packages(req.packages, dependencies = TRUE)
shiny::runGitHub('CEAMEC_beta', 'qt37t247')
```

## How to run the demo

1. Download the repository, unzip to aquire example files.

2. Follow the user manual (section 5.	Example data demostration) to complete the CEAMEC run. 

3. Acomplished the run and download the results. 

4. Raise issues and provide feedbacks.

## What have changed from main version

1. Added function "parboot" from R package "unmarked" to examine the adequacy of model fit.

2. Replaced majority of the textInput with selectInput/checkboxes to minimize human error.

3. Allow spaces to be typed in the text boxes.

4. Tooltips are now available at every input.

5. Background density of selected cells is available.  

## Contact author

tangqiannus@gmail.com
