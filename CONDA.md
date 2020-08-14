## Creating environment with Conda

**Create a conda environment with (pandas, numpy, matplotlib, scikit-learn) dependencies (from inside current project folder)**

```
$ conda create --prefix ./env pandas numpy matplotlib scikit-learn
```

**Activate the current environment (from inside current project folder)**

```
$ conda activate ./env
```

**Installing additional dependency (Jupyter Notebook)**

```
$ conda install jupyter
```

**Starting jupyter notebook server**

```
$ jupyter notebook
```

**Exit current environment**

```
$ conda deactivate
```

**Share your conda environment (from inside current environment)**

```
$ conda env export --prefix ./env > environment.yml
```

**Finally, to create an environment called env_from_file from a .yml file called environment.yml, you can run the command:**

```
$ conda env create --file environment.yml --name env_from_file
```
