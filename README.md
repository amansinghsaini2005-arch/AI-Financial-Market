
🧠 AI Financial Market – Data Analysis Using Python

This project explores AI-driven financial market trends using data analysis techniques in Python. The dataset simulates realistic daily R&D spending, AI revenue, growth percentages, stock impacts, and key AI events for major tech companies — OpenAI, Google, and Meta — from 2015 to 2024.

It demonstrates the use of Pandas, Matplotlib, and Seaborn for exploratory data analysis, visualization, and correlation insights — all tailored to understand the financial dynamics of AI investments.

📊 Project Overview

Goal:
Analyze how R&D spending influences AI revenue growth and stock performance over time, and visualize event-driven stock impacts (e.g., GPT releases, TensorFlow launch).

Key Analysis Steps:

Import and clean raw CSV data.

Explore dataset structure (size, columns, data types).

Analyze R&D spending and AI revenue across companies.

Visualize spending vs. revenue trends.

Examine daily and yearly stock impacts.

Investigate correlations between financial indicators.

Study effects of major AI events (e.g., GPT-4 release, TensorFlow open-source).

🧩 Dataset Information
Column Name	Description
Date	Daily observation date (2015–2024)
Company	Company name (OpenAI, Google, Meta)
R&D_Spending_USD_Mn	Daily R&D spending (in million USD)
AI_Revenue_USD_Mn	AI-generated revenue (in million USD)
AI_Revenue_Growth_%	AI revenue percentage growth
Event	Major AI release or market event
Stock_Impact_%	Daily stock impact percentage

Dataset Size: 10,959 rows × 7 columns

🧮 Tools and Libraries Used

Python 3.10+

Pandas – data cleaning and aggregation

NumPy – numerical computations

Matplotlib – data visualization

Seaborn – advanced statistical plotting

📈 Key Insights and Visuals
1. R&D Spending by Company

Bar chart showing total R&D investment across companies (in USD Bn).

2. AI Revenue by Company

Comparative visualization of total AI revenues (Google > Meta > OpenAI).

3. Spending vs. Revenue Comparison

Side-by-side charts showing correlation between investment and income.

4. Stock Impact Analysis

Line plots tracking stock performance over time for each company.

5. Correlation Heatmap

Visual correlation between R&D, revenue, growth %, and stock impact.

6. Event Impact Studies

Special analysis of stock performance before and after:

TensorFlow release (Google)

GPT-4 launch (OpenAI)

AI policy updates and partnerships (Meta)

🧠 Insights Summary
Company	Avg R&D Spending (Mn USD)	Avg Stock Impact (%)	Key Observations
OpenAI	7.53	Highest (191%)	Rapid stock growth linked to GPT model launches
Google	111.86	64.5	Consistent growth through AI product releases
Meta	72.91	101.4	Steady improvement post AI ethics and video AI initiatives
🧩 Yearly Trend Highlights

R&D spending and AI revenue have both grown exponentially from 2015 to 2024.

🧾 Example Visual Output

Bar Charts: R&D vs AI Revenue

Line Charts: Year-wise Stock Impact

Heatmaps: Feature correlation

Scatter Plots: AI Revenue Growth vs Spending

🌍 Business Application

Helps investors and analysts understand the financial impact of AI R&D.

Identifies which AI events most affect stock performance.

Supports data-driven decisions in AI investment strategies.

Stock impact spikes strongly correlate with major AI releases.

Strong positive correlation between R&D spending and revenue growth (~0.89).
