# clean-csv-for-notion
A simple bit of code to clean Google Meet Attendance csv for Notion import

# What this code does
1. csv files are renamed to include the meeting name and time. eg. "My meeting_2022-03-01.csv"
1. Initial comments in the csv from Google Meet Attendance plugin are removed

# Requirements
1. python 3, pandas, jupyter

If you have Anaconda Python, any environment with Pandas should work fine. Or try the following:

```bash
# Create a new env called csv_clean (only do this once)
conda create -n csv_clean pandas jupyter python=3

# Activate the conda environment (run as required)
conda activate csv_clean

# Open Jupyter to run this notebook (optional, you could run via VSCode or your preferred method)
jupyter notebook
```

# How to use
1. Clone this code.
1. Download csv files from Google Meet Attendance plugin and place them in a folder called `data`
1. Create a folder called `output`
1. Run the clean_csv.ipynb script (I ran via Jupyter)
1. Your new csvs will be in the `output` folder. 

