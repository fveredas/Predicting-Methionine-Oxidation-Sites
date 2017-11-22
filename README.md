# Prediction of Methionine Oxidation Sites
A Machine Learning Approach

The file "MetOData" is a RData containing all the data used in the paper entitled “Feature Engineering to Improve the Prediction of Methionine Oxidation Sites in Proteins”.

Once the file has been loaded into R, we will be able to access to a data frame formed by 975 observations (rows), one for each methionine analyzed, and 80 variables (columns). The first column provides the accession number (ACC) for the UniProtKB entry corresponding to the relevant protein. The second column gives the Protein Data Bank identifier (PDB) of the structure used for the computations. The third variable collects the methionine position within the primary structure of the protein. The fourth variable informs about whether the analyzed methionine has been detected in vivo as MetO. The remaining 76 variables are described in detail in the aforementioned paper, as well as the way they have been computed.
