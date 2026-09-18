# MISUO Furniture Dashboard

Excel dashboard I built while doing the Mazen Analytics diploma, using MISUO's furniture sales data.

## Tools
Excel, Power Query, Power Pivot, DAX, Slicers, KPI Cards

## What the data looked like
The raw data had two main problems. First, product categories weren't consistent — same category written in different ways in Arabic across rows. Second, there were duplicate orders and some empty fields in the region and delivery status columns. I used Power Query to clean all of that up and get the categories into one consistent format before building anything on top of it.

## Why I designed it this way
I put the KPI cards at the top because those are the numbers anyone opening the dashboard wants to see first — total sales, orders, best seller, etc. For delivery status specifically I went with a pie chart instead of bars, because it makes the split between the three statuses easier to read at a glance than a bar chart would.

## What I found
The thing that stood out most to me was the delivery numbers. Only 35.7% of orders got delivered on time. 42.9% never got delivered at all, and the rest (21.4%) arrived late. So basically less than half of the orders actually made it to the customer properly — that's a real problem for the business, not just a stat.

Cairo also stood out — it had 56 out of the ~126 total orders, way more than any other region. And on the sales side, one platform (هوم مارت) brought in 78 orders on its own, more than all the other channels combined.

سرير (beds) was the best-selling category, and أبيض (white) was the most popular color.

## My take
If I were advising MISUO, I'd say the delivery issue in Cairo specifically needs to be looked at before spending more on marketing there — there's no point bringing in more orders to a region where almost half of them aren't reaching customers anyway.

## Dashboard
![MISUO Dashboard](C:\Users\ahmed\OneDrive\Desktop\images/misuo-dashboard.png)
