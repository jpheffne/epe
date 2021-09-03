# epe
Behavioral data and analysis script for "Emotion Prediction Errors Guide Socially Adaptive Behavior"

The manuscript is published in Nature Human Behavior at the following doi: [to add]

# Setup
Clone repository or simply download in a zip file. 

The R Markdown file in the Analysis folder contains all the analysis code for the paper, as well as a html version, and the supplement. In order to run the code you'll need the following packages up-to-date: 

```
library(here)         # relative paths
library(tidyverse)    # tidy functions
library(knitr)        # knit functions
library(kableExtra)   # extra markdown functions
library(lsr)          # cohenD()
library(lme4)         # mixed-effects regressions
library(lmerTest)     # mixed-effects regressions
library(broom.mixed)  # tidy()
library(AICcmodavg)   # predictSE()
library(cowplot)      # plot_grid()
library(ggrepel)      # geom_text_repel
library(gridExtra)    # aesthetics 
library(permutes)     # permutation testing
library(doParallel)   # parallel computing 
library(purrr)        # map functions
library(sjPlot)       # clean tables
library(ggstance)     # vertical position dodge
library(mousetrap)    # mouse tracking analysis
library(clusterperm)  # cluster-based permutation
library(exchangr)     # shuffle function
```

# Folders
This repo contains the following folders: analysis, data, and graphs. 

1. **analysis**

   Main analysis script can be found here alongside an html Markdown file showing all results and code. Supplementary analysis script can be found here as well. 

2. **data**

   Cleaned data can be found here for all experiments separately. **Note** Data files for Experiment 3, involving mouse tracking, are too large to host in Github but can be found in an OSF repository [here](https://osf.io/puwt8/). You'll want to place these in the `data/study3_jg/` folder or change the path locations in the analysis script. 

3. **graphs**

   Graphs produced for manuscript from R. Note that some style changes have been added to the final graphs in the manuscript using Illustrator, but in general I try to keep the graph output from R as close as possible to the final graph.

# Contact
If you have any questions or suggestions please feel free to open an issue on this repo or email me directly at joseph_heffner@brown.edu. 

