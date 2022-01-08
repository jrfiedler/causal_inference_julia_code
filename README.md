# Julia Code for _Causal Inference: What If_

This repo contains Julia code for Part II of the book _Causal Inference: What If_, by Miguel Hernán and James Robins ([book site](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/)):

> Hernán MA, Robins JM (2020). _Causal Inference: What If_. Boca Raton: Chapman & Hall/CRC.

These notebooks were translated from the Python version [here](http://www.github.com/jrfiedler/causal_inference_python_code), and the code also roughly corresponds to the Stata, R, or SAS programs found at the book site.

The code in this repo has been checked against the 30 March 2021 version of the book.


## Dependencies

Required Julia packages:

- IJulia.jl
- CSV.jl
- DataFrames.jl
- CategoricalArrays.jl
- CairoMakie.jl
- StatsBase.jl
- GLM.jl
- Distributions.jl
- Roots.jl
- Econometrics.jl
- PyCall.jl

PyCall.jl allows you to call Python code from within Julia. See [PyCall's GitHub page](https://github.com/JuliaPy/PyCall.jl) for more information, in particular about the Python installation used. Within that Python installation, you'll also need Statsmodels package. You might want to use the Conda.jl package to install Statsmodels. If you're familiar with Python and know which Python installation is being used, you can install Statsmodels in one of the usual ways.


## Data

The data can be obtained from the [book site](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/).

The notebooks all assume that the **CSV version** of the data has been saved in the same directory as the notebooks.


## Author

James Fiedler
