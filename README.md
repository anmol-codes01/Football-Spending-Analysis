# Football-Spending-Analysis
Analyzing and Visualizing The Transfer Spending of Top European Football Leagues and Clubs

European Football Transfer Spending Analysis

Project Overview

This project analyzes transfer spending by football clubs in Europe's top leagues using data sourced from Kaggle. The data has been cleaned and processed using Pandas in Jupyter Notebook, and visualizations have been created using Matplotlib and Seaborn.

Data Source

The dataset was obtained from Kaggle and contains information about player transfers, including club names, transfer fees, and league details.

The data has been preprocessed and grouped by club to analyze total spending across the top five European leagues:

Premier League (England - EPL)

La Liga (Spain - ES1)

Serie A (Italy - IT1)

Bundesliga (Germany - L1)

Ligue 1 (France - FR1)

Technologies Used

Python (for data manipulation and analysis)

Pandas (for data cleaning and processing)

Jupyter Notebook (for interactive development and visualization)

Matplotlib & Seaborn (for visualizing transfer spending trends)

Git & GitHub (for version control and project management)

Project Structure

/your_project
├── README.md             # Project documentation
├── your_notebook.ipynb   # Jupyter Notebook with analysis
├── data/
│   └── spending.csv      # Transfer spending data
├── plots/
│   └── top_spending.png  # Visualizations
├── requirements.txt      # List of dependencies
└── .gitignore            # Files to exclude from GitHub

Analysis Summary

We grouped transfer spending data by club and league.

Converted transfer fees into a readable format (millions and billions).

Created bar plots to visualize the highest spending clubs in each league.

Installation & Usage

1. Clone the Repository

git clone https://github.com/yourusername/your-repository.git
cd your-repository

2. Install Dependencies

Ensure you have Python installed, then run:

pip install -r requirements.txt

3. Run the Jupyter Notebook

Launch Jupyter Notebook and open the provided .ipynb file:

jupyter notebook

Notes

If the dataset is too large, it may not be included in this repository. You can download it from Kaggle and place it in the data/ folder.

If you modify the notebook, remember to re-run the cells and save your changes before committing to GitHub.
