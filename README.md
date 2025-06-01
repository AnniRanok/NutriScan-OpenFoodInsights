# NutriScan: Open Food Facts App Feasibility Study

This repository presents a complete data analysis project conducted in response to the **Public Health France** call for innovation. Our goal is to explore the **Open Food Facts** dataset to assess the **feasibility of creating a public-facing nutrition application** using open data.


##  Project Objectives

- Propose and justify an innovative application idea related to nutrition
- Explore the Open Food Facts dataset for relevant variables
- Perform data cleaning, handling of missing/aberrant values
- Automate preprocessing for future updates to the dataset
- Provide insights through univariate and multivariate visualizations
- Validate hypotheses through statistical testing
- Deliver a structured feasibility analysis for the app idea


##  Data Source

- **Dataset**: [Open Food Facts](https://world.openfoodfacts.org/data)
- **Data Structure**:
  - Product metadata (name, brands, barcode, last modified)
  - Tag fields (categories, labels, origin, countries sold)
  - Ingredients & additives
  - Nutritional values (per 100g)



##  Application Idea

We propose an intuitive mobile/web app that allows users to:
- Scan or search food products
- Understand their nutritional profile visually
- Get simple suggestions for healthier alternatives
- Receive alerts on additives or allergens

This tool would be designed for **non-specialists**, focusing on **accessibility and impact** on public habits.



##  Methods

###  Data Preparation
- Handling missing values: median imputation, indicator variables, deletion
- Detecting outliers using IQR, Z-score, visual inspection
- Normalization for continuous variables

###  Analysis
- **Univariate analysis**: Histograms, box plots, pie charts
- **Multivariate analysis**: Correlation matrix, scatter plots, PCA
- **Statistical testing**: Chi² test, ANOVA, t-tests for feature selection



##  Repository Structure

```
NutriScan-OpenFoodInsights/
├── data/ # Raw and cleaned datasets
├── notebooks/ # EDA, modeling, report preparation
├── scripts/ # Preprocessing and cleaning automation
├── visualizations/ # Plots and graphs for the report
├── pitch/ # Slides, presentation notebook, summary
└── README.md # This file
```

##  Deliverables

- Exploratory data analysis notebook
- Visualization-rich report with narrative
- Hypothesis testing summary
- App feasibility summary
- Pitch presentation materials

##  Acknowledgments

This project was built as part of a public health innovation initiative by **Public Health France**. The data is freely available from [OpenFoodFacts](https://world.openfoodfacts.org).


