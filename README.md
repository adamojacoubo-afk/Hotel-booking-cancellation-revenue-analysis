
# Hotel Booking Cancellation & Revenue Analysis

## Objective
This project analyzes hotel booking data to identify cancellation patterns and estimate the impact on potential revenue.

The goal is to support Revenue Management decisions using data-driven insights.

---

## Dataset
- Source: Kaggle – Hotel Booking Demand Dataset
- Period: 2015–2017
- Hotels: City Hotel & Resort Hotel
- Observations: 119,390 bookings

---

## Key Business Questions
- What is the overall cancellation rate?
- Which hotel type has higher cancellation risk?
- How does lead time affect cancellations?
- What is the impact of cancellations on revenue?
- Which segments generate more cancellations?
## Sample Visual Insights

### Cancellation Rate
![Cancellation Rate](images/01_cancellation_rate.png)

### City vs Resort Comparison
![Hotel Comparison](images/02_hotel_comparison.png)

### Revenue Lost
![Revenue Lost](images/09_revenue_lost.png)
---
### Lead Time Analysis
![Lead Time](images/08_lead_time_analysis.png)

### Market Segment Analysis
![Market Segment](images/06_market_segment.png)
## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Key Insights

- Cancellation rate is approximately **37.5%**, meaning 1 out of 3 bookings is lost.
- City Hotel shows a higher cancellation rate compared to Resort Hotel.
- Long lead time bookings are more likely to cancel.
- Certain market segments contribute more to cancellations.
- Cancelled bookings represent significant **revenue lost**.

---

## Revenue Management Recommendations

- Implement stricter cancellation policies for high-risk segments.
- Introduce non-refundable or advance purchase rates.
- Monitor booking pace and lead time continuously.
- Apply dynamic pricing strategies to protect ADR.
- Focus on segment-based forecasting instead of general forecasting.

---

## Project Structure

- `EDA_Hotel_Booking_PROFESSIONAL.ipynb` → Full analysis
- `images/` → Charts and visual insights

---

## Author

This project was developed as part of my portfolio for Junior Revenue Analyst / Revenue Management roles.
