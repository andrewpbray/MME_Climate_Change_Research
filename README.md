# MME_Climate_Change_Research

This project contains the code for a publication in XXXXXXX 

# Publication Title: 'Thermal Extremes Drive Die-offs in North Temperate Lakes'

  Authors: Aaron Till, Andrew L. Rypel, Andrew Bray, Samuel B. Fey
  
  Code: Aaron Till with assistance from Andrew Bray and Kristen Bot
  
This project aims to 
  
  a) explore the relationship between temperature and fish die-off events 
  
  b) model how die-offs will change in the future

Files:

# Importing and Tidying 
(package loading:rgdal, readr, dplyr, tidyr, stringer, lubridate)

  The steps for importing and tidying various datasets
    
    1) Wisconsin MME Dataset (available in data folder)
    
    2) US census data for wisconsin census blocks (https://www.census.gov/geo/maps-data/data/tiger-data.html)
    
    3) Coordinate data for Wisconsin and Wisconsin lakes (Winslow et al., 2017)
    
    4) Data on modeled thermal temperatues (Winslow et al., 2017 - Concurrent = NLDAS and Future = ASC)
    
# Modeling 
(package loading: caret, glmnet)

  The creation and testing of the Lasso, Ridge, basic Logistic models for Summerkill and all MMEs
  
# Visualizations 
(package loading: ggplot2, ggthemes, ggmap, gridExtra, spdep)

  Code for all visualizations in the paper including:
    
    The visualizations and statistics for relating temperature to die-offs
    
    The visualizations of the primary model X taken from modeling
    
# SI Visualizations
  All visualizations included in papers supplementary information section
  
# Sandbox 
  Unorganized scratchwork repository
  
 
    
