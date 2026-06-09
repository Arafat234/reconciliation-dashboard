# Transaction Reconciliation Dashboard

An end-to-end reconciliation analytics project built in Excel and Power BI, 
modelled on operational workflows from Tier 1 financial institutions.

## Overview
Simulates a dual-system reconciliation process (System A vs System B) across 
60 transactions, with intentional mismatches introduced to reflect real-world 
break scenarios including amount mismatches, missing transactions, and 
currency discrepancies.

## Tools & Tech
- **Excel** — VLOOKUP, nested IFs, SUMPRODUCT, KPI calculation sheet
- **Power BI** — DAX measures, KPI cards, donut chart, transaction table
- **SQL** — underlying data querying and transformation logic

## Key Metrics Tracked
| KPI | Value |
|-----|-------|
| Match Rate | 86.67% |
| Break Rate | 13.33% |
| Total Breaks | 8 |
| Total Absolute Difference | $12,068 |
| Largest Single Mismatch | $10,723 |

## Context
Inspired by reconciliation system implementations I supported at Santander 
and Mizuho Financial Group as a Professional Services Consultant at Boundaryless.
