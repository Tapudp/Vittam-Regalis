# Zerodha Stock Trading Charges Summary

## Complete Charge Structure Implemented

### Trading Charges

#### **Brokerage**
- **Delivery**: ₹0 (Absolutely free)
- **Intraday**: ₹20 or 0.03% (whichever is lower) per executed order

#### **Exchange Transaction Charges**
- **NSE**: 0.00297% of turnover
- **BSE**: 0.00375% of turnover

#### **Clearing Charges**
- ₹0.002 per share (capped at 0.01% of turnover)
- Applied on both NSE and BSE

#### **IGST (Integrated Goods and Services Tax)**
- **Rate**: 18%
- **Applied on**: (Brokerage + Exchange Transaction Charges)
- **Note**: Applicable when trader and broker are in different states

#### **Securities Transaction Tax (STT)**
- **Delivery Trading**: 0.1% on both buy and sell transactions
- **Intraday Trading**: 0.025% on sell side only

#### **SEBI Turnover Fees**
- **Rate**: ₹10 per crore of turnover
- **Calculation**: 0.000001% of turnover

#### **Stamp Duty**
- **Rate**: 0.015% on buy side
- **Cap**: Maximum ₹1500 per trade

### Tax Calculations

#### **Short-Term Capital Gains Tax (STCG)**
- **Base Rate**: 20%
- **Cess**: 4% on the base rate
- **Total STCG**: 20.8% on net profits
- **Applied on**: Net profit after deducting all trading charges

### Important Notes

1. **Delivery Trading**: Most cost-effective with zero brokerage
2. **Intraday Trading**: Fixed ₹20 brokerage makes it suitable for larger trades
3. **Tax Optimization**: STCG tax only applies on net profits after all charges
4. **State Considerations**: IGST applies when trader and broker are in different states
5. **Turnover Calculation**: Sum of buy value and sell value for all transactions

### Calculation Formula

```
Total Investment = Σ(Shares × Buy Price)
Total Sale Value = Σ(Shares × Sell Price)
Gross P&L = Total Sale Value - Total Investment
Total Charges = Brokerage + Exchange Charges + Clearing Charges + IGST + STT + SEBI Fees + Stamp Duty
Net P&L = Gross P&L - Total Charges
STCG Tax = Net P&L × 20.8% (if Net P&L > 0)
Final Amount = Total Sale Value - Total Charges - STCG Tax
```

### Example Calculation

For a delivery trade of 100 shares:
- Buy Price: ₹150
- Sell Price: ₹165

**Charges Breakdown:**
- Brokerage: ₹0 (delivery)
- Exchange Charges: ₹0.94
- Clearing Charges: ₹0.40
- IGST: ₹0.24
- STT: ₹31.50
- SEBI Fees: ₹0.03
- Stamp Duty: ₹2.25
- **Total Charges**: ₹35.36

**P&L Calculation:**
- Investment: ₹15,000
- Sale Value: ₹16,500
- Gross Profit: ₹1,500
- Net Profit: ₹1,464.64
- STCG Tax: ₹304.65
- **Final Amount**: ₹16,195.35

This calculator provides accurate calculations based on current Zerodha charges as of 2024.