# EWC Cleaning and Viz

**Project goal**:
- cleaning a messy text file containing data (codes and descriptions found in the EWC, European Waste Catalogue) of waste that is export-eligible in the EU,
- creating both json and other r-friendly hierarchical data structures with the previously cleaned data (both with codes and descriptions),
- visualizing the waste hierarchies.

**How this is achieved**:
- cleaning and wrangling in Python (see *Parser.ipynb* - libraries: re, itertools, pandas, json),
- tree visualization in R/HTML (see *Visualization.Rmd* - libraries: D3network and NetworkD3).
