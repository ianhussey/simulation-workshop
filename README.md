# Simulated data & Monte-Carlo simulation studies

## Overview

This repo contains materials for the 2-day workshop "Simulated data & Monte-Carlo simulation studies" first taught at the Unviersity of Bern in Fall 2024.

The course assumes users are familar with R, R Markdown, dplyr, and tidyr, as well as graduate level statistical methods. It was designed for a PhD students and postdocs.

It teaches a tidyverse approach to Monte-Carlo simulation studies using {purrr}.

All simulations are implemented in R using a specific workflow written in [{tidyverse}](https://www.tidyverse.org/) and [{purrr}](https://purrr.tidyverse.org/) that is designed to maximise ease of writing, interpreting, and reusing code - sometimes at the expense of the speed at which the code runs at. 
Researchers who are already familiar with writing simulations whose simulations may be more computationally intensive should consider implementing them in other dedicated packages such as [{SimDesign}](https://cran.r-project.org/web/packages/SimDesign/vignettes/SimDesign-intro.html) or [{simhelpers}](https://meghapsimatrix.github.io/simhelpers/).

## Author

Ian Hussey 

## Licence

All materials are public domain under a CC-0 1.0 licence. You may therefore use or modify these materials however you like.

# TODO

week 1

- create copy without answers
- make 4 - simulating the impact of the violation of assumptions of a students t test, using code from general structure lesson. what property is distorted? p values. when? only when heterogeneous variances and also different sample sizes.
- add old lesson 4 on skew normal distributions if needed - distorted p values only when different distributions between conditoins, not when normality is violated generally. however, distorted effect sizes.

Week 2

- mvnorm()
- lavaan::simulate_data()

NB files higlighted in red (on my local machine only) either have small corrections to be made to them or include partial answers that need to be removed for future courses or have notes for content to be added for future courses.
