# pyspark-eda-demo
Just messing around with Pyspark =)


# Prerequisites
- `uv` package manager
- Python 3.10
- Java (Required by Pyspark)
- OpenJDK 17, if you intend to use pyspark 3.5.5, installed via `brew install openjdk@17`
- Kaggle API key in the format of `kaggle.json` in the root directory

# Setup

1. Install uv: `brew install uv`
2. Install the project dependencies by running `uv sync` in the project root directory.

# Run the notebooks
1. Run the get_dataset.ipynb notebook to download the dataset and move it to project root directory.
2. Run the unnest_and_parquet.ipynb notebook to unnest the dataset and save the data as a parquet file.
3. Run the main.ipynb notebook to clean the dataset and generate charts.
