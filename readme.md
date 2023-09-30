# Music Charts Analysis with PySpark and Pandas

This repository contains Python code for analyzing music charts data using PySpark and Pandas. The code covers various aspects of data analysis, including data loading, data cleaning, and visualization. The primary dataset used in this analysis is a CSV file containing music charts data.

## Table of Contents

1. [Introduction](#introduction)
2. [Dependencies](#dependencies)
3. [Usage](#usage)
4. [Code Overview](#code-overview)
5. [Results](#results)
6. [Contributing](#contributing)
7. [License](#license)

## Introduction

This project aims to analyze music charts data to gain insights into the popularity of songs and artists over time. It uses both PySpark and Pandas to perform data manipulation and visualization tasks. The analysis includes visualizing word counts of regions, computing total streams by region, and examining specific artist's performance on the charts.

## Dependencies

Before running the code, ensure you have the following dependencies installed:

- Python 3.x
- PySpark
- Pandas
- NumPy
- WordCloud
- Seaborn
- Matplotlib

You can install the required Python packages using pip:

```bash
pip install pyspark pandas numpy wordcloud seaborn matplotlib
```

## Usage

1. Clone or download this repository to your local machine.

2. Open a terminal and navigate to the project directory.

3. Run the Python script:

```bash
python your_script_name.py
```

Replace `your_script_name.py` with the name of the script containing the code you provided.

## Code Overview

- **Data Loading**: The code starts by loading the music charts data from a CSV file using Pandas and Spark.

- **Data Preprocessing**: It performs data preprocessing tasks such as converting data types and creating additional columns for analysis.

- **Visualization**: The code includes various visualization tasks using libraries like Seaborn and WordCloud. It generates visualizations of word counts for regions and a pie chart showing the percentage of streams by region.

- **SQL Queries with Spark**: The code demonstrates how to run SQL queries on the loaded data using PySpark's SQL API. It includes example queries to extract specific information from the dataset.

## Results

The code provides insights into the music charts data, including word counts for regions, the percentage of streams by region, and specific artist performance on the charts.

## Contributing

Contributions to this project are welcome! If you have suggestions or improvements, please feel free to submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.