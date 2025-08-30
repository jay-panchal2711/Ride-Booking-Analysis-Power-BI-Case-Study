# 🚖 Ride-Booking-Analysis-Power-BI-Case-Study

## 📊 Overview
This project analyzes **150,000 ride booking records (21 columns)**, uncovering insights about:
- Ride booking patterns
- Customer behavior
- Driver performance
- Operational efficiency
- Peak demand trends

The analysis was performed using **Power BI** and supported by preprocessing in Power Query.

---

## 📂 Repository Contents
- `data/` – Raw datasets
- `powerbi/` – Power BI report file (`.pbix`)
- `reports/` – Detailed project report (Word)
- `scripts/` – Data cleaning steps & DAX measures
- `README.md` – Project documentation

---

## ⚙️ Data Preprocessing
- Removed nulls, blanks, duplicates, and errors.
- Standardized categorical fields (case-insensitive).
- Created derived columns:
  - `DateTime` (merged Date + Time)
  - `DayOfWeek` (weekday name)
  - `HourOfDay` (0–23)
- Converted ride status, cancellations, and incomplete flags into binary (0/1).
- Trimmed extra spaces from text fields.

---

## 📈 Key Insights
1. **Most popular vehicle:** Auto (37,419 bookings)  
   **Least popular vehicle:** Uber XL (4,449 bookings)

2. **Average ride distance:** 24.64 km  
   **Average booking value:** ₹508.30

3. **Ratings distribution:** Most users rate between 3.5 and 4.5

4. **Cancellation reasons:**  
   - By Customers: Wrong Address (2,362 cases)  
   - By Drivers: Customer-related Issues (6,837 cases)

5. **Peak demand:**  
   - Locations: Adarsh Nagar, AIIMS, Akshardham  
   - Times: Morning 10 AM, Evening 5–7 PM

---

## 📌 Recommendations
- **Improve cancellation handling** with better address validation.
- **Driver training** to reduce cancellations tagged as “customer issues.”
- **Dynamic pricing model** during peak hours.
- **Customer loyalty rewards** for frequent riders.

---

## 🛠️ How to Use
1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/Ride-Booking-Analysis.git
