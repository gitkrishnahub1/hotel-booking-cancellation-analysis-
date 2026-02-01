# hotel-booking-cancellation-analysis-
Analyzed hotel booking cancellations and quantified revenue risk using Python and Pandas

Topics:
python, pandas, data-analysis, eda, hotel-bookings

## Project Overview
This project analyzes hotel booking data to understand cancellation patterns and quantify revenue loss caused by canceled bookings.  
The goal is to identify high-risk booking periods, customer segments with higher cancellation rates, and estimate revenue at risk.

---

## Dataset
- Source: Hotel booking dataset
- Records: ~119,000 bookings
- Target variable: `is_canceled`
- Key attributes: lead time, customer type, stay duration, ADR

---

## Tools & Technologies
- Python
- Pandas
- Jupyter Notebook

---

## Data Cleaning
- Removed invalid records such as negative ADR and bookings with zero adults
- Handled missing values using business context (not random filling)
- Ensured clean and reliable data for analysis

---

## Feature Engineering
- `total_stay_nights` – total length of stay
- `booking_value` – revenue proxy (ADR × stay length)
- `lead_time_bucket` – booking period categories for cancellation analysis

---

## Key Analysis & Insights
- Overall cancellation rate was ~37%
- Bookings made more than 90 days in advance had the highest cancellation rate (~51%)
- Transient customers showed the highest cancellation rate (~41%)
- Group bookings were the most reliable (~10% cancellation)
- Total revenue at risk due to cancellations was approximately 16.7 million

---

## Business Recommendations
- Apply stricter cancellation policies or deposits for early bookings
- Use controlled overbooking strategies for high-risk customer segments
- Prioritize group bookings for stable revenue

---

## Conclusion
This analysis highlights how booking lead time and customer type significantly impact cancellation behavior and revenue risk, providing actionable insights for improving hotel revenue management strategies.
