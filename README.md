# Coca-Cola Company Sales Analysis 2022.Coca-
# Power BI Dashboard Review & Business Insights 
# Data from the "Sales Made by Coca-Cola Company in 2022” by Junior Owusu Ansah


 <img width="875" height="619" alt="image" src="https://github.com/user-attachments/assets/e40c33cc-ed1e-4d36-8f52-2f572b4b391d" />

Figure 1. Full Power BI dashboard.



1. Executive Summary

The Dashboard compares Coca-Cola Company's 2022 sales by beverage brand, retail partner, shipping carrier, U.S. region and states. High level, it had $8.22M in total sales and 16.48M units sold, which equates to a $3.04M operating profit and implied operating margin of about 37%. A fourth KPI card ("1.37K, Sum of Operating…") is missing a portion of the word in the source export and the definition of this KPI (which was most likely an operating metric like cost per unit or margin index) cannot be confirmed from the file provided. The results reveal three patterns. (1) Coca-Cola's product outsells all other products in the portfolio, and Fanta is the least profitable product, with Walmart's profits being nearly as low as Fanta's; (2) Walmart is overwhelmingly the largest retail channel by units sold and operating profit, significantly outpacing CVS, Costco, and Target combined; and (3) sales and profit are volatile in the near daily sense of the word year-round with a visibly denser and higher peak appearing in the mid-to-late year months in alignment with beverage demand seasonality during the warm months.


 <img width="625" height="350" alt="image" src="https://github.com/user-attachments/assets/c4b82801-4aed-44bd-b85f-008a1863fa23" />

Figure 2. Top-line KPI cards: Total Sales, Units Sold, Operating Profit, and an unlabeled fourth metric.



<img width="1067" height="592" alt="image" src="https://github.com/user-attachments/assets/dc37fc3f-576f-445e-a811-dfda67be94ed" />





2. Top Beverage Brands by sales

Coca-Cola is the clear volume leader, and Dasani Water, Diet Coke, Sprite and Powerade are the other leading products. Fanta is confirmed as the lowest profit-making brand elsewhere on the dashboard.


 <img width="625" height="338" alt="image" src="https://github.com/user-attachments/assets/4bc501d6-9d00-4df5-aa20-41ede4ab131d" />

Figure 3. Units sold by beverage brand (top 5 shown).



<img width="1067" height="476" alt="image" src="https://github.com/user-attachments/assets/a7822f50-66cd-4282-abd4-d76efe51623e" />




The profit side of this story is evident directly on the dashboard: "Coca-Cola had the highest Sum of Operating Profit at $767,510.38, which was 115.78% higher than the lowest Sum of Operating Profit at $355,685 for Fanta, representing a 25.24% share of Sum of Operating [Profit]…"


 <img width="594" height="483" alt="image" src="https://github.com/user-attachments/assets/205eaf9a-52a2-4613-960c-436eb38b3eff" />
 
Figure 4. Dashboard's auto-generated narrative insight on brand profitability (truncated in source).


The portfolio covers at least 6 brands, but the operating profit is dominated by Coca-Cola because of the low volume concentration; flat/still water (Dasani) and diet cola are not bad sellers and probably have lower margins.


 <img width="594" height="397" alt="image" src="https://github.com/user-attachments/assets/b690218f-75a6-4f78-a208-c689b2ef5632" />
 
Figure 5. Units sold, total sales, and operating profit trend across brands (Coca-Cola → Fanta).



3. Sales & Profit by Retailer
   
Walmart leads the pack by a significant margin in each category, with CVS being the next largest, Costco being further behind, and Target holding the bottom spot in each category, according to all metrics measured units sold, total sales, and operating profit.


 <img width="594" height="324" alt="image" src="https://github.com/user-attachments/assets/52a3164b-ea0b-40c0-ab1f-f08779532926" />
 
Figure 6. Operating profit, total sales, and units sold by retailers (Walmart → Target).


 <img width="500" height="389" alt="image" src="https://github.com/user-attachments/assets/65874652-ad72-4c6c-9f34-df6249493068" />
 
Figure 7. Share of operating profit by retailer.



<img width="1067" height="516" alt="image" src="https://github.com/user-attachments/assets/e1beb43a-e167-4d07-a164-934fa26ce11c" />




This trend is reflected in the "Sales by Retailers Group Under Suppliers" cross tab below, which crosstabs each retailer by the four shipping carriers (DHL, FedEx, UPS, USPS): Walmart's bars are about twice as tall as CVSs, and about three times as tall as Costco's in each column, so the retailer concentration isn't an artifact of anyone shipping relationship.


<img width="625" height="508" alt="image" src="https://github.com/user-attachments/assets/6f784f79-c71e-4418-a180-73afd58e7235" />

Figure 8. Sales by retailer, split by shipping carrier (DHL, FedEx, UPS, USPS).




4. Geographic Distribution

The remaining slices are labeled in the source file, but some labels are not shown here, with the West region being confirmed at $542.05K (17.82% of total operating profit) and two additional regions at approximately $641.5K (17.1%) and $790K (25%) respectively. In addition to the visible figures, the pattern shows the profit is split relatively evenly between regions (whereas at Walmart, the pattern is that one region enjoys a runaway majority).



 <img width="625" height="464" alt="image" src="https://github.com/user-attachments/assets/106010e1-7c2c-4235-80b3-945a5ab06d0c" />
 
Figure 9. Operating profit by U.S. region.


It's a tree map at the state level, where units/sales are grouped into individual states, which are initially visible as California, Florida, New York and Texas, and some other states are also available as color blocks. This means that Coca-Cola's retail presence in the dataset in 2022 is not limited to a few states, and is a national presence, as is evident in the relatively even split of the profit pie chart across the regions.


 <img width="594" height="545" alt="image" src="https://github.com/user-attachments/assets/d5d8a824-5999-43d3-9249-65f92b569615" />
 
Figure 10. Distribution of sales/units by U.S. state (tree map).


5. Logistics: Delivery Carriers
6. 
The various shipping carriers that you can find next to the dashboard are USPS, DHL, FedEx and UPS. Within each carrier's regional split (Midwest, Northeast, South and a fourth region, which in the legend is shorted to West, but presumably to the West), the split is pretty even across all the regions, ranging from about 0.7M to 1.1M units per region, with the West/4th region always being the highest bar for each carrier. There's no obvious leader (all four are in a similar range to each other), other than Coca-Cola's thirst for spreading its shipping risk around instead of depending on any single logistics partner.


 <img width="531" height="548" alt="image" src="https://github.com/user-attachments/assets/54454214-9969-4508-8854-54f8b057dc00" />
 
Figure 11. Delivery volume by carrier and region.


6. Sales & Operating Profit Trend Over 2022

The timeseries graph is a chart that shows Total Sales as well as Operating Profit, both on a daily (not monthly) basis from Jan-Dec 2022. The two stand out are: (1) Operating Profit tracks consistently below and smoother than Total Sales over the course of the year, as would be expected, since profit is a portion of gross sales; (2) both series exhibit significantly larger, denser peaks from about mid-year through the early autumn months, followed by the smaller January-April peaks, which is consistent with the higher demand for beverages during the warmer months (a common seasonal pattern for carbonated soft drinks and sports drinks like Powerade).


 <img width="625" height="444" alt="image" src="https://github.com/user-attachments/assets/4d8b9f9c-2b9c-4220-a1ec-89ff96f9ad4c" />
 
Figure 12. Daily total sales and operating profit, Jan 2022 - Dec 2022.



7. Conclusions & Recommendations

●	Retail performance – measured here in 2022 is highly dependent on the performance of one retailer: Walmart is apparently responsible for about half or more of units sold, sales and operating profit. The price or shelf space shift at Walmart would have a disproportionate effect compared to the combined effect of CVS and Costco or Target test this in future planning.

●	Coca-Cola-brand product is faring better than the other product lines in terms of the return on investment, with 25%+ of operating profit coming from one SKU family, compared to the other product lines. This is a good reason to consider the possibility of revisiting Fanta pricing, distribution expenses or promotional budget assuming volume leads to profits is a dangerous practice.

●	Unlike the retailer concentration mentioned above, geographic concentration is not a significant risk in this data set as operating profit is divided up evenly between the regions, and sales are distributed nationally at a state level.

●	Clear mid-year sales and profit swings favor the development of inventory, staff, and promotional plans for a spring build-up to a summer/early fall peak.

●	Diversified logistics: Operating strength carrier volumes balanced across USPS, DHL, FedEx and UPS, this does not need to be rebalanced based on this data.


