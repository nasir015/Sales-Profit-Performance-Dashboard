# 📊 Sales Dashboard | Tableau Project

An interactive **Sales & Profit Performance Dashboard** built in Tableau, following a structured BI development process. The dashboard enables business stakeholders to monitor KPIs, analyze subcategory-level performance, and track sales and profit trends over time with year-over-year comparisons.

---

## 🖼️ Dashboard Preview

![Sales Dashboard](Screenshot%20of%20Sales%20Dashboard.png)

🔗 **[View Live on Tableau Public](https://public.tableau.com/app/profile/md.nasir.uddin7431/viz/Salesdashboardpractice_17420653138460/SalesDashboard)**

---

## 📌 Project Overview

This project demonstrates a complete BI dashboard development workflow — from requirements analysis and data modelling through to chart building and final dashboard assembly — using Tableau as the primary tool.

### Key Features

- **KPI Summary Cards** — Total Sales, Total Profit, and Total Quantity with sparklines and year-over-year (YoY) variance indicators
- **Sales & Profit by Subcategory** — Dual horizontal bar chart with profit/loss color coding across all product subcategories
- **Trends over Time** — Dual time-series chart with average reference lines for both sales and profit
- **Dynamic Filters** — Interactive icon-based filter panel (Category, Sub-Category, Region, City)
- **Highest/Lowest Month Highlights** — Automatic dot markers for peak and lowest performing months

---

## 🗂️ Repository Structure

```
├── Dashboard Icons/              # Custom icons used in the Tableau dashboard
├── EU-Dataset/                   # Dataset for EU region
├── Non-EU Dataset/               # Dataset for non-EU region
├── Sales dashboard practice.twb  # Tableau workbook file
├── Screenshot of Sales Dashboard.png  # Dashboard preview image
├── Section-15-_-Tableau-Project.pdf   # Project brief and design process guide
├── LICENSE                       # License file
└── README.md                     # Project documentation
```

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Tableau Desktop** | Dashboard and visualization development |
| **Tableau Public** | Publishing and sharing the live dashboard |
| **CSV / Excel** | Source data (EU and Non-EU datasets) |
| **Draw.io** | Mockup and container layout planning |

---

## ⚙️ Dashboard Design Process

This project follows a professional 4-step BI dashboard design methodology:

### Step 1 — Analyse Requirements
- Collected user story and business requirements
- Selected appropriate chart types
- Drew dashboard mockups
- Chose color palette

### Step 2 — Build Data Source
- Connected and joined EU and Non-EU datasets
- Created data model and verified relationships
- Renamed fields and tables for clarity
- Checked and corrected data types

### Step 3 — Build Charts
- Created calculated fields (YoY variance, profit flags, averages)
- Built and formatted individual visualizations
- Cleaned up axes, headers, and gridlines
- Applied consistent coloring and tooltips

### Step 4 — Build Dashboard
- Designed container structure (vertical main + horizontal sub-containers)
- Assembled all charts into a unified layout
- Added dynamic filters, icons, legends, and padding
- Published to Tableau Public

---

## 📈 Key Metrics (2022)

| Metric | Value | vs. Prior Year |
|--------|-------|---------------|
| Total Sales | $609K | ▲ 29.5% |
| Total Profit | $82K | ▲ 32.7% |
| Total Quantity | 10K units | ▲ 23.3% |

---

## 🚀 Getting Started

1. Clone this repository
   ```bash
   git clone https://github.com/nasir015/sales-dashboard
   ```
2. Open `Sales dashboard practice.twb` in **Tableau Desktop**
3. Ensure the EU and Non-EU datasets are correctly linked from the `/EU-Dataset/` and `/Non-EU Dataset/` folders
4. Explore the dashboard or publish to your own Tableau Public profile

> **Note:** Tableau Desktop (or Tableau Public Desktop) is required to open `.twb` files locally.

---

## 📄 License

This project is licensed under the terms in the [LICENSE](LICENSE) file.

---

## 🔗 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/md-nasir-uddin-620942336/)
[![Tableau Public](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)](https://public.tableau.com/app/profile/md.nasir.uddin7431)
