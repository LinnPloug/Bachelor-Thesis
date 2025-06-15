# Bachelor Thesis: Data Analysis

This repository contains data analysis scripts and measurement data used for the bachelor thesis:

**"An Integrated Pressure Sensor for Standardized Optical Coherence Tomography Angiography."**

## Notebook naming format

Each Jupyter Notebook used for data analysis follows this naming convention:  
**FSR_Test_[resistor value].ipynb**

---

## Overview

The project investigates the behavior of a Force Sensitive Resistor (FSR) under different electrical configurations.  
It includes signal acquisition, statistical analysis, and evaluation of the sensor’s performance using different reference resistors and test rounds.

---

## Data folder

The `/data/` folder contains raw measurement data from all test rounds (TR) for each reference resistor (RM).  
Each dataset represents a full test round, consisting of 60-second recordings for five individual weights.

**Structure:**
- `TR` = Test Round (e.g., TR1, TR2...)  
- `RM` = Reference resistor used during that round (e.g., 2.2kΩ, 10kΩ, etc.)

These files are used in the analysis notebooks to extract features like signal mean, standard deviation, and evaluate performance across test conditions.
