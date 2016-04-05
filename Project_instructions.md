## Introduction

In this assignment you will create a reproducible report 
making use of the quarterly UK gas consumption data for the period
1960-Q1 to 1986-Q4. Data are in millions of therms.

## Data
The data for this assignment can be downloaded from:

[UK Quarterly Gas Consumption](https://vincentarelbundock.github.io/Rdatasets/csv/datasets/UKgas.csv)

The variables included in this dataset are:

  - *X*: An index variable of time
  - *time*: Time in quarters of a year
  - *UKgas*: Gas consumption (in millions of therms)

The dataset is stored in a comma-separated-value (CSV) file and there are a total of 108 observations in this dataset.

## Assignment

This assignment will be described in multiple parts. You will need
to write a report that answers the questions detailed below. Ultimately, 
you will need to complete the entire assignment in a single **_R markdown_**
document that can be processed by knitr and be transformed into an 
**_HTML file_**.

Throughout your report make sure you always include the code that you used 
to generate the output you present. When writing code chunks in the R markdown 
document, always use echo = TRUE so that someone else will be able to read 
the code. It is essential that your peers are able to review the code used for 
your analysis.

For the plotting aspects of this assignment, feel free to use any plotting 
system in R (i.e., `base`, `lattice`, `ggplot2`)

Fork/clone the GitHub repository created for this assignment. Push your 
completed files into your forked repository on GitHub. The assignment 
submission will consist of the URL to your GitHub repository to the
following email (f.colon@uea.ac.uk).

## Loading and preprocessing the data
Show any code that is needed to

  - Load the data
  - Process/transform the data (if necessary) into a format suitable for your analysis

## Questions

- What is mean annual UK gas consumption? which year had the greatest gas consumption?
- Make a histogram of the total UK gas consumption
- Calculate and report the mean and median UK gas consumption for the whole period
- Make a time series plot (i.e. type = "l") of time (x-axis) vs. annual gas consumption (y-axis)
- Create a factor variable for each year and create a box and whisker plot of gas consumption
  as a function of year

## Submitting the Assignment

To submit the assignment:

- Fork this [repo](https://github.com/FelipeJColon/Reproducible_Research/)
- Update the `README.md` file with an executive summary of your analysis as well as 
  any information relevant for its reproducibility (e.g. packages required, 
  software versions, etc - see [slide 66](http://rpubs.com/FelipeJColon) for more details)
- Commit the your completed `template.Rmd` file to the master branch of your GitHub 
  repository (you should already be on the master branch unless you created new ones)
- Commit also the template.md and template.html files produced by processing your 
  R markdown file
- If your document has figures included (it should) then they should have been 
  placed in the figures/ directory by default (unless you overrided the default). 
  Add and commit the figures/ directory to yoru git repository (If the figures/ folder
  does not appear, type `knit2html("myfile.Rmd")` on your R console).
- Push your master branch to GitHub
- Submit the URL to your GitHub repository for this assignment to f.colon@uea.ac.uk
      - A valid submission would look something like:

        `https://github.com/FelipeJColon/Reproducible_Research/`

- Upload your submission file to RPubs too and submit the URL to your file
  to the same account (f.colon@uea.ac.uk)
      - Your submission would be something like:

        `http://rpubs.com/FelipeJColon/149097`

