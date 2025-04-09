# Golden-Swing-
Golden Swing pattern automated with pinescript on trading view and integrated pine connector for autmoated trades

# Golden Swing EA

An executable Expert Advisor (EA) implementing a custom strategy called the **Golden Swing (GS)**.

## 📌 Overview

The Golden Swing is a reversal pattern strategy designed for use on the **H1** or **M30** timeframes, particularly after a clean trend. This EA automates the GS strategy, previously traded manually on TradingView using a proprietary system of “dots.”

These dots help highlight swing high/low points and are used to draw trendlines, from which tradeable patterns emerge.

While applicable to any TradingView instrument — including currencies, stocks, bonds, and futures — our primary focus is currently on **forex markets**.

---

## 📊 Traded Performance

Manual trading of this strategy has been ongoing since **April 2022**, with the following statistics (as of **February 6, 2025**):

- ✅ **Win Rate**: 31.03%  
- ➖ **Break-even Rate**: 37.4%  
- ❌ **Loss Rate**: 32.5%  
- 📈 **Return on Risk**: 3:1

Our aim is to fully **automate** this pattern to improve consistency and efficiency.

---

## 🔍 What is the Golden Swing?

The Golden Swing was created to avoid **stop-loss hunting** by large institutions. It serves as an **early signal** of potential reversals within a trend.

### 🧩 Key Components

1. **Impulse Move**  
   - The setup begins with a strong move in one direction (up or down).
   - This move defines the foundation of the GS pattern.

2. **Retracement**  
   - A pullback follows the impulse leg.
   - The retracement must not exceed **38.2%** of the impulse move (some discretion: “Victor says half”).
   - **Note**: Wicks below 38.2% are acceptable, but the **candle body must not close** below this level.

3. **Second Leg**  
   - A second leg forms that mirrors the impulse leg in height and width.
   - This symmetry provides confirmation and enhances the setup's validity.

4. **Additional Confluence** *(details can be added here if needed)*

---

## 🚫 Invalid Setups

- If there are **only two dots**, the setup is not valid.

---

## ⚙️ Future Plans

- Full EA automation of Golden Swing pattern  
- Integration with MetaTrader or other trading platforms  
- Backtesting and optimization across multiple instruments and timeframes

---

## 📄 Disclaimer

This repository is intended for educational and informational purposes. Trading carries risk, and past performance does not guarantee future results.

---

## 📬 Contact

For inquiries, collaborations, or support, feel free to open an issue or reach out directly.

