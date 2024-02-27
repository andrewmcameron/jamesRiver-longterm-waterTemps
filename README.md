# jamesriver-summarystatistics

A project to to combine 15 years of water quality monitoring data and generate daily mean summary statistics for select variables,

* Temperature (`TempC`)
* pH (`pH`)
* Specific Conductance (`SpCond_uScm`)
* Turbidity (`turb_NTU`)
* Chlorophyll a (`Chla`)
* Oxygen Dissolved Saturation (`ODOsat`)
* Oxygen Dissolved (mg/L) (`ODOmgl`)

as well as produce an animated plot depicting seasonal patterns and inter-annual variation in water temperature at VCU's Rice River Center monitoring station, located in the upper estuarine portion of the James River. This work was completed in collaboration with [Dr. Paul Bukaveckas](https://blogs.vcu.edu/pabukaveckas/) of VCU's Center for Environmental Studies.

## Files

- `data_wrangling.Rmd`: This R Markdown file contains the code for combining 15 years of long-term water monitoring data.
- `ggplot_gif_generator.Rmd`: This R Markdown file includes the script to generate a complex ggplot object and export it as a GIF.

## Requirements

List of libraries and tools required to run the R Markdown files, including R version, ggplot2, dplyr, etc.

## Installation

Instructions on how to install and run the project. This could include steps to install R and RStudio, as well as any necessary libraries.

```r
# Example of library installation
install.packages("ggplot2")
install.packages("dplyr")
# Add other necessary libraries

Code written to combine 15 years of water quality monitoring data and generate daily mean summary statistics for select variables.

animatedPlot.rmd 

