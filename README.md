# FSCI_2024Interactions_Replication
Replication files for the 2024 publication of the Food Systems Countdown Initiative
Last modified: 11 September 2024

LICENCE: This work is licensed under CC BY-NC-SA 4.0: Attribution-NonCommercial-ShareAlike 4.0 International
See LICENSE.txt for further details.

SOFTWARE:
Software required: R and R studio
R version used to create the code: R version 4.4.0
Dependencies: packages required are listed at the top of each script. If not installed, these must first be installed to your R instance's library and then loaded.

LOADING INSTRUCTIONS:
The files should be opened through the R project file so that all file paths work correctly.

SCRIPTS:
There are two scripts in the scripts subfolder. The first is data management, which creates the FSCI monitoring dataset, processes the raw dataset collected through the global expert elicitation exercise, and executes the automated literature search. Most input data loads directly through APIs or an R package, any datasets that were manually downloaded first are in the "Input Datasets" subfolder. Additionally, the raw dataset from the global expert elicitation exercise is also contained in the "Input datasets" subfolder.  All figures in the manuscript (including extended data and supplementary materials) can be replicated with the "FSCI_2024_Analysis" script and using the output datasets listed below.

EXPECTED PROCESSING TIME: Several steps in the data management script require several minutes to run. When processing the spatial data for the Milan Urban Food Policy Pact indicator, working memory may also be a constraint on certain systems. 

OUTPUT DATASETS:
Six datasets are created using the Data management script, listed below (supplementary data files 2-7). Intermediate datasets created for each indicator or data source and final datasets for subsequent analysis are saved in the "Output Data" folder. 

SUPPLEMENTARY FILES:
# Supplementary data file 1: "Supplementary Data 1 - Metadata and Codebook.xlsx" - Provided for context, not necessary for replication

# Supplementary data file 2: Full FSCI dataset, "FSCI_2024.rds"

# Supplementary data file 3: Global expert elicitation results, lowest connection between each pair of indicators, "Interactions_ExpertElicit_LowestConnect.rds"

# Supplementary data file 4: Global expert elicitation results, all direct connections, "Interactions_ExpertElicit_Direct.rds" (dataset in long form)

# Supplementary data file 5: Global expert elicitation results, all direct connections, "Interactions_ExpertElicit_DirectMatrix.rds" (dataset in matrix)

# Supplementary data file 6: Global expert elicitation results, all direct connections including bidirectional connections, "Interactions_ExpertElicit_Bidirect.rds"

# Supplementary data file 7: Literature search results, after manual screening, "Search results_screened.xlsx"

CONTACT: 
Kate Schneider, kschne29@jhu.edu or kateschneider.phd@gmail.com