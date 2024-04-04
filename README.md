# AtliQ-Hardware-Sales-Finance-Analysis <img src='https://github.com/ShailajaSirumalla22/Excel-Sales-and-Finance-Report/blob/main/atliq_logo.png' width='40'>

AtliQ Hardware is a company that supplies computer hardware and peripherals to clients across the world.

## Project Overview:

AtliQ Hardware has over half a million records of unorganized sales and finance data. AtliQ aims to optimize sales by identifying growth opportunities and making effective financial decisions. The objective of the project is to analyze the sales and financial data with the help of Excel and create Sales and Finance-related reports to help the AtliQ sales and finance team make data-driven decisions that help them boost the company's performance.

## Approach:

Using advanced Excel tools like Power Query and Power Pivot to analyze the data and create reports.

**1. Power Query**
  + For data extraction, transformation and loading (ETL) from various sources.
  + For comprehensive data cleaning

**2. Power Pivot**
  + For data modeling
  + Creating Key Performance Indicators (KPIs) using DAX

## Reports

### Sales Analysis Reports

1. [Customer Performance Report: Net Sales](https://github.com/ShailajaSirumalla22/Excel-Sales-and-Finance-Report/blob/main/Sales%20Performance%20Analysis/Customer%20Performance%20Report%20-%20Net%20Sales.pdf) - Analyse net sales of customers over the years
2. [Market Performance Vs Target](https://github.com/ShailajaSirumalla22/Excel-Sales-and-Finance-Report/blob/main/Sales%20Performance%20Analysis/Market%20Performance%20Vs%20Target.pdf) - Analyse country-wise performance against the target over the years
3. [Top 10 Products Performance](https://github.com/ShailajaSirumalla22/Excel-Sales-and-Finance-Report/blob/main/Sales%20Performance%20Analysis/Top%2010%20Products%20Performance.pdf) - Analyse top 10 products based on the sales over the years
4. [Top and Bottom 5 Products](https://github.com/ShailajaSirumalla22/Excel-Sales-and-Finance-Report/blob/main/Sales%20Performance%20Analysis/Top%20n%20Bottom%205%20Products%20by%20Qty.pdf) - Analyse top and bottom 5 products based on the quantity sold over the years 

- **Purpose of sales analysis -** Empower businesses to monitor and evaluate their sales activities and performance

- **Importance of analyzing sales data -** Identify sales patterns and track key performance indicators (KPIs)

- **Role of reports -** Determine effective customer discounts, facilitate negotiations with consumers, and identify potential business expansion opportunities in promising countries

### Finance Analysis Reports

1. [P & L by Fiscal Year](https://github.com/ShailajaSirumalla22/Excel-Sales-and-Finance-Report/blob/main/Finance%20Analysis/P%20%26%20L%20by%20Fiscal%20Year.pdf) - Analyse profit and loss based on the fiscal years
2. [P & L by Fiscal Months](https://github.com/ShailajaSirumalla22/Excel-Sales-and-Finance-Report/blob/main/Finance%20Analysis/P%20%26%20L%20by%20Fiscal%20Months.pdf) - Analyse profit and loss based on the fiscal months
3. [P & L by Markets](https://github.com/ShailajaSirumalla22/Excel-Sales-and-Finance-Report/blob/main/Finance%20Analysis/P%20%26%20L%20by%20Markets.pdf) - Analyse profit and loss based on markets
4. [GM % by Quarters for Sub Zones](https://github.com/ShailajaSirumalla22/Excel-Sales-and-Finance-Report/blob/main/Finance%20Analysis/GM%20%25%20by%20Quarters%20for%20Sub%20Zones.pdf) - Analyse gross margin % by quarters for the zones

- **Purpose of sales analytics:** Evaluation of financial performance, support decision-making, and facilitate communication with stakeholders

- **Importance of analyzing Finance data:** Aid in benchmarking against industry peers and previous periods Foundation for budgeting and forecasting

- **Role of reports:** Align financial planning with strategic goals Instill confidence in the organization's financial outlook

## Key Learnings & Skills:

+ Functional Knowledge: Sales and Finance domain expertise
+ ETL Knowledge: Mastered data extract, transformation and loading techniques with Power Query
+ Data Cleaning: Gained extensive knowledge in data cleaning with Power Query
+ Data Modeling: Created data models using Power Pivot
+ DAX Measures: Created KPIs/customized measures by utilizing DAX in Power Pivot
+ User Empathy: Designed user-centric reports

# ➡️ 𝐒𝐭𝐞𝐩𝐬 𝐢𝐧𝐯𝐨𝐥𝐯𝐞𝐝 𝐢𝐧 𝐦𝐚𝐤𝐢𝐧𝐠 𝐭𝐡𝐢𝐬 𝐑𝐞𝐩𝐨𝐫𝐭: -

1. 𝐄𝐓𝐋 (𝐄𝐱𝐭𝐫𝐚𝐜𝐭 𝐓𝐫𝐚𝐧𝐬𝐟𝐨𝐫𝐦 𝐚𝐧𝐝 𝐋𝐨𝐚𝐝)
Load all the CSV files that were provided, to Power Query. Ensured there were no missing values, all dimension tables contained a unique column, removed duplicate values, corrected the spelling errors, and in the end loaded the files in the Power Pivot.
 
2. 𝐃𝐚𝐭𝐚 𝐌𝐨𝐝𝐞𝐥𝐢𝐧𝐠
Connect all the tables using star schema. Create a new table dim_date using Power Query that includes the date, month, and year in a separate column. Add a new column for adding AtiliQ Hardware Fiscal year that runs from September to August and then connect the table with others.
 
3. 𝗣𝗶𝘃𝗼𝘁 𝗧𝗮𝗯𝗹𝗲 𝗮𝗻𝗱 𝗣𝗼𝘄𝗲𝗿 𝗣𝗶𝘃𝗼𝘁
Integrate the data model with a Pivot Table for quick data analysis. Utilize Power Pivot to create new measures and columns. Employ Power Query for seamless data transformation and connectivity, streamlining the entire process of preparing and analysing data efficiently.
 
4. 𝐃𝐀𝐗 (𝐃𝐚𝐭𝐚 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬 𝐄𝐱𝐩𝐫𝐞𝐬𝐬𝐢𝐨𝐧)
Create 10 + new Measures such as Net sales for each year, Gross Margin, GM %, and COGS using Formulas like Calculate, Sum, Divide, etc. Create new Columns using Functions like Related, Calculate, Format and extract quarterly months by adding 4 months to the calendar year for a fiscal year perspective.
 
5. 𝐂𝐨𝐧𝐝𝐢𝐭𝐢𝐨𝐧𝐚𝐥 𝐅𝐨𝐫𝐦𝐚𝐭𝐭𝐢𝐧𝐠
Applied Conditional Formatting to enhance data presentation by applying rules, and formatting numbers and text. This approach highlights important data, identifies trends, and improves overall data readability for more effective analysis.

# 💡 𝐈𝐧𝐬𝐢𝐠𝐡𝐭𝐬:-
1. In 2021, India emerged as the top-performing market with the highest net sales of $161.3 million, while Sweden recorded the lowest sales at $1.8 million.
2. The AQ Master Wired X1 MS proved to be the best-selling product, moving 4.2 million units, whereas the AQ Home Allin1 Gen2 had the lowest sales, with only 8.8 thousand units sold.
3. During the festive months of October to December, a notable surge in sales and profits was observed in India.
4. The top 3 customers contributing to the highest net sales were Amazon, AtliQ Exclusive, and AtliQ e-store.
5. The introduction of 16 new products in 2021 showcased AQ's innovation, with the AQ Qwerty leading sales at 22 million units.
