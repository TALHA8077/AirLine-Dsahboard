# ✈️ Airline Price Analysis — Power BI Dashboard

A Power BI dashboard analyzing Indian domestic flight pricing patterns across airlines, routes, travel classes, and booking windows.

---

## 📊 Dashboard Overview

This project explores what drives flight ticket prices on Indian domestic routes. The interactive dashboard allows users to filter and compare prices across multiple dimensions — helping travelers, analysts, and business stakeholders understand pricing trends at a glance.

**Tool Used:** Microsoft Power BI Desktop (`.pbix`)

---

## 📁 Repository Structure

```
├── Airline.pbix        # Power BI Dashboard file
├── Airline.xlsx        # Cleaned dataset (source data)
└── README.md
```

---

## 🗃️ Dataset Details

**File:** `Airline.xlsx` — Sheet: `Clean_Dataset`

| Column | Description |
|---|---|
| `airline` | Airline name (e.g., Indigo, Vistara, Air India) |
| `flight` | Flight number / code |
| `source_city` | Departure city |
| `destination_city` | Arrival city |
| `departure_time` | Time of departure (Early Morning, Morning, Afternoon, Evening, Night) |
| `arrival_time` | Time of arrival |
| `stops` | Number of stops (zero, one, two_or_more) |
| `class` | Travel class (Economy / Business) |
| `duration` | Flight duration in hours |
| `days_left` | Days remaining before departure at time of booking |
| `price` | Ticket price in INR (₹) |

**Dataset size:** ~300,000 rows

**Airlines covered:** SpiceJet, AirAsia, Vistara, GO FIRST, IndiGo, Air India

**Price range:** ₹2,409 – ₹31,260

---

## 💡 Key Insights from the Dashboard

- **Vistara and Air India** tend to have higher average fares, while **SpiceJet and AirAsia** are the most budget-friendly options.
- **Non-stop flights** (zero stops) are priced competitively but vary significantly by airline.
- **Early morning departures** generally offer lower prices compared to evening or night flights.
- **Ticket prices rise sharply** as the number of days left before departure decreases — booking early saves significantly.
- **Business class** tickets are priced considerably higher than Economy across all airlines.

---

## 🚀 How to Use

1. **Clone or download** this repository.
2. Open `Airline.pbix` in **Power BI Desktop** (free download from [Microsoft](https://powerbi.microsoft.com/desktop/)).
3. If prompted, re-link the data source to `Airline.xlsx` using **Transform Data → Data Source Settings**.
4. Explore the dashboard using the slicers/filters for airline, stops, class, and departure time.

> **Note:** Power BI Desktop is required to open `.pbix` files. It is free and available for Windows.

---

## 📌 Use Cases

- **Travelers** — Find the cheapest airline and best time to book.
- **Data Analysts** — Explore a real-world dataset for practice with Power BI.
- **Business Analysts** — Understand competitive pricing in Indian aviation.

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop** — Dashboard creation and data visualization
- **Microsoft Excel / Power Query** — Data cleaning and transformation
- **DAX** — Calculated measures and KPIs within Power BI

---


## 👤 Author

**MOHD TALHA ASHRAF**
- GitHub: [@yourusername](https://github.com/TALHA8077)
- LinkedIn: [your-linkedin](https://linkedin.com/in/mohd-talha-ashraf)

