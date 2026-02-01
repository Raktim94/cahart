# Options Signal Pro - Ultra [Antigravity]

Professional-grade Pine Script® v6 indicator designed for Options Trading. It focuses on identifying high-probability signals by filtering out market noise and consolidation while ensuring high liquidity participation.

## 🚀 Key Features

- **False Signal Avoidance**: Uses **TTM Squeeze** logic (Bollinger Bands vs. Keltner Channels). Standard signals are hidden during consolidation phases to prevent "choppy" trades.
- **Liquidity Identification**: Only "Strong" signals are triggered when volume is significantly above average (**> 1.5x of 50-SMA**), indicating institutional interest.
- **Multi-Layer Trend Confirmation**: Aligns price action with **Triple EMAs** (9, 21, 50, 200) and **ADX** (Average Directional Index) for trend strength verification.
- **Dynamic Dashboard**: Real-time on-chart table showing trend bias, consolidation status, liquidity levels, and ADX strength.

## 📊 Signal Types

| Signal | Description | Confirmation |
|--------|-------------|--------------|
| **BUY** | Trend flip with momentum. | Price > EMA 21 + No Squeeze + ADX > 20. |
| **STRONG BUY** | High-probability entry. | Buy conditions + Price > EMA 200 + High Volume + RSI > 60. |
| **SELL** | Trend flip with momentum. | Price < EMA 21 + No Squeeze + ADX > 20. |
| **STRONG SELL** | High-probability entry. | Sell conditions + Price < EMA 200 + High Volume + RSI < 40. |

## 🛠️ Installation

1. Open **TradingView**.
2. Click on the **Pine Editor** tab at the bottom.
3. Open `options_signal_pro.pine` from this repository.
4. Copy the entire code and paste it into the editor.
5. Click **Save** and then **Add to Chart**.

## ⚙️ Customization

Users can adjust several parameters in the indicator settings:
- **EMA Lengths**: Customize the trend bias.
- **SuperTrend Factor/ATR**: Adjust sensitivity to price volatility.
- **ADX Threshold**: Change the minimum trend strength required for a signal.
- **Volume Multiplier**: Define what counts as "High Liquidity".

## 📜 License

This project is subject to the terms of the Mozilla Public License 2.0.

---
*Disclaimer: Trading involves risk. High liquidity and filters do not guarantee profit. Use this indicator as part of a broader trading strategy.*
