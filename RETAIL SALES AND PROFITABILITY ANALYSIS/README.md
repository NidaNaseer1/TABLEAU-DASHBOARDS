# Retail Sales & Profitability Analysis (Tableau)

An interactive **Tableau** dashboard that analyses retail sales and profit across categories, regions, segments and states, and shows how discounts affect profitability.

**Live dashboard:** https://public.tableau.com/views/Sales_17931172532170/Dashboard1?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Objective

To help a retail business understand where its sales come from and where it makes or loses profit, by answering questions such as:

- What are the total sales and total profit?
- Which product categories and sub-categories perform best?
- Which regions and states contribute the most?
- Do higher discounts reduce profit?

## Tools Used

- **Tableau Public / Tableau Desktop**: data connection, worksheets, dashboard design
- **Dataset:** Retail sales data from kaggle

## Dataset Fields Used

Order Date, Category, Sub-Category, Region, Segment, State/Province, Customer Name, Sales, Profit, Discount

## Dashboard Features

**KPI cards:** Total Sales, Total Profit

**Visuals**

- Sales by Category (packed bubble chart)
- Profit by Region (bar chart)
- Profit by Sub-Category (treemap)
- Discount vs. Profit (scatter plot)

**Filters:** Category, Order Date, Region, Segment, State/Province, Customer Name

## Key Insights

- **Sales by category:** Technology leads with **601,546**, followed by Furniture (**510,343**) and Office Supplies (**461,787**). Total across the three categories: **1,573,676**.
- **Profitable sub-categories:** Copiers (12,705) and Phones (1,069) are profitable.
- **Loss-making sub-categories:** Machines (-1,794) and Chairs (-31) show negative profit.
- **Discounts:** the Discount vs. Profit chart shows how profit changes as discounts increase. Add your observation here.

## Recommendations

- Reduce or review discounts on loss-making sub-categories (Machines, Chairs).
- Focus marketing and stock on high-performing categories and profitable sub-categories such as Copiers and Phones.
- Look into low-profit regions and states and plan region-specific strategies.

## How to View

1. Open the Tableau Public link above, or download `sales.twbx` and open it in Tableau Desktop / Tableau Public.
2. Use the filters to explore by category, region, segment, state or date.

