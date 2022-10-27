# HYSPLIT_tutorial
 A small tutorial to help you get started on reading and processing output from HYSPLIT.
 
 You cna find an environment with all necessary packages to start reading in HYSPLIT output
 and plot a trajectory frequency plot on a hexbin map, as well as how to transform your data to
 cluster depending on latitude, longitude and height on a x,y,z,-plane.




Conda Environment
This file may be used to create an environment using: hysplit.yml
To install the environment go to the terminal and type:
$ conda env create -f hysplit.yml
To activate this environment, use:
$ conda activate hysplit
now you are in the activated environment and have all packages installed
to read HYSPLIT output files and plot them.
starting working on the script type:
$ jupyter notebook hysplit_tutorial.ipynb

To deactivate an active environment, use:
$ conda deactivate

