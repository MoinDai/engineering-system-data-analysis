# CNC Spindle Sensor Data Analysis

Analysis of pressure and temperature sensor data 
from a CNC machine tool spindle to detect anomalies 
and support predictive maintenance.


## Learning Log

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
