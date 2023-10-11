
[![Reproducibility](https://github.com/espm-157/fish-fisheries-russelh-maeveg/actions/workflows/main.yml/badge.svg)](https://github.com/espm-157/fish-fisheries-russelh-maeveg/actions/workflows/main.yml)

## Team Members:

- Russell Huang, Huangary1126
- Maeve Gilbert, maevegi

## Assignment Description
This module examines global fish stock data based on the RAM Legacy Database. The work is an attempt to reproduce the data examined by Worm et al. (2006) which examined the collapse of Canadian Atlantic cod stocks. The second table in this module examines global fish stocks.
All work for this assignment should be in the `assignment` directory.  You will work in the `.Rmd` notebook, and commit your rendered output files (`.md` and associated files) in the `assignment` directory as well.

## Special files

All team repositories will also include most of the special files found here:

### Common files

- `README.md` this file, a general overview of the repository in markdown format.  
- `.gitignore` Optional file, ignore common file types we don't want to accidentally commit to GitHub. Most projects should use this. 
- `<REPO-NAME>.Rproj` Optional, an R-Project file created by RStudio for it's own configuration.  Some people prefer to `.gitignore` this file.


### Infrastructure for Testing

- `.travis.yml`: A configuration file for automatically running [continuous integration](https://travis-ci.com) checks to verify reproducibility of all `.Rmd` notebooks in the repo.  If all `.Rmd` notebooks can render successfully, the "Build Status" badge above will be green (`build success`), otherwise it will be red (`build failure`).  
- `DESCRIPTION` a metadata file for the repository, based on the R package standard. It's main purpose here is as a place to list any additional R packages/libraries needed for any of the `.Rmd` files to run.
- `tests/render_rmds.R` an R script that is run to execute the above described tests, rendering all `.Rmd` notebooks. 




