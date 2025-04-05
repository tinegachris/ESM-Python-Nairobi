# ESM Python Nairobi

[![GitHub License](https://img.shields.io/github/license/tinegachris/ESM-Python-Nairobi.svg)](https://github.com/tinegachris/ESM-Python-Nairobi/blob/main/LICENSE)
[![GitHub Contributors](https://img.shields.io/github/contributors/tinegachris/ESM-Python-Nairobi.svg)](https://github.com/tinegachris/ESM-Python-Nairobi/graphs/contributors)
[![GitHub Issues](https://img.shields.io/github/issues/tinegachris/ESM-Python-Nairobi.svg)](https://github.com/tinegachris/ESM-Python-Nairobi/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/tinegachris/ESM-Python-Nairobi.svg)](https://github.com/tinegachris/ESM-Python-Nairobi/pulls)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![GitHub Stars](https://img.shields.io/github/stars/tinegachris/ESM-Python-Nairobi.svg?style=social&label=Star)](https://github.com/tinegachris/ESM-Python-Nairobi/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/tinegachris/ESM-Python-Nairobi.svg?style=social&label=Fork)](https://github.com/tinegachris/ESM-Python-Nairobi/network/members)
[![GitHub Watchers](https://img.shields.io/github/watchers/tinegachris/ESM-Python-Nairobi.svg?style=social&label=Watch)](https://github.com/tinegachris/ESM-Python-Nairobi/watchers)

![](images/graphics/Python%20for%20Energy%20System%20Modelling.jpg)

Welcome to the ESM Python Nairobi repository! This repository contains resources, and documentation related to Energy System Modelling (ESM) using Python, with a focus on the PyPSA (Python for Power System Analysis) library. These materials were used for the ESM Python Nairobi session.

## Directory Structure

-   `docs/` - Detailed write-ups, slides, and additional resources.
-   `notebooks/` - Jupyter Notebooks with live examples and tutorials.
    -   `tutorials/` - Step-by-step guides covering PyPSA fundamentals and applications.
-   `images/` - Screenshots, event photos, and diagrams used in documentation or notebooks.

## Tutorials Overview

The `notebooks/tutorials/` directory contains the following guides:

1.  **`01_getting_started.ipynb`**: Introduces PyPSA, basic network creation, components, power flow, and visualization.
2.  **`02_components_basics.ipynb`**: Covers the core PyPSA components (Bus, Generator, Load, Line, Store, etc.) and their configuration.
3.  **`03_network_visualization.ipynb`**: Demonstrates static and interactive network plotting, including geographic maps with `cartopy`.
4.  **`04_basic_optimization.ipynb`**: Explains different optimization types: Power Flow (PF), Linear Optimal Power Flow (LOPF), and Investment Optimization.
5.  **`05_investment_planning.ipynb`**: Details multi-period investment planning, costs, discount rates, and capacity expansion.
6.  **`06_storage_and_balancing.ipynb`**: Focuses on modelling various storage types (electrical, thermal, hydrogen) and demand-side management.
7.  **`07_sector_coupling.ipynb`**: Covers integrating power, heat, transport demand, and hydrogen sectors using coupling technologies.
8.  **`08_diy_solar_simulation.ipynb`**: A practical example modelling a small Solar Home System (SHS) with PV and battery.

## Getting Started

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/tinegachris/ESM-Python-Nairobi.git
    cd ESM-Python-Nairobi
    ```

2.  **Install dependencies:**
    Ensure you have Python installed. Then, install the required packages using pip:
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the notebooks:**
    Navigate to the `notebooks/tutorials/` directory and launch Jupyter Lab or Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
    Then open the desired `.ipynb` file to start exploring.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues.

## Questions?

If you have questions about the materials, feel free to raise an issue in this repository.
