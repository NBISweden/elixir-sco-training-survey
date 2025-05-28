# ELIXIR SCO Training Survey Analysis

This repository contains the analysis and visualization of the ELIXIR SCO Training Survey responses.

## Project Structure

- `survey_overview_report.qmd`: Main Quarto document containing the analysis and visualizations
- `figure/`: Directory containing generated figures
- `styles.css`: Custom styling for the HTML report

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

## Output

The analysis generates:
- HTML report with interactive visualizations
- PDF and PNG figures in the `figure/` directory 