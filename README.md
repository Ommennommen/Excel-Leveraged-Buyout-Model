# Leveraged Buyout (LBO) Model – Excel

This project models a Leveraged Buyout (LBO) scenario in Excel to demonstrate understanding of private equity deal mechanics, capital structuring, and returns analysis.

---

## Overview

An LBO is a transaction in which a financial sponsor acquires a company primarily using borrowed funds, with the expectation that the company’s cash flows will be sufficient to service the debt and generate a strong equity return at exit.

This Excel model:
- Builds a simplified LBO framework with dynamic assumptions.
- Forecasts financial performance over the investment period.
- Models debt amortization and interest expense.
- Calculates key returns metrics: IRR and MOIC.
- Includes sensitivity tables to stress-test assumptions.

---

## Project Structure

- Assumptions Tab – Key deal inputs (purchase price, leverage, growth rates, etc.).
- Ops (Operations) Tab – Revenue, EBITDA, Capex, Working Capital, Free Cash Flow calculations.
- Sources & Uses Tab – Purchase price funding breakdown between debt and equity.
- Debt Schedule Tab – Interest, amortization, cash sweeps, and ending debt balances.
- Returns Summary Tab – IRR, MOIC, and exit calculations.
- Sensitivity Tab – IRR sensitivity to exit multiples and leverage levels.

---

## Methodology

### 1. Assumptions
- Entry EBITDA (Y0): 100
- EBITDA Growth: 8% per year
- EBITDA Margin: 30%
- Capex % of Revenue: 3%
- ΔNWC % of ΔRevenue: 2%
- D&A % of Revenue: 2%
- Tax Rate: 25%
- Entry/Exit EV / EBITDA Multiple: 12x
- Debt % of Entry EV: 60%
- Interest Rate: 8%
- Mandatory Amortization: 5% of original debt/year
- Fees: 2% of EV
- Exit Year: 5

---

### 2. Operational Forecast
- Revenue grows at 8% annually.
- EBITDA = Revenue × EBITDA Margin.
- EBIT = EBITDA – D&A.
- Free Cash Flow (Unlevered) = EBIT – Taxes + D&A – Capex – ΔNWC.

---

### 3. Sources & Uses
- Uses: Purchase EV + fees.
- Sources: Debt financing + sponsor equity.
- Debt covers 60% of EV; equity funds the remainder.

---

### 4. Debt Schedule
- Tracks beginning debt, interest expense, mandatory amortization, and optional prepayments from excess cash flow (cash sweep).
- Links interest expense into Ops tab to ensure accurate after-debt FCF.

---

### 5. Returns Calculation
- Exit EBITDA: Year 5 EBITDA.
- Exit EV: Exit EBITDA × Exit Multiple.
- Net Debt at Exit: Ending debt balance in Year 5.
- Equity Value at Exit: Exit EV – Net Debt.
- MOIC: Equity Value at Exit ÷ Initial Equity Invested.
- IRR: Based on equity cash flows from Y0 to Y5.

---

### 6. Sensitivity Analysis
Two tables included:
1. Exit Multiple vs IRR (Debt % fixed at 60%)
2. Leverage vs IRR (Exit Multiple fixed at 12x)

---

## Base Case Results

- Exit Multiple: 12x
- Debt % of EV: 60%
- MOIC: 3.24x
- IRR: 27%

---

## How to Use
1. Open the Excel file.
2. Adjust Assumptions tab to reflect different deal structures.
3. Review impact in Returns Summary and Sensitivity tabs.

---

## Key Learnings
- How leverage impacts equity returns in private equity.
- Relationship between exit multiple, growth rate, and IRR.
- Importance of debt amortization and cash sweep in return profiles.
