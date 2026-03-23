# Interest Rate Swap Valuation in Excel

## Overview
This project is an Excel-based valuation model for a bullet interest rate swap.

The model calculates the present value of both the floating and fixed legs of the swap, solves for the fair fixed rate using a goal-seek setup and evaluates interest-rate sensitivity through PV01.

---

## Model Features

- Bullet swap cashflow schedule
- Floating-leg cashflow valuation
- Fixed-leg cashflow valuation
- Present value calculation for both legs
- Fair swap rate solving using goal seek
- PV01 / sensitivity analysis

---

## Methodology

The model is built around a scheduled set of swap periods, where each period includes:
- start date and end date,
- day-count convention,
- opening notional,
- floating rate cashflow,
- fixed rate cashflow,
- and discounted present values.

The floating leg is derived using discount-factor-based implied forward rates, while the fixed leg is valued using the swap fixed rate. The model then compares the present values of the two legs to determine the fair rate and sensitivity.

---

## Skills Demonstrated

- Interest Rate Derivatives
- Swap Valuation
- Sensitivity Analysis
- PV01 / Delta Interpretation

---

## Relevance

This project is relevant to:

- Risk Management

It demonstrates the ability to build a structured valuation model in Excel and apply fixed-income concepts in a practical setting.

---

## Files

- `Swap_Model_Bullet_PV01.xlsx` -> Excel model for bullet swap valuation and PV01 analysis
