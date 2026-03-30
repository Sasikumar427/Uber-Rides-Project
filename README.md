🚖 Uber Ride Data Analysis — Power BI Dashboard

A comprehensive Power BI project analyzing Uber ride data to uncover insights into customer behavior, demand trends, and operational efficiency. The dashboard spans 5 analytical pages and covers over 104K bookings, ₹51.85M in revenue, and 2.51M km of total distance traveled.

📊 Dashboard Pages

1. Overview Page
High-level KPIs and summary metrics across all vehicle types.
KPIs tracked:
- Completed Bookings — 93K
- Lost Bookings — 57K
- Revenue — ₹51.85M
- Total Distance — 2.51M km
- Avg Distance — 24.64 km
Features:
- Vehicle type filter
- Monthly & quarterly analysis for bookings and revenue
- Revenue breakdown by vehicle type
- Top pickup location: Khandsa (600) | Top drop location: Ashram (592)
- Average Customer Rating: 4.40 | Average Driver Rating: 4.23

2. Vehicle Page
Detailed performance breakdown per vehicle type.
| Vehicle | Customers | Revenue | Completed Bookings |
| Auto | 32,948 | ₹1,28,78,422 | 23,128 |
| Bike | 29,138 | ₹1,14,56,182 | 20,560 |
| Go Mini | 28,358 | ₹1,03,38,496 | 18,529 |
| Go Sedan | 23,330 | ₹93,69,719 | 16,666 |
| Premier Sedan | 16,827 | ₹62,75,332 | 11,247 |
| Uber XL | 4,447 | ₹15,28,032 | 2,783 |

- Booking contribution % per vehicle
- Monthly booking trend sparklines per vehicle

3. Revenue Page
Multi-dimensional revenue analysis.
- By Vehicle Type — Auto leads at ₹13M
- By Payment Method — UPI dominates at ₹23M, followed by Cash ₹13M, Uber Wallet ₹6M, Credit Card ₹5M, Debit Card ₹4M
- By Customer — Top customer C7828101 at ₹7.7K
- Monthly & Quarterly trends — Revenue ranges from ₹3.97M (Feb) to ₹4.57M (Mar)

4. Rider Page
Customer segmentation and cancellation analysis.
Rider segments:
- 🆕 First Time Riders — 48K
- 🔁 Return Riders — 5,650
- ⭐ Regular Riders (3+ rides) — 11K
Insights:
- Payment method preference: UPI (37K) > Cash (16K) > Uber Wallet (11K) > Credit Card (9K) > Debit Card (8K)
- Cancellation reasons tracked: Customer-related issues, Driver-related issues, Incomplete rides
- Detailed customer-level data table with booking value, completed/lost rides, and avg distance

5. Location Page
Geo-temporal demand and distance analysis.
- Total Distance by Vehicle — Auto: 0.63M km | Bike: 0.56M km | Go Mini: 0.50M km
- Monthly Distance Trend — Peak in January (222K km), dip in February (190K km)
- Top Areas by Booking — Khandsa (949), Barakhampur (946), Saket (931), Badarpur (921)
- Busy Time Slots (all days):
  - 🔥 Peak: 09 AM–12 PM (~4,700–4,800 rides/day)
  - 🔥 High: 03 PM–06 PM and 06 PM–09 PM
  - 🌙 Lowest: 12 AM–03 AM (~755–835 rides/day)

🛠️ Tools & Technologies

| Tool | Usage |
| Microsoft Excel | Data cleaning & preparation |
| SQL | Data querying & transformation |
| Power BI Desktop | Dashboard design & visualization |
| DAX | Calculated measures & KPIs |

📁 Project Struture
uber-powerbi-analysis/
├── uber.xlsx               # Raw / cleaned source data
├── Uber.pbix               # Power BI report file
├── Uber.pdf                # Dashboard export (screenshots)
└── README.md

🔍 Key Insights

- Auto is the highest-revenue and most-used vehicle type
- UPI is the dominant payment method by a wide margin
- Morning peak (9 AM–12 PM) consistently sees the highest ride demand across all days
- Lost bookings (57K) represent a significant opportunity — roughly 38% of total attempted bookings
- Top pickup/drop clusters around Khandsa and Ashram suggest strategic driver placement opportunities

🚀 Getting Started

1. Clone this repository
2. Open `uber.xlsx` to explore the raw data
3. Open `Uber.pbix` in Power BI Desktop to interact with the full dashboard
4. Use the vehicle filter and Month/Quarter toggle to drill into specific segments

📬 Contact

Feel free to open an issue or reach out if you have questions or suggestions for improvements.
