# Retail Data Mining & Analytics Dashboard

Interactive data mining and visualization dashboard built using R and Shiny for analyzing retail customer transactions, purchasing behavior, and spending patterns.

---

# Project Overview

This project combines data analysis, visualization, clustering, and association rule mining into a single interactive dashboard. The system processes retail transaction data and provides insights through multiple analytical techniques and graphical visualizations.

The application was developed using:
- R
- Shiny
- ggplot2
- dplyr
- arules

---

# Features

## 1. K-Means Customer Clustering

Groups customers based on:
- Age
- Total spending

The dashboard allows the user to dynamically adjust the number of clusters and visualize customer segmentation results.

### Pipeline
- Data grouping and summarization
- K-Means clustering
- Cluster labeling
- Interactive table rendering

---

## 2. Association Rule Mining (Apriori Algorithm)

Discovers relationships between purchased items using market basket analysis.

### User Controls
- Minimum Support
- Minimum Confidence
- Minimum Rule Length

### Pipeline
- Convert item lists into transactions
- Apply Apriori algorithm
- Generate association rules
- Display results interactively

---

## 3. Payment Method Analysis

Compares total spending between:
- Cash payments
- Credit payments

### Visualization
- Pie chart
- Percentage distribution labels

---

## 4. Age vs Spending Analysis

Analyzes the relationship between customer age and total spending.

### Visualization
- Scatter plot
- Spending distribution across age groups

---

## 5. City Spending Comparison

Compares total customer spending across multiple cities.

### Visualization
- Sorted bar graph
- City-wise spending analysis

Supported cities include:
- Cairo
- Alexandria
- Giza
- Aswan
- Hurghada
- Port Said
- Fayoum
- Sohag
- Gharbia
- Dakahlia

---

## 6. Spending Distribution Analysis

Displays the frequency distribution of total spending values.

### Visualization
- Histogram
- Spending frequency analysis

---

# Technologies Used

- R
- Shiny
- ggplot2
- dplyr
- arules
- data.table
- shinythemes
- readxl
- scales

---

# Project Structure

## Data Processing
- CSV data loading
- Data cleaning
- Numeric conversion
- Missing value handling

## Data Mining
- K-Means clustering
- Apriori association rules

## Data Visualization
- Pie charts
- Scatter plots
- Bar graphs
- Histograms

## GUI
Interactive dashboard built using Shiny with:
- Dynamic controls
- Reactive outputs
- Real-time updates

---

# Example Usage

```r
shinyApp(ui = ui, server = server)
