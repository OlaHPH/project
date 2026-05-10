# Waste treatment analysis in Europe (2004–2022)

## Overview
This project explores waste treatment operations across European countries 
from 2004 to 2022 using data from Eurostat.

## Research questions
1. Which European countries generate the most waste?
2. How have recovery and disposal operations changed over time?
3. Are there differences between hazardous and non-hazardous waste trends?

## How to run
1. Clone this repository
2. Open `project.ipynb` in Jupyter Notebook or VS Code.
3. Run all cells in order from top to bottom.
4. No API key required — data is fetched from the public Eurostat.

## Folder structure
```
project/
├── project.ipynb          — main notebook
├── Data_pipeline.png           — data pipeline diagram
├── README.md              — this file
├── data/
│   └── raw_waste_data.csv — raw data from Eurostat API
└── exports/
├── clean_waste_data.csv       — cleaned dataset
```
## Data source
Eurostat — Treatment of waste by waste category, hazardousness and waste management operations (env_wastrt)
URL: https://ec.europa.eu/eurostat/databrowser/product/page/env_wastrt

## AI use statement
Claude (Anthropic) was used to assist with concept explanation, debugging and alternative solution susgestion.
Solution is conducted based on my own understanding using course PythonForBusinessInt2026 material by Sippo Jussi via https://github.com/sippohippo/PythonForBusinessInt2026.