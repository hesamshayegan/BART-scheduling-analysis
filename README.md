# BART Scheduling Analysis: Richmond ↔ Civic Center

## 🚆 Overview
This project analyzes scheduled BART trips between **Richmond (RICH)** and **Civic Center (CIVC)** using the BART API. It focuses on trip durations, transfers, and schedule consistency.

## Key Insights
- Average trip time ≈ **40.5 minutes**, with most trips clustering around **40–41 minutes**.  
- Both direct trips (RICH → CIVC) and transfer trips (via MacArthur, MCAR) take similar durations.  
- Schedule shows strong consistency across the observed window.

## How It Works
1. Pull trip data from the BART API.  
2. Normalize JSON into tables with pandas.  
3. Compute durations, assign trip IDs, and group legs.  
4. Visualize timelines and durations with Plotly.

## Requirements
- Python 3.x  
- Libraries: `pandas`, `requests`, `plotly`

## Run
```bash
git clone https://github.com/hesamshayegan/BART-scheduling-analysis.git
cd BART-scheduling-analysis
jupyter notebook richmond_civic_analysis.ipynb
