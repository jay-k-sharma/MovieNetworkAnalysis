# Network Analysis and Propagation Dynamics of the Most Successful Films

## Overview

This repository contains Python scripts and data files used for conducting network analysis on the top films to understand their success factors based on shared actors. The analysis employs techniques like network construction, community detection, and centrality measures.

## Contributors

- Jay Sharma 
- Saiz Prasla
- Harsimran Saini
- Zuhair Siddiqi

## Motivation

The motivation behind this project is to explore connections between successful films through shared actors, aiming to provide insights that could benefit filmmakers and industry stakeholders in optimizing film production decisions.

## Files

### Code Files

1. **data_collection.py**: Python script to collect data from TMDB API, cleanse it, and prepare it for analysis.
2. **network_construction.py**: Script to construct the film network based on shared actors and compute edge weights.
3. **analysis.py**: Contains functions for performing network analysis using algorithms like PageRank, Louvain community detection, and degree centrality.
4. **utils.py**: Utility functions used across the scripts for data preprocessing and calculation.

### Data Files

1. **top_films_data.csv**: CSV file containing details of the top-rated films used in the analysis, including budget, revenue, genres, actors, etc.
2. **film_network.graphml**: GraphML file representing the film network with nodes as films and weighted edges based on shared actors.

## Setup Instructions

To run the scripts and replicate the analysis:

1. **Prerequisites**:
   - Python 3.x installed.
   - Required Python packages installed (listed in `requirements.txt`).

2. **Installation**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Running the Scripts**:
   - Adjust configurations (API keys, file paths) in the scripts if necessary.
   - Execute each script in the following order:
     ```bash
     python data_collection.py
     python network_construction.py
     python analysis.py
     ```

4. **Output**:
   - Check generated output files (`film_network.graphml`, etc.) for results of the analysis.

## Additional Notes

- Ensure API keys and paths to data files are correctly configured in the scripts.
- For detailed explanations of algorithms and methodologies used, refer to the comments within each script.
- For any questions or issues, contact the contributors listed above.
