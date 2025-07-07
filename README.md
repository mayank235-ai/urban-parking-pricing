# 🚗 Dynamic Pricing for Urban Parking Lots

This project implements three intelligent dynamic pricing models for urban parking lots, developed as part of **Summer Analytics 2025**.

---

## 📊 Models Implemented

### ✅ Model 1: Baseline Linear Pricing
- Price increases linearly based on occupancy.
- Formula:  
  \[
  \text{Price}_{t+1} = \text{Price}_t + \alpha \cdot \left( \frac{\text{Occupancy}}{\text{Capacity}} \right)
  \]

### ✅ Model 2: Demand-Based Pricing
- Price adjusts based on multiple demand signals:
  - Occupancy Rate
  - Traffic Condition
  - Queue Length
  - Special Day
  - Vehicle Type

### ✅ Model 3: Competitive Pricing
- Considers nearby lots (within 1 km) using latitude/longitude.
- Adjusts price based on competitors’ prices and occupancy levels.

---

## 📈 Visualizations
- Trend comparison of all 3 models per parking lot
- Timestamp-based price progression

---

## 🗂️ Project Structure

