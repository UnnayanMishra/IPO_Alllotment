# IPO Tracker – IPO Information & Allotment Tracking Platform

## 1. Project Overview

IPO Tracker is a web-based application designed to provide users with comprehensive information about Initial Public Offerings (IPOs) in the Indian stock market.

The platform allows users to track Mainboard and SME IPOs, monitor Grey Market Premium (GMP), check IPO subscription status, view allotment results, and track upcoming listing dates.

The application provides a centralized dashboard for investors to access IPO-related information and monitor IPO performance.

## 2. Core Features

### IPO Dashboard
- View all upcoming, ongoing, and closed IPOs.
- Separate categories for Mainboard and SME IPOs.
- Display IPO opening and closing dates.
- Show price bands and lot sizes.
- Display issue size and minimum investment.

### IPO Grey Market Premium (GMP)
- Display current GMP for each IPO.
- Show GMP percentage.
- Track GMP changes over time.
- Display estimated listing prices.
- Show estimated listing gains or losses.

### IPO Allotment Tracking
- View IPO allotment status.
- Search IPO allotment results.
- Provide allotment status information.
- Display registrar information and allotment result links.

### IPO Listing Information
- Display expected listing dates.
- Show listing prices when available.
- Compare IPO issue prices against listing prices.
- Track listing gains or losses.

### IPO Categories
- Mainboard IPOs
- SME IPOs
- Upcoming IPOs
- Open IPOs
- Closed IPOs
- Allotted IPOs
- Listed IPOs

### Search and Filters
- Search IPOs by company name.
- Filter by IPO category.
- Filter by issue status.
- Sort by opening date and listing date.
- Search historical IPO records.

## 3. Application Modules

| Module | Description |
|---|---|
| Dashboard | Overview of IPO market activity |
| IPO Listing | Complete IPO directory |
| Mainboard IPOs | Mainboard IPO information |
| SME IPOs | SME IPO information |
| GMP Tracker | Live or periodically updated GMP |
| Allotment Tracker | IPO allotment status |
| Listing Tracker | Listing date and performance |
| Search | IPO search and filtering |
| Admin Panel | IPO data and content management |

## 4. Suggested Technology Stack

### Frontend
- React.js / Next.js
- HTML5
- CSS3
- JavaScript / TypeScript
- Tailwind CSS

### Backend
- Python
- FastAPI / Flask
- REST APIs

### Database
- PostgreSQL
- Redis for caching

### Data Collection
- Authorized financial data APIs
- Exchange and registrar information
- Permitted data feeds
- Admin-managed IPO information

### Deployment
- AWS / Azure / GCP
- Docker
- Nginx
- CI/CD pipeline

## 5. Suggested Database Entities

- Users
- IPO Companies
- IPO Details
- IPO Categories
- IPO Subscription Data
- GMP History
- Allotment Records
- Listing Information
- Historical IPO Performance
- Admin Users

## 6. Application Workflow

1. Collect IPO information from permitted data sources.
2. Validate and store IPO information in the database.
3. Categorize IPOs into Mainboard and SME.
4. Update IPO subscription and GMP information.
5. Display IPO information on the dashboard.
6. Update allotment results when officially available.
7. Update listing prices after market listing.
8. Maintain historical IPO information for analysis.

## 7. Important Data Fields

| Field | Description |
|---|---|
| Company Name | IPO issuing company |
| IPO Type | Mainboard / SME |
| Price Band | Minimum and maximum issue price |
| Lot Size | Shares per application lot |
| Issue Size | Total issue value |
| Open Date | IPO opening date |
| Close Date | IPO closing date |
| GMP | Grey Market Premium |
| GMP Percentage | GMP relative to issue price |
| Estimated Listing Price | Indicative price based on GMP |
| Allotment Date | Expected allotment date |
| Listing Date | Expected stock exchange listing |
| Subscription | Category-wise subscription status |
| Allotment Status | Allotted / Not Allotted / Pending |

## 8. Non-Functional Requirements

- Responsive mobile-friendly interface.
- Fast dashboard loading.
- Reliable data synchronization.
- Secure authentication.
- Scalable backend architecture.
- API rate limiting.
- Database backup and recovery.
- Logging and error monitoring.

## 9. Suggested Project Structure

```text
ipo-tracker/
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── hooks/
│   │   └── assets/
│   └── package.json
│
├── backend/
│   ├── app/
│   │   ├── api/
│   │   ├── models/
│   │   ├── schemas/
│   │   ├── services/
│   │   ├── database/
│   │   └── main.py
│   └── requirements.txt
│
├── database/
│   └── schema.sql
│
├── tests/
│
├── docker-compose.yml
├── .env.example
└── README.md
```

## 10. Security and Compliance

- Do not store sensitive financial credentials unnecessarily.
- Use secure authentication and authorization.
- Protect APIs against unauthorized access.
- Use authorized data sources and comply with their terms.
- Clearly identify unofficial GMP information.
- Display appropriate financial risk disclaimers.

## 11. Disclaimer

IPO Tracker is an informational platform. IPO information, GMP values, subscription figures, and estimated listing prices are subject to change.

Grey Market Premium is unofficial and is not an exchange-confirmed indicator of listing performance.

The application does not guarantee IPO allotment or investment returns and should not be treated as financial advice.

## 12. Future Enhancements

- User watchlists and personalized IPO tracking.
- Email and push notifications.
- IPO allotment alerts.
- Historical GMP charts.
- IPO performance analytics.
- Investment calculators.
- IPO comparison tools.
- AI-powered IPO research and summaries.

---

**Project Name:** IPO Tracker  
**Application Type:** Financial Information & IPO Tracking Platform  
**Target Market:** Indian Stock Market  
**Supported IPO Categories:** Mainboard and SME
