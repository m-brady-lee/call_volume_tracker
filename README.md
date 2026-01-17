# CALL VOLUME & INQUIRY TREND DASHBOARD

An interactive operational analytics dashboard designed to monitor inbound call volume, inquiry drivers, caller mix, and performance metrics over time. Built to support management reporting, early issue detection, and workload analysis in a regulated customer service environment.

## OBJECTIVE

Provide a centralized, filterable view of call activity that enables teams to identify emerging inquiry trends, monitor operational workload, and assess performance patterns across time periods and inquiry types.

## KEY QUESTIONS ANSWERED

What are the most frequent customer inquiries?

How has inquiry mix changed month over month (MoM)?

Which inquiry types are increasing or decreasing in volume?

How does call volume fluctuate by hour of day?

What is the breakdown of calls by caller type?

How do handle time and calls per day trend over time?

## DATA OVERVIEW

The dashboard aggregates inbound call records with attributes including:

Call date and time

Primary, secondary, and tertiary inquiry categories

Caller type

Handle time (mins:secs)

The date timeline supports:

Custom date ranges

Month-level filtering

Inquiry-level filtering for focused analysis

## ANALYSIS & ENGINEERING

Designed calculated metrics to track:

Total call volume

Average handle time

Calls per day

Inquiry-level call counts

Implemented Month-over-Month (MoM) % change logic to surface shifts in inquiry behavior and highlight emerging drivers before they appear in raw totals

Enabled inquiry-level drill-down analysis, allowing users to:

Select a specific inquiry

View call volume trends over time

Identify seasonality, spikes, or sustained increases

Built logic to surface operational signals tied to:

Workload distribution

Inquiry mix changes

Potential process or documentation gaps

## DASHBOARD FEATURES
### Inquiry Analysis

Bar chart highlighting most frequent primary inquiries

Inquiry volume comparison across time periods

MoM % change indicators to detect rising or declining inquiry types

### Caller Type Breakdown

Percentage-based visualization of calls by caller category

Helps identify shifts in who is contacting the organization and why

### Call Volume by Hour

Hourly trend analysis to identify peak call times

Supports staffing and capacity planning decisions

### Call Volume by Day

Daily trend analysis to monitor call volume spread across the week

### Performance Metrics

Average Handle Time (mins:secs)

Calls Per Day

Metrics update dynamically based on date and inquiry filters

### Interactive Filtering

Custom date range selection

Inquiry and User selection for focused trend analysis

## KEY INSIGHTS 

Certain inquiry categories consistently represent the largest share of inbound calls, indicating repeat friction points

Month-over-month changes reveal emerging inquiry drivers before they appear in raw totals

Call volume peaks during mid-day hours, aligning with staffing optimization opportunities

Inquiry-level trend analysis reveals seasonality for certain inquiries and enables targeted process / documentation improvements

## TOOLS & TECHNOLOGY

Visualization & BI: Excel (Dashboarding & calculated metrics)

Analysis: Pivot-based aggregations, calculated fields, MoM % change logic

Design: Interactive slicers, charts, and KPI cards

## SKILLS DEMONSTRATED

Operational metrics design

Call volume and workload analysis

Month-over-month trend analysis

Inquiry-level drill-down analytics

Dashboard design for management reporting

Translating raw call data into actionable insights

## SCREENSHOTS
![Call Capture](https://github.com/m-brady-lee/call_volume_tracker/blob/main/Call%20Capture%20-%20Anonymized.png)

![Dashboard](https://github.com/m-brady-lee/call_volume_tracker/blob/main/Dashboard%20-%20Anonymized.png)

![Inquiry Over Time](https://github.com/m-brady-lee/call_volume_tracker/blob/main/Inquiry%20Over%20Time%20-%20Anonymized.png)

## NOTES ON DATA USAGE

All data shown is sample and/or anonymized. No proprietary, sensitive, or personally identifiable information is included.

## FUTURE IMPROVEMENTS

Add rolling averages to smooth short-term volatility

Introduce alert thresholds for sudden inquiry spikes

Add comparison views across multiple months or quarters

## AUTHOR

Michael Lee
m.brady.lee@gmail.com
