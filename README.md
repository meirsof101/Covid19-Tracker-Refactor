# COVID-19 Global Data Tracker

A data analysis and visualization project that tracks global COVID-19 trends across countries and time. The project focuses on cases, deaths, and vaccinations using real-world data, with insights presented through charts, graphs, and maps.

## Project Objectives

- Import and clean global COVID-19 data  
- Analyze time-based trends in cases, deaths, and vaccinations  
- Compare pandemic metrics across countries and regions  
- Visualize key indicators using charts and choropleth maps  
- Summarize findings with narrative insights and data storytelling  

## Tools and Libraries Used

- Python 3  
- pandas – data manipulation and analysis  
- matplotlib – data visualization  
- seaborn – statistical data visualization  
- plotly.express – interactive choropleth maps  
- Jupyter Notebook – code, visuals, and markdown documentation  

## How to Run the Project

1. Clone the repository or download the project files.  
2. Ensure you have Python 3 and Jupyter Notebook installed (via Anaconda or pip).  
3. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn plotly
   ```
4. Launch Jupyter:
   ```bash
   jupyter notebook
   ```
5. Open the `covid_global_data_tracker.ipynb` file and run all cells.  
   Make sure the `owid-covid-data.csv` file is in the same folder as the notebook.

## Key Insights & Reflections

1. **Vaccine Rollouts**: High-income countries like the USA and UK had faster and broader vaccination campaigns.  
2. **Infection vs. Mortality**: Some countries had high case numbers but relatively low death rates due to stronger healthcare systems.  
3. **Emerging Trends**: Rolling averages reveal distinct waves of infection; vaccination appears to dampen peak severity.  
4. **Data Quality**: Some countries had missing or inconsistent data, highlighting challenges in global health reporting.
