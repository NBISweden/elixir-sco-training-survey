# ELIXIR Single-Cell Omics Training Survey Analysis

This repository contains the analysis and visualization of the training survey conducted by the ELIXIR Single-Cell Omics Community. The survey aims to understand the current state of training in single-cell and spatial omics data analysis across different countries and institutions.

## Project Overview

The ELIXIR Single-Cell Omics Community focuses on building capacity in Single-Cell and Spatial Omics through various activities:
- Organizing workshops for single-cell and spatial omics data analysis trainers
- Conducting training gap surveys to understand current training offerings and needs
- Providing collections of training materials
- Organizing recorded courses

## Data Structure

The repository contains:
- `data/Training_survey_parsed_courses.xlsx`: The main dataset containing parsed information about training courses
- `results_section.Rmd`: R Markdown file containing the analysis and visualizations
- `survey_overview_report.qmd`: Quarto document for generating the HTML report
- `figure/`: Directory containing generated figures

## Key Findings

Based on the survey analysis:
- Most courses are given once a year, for 1 week with 20-40 students
- Main challenges include non-uniform audiences and different operating systems
- Most courses are R-based
- Limited coverage of single-cell omics beyond RNA-seq (e.g., ATAC, CITE, VDJ)
- For spatial data, mainly Visium is covered in courses

## Training Materials

The survey has collected information about various course instances that have materials available online, including:
- Course slides
- Practical exercises
- Some recorded lectures

## Contributing

This project is part of the ELIXIR Single-Cell Omics Community's efforts to make training scalable and FAIR, in coordination with the ELIXIR Training platform. The community ensures that training materials and expertise are shared efficiently following FAIR and open research principles.

## License

This project is part of the ELIXIR infrastructure and follows ELIXIR's open science principles.

## Project Structure

- `survey_overview_report.qmd`: Main Quarto document containing the analysis and visualizations
- `figure/`: Directory containing generated figures
- `styles.css`: Custom styling for the HTML report
- `data/`: Directory containing the survey data

## Setup

1. Clone this repository
2. Install required R packages:
   ```R
   install.packages(c("ggplot2", "xlsx", "dplyr", "gridExtra", "stringr", "pheatmap", "reactable", "htmltools"))
   ```
3. Run the Quarto document to generate the report:
   ```bash
   quarto render survey_overview_report.qmd
   ```

## Data

The survey data is stored in an Excel file (not included in the repository due to privacy concerns).

