# Supply Chain Performance & Late Shipment Analysis

---

## Overview

This project analyzes supply chain performance with a focus on late shipments, SLA compliance, and operational bottlenecks. The goal was to identify root causes of delivery delays and provide KPI-driven insights to improve fulfillment efficiency and service reliability.

The analysis evaluates shipping performance across regions, ship modes, and operational metrics to support data-driven decision-making.

---

## Business Problem

Late shipments negatively impact customer satisfaction, increase operational costs, and reduce service-level agreement (SLA) compliance.

The business needed to understand:

- What is driving late shipment rates?
- Which regions or ship modes are underperforming?
- How fulfillment time impacts SLA compliance?
- Where operational bottlenecks exist?

Without structured KPI visibility, leadership could not identify performance gaps or prioritize corrective actions.

---

## Dataset

### Source
Simulated operational supply chain dataset representing order-level shipment activity.

### Size
- ~10,000+ order records  
- Multi-region shipment data  
- Historical time-based performance tracking  

### Key Fields

- Order ID  
- Order Date  
- Ship Date  
- Region  
- Ship Mode  
- SLA Target Days  
- Fulfillment Days  
- Late Shipment Flag  
- Sales  
- Profit  

---

## Tools Used

- SQL (Data extraction, joins, aggregations)
- Power BI (Data modeling, DAX measures, dashboard creation)
- Excel (Data validation and exploration)

---

## Key Analysis

- Late Shipment Rate by Month
- Late Shipment Rate by Region
- Late Shipment Rate by Ship Mode
- SLA Compliance Percentage
- Average Fulfillment Time
- Open Orders Impact Analysis
- Cause-and-effect relationship between fulfillment delays and SLA performance

---

## Metrics

- Total Orders  
- Late Orders  
- Average Fulfillment Days  
- SLA Target Days  
- Open Orders  
- Completion Rate  

---

## KPIs

- **Late Shipment Rate (%)**
- **SLA Compliance Rate (%)**
- **Average Fulfillment Days**
- **Completion Rate (%)**
- **Open Orders Volume**

These KPIs were designed to highlight operational risk and efficiency gaps.

---

## Logic

Operational Cause → Effect Flow:

Open Orders ↑  
→ Completion Rate ↓  
→ SLA Compliance ↓  
→ Late Shipment Rate ↑  

This structured KPI chain demonstrates how operational inefficiencies cascade into customer-facing performance issues.

---

## Results and Insights

- Identified specific regions with consistently higher late shipment rates.
- Certain ship modes showed significantly lower SLA compliance.
- Increased fulfillment days strongly correlated with late delivery risk.
- Operational bottlenecks were concentrated in high-volume periods.

The dashboard provides leadership with clear visibility into performance risk areas and supports proactive operational adjustments.

---

## Deliverables

- Executive Supply Chain Dashboard (Power BI)
- Structured KPI Framework
- Performance Trend Analysis
- Root Cause Breakdown

---

## Screenshots

Include:

- KPI Overview Dashboard
- Late Shipment Trend Analysis
- Regional Performance Breakdown
- Ship Mode Comparison
- SLA vs Late Rate Scatter Plot

---

## Files

- Power BI Report File (.pbix)
- SQL Query Scripts
- Cleaned Dataset (if permitted)
- Documentation Notes

---

## Links

- Dashboard Repository: [Insert Repository Link]
- Power BI File (if hosted): [Insert Link]
- Additional Documentation: [Insert Link]

---

## What I Learned

- The importance of structuring KPIs around cause-and-effect relationships.
- How operational metrics directly influence customer satisfaction indicators.
- The value of designing dashboards that move beyond reporting into decision support.
- The impact of clean data modeling on accurate performance measurement.
