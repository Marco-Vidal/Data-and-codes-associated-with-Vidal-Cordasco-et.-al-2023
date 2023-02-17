# Data-and-codes-associated-with-Vidal-Cordasco-et.-al-2023
Here data and codes are available to reproduce the models and figure rendering of the paper: “Carrying capacity affected Neanderthal coexistence with modern humans”.  This research is based on two set of data: 1) herbivore species recovered from archaeo-palontological sites, and 2) chronometric determinations obtained from archaeological units with techno-complexes attributed to Neanderthals or modern humans. All this information is available in the Data.xlsx file. The file 1_MainScript.R includes the functions to estimate the biomass of each herbivore species according to the Net Primary Productivity (NPP), the allometric relationships between body mass and population density, and the specific herbivore guild composition in each region. This script was used to analyse and compare the NPP and the herbivore guild composition in each biogeographic region of Europe during the Marine Isotope Stage (MIS) 3.The file 2_HB.R reproduces the validation process of the macroecological model to estimate herbivore abundances (used in the 1_Main_Script.R) against empirical present-day herbivore densities from a broad range of terrestrial ecosystems. The file 3_PollenScript.R was used to perform pollen-based paleoclimate reconstructions with weighted averaging (WA) regressions. These predictive functions are used to estimate temperature and precipitation from the palynological fossil record in Europe. The file 4_OLE.R was used to perform optimal linear estimation models and to compare the obtained chronologies with the outcomes obtained from Bayesian age models.  The file 5_Correlations_ESF.R performs Eigenvector Spatial Filtering analyses to assess the correlation between the end of the techno-complexes associated with Neanderthals, those associated with AMH, and the productivity of the ecosystems in each European region. As the data and codes in this repository are complete, it can be reproduced with only an R environment (tested for R v4.2.0) in RStudio. The necessary package dependencies are documented in each .R file. 
The content of this repository was made possible thanks to funding from the European Research Council (ERC) under the European Union's Horizon 2020 research and innovation programme (grant agreement No. 818299) for the SUBSILIENCE project