# Python Data Analysis Project

A Python-based data analysis workspace built with NumPy, pandas, Matplotlib, and seaborn. The project notebook provides the starting point for loading, exploring, analyzing, and visualizing data.

## Features

- Numerical operations with NumPy
- Tabular data loading and manipulation with pandas
- Static plots with Matplotlib
- Statistical visualizations with seaborn

## Requirements

- Python 3.9 or newer
- Jupyter Notebook or JupyterLab

Python packages:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`

## Installation

Clone the repository and enter the project directory:

```bash
git clone <repository-url>
cd <project-directory>
```

Create and activate a virtual environment:

```bash
python -m venv .venv
```

On Windows:

```powershell
.venv\Scripts\Activate.ps1
```

On macOS or Linux:

```bash
source .venv/bin/activate
```

Install the dependencies:

```bash
python -m pip install jupyter numpy pandas matplotlib seaborn
```

## Usage

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open `file_project_1.ipynb`, then run the notebook cells from top to bottom.

## Project Structure

```text
.
|-- file_project_1.ipynb
`-- README.md
```

## Development

When adding new analysis steps:

1. Import required libraries in a dedicated setup cell.
2. Document data sources and assumptions.
3. Separate loading, cleaning, analysis, and visualization steps.
4. Include clear cell headings and concise explanations.
5. Keep generated plots and processed data in appropriately named folders.

## License

Add a license file if you plan to distribute this project.
