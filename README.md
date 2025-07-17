# Live Crypto Tracker

## Dashboard
Please click here to view the **Live Crypto Tracker** in **Power BI**:
[Crypto Dashboard](https://app.fabric.microsoft.com/view?r=eyJrIjoiMTRmMDE0MmMtNGVkNi00ZWQ2LTljY2EtNjViMmVmZTBmMjMzIiwidCI6IjA0NjZlNDc4LWQ5MjMtNDliOS1hZGYzLWRiYzI0MTVkOGEwZiJ9).

## Purpose
This dashboard has been developed for educational purposes, demonstrating data engineering capabilities using Microsoft Fabric and data visualisation skills with Power BI.

## Data Source
This dashboard runs on near real-time cryptocurrency data. Every hour, a Python script in a Microsoft Fabric Notebook pulls data from the Binance REST API and stores it in a Lakehouse, making it ready for analysis.

## Visualisation Design Features

- **Candlestick Chart**:  Created using Power BI’s native visuals (Clustered Line & Column chart + Error Bar), essential for understanding price fluctuations.

- **Dynamic Timeframes**: Toggle across various time intervals to explore crypto performance over different time periods (i.e. 1H, 4H, 1D, 1W, YTD, 1Y, MAX).
  
- **Light/Dark Mode**: Switch between light and dark modes for a customized viewing experience.
  
- **Animated Text**: Using Power BI’s native SVG capabilities, I added animated text to mimic a crypto ticker common in trading platforms. 

- **Sleek Interface**: Professional, user-friendly design for clear insights.
