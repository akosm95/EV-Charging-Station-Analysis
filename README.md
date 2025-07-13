Project Overview

This project analyzes the utilization and network growth of Electric Vehicle (EV) charging stations in Hungary. By combining open geospatial data, robust data cleaning, a geospatial-enabled Postgres database, and interactive Tableau dashboards, we provide actionable insights for network operators and policymakers to optimize EV infrastructure investments.

Workflow Summary

Data Acquisition
Open Charge Map dataset for Hungary is imported and raw data is explored.

Data Cleaning & Geo-Processing
Python + Pandas/GeoPandas notebooks clean the data, unify station IDs, and fill missing geocoordinates.

Database Loading
Cleaned data is loaded into a PostgreSQL database (with PostGIS for geospatial support) using both SQL scripts and Python ETL.

Data Analysis
PostgreSQL SQL scripts support time-series aggregation, pricing, geographic queries, and coverage analysis.

Interactive Visualization
Tableau dashboards provide geospatial drilldowns, KPI cards, and pricing/network growth analytics.
