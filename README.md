# San Diego & San Francisco Housing Affordability Gap

## Project Overview

**Problem Statement:**
Housing affordability is a critical economic and social challenge in San Diego and San Francisco, where median home prices significantly outpace median household incomes. This project aims to **quantify this disparity** by creating a **Housing Affordability Gap** metric at the ZIP code level.

**Goal:**
The main objective is to analyze the relationship between property characteristics (size, beds/baths), listing price, and local income to determine where housing is most and least accessible in San Diego and San Francisco. The findings are intended to provide data-driven insights for prospective buyers and policymakers.

## Executive Summary

This project addresses the pressing challenge of housing affordability for young adults in San Diego and San Francisco. We determine a Housing Affordability Gap by comparing household incomes to average home prices and price-per-square-foot. The analysis uses real estate listings and income statistics to examine how property size and features affect affordability. Our findings identify which regions are most and least affordable, offering insights for potential homeowners and community stakeholders.

## Analysis Highlights (Key Findings)

Initial analysis focused on the San Diego housing market, with a subsequent expansion to include San Francisco for comparison.

* **Property Size and Price:** There is a clear positive relationship between house size (square footage) and price, confirming that larger homes tend to carry a premium cost.
* **Affordability Gaps:** Significant affordability gaps remain in the San Diego housing market. Certain ZIP codes, including **91905**, **92119**, and **92024**, showed the most significant gaps, exceeding the defined affordability threshold.
* **Price per Square Foot:** A large number of homes in San Diego are available in the **\$500/sqft to \$750/sqft** range, which home buyers should generally expect to pay.
* **Bedrooms and Price per Square Foot:** The median price per square foot remains relatively stable until the number of bedrooms approaches eight. Starting at eight bedrooms, the median price per square foot decreases with every subsequent increase in bedroom number.

## Data Sources

The project utilizes data from two primary sources:

1.  **Real Estate Listing Data:**
    * **Source:** Reality.com
    * **Kaggle Dataset:** [USA Real Estate Dataset](https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset)
2.  **Income Statistics:**
    * **Source:** United States Census Bureau
    * **Data Link:** [California Income Data](https://data.census.gov/table?q=california+income)

## Limitations and Future Work

### Limitations
The current analysis has several limitations that could affect the interpretation of the affordability gap:

* **Income Simplification:** Median household income does not fully account for income distribution or purchasing power at an individual ZIP code level.
* **Market Dynamics:** The affordability gap calculation may not fully capture fast-changing market dynamics or unique neighborhood conditions.
* **Property Features:** The analysis does not explicitly consider property features such as amenities or quality of construction.

### Next Steps
Future work could expand the analysis in the following areas:

* **Expanded Data:** Include rental market data, historical housing price trends, and other cost-of-living factors, such as transportation costs.
* **Predictive Modeling:** Develop predictive models to forecast affordability based on proposed zoning laws or other policy changes.
* **Comparative Analysis:** Explore other cities in California or other states to compare their metrics against San Diego and San Francisco.
* **Historical Trends:** Compare the current data to historical data to analyze how the Californian housing market has progressed.

## Team Information

* **Team Number:** 5
* **Project Manager:** Yashaswini Reddy
* **Team Members:** Yashaswini Reddy, Gurveen Rekhi, Aryan Jain, Tae Yoon Kim, Xiaoxuan Zhu
* **File Name:** `A05-Housing-Affordability.ipynb`
