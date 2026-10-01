# balochi-aspiration-transposition

R Markdown scripts and analysis for Documentation of Transposition of Aspiration in Dialectal Balochi. Linked to OSF project: https://osf.io/28ax7.

---

# Acoustic Phonetic Analysis: Transposition of Aspiration in Dialectal Balochi

This repository hosts the **R Markdown (`.Rmd`) data wrangling pipelines** and **acoustic and analytic visualizations** generated for the acoustic phonetic analysis of production and perception data on transposition of aspiration. The project is integrated with the permanent data archive on OSF.

---

### Repository Structure
* **`README.md`**: Documentation guide.
* **`.gitignore`**: Configured for R workspace variables (ignores local temporary cache and system metadata).
* **Scripts/**: Contains R Markdown files for data processing, visualizations, and perception category analytics, etc.

---

### Linked Open Science Resources
* **Permanent Data & Metadata:** The **acoustic measurement spreadsheets**, **R Scripts**, and the **"Key to terms in the analysis"** metadata sheet are archived at the **[OSF Project Repository](https://osf.io/28ax7/overview)** (Project ID: `28ax7`).
* **Associated Monograph:** The doctoral dissertation can be accessed via the [University of Oslo Library Repository](https://bibsys-k.primo.exlibrisgroup.com) or via [External Link](https://www.researchgate.net/publication/405390552).

---

### Computational Requirements
To run the analysis script (`Scripts_final.Rmd`), you must have **R** installed alongside the following libraries:

```r
# Core Data Wrangling & Manipulation
library(readr)
library(dplyr)
library(tidyverse)
library(tidyr)
library(data.table)

# Visualizations & Acoustic Plotting
library(ggplot2)
library(ggdist)
library(ggrepel)
library(plotly)
```
