## Overview

Smartswap is an intranet-based project designed to take automated positions in cryptocurrency markets using strategies developed through quantitative backtesting, interacting with centralized platforms such as Binance. The platform facilitates automated trading through a trading algorithm based on quantitative market analysis. You can create, import, and simulate your own strategies, as well as run multiple automated trading strategies using a web interface and fast APIs.

> [!IMPORTANT]  
> **See the main repository** : [smartswap](https://github.com/smartswap-org/smartswap)

### How it works

- Use **simonpotel/QTSBE** and **smartswap-org/webapp** to create and visualize your trading strategy, including metrics, cumulative returns, and positions across multiple pairs. Utilize the lab for faster analysis and charts for detailed insights.

- Import your strategy into **QTB** in simulation mode, where it will automatically manage positions on CEX/DEX using **simonpotel/CEXcryptoLib** and **simonpotel/DEXcryptoLib**. Data will be recorded in **smartswap** databases for real-time visualization.

- If effective, switch to live trading to start generating profits.

- **QTB** includes Discord integration for faster position monitoring and enhanced configurations.

- The platform features multiple logging levels and security measures, including a phone call system for critical logs.

- The infrastructure is designed for efficient strategy creation, upload, visualization, and automated monitoring.

  
---

## Details

### Key Projects Integrated

- [**QTSBE (Quantitative Trading Strategy Backtesting Environment)**](https://github.com/simonpotel/QTSBE): A platform for creating and testing financial strategies, featuring data visualization and a real-time API for analysis.

- [**CEXcryptoLib**](https://github.com/simonpotel/CEXcryptoLib) & [**DEXcryptoLib**](https://github.com/simonpotel/DEXcryptoLib): Libraries for executing orders and broadcasting transactions on markets.

### Internal Modules

- [**webapp**](https://github.com/smartswap-org/webapp): A web interface for portfolio management, order tracking, and cryptocurrency price monitoring (DEX/CEX). It includes features like Charts for enhanced strategy analysis and Lab for obtaining stats on over 50 cryptocurrencies in just 5 seconds.

- [**simulator**](https://github.com/smartswap-org/simulator): A real-time strategy simulation tool for testing bag management and position strategies. It simulates buy/sell signals across multiple pairs and provides comprehensive backtest statistics.

- [**qtb**](https://github.com/smartswap-org/qtb): The central module that retrieves strategies, signals, and executes transactions. It can operate in simulation mode for live statistics, which is not available in the simulator. The **qtbapp** module integrates with Discord for faster admin control, including phone call management and configurations.

- [**databases**](https://github.com/smartswap-org/databases): Manages the creation and updating of the smartswap database, handling user logins for the webapp and position management for QTB configurations.

## Related Technologies

### Databases
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

### Frontend
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Chart.js](https://img.shields.io/badge/chart.js-F5788D.svg?style=for-the-badge&logo=chart.js&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)

### Backend
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)

### Programming Languages
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

### Data Science Libraries
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)

### Communication
![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=for-the-badge&logo=Twilio&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white)

### Version Control
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

### Exchanges
![Binance](https://img.shields.io/badge/Binance-FCD535?style=for-the-badge&logo=binance&logoColor=white)

## Actual Tested OS

![Raspberry Pi](https://img.shields.io/badge/-RaspberryPi-C51A4A?style=for-the-badge&logo=Raspberry-Pi)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Windows 11](https://img.shields.io/badge/Windows%2011-%230079d5.svg?style=for-the-badge&logo=Windows%2011&logoColor=white)
![macOS](https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=macos&logoColor=F0F0F0)

> [!CAUTION]
> **Why are not all repositories public?**  
> Some parts of the project are private for security and confidentiality reasons.

## Usage and License

All projects are licensed under the Smartswap copyright (© Simon Potel). If you use the project, please do so for personal, non-commercial purposes only.
