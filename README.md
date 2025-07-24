# 🚖 Dynamic Pricing Simulator | Excel + Python

This project simulates real-time fare changes for a ride-booking platform based on demand-supply dynamics, customer loyalty, booking time, and vehicle type. Built using **Python for logic simulation** and **Excel for dashboard visualization**.

---

## 📌 Project Objective

To build a rule-based Dynamic Pricing Simulator that adjusts ride prices dynamically using the following business logic:

- Surge pricing when demand exceeds supply
- Loyalty-based discounts
- Time-based price surges (e.g., peak hours)
- Vehicle-based premium pricing

---

<img width="1331" height="596" alt="image" src="https://github.com/user-attachments/assets/92e94054-b841-43e3-93bc-c1e282d12a0f" />

## 📊 Dataset Features

| Column Name               | Description |
|--------------------------|-------------|
| Number_of_Riders         | Riders requesting rides |
| Number_of_Drivers        | Available drivers |
| Location_Category        | Urban, Rural, Suburban |
| Customer_Loyalty_Status  | Gold, Silver, Bronze |
| Number_of_Past_Rides     | Past rides by the customer |
| Average_Ratings          | Ride quality feedback |
| Time_of_Booking          | Morning Peak, Evening Peak, Off-Peak |
| Vehicle_Type             | SUV, Sedan, Bike |
| Expected_Ride_Duration   | Estimated duration of the ride |
| Historical_Cost_of_Ride  | Original price before adjustments |

---

## ⚙️ Pricing Simulation Logic

- **Demand-Supply Surge**:  
  `+25%` if `riders > 1.5 × drivers`, `-10%` if underutilized.
  
- **Time-based Surge**:  
  Morning Peak / Evening Peak: `+15%`.

---

## 🧠 Key Insights Enabled in Dashboard (Excel)

- 📈 **Simulated Price vs. Time of Booking**
- 🗺️ **Price by Location Category**
- 🚗 **Vehicle Type vs Simulated Price**
- 👥 **Loyalty Status vs Discount Received**
- 🔄 **Before vs After Price Comparison**

---

