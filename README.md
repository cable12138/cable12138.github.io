# My Quarto weibite
This repository uses Github Pages and it contains my profile website background and blogs as a MDS student.
This repository's content contains the source code about the frequency of (non)official languages used in different situations in Canadam and the results of some mean value
in different given column's situations to explore the most-used languages of them.

# Page link
https://cable12138.github.io/

#Introductions to clone and run
## Installation

- R 4.6.1
- Git 2.50.1
- Quarto 1.10.18
- uv 0.12.7
- R packages: ('tidyverse', 'reticulate', 'gapminder', 'readxl')


The R package dependencies are managed using `renv`.

## Build the website steps/ # Built site's lands and opens
nagivate to the folder you need to clone: cd <folder path>
get the HTTPS URL from Github Repository > Code > Local > HTTPS > Copy the URL
git clone https://github.com/cable12138/cable12138.github.io.git
nagivate to the folder: cd ~/cable12138.github.io/

## Sync the UV environment to create the Virtual Environment, and R packages
uv sync
open RStudio > File > Open Project > Nagicate to corresponding folder > .Rproj file > Concole
renv::restore()
uv run quarto preview

## Render the site
uv run quarto render

## Note



# Data source
The data comes from the lab 1 work's data used to practice, section 001, of the course DSCI 511 of data science of UBC, processfor name: Elham E Khoda. 



