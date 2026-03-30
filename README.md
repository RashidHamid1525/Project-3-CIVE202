# Project 3 CIVE202  
##  Project Summary
This project analyzes transportation data provided by the Federal Highway Administration (FHWA) using Python. Two datasets were used: the National Household Travel Survey (NHTS) and the Next Generation Simulation (NGSIM) dataset.

The goal of this project is to:
- Visualize transportation trends and travel behavior  
- Analyze vehicle movement and interactions  
- Simulate vehicle behavior using the Intelligent Driver Model (IDM)  

The results provide insight into travel demand, vehicle characteristics, and driving behavior, which are important for transportation planning, safety analysis, and traffic flow modeling.


## Data Files Used
The following datasets are required to run the code:

- `NHTS.csv`  
  Contains travel behavior data such as travel day, vehicle age, and vehicle type  

- `NGSIM.csv`  
  Contains vehicle trajectory data including time, speed, acceleration, and position  

 These files must be placed in the same folder as the Python code or notebook.

##  Python Code
- `Project3Code.ipynb`  
  Main Jupyter Notebook used for all analysis, visualization, and simulation  

The code performs:
- Data import and cleaning using pandas  
- Variable selection and filtering  
- Visualization using matplotlib and seaborn  
- Time-series analysis of vehicle behavior  
- IDM simulation  

##  Visualizations
The following plots are included in the analysis:

- **Bar Chart**  
  Variable: `travel_day`  
  Purpose: Compare trip frequency across days  

- **Histogram**  
  Variable: `vehicle_age`  
  Purpose: Show distribution of vehicle ages  

- **Boxplot**  
  Variables: `vehicle_type` vs `vehicle_age`  
  Purpose: Compare vehicle age across categories  

- **Time-Series Plots (NGSIM)**  
  - Leader vs follower speed  
  - Vehicle spacing over time  


##  User Step by Step Guide

### Step 1: Download the Repository
Download this repository to your computer.

### Step 2: Add Data Files
Place the following files in the project folder:
- `NHTS.csv`  
- `NGSIM.csv`

### Step 3: Open the Notebook
Open: Project3Code.ipynb

### Step 4: Run the Code
Run all cells from top to bottom. The code will:
- Load and clean datasets  
- Generate all visualizations  
- Run the IDM simulation  

### Step 5: View Results
- Graphs will display in the notebook  
- Simulation results will be plotted and compared to real data  


##  Methods Used
- Data cleaning and manipulation using pandas  
- Frequency counting and grouping  
- Data visualization using matplotlib and seaborn  
- Time-series analysis  
- Simulation using a Python loop (IDM model)  



##  Deliverables
- Jupyter Notebook (.ipynb)  
- Python Code File (.py)  
- Scope of Work  
- Annotated Code Document  
- Technical Report  
- Engineering Timesheet  
- Gantt Chart  
