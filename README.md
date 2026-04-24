# sp500-long-term-return-analysis
This project conducts a Python-based analysis of long-term returns using S&amp;P 500 historical data from 1871 to 2026, to verify the effects of holding periods, valuations, and inflation on real investment returns.
# S&P 500 Long-Term Return Analysis (1871–2026)

Do stocks always beat inflation in the long run? This project uses 155 years of S&P 500 data to find out.

**ACC102 Mini Assignment · Track 2 · JingLang Xu 2470949**

## What This Project Does

- Analyses rolling real (inflation-adjusted) returns over 1, 5, 10, 20, and 30-year holding periods
- Examines how starting valuation (PE10 / CAPE ratio) affects future 10-year returns
- Produces a sector scorecard with actionable insights for retail investors

## Dataset

Robert Shiller's S&P 500 dataset (monthly, 1871–2026), cloned from [github.com/datasets/s-and-p-500](https://github.com/datasets/s-and-p-500) (PDDL license).

The notebook automatically clones the data via `git clone` — no manual download needed.

## How to Run

```bash
# 1. Clone this repo
git clone https://github.com/YOUR_USERNAME/sp500-longterm-analysis.git
cd sp500-longterm-analysis

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn

# 3. Open and run the notebook
jupyter notebook sp500_longterm_analysis.ipynb
```

Run all cells top to bottom. The first code cell will clone the dataset automatically.

## Requirements

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- git (for cloning the dataset)

## Project Structure

```
├── sp500_longterm_analysis.ipynb   # Main analysis notebook
├── reflection_report.md            # 500-800 word reflection
├── README.md                       # This file
└── data/                           # Created automatically on first run
    └── data.csv
```

## License

This project is for educational purposes (ACC102 coursework). The underlying dataset is released under the [Public Domain Dedication and License (PDDL)](https://opendatacommons.org/licenses/pddl/).
