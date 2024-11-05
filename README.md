# README

This README file describes the visualizations created in Tableau Desktop Public Edition based on Titanic dataset attributes. These visualizations include a bar chart and a histogram, illustrating survival rates by gender and age distribution, respectively.

## Files
1. **bar_chart.png** - A bar chart showing the count of passengers who survived and did not survive, categorized by gender.
2. **histogram.png** - A histogram showing the distribution of passenger ages, using binned age groups.

## Visualizations

### 1. Bar Chart: Survival Count by Gender (bar_chart.png)
- **Data Source**: Titanic dataset
- **Purpose**: To visualize survival rates by gender, displaying how many males and females survived or did not survive.
- **Columns**: `Sex`
- **Rows**: Two measures:
  - `SUM(survived_count)`: Represents the count of passengers who survived.
  - `SUM(not_survived_count)`: Represents the count of passengers who did not survive.
- **Visualization Type**: Stacked bar chart, split by gender and survival status.
- **Marks**:
  - The darker blue indicates the count of survivors.
  - The lighter blue represents the count of non-survivors.
- **Key Insight**: This visualization makes it easy to compare survival rates between males and females.

### 2. Histogram: Age Distribution (histogram.png)
- **Data Source**: Titanic dataset
- **Purpose**: To analyze the age distribution of passengers.
- **Columns**: `Age (bin)` - Age grouped into bins.
- **Rows**: `CNT(Age)` - Count of passengers within each age bin.
- **Visualization Type**: Histogram.
- **Marks**: Standard color for bars.
- **Key Insight**: Shows the concentration of passengers in various age groups, revealing the age demographics of Titanic passengers. The highest count is for passengers in their 20s.

## Software Requirements
- **Tool Used**: Tableau Desktop Public Edition
- **Dataset Requirements**: The Titanic dataset, which includes fields such as Age, Sex, and Survived.

## Usage
These visualizations are intended for analysis of demographic patterns related to survival on the Titanic. They can be used for educational purposes or for understanding how gender and age influenced survival rates.
