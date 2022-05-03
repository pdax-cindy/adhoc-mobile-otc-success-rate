# adhoc-requests
Readme File

Installing Jupyter Notebook

Prerequisites

- Python
- Anaconda Distribution



The simplest way to install Jupyter notebooks is to download and install the Anaconda distribution of Python. The Anaconda distribution of Python comes with Jupyter notebook included and no further installation steps are necessary.


- Download and install Anaconda Distribution (a few 100MB), Python 3, 64 bits.

- Open Anaconda Navigator and window will open. In the middle of the page, in the Jupyter notebook tile, click Launch.

- A Jupyter file browser will open in a web browser tab. Navigate to the directory you put the notebook in. Open the file with .ipynb extension .





Running Jupyter Notebook

- You can run the notebook document step-by-step (one cell a time) by pressing shift + enter.

- You can run the whole notebook in a single step by clicking on the menu Cell -> Run All.

- To restart the kernel (i.e. the computational engine), click on the menu Kernel -> Restart. This can be useful to start over a computation from scratch (e.g. variables are deleted, open files are closed, etc…).



Upload source file:

- Download source file (e.g. OTC data from Admin Portal), rename and save it under {project_name}/data folder on your local.

- Set filename variable on your notebook. Indicate the source folder location and filename. (e.g. filename = 'data/OTC_Trade_Ledger_04132022.csv’) 


Generate output file:

- You can save the output file of the dataframe using this script: {df_name}.to_csv(r'filename.csv', index = False

- Output files will be saved under the {project_name} folder on your local.


