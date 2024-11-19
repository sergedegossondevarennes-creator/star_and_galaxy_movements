# Dynamic Mapping and Evolution of the Milky Way and Interacting Galaxies"

## Project Goals:
### Analyze Galactic Rotation Curves:

Study the relationship between radial distance and rotational velocity in galaxies to infer mass distribution (e.g., dark matter analysis).
Use rotation curves to create baseline models for individual galaxies.
Simulate Galactic Interactions:

### Incorporate collision and merger simulations to predict how interactions affect rotation curves and structure.
Explore the aftermath of galactic collisions (e.g., formation of spiral arms or elliptical galaxies).
### 3D Mapping of Stellar Data:

Create a 3D map of the Milky Way using real data from Gaia and other surveys.
Integrate data from nearby galaxies to simulate interactions and the broader cosmic neighborhood.
### Visualize Dynamic Changes:

Develop visualizations to show the impact of collisions and gravitational forces on galactic rotation and structure.
Model dynamic scenarios (e.g., before, during, and after collisions).
## Methodology:
### Data Collection:

### Rotation Curves: Use databases like NED and SDSS.
3D Stellar Mapping: Use Gaia's stellar position and velocity data.
Galaxy Collision Data: Leverage resources like the Illustris Project.
### Tools and Libraries:

Astrophysics Calculations: astropy, galpy
#### 3D Mapping: plotly, matplotlib
#### Simulation of Interactions: poliastro, numpy (for N-body simulations)
#### Data Analysis: pandas, scipy, sklearn

##Steps:

### Rotation Curve Analysis:
Use existing data to model the mass distribution of galaxies.
Predict the impact of galactic mergers on rotation curves.
### Collision Simulation:
Simulate N-body gravitational interactions between the Milky Way and nearby galaxies.
Test scenarios (e.g., Andromeda's collision with the Milky Way).
### 3D Mapping:
Plot the current positions and velocities of stars and galaxies.
Use simulation results to predict future structures.
### Visual Outputs:

Rotational curves before and after interactions.
Real-time visualization of galactic collisions and 3D maps of stars in the Milky Way.

## Potential Outcomes:
A deeper understanding of the relationship between rotation curves, dark matter, and galactic evolution.
Predictive models for future galactic collisions (e.g., the Milky Way-Andromeda interaction).
3D visualizations for better interpretation of galactic data and dynamics.

## References:
### Galactic Rotation Curves:

* Sloan Digital Sky Survey (SDSS)
* NASA/IPAC Extragalactic Database (NED)

### Galactic Collisions:

* Illustris Project
* Galaxy Zoo

### Stellar Mapping:

* Gaia Archive
* 2MASS

# Code architecture

```
galactic_dynamics_project/
│
├── data/                          # For storing raw and processed data
│   ├── raw/                       # Raw datasets
│   ├── processed/                 # Cleaned and prepared data
│
├── notebooks/                     # Jupyter notebooks for exploration
│   ├── rotation_analysis.ipynb    # Analyze galactic rotation curves
│   ├── collision_simulation.ipynb # Simulate galaxy collisions
│   ├── stellar_mapping.ipynb      # Create 3D maps of the Milky Way
│
├── src/                           # Core Python scripts
│   ├── data_processing.py         # Data cleaning and preparation
│   ├── rotation_curves.py         # Rotation curve analysis
│   ├── collision_simulation.py    # Galaxy collision simulations
│   ├── stellar_mapping.py         # 3D mapping of stars
│   ├── visualization.py           # Functions for plotting and animations
│
├── tests/                         # Unit tests for core modules
│   ├── test_rotation_curves.py
│   ├── test_collision_simulation.py
│   ├── test_stellar_mapping.py
│
├── outputs/                       # Save outputs (e.g., plots, animations)
│
├── requirements.txt               # Python dependencies
├── README.md                      # Project description and usage guide
└── main.py                        # Entry point for the entire workflow
```
