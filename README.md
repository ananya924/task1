# task1

## Overview  
- Analyze 3-year cyclone sensor dataset.  
- Tasks: data cleaning, shutdown detection, clustering, anomaly detection, forecasting, insights.

## How to Run  
- Use `task1_analysis.ipynb` Jupyter notebook.  
- Install dependencies: `pip install -r requirements.txt`.  
- Run notebook cells top to bottom.

## Tasks & Deliverables  

- **Data Prep & EDA:** 
  - Clean data, handle missing/outliers.  
  - Summary stats & correlation.  
  - Visualize sample periods.
    
- **Shutdown Detection:**  
  - Identify shutdown periods.  
  - Calculate downtime & event count.  
  - Visualize with highlights.

- **Machine State Clustering:**  
  - Exclude shutdowns.  
  - Cluster active data (KMeans, DBSCAN).  
  - Define states with stats & descriptions.

- **Anomaly Detection & Root Cause:**  
  - Detect anomalies per cluster.  
  - List events with metadata.  
  - Explain selected anomalies.  
  - Visualize anomalies.

- **Short-Horizon Forecasting:**  
  - Forecast inlet gas temp (1-hour ahead).  
  - Compare models (baseline + ML).  
  - Evaluate and discuss.

## Output Files
- `shutdown_periods.csv`  
- `anomalous_periods.csv`  
- `clusters_summary.csv`  
- `forecasts.csv`  
- `plots/` folder with PNG visualizations

