# 📊 Bank of Baroda Stock Exchange Analysis

## 📌 Problem Description
Stock market data is highly dynamic, and investors often struggle to analyze and interpret patterns efficiently. Traditional tabular views of stock data make it difficult to spot trends, track price fluctuations, and make informed trading decisions.  

The problem addressed here is to **visually analyze stock price movements, identify trends using moving averages, and study trading volume behavior** for better decision-making in the financial domain.

---

## 💡 Project Idea
The idea is to create an **interactive visualization dashboard** that helps investors and analysts:
- Understand stock price trends over time using candlestick charts.  
- Smoothen short-term fluctuations with **20-day Moving Average (MA20)**.  
- Analyze market participation by observing **trading volumes**.  

This project uses **Bank of Baroda’s stock data** as a case study to demonstrate the visualization.

---

## ⚙️ Implementation
1. **Data Collection**  
   - Stock data (Open, High, Low, Close, Volume) is fetched from a CSV file.

2. **Data Preprocessing**  
   - Convert dates into proper datetime format.  
   - Sort data chronologically.  
   - Calculate **20-day Moving Average (MA20)** on closing prices.  

3. **Visualization** (Using Plotly)  
   - **Candlestick chart** for stock price movements.  
   - **Line chart overlay** for the MA20 trend.  
   - **Bar chart** for trading volume.  
   - Combined in an interactive subplot for better analysis.  

4. **Output**  
   - Interactive chart exported as an **HTML file** for easy sharing and exploration.  

---

## 🛠 Tech Stack
- **Programming Language:** Python  
- **Libraries Used:**  
  - `pandas` → Data processing  
  - `plotly` → Interactive visualization  
  - `plotly.subplots` → Multi-plot integration  

---

## ✨ Features
- 📈 Interactive **candlestick chart** with zoom and hover tooltips.  
- 📉 20-day **moving average overlay** for trend detection.  
- 📊 Separate volume analysis panel.  
- 💾 Export results to **HTML** for offline viewing.  


