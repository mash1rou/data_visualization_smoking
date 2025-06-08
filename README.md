# Final Project - Data Visualization (BigAnalData) - Arif N
# Smoking Trends Analysis

## Team Members

- **Name**: Raditya Maheswara  
  **NIM**: 23/516252/PA/22075  
  **University**: Universitas Gadjah Mada (UGM)  
  **GitHub Link**: https://github.com/mash1rou

- **Name**: Muhammad Fariz  
  **NIM**: 23/518174/PA/22237  
  **University**: Universitas Gadjah Mada (UGM)  
  **GitHub Link**: https://github.com/RujakBuah

- **Name**: Muhammad Shaquille Omar Ariawan  
  **NIM**: 23/511501/PA/21809  
  **University**: Universitas Gadjah Mada (UGM)  

---

## Introduction

This project explores global smoking patterns using a multi-year dataset that includes smoking percentages by gender, daily cigarette consumption, and smoker population per country.

## Dataset

Source: [CORGIS Smoking Dataset](https://corgis-edu.github.io/corgis/csv/smoking/)

## Environment Setup

This project was executed within WSL using the Debian Linux distribution

### 1. Activate WSL (Debian)

```bash
wsl -d Debian
```

### 2. Activate Python Virtual Environment

If you don't have one yet, run:
```bash
sudo apt update
sudo apt install python3-venv -y
```

Then create and activate the virtual environment:
```bash
python3 -m venv myenv
source myenv/bin/activate
```

### 3. Install Jupyter Notebook

```bash
pip install notebook
```

### 4. Install Project Dependencies

```bash
pip install pandas plotly seaborn matplotlib statsmodels ipywidgets
```

---

## Run the Project

### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

Copy the link from the terminal (e.g. `http://localhost:8888/?token=...`) and open it in your browser.

### 6. Open the Notebook File

From the Jupyter interface, open:
```
final_project_smoking_data_visualization.ipynb
```

### 7. Run All Cells

In the Jupyter toolbar:
```
Kernel → Restart & Run All
```

This ensures the entire notebook is executed in order.
