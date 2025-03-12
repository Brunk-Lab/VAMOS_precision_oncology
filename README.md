# VAMOS_precision_oncology

Developed by Kriti Shukla, kritis@unc.edu

# What this does:
Using this workflow, you can obtain whole proteome structural information from Alphafold, create dense variant clusters, identify which clusters are associated with a given pathway, run statistical analysis on these clusters to identify likelihood of association, and find drugs differentially associated with those clusters in cell lines.

# Instructions to run:
Data : All input data is publicly available on DepMap, TCGA, CTRP, Alphafold, and MSigDB.
Environment: Set up conda environment using the provided YAML file

# Known issues:
This workflow uses the kneed package for automatic finding of the epsilon parameter during density based clustering. If your input data does not have a clear "elbow" or "knee," this automatic process will fail and a manual epsilon parameter will need to be assigned for that protein. 

#Citations:
Please cite the following paper: 
