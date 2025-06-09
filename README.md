🏈 NFL Player Contract Analysis

This project analyzes the contract values of NFL players to better understand how teams allocate their salary cap, identify patterns in spending, and surface potential inefficiencies in player compensation. It scrapes data from Spotrac and processes it into a clean and structured format for further exploration.

📊 Project Overview

The NFL operates under a hard salary cap, meaning each team must carefully manage its player contracts. Yet, teams often overpay or underpay players, leading to significant differences in team performance and cap health. This project explores:
	•	The structure of NFL player contracts
	•	The timing and duration of contracts
	•	Trends in player earnings over the years
	•	Cleaning and transforming real-world web data

🎯 Goal

To determine whether certain positions or player profiles are consistently overpaid or underpaid relative to others—and whether teams with more efficient contract structures tend to perform better.

💡 Hypothesis

We initially hypothesize that:

	•	Skilled positions (like QB and WR) tend to be overpaid relative to their on-field impact.
	•	Teams that invest more in younger, high-upside players tend to have healthier cap structures.
	•	There are inefficiencies where veteran players are overpaid based on past performance rather than expected future contribution.

📊 Key Discoveries

After processing the data, we observe:
/n
	•	Many multi-year contracts backload payments, leading to large cap hits late in the deal.
	•	Positions like quarterback and edge rusher dominate the top contract values, but does not always align with win percentage or team success.
	•	Some teams consistently structure contracts with lower guaranteed money and high bonuses—possibly as a hedge against performance drop-offs.
	•	First-year salary vs. average annual value (AAV) varies widely which we go into further depth

🔍 Features

	•	✅ Web Scraping: Extracts raw contract tables from Spotrac using pandas.read_html
	•	✅ Regex Parsing: Cleans up messy player data using regex to extract names and contract years
	•	✅ DataFrame Processing: Converts salaries to numeric values and creates new features for analysis
	•	✅ Error Handling: Skips bad records gracefully without crashing
	•	✅ Exploratory Analysis Ready: Cleaned data ready for plotting, aggregation, and model training

⚙️ Technologies Used

	•	Python 3
	•	Jupyter Notebook
	•	pandas, numpy
	•	Regular expressions (re)

⸻

🚀 Future Work

	•	Add team-level aggregation to compare contract strategies
	•	Integrate performance stats (e.g., PFF grades, win shares)
	•	Build a predictive model to flag potential overvalued contracts

 
