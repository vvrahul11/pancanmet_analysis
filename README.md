# Pan-Can Metabolism Code

Input data and informatic pipeline, analysis, visualization R code for the analysis of metabolomics data from over 900 tissue samples spanning 7 cancer types. 

# Code Structure
* analysis: R code for analyses performed in the project 
* data: Primary data that was processed as part of the project 
  * merged_metabolomics: Merged datasets after informatic standardization (e.g. name mapping across studies) pipeline, including metabolic profiling values, clinical features, and paired tumor-normal fold changes
  * studies: Primary data collected from studies (often supplementary tables) both metabolomic profiling and clinical variable data
  * pharmacology_drugbank: CHEBI IDs from Pathway Commons (pathwaycommons.org) dataset categorized using DrugBank drug categories
* import: Scripts for importing data (e.g. KEGG pathway data, metabolite ID mapping)
* results: Results from analysis 
* shinyapp: Data used for the R Shiny web application 
