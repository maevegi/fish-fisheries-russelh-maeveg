
[![Reproducibility](https://github.com/espm-157/fish-fisheries-russelh-maeveg/actions/workflows/main.yml/badge.svg)](https://github.com/espm-157/fish-fisheries-russelh-maeveg/actions/workflows/main.yml)

## Team Members:

- Russell Huang, Huangary1126
- Maeve Gilbert, maevegi

## Assignment Description
This module examines global fish stock data based on the RAM Legacy Database. The work is an attempt to reproduce the data examined the Millennium Ecosystem Assessment, which examined the collpase of Atlantic cod stocks in Canada, and the paper by Worm et al. (2006) which examined the collapse of global fish stocks. The relevant papers can be found here:
https://doi.org/10.1126/science.1132294
https://doi.org/10.1111/j.1467-2979.2011.00435.x
https://doi.org/10.1073/pnas.1604008113
All work for this assignment is in the `assignment` directory.  


### Common files

- `README.md` this file, a general overview of the repository in markdown format.  
- `.gitignore` Optional file, ignore common file types we don't want to accidentally commit to GitHub. Most projects should use this. 


### Infrastructure for Testing

- `.travis.yml`: A configuration file for automatically running [continuous integration](https://travis-ci.com) checks to verify reproducibility of all `.Rmd` notebooks in the repo.  If all `.Rmd` notebooks can render successfully, the "Build Status" badge above will be green (`build success`), otherwise it will be red (`build failure`).  
- `DESCRIPTION` a metadata file for the repository, based on the R package standard. It's main purpose here is as a place to list any additional R packages/libraries needed for any of the `.Rmd` files to run.
- `tests/render_rmds.R` an R script that is run to execute the above described tests, rendering all `.Rmd` notebooks. 




