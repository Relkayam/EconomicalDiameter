# EconomicalDiameter

# Optimal Pipe Diameter Selection in Water Supply Systems: A Python-Based Analysis

## Overview

This repository contains a Jupyter Notebook (`.ipynb` file) that implements a Python-based analysis to determine the economically optimal diameter for a pipe in a water supply system. The analysis considers both hydraulic limitations (using the Hazen-Williams equation) and economic factors (capital and operational costs, including the time value of money).

The notebook takes into account various pipe diameter options and their associated installation costs. It calculates head loss, required pump power, energy costs, and the annualized capital costs to determine the total cost for each diameter. By comparing these total costs, the notebook identifies the most economical pipe size for the given parameters.

Furthermore, the notebook includes a bonus section that allows for the exploration of how different financial parameters, such as return periods and interest rates, can influence the selection of the economic diameter.

## Contents

* **`Optimal_Diameter.ipynb`:** The main Jupyter Notebook containing the Python code and analysis.
* **`Pipes.xlsx`:** An Excel file (which the notebook expects to download from a specified path) containing the data for different pipe diameters and their installation costs per kilometer.

## Prerequisites

Before running the notebook, ensure you have the following Python libraries installed:

* **numpy:** For numerical computations.
* **pandas:** For data manipulation and working with DataFrames.

You can install these libraries using pip:

```bash
pip install numpy pandas