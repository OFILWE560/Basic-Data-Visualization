# Basic Data Visualization - Boston Housing Dataset

> Repository: `OFILWE560/Basic-Data-Visualization`

## Description

This project is **Task 3** of the Codveda Technologies data analytics internship. It builds on the cleaned Boston housing dataset (see the [Data Cleaning & EDA repo](https://github.com/OFILWE560/Data-Cleaning_EDA)) to create basic plots and charts that visualize the distribution of, and relationships within, the data.

## Objectives

- Create bar plots, line charts, and scatter plots
- Customize plot labels, titles, and legends
- Export plots as images for reporting

## Visualizations

| Plot | What it shows |
|---|---|
| **Bar plot** | Average home value (`MEDV`) for properties on vs. off the Charles River - riverside homes average noticeably higher. |
| **Line chart** | Average home value across building-age groups (`AGE`, % of homes built before 1940) - shows how price trends as building stock gets older. |
| **Scatter plot** | Number of rooms (`RM`) vs. home value (`MEDV`), colored by Charles River proximity - confirms more rooms tracks with higher price across both groups. |

All exported images are saved to the `plots/` folder.

## Repository Structure

```
Basic-Data-Visualization/
├── cleaned_house_data.csv      # cleaned Boston housing dataset (506 rows, 14 features)
├── data_visualization.ipynb    # notebook with all plotting code
├── plots/
│   ├── bar_river_avg_price.png
│   ├── line_age_trend.png
│   └── scatter_rm_vs_medv.png
└── README.md
```

## Tools

Python · pandas · matplotlib · seaborn

## How to Run

1. Clone the repo and install dependencies:
   ```bash
   pip install pandas matplotlib seaborn
   ```
2. Open `data_visualization.ipynb` in Jupyter Notebook or JupyterLab.
3. Run all cells in order - plots will render inline and save automatically to `plots/`.

## Dataset

The dataset is the classic Boston housing dataset (506 rows, 14 features), already cleaned in a prior task: column names standardized, missing values and duplicates checked. Key columns used here:

- `MEDV` - median home value ($1000s)
- `RM` - average number of rooms
- `CHAS` — whether the property borders the Charles River (1) or not (0)
- `AGE` — % of owner-occupied units built before 1940

## Author

**Ofilwe Gabaitse**
[LinkedIn](https://www.linkedin.com/in/ofilwe-gabaitse/) · [GitHub](https://github.com/OFILWE560) · [Email](mailto:ofilwegabaitse@gmail.com)
