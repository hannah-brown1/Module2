# Module 2 – R for Marine Science

## Overview

This repository contains work completed for Module 2 of MB5370 Techniques in Marine Science. The module focused on applying R to marine science datasets, including data cleaning, wrangling, visualisation and analysis.

The module built on the programming skills developed in Module 1 and focused more strongly on preparing real ecological datasets for analysis and interpreting patterns in a marine science context.

## Repository contents

- `code/` – workshop exercises and R analysis scripts
- `data/` – datasets used throughout the module
- `docs/` – rendered documents and supporting material

## Key skills

- Data wrangling with the `tidyverse`
- Joining and organising datasets
- Managing missing and inconsistent data
- Data visualisation with `ggplot2`
- Interpreting ecological patterns

## Data

Earlier activities in this module used datasets available within R to develop skills in data wrangling, visualisation and analysis.

The keystone exercise used four datasets provided through the [MB5370 R for Marine Science class repository](https://github.com/MB-5370/R4MarineScience). These represented a study of water quality and predatory fish assemblages along the Ross River Estuary gradient:

- `estuary_catch_log.xlsx` – fish catch records collected across multiple spreadsheet tabs
- `estuary_metadata.csv` – site coordinates and estuary zones
- `estuary_sonde_data.csv` – water quality sensor measurements
- `species_dictionary.csv` – taxonomic information linking common and scientific names

The datasets were cleaned, standardised and joined in R to create a single master dataset that could be used to explore ecological patterns across the estuary.
