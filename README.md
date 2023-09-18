To create book :

Create a conda/mamba environnment :

conda create -n map551
conda activate map551
conda install jupyter-book numpy scipy plotly jupyter jupyterlab -c conda-forge


Then, type in jupyterbook directory :

jupyter-book build .
