# Flight Price Tracker with API & Power BI Integration

This project tracks flight prices using the Amadeus Flight Offers Search API. The data is collected via Python, processed into a structured format, and optionally exported for live dashboarding in Power BI.

## Features

- Fetches real-time flight offers for multiple destinations
- Extracts and stores:
  - Price (base & total)
  - Cabin class & fare class
  - Duration
  - Traveler type
  - Number of segments
  - Seats available
- Saves data as a CSV for use in Power BI or other tools
- Can be connected to cloud storage or databases for automatic refresh

## Tech Stack

- **Python** (requests, pandas)
- **Amadeus API**
- **Power BI** (for dashboard visualization)
- Optional: **Azure SQL / OneDrive / Google Drive** for live data refresh

## Setup

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/flight-price-tracker.git
   cd flight-price-tracker
