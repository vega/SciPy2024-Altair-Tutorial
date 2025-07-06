# Vega-Altair Tutorial for SciPy 2024
This repository contains resources for the Vega-Altair tutorial for [SciPy 2024](https://www.scipy2024.scipy.org/).

See the [tutorial description](https://cfp.scipy.org/2024/talk/CLKG8E/) for more information.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/vega/SciPy2024-Altair-Tutorial/HEAD)

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

### Part 1: Effective Visual Data Communication
- **Objective**: Understand the principles of designing effective and perceptually efficient visualizations, including chart anatomy, the grammar of graphics, and how design choices impact viewer comprehension.
- **Key Topics**:
  - Grammar of Graphics: marks and encoding channels
  - Human perception and graphical effectiveness
  - Visual affordances and Gestalt principles
  - Using color, annotations, and layout to guide attention
  - Common visualization pitfalls and how to avoid them

### Part 2: Data Types, Graphical Marks, and Visual Encoding Channels
- **Objective**: Learn the basic syntax of Altair, understand how to encode data into visual properties, and customize chart appearances.
- **Key Topics**:
  - Basic Altair syntax
  - Encoding data dimensions
  - Customizing chart appearance
- **Notebook**: [Part 2 - Data Types, Graphical Marks, and Visual Encoding Channels](part2/Part%202%20-%20Data%20Types%2C%20Graphical%20Marks%2C%20and%20Visual%20Encoding%20Channels.ipynb)
- **Exercises**: [Part 2 - Exercises](part2/Part%202%20-%20Exercises.ipynb)

### Part 3: Data Transformation and Interactivity
- **Objective**: Learn about integrating data transformations and interactivity into a charts.
- **Key Topics**:
  - Binning and aggregation
  - Basic interactive features (tooltips and pan/zoom)
  - Selection parameters
  - Conditional encodings and filtering
- **Notebook**: [Part 3 - Data Transformation](part3/Part%203%20-%20Data%20Transformation%20and%20Interaction.ipynb)
- **Exercises**: [Part 3 - Exercises](part3/Part%203%20-%20Exercises.ipynb)

### Part 4: Workflows with Altair
- **Objective**: Learn how to export and share Altair visualizations in various formats, integrate with dashboarding systems, and create custom theming for consistent visual design across projects.
- **Key Topics**:
  - Exporting visualizations (HTML, PNG, SVG, PDF)
  - Creating self-contained shareable URLs
  - Integration with dashboarding systems (PowerBI, Panel, Streamlit)
  - Building custom charting libraries with Altair
  - Applying themes and consistent styling across charts
- **Notebook**: [Part 4 - Workflows with Altair](part4/Part%204%20-%20Workflows%20with%20Altair.ipynb)
- **Exercises**: [Part 4 - Exercises](part4/Part%204%20-%20Exercises.ipynb)

