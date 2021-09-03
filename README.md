# covid_models
Behavioral data and analysis script for "Psychological determinants of emotional distress during the COVID-19 pandemic"

The manuscript has a preprint on [PsyArXiv](10.31234/osf.io/ah7jq).

# Setup
Clone repository or simply download in a zip file. 

The R Markdown file in the Analysis folder contains all the analysis code for the paper as well as a html version. In order to run the code you'll need the following packages up-to-date: 

```
library(here)         # relative path
library(conflicted)   # resolve conflicts
library(tidyverse)    # tidy functions
library(knitr)        # knit functions
library(broom.mixed)  # tidy()
library(kableExtra)   # extra markdown functions
library(ggrepel)      # geom_text_repel
library(psych)        # alpha(), omega()
library(caret)        # train-test functions
```

# Folders
This repo contains the following folders: analysis, data, and graphs. 

1. **analysis**

   Main analysis script can be found here alongside an html Markdown file showing all results and code. 

2. **data**

   Cleaned data can be found here. See analysis script for a description of all variables. 

3. **graphs**

   Graphs produced for the preprint manuscript from R. Note that some style changes have been added to the final graphs in the manuscript using Illustrator, but in general I try to keep the graph output from R as close as possible to the final graph. 

# Contact
If you have any questions or suggestions please feel free to open an issue on this repo or email me directly at joseph_heffner@brown.edu. 

