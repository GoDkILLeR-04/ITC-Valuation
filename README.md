# Comprehensive Stock Valuation Models

This repository provides a suite of stock valuation models **Discounted Cash Flow (DCF)**, **Dividend Discount Model (DDM)**, and **Relative Valuation** to help you estimate the intrinsic and relative value of a publicly traded company. Whether you want to analyze a dividend-paying stock or benchmark against peers, this toolkit offers practical, customizable templates for your analysis.

---

## Overview of Valuation Methods

### 1. Discounted Cash Flow (DCF)

DCF valuation estimates a company's intrinsic value by projecting its future free cash flows and discounting them to the present using an appropriate discount rate (typically the Weighted Average Cost of Capital, or WACC).  
- **Best for:** Companies with predictable cash flows.
- **Key Inputs:** Revenue growth, margins, capital expenditures, working capital changes, discount rate, terminal growth rate.

### 2. Dividend Discount Model (DDM)

The DDM is a method used to value companies that pay regular dividends. It estimates the value of a stock based on the present value of expected future dividend payments.  
- **Best for:** Mature, stable companies with consistent dividend payouts.
- **Key Inputs:** Expected dividends, dividend growth rate, required rate of return.

### 3. Relative Valuation

Relative valuation compares the target company’s valuation multiples (such as P/E, EV/EBITDA, P/B) to those of similar companies in its peer group. This method assesses whether a stock is undervalued or overvalued relative to comparable businesses.  
- **Best for:** Benchmarking against industry peers.
- **Key Inputs:** Peer group selection, financial metrics, multiples.

---

## Directory Structure

```
/stock-valuation-models
│
├── README.md                    # This file
│
├── dcf/
│   ├── DCF_Model.xlsx
│   └── README.md
│
├── ddm/
│   ├── DDM_Model.xlsx
│   └── README.md
│
├── relative/
│   ├── Relative_Valuation_Model.xlsx
│   └── README.md
│
└── src/
    ├── dcf_model.py
    ├── ddm_model.py
    └── relative_valuation.py
```

---

## Getting Started

### Prerequisites

- [Excel](https://www.microsoft.com/en/microsoft-365/excel)

### How to Use

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/stock-valuation-models.git
    ```

2. **Select a Model:**
    - For **DCF analysis**, go to `/dcf/DCF_Model.xlsx`.
    - For **DDM analysis**, go to `/ddm/DDM_Model.xlsx`.
    - For **Relative Valuation**, go to `/relative/Relative_Valuation_Model.xlsx`.

3. **Input Data:**
    - Fill in the required financial and market data for the target company.
    - For DDM, provide dividend forecasts, growth rates, and required return.

4. **Review Outputs:**
    - Each model provides implied valuation outputs and summary tables.
    - Use built-in sensitivity analysis features to test different scenarios.

5. **Python Option:**  
   Navigate to `/src` and run the corresponding script for each model if you prefer a programmatic approach.

---

## Example Scenarios

- **DCF Example:** Project free cash flows for five years, apply a terminal growth rate, and discount at WACC to get intrinsic value.
- **DDM Example:** Estimate the present value of all expected future dividends for a dividend-paying stock.
- **Relative Example:** Compare your target’s EV/EBITDA to peers, then apply the median multiple to your target’s EBITDA.

---

## When to Use Each Model

| Model                | Best For                                      |
|----------------------|-----------------------------------------------|
| **DCF**              | Companies with stable, predictable cash flows |
| **DDM**              | Mature, stable, dividend-paying companies     |
| **Relative**         | Peer benchmarking and market positioning      |

---

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements or new features.
