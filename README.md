# c14AAR_pres

Title:

c14bazAAR & oxcAAR -- two R packages for the collection, calibration and modelling of C14 dates

Abstract:

In this paper we will present our two new packages c14bazAAR and oxcAAR that were created to simplify working with radiocarbon dates in R. Radiocarbon dates are extremely relevant for archaeological research on an intra site level, for regional comparison and to trace spatio-temporally large processes of exchange and transformation. Most comparative work relies on openly available collections of published dates -- radiocarbon date archives with a long history of data import and maintenance. Many of the latter with different regional and temporal emphasis were created in a rampant growth over the last two decades. They are highly decentralised and lack basic standardization internally as well as in between each other. c14bazAAR provides tools to query, merge and clean a growing selection of radiocarbon date archives automatically and systematically. oxcAAR now serves as an R API to the widely popular software package Oxcal for calibration and modelling of C14 data. Thereby it allows not only to streamline a reproducible and coherent workflow of import, calibration and visualization, it also provides an interface for Bayesian simulation and further statistical analysis where R finally excels. Both packages are well interlinked and support tidy datastructures that fit into modern and powerful tools like dplyr, sf or ggplot2.                   

The packages are developed by the ISAAKiel group (Initiative for Statistical Analysis in Archaeology Kiel) https://isaakiel.github.io