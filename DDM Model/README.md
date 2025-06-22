# Dividend Discount Model (DDM) for Stock Valuation

This repository provides a **Dividend Discount Model (DDM)** for valuing dividend-paying stocks. The DDM estimates the intrinsic value of a stock based on the present value of its expected future dividend payments.

---

## What is the Dividend Discount Model (DDM)?

The DDM is a fundamental valuation approach that determines the fair value of a stock by projecting all future dividends and discounting them back to their present value. This model is best suited for mature companies with stable and predictable dividend policies.

---

## Key Features

- **Single-stage (Gordon Growth) and Multi-stage DDM:** Choose between a constant dividend growth rate or variable stages (e.g., high growth followed by stable growth).
- **Customizable Inputs:** Easily adjust dividend amounts, growth rates, and required rate of return.
- **Sensitivity Analysis:** Assess how changes in assumptions (growth, required return) impact valuation.
- **User-Friendly:** Available as an Excel/Google Sheets template or Python script for flexible use.

---

## Getting Started

### Prerequisites

- [Excel](https://www.microsoft.com/en/microsoft-365/excel)

### Usage

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/ddm-model.git
    ```
2. **Open the model:**
    - For the spreadsheet: Open `DDM_Model.xlsx` (or use the Google Sheets version).
    - For the Python script: Go to `/src` and run `python ddm_model.py`.

3. **Input Data:**
    - Enter recent dividend amount(s), expected dividend growth rate(s), and your required rate of return.

4. **Review Outputs:**
    - The model calculates the present value of expected dividends and the intrinsic value per share.
    - Use sensitivity tables to test different growth and discount rate scenarios.

---

## Example: Gordon Growth (Single-Stage DDM)

The intrinsic value (P) is:

```
P = D1 / (r - g)
```

Where:
- `D1` = Expected dividend per share next year
- `r` = Required rate of return
- `g` = Expected dividend growth rate

---

## Files

- `DDM_Model.xlsx` – Main spreadsheet template
- `/src/ddm_model.py` – Optional Python implementation
- `README.md` – This file

---

## When to Use the DDM

| Scenario                                   | DDM Suitability      |
|---------------------------------------------|----------------------|
| Mature, stable, dividend-paying companies   | Highly suitable      |
| Irregular or no dividends                   | Not recommended      |
| High-growth, non-dividend stocks            | Not suitable         |

---

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with suggestions or improvements.
