# GCxGC Decomposition Study in Canada
PhD research project_UQTR
The files in this repository are the work done to take initial outputs from a set of GCxGC scans of headspaces from decomposition targets, looking for relevant VOCs in the scans. This is an edited version of the the original respository, which can be found using the link: https://github.com/wesleyburr/GCxGC_Amputated_Limbs. 
There are four main files, which:
* 1: load and process the Excel sheets into .rda objects
* 2: load the .rda objects, and normalize with respect to Bromobenze, the reference standard
* 5: select, filter, clean and merge compounds to export to files which are suitable for PCA using the original software of the GCxGC system
* 9: Merge normalised areas of VOCs detected across all samples into one file and fill in 0 for VOCs that were not detected in specific samples
Downloading this repository and starting from the file 1_Load_Review.Rmd, if each Rmd is run in turn, they should run correctly. Do note that there is a dependency on each subsequent number on some of the previous numbers.
