# Analysing Pharmaceutical Sales Data

An exploratory data analysis project using **Python**, **Pandas**, and **Matplotlib** based on the [Analysing Pharmaceutical Sales Data](https://roadmap.sh/) project on [roadmap.sh](https://roadmap.sh/roadmaps).

## Dataset

This project uses `salesdaily.csv` from the linked [Kaggle project](https://www.kaggle.com/milanzdravkovic/pharma-sales-data). Because raw dataset files are kept out of the repository, download `salesdaily.csv` from Kaggle and upload it to your Google Colab environment (or place it inside a local `data/` folder) before running the notebook.

## Questions Answered

1. **Total sales by ATC category:** Cumulative sales quantities across drug categories (ATC codes).
2. **Top individual drug brands:** Drugs with the highest overall sales volume.
3. **Key time periods:** Top three drugs by sales in **January 2015**, **July 2016**, and **September 2017**.
4. **Most frequent drug in 2017:** The drug recording non-zero sales on the highest number of days/entries in 2017.
5. **Highest average daily sales by category:** Drug category with the highest mean daily sales.
6. **Seasonal trend for respiratory drugs (`R03`):** Monthly sales patterns across years to check whether `R03` sales peak in specific months.

## Tech Stack

- **Python 3**
- **Pandas** (data loading, date parsing, filtering, grouping, and aggregation)
- **Matplotlib** (bar and line visualizations)
- **Google Colab** (notebook execution)

## How to Run

1. Open `pharma_sales_analysis.ipynb` in [Google Colab](https://colab.research.google.com/).
2. Download `salesdaily.csv` from [Kaggle](https://www.kaggle.com/milanzdravkovic/pharma-sales-data) and upload it to your Colab session.
3. Run all cells from top to bottom (**Runtime > Run all**) to view tables and charts.
