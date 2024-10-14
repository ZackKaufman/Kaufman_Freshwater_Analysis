# Code and data for 'The Impact of Underestimated Southern Ocean Freshening on Simulated Historical Sea Surface Temperature Trends’

Authors: Zachary Kaufman, Earle Wilson, Rebecca Beadling, Ariaan Purich, Yuchen Li
 
Submitted to Geophysical Research Letters (September 2024), [Preprint Link](https://essopenarchive.org/users/836836/articles/1228563-the-impact-of-underestimated-southern-ocean-freshening-on-simulated-historical-sea-surface-temperature-trends)

Code by Zachary Kaufman

This is a preliminary release (manuscript in review) 

The repository contains Python notebooks to re-produce manuscript figures. Historical and SSP5-8.5 output is accessed in the notebooks directly from the intake.open_esm_datastore. The remaining model and reanalysis output has been pre-processed on Sherlock, Stanford’s high-performance computing cluster, and provided here as smaller .nc files requiring minimal compute resources. 

## Installation 
Before using the notebooks, run the following commands: 
`conda env create -f environment.yml -n your_env_name`

`conda activate your_env_name`

Analysis notebooks are configured  to be run out of the box. Note for Fig2.ipynb, Fig3.ipynb, that it can sometimes take several minutes to successfully connect to intake_esm datastore.
