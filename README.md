# jamesriver-summarystatistics

A project to to combine 15 years of water quality monitoring data and generate daily mean summary statistics for select variab

* Temperature (`TempC`)
* pH (`pH`)
* Specific Conductance (`SpCond_uScm`)
* Turbidity (`turb_NTU`)
* Chlorophyll a (`Chla`)
* Oxygen Dissolved Saturation (`ODOsat`)
* Oxygen Dissolved (mg/L) (`ODOmgl`)

as well as produce an animated plot depicting seasonal patterns and inter-annual variation in water temperature at VCU's Rice River Center monitoring station, located in the upper estuarine portion of the James River. This work was completed in collaboration with [Dr. Paul Bukaveckas](https://blogs.vcu.edu/pabukaveckas/) of VCU's Center for Environmental Studies.

## Files

This repository contains the following components:

| File/Folder Name                 | Description                                                               |
|----------------------------------|---------------------------------------------------------------------------|
| `annual summaries/`              | Contains yearly summary reports as separate .xlsx files.                                          |
| `annual summaries folder/`       | Directory for storing annual summary reports.                             |
| `data/`                          | Folder with raw and processed data files.                                 |
| `what a commitment`              | Likely a note or comment about the dedication required for the project.   |
| `.gitignore`                     | Specifies intentionally untracked files to ignore.                        |
| `Initial commit`                 | The first commit to the repository, setting up the project structure.     |
| `README.md`                      | File containing the project overview and instructions.                    |
| `Update README.md`               | A commit message indicating an update to the README file.                 |
| `RicePier_dailymeans_2009to23.Rmd`| R Markdown document calculating daily mean values from 2009 to 2023.     |
| `animated_timeSeries.rmd`        | R Markdown document for creating animated time series visualizations.     |
| `jamesRiver-longterm-waterTemps.Rproj`| R Project file for long-term water temperature analysis in James River. |
| `waterTemps_benchmarkLines.gif`  | Animated GIF showing water temperature trends with benchmark lines.        |

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

