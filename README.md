# Assignment1_Volkova_16897137
Model-Based Decision Making

This project analyses mentions between selected Pro-Kremlin and Anti-Kremlin Telegram channels from **24 February to 24 May 2022**.

The analysis includes:
- Empirical network analysis
- ER, WS and BA benchmark models
- Node centrality measures
- Network robustness analysis

## Dataset

Based on Bawa et al. (2025).

Original dataset: [Figshare](https://doi.org/10.6084/m9.figshare.28785449)

## How to obtain the data

The raw data are not included in this repository because of their size (about 4.5 GB). To reproduce the analysis:

1. Download the dataset from Figshare: https://figshare.com/articles/dataset/Pro-Kremlin_and_Anti-Kremlin_Telegram_Dataset_during_Russia-Ukraine_Conflict_/28785449
   (the same record is linked above via its DOI).
2. Unzip the archive and place the files in the project folder so that the structure is:
Place the files in the project folder: `anti_kremlin_dataset/` (anti_kremlin1.csv ... anti_kremlin12.csv), `pro_kremlin_dataset/`, `anti_kremlin_channel_list.csv` and `pro_kremlin_channels_list.csv` next to `analysis.ipynb`.


3. Open `analysis.ipynb` and run all cells from top to bottom. The first run reads all CSV files and can take several minutes; the results are then cached in a folder named after the study window, so later runs are faster.

## Files

- `analysis.ipynb` – code
- `Assignment1_Volkova_16897137.pdf` – written report

## Requirements

Python 3, pandas, NumPy, NetworkX, Matplotlib and SciPy.

Install dependencies:

```bash
pip install pandas numpy networkx matplotlib scipy
```

## Reference

Bawa et al. (2025). *Telegram as a Battlefield: Kremlin-related Communications during the Russia–Ukraine Conflict.*

[https://doi.org/10.1609/icwsm.v19i1.35939](https://doi.org/10.1609/icwsm.v19i1.35939)
