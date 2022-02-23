# Data Clustering in Julia

Lecture notebooks on data clustering.

Notebooks are written in [Julia](https://julialang.org) using [Pluto.jl](https://github.com/fonsp/Pluto.jl).

Notebooks have been used in:
* Tutorial given at SoftCOM, September 2021.
* SEA-EU Virtual Course at University of Malta, September 2021.



## Viewing the notebooks

You can view the notebooks at [https://ivanslapnicar.github.io/Data-Clustering-in-Julia.jl](https://ivanslapnicar.github.io/Data-Clustering-in-Julia.jl)

## Running the notebooks

You can run the notebooks in two ways:

### Running on `binder`

1. Go to [https://ivanslapnicar.github.io/Data-Clustering-in-Julia.jl](https://ivanslapnicar.github.io/Data-Clustering-in-Julia.jl) and choose the desired notebook.
2. Press `Edit or run this notebook` button and choose `binder`. This will read all the necessary packages and start the notebook (within several minutes).

### Running on your computer

1. Clone the entire repository using `git` command:
```
git clone https://github.com/ivanslapnicar/Data-Clustering-in-Julia.jl
```
If you are unfamiliar with the `git` tool, check GitHub [help pages](https://help.github.com/articles/set-up-git/). You can also download the repository as a zip file.

2. Install [Julia](https://julialang.org/downloads/). In Julia terminal run the commands
```
> using Pkg
> Pkg.add("Pluto")
> using Pluto
> Pluto.run()
```
This opens local Pluto server in your browser. Now you can choose the notebook and run it
(the notebboks are located in the directory `Data-Clustering-in-Julia.jl/Lectures/`).
