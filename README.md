# **📊 Tableau Project: Sales Analysis Dashboard**

 ![3  Sales Analysis Dashboard](https://github.com/user-attachments/assets/a5156a84-20a5-44d7-8a18-bae7bb13fbab)

## **Introduction**
In today’s fast-paced, data-saturated world, businesses don’t just need data, they need **clarity, speed, and strategic insight**. This **interactive Tableau Sales Dashboard** does exactly that. It goes beyond charts and graphs to **breathe life into raw numbers**, uncovering trends, revealing patterns, predicting sales, and instantly spotlighting top-performing regions, products, and high-value customers.

**Built for speed and built for impact**, this dashboard is packed with **automated analytics and real-time intelligence**, making it your all-in-one command center for **smarter decisions** and **unmatched business growth**.

For this car company, it marks a transformation from static spreadsheets to a dynamic, data-driven powerhouse. It empowers teams to unlock performance, **elevate customer engagement**, and gain a razor-sharp **competitive edge** in an ever-evolving market.

### **💡 Why This Matters**
To make impactful decisions, sales leaders, executives, and marketing teams need a clear, data-backed view of sales performance and customer behaviour. This **Tableau-powered solution** enables the car company to:

**1. Optimize Sales Strategies** – Identify key trends and patterns to maximize revenue.

**2. Enhance Customer Relationships** – Understand behaviours, preferences, and purchasing habits for better engagement.

**3. Boost Operational Efficiency** – Move beyond static spreadsheets with **automated, real-time reporting**.

**4. Drive Data-Backed Growth** – Use **predictive insights** to stay ahead in a competitive market.

**5. Mitigate Risks Proactively** – Spot inefficiencies and challenges before they impact performance.


### **Who Benefits the Most from This Dashboard?**

**1. Sales Managers** – Track team performance, optimize sales strategies, and boost revenue.

**2. Executives & Decision-Makers** – Gain high-level insights into profitability, growth trends, and risks.

**3. Marketing Teams** – Analyse customer behaviours to refine targeting and improve engagement.

**4. Business Analysts** – Transform complex data into actionable strategies for long-term success.


### **What Sets This Dashboard Apart**

**1.  Automated & Dynamic** – Say goodbye to manual reporting and embrace **real-time analytics**.

**2.  Interactive Visuals** – Uncover insights with drill-down capabilities and intuitive dashboards.

**3.  Predictive Intelligence** – Forecast trends, optimize strategies, and stay **ahead of the competition**.

**4.  Strategic Intelligence** – Move beyond visualization to gain deep, actionable insights that fuel **business growth**.

**5.  Seamless Reporting & Efficiency** – Reduce manual work and focus on what truly matters, **driving success**.


### **📊 Competitive Advantage**
By integrating **cutting-edge analytics, automated workflows, and intelligent storytelling, this Tableau Sales Analysis Dashboard** enables the company to:

**1. Identify trends and patterns** in sales performance.

**2. Understand customer behaviours** to strengthen relationships and improve retention.

**3. Optimize sales strategies** with **data-driven insights**.

**4. Enhance marketing efforts** by targeting **high-value customer segments**.

**5.  Improve decision-making** with **interactive, dynamic visualizations**.


### **Dashboard File**
**🔗 Access the final dashboard here**:[Dashboard](https://public.tableau.com/app/profile/olumide.balogun1/viz/SalesAnalysisDashboard_17283835601310/SalesDashboard)


### **Tableau Skills Used**
The following Tableau skills were utilised for analysis:

- **🧮 Calculated Fields** 

- **🚫 Bans** 

- **📉 Charts** 

- **📊 Table** 

- **❎ Data Validation**
   

### **Dataset Overview**
The dataset used for this project is a **realistic cars sales dataset covering 2020 to 2021**, providing a **comprehensive** view of **23,906 Rows and 16 Columns**.

**🔗 Access the dataset here**: [Raw Data](https://github.com/olumidebalogun1/Sales-Analysis-Dashboard/tree/main/1.%20Dataset)


## **📊 Sales Analysis Dashboards | Key Requirements**

### **📈 Sales Dashboard | Requirements**
**🎯 Purpose**:

The Sales Dashboard provides a comprehensive **overview of key sales metrics and trends**, helping stakeholders analyse **year-over-year performance** and uncover actionable insights to improve revenue and efficiency.

**🔑 Key Requirements**

**1. KPI Overview**

- **Quick snapshot** of total sales, quantity sold, and average price, comparing the **current year vs. the previous year** for an at-a-glance performance check.

**2. Sales Trends**

- Monthly trend analysis for key performance indicators (**sales, quantity, and average price**) for the current and previous years.

- **Highlight the best and worst-performing months** to identify seasonal fluctuations and business cycles quickly.

**3. Weekly Trends for Sales & Quantity**

- **Break down sales and quantity data by week** for real-time monitoring.

- Show **average weekly values** to track consistency.

- Automatically **highlight weeks** where performance was significantly above or below average.

**4. Car Body Size Comparison**

- Compare **sales performance by different car body sizes** across the current and previous years.

- Showcase **average sales per body size** to determine which categories drive the most revenue.

**5. Car Colour Comparison**

- **Identify trends in car colour preferences**, comparing sales performance by colour for the **current and previous year**.

**6. Regional Dealers Comparison**
- Compare **sales performance across different regional dealers** for the **current and previous year**.

- **Analyse transmission type preferences** per regional dealer for deeper insights.


### **👥 Customer Dashboard | Requirements**
**🎯 Purpose**:

The **Customer Dashboard** focuses on **customer segmentation, sales trends, and engagement insights**, helping marketing teams and management make **data-driven decisions** to enhance customer satisfaction and retention.

**🔑 Key Requirements**

**1. KPI Overview**

- A quick view of **total customers, sales per customer, and total quantity sold, comparing the current year vs. the previous year**.

**2. Customer Trends**

- Track **monthly customer trends** by analysing **new customers, sales per customer, and total quantity sold**.

- **Highlight peak and low-performing months** to understand seasonal patterns and engagement levels.

**3. Top 10 Companies by Sales**

- Showcase the **top 10 companies that contributed the highest sales**.

- Include **key details like current sales, quantity, average price, and percentage of total sales**.

**4. Top 5 Dealers by Sales**

- Identify the **top 5 highest-performing dealers** driving sales growth.

- Display details such as **rank, current sales, quantity, average price, and last order date** for better sales tracking.

**5. Bottom 5 Dealers by Sales**

- Highlight **dealers with the lowest sales performance** to identify areas for improvement.

- Include details like **rank, current sales, quantity, average price, and last order date** to facilitate targeted strategy adjustments.
 

## **🎨 Design & Interactivity Requirements**

### **📊 Dashboard Dynamics**

**1. Year Selection**: Users should be able to select and analyse data from any **historical year**.

**2. Seamless Navigation**: Ensure **easy switching between dashboards** for a smooth user experience.

**3. Interactive Visuals**: Charts and graphs should be **dynamic**, allowing users to filter data directly from visuals.

### **🔍 Data Filters**
Give users the **flexibility to filter insights** by:

**✔ Gender**

**✔ Company**

**✔ Dealer Name**

**✔ Car Model**

**✔ Engine Type**


# **📊 Sales Analysis Dashboards**

## **📈 Sales Dashboard**

### **1.  KPI Overview**
To display a summary of **total sales, total quantity sold, and average price** for the current and previous years, I need to create **BANs**. To achieve this, I will first create a **parameter and new calculated fields**:

### **Parameter & Calculated Field**
**1. Parameter - Select Year** 

![1 0 Select Year Parameter](https://github.com/user-attachments/assets/d84c6d55-f334-4001-b2c3-486eca8e5f76)

**2. Selected Year**

![1 1 Calculated Field - Selected Year](https://github.com/user-attachments/assets/f862e4d8-b741-42dd-adb6-223c33d630ba)

**3. Current Year**

![1 2 Calculated Field - Current Year](https://github.com/user-attachments/assets/1c8089de-28ed-483d-ae27-babdb557a65f)

**4. Previous Year** 

![1 3 Calculated Field - Prior Year](https://github.com/user-attachments/assets/72d0c759-732a-4825-9549-42ab29e96eb6)

### **Total Sales** - Calculated Fields
**1. Current Year Sales**

![2 0 Calculated Field - Current Sales](https://github.com/user-attachments/assets/3c456f63-b7a7-4daa-ad4b-4df50c707a97)

**2. Previous Year Sales**

![2 1 Calculated Field - Previous Sales](https://github.com/user-attachments/assets/120df102-0644-4bed-9fa4-4874990a04ac)

**3. % Diff. Sales**

![2 2 Calculated Field - % Diff  Sales](https://github.com/user-attachments/assets/9e6479f0-495a-4bb9-96b0-587d19c0a9de)

### **Total Quantity Sold** - Calculated Fields 
**1. Current Year Quantity Sold**

![3 0 Calculated Field - Current Quantity Sold](https://github.com/user-attachments/assets/90fb4311-e30e-494f-8b03-c3525d678442)

**2. Previous Year Quantity Sold**

![3 1 Calculated Field - Previous Quantity Sold](https://github.com/user-attachments/assets/5d2c9404-97a4-4b13-af54-6df7cc776ae3)

**3. % Diff. Quantity Sold**

![3 2 Calculated Field - % Diff  Qty  Sold](https://github.com/user-attachments/assets/3b9c8543-e7b7-441c-9fd6-ed8ec72472d5)

### **Avg. Price** - Calculated Fields 
**1. Current Year Avg. Price**

![4 0 Calculated Field - Avg Price](https://github.com/user-attachments/assets/9b9539a1-3b94-4fb6-9d78-8ce3641b2b62)

**2. Previous Year Avg. Price**

![4 1 Calculated Field - Previous Avg Price](https://github.com/user-attachments/assets/836fae2c-f9f6-4b10-889e-c7baa2a96a94)

**3. % Diff. Avg. Price**

![4 2 Calculated Field - % Diff  Avg  Price](https://github.com/user-attachments/assets/2a3ab8da-7d2f-4521-a141-34b595a6ae3c)


### **2. Sales Trends**
To **analyse** the monthly trend of key performance indicators (**sales, quantity, and average price**) for the current and previous years and **highlight the best and worst-performing months**, enabling quick identification of seasonal fluctuations and business cycles. To achieve this, I will first create **calculated fields for maximum and minimum values** and then build **bar charts**:

### **Total Sales Calculated Field - Min/Max Sales**
![2 3 Calculated Field - Min   Max Sales](https://github.com/user-attachments/assets/d9d1ef79-1f82-4849-8351-30f4d714d0b5)

### **Total Sales Ban & Bar Chart**
![2 4 CHART - Ban   Bar Chart](https://github.com/user-attachments/assets/bfd1588e-0a85-4475-abcd-e1e5ebfa38c0)

### **Total Quantity Sold Calculated Field - Min/Max Qty. Sold**
![3 3 Calculated Field - Min   Max Qty  Sales](https://github.com/user-attachments/assets/05c0cee8-37a0-46a2-ac98-203bfbfcccb7)

### **Total Quantity Sold Ban & Bar Chart**
![3 4 CHART - Ban   Bar Chart](https://github.com/user-attachments/assets/08f248d0-5f28-45ba-b800-35a9c0109eb5)

### **Avg. Price Calculated Field - Min/Max Avg. Price**
![4 3 Calculated Field - Min   Max Avg  Price](https://github.com/user-attachments/assets/73970154-5df0-4d91-b6f1-55dd7bd3e274)

### **Avg. Price Ban & Bar Chart**
![4 4 CHART - Ban   Bar Chart](https://github.com/user-attachments/assets/5419bf38-2856-4ec9-953a-1d8b9a2d8343)


### **3. Weekly Trends for Sales & Quantity**
To break down **sales and quantity data by week** for real-time monitoring, display **average weekly values** to track consistency, and automatically **highlight weeks** with significantly above or below average performance, I need to build **line charts**. To achieve these, I will first create **new calculated fields**:

### **Weekly Sales Calculated Fields - Sales Average**
![5 0 Calculated Field - KPI Sales Avg](https://github.com/user-attachments/assets/ceae2610-f227-4527-a3f8-a9cbc3d25f15)

### **Weekly Sales Line Charts**
![5 1 CHART - Sales Line Chart](https://github.com/user-attachments/assets/f1ebcdfe-085e-4326-a6cf-bb306c9ccbc9)

### **Weekly Qty. Sold Calculated Fields - Qty. Sold Average**
![6 0 Calculated Field - KPI Qty  Sold Avg](https://github.com/user-attachments/assets/be0cf5b4-3d34-4155-bd45-b443a7f0f859)

### **Weekly Qty. Sold Line Charts**
![6 1 CHART - Qty  Sold Line Chart](https://github.com/user-attachments/assets/4d19bb5a-bb8b-40ee-919f-04a853778c64)


### **4. Car Body Size Comparison**
To **compare sales performance across different car body sizes** for the current and previous years, and showcase **average sales per body size** to determine which categories generate the most revenue. To achieve this, I will build a **rounded bar chart**:

![7 1 CHART - Total Car Sales by Body Size](https://github.com/user-attachments/assets/18c28535-156d-4f76-9ec6-b99f528ec786)

### **5. Car Colour Comparison**
To **identify trends in car color preferences** by comparing **sales performance by colour** for the current and previous years. To achieve this, I will build a **rounded bar chart**:

![7 3 CHART - Total Car Sales by Color](https://github.com/user-attachments/assets/ac977b29-0752-4220-83c2-e1f82426cd41)

### **6. Regional Dealers Comparison**
To **compare sales performance across different regional dealers** for the current and previous years and **analyse transmission type preferences** per regional dealer for deeper insights. To achieve this, I will build a **rounded bar chart**:

![7 2 CHART - Total Car Sales by Regional Dealers](https://github.com/user-attachments/assets/cc1ddec4-b495-4584-a888-318d8d5eb742)


### **Dashboard**
![1  Sales Dashboard](https://github.com/user-attachments/assets/4f99efd2-f517-4686-8d60-c47c1381ceda)


## **👥 Customer Dashboard**

### **1.  KPI Overview**
To display the total number of customers and total sales per customer for the current and previous years, I need to create BANs. To achieve this, I will first create calculated fields.

### **Total Customers** - Calculated Fields 
**1. Current Year Customer**

![1 0 Calculated Field - CY Customer](https://github.com/user-attachments/assets/9784fec0-2062-4b00-8799-b57294ca58ae)

**2. Previous Year Customer**

![1 1 Calculated Field - PY Customer](https://github.com/user-attachments/assets/b831b06e-3969-4116-9f54-9ce60941fc35)

**3. % Diff. Customer**

![1 2 Calculated Field - % Diff  Customer](https://github.com/user-attachments/assets/20fcfa3c-432f-4fd2-ac36-00807b177dd5)

### **Total Sales per Customer** - Calculated Fields
**1. Current Year Sales per Customer**

![2 0 Calculated Field - CY Sales per Custom](https://github.com/user-attachments/assets/40a0f067-a798-41d3-bc04-f31537bc2d7a)

**2. Previous Year Sales per Customer**

![2 1 Calculated Field - PY Sales per Custom](https://github.com/user-attachments/assets/25bc4005-df93-4579-b470-a985cbaf1c5d)

**3. % Diff. Sales per Customer**

![2 2 Calculated Field - % Diff  Sales per Custom](https://github.com/user-attachments/assets/7f706878-6b5c-4b16-a657-805ae64e810d)

### **2.  Customer Trends**
To track **monthly trends** for customer-related KPIs and identify months with **the highest and lowest customer activity**, I need to build **bar charts**. To achieve this, I will first create **calculated fields for maximum and minimum values**.

### **Total Customers Calculated Field - Min/Max Customer**
![1 3 Calculated Field - MIN   MAX Customer](https://github.com/user-attachments/assets/796303da-96e0-4656-8057-e4db63c3defb)

### **Total Customers Ban & Bar Chart**
![1 4 CHART - Ban   Bar Chart](https://github.com/user-attachments/assets/173d8428-59f9-4787-a750-6b215819fcc5)

### **Total Sales per Customer Calculated Field - Min/Max Sales per Customer**
![2 3 Calculated Field - MIN   MAX Sales per Custom](https://github.com/user-attachments/assets/ee2b1192-fc34-43e0-ba10-eaaf1b9a76fb)

### **Total Sales per Customer Ban & Bar Chart**
![2 4 CHART - Ban   Bar Chart](https://github.com/user-attachments/assets/1b0b4cd0-d087-4386-ab05-e99606a714ad)

### **3. Top 10 Companies by Sales**
To showcase the **top 10 companies contributing the highest sales**, including key details such as **current sales, quantity, average price, and percentage of total sales**. To achieve this, I will build a **table chart**:

![3 0 CHART - Company Sales Trends 2](https://github.com/user-attachments/assets/50408e9d-01e1-4b63-b807-195f58680d5c)

![3 1 CHART - Company Sales Trends 2](https://github.com/user-attachments/assets/ea748633-d3a6-4828-9a02-c3aec8d5c101)

### **4. Top 5 Dealers by Sales**
To identify the **top 5 highest-performing dealers** driving sales growth and display details such as **rank, current sales, quantity, average price, and last order date** for better sales tracking. To achieve this, I will build a **table chart**:

![4 0 CHART - Top 5 Dealers by Sales 2](https://github.com/user-attachments/assets/80129b77-e467-456f-8ac7-82100cc4360b)

![4 1 CHART - Top 5 Dealers by Sales 2](https://github.com/user-attachments/assets/435ac16b-3292-4b63-9c66-014b6e6c1e1a)

### **5. Bottom 5 Dealers by Sales**
To highlight **dealers with the lowest sales performance** and identify areas for improvement, including details such as **rank, current sales, quantity, average price, and last order date** to facilitate targeted strategy adjustments. To achieve this, I will build a **table chart**:

![5 0 CHART - Bottom 5 Dealers by Sales 2](https://github.com/user-attachments/assets/c768c0f1-ffe8-4440-99eb-e2aac831898e)

![5 1 CHART - Bottom 5 Dealers by Sales 2](https://github.com/user-attachments/assets/bde804db-3835-4adf-8e05-ce50ff4fbe3b)


### **Dashboard**
![2  Customer Dashboard](https://github.com/user-attachments/assets/366a7482-a6c8-485c-9722-3d5c97da2f1e)


## **Conclusion**
This **Tableau-powered Sales Analysis Dashboard** is more than just a visualization tool, it’s a **data-driven engine** that converts raw data into **strategic insights and impactful decisions**. It enables the company to **pinpoint top-performing regions, best-selling models, and high-value customer segments** while identifying areas that need improvement.
Beyond data visualization, this **intelligent analytics solution** equips sales managers, marketing executives, and analysts with the **clarity and confidence** needed to thrive in a competitive market. By transforming complex data into a compelling business narrative, it empowers stakeholders to make **informed, data-backed decisions that drive growth, efficiency, and long-term success**.

## **Closing Thought**
Data is abundant, but its true power lies in the insights it reveals. As a Business/Data Analyst, my passion is translating complex data into **actionable strategies** that drive real business impact. It’s not just about numbers—it’s about making informed decisions that turn challenges into opportunities and fuel long-term success.

**Let’s connect, collaborate, and explore the power of data together!** 

## **Connect with Me**
- **📞 +234-8065060691**
- **📧 Email: krisbalo11@gmail.com**
- **🔗 LinkedIn**: [Connect with me on LinkedIn](https://www.linkedin.com/in/olumide-balogun1/)
- **🔗 Medium**: [Explore my Data Storytelling articles](https://medium.com/@Olumide-Balogun)



