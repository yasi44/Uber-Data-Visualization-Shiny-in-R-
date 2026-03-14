# Uber Data Visualization(Shiny in R)


# DSCI-532_2026_32: Uber Dashboard Project Individual Assignment

This project develops an interactive dashboard analyzing Uber’s 2024 ride data to evaluate operational performance, and revenue trends. The dashboard provides key business insights through visual analytics, helping stakeholders understand ride volume patterns, vehicle type performance, and customer ratings.

Using **R, Shiny, and interactive visualizations**, the project transforms raw ride-level data into meaningful KPIs and decision-support tools. The dashboard enables users to explore trends over time, compare service categories, and identify areas for operational improvement and revenue optimization.

This project demonstrates the full data workflow: data cleaning, exploratory data analysis (EDA), KPI development, and interactive dashboard deployment. It emphasizes business storytelling, data-driven decision-making, and clear visual communication.

---
## Prerequisites
1. Install [R](https://cran.r-project.org/) (version >= 4.2 recommended)
2. Install [RStudio](https://www.rstudio.com/) (optional, but recommended)
3. Make sure you have Git installed if you want to clone the repository.

## Setup Instructions
### 1. Clone the repository
```bash
git clone https://github.com/yasi44/DSCI-532_2026_32_Uber_dashboard.git
cd DSCI-532_2026_32_Uber_dashboard
```
### 2. **Install required R packages**
Open R or RStudio and run:
```R
install.packages(c(
  "shiny",
  "rsconnect",
  "plotly",
  "dplyr",
  "lubridate",
  "readr"
))
```
If you want, you can also create a renv environment to track dependencies:
```R
install.packages("renv")
renv::init()
renv::restore()
```
### 3. Run the Shiny app locally:
```R
library(shiny)
runApp("app.R", launch.browser = TRUE)
```

#### To run the shiny app from your terminal (here we explained windows): 
Navigate to the project folder:
```bash
Rscript -e "shiny::runApp('app.R', launch.browser=TRUE)"
```
If the Rscript command is not recognized on your system, make sure the R is installed on your system and it's path is added to the path:
##### Add R to your system PATH
1. Press Win + S, type Environment Variables, click Edit the system environment variables.
2. Click Environment Variables… at the bottom.
3. Under System variables, find Path, then click Edit.
4. Click New, and paste your R bin folder path, e.g.:   C:\Program Files\R\R-4.3.1\bin
5. Click OK all the way out.
6. Close and reopen Command Prompt — new PATH is only applied in new sessions.
7. Test if Rscript works: Open a new Command Prompt and type --> Rscript --version

This will start the Shiny app, and you can access it in your web browser. 
The dashboard allows you to explore Uber's 2024 ride data through interactive visualizations and KPIs.

### 4.Demo
The dashboard is deployed on Posit Cloud, and users can interact with it without needing to run it locally.
[Click here to see the demo](https://019cee63-04f2-45c1-efa3-88a007e5dca0.share.connect.posit.cloud/)
