
# Exploring Experimental Design in the Energy Field

## Project Overview
This project analyzes CO2 emissions across various geographical regions and fuel sources to understand the environmental impact in the energy sector. The analysis includes data visualization, statistical testing, and interpretation of significant patterns.

### Objectives:
- Determine which fuel sources contribute the most to CO2 emissions.
- Analyze variations in emissions based on geographical regions.
- Use experimental design techniques (factorial and randomized block designs) to gain insights.

## Datasets
The datasets used are:
- `energy_design_a.csv`: Contains energy usage data categorized by fuel source and building type.
- `energy_design_b.csv`: Contains CO2 emissions data for various regions and fuel sources.

## Analysis
The analysis is performed using Python (pandas, seaborn, matplotlib) with a focus on:
1. Data visualization (Boxplots of CO2 emissions).
2. Statistical tests (ANOVA and Tukey's HSD for post-hoc analysis).
3. Insights into significant differences in emissions.

## Instructions
To run the analysis:
1. Clone the repository.
2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
3. Open `main_analysis.ipynb` to view the analysis and visualizations.

## Results
The analysis revealed that:
- Coal consistently resulted in the highest CO2 emissions in most regions.
- Natural Gas was the cleanest fuel source, especially in the South and West regions.

## Visualization
Below is an example visualization from the project:
![CO2 Emissions by Region and Fuel Source](images/co2_emissions.png)

## Licenses
The dataset was provided by Datacamp
