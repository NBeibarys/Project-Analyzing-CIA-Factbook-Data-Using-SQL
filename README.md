[![Open in Jupyter](https://img.shields.io/badge/Open%20in-Jupyter-orange?logo=jupyter)](Project.ipynb)   

# World Factbook Data Analysis
This project explores global socioeconomic and demographic indicators using the CIA World Factbook dataset. The goal is to extract meaningful insights about population, geography, and other indicators across countries, while also practicing SQL-driven analysis. 

## Project Structure
- `Project.ipynb` - Jupyter Notebook with SQL code.
- `factbook.db` - SQLite database containing World Factbook data (population, GDP, area, resources, etc.).

## Key Insights
- Identified outliers (e.g., World, Antarctica) and built a clean dataset to avoid skewed results.

- Analyzed population growth trends, pinpointing regions with rapid demographic pressure.

- Identified countries with the highest and lowest population densities, showing striking global contrasts.

- Identified nations with natural population decline (death rate > birth rate), interpreting results with unit-aware rigor.

- Implemented SQL best practices (CTEs, safe division, filtering NULLs/zeros) to ensure reproducibility and reliability.
  
## Tools & Technologies
 - **SQL** 
- **Jupyter Notebook** 

## Data Source 
- Provided by the [CIA](https://www.cia.gov/the-world-factbook/)
- Download [dataset](https://github.com/NBeibarys/Project-Analyzing-CIA-Factbook-Data-Using-SQL/blob/main/factbook.db)
