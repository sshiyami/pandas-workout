# Pandas Workout — Solutions

My solutions to the exercises from **"Pandas Workout"** by Reuven Lerner (Manning, 2024),
including the extra "Beyond the exercise" tasks.

Goal: build fluent, idiomatic pandas skills on real-world datasets
(data cleaning, grouping, joining, time series, text data).

## Tech stack
Python 3.12 · pandas 2.x · NumPy · Matplotlib · Jupyter

## Progress

| Chapter | Topic | Status |
|---|---|---|
| 1 | Series | 🔄 |
| 2 | Data frames | ⬜ |
| 3 | Importing and exporting data | ⬜ |
| 4 | Indexes | ⬜ |
| 5 | Cleaning data | ⬜ |
| 6 | Grouping, joining, and sorting | ⬜ |
| 7 | Advanced groupby, apply, and agg | ⬜ |
| 8 | Midway project | ⬜ |
| 9 | Strings | ⬜ |
| 10 | Dates and times | ⬜ |
| 11 | Visualization | ⬜ |
| 12 | Performance | ⬜ |
| 13 | Final project | ⬜ |

✅ done · 🔄 in progress · ⬜ not started

## Repository structure

    ch01_series/
        ex01_<name>.ipynb      # one notebook per exercise
    ch02_dataframes/
    ...
    data/                      # datasets are not stored in git, see data/README.md
    environment.yml

## How to run

    conda env create -f environment.yml
    conda activate ml
    jupyter notebook

Datasets: download them as described in [data/README.md](data/README.md)
and put them into the `data/` folder.

## Notes
Each notebook contains the task in my own words, the solution,
and short comments on the approach.