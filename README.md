# Global Semiconductor Industry BI Dashboard

A 5-page Power BI dashboard analyzing the global semiconductor industry - market cap, financial performance, valuation, stock price history, and country-wise distribution.

## Overview

Combined 3 datasets covering 38 major semiconductor companies, daily stock price history from 2000-2026, and a global ranking of 358 companies. Reshaped a 195-column wide-format price table into long format using `pandas.melt()`, cleaned currency inconsistencies, and built the data model with 13 custom DAX measures.

## Pages

| Page | Highlights |
|---|---|
| **Executive Overview** | Total market cap ($4.15T), revenue, companies by category & country |
| **Financial Performance** | Revenue, profit margin, operating margin by company |
| **Market Valuation** | PE ratio, 52-week high/low, market cap distribution |
| **Stock Price Trends** | 2000-2026 price history, 228K daily records, company-level filtering |
| **Global Intelligence** | Country-wise rankings, top 20 companies globally |

## Key Insights

- NVIDIA leads at a **$1.18T market cap**, more than double the next closest competitor
- The semiconductor sector trades at an average **PE ratio of ~60**, well above the broader market's 20-25 range
- The **US dominates** global semiconductor market cap at **$2.59T** across 66 tracked companies

## Demo

See `Capstone_Project_2_Recording_Cropped.mp4` for a full walkthrough showing page navigation and live filtering, or browse `Capstone_Project2.pdf` for a static export of all 5 pages.

## Tech Stack

Power BI (DAX, Power Query) · Python (pandas) · Data Modeling

## Author

Raj Kumbhar - [LinkedIn](https://www.linkedin.com/in/raj-kumbhar-007b27211)
