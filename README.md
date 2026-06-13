# n8n Automation Workflows

A collection of n8n workflows I created for a workshop.

## Workflows

### 1. Weather Database Sync
Fetches weather data from OpenWeatherMap and synchronizes it with a MySQL database by updating existing records or inserting new ones.

**Technologies:** n8n, OpenWeatherMap API, MySQL

---

### 2. Weather Data Logger
Retrieves weather information periodically and appends city, temperature, weather conditions, and timestamps to Google Sheets.

**Technologies:** n8n, OpenWeatherMap API, Google Sheets

---

### 3. Product Price Sync and Monitoring
Fetches products from an external API, filters high-rated products, checks for existing records in MySQL, detects price changes, and inserts new products when necessary.

**Technologies:** n8n, Fake Store API, MySQL

---

## Technologies Used

- n8n
- REST APIs
- MySQL
- Google Sheets
- JavaScript
- Scheduling and automation

## Use Cases

- Database synchronization
- API integrations
- Data collection and logging
- Product monitoring
- Scheduled workflows

## Getting Started

1. Clone the repository.
2. Import any `.json` workflow into n8n.
3. Configure the required credentials and API keys.
4. Activate the workflow.

## Repository Structure

```
.
├──  weather-data-logger.json
├── weather-database-sync.json
├── product-price-sync-monitoring.json
├── screenshots/
└── README.md
```
