# Bond Price Sensitivity Analysis Using Python

## Overview

This project analyzes how changes in market yield affect the price of a fixed-rate bond using Python.

The analysis applies key **CFA Level I Fixed Income concepts**, including bond pricing, cash flows, Macaulay Duration, Modified Duration, and bond price sensitivity.

A hypothetical 5-year bond with a face value of **$1,000** and an annual coupon rate of **8%** is used for the analysis.

---

## Objectives

* Calculate the price of a coupon-paying bond
* Analyze the inverse relationship between bond prices and market yields
* Calculate Macaulay Duration
* Calculate Modified Duration
* Estimate bond price sensitivity using Modified Duration
* Compare estimated and actual bond prices

---

## Key Concepts

### 1. Bond Pricing

The bond price is calculated as the present value of its future coupon payments and principal repayment.

### 2. Yield–Price Relationship

The analysis demonstrates the fundamental Fixed Income relationship:

**Market Yield ↑ → Bond Price ↓**

**Market Yield ↓ → Bond Price ↑**

### 3. Macaulay Duration

Macaulay Duration measures the weighted-average time until the bond's cash flows are received.

### 4. Modified Duration

Modified Duration measures the approximate sensitivity of a bond's price to changes in market yield.

---

## Analysis

The bond was evaluated across different market yields:

| Market Yield | Bond Price |
| -----------: | ---------: |
|           6% |  $1,084.25 |
|           7% |  $1,041.00 |
|           8% |  $1,000.00 |
|           9% |    $961.10 |
|          10% |    $924.18 |

The results demonstrate the inverse relationship between market yield and bond price.

---

## Duration Analysis

At an 8% market yield:

* **Macaulay Duration:** approximately 4.31 years
* **Modified Duration:** approximately 3.99 years

When the yield increased from **8% to 9%**:

* Original Bond Price: **$1,000.00**
* Estimated Price using Modified Duration: **$960.07**
* Actual Bond Price: **$961.10**

The difference between the estimated and actual price demonstrates that Modified Duration provides an **approximation** of price sensitivity rather than an exact price prediction.

---

## Tools & Libraries

* Python
* NumPy
* Pandas
* Matplotlib
* Google Colab

---

## CFA Relevance

This project applies concepts from **CFA Level I Fixed Income**, particularly:

* Bond valuation
* Coupon payments
* Yield and bond prices
* Macaulay Duration
* Modified Duration
* Interest-rate sensitivity

This is an independent educational project and is **not an official CFA Institute project**.

---

## Project Structure

```text
Bond-Price-Sensitivity-Analysis-Python/
│
├── Bond_Price_Sensitivity_Analysis.ipynb
└── README.md
```

---

## Key Takeaway

A change in market yield can significantly affect the price of a fixed-rate bond. Duration provides a practical framework for measuring and estimating this interest-rate sensitivity.

This project demonstrates how Python can be used to translate financial theory into a practical quantitative analysis.

