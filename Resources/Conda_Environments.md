# Generate a conda environment on your local machine

To generate the `conda` environment on your local machine, load the following packages:

```
conda create --name sjsu_demo
conda activate sjsu_demo
conda install -c anaconda pandas
conda install -c conda-forge matplotlib
conda install -c anaconda jupyter
```
To make your environment accessible in a Jupyter notebook, use the following command
```
python -m ipykernel install --user --name=sjsu_demo
```
