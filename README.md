# Name Generator
### A character-level recurrent neural network model that generates new names


## Data
---
The data comes from the Social Security Administration's [Popular Baby Names data](https://www.ssa.gov/oact/babynames/limits.html). I'm using the National data to ensure the largest coverage of all names given to babies born in the US. 


According to SSA: 
> To safeguard privacy, we exclude from these files certain names that would indicate, or would allow the ability to determine, names with fewer than 5 occurrences in any geographic area.

## Setup
### Setting up the environment
Create a conda environment by using the following command in an Anaconda Prompt:

`conda env create -f environment.yml`

*Note*: `environment.yml` was created using `conda env export -n <environment name> > environment.yml`
