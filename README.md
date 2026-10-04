# Orestis Androulakis

Financial Analyst moving into data analytics. I work in SQL, Power BI and Excel, with Python where the question needs it.

My background is finance — a degree in Accounting & Finance, an MBA, and day-to-day work on budgets, P&L and balance sheets. That shapes how I analyse data: every project below starts from a business question, reconciles to the euro, and says plainly what the data cannot prove.

## Projects

### [Olist E-Commerce Analytics](https://github.com/OrestisAndr/olist-ecommerce-analytics)

**6.7% of orders arrive late. They generate 36.8% of all one-star reviews.**

SQL-first analysis of 99,092 orders from a Brazilian marketplace. With a 3.5% repeat rate, reviews drive acquisition rather than retention, which makes delivery reliability the growth lever and not just an operations KPI.

- Every business definition lives in a PostgreSQL semantic layer; Power BI consumes it without redefining anything
- Caught a join fan-out that inflated revenue by 4.54% (R$ 617K of phantom GMV)
- Applied RFM segmentation, then rejected it and documented why it is meaningless on this data

`PostgreSQL` `SQL` `Power BI` `Docker`

### [Hotel Booking Analytics](https://github.com/OrestisAndr/hotel-booking-analytics)

**Two hotels lose €16.7M to cancellations against €26.0M realised.**

A Power BI report that measures where the revenue leaks, followed by a model that predicts which bookings will cancel and turns that into two decisions: how many rooms to oversell, and which guests to call.

- Revenue-weighted ADR reversed the channel ranking that a simple average had shown
- Removed five columns that leak the outcome, including one used in many published notebooks on this dataset
- Monthly recalibration brought the forecast error from −19.6% to −5.6%, tested on a time-based split

`Power BI` `DAX` `Python` `scikit-learn`

## Tools

| Area | Tools |
|---|---|
| SQL | PostgreSQL — CTEs, window functions, views, data-quality audits |
| BI | Power BI — star schemas, DAX, PBIP version control |
| Spreadsheets | Excel (advanced) — financial models, reporting automation |
| Python | pandas, scikit-learn, Jupyter |
| Finance | Budgeting, variance analysis, P&L, balance sheet |

## Contact

[LinkedIn](https://www.linkedin.com/in/orestis-androulakis) · or.androulakis@icloud.com
