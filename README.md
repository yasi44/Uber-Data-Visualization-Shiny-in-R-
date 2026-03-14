# Uber Data Visualization(Shiny in R)


# DSCI-532_2026_32: Uber Dashboard Project Individual Assignment

This project develops an interactive dashboard analyzing Uber’s 2024 ride data to evaluate operational performance, and revenue trends. The dashboard provides key business insights through visual analytics, helping stakeholders understand ride volume patterns, vehicle type performance, and customer ratings.

Using **R, Shiny, and interactive visualizations**, the project transforms raw ride-level data into meaningful KPIs and decision-support tools. The dashboard enables users to explore trends over time, compare service categories, and identify areas for operational improvement and revenue optimization.

This project demonstrates the full data workflow: data cleaning, exploratory data analysis (EDA), KPI development, and interactive dashboard deployment. It emphasizes business storytelling, data-driven decision-making, and clear visual communication.

---

## Installations

1. **Fork the repository**: [https://github.com/UBC-MDS/DSCI-532_2026_32_Uber_dashboard.git](https://github.com/UBC-MDS/DSCI-532_2026_32_Uber_dashboard.git)

2. **Clone the fork locally**:
```bash
git clone https://github.com/yasi44/DSCI-532_2026_32_Uber_dashboard.git
cd DSCI-532_2026_32_Uber_dashboard
```

3. **Install required R packages**

Open R or RStudio and run:
```bash
install.packages(c(
  "shiny",
  "plotly",
  "dplyr",
  "lubridate",
  "readr"
))
```

(If you are using renv for project-specific package management, you can run renv::restore() instead.)

4. Run the Shiny app locally:
```bash
shiny::runApp("src/app.R")
```

This will start the Shiny app, and you can access it in your web browser. The dashboard allows you to explore Uber's 2024 ride data through interactive visualizations and KPIs.

Deployment

The dashboard is deployed on Posit Cloud, and users can interact with it without needing to run it locally.

[Click here to see the demo](https://019cee63-04f2-45c1-efa3-88a007e5dca0.share.connect.posit.cloud/)
