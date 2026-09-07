HDFC Bank – Personal Loan Sales Performance Dashboard
Overview

This Excel workbook tracks the daily sales performance of the Personal Loan sales team for HDFC Bank. It consolidates individual executive-level sales data into an interactive dashboard that highlights top and bottom performers, making it easy for sales managers to monitor productivity, identify coaching opportunities, and recognize high achievers.

File Structure

The workbook contains two sheets:

1. Row Data

The raw data sheet — one row per sales executive. Columns include:

Column	Description
Emp Code	Unique employee identifier (e.g. Mum-TCL001)
Sales Executive	Employee name
Region	Branch/region (Mumbai, Delhi, Nagpur, Chennai, Pune, Patna, Ranchi, Surat)
Day1–Day5	Number of personal loan sales made each day over a 5-day tracking window
Total Sales	Sum of Day1–Day5
Target	Sales target per executive (fixed at 500)
Target Hit %	Total Sales ÷ Target
Away From Target %	Percentage shortfall from target (1 − Target Hit %)

This sheet holds data for 141 sales executives across 8 regions.

2. Dash Board

A summary view built on top of the raw data, using pivot tables, slicers, and charts to surface:

Top 5 Sales Executives — ranked by Total Sales
Bottom 5 Sales Executives — ranked by Total Sales
Target Achievement % — executives ranked by highest Target Hit %
Away From Target % — executives ranked by largest shortfall from target
Purpose

The dashboard is intended as a quick management tool to:

Spot top-performing sales executives for recognition or incentive programs
Flag underperforming executives who may need additional training or support
Compare performance across regions and individuals over the tracking period

How to Use
Open the Dash Board sheet for the at-a-glance summary view.
Use the slicer(s) to filter by region or other available dimensions.
Refer to the Row Data sheet for the underlying daily figures behind any summary number.
Pivot tables and charts can be refreshed (right-click → Refresh) if the underlying Row Data is updated.

Notes / Assumptions
The daily sales target appears fixed at 500 per executive across the tracking window.
"Day1"–"Day5" represent a 5-day sales tracking cycle (exact calendar dates are not specified in the sheet).
Employee codes follow a regional prefix pattern (e.g. Mum-TCL0xx) though the code prefix does not always match the listed region — worth verifying against source HR/sales records if used for official reporting.

📌 Disclaimer: This project uses a simulated dataset created solely for learning and demonstration purposes, and does not reflect actual data, figures, or operations of any organization.
