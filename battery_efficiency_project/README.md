# Battery Efficiency Analysis Project

## Overview
This project analyzes battery efficiency across different devices and usage patterns.
It follows the full data science pipeline: data loading, cleaning, exploration, and visualization.

## Project Structure
```
battery_efficiency_project/
│
├── data_process_v2.ipynb            # Data loading, cleaning, preprocessing
├── data_visualization_v2.ipynb       # Data visualization and plots
├── battery_efficiency_data.csv       # Raw dataset
├── battery_efficiency_processed.csv  # Processed dataset
├── requirements.txt                  # Python dependencies
├── *.png                             # Plots generated from the analysis
```

## How to Run
1. Clone the repository.
2. Install required packages:
    ```
    pip install -r requirements.txt
    ```
3. Run the Jupyter notebooks in order:
   - `data_process_v2.ipynb`
   - `data_visualization_v2.ipynb`
   
## Graphs Created
- Distribution of Battery Life
- Device Temperature vs Battery Life
- CPU Utilization vs Battery Life
- Memory Usage vs Battery Life

## Notes
- Data was cleaned by converting 'Battery Life' into total minutes.
- Visualizations created using `seaborn` and `matplotlib`.

## Acknowledgments
- Dataset: Self-created for project demonstration purposes.
