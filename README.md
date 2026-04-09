# 🎮 Gaming Industry SQL Analysis

## Overview
A data analysis project focused on uncovering insights from a game development company's dataset. The analysis was performed using **MySQL Workbench** and covers revenue performance, player engagement, and publisher metrics across multiple game titles and genres.

## Dataset
Three relational tables were imported and analysed:
- `games_description` — game metadata including genre, publisher, and release year
- `games_revenue` — sales data with unit prices and purchase counts
- `games_reviews` — player feedback, engagement hours, and review counts

## Tasks Completed
- **Data Cleaning** — corrected genre inconsistencies prior to loading into MySQL
- **Database Setup** — created a `games` schema and imported all datasets using the Table Data Import Wizard
- **Data Analysis** — used SQL joins and aggregate functions to calculate total revenue, review percentages, English review breakdowns, publisher rankings, and engagement ratios
- **Advanced SQL** — applied `RANK()` window functions to rank games by revenue and reviews within each genre
- **Reporting** — compiled findings into a structured report covering revenue insights, review analysis, publisher performance, and actionable recommendations

## Tools & Skills
`MySQL` · `SQL Joins` · `Window Functions` · `Data Cleaning` · `Aggregate Functions`
