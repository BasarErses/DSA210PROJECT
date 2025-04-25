# Battery Efficiency Analysis Project

## 📌 Motivation
Battery performance is crucial for device usability, especially under varying workloads. This project investigates how different factors—such as CPU usage, memory usage, temperature, and screen brightness—affect battery efficiency across devices.

## 🗂️ Project Structure
```
battery_efficiency_project/
│
├── data_process.ipynb            # Data loading, cleaning, preprocessing
├── data_visualization.ipynb      # Data visualization and plots
├── ml_modeling.ipynb             # Machine learning model for battery life prediction
├── battery_efficiency_data.csv   # Raw dataset
├── parameter_summaries.csv       # CPU, temperature, and memory usage stats
├── *.png                         # Visual output graphs
├── requirements.txt              # Python package list
├── README.md                     # Project documentation
```

## 🔍 Data Source
The dataset was synthetically generated to simulate real-world battery performance measurements. It includes multiple device models, task types, and performance indicators.

## 📊 Analysis Overview
- Data was cleaned and battery life converted into minutes
- Exploratory visualizations included: battery life distribution, boxplots by task type, and heatmaps
- Summary statistics were calculated per-parameter (CPU, memory, temperature)

## 🤖 ML Modeling
A linear regression model was trained to predict battery life (in minutes). Features used:
- Brightness level
- Battery health
- CPU utilization
- Memory usage
- Task type (encoded)

## 📈 Findings
- Higher CPU and memory usage were generally correlated with lower battery life
- Temperature increases with workload intensity but has non-linear effects
- Certain task types (like Gaming or Streaming) consistently showed lower battery durations

## 🚧 Limitations & Future Work
- Dataset is simulated and may not reflect all edge-case scenarios
- Could be extended with external real-time device logging data
- More advanced models can be tried

---

