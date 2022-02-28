# integration-mapping-output-file-validation
Script to automate the validations of files output from integration mapping project

#### Run command on command line to start Jupyter Notebook
`~ docker run --rm -p 8888:8888 -p 4040:4040 -e JUPYTER_ENABLE_LAB=yes -v $(pwd):/home/jovyan/work jupyter/datascience-notebook`

Follow instructions for accessing the notebook - Copy and paste url with token into the browser

Create "data" directory and place all data files inside this directory

Navigate to work/notebooks/validate_output_files.ipynb

Edit the path according to the naming convention you've used for your folder structure.

Run all code cells from top to bottom

## Current list of output files:

#### location.txt
#### orders.txt
#### relay_pars.json
#### static_driver.txt