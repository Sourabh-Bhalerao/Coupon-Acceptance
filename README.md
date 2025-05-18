# Coupon-Acceptance
Studies user coupon acceptance based on various criteria when driving

# Coupon Acceptance Prediction

This project analyzes driver behavior in response to location-based mobile coupons. Using a dataset from the UCI Machine Learning Repository, it explores how various factors — such as age, income, passenger type, and trip context — influence a driver’s decision to accept or reject a coupon.

---

## Project Structure

- `data/` – Raw data files (`coupons.csv`)
- `prompt.ipynb` – Jupyter notebooks for data exploration and modeling
- `README.md` – This file

---

## Dataset Overview

- **Source**: UCI Machine Learning Repository
- **Records**: ~5,000 simulated scenarios
- **Features**:
  - Destination, Weather, Time of Day
  - Passenger Type
  - Type of Coupon (Bar, Restaurant <$20, Restaurant $20–50, Coffee House, etc.)
  - Demographics (Age, Income, Marital Status, Occupation)
- **Target**: Whether the user accepts the coupon (`Y = 1`) or not (`Y = 0`)

---

## Key Questions Explored

- Are younger or older drivers more likely to accept coupons?
- Do income or occupation influence coupon acceptance?
- How does passenger type (e.g., with kids vs. alone) affect decisions?
- Which coupon types are most accepted?

---

## Technologies Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib, Plotly
- Jupyter Notebooks
- Git for version control

---

## Insights

- Cheaper restaurant coupons are widely accepted across all income levels.
- Bar coupons are much more likely to be accepted by younger, frequent bar-goers traveling without kids.
- Higher-income drivers are less influenced by coupon value alone.

---


