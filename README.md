# Karnataka Rice Production Analysis

This Jupyter Notebook provides an in-depth analysis of rice production in Karnataka for the year 2021-22. The dataset includes information on area, production, and yield for different seasons (Kharif, Rabi, and Summer) across various districts in Karnataka.

## Dataset Overview

The dataset contains the following columns:
- **District Name**: Name of the district.
- **Kharif_AreaBefore bund correction factor**: Area under Kharif season before bund correction (in hectares).
- **Kharif_AreaAfter bund correction factor**: Area under Kharif season after bund correction (in hectares).
- **Kharif_Yield**: Yield during Kharif season (in kg/hectare).
- **Kharif_Production**: Production during Kharif season (in tonnes).
- **Rabi_AreaBefore bund correction factor**: Area under Rabi season before bund correction (in hectares).
- **Rabi_AreaAfter bund correction factor**: Area under Rabi season after bund correction (in hectares).
- **Rabi_Yield**: Yield during Rabi season (in kg/hectare).
- **Rabi_Production**: Production during Rabi season (in tonnes).
- **Summer_AreaBefore bund correction factor**: Area under Summer season before bund correction (in hectares).
- **Summer_AreaAfter bund correction factor**: Area under Summer season after bund correction (in hectares).
- **Summer_Yield**: Yield during Summer season (in kg/hectare).
- **Summer_Production**: Production during Summer season (in tonnes).
- **All Seasons_AreaBefore bund correction factor**: Total area before bund correction (in hectares).
- **All Seasons_AreaAfter bund correction factor**: Total area after bund correction (in hectares).
- **All Seasons_Yield**: Total yield across all seasons (in kg/hectare).
- **All Seasons_Production**: Total production across all seasons (in tonnes).
- **Total_Production**: Total production across all seasons (in tonnes).

## Analysis Performed

### 1. Seasonal Contribution and Percentage Contribution to Total Rice Production
- Visualized the seasonal contribution to total rice production for the top 10 districts.
- Analyzed the percentage contribution of each season to the total production.

### 2. Total Rice Production and Rice Productivity (Yield) by District
- Bar plots showing total rice production and yield for all districts.

### 3. Yield vs Area and Yield vs Production (All Seasons)
- Scatter plots to analyze the relationship between yield and area, and yield and production.

### 4. Heatmap — Area, Yield & Production Correlations
- Heatmap showing correlations between area, yield, and production metrics.

### 5. Yield Efficiency Ranking (All Seasons)
- Bar plot ranking districts based on yield efficiency.

### 6. Scatter Plot of Kharif Season: Area vs Production
- Scatter plot to analyze the relationship between area and production during the Kharif season.

## Requirements

The following Python libraries are used in the notebook:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

## How to Use

1. Clone this repository and open the Jupyter Notebook.
2. Ensure the dataset (`datafile.csv`) is in the same directory as the notebook.
3. Run the cells in the notebook to generate the visualizations and analysis.

## Insights

- The analysis highlights the top-performing districts in terms of production and yield.
- Seasonal contributions to total production are visualized, providing insights into the importance of each season.
- Correlation analysis helps identify relationships between area, yield, and production.

## License

This project is licensed under the MIT License. Feel free to use and modify the code as needed.

## Data Source

The Data can be accessed using this link (https://www.data.gov.in/resource/crop-rice-area-hectares-production-tonnes-yield-kgshectare).
