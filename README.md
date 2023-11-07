# Analysis of methylation data with minfi and conumee

[![Binder](http://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/chavez-lab/methylation-analysis-tutorial/HEAD?filepath=methylation.ipynb)

## Todo
- Import code for Exercises I, II and III
- Deploy code, data and environment somewhere to the cloud (binder? SDSC accounts? genepattern 
notebook?)

## Lab notebook

Things I have learned so far:
- To set up your virtual environment with jupyter lab, see 
https://www.zainrizvi.io/blog/jupyter-notebooks-best-practices-use-virtual-environments/
- Lots of bioconda packages will will only build on intel cpus. If you are using conda and 
apple silicon, see 
https://stackoverflow.com/questions/71515117/how-to-set-up-a-conda-osx-64-environment-on-arm-mac
- Using conda to install R packages (minfi and conumee + dependencies) seems to exceed the 
RAM limit for [mybinder.org](mybinder.org). See 
https://discourse.jupyter.org/t/how-can-i-prevent-an-out-of-memory-error-in-github-actions/17294

