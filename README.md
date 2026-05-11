# CNC Spindle Sensor Data Analysis

Analysis of pressure and temperature sensor data 
from a CNC machine tool spindle to detect anomalies 
and support predictive maintenance.


## Learning Log
### Day 23: Add cross validation, feature importance plot, and StandardScaler
### Day 22: Add Random Forest and feature importance
### Day 21: Add train/test split and model evaluation
### Day 20: Linear regression intro with sklearn (cnc_ml.ipynb)

### Engineering Context
- Pressure spike (>2σ): indicates potential tool wear
- Temperature spike (>2σ): indicates thermal overload
- Vibration spike (>2σ): indicates mechanical fault

###  Day 19: Add legend to moving average plot, refactor anomaly plot
### Day 18: Add moving average smoothing for all three sensors
###  Day 17: Add reusable detect_anomalies() function
###  Day 16: Combine anomaly detection plots into one figure
### Day 15: Add axis labels and titles to overview plot
###  Day 14: Added anomaly detection for all three sensors
### Day 13: Created cnc_analysis.ipynb from scratch

### Day 12 - 2026-04-16
- Generated CNC sensor data with 100 data points (spindle_pressure, spindle_temp, vibration)
- Added 3 manual anomalies at row 30, 55, 78
- Created 3-variable overview plot: cnc_overview.png
- Learned: Boolean indexing, np.random.normal parameters
- First time using Git Bash to push from command line
- 
### Day 11: Update project description for engineering context

### Day 10 - April 8, 2026 (Completed)
- **Data Visualization**: Generated a comparison plot using `matplotlib` to verify the smoothing effect.
- **Troubleshooting**: Fixed a `KeyError: 'pressure_smooth'` by ensuring the data processing cell runs before the plotting cell.

### Day 10 - April 7, 2026
- Fixed the 'AttributeError' in the data cleaning step.
- Learned how to use 'rolling mean' to smooth sensor data.
- Understood the difference between 'limit' and 'threshold' in functions.
- Tomorrow's goal: Plot the comparison graph. 
