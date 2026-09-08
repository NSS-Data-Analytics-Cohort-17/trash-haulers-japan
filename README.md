## Project Overview

This project analyzes an Excel dataset containing service requests from hubNashville, Metro Nashville’s customer service platform. The source data was imported into Python for cleaning, classification, financial analysis, and visualization.

The analysis distinguishes missed pickups from other complaints, standardizes inconsistent address and hauler data, and identifies recurring failures at the same premises. Under the existing contract methodology, the first missed pickup does not result in a penalty, while each subsequent occurrence generates a $200 fine.

## Project Objective

Transform raw Excel service-request data into an analysis of financial liability and operational performance by determining:

- Which service requests represent legitimate missed pickups
- Which addresses experienced repeated collection failures
- How much each trash hauler owes under the current fine policy
- How contractor and Metro collection performance compare
- Which routes generated the most missed-pickup complaints
- Whether complaint patterns change by year, month, or season
- How damages would change under proposed 180-day fine policies
- How preventing dates from being reused would affect total fines

## Technologies Used

- Microsoft Excel
- Python
- Jupyter Notebook

## Techniques and Methodology Used

- Excel data ingestion and validation with pandas
- Regex-based classification of complaint descriptions
- Address normalization and composite location-key construction
- Rule-based identification of recurring service failures
- Contract-based damage and penalty calculations
- Performance segmentation by trash hauler and collection route
- Temporal segmentation by year, month, and season
- Year-over-year and seasonal complaint analysis
- Time-series visualization with Seaborn and Matplotlib
- Scenario-based comparison of current and proposed fine policies