# Crime Data Analysis Project

## Overview

This project involves a comprehensive analysis of crime data from Los Angeles, aimed at uncovering trends, patterns, and insights to better understand crime dynamics. The dataset, sourced from the Crime Data Catalog, covers various crime incidents and has been rigorously cleaned, prepared, and analyzed.

## Project Components

### Data Cleaning and Preparation

To ensure the dataset's accuracy and usability, we performed the following tasks:

- **Removed Duplicates**: Eliminated duplicate entries to maintain data integrity.
- **Standardized Missing Values**: Addressed missing values by imputing with median or mode values based on crime type.
- **Converted Time and Date Formats**: Standardized time and date formats for consistency across the dataset.
- **Merged Columns**: Created meaningful addresses and collated crime codes for enhanced analysis.

### Exploratory Data Analysis (EDA)

Our exploratory analysis focused on uncovering key insights:

- **Overall Crime Trends**: Observed an 8.3% annual increase in crime rates, with a data skew for 2023 due to incomplete records for the last three months.
- **Seasonal Patterns**: Identified a general decline in crime rates post-summer and an increase around the New Year.
- **Most Common Crimes**: Determined that 'Stolen Vehicle' was the most frequent crime, followed by 'Battery Simple Assault' and 'Identity Theft'. Categorized 138 original crime types into 13 broad categories for simplicity.

## Tools and Technologies

- **Python**: For data cleaning and analysis.
- **Pandas**: For data manipulation and preparation.
- **Matplotlib/Seaborn**: For data visualization.

## Getting Started

To get started with this project:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/crime-data-analysis.git
