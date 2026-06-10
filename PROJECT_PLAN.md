# Foodbasket Analytics Project Plan

## Project Overview

Foodbasket Analytics is a data analytics project focused on analysing the cost of essential food items and understanding food affordability pressure through basket-level pricing, category contribution, and dashboard-based insights.

## Project Scope

Foodbasket Analytics will analyse the cost of a basic student food basket in Malaysia using item-level grocery price data. The project will focus on understanding total basket cost, category-level cost contribution, and basic affordability pressure.

The first version of the project will use manually collected grocery price data from selected supermarket or online grocery sources. The project will begin with one store/source and may later expand to compare prices across multiple stores.

## Main Research Question

How much does a basic student food basket cost, and which food categories contribute most to the total cost?

## Target User

The target users are students and young adults in Malaysia who want to understand the cost of essential food items and how different food categories contribute to monthly grocery spending.

This project may also be useful for individuals interested in basic food affordability, cost-of-living analysis, and household budgeting.

## Initial Food Basket Category Structure

The first version of the food basket will use the following categories:

| Category | Purpose | Example Items |
|---|---|---|
| Staples | Main carbohydrate and base meal items | Rice, bread, noodles, pasta |
| Protein | Common protein sources | Dhal, tofu, eggs |
| Vegetables | Common cooking vegetables | Onion, tomato, potato, carrot |
| Dairy | Basic dairy items | Milk, yogurt |
| Cooking Basics | Items needed for regular cooking | Cooking oil, sugar, salt |
| Beverages / Extras | Optional but common student items | Tea, coffee |

## Planned Analysis

1. Calculate the total cost of the selected food basket.
2. Calculate category-level contribution to total basket cost.
3. Identify the most expensive items and categories.
4. Compare basket cost across stores if multiple stores are added later.
5. Create dashboard views to communicate the findings clearly.
6. Summarise key insights, limitations, and possible improvements.

## Planned Dashboard Sections

1. Basket Overview
2. Category Breakdown
3. Item-Level Price Table
4. Store Comparison
5. Key Insights

## Planned Tools

- Python
- Pandas
- Excel / CSV
- Streamlit
- GitHub

## Expected Outputs

- Raw food price dataset
- Cleaned food price dataset
- Exploratory data analysis notebook
- Basket-level cost metrics
- Category contribution analysis
- Interactive dashboard
- Final project insights and documentation

## Milestone Structure

### 1. Project Foundation

- Create GitHub repository
- Set up project folder structure
- Add README.md
- Add PROJECT_PLAN.md
- Define project scope and target user
- Decide initial food basket category structure

### 2. Dataset Design & Data Collection

- Create raw food price dataset template
- Define food basket items
- Define item categories
- Select first grocery price source
- Collect initial food price data
- Add source URLs and notes
- Validate collected item prices

### 3. Data Cleaning & Preparation

- Load raw dataset in Python
- Check missing values
- Standardise item names and categories
- Fix data types
- Create processed dataset
- Export cleaned dataset
- Document data cleaning steps

### 4. Exploratory Data Analysis

- Calculate total basket cost
- Calculate category-level cost contribution
- Identify most expensive items
- Create category breakdown chart
- Create item price comparison chart
- Create basket summary metrics
- Write initial EDA insights
- Save charts to outputs folder

### 5. Dashboard Development

- Create Streamlit dashboard app
- Build basket overview section
- Build category breakdown section
- Build item-level price table
- Add filters for category and store
- Add key insight cards
- Improve dashboard layout and styling
- Test dashboard locally

### 6. Portfolio Case Study & Final Documentation

- Update README with final project details
- Add dashboard screenshots
- Write final project insights
- Document limitations
- Document future improvements
- Prepare portfolio case study content
- Add GitHub project progress tracker to website
- Add live dashboard link if deployed

## Notes

This project should start simple and expand gradually. The first version should focus on building a clean dataset, calculating basket cost, and showing category-level contribution. Forecasting or advanced analytics can be added later after the core project is working.
