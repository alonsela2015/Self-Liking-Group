# 🌍 Collaboration and Academic Excellence – SLG Code and Data

This repository contains the data and R code used in support of our study:  
**"Collaboration Between Countries is Associated with Academic Excellence and Funding"**

---
The repository include: 
🔹 **`.csv` files**  
  1. A sample dataset for one year’s country-level co-authorship network. Nodes represent countries, and edges indicate co-authorship links within that year.
File name = "CountryHomophily_year1980_Gap3_r=1.0_LA50_p0.csv"
     
  2. An additional metadata file provides country-level attributes, such as:
    - Region classification  
File name = "AuthorNode_CountryHomophily_Cluster_k=4new.csv"
  3. Continent
File name = "Country_Continent.csv"

---
Compiled standalone software and/or source code - AuthorNode_CountryHomophily_year1980_Gap3_r=1.0_LA50_p0.csv
## 📁 Structure

- 🔹 **`Country_SLG.R`**  
  Core script implementing the SLG (Self-Liking Group) computation for country-level scientific collaboration networks.

- 🔹 **`FUN_*.R`**  
  A set of custom functions required by the main script. These include routines for network preprocessing, SLG matrix generation, and temporal aggregation.



## ⚙️ Installation & Requirements

- **Operating System**  
  Tested on MacOS (≥ 12.0), Windows 10/11

- **R Version**  
  Requires **R ≥ 4.5.0**

- **R Packages**  
  The following R packages are required:
  ```r
  install.packages(c("igraph", "tidyverse", "data.table", "ggplot2"))

