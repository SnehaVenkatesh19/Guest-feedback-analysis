# Guest Feedback Analysis – Check-In vs Check-Out

This project analyzes hotel guest feedback to understand what persuades customers to book a stay and what actually impresses them during their visit. Using Check-In and Check-Out survey responses, we identify top-performing features, satisfaction gaps, and actionable business insights.

---

## Objective

To compare guest expectations (`Check-In` responses) vs. actual experiences (`Check-Out` responses) and classify hotel features as:
- Star Performers
- Overperformers
- Underperformers
- Low Impact

---

## Tools & Technologies

- Python (pandas, matplotlib)
- Google Colab
- Tableau Public
- Manual feature categorization and median-based classification

---

## Key Steps

- Cleaned and exploded semicolon-separated multi-response survey data
- Counted frequency of each feature in Check-In and Check-Out
- Calculated:
  - `Difference = Check-Out - Check-In`
  - `% Change = (Difference / Check-In) * 100`
- Categorized responses into themes (Amenities, Service, etc.)
- Classified responses using median-based logic:
  - High/Low Check-In and Check-Out volumes
- Visualized the results in Tableau using bar charts and KPI tiles

---

## Tableau Dashboard

View the interactive dashboard here:  
[Tableau: Guest Feedback Dashboard](https://public.tableau.com/app/profile/sneha.venkatesh3644/viz/Hotel_response/Dashboard1)

---

## Key Insights

- **Quiet and Restful Environment** showed a +65 mention increase → a clear delight factor
- **Wi-Fi** exceeded expectations with consistent praise pre- and post-stay
- **Fitness Facilities** and **Parking** underperformed vs. expectations
- Features like **Interior Design** were rarely mentioned and may need reevaluation

---

## Next Steps

- Integrate guest demographic or booking data to enable segmentation
- Extend the classification framework to other hotel locations or time periods
- Automate reporting for continuous feedback loop

