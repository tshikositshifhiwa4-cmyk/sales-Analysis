# 📊 Retail Sales Case Study 

# Project Overview

This project analyses daily retail sales data for a single product to understand pricing behaviour, profitability, and the impact of promotional pricing. Using SQL, the study calculates key performance metrics such as daily unit price, gross profit percentages, and price elasticity of demand (PED). The project also identifies promotional periods and evaluates how price changes influence demand.

# Aim

To evaluate product performance by analysing sales, cost, and quantity trends while assessing how promotional pricing affects demand and profitability.

# Objectives

Calculate daily unit price and average unit sales price.

Compute daily gross profit % and daily gross profit per unit %.

Identify promotional periods where unit price decreases.

Analyse changes in price and quantity during promos.

Compute Price Elasticity of Demand (PED).

Interpret whether product demand is elastic or inelastic.

Provide actionable insights for pricing and promotion decisions.

# Methodology (Summary)

Imported the retail sales dataset into SQL for analysis.

Calculated:

Daily unit price = Sales ÷ Quantity Sold

Average unit sales price

Daily % Gross Profit = (Sales – Cost of Sales) ÷ Sales

Daily % Gross Profit per Unit

Identified promotional periods based on decreases in unit price.

Compared average quantity and price before vs. during promotions.

Calculated PED to determine demand sensitivity to price changes.

Joined daily results with monthly promo/regular averages for elasticity evaluation.

Generated final table including all dates, sales metrics, and elasticity values.

# Key Metrics Produced

sales_price_per_unit

avg_unit_sales_price

fraction_daily_gross_profit

fraction_daily_gross_profit_per_unit

promo_price vs regular_price

promo_quantity vs regular_quantity

price_elasticity

year, month, and complete daily records

# Technologies Used

SQL / Snowflake (data processing and calculations)

Excel / Numbers (final table review and charts)

Statistical concepts (elasticity, pricing analysis)

# Insights & Findings

Promotional periods resulted in clear price reductions but not always proportional increases in quantity.

Price elasticity varied across promo events, indicating mixed sensitivity of demand.

Gross profit % and gross profit per unit fluctuate significantly depending on daily volume and cost structure.

Daily metrics help isolate strong and weak performance days, informing pricing decisions.
