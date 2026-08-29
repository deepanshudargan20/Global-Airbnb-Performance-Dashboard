# Global Airbnb Performance Dashboard

An interactive Power BI dashboard analyzing Airbnb listings, pricing, guest reviews, cities, room types, property types, and host trust indicators.

## Dashboard Pages

### 1. Global Airbnb Performance Dashboard
- Average Rating
- Average Price
- Total Cities
- Total Hosts
- Total Listings
- Total Reviews
- Listings by City
- Top Property Types
- Room Type Distribution
- Listings by Location

### 2. Pricing & Guest Rating
- Average Price by room type
- Average Rating
- Average Monthly Price by City
- Average Rating by City
- Price vs Rating
- Superhost vs Non-Superhost Listings
- Rating Distribution

### 3. Reviews & Host Trust
- Total Reviews
- Unique Reviewers
- Guests with 3 or Fewer Reviews
- Guests with Exactly 1 Review
- Hosts with Verified ID & Profile Photo
- Hosts with Neither ID nor Profile Photo
- Reviews Over Time
- Reviews by Year
- Review Frequency
- Host Identity Verification
- Host Profile Picture

### Additional Learning Page — Review Seasonality
A separate page was created to practice a Matrix heatmap because fitting every visual into one dashboard page would reduce readability.

It contains:
- Review Seasonality (Share of Monthly Reviews)
- Top 5 Cities
- Monthly review-share heatmap from January to December

## Tools & Techniques
- Microsoft Power BI Desktop
- Power Query
- DAX
- KPI cards
- Bar, line, area, donut and scatter charts
- Matrix heatmaps
- Conditional formatting
- Top N filtering
- Distinct-count calculations
- Interactive slicers
- Dashboard navigation

## Data Model
The report combines listings and reviews information to analyze listing, host, city, room-type, property-type, pricing, rating and review behavior.

## Repository Structure

```text
Global-Airbnb-Performance-Dashboard/
├── README.md
├── Screenshots/
│   ├── overview.png
│   ├── pricing-rating.png
│   ├── reviews-host-trust.png
│   └── review-seasonality.png
└── DAX/
    └── measures.txt
```

## Power BI File
The `.pbix` file is approximately 175 MB, so it is hosted separately rather than stored directly in this GitHub repository.

**[Download the Power BI PBIX file](https://drive.google.com/file/d/1kEiyMuX9zpuRkVMqGAcP6EhDBiIeEebO/view?usp=drive_link)**

The PBIX is shared from Google Drive as a separate portfolio download. GitHub is used for the project documentation, screenshots and DAX.

## Project Status
Completed dashboard project. Future improvements may include advanced tooltips, dynamic titles and additional analytical measures.
