📈 Live Bank Marketing Analytics Dashboard (Streamlit)
✨ Project Overview
Welcome to the Live Bank Marketing Analytics Dashboard! This project is a powerful, interactive web application built entirely in Python using Streamlit. It transforms static bank marketing data into a dynamic, "real-time" dashboard, allowing stakeholders to monitor key performance indicators (KPIs) and data distributions with zero latency.

This dashboard is designed to simulate a live data feed, making it a perfect showcase for Streamlit's ability to handle and visualize frequently updating data and is powered by the popular Plotly library for rich, interactive charts.

🚀 Features
Real-Time Data Simulation: The core script runs in a loop, continuously updating the underlying data (age and balance) with random factors to simulate fresh incoming data.

Key Performance Indicators (KPIs): Three top-level metrics dynamically track crucial figures:

⏳ Age: Average age of targeted customers.

💍 Married Count: The total count of married individuals in the targeted group.

💲 A/C Balance: The average account balance.

Interactive Filters: Use the top-level st.selectbox to filter the entire dashboard instantly by Job Type.

Dynamic Visualizations: Features two interactive Plotly charts that update with every simulated data refresh:

A Density Heatmap visualizing the relationship between updated Age and Marital Status.

A Histogram showing the distribution of the updated Age data.

Detailed Data View: A live-updating st.dataframe displays the raw, filtered, and processed data table.

🛠️ Technology Stack
Technology	Purpose
Python	Core application language.
Streamlit	Framework for building the interactive web dashboard.
Pandas	Data loading and manipulation (DataFrames).
NumPy	Statistical and numerical operations (for simulating new data).
Plotly Express	Creating beautiful, interactive data visualizations.
⚙️ How to Run Locally
Follow these steps to get a copy of the project running on your local machine.

Prerequisites

You need Python (3.9+) and pip installed.

Clone the repository:

Bash
git clone https://github.com/YourUsername/YourRepoName.git
cd YourRepoName
Create and activate a virtual environment (recommended):

Bash
python -m venv .venv
source .venv/bin/activate  # On macOS/Linux
.venv\Scripts\activate     # On Windows
Install dependencies:

Bash
pip install streamlit pandas numpy plotly
Run the Streamlit app:

Bash
streamlit run main.py
Your web browser will automatically open to http://localhost:8501, and the dashboard will begin its dynamic update cycle!
