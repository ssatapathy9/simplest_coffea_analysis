# simplest_coffea_analysis
# Coffea Analysis Workflow

## Overview
The **Coffea Analysis Workflow** is a data analysis pipeline designed for high-energy physics (HEP) workflows using the [Coffea](https://coffeateam.github.io/coffea/) framework. This repository provides tools for processing large datasets efficiently with parallel execution, making it ideal for physics data analysis.

## Repository Structure
```
Coffea_Analysis_Workflow/
│── README.md        # Project documentation
│── fileset.json     # JSON file specifying input datasets
│── plotter.py       # Script for visualizing processed data
│── processor.py     # Defines the event processing logic
│── runner.py        # Main script for running the analysis
│── runner2.py       # Alternate execution workflow
│── shell/           # Shell scripts for setup and execution
```

## Installation
This project requires Python and the Coffea package. To install dependencies, run:
```bash
pip install coffea matplotlib numpy
```

## Usage
### 1. Define Input Data
Modify `fileset.json` to specify the datasets to be processed.

### 2. Run the Analysis
Execute the main runner script:
```bash
python runner.py
```
Alternatively, use `runner2.py` if needed:
```bash
python runner2.py
```

### 3. Generate Plots
After processing, visualize the results:
```bash
python plotter.py
```

## Customization
- **Processing Logic**: Modify `processor.py` to implement custom event selection and feature extraction.
- **Dataset Configuration**: Update `fileset.json` to include different input datasets.

## Contributing
Feel free to contribute by submitting pull requests or reporting issues!

## License
This project is open-source and licensed under the MIT License.

