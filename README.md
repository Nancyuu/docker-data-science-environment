# docker-minimal-notebook-environment
This forked repository offers a starting framework for a standardized and reproducible data minial notebook environment. This repository is built based on the [main repository](https://github.com/mtholyoke/docker-data-science-environment) which was developed by [Abby Drury](https://lits.mtholyoke.edu/about-lits/staff/abby-drury) in the [Academic Technologies department in LITS](https://lits.mtholyoke.edu/about-lits/departments/technology-infrastructure-systems-support/academic-technologies) in consultation with [Ben Gebre-Medhin](https://www.mtholyoke.edu/directory/faculty-staff/benjamin-gebre-medhin) from the Department of Sociology and Anthropology and [Sarah Oelker](https://lits.mtholyoke.edu/about-lits/staff/sarah-oelker) in the [Educational Technology department in LITS](https://lits.mtholyoke.edu/about-lits/departments/research-instructional-support/educational-technology). 

Additional information can be found in the [parent project wiki](https://github.com/mtholyoke/docker-data-science-environment/wiki). 

## Environment Customization and Statup
See [`environment/README.md`](environment/README.md)

## Project structure

### `analysis/`

Notebooks and analysis to be shared between docker container and local machine. 

### `data/`

Data to be shared between docker container and local machine. 

### `environment/`

Docker related files and package lists for Python only.
