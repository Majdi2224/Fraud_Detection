# Fraud Detection Project

## Project Overview
This project is a professional-level fraud detection pipeline using a large-scale financial transactions dataset. The goal is to **identify fraudulent transactions** with a combination of feature engineering, exploratory data analysis (EDA), and machine learning models.

**Dataset:** 6M+ transactions with features like transaction amount, type, origin and destination accounts, balances, and fraud labels.

---

## Features
Some key engineered features:
- `suspicious_dest_balance` – flags suspicious destination balances
- `is_new_dest` – flags destinations appearing for the first time
- `is_unique_dest` – flags destinations used only once
- Transaction amounts, account balances, transaction types, etc.

---

## Getting Started

### Requirements
```bash
pip install -r requirements.txt
