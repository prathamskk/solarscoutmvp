# SolarScout MVP - Jupyter Environment

This directory is set up with a dedicated Python 3.11 virtual environment and Jupyter kernel.

## Setup Overview

- **Virtual Environment**: `.venv/`
- **Jupyter Kernel**: `solarscoutmvp` (`Python (solarscoutmvp)`)
- **Python Version**: 3.11.9
- **Included Packages**: `jupyterlab`, `notebook`, `ipykernel`, `ipywidgets`, `pip`

---

## Quick Start

### 1. In VS Code / Antigravity IDE
1. Open [starter.ipynb](file:///c:/Users/Pratham/Documents/GitHub/solarscoutmvp/starter.ipynb).
2. Click **Select Kernel** in the top right of the notebook.
3. Choose **Python Environments...** -> **`.venv`** or select **Jupyter Kernel...** -> **`Python (solarscoutmvp)`**.

### 2. Launching Jupyter Lab from Terminal
Run in PowerShell:
```powershell
.\.venv\Scripts\activate
jupyter lab
```

### 3. Launching Classic Notebook
```powershell
.\.venv\Scripts\activate
jupyter notebook
```

### 4. Installing Additional Packages
Activate the environment and use `uv pip` or standard `pip`:
```powershell
.\.venv\Scripts\activate
pip install <package-name>
# or using uv:
uv pip install --python .venv\Scripts\python.exe <package-name>
```
