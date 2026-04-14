# Stock Market Simulator

A comprehensive Java-based stock market simulator application for learning and practicing stock trading strategies.

---

## Overview

Stock Market Simulator is an educational desktop application built entirely in Java that provides a realistic simulation of stock market trading. This project allows users to practice trading strategies, learn about market dynamics, and understand portfolio management in a risk-free environment.

---

## Features

- **Realistic Market Simulation**: Simulates real stock market behavior with live or historical data  
- **Portfolio Management**: Create, manage, and monitor investment portfolios  
- **Trading Interface**: Intuitive GUI for buying and selling stocks  
- **Performance Analytics**: Track gains, losses, and performance metrics  
- **Market Data**: Access to comprehensive stock data and market information  
- **Educational Value**: Learn stock trading fundamentals  
- **Customizable Settings**: Configure simulation parameters and trading rules  
- **Historical Backtesting**: Test strategies against historical market data  

---

## Technology Stack

- **Language**: Java (100%)  
- **Architecture**: Object-Oriented Design  
- **GUI Framework**: Swing / JavaFX  
- **Data Management**: In-memory data structures (optional DB support)  

---

## Project Structure

```bash
Stock-market-simulator/
│
├── stocks/                    # Stock-related data/files
├── lib/                       # External libraries
├── fxlib/                     # Additional libraries (possibly JavaFX)
├── .vscode/                   # VS Code settings
├── .git/                      # Git metadata
│
├── runj.bat                   # Script to run the application
├── Userinfo.txt               # Stores user-related data
│
├── User.java                  # User model
├── stockAPI.java              # API handling for stock data
├── stock.java                 # Stock model
├── graphing.java              # Graph plotting logic
├── AppUI.java                 # Main UI logic
│
├── *.class                    # Compiled Java bytecode files
│   ├── User.class
│   ├── stockAPI.class
│   ├── Stock.class
│   ├── graphing.class
│   ├── AppUI.class
│   └── etc.
│
└── .gitignore                 # Git ignore rules
```

---

## Getting Started

### Prerequisites

- Java Development Kit (JDK 11 or higher)  
- IDE (IntelliJ / Eclipse / VS Code recommended)  

---

### Installation

```bash
git clone https://github.com/WarMachine108/Stock-market-simulator.git
cd Stock-market-simulator
```

Run:

```bash
runj.bat
```

---

## Usage

### Starting the Application

- Launch via IDE or command line  
- Main window will display the simulator interface  
- Create or load a portfolio  

---

### Basic Operations

#### Creating a Portfolio

- Enter initial investment  
- Select stocks  
- Define strategy  

#### Trading Stocks

- **Buy** → Select stock + quantity  
- **Sell** → Choose stock + quantity  
- **View Holdings** → Track performance  

#### Analyzing Performance

- Portfolio value over time  
- Individual stock performance  
- Gains/losses  
- Trading history  

#### Backtesting Strategies

- Select historical time period  
- Configure parameters  
- Run simulation  
- Compare strategies  

---

## Key Components

### Models

- **Stock** → Price, volume, metadata  
- **Portfolio** → Holdings + balance  
- **Trade** → Buy/sell records  
- **MarketData** → Market info  

---

### Controllers

- **TradingEngine** → Executes trades  
- **MarketSimulator** → Simulates prices  
- **PortfolioManager** → Handles analytics  

---

### Views

- **MainWindow** → Main UI  
- **PortfolioView** → Holdings display  
- **TradingPanel** → Trade interface  
- **AnalyticsPanel** → Charts & metrics  

---

## Features in Detail

### Real-Time Market Simulation

- Dynamic price updates  
- Market volatility simulation  
- Bid-ask spread modeling  

---

### Portfolio Analytics

- Net worth tracking  
- ROI calculations  
- Gain/loss insights  
- Diversification analysis  

---

### Educational Tools

- Trading tutorials  
- Market glossary  
- Strategy guides  
- Risk management tips  

---

### Data Export

- Portfolio snapshots  
- Trading reports  
- Performance charts  
- Transaction history  

---

## Configuration
Core simulation parameters and user-specific behaviors can be customized via the `User.java` class
