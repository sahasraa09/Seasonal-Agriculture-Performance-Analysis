# Seasonal Agriculture Performance Analysis

**VOIS AICTE Batch1 2026-2027 — Major Project**

## Overview
This project analyzes a seasonal agriculture dataset to investigate how yield, profit, 
water efficiency, and pest risk vary across the Kharif, Rabi, and Zaid seasons, and 
identifies patterns that can support evidence-based agricultural planning.

## Dataset
`seasonal_agriculture_performance_dataset.csv` — 4,000 farm-level records across multiple 
Indian states, crops, and irrigation methods, covering farming practices, environmental 
conditions, and economic outcomes.

## Contents
- `Seasonal_Agriculture_Performance_Analysis.ipynb` — full analysis notebook (data cleaning, 
  EDA, visualizations, key findings, recommendations, conclusion)
- `seasonal_agriculture_performance_dataset.csv` — raw dataset used in the analysis
- `chart1_yield_by_season.png` through `chart7_fertilizer_vs_yield.png` — saved chart outputs

## How to run
1. Clone this repository (or download the notebook and CSV into the same folder).
2. Open `Seasonal_Agriculture_Performance_Analysis.ipynb` in Jupyter or Google Colab.
3. Run all cells — the notebook reads the CSV directly from the same folder, no additional 
   setup required.

## Key Findings
- Kharif is the most profitable and highest-yielding season; Zaid runs at a loss on average.
- Sugarcane outperforms other crops in yield across all seasons.
- Rainfall and temperature show a weak correlation with yield in this dataset.
- Rainfed farming shows the highest water efficiency, followed by Drip.
- Fertilizer usage shows a near-zero correlation with yield, warranting further investigation.

## Author
M. Lakshmi Sahasra — Megha Institute of Engineering and Technology for Women
