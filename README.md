# Project 3 – Transportation Data Analysis and IDM Simulation

## Project Overview
This project analyzes transportation trends and driving behavior using two datasets: the National Household Travel Survey (NHTS) and the Next Generation Simulation (NGSIM) dataset.

The NHTS dataset provides information about household travel characteristics, while the NGSIM dataset provides detailed vehicle trajectory data. The project includes data visualization and a simulation study using the Intelligent Driver Model (IDM).

---

## Objectives
- Create visualizations to identify transportation trends
- Analyze driving behavior using time-series data
- Simulate vehicle following behavior using the IDM model
- Compare simulated results with real trajectory data

---

## Data Used
- **NHTS.csv** – household travel data
- **NGSIM.csv** – vehicle trajectory and driving behavior data

---

## Visualizations Included
- Bar chart: fuel type distribution
- Histogram: household size distribution
- Boxplot: vehicle age by household location
- Time-series plots:
  - Follower speed vs time
  - Leader and follower position vs time
  - Gap distance vs time (extra analysis)

---

## Simulation Study (IDM)
The Intelligent Driver Model (IDM) is used to simulate follower vehicle behavior.

- Leader vehicle data is used as input
- Initial follower conditions are taken from real data
- Acceleration is calculated using IDM equations
- Speed and position are updated over time
- Simulated results are compared with actual data

---

## Tools and Libraries
- pandas
- numpy
- matplotlib
- seaborn

---

## User Guide
1. Open the Jupyter Notebook file: CIVE202_Spring2026_Group8_Final_Python_Code.ipynb
   
2. Make sure the following files are in the same folder:
- NHTS.csv
- NGSIM.csv

3. Run all cells in order from top to bottom.

4. The notebook will:
- load the datasets
- create all required plots
- run the IDM simulation
- display results and comparisons

---

---

## Summary
The results show clear transportation trends in the NHTS dataset and realistic driving behavior in the NGSIM dataset. The IDM simulation produces similar patterns to the actual data, demonstrating the ability of the model to represent vehicle following behavior.
