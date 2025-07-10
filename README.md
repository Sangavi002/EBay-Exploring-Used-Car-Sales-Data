
# 🚗 EBay - Exploring Used Car Sales Data

This project analyzes used car listings from eBay Kleinanzeigen, a classifieds website in Germany. The goal is to clean the data and explore trends such as brand popularity, pricing, and odometer readings.

---

## 📊 Dataset Overview

- Source: eBay Kleinanzeigen
- Records: ~50,000 car listings
- Original fields included seller type, brand, registration year, price, odometer, etc.

---

## 🧹 Data Cleaning Steps

- Removed irrelevant columns (`seller`, `offer_type`, `pictures_number`)
- Cleaned `price` and `odometer` fields by removing symbols and converting to integers
- Renamed columns to use snake_case for consistency
- Removed outliers and incorrect values where necessary

---

## 🔍 Key Insights

- Most listings are from brands like **Volkswagen**, **BMW**, and **Opel**
- Common odometer readings are round numbers like 150,000 km
- Average price varies significantly by brand
- Popular brands were filtered by those having >5% of total listings

---

## 📁 Files in this Repository

| File Name       | Description                              |
|------------------|------------------------------------------|
| `ebay.ipynb`     | Main Jupyter Notebook with full analysis |
| `README.md`      | Project description and instructions     |

---
