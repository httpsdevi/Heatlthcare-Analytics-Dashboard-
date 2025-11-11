# Healthcare Analytics Dashboard

## Overview

This project focuses on developing a **Healthcare Analytics Dashboard** using Microsoft Power BI to analyze and monitor key performance indicators (KPIs) in the healthcare domain. The dashboard provides actionable insights into patient wait times, case distribution, and specialty-level efficiency, enabling data-driven decision-making for hospital management and operations teams.

## Objectives

- Evaluate patient wait time trends across different specialties and age groups
- Identify operational bottlenecks impacting service delivery
- Enable dynamic exploration of healthcare performance metrics through interactive filters

## Key Features

### KPI Monitoring
- **Total Wait List**: Real-time tracking of patients awaiting service
- **Median Wait Time**: Central tendency measure for wait time analysis
- **Average Wait Time**: Mean wait time across all cases

### Interactive Analysis
- **Dynamic Filters**: Filter by Case Type, Specialty Name, and Age Profile
- **Time-Series Analysis**: Track trends in patient volume and efficiency over time
- **Visual Insights**: Compare specialties and monitor long-term patterns
- **Drill-Down Pages**: Investigate detailed metrics at case and department level

## Data Preparation

The data preparation process involved multiple stages to ensure data quality and consistency:

1. **Data Cleaning** (Excel & SQL)
   - Handled missing values and outliers
   - Standardized data formats across all fields
   - Validated data integrity and consistency

2. **Data Transformation**
   - Aggregated tables prepared for optimal Power BI modeling
   - Created calculated columns for enhanced analysis
   - Established relationships between data tables

## Tech Stack

| Technology | Purpose |
|------------|---------|
| **Power BI** | Dashboard design, data modeling, DAX measures |
| **Excel** | Data cleaning and transformation |
| **SQL** | Data extraction and aggregation |

## Insights Delivered

✅ Identified high-wait-time specialties and their year-on-year performance  
✅ Highlighted key trends in patient volume and service utilization  
✅ Enabled better resource allocation decisions through clear visual reporting  
✅ Provided actionable metrics for operational improvement initiatives

## Project Structure

```
Healthcare-Analytics-Dashboard/
│
├── Healthcare_Analytics.pbix          # Power BI report file
├── Dataset.xlsx                       # Cleaned dataset (Excel format)
├── Dataset.csv                        # Cleaned dataset (CSV format)
├── Dashboard_Screenshots/             # Visual overview of report pages
│   ├── overview_page.png
│   ├── detail_page.png
└── README.md                          # Project documentation
```

## Getting Started

### Prerequisites
- Microsoft Power BI Desktop (latest version recommended)
- Basic understanding of healthcare KPIs and metrics

### Installation Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/httpsdevi/healthcare-analytics-dashboard.git
   ```

2. **Open the Power BI file**
   - Navigate to the project folder
   - Open `Healthcare_Analytics.pbix` using Power BI Desktop

3. **Refresh the data** (if needed)
   - Click on "Refresh" in the Home ribbon
   - Ensure dataset files are in the correct directory

## Dashboard Usage

### Navigation
- Use the navigation buttons to switch between different report pages
- Apply filters from the filter pane to customize your view
- Click on visual elements to cross-filter related charts

### Key Metrics to Monitor
- **Wait List Trends**: Monitor patient volume changes over time
- **Specialty Performance**: Compare efficiency across different medical specialties
- **Age Group Analysis**: Understand demographic patterns in service demand

## Key Metrics & KPIs

| Metric | Description | Purpose |
|--------|-------------|---------|
| Total Wait List | Number of patients currently waiting | Capacity planning |
| Median Wait Time | Middle value of wait time distribution | Performance benchmark |
| Average Wait Time | Mean wait time across all cases | Overall efficiency indicator |
| Case Distribution | Breakdown by specialty and case type | Resource allocation |

## Future Enhancements

- [ ] Integration with real-time hospital management systems
- [ ] Predictive analytics for wait time forecasting
- [ ] Patient satisfaction correlation analysis
- [ ] Mobile-responsive dashboard version
- [ ] Automated alert system for threshold breaches

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For questions or feedback, please reach out:
- **Email**: your.email@example.com
- **LinkedIn**: [Deblina Mandal](https://www.linkedin.com/in/deblina-mandal-615507273/?originalSubdomain=in)
- **GitHub**: [httpsdevi](https://github.com/httpsdevi)

## Acknowledgments

- Hospital operations team for domain expertise
- Data analytics community for best practices
- Power BI community for visualization inspiration

---

**Note**: This dashboard is designed for educational and analytical purposes. Ensure compliance with healthcare data privacy regulations (HIPAA, GDPR, etc.) when working with real patient data.
