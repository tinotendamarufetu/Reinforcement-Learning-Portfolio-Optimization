# Reinforcement-Learning-Portfolio-Optimization Trading Bot 📈🤖

This project implements a Deep Reinforcement Learning (DRL) agent using **PPO-LSTM** to optimize a portfolio of **ETFs**.  
It uses historical stock data to learn dynamic trading strategies, aiming to maximize returns while minimizing risk.

---

## 🚀 Project Overview

- **Framework:** PPO-LSTM (Proximal Policy Optimization with Recurrent Neural Network)
- **Market Data:** 50+ ETFs historical price data (Yahoo Finance)
- **Environment:** Custom OpenAI Gym Trading Environment
- **Evaluation Metrics:**
  - Portfolio Final Value
  - Profit / Returns (%)
  - Sharpe Ratio
  - Maximum Drawdown
  - Total Number of Trades

---

## 📊 Visualizations

- Portfolio Value Over Time
- Smoothed Rewards Over Time
- Daily Returns
- Trade Penalty Costs
- Portfolio vs. Benchmark Comparison
- Top 5 Performing Stocks (by cumulative profit)
- Drawdown Plot (% from peak)
- Rolling Sharpe Ratio (volatility-adjusted returns)

![image](https://github.com/user-attachments/assets/dbbd120b-12c6-4e58-8698-2fa330addcbf)


---

## 🛠️ Project Structure

RL-Trading-Bot/
├── data/
    ├── stock_data.csv
├── models/
    ├── ppo_model.zip
├── trading_logs/
    ├── trading_history.csv
├── environment.py
├── train.py
├── evaluate.py
├── requirements.txt
├── README.md


