# Smartswap 

## Overview

Smartswap is an intranet-based project designed to take automated positions in cryptocurrency markets using strategies developed through quantitative backtesting, interacting with centralized platforms such as Binance. The platform facilitates automated trading through a trading algorithm based on quantitative market analysis. You can create, import, and simulate your own strategies, as well as run multiple automated trading strategies using a web interface and fast APIs.

> [!IMPORTANT]  
> **See the main repository**: [smartswap](https://github.com/smartswap-org/smartswap)

### How it works

- Use **QTSBE** and **webapp** to create and visualize your trading strategy, including metrics, cumulative returns, and positions across multiple pairs. Utilize the lab for faster analysis and charts for detailed insights.

- Import your strategy into **QTB** in simulation mode, where it will automatically manage positions on CEX/DEX using **CEXcryptoLib** and **DEXcryptoLib**. Data will be recorded in **Nexus** databases for real-time visualization.

- If effective, switch to live trading to start generating profits.

- The platform features multiple logging levels and security measures, including a phone call system for critical logs.

- The infrastructure is designed for efficient strategy creation, upload, visualization, and automated monitoring.

---

## Tech Stack

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white)

### Backend
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

### Data & Analysis
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)

### Databases
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black)

### Infrastructure & Tools
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

### Communication
![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=for-the-badge&logo=Twilio&logoColor=white)

### Design
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)

### Exchanges
![Binance](https://img.shields.io/badge/Binance-FCD535?style=for-the-badge&logo=binance&logoColor=white)

---

## Services

### Nexus
Central backend API managing core infrastructure:
- Database connections (MySQL & ClickHouse)
- Log ingestion and management
- Position tracking 
- Client and wallet management
- Trading execution coordination

### QTB (Quant Trading Bot)
Main execution engine for the platform:
- Real-time trading automation
- Strategy execution on cryptocurrency exchanges
- Position management and monitoring

### QTSBE (Quantitative Trading Strategy Backtesting Environment)
Python-based algorithmic trading analysis api toolkit:
- Strategy backtesting 
- Technical analysis & indicators
- Performance metrics & statistics
- Market data fetching 

---

## Key External Libraries

- [**CEXcryptoLib**](https://github.com/simonpotel/CEXcryptoLib): Library for executing orders on centralized exchanges

- [**DEXcryptoLib**](https://github.com/simonpotel/DEXcryptoLib): Library for broadcasting transactions on decentralized exchanges

---

## Usage and License

All projects are licensed under the Smartswap copyright (© Simon Potel). If you use the project, please do so for personal, non-commercial purposes only.

> [!CAUTION]
> **Why are not all repositories public?**  
> Some parts of the project are private for security and confidentiality reasons.

---

<div align="center">
  
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

</div>

