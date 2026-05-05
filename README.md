# 🏨 Hotel Booking Data Engineering Project — Snowflake Native

A complete end-to-end data engineering project built entirely inside Snowflake.
No external tools. No Power BI. No Python notebooks. Pure Snowflake.

## 🏗️ Architecture
Bronze → Silver → Gold (Medallion Architecture)

## 🧰 Tech Stack
- Snowflake
- Snowsight Dashboards
- Snowflake SQL
- File Formats, Stages & COPY INTO

## 🚀 What's Built
- Raw CSV data loaded into Snowflake Stages
- Bronze Layer — raw data ingestion
- Silver Layer — data cleaning & validation
  - Missing values handled
  - Invalid emails removed
  - Negative pricing fixed
  - Wrong date ranges corrected
  - Status typos cleaned
- Gold Layer — aggregated & analytics-ready tables
- Interactive Dashboard inside Snowsight

## 📊 Gold Layer Tables
- `GOLD_BOOKING_CLEAN` — cleaned booking data
- `GOLD_AGG_DAILY_BOOKING` — daily revenue & bookings
- `GOLD_AGG_HOTEL_CITY_SALES` — revenue by city

## 💡 Key Learnings
- Medallion Architecture in Snowflake
- Data validation using pure SQL
- Snowflake-native dashboarding
- Production-style pipeline design
