
# 🎬  Web Series Ratings & Revenue Dashboard


## 1.  Project Heading
• Web Series Ratings & Revenue Dashboard — An Analytics Solution for OTT Platform Performance Tracking.


## 2.  Short Description
• This Excel dashboard analyses 500 web series across five OTT platforms and five global industries.

• It tracks viewer ratings, revenue, profit, genre performance, and platform-wise comparisons — enabling content teams and business analysts to identify top-performing series, understand audience preferences, and drive data-informed content investment decisions.
## 3. Tech stack Tools and technologies used
📊 Microsoft Excel.

📈 Pivot Tables & Pivot Charts. 

⚙️ Power Query.

🧰 Excel Formulas (SUMIF, COUNTIF, AVERAGEIF) 

🌟 Conditional Formatting 

📋 Data Validation & Slicers 

📄 Data Modeling (multi-sheet relationships) 
## 4. Data Source

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| S.No | ![#0a192f](https://dummyimage.com/10/0a192f/white?text=+)Serial number (row identifier).|
| Release Date | ![#f8f8f8](https://dummyimage.com/10/f8f8f8/white?text=+)Date the series was released on the platform .    |
| Industry. | ![#00b48a](https://dummyimage.com/10/00b48a/white?text=+)Content origin — Bollywood, Hollywood, Tollywood, Chinese, Japanese  .|
|Web Series Name | ![#00d1a0](https://dummyimage.com/10/00d1a0/white?text=+)Title of the web series.|
|Genre | ![#00d1a0](https://dummyimage.com/10/00d1a0/white?text=+)Content genre — Action, Comedy, Drama, Horror, Crime, Thriller, Fantasy, Romance.|
|Rating (1-5)| ![#00d1a0](https://dummyimage.com/10/00d1a0/white?text=+)Viewer rating on a scale of 1 to 5.|
|Review| ![#00d1a0](https://dummyimage.com/10/00d1a0/white?text=+)Qualitative label — Poor, Average, Good, Must Watch.|
|Platform| ![#00d1a0](https://dummyimage.com/10/00d1a0/white?text=+)OTT platform — Netflix, Hotstar, Amazon Prime, SonyLIV, Jio Cinema.|
|Viewers (Millions)| ![#00d1a0](https://dummyimage.com/10/00d1a0/white?text=+)Total number of viewers in millions.|
|Price Per Viewer (₹)| ![#00d1a0](https://dummyimage.com/10/00d1a0/white?text=+)Revenue earned per viewer in Indian Rupees.|
|Total Sales (₹ Crore)| ![#00d1a0](https://dummyimage.com/10/00d1a0/white?text=+)Total sales revenue per series.|
|Profit (₹ Crore)| ![#00d1a0](https://dummyimage.com/10/00d1a0/white?text=+)Net profit per series.|
## 5.  Business Problem
OTT platforms and content producers face key challenges without a structured analytics view:

•	No clear visibility into which genres, industries, or platforms generate the most revenue and profit.

•	Difficulty comparing viewer engagement (ratings and viewership) across different content categories.

•	Inability to identify underperforming series or platforms that need strategy changes.

•	Lack of insight into how release timing (month/year) affects viewership and sales.

•	Manual data review across 500 entries is time-consuming and error-prone without a dashboard.

## 6.  Insights/Goals of the Dashboard
The key goals of this dashboard are:

•	Provide a quick overview of total sales (₹4,509 Cr), total profit (₹1,803 Cr), and average rating (4.01) across all 500 series.

•	Compare OTT platform performance — SonyLIV leads with ₹974 Cr in total sales.

•	Identify top-performing industries — Hollywood contributes the highest revenue at ₹1,848 Cr.

•	Analyse genre-wise and review-wise distribution to guide future content commissioning.

•	Track viewer trends over release dates to detect seasonal patterns.

•	Enable quick filtering and sorting by platform, industry, genre, rating, or review label.

## API Reference

#### Get all items

```http
  GET /api/items
```

| 📊  Bar Chart  | 
| :--------|
  Compares total sales revenue across Netflix, Hotstar, Amazon Prime, SonyLIV, and JioCinema. |



| 🥧  Pie Chart   | 
| :--------|
  Shows percentage share of total sales by content origin — Hollywood, Bollywood, Tollywood, Chinese, Japanese. |


|  📈  Line Chart   | 
| :--------|
  Tracks total sales over time to identify seasonal and monthly content performance trends. |



|  📉  Column Chart   | 
| :--------|
   Displays revenue contribution of each genre: Action, Comedy, Drama, Horror, Crime, Thriller, Fantasy, Romance|


|  ⭐  Rating Distribution Chart  | 
| :--------|
   Visualises how series are spread across ratings 1–5 and review labels (Poor to Must Watch).|

|  🔢  KPI Summary Cards  | 
| :--------|
  Shows headline numbers: Total Sales, Total Profit, Total Viewers, and Average Rating at a glance. |

|  🗂️  Pivot Table — Platform vs Genre  | 
| :--------|
  Cross-tab of platform and genre to reveal which genre performs best on each OTT platform. |

|  🎛️  Slicers / Filters  | 
| :--------|
   Interactive filters by Platform, Industry, Genre, and Rating for self-service exploration.|
##  8.  Key Questions the Dashboard Answers
•	Which OTT platform generates the highest total sales and profit?

•	Which industry (Hollywood, Bollywood, etc.) produces the most-watched and highest-revenue series?

•	What genres are most popular by viewership and revenue?

•	How does the average viewer rating vary across platforms and industries?

•	Which series have the highest number of viewers and total sales?

•	What is the distribution of reviews — how many series are rated 'Must Watch' vs 'Poor'?

•	Are there seasonal trends in series releases that affect viewership?

•	What is the relationship between Price Per Viewer and Total Profit?

## 9.  Conclusion

• This dashboard turns 500 rows of raw OTT data into clear insights on revenue, ratings, and platform performance. 

• It helps stakeholders quickly identify what content works, which platforms lead, and where to invest next.

## 10. ScreenShot/Demo
<img width="1309" height="533" alt="snap_short Web Series Rating   Revenue Dashboard screen short" src="https://github.com/user-attachments/assets/a12f8640-d1ab-4823-b7bd-5157d2a604d3" />

