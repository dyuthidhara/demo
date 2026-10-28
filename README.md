# Simulating Physiological Arousal and Psychological State

## Overview
A small Python project demonstrating reproducible simulation, descriptive analysis, correlation analysis, and visualisation of illustrative physiological and subjective-state signals.

## Research question
How can simulated physiological and subjective-state variables be generated, visualised, and explored using a reproducible computational workflow? The given workflow aims to assess the exact threshold of EDA and heart rate at which a consumer switches to a different brand owing to frustration arising from high cost, lack of repairability, and shorter use-cycle leading to frequent replacements. 

## Data
All observations are simulated. They are not real participant measurements.

## Methods
- Reproducible random-number generation
- Data organisation using pandas
- Descriptive statistics
- Spearman correlation analysis
- Visualisation using Matplotlib

## How to run
1. Install Python.
2. Install dependencies with `pip install -r requirements.txt`.
3. Open `01_reproducible_physiological_simulation.ipynb` in Jupyter or Google Colab.
4. Run all cells from beginning to end.

## Outputs
- `outputs/simulated_data.csv`
- `outputs/simulated_signals.png`

## Limitations
The simulated variables are defined by illustrative mathematical functions. Correlations may reflect common time trends. Results do not establish empirical or causal relationships in human physiology.

## Future development
Potential extensions include analysis of appropriately sourced real physiological data and a separately labelled computational demonstration of approach–avoidance decisions.

## Author
Dyuthidhara Gurunath
