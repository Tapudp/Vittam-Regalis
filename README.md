# Vittam-Regalis 👑

*Royal Wealth Management for Modern Traders*

A comprehensive Zerodha Stock Trading P&L Calculator that provides accurate profit/loss calculations with all applicable charges and taxes for the Indian stock market.

## 🏛️ About

**Vittam-Regalis** (*Vittam* - Sanskrit: Wealth/Property + *Regalis* - Latin: Royal) is a sophisticated trading calculator designed to help Indian stock market traders calculate their exact profit/loss with precision fit for royalty. Built specifically for Zerodha brokerage charges and Indian tax regulations.

## ✨ Features

### 📊 Comprehensive Calculations
- **Multiple Transaction Support**: Add unlimited buy/sell transactions
- **Real-time P&L Calculation**: Instant profit/loss computation
- **Complete Charge Breakdown**: Detailed view of all applicable charges
- **Tax Optimization**: Accurate STCG tax calculation on net profits

### 🎨 Royal User Experience
- **Elegant Two-Column Layout**: Transactions on left, results on right
- **Visual Profit/Loss Indicators**: Green for profits, red for losses
- **Responsive Design**: Works seamlessly on desktop and mobile
- **Color-Coded Transaction History**: Individual P&L tracking

### 💰 Complete Charge Structure

#### Trading Charges
| Charge Type | Rate | Description |
|-------------|------|-------------|
| **Brokerage** | ₹0 (Delivery) / ₹20 per order (Intraday) | FREE for delivery, ₹40 total for intraday (buy+sell) |
| **Exchange Transaction Charges** | NSE: 0.00297% / BSE: 0.00375% | Of turnover |
| **Clearing Charges** | ₹0.002 per share | Capped at 0.01% of turnover |
| **IGST** | 18% | On (brokerage + transaction charges) |
| **Securities Transaction Tax** | Delivery: 0.1% / Intraday: 0.025% | On buy & sell / sell only |
| **SEBI Turnover Fees** | ₹10 per crore | 0.000001% of turnover |
| **Stamp Duty** | 0.015% | On buy side (capped at ₹1500) |

#### Tax Calculations
- **Short-Term Capital Gains Tax (STCG)**: 20% + 4% cess = **20.8%** on net profits
- Applied only on profits after deducting all trading charges

## 🚀 Quick Start

### Option 1: Direct Use
1. Download or clone the repository
2. Open `zerodha-pnl-calculator.html` in any web browser
3. Start adding your transactions!

### Option 2: GitHub Pages
Visit the live calculator: [Vittam-Regalis Calculator](https://your-username.github.io/Vittam-Regalis/)

## 📖 How to Use

### Adding Transactions
1. **Enter Transaction Details**:
   - Number of shares
   - Buying price per share
   - Selling price per share
   - Trade type (Delivery/Intraday)

2. **Click "Add"** to add the transaction to your portfolio

3. **Repeat** for multiple transactions

4. **Click "Calculate P&L"** to see comprehensive results

### Understanding Results

#### Key Metrics
- **Total Investment**: Amount invested in buying shares
- **Total Sale Value**: Amount received from selling shares
- **Gross P&L**: Raw profit/loss (Sale Value - Investment)
- **Total Charges**: Sum of all trading charges
- **Net P&L**: Profit/loss after deducting all charges
- **Final Amount**: Actual amount in hand after all deductions

#### Detailed Breakdown
View granular breakdown of:
- Individual charge components
- STCG tax calculation (if applicable)
- Transaction-wise P&L with color coding

## 🧮 Calculation Formula

```
Total Investment = Σ(Shares × Buy Price)
Total Sale Value = Σ(Shares × Sell Price)
Gross P&L = Total Sale Value - Total Investment
Total Charges = Brokerage + Exchange Charges + Clearing Charges + IGST + STT + SEBI Fees + Stamp Duty
Net P&L = Gross P&L - Total Charges
STCG Tax = Net P&L × 20.8% (if Net P&L > 0)
Final Amount = Total Sale Value - Total Charges - STCG Tax
```

## 💡 Example Calculation

**Transaction**: 100 shares, Buy: ₹150, Sell: ₹165 (Delivery)

**Charges Breakdown**:
- Brokerage: ₹0 (delivery)
- Exchange Charges: ₹0.94
- Clearing Charges: ₹0.40
- IGST: ₹0.24
- STT: ₹31.50
- SEBI Fees: ₹0.03
- Stamp Duty: ₹2.25
- **Total Charges**: ₹35.36

**P&L Calculation**:
- Investment: ₹15,000
- Sale Value: ₹16,500
- Gross Profit: ₹1,500
- Net Profit: ₹1,464.64
- STCG Tax: ₹304.65
- **Final Amount**: ₹16,195.35

## 📱 Responsive Design

The calculator is fully responsive and works on:
- 🖥️ Desktop computers
- 📱 Mobile phones
- 📟 Tablets
- 💻 Laptops

## 🔧 Technical Details

- **Frontend**: Pure HTML, CSS, JavaScript
- **No Dependencies**: Works offline, no external libraries
- **Browser Support**: All modern browsers
- **File Size**: Lightweight and fast-loading

## 📋 Files Structure

```
Vittam-Regalis/
├── README.md                    # This file
├── zerodha-pnl-calculator.html  # Main calculator application
└── zerodha-charges-summary.md   # Detailed charges documentation
```

## 🎯 Use Cases

- **Day Traders**: Calculate intraday trading profits with accurate charges
- **Investors**: Analyze delivery trading returns with tax implications
- **Portfolio Analysis**: Track multiple transactions and consolidated P&L
- **Tax Planning**: Understand STCG tax liability on trading profits

## ⚠️ Important Notes

1. **Accuracy**: Charges are based on current Zerodha rates as of 2024
2. **IGST**: 18% applies when trader and broker are in different states
3. **Tax Liability**: STCG tax only applies on net profits
4. **Updates**: Verify current rates on Zerodha's official website

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Built for the Indian trading community
- Inspired by the need for accurate P&L calculations
- Designed with royal precision for modern traders

---

**Vittam-Regalis** - *Where Royal Precision Meets Modern Trading* 👑

*Calculate like a king, trade like a champion!*
