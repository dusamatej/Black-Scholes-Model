# Black-Scholes-Model
Real-Time Option Pricing Calculator
Using Black-Scholes Model, Historical Volatility, and Live Risk-Free Rate

🛠 Project Overview
This project builds a simple yet powerful Python application that calculates the theoretical price of call and put options using the Black-Scholes model.

The script dynamically:

Fetches the current stock price from Yahoo Finance.

Calculates the historical volatility of the stock based on recent price movements.

Retrieves the risk-free interest rate by automatically matching U.S. Treasury bond yields to the user's expected option expiration time.

Computes the theoretical call and put prices.

Visualizes the call option payoff diagram including the strike price and break-even point.

✅ Designed for educational, analysis, and lightweight financial modeling purposes.

📋 Features
📊 Historical Volatility Estimation: Calculates volatility from past stock price returns.

💵 Risk-Free Rate Automation: Fetches up-to-date U.S. Treasury yields based on selected expiration.

⚡ Black-Scholes Model Implementation: Computes theoretical call and put prices.

🧮 Visualization: Displays the call option payoff curve with strike and break-even points clearly marked.

🛡️ Failsafe User Inputs: If live data fetching fails, users can manually input missing values.

🧩 How It Works
User enters the stock symbol.

User enters the number of years until option expiration.

Program automatically:

Pulls live stock price.

Estimates historical volatility.

Pulls the matching Treasury yield as the risk-free rate.

User reviews the calculated theoretical call and put prices.
