# 🏨 Hospitality Data Analytics Project

## 📌 Main Aim

The primary objective of this project is to explore and analyze hotel booking data across multiple dimensions—hotels, rooms, dates, and customer behaviors—to extract actionable insights that support data-driven decision-making in the hospitality industry. This dataset can be used to model customer preferences, optimize booking strategies, and improve revenue management.

---

## 🌟 Feature Highlights

- 📅 **Date-Level Analysis**: Weekday vs Weekend trends, seasonal fluctuations.
- 🏨 **Hotel Performance Tracking**: Compare revenue, capacity, and bookings across cities and hotel categories (Luxury, Business).
- 🛏️ **Room Type Insights**: Analyze popularity and performance of room categories (Standard, Elite, Premium, Presidential).
- 📈 **Revenue & Occupancy Metrics**: Distinguish between generated vs realized revenue based on booking status.
- 🌐 **Booking Channel Evaluation**: Understand customer preferences across different platforms.
- 🙋‍♂️ **Customer Behavior Study**: Analyze guest volume, satisfaction ratings, and booking trends.

---

## 🗃️ Dataset Overview

This project is based on five CSV files representing dimensional and factual data related to hotel bookings.

### 1. `dim_date.csv`
Information about calendar dates used in analysis.

| Column Name | Description |
|-------------|-------------|
| `date` | Complete date (May, June, July) |
| `mmm yy` | Abbreviated month-year format |
| `week no` | Week number in the year |
| `day_type` | Categorizes the day as `Weekend` or `Weekday` |

---

### 2. `dim_hotels.csv`
Static hotel-related attributes.

| Column Name | Description |
|-------------|-------------|
| `property_id` | Unique ID for each hotel |
| `property_name` | Hotel name |
| `category` | Hotel class: `Luxury` or `Business` |
| `city` | City of operation |

---

### 3. `dim_rooms.csv`
Details regarding room classifications.

| Column Name | Description |
|-------------|-------------|
| `room_id` | Room type identifier (e.g., RT1, RT2) |
| `room_class` | Room class: `Standard`, `Elite`, `Premium`, `Presidential` |

---

### 4. `fact_aggregated_bookings.csv`
Aggregated data of room availability and bookings.

| Column Name | Description |
|-------------|-------------|
| `property_id` | Hotel identifier |
| `check_in_date` | Date of guest check-in |
| `room_category` | Room type |
| `successful_bookings` | Count of successful bookings on a given date |
| `capacity` | Total available rooms for the category on that date |

---

### 5. `fact_bookings.csv`
Detailed transactional data for each booking made.

| Column Name | Description |
|-------------|-------------|
| `booking_id` | Unique booking reference |
| `property_id` | Hotel ID |
| `booking_date` | Date the booking was made |
| `check_in_date` | Check-in date |
| `check_out_date` | Check-out date |
| `no_guests` | Number of guests in the booking |
| `room_category` | Booked room type |
| `booking_platform` | Platform used to book (website, app, etc.) |
| `ratings_given` | Customer rating |
| `booking_status` | Status: `Cancelled`, `Checked Out`, or `No Show` |
| `revenue_generated` | Gross revenue from the booking |
| `revenue_realized` | Net revenue after refund rules based on status |

---

## 📊 Use Cases

This dataset enables various business intelligence use cases:
- Time-based booking trend analysis
- Revenue and occupancy forecasting
- Room category and city-based performance metrics
- Cancellation rate impact on revenue
- Customer satisfaction analysis

---

## 🛠️ Tools Recommended

- Microsoft Power BI / Tableau – for dashboard creation and visualization
- Python / Pandas – for data cleaning and preprocessing
- SQL – for relational querying and data joining
- Excel – for exploratory data analysis

---

## 🧠 Insights & Outcomes (Add after Analysis)

You can include this section to document key findings from your analysis, such as:
- Which city has the highest revenue?
- Which room category gets booked the most on weekends?
- Revenue loss due to cancellations and "No Shows"

---

## 📎 How to Access the Data

All five CSV files are included in the repository. You can clone the repo and use your preferred analytics tools for further exploration.

---

## 📬 Contact

For inquiries or collaboration opportunities, please reach out via:

**Email**: [your.email@example.com]  
**LinkedIn**: [Your LinkedIn Profile]  

---

> ⭐ *If you find this repository useful, please give it a star to show your support!*
