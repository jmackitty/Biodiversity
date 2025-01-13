# Biodiversity
Biodiversity Project
# National Parks Species Analysis

This project analyzes biodiversity data from national parks, focusing on species conservation status and observation counts. It uses Python with the pandas library for data manipulation and matplotlib for visualization.

## Project Goal

The goal is to analyze and visualize biodiversity data to understand:

- The distribution of species categories across different national parks.
- The conservation status of observed species.
- The relationship between species categories and their protection status.

## Data

The project uses two CSV files:

- `observations.csv`: Contains observation data for different species in national parks.
- `species_info.csv`: Contains information about different species, including their category, common names, and conservation status.

## Code

The code performs the following steps:

1. **Data Loading and Cleaning:**
   - Loads the CSV files into pandas DataFrames.
   - Cleans the data by handling missing values and removing duplicates.

2. **Data Transformation:**
   - Merges the two DataFrames based on the `scientific_name` column.
   - Creates new columns for species protection status.
   - Aggregates the data to count observations and protected species by category and park.

3. **Data Visualization:**
   - Creates a stacked bar chart showing the number of observations and protected species for each category.
   - Creates a pie chart showing the distribution of observations across different parks.
   - Creates a horizontal bar chart showing the number of protected species in each category.

## Visualizations

The project generates three visualizations:

- **Stacked Bar Chart:** Shows the number of observations and protected species for each category.
- **Pie Chart:** Shows the distribution of observations across different parks.
- **Horizontal Bar Chart:** Shows the number of protected species in each category.

## Usage

1.  Ensure you have the necessary libraries installed (`pandas` and `matplotlib`).
2.  Place the CSV files (`observations.csv` and `species_info.csv`) in the same directory as the Python script.
3.  Run the Python script to generate the visualizations.

## Additional Notes

- The code includes comments explaining each step.
- The visualizations provide insights into the distribution and conservation status of species in national parks.
- Further analysis and visualizations can be added to explore the data in more detail.

This README provides a basic overview of the project. You can add more details or customize it as needed for your GitHub repository.
