# Nuclear Energy Adoption Economic Impact Simulation

This repository contains a Jupyter Notebook that simulates the economic impacts of various nuclear energy adoption scenarios in Australia. The simulation uses a Monte Carlo approach to assess key economic indicators under three adoption scenarios: low (5%), high (20%), and very high (40%) nuclear adoption rates by 2050.

## Key Components

### Simulation Code
The code utilises a Monte Carlo method to generate a range of outcomes for economic indicators based on specified means and standard deviations. The primary function, `run_monte_carlo`, simulates multiple economic variables, including:
- GDP impact
- Job creation and job loss in fossil fuel sectors
- Emissions reduction
- Economic multiplier effects
- Export revenue and fossil revenue losses
- Electricity price increase
- Market concentration
- Tax revenue and waste management costs

### Confidence Intervals
A `calc_ci` function calculates 90% confidence intervals for each simulated variable to estimate the range of likely outcomes.

### Visualisation
The `plot_results` function generates histograms to visualise and compare the frequency distributions for high, medium and low adoption scenarios across various indicators.

### Results
The notebook outputs summary statistics, including mean values and 90% confidence intervals, for each adoption scenario. This provides insights into potential economic outcomes associated with different nuclear adoption levels.

## Requirements
This code requires:
- Python 3.x
- numpy, matplotlib, scipy

## How to Use
Open the `.ipynb` file in a Jupyter Notebook environment and run all cells to execute the simulation and view the results.

