# Bayesian Knowledge Tracing Implementation

A Python implementation of the Bayesian Knowledge Tracing (BKT) model based on Corbett and Anderson's work (1995). BKT is a statistical model that aims to estimate a student's knowledge state through their pattern of correct and incorrect responses.

## Overview

This implementation models the acquisition of student knowledge as described in:
> Corbett, A. T.; Anderson, J. R. (1995). "Knowledge tracing: Modeling the acquisition of procedural knowledge". User Modeling and User-Adapted Interaction. 4 (4): 253–278.


## Requirements

See the `Requirements` file for detailed dependencies.

## Setup

1. Clone this repository
2. Install the required dependencies:
```bash
pip install -r Requirements
```

## Usage
Run the main script
```bash
python run.py
```

## Model Parameters
The BKT model uses four parameters:

- Initial Knowledge (p(L₀)): Probability a student knows the skill before any practice
- Learning Rate (p(T)): Probability of transitioning from not knowing to knowing the skill
- Slip (p(S)): Probability of making a mistake despite knowing the skill
- Guess (p(G)): Probability of correctly answering despite not knowing the skill

## Configurations
Model parameters and runtime settings can be configured in `config.json`.