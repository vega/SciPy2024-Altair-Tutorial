# Vega-Altair Tutorial for SciPy 2024
This repository contains resources for the Vega-Altair tutorial for [SciPy 2024](https://www.scipy2024.scipy.org/).

See the [tutorial description](https://cfp.scipy.org/2024/talk/CLKG8E/) for more information.

## Dependencies
The only Python dependency of this tutorial is the `altair` package with the `all` extras enabled.

To install with pip from PyPI:
```
pip install altair[all]
```

Or, to install from conda-forge:
```
conda install -c conda-forge altair-all vega_datasets anywidget
```

During the live tutorial at SciPy 2024, participants are encouraged to use the Nebari JupyterHub distribution (https://scipy.quansight.dev) with the `vega-altair-tutorial` conda environment, which has these dependencies pre-installed.

## Outline
This tutorial is divided into four parts, each focusing on different aspects of data visualization using Vega-Altair. Below is an outline of the tutorial along with links to each notebook.

### Part 1: Data Types, Graphical Marks, and Visual Encoding Channels
- **Objective**: Learn the basic syntax of Altair, understand how to encode data into visual properties, and customize chart appearances.
- **Key Topics**:
  - Basic Altair syntax
  - Encoding data dimensions
  - Customizing chart appearance
- **Notebook**: [Part 1 - Data Types, Graphical Marks, and Visual Encoding Channels](part1/Part%201%20-%20Data%20Types%2C%20Graphical%20Marks%2C%20and%20Visual%20Encoding%20Channels.ipynb)
  - With all inline code: [Completed - Part 1 - Data Types, Graphical Marks, and Visual Encoding Channels](part1/completed/Completed%20-%20Part%201%20-%20Data%20Types%2C%20Graphical%20Marks%2C%20and%20Visual%20Encoding%20Channels.ipynb)
- **Exercises**: [Part 1 - Exercises](part1/Part%201%20-%20Exercises.ipynb)

### Part 2: Data Transformation
- **Objective**: Learn about integrating data transformations into a chart definition.
- **Key Topics**:
  - Binning and aggregation
  - Advanced data transformations

- **Notebook**: [Part 2 - Data Transformation](part2/Part%202%20-%20Data%20Transformation.ipynb)
- **Exercises**: [Part 2 - Exercises](part2/Part%202%20-%20Exercises.ipynb)

### Part 3: Interactivity
- **Objective**: Learn how to add interactivity to charts.
- **Key Topics**:
  - Basic interactive features (tooltips and pan/zoom)
  - Selection parameters
  - Conditional encodings and filtering
- **Notebook**: [Part 3 - Interactivity](part3/Part%203%20-%20Interactivity.ipynb)
- **Exercises**: [Part 3 - Exercises](part3/Part%203%20-%20Exercises.ipynb)

### Part 4: Sharing and Publishing Visualizations
- **Objective**: Learn how to share and publish your Vega-Altair visualizations.
- **Key Topics**:
  - Exporting charts as HTML
  - Saving charts as static images (PNG, SVG, PDF)
  - References for embedding charts in static documents (Quarto, Jupyter Book, LaTeX)
  - References for creating dashboards
- **Notebook**: [Part 4 - Sharing and Publishing Visualizations](part4/Part%204%20-%20Sharing%20and%20publishing%20visualizations.ipynb)
- **Exercises**: [Part 4 - Exercises](part4/Part%204%20-%20Exercises.ipynb)
