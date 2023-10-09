# DMT

## Install this project on your machine

First, you need to install Anaconda (or Miniconda), git.

Next, clone this project by opening a terminal and typing the following commands (do not type the first $ signs on each line, they just indicate that these are terminal commands):

```
$ git clone https://github.com/Guo-Weiqiang/DMT.git
$ cd DMT
```
Next, run the following commands:
```
$ conda env create -f environment.yml
$ conda activate dmt
$ python -m ipykernel install --user --name=python3
```

Next, start Jupyter:
```
$ jupyter notebook
```

If you want to quit the conda environment, run:
```
conda deactivate
```