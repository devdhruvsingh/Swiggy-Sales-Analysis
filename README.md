# Swiggy Sales Analysis Project 📊

A comprehensive data analysis project using Python to uncover sales trends, consumer behavior, and geographical performance for orders on the Swiggy platform.

## 📌 Project Overview
This project transforms raw Swiggy order data into actionable business insights. By performing time-series analysis and categorical grouping, I identified key growth periods, top-performing food categories, and high-revenue cities.

## 🛠️ Tech Stack
- **Language:** Python 3.13
- **Libraries:** Pandas (Data Manipulation), Matplotlib & Seaborn (Data Visualization)
- **Tools:** VS Code, Jupyter Notebooks, Git/GitHub
- **Environment:** Virtual Environment (`.venv`)

## 🚀 Key Insights & Features
- **Time-Series Analysis:** Visualized Monthly, Quarterly, and Daily sales trends to identify peak ordering periods.
- **Categorical Breakdown:** Analyzed the Top 10 food categories to understand consumer preferences.
- **Geographical Insights:** Identified the Top 5 cities by revenue and performed a city-wise breakdown of sales.
- **Premium Product Tracking:** Discovered the Top 10 most expensive dishes ordered across different cities.
- **Data Cleaning:** Implemented robust error handling to manage messy data, including `to_datetime` conversion and handling bad lines.

## 📁 Repository Structure
text
├── analysis.ipynb        # Main Jupyter Notebook with all code and visualizations
├── swiggy_data.xlsx      # Raw dataset (Excel format)
├── requirements.txt      # List of dependencies for reproducibility
├── .gitignore            # Files excluded from version control (like .venv)
└── README.md             # Project documentation

⚙️ How to Run Locally
Clone the repository:

Bash
git clone <copy the link of this repository>
cd swiggy-analysis
Set up the environment:

Bash
python3 -m venv .venv
source .venv/bin/activate  # On Windows use: .venv\Scripts\activate
Install dependencies:

Bash
pip install -r requirements.txt
Launch the analysis:
Open analysis.ipynb in VS Code and run all cells.

📊 Visualizations Included
Monthly Revenue Growth (Line Chart)

Daily Sales Fluctuations (Detailed Trend)

Top 10 Food Categories by Revenue (Seaborn Bar Chart)

Top 5 Cities by Revenue Contribution

Most Expensive Dishes City-wise

Author: Dhruv Singh
