# Fitness-Based Growth of Directed Networks with Hierarchy

[![DOI](https://zenodo.org/badge/775540456.svg)](https://zenodo.org/doi/10.5281/zenodo.13378865)

This code was used to generate the results of the paper "Fitness-Based Growth of Directed Networks with Hierarchy" by Niall Rodgers, Peter Tino and Samuel Johnson. Accepted by the Jounral of Physics: Complexity, an initial verison is also avaliable on arXiv https://arxiv.org/abs/2405.06395


This code based on work during my PhD can be used to generate directed networks using combinations of preferential attachment based on degree and node fitness interactions. 

The code is divided into many variants of the model using different fitness functions, to analyse the structure of a single network or many. In a way that was convenient to generate the figures for research work. Most of the jupyter notebooks contain repeated base code with some feature changed to the one which they intended to analyse. Example figures are also left in the jupyter notebook but not necessarily the ones used in the submitted work as these can be reproduced by changing the parameters in the code to match the ones listed in the paper. There also may be some superfluous variables and plots that arise from moving between functions and refer to other variables but the relevant variables should all be contained in each notebook. 


Any code for any fitness function can be easily modified to fit the required function just by changing it and any code labelled for a specific function will contain commented expressions of other possible functions.


Some modifications were made to the historical network data in order to get it converted into the appropriate format. Some letters had to be removed from the names of the individuals in the networks manually as the accent characters were not compatible and conversion errors, affecting one individual, were manually corrected to make sure the number of edges matched the value listed in the data-set description. The modification of the names did not alter the network structure and the results hold identically minus the correction of the unconverted edge. 

Files are compressed due to the large nature of some of the Jupyter Notebook files.

I can be contacted on nxr081@student.bham.ac.uk until the end of my PhD in September 2024. If you have questions about the work after that date contact my co-author Samuel Johnson at s.johnson.4@bham.ac.uk 

