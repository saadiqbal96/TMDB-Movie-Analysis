# TMDb Movie Data Analysis

## Project Overview
This project analyzes a dataset containing information about 10,000 movies collected from **The Movie Database (TMDb)**. The goal is to explore trends in movie revenue, genre popularity, and other key factors like budget, vote average, and runtime. We use **Pandas** for data manipulation, **Matplotlib** and **Seaborn** for data visualization, and **NumPy** for numerical operations.

By the end of the analysis, we aim to answer questions like:
- What genres tend to generate the highest revenue?
- How does budget influence revenue?
- What are the trends in movie revenues over time?

## How to Run the Notebook
To replicate the analysis and view the results, follow these steps:

1. **Download the repository** by clicking the "Code" button on the GitHub page and choosing "Download ZIP."
2. **Open the notebook** in your preferred environment (Google Colab or Jupyter Notebook).
   - To open in **Google Colab**, use the link provided below, or upload the `.ipynb` file directly to Colab.
   - In **Jupyter Notebook**, open the `.ipynb` file from your local environment.
3. **Run all the cells** to perform the analysis and generate visualizations. The notebook is interactive and will guide you through each step.

## Required Libraries
This notebook uses the following Python libraries for data analysis and visualization:

- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical operations
- **Matplotlib**: Plotting and visualization
- **Seaborn**: Statistical data visualization

You can install them via pip if they are not already installed:

```bash
pip install pandas numpy matplotlib seaborn

Dataset

The dataset used in this analysis contains information about 10,000 movies, including features like:

Revenue

Budget

Genres

Release Date

Vote Average and Vote Count

Runtime

Director, Cast, and Production Companies

This dataset was sourced from The Movie Database (TMDb), and is adjusted for inflation in terms of revenue and budget.

Visualizations

This project includes various visualizations to explore the relationships between movie revenue and other factors, including:

Bar charts for average revenue by genre.

Heatmaps to visualize correlations between numerical variables.

Line plots showing revenue trends over time.

Conclusions and Limitations
Key Findings:

Certain genres (e.g., Action, Adventure) tend to generate higher revenues.

There is a positive correlation between movie budget and revenue.

Vote average and vote count also have a moderate influence on revenue.

Limitations:

The analysis does not take into account external factors like marketing or audience engagement, which could significantly impact revenue.

The dataset has some missing values, particularly in columns like budget and revenue, which were imputed with zeros in the analysis.

Further Research:

Future work could involve analyzing the impact of cast or director on movie revenue.

Investigating the role of marketing budgets and audience ratings could also provide deeper insights into a movie’s success.

License

This project is licensed under the MIT License
