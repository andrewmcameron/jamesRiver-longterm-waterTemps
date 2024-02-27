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

This repository contains the following files and folders:

| File/Folder Name                 | Description                                                               |
|----------------------------------|---------------------------------------------------------------------------|
| `annual summaries/`              | folder with yearly summary reports as separate .xlsx files                                       |
| `data/`                          | folder with raw and processed data files                                 |
| `.gitignore`                     | specifies intentionally untracked files to ignore                        |
| `RicePier_dailymeans_2009to23.Rmd`| R Markdown document calculating daily mean values from 2009 to 2023     |
| `animated_timeSeries.rmd`        | R Markdown document for creating animated time series visualization    |
| `jamesRiver-longterm-waterTemps.Rproj`| R Project file |
| `waterTemps_benchmarkLines.gif`  | final animation file |

## Requirements

The following libraries are required:

* `tidyverse`
* `openxlsx`
* `gganimate`
* `gifski`
* `showtext`

