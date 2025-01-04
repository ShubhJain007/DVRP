# Course Project CS637- Intro to Cyber-Physical Systems

For more details on implementation and explain kindly review the attached presentation in the repo.


# Dynamic Vehicle Routing Problem (DVRP)

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Julia Version](https://img.shields.io/badge/Julia-v1.6+-blue)](https://julialang.org/)

This repository contains a project implementation for solving the **Dynamic Vehicle Routing Problem (DVRP)**. It includes tools for data preparation, simulation, and analysis, tailored to optimize dynamic routing in cyber-physical systems.

## Features
- **Data Preparation**: Tools for processing raw trip data and generating travel time matrices.
- **Dynamic Simulation**: Real-time routing using the ICAPS baseline model (DRLSA).
- **Analysis**: Visualizations and outputs for evaluating performance.

## Quick Start
### 1. Clone the Repository
```bash
git clone https://github.com/ShubhJain007/DVRP.git
cd DVRP
```

### 2. Set Up the Environment
Follow the [setup guide](setup/setup_guide.md) to install dependencies and set up Julia.

### 3. Run the Simulation
```bash
cd bin
julia sim_proc.jl
```

## Repository Structure
- **`data/`**: Raw and processed datasets for the DVRP simulations.
- **`dataprep/`**: Scripts for preparing trip data and travel time matrices.
- **`bin/`**: Main simulation executable (`sim_proc.jl`).
- **`docs/`**: Project documentation.
- **`examples/`**: Example inputs and outputs for DVRP simulations.
- **`results/`**: Output data from simulations.

## Documentation
Detailed documentation is available in the [docs/](docs/) folder:
- [Introduction](docs/introduction.md)
- [Simulation Workflow](docs/simulation_workflow.md)
- [Usage Examples](docs/usage_examples.md)

## Contributing
We welcome contributions! See [CONTRIBUTING.md](docs/contributing.md) for more information.

## License
This project is licensed under the [MIT License](LICENSE).
