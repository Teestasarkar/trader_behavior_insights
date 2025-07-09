# trader_behavior_insights
Sentiment vs Trader Behavior Analysis
This project explores how trader behavior shifts in response to changing market sentiment — specifically during periods of Fear and Greed in the Bitcoin ecosystem.

We analyzed two datasets:

Bitcoin Fear & Greed Index: A daily sentiment label indicating the market's emotional state.

Hyperliquid Trader Data: Real-world trading records including size, direction, and profitability.

 What We Did
Cleaned and prepared both datasets for analysis

Aligned trades with sentiment data based on matching dates

Simulated realistic timestamps in trader data (due to corrupted original values)

Merged both datasets to tag every trade with the corresponding market sentiment

Ran four key analyses:

📈 Profitability during Fear vs Greed

📊 Volume of trades and total USD moved

🔀 Long vs Short trade direction comparisons

⚠️ Risk exposure using profit volatility
ds_teesta_sarkar/
├── notebook_1.ipynb         # Main analysis notebook
├── csv_files/               # Cleaned input data
├── outputs/                 # Plots and visuals
├── ds_report.pdf            # Summary of analysis and insights
└── README.md                # You're reading it :)



