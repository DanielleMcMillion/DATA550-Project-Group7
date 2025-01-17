# Code Description for The Project

`code/01_data_processing.R`

- read raw data from `data/` folder
- save clean data as `.rds` in `data/` folder

`code/02_make_table1.R`

- read clean data from `data/` folder
- save table 1 in `table/` folder

`code/03_make_heatmap.R`

- read clean data from `data/` folder
- save heatmap picture in `figure/` folder

`code/04_make_figures.R`

- read clean data from `data/` folder
- save figures in `figure/` folder

`code/05_survival_analysis.R`

- read clean data from `data/` folder
- save survival analysis results in `output/` folder

`code/06_render_report.R`

- render `report_group7.Rmd` 
- save compiled report

`report_group7.Rmd`

- this is the code file of final report for this project
- read data, table, figures, and analysis results from respective locations
- display results for production report

`Makefile`

- contains rules for building the final report
- `make covid_data_cleaned.rds` will save the cleaned data in `data/` folder
- `make table1.rds` will generate a descriptive summary table needed to compile the report
- `make .png` will generate figures needed to compile the report
- `make *****` will generate survival analysis results needed to compile the report in `output/`folder
- `make clean` will remove all generated files

------------------------------------------------------------------------

# Coders's work Description

### Coder 1
- modify `01_data_processing.R` in `code/` folder:
    - clean the data and save cleaned data as `covid_data_cleaned.rds` in `data/` folder.

- modify `02_make_table1.R` in `code/` folder:
    - make table 1 and save it as `table1.rds` in `table/` folder

- update and add all related content into `report_group7.Rmd`.

### Coder 2
- modify `03_make_heatmap.R` in `code/` folder:
    - plot the heatmap and save the figure in `.png` format in `figure/` folder

- update and add all related content into `report_group7.Rmd`.

### Coder 3
- modify `04_make_figures.R` in `code/` folder:
    - plot figures of interest and save them in `.png` format in `figure/` folder

- update and add all related content into `report_group7.Rmd`.

### Coder 4
- modify `05_survival_analysis.R` in `code/` folder:
    - do the survival analysis and save all results in `output/` folder
    
- update and add all related content into `report_group7.Rmd`.




