## LC6_code_R

This contains R scripts and data used for the anatomical analysis of LC6 and downstream neurons. Most EM figures (except connectivity matrices) were generated using this code.  First run "startup.R" and follow the instructions therein.

However, if you only want to generate a particular figure, you can load the workspace file (you need to unzip them first)

full workspace_20201105.7z

LC6_proc_data.7z

After this, look for the figure of interest by searching, eg.  "Figure 6C". Then you need to run the whole blocks.

# startup.R
load libraries and some data

# LC6_proc.R
mostly codes to make figures only pertaining LC6 cells

# target_proc.R
make figures pertaining downstream target cells

# RI.R
generate examples for retinotopy index calculation

# LC6_Analysis_connMatrix.R  
contains R code to generate the connectivity matrices.

