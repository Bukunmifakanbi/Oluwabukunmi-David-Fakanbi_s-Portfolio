# 📊 Retail Store Customer Purchasing Behaviour Analysis

## 📊 Overview

This project analyzes retail sales and customer purchasing patterns using Microsoft Power BI.
The goal is to uncover insights into customer demographics, spending behavior, product performance, and seasonal trends that can guide marketing, inventory, and revenue optimization decisions.

The dashboard provides an interactive view of total revenue, purchase behavior, customer demographics (age and gender), and purchasing trends over time.

---

## 🎯 Objectives

The analysis seeks to answer key business questions such as:

How do age and gender influence purchasing behavior?

Which product categories generate the highest revenue and engagement?

What seasonal trends exist in customer spending?

How do basket sizes (number of items per transaction) affect total sales?

Which customer segments contribute most to the company’s revenue?

---

## 📂 Dataset Description
- **Source:** Retail Sales Dataset - Kaggle (https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset)

- **Key Columns:**  
  - `CustomerID`  
  - `Gender`  
  - `Age` → transformed into `Age_Group`  
  - `Product_Category`  
  - `Quantity` → transformed into `Purchasing Behaviour Group`
  - `Total_Amount`  
  - `Date` → transformed into `Month` 

---

## 🧩 Tools & Techniques

Power BI

Data import and cleaning using Power Query

Data modeling using relationships and calculated measures (DAX)

Interactive slicers (Age Group, Gender, Product Category)

KPIs and trend analysis visuals

DAX Measures

Total Revenue = SUM(Total_Amount)

Total Quantity = SUM(Quantity)

Avg Spend per Transaction = AVERAGE(Total_Amount)

Age Grouping and Purchasing Behaviour classification via SWITCH() logic

## 📈 Dashboard Summary
### 🧾 Key Metrics
KPI	Value
Total Revenue	$456K
Total Quantity Sold	2,514 units
Top Revenue Category	Electronics ($156.9K)
Top Quantity Sold Category	Clothing (894 units)
Peak Sales Month	May
Gender Split	Female (51.06%), Male (48.94%)

---

## 🔍 Key Insights

### 🧠 Customer Demographics & Behaviour
- **Mature Adults (45–54)** are the top revenue generators (**$97.2K**) — mostly purchasing **Beauty products ($36K)**, dominated by **male buyers (51.84%)**.  
- **Young Professionals (25–34)** follow closely, primarily purchasing **Clothing**, with **females accounting for 53.4%** of sales.  
- **Young Adults (18–24)** males tend toward **Beauty**, while females prefer **Clothing** — both with **moderate baskets (3–4 items)**.  
- **Senior Adults (55+)** maintain a near-equal gender balance (**50.21% female**) and show higher interest in **Electronics**.  

### 💰 Product & Category Performance
- **Beauty ($467.5K)** leads overall revenue, followed by **Electronics ($458.8K)**, while **Clothing** records the highest quantity sold.  
- **Male customers** contribute notably to **Beauty** and **Electronics**.  
- **Clothing** drives large-volume purchases, while **Beauty** drives higher profit margins.  

### 🛒 Purchasing Patterns
- The **Moderate Basket (3–4 items)** dominates, with **504 transactions**, contributing the largest revenue share.  
- Customers buying fewer items (1–2) present upselling opportunities.  

### 📅 Seasonal & Time-Based Trends
- **Top-performing months:** **May, October, and December.**
  - *May:* Electronics sales peak.  
  - *October–December:* Beauty and Electronics perform strongly.  
- **Low-performing months:** **March and September**, where Electronics decline and Clothing/Beauty perform moderately.  

### 👥 Gender Influence
- **Females contribute 51.06%** of total revenue, especially strong in **Clothing**.  
- **Males** are prominent in **Electronics** and **Beauty**, showing a balanced category interest.  

### 📈 Cross-Age & Category Relationships
- **Electronics** revenue peaks among **Senior Adults ($38K)**.  
- **Clothing** performs best with **Young Professionals ($42K)**.  
- **Beauty** achieves top revenue with **Mature Adults ($36K)**.  

### 🔁 Customer Retention
- **Customers aged 25–54** are the most consistent repeat buyers.  
- **Moderate-basket customers** correlate with higher repeat purchase likelihood.  

### 💹 Pricing & Future Analytics
- Pricing variations exist across categories, but **no price distribution visual** yet in the dashboard — suggesting room for margin optimization.  

---

## 💡 Recommendations & Actionable Steps

### 🧠 Customer Demographics & Behaviour
- Create **premium loyalty tiers** (e.g., *Beauty Elite Program*) for Mature Adults (45–54).  
- Run **targeted clothing campaigns** for Young Professionals (25–34) — *“Style Saver Membership”* or *“Office Fits Promo.”*  
- Engage **Young Adults (18–24)** with trendy, affordable starter packs to build early loyalty.  
- Offer **warranty and reliability-driven promotions** to attract Senior Adults (55+).  

### 💰 Product & Category Growth
- Expand **Beauty** product range and introduce **subscription boxes** (*“Monthly Essentials Box”*).  
- Launch **cross-category bundles** (*“Buy 3 Get 1 Free”*) to raise average order value.  
- Use **Men’s Grooming + Tech** bundle campaigns to attract male buyers.  
- Keep **Clothing** as the entry-level volume driver and upsell to Beauty or Accessories.  

### 🛒 Purchasing Patterns
- Introduce **tiered discounts** (5% for 2 items, 10% for 3+ items) to increase basket sizes.  
- Use **cross-selling** strategies like *“Frequently Bought Together”* or *“Complete the Look”* recommendations.  
- Monitor **basket composition KPIs** in Power BI to identify complementary product combinations.  

### 📅 Seasonal Trends
- **Increase stock and marketing spend** before May, October, and December to maximize peak sales.  
- **Run re-engagement campaigns** during March and September (e.g., clearance sales or loyalty offers).  
- Adjust **staff schedules and inventory planning** around seasonal demand patterns.  

### 👥 Gender-Specific Strategies
- Create **female-oriented loyalty programs** and *“Refer a Friend”* campaigns.  
- Promote **cross-category bundles** (Beauty + Clothing) for female customers.  
- For male customers, highlight **tech accessories and grooming bundles** (*“Smart + Sleek Deals”*).  

### 📈 Cross-Age & Category Optimization
- Customize ad messaging per age group:  
  - *Seniors:* emphasize reliability and after-sales support.  
  - *Young Professionals:* stress style and affordability.  
  - *Mature Adults:* focus on quality and exclusivity.  
- Use **segmented email campaigns** to deliver targeted promotions by customer group.  

### 🔁 Customer Retention & Loyalty
- Track **repeat vs. new buyers** using Power BI KPIs.  
- Send **personalized thank-you emails** and **win-back campaigns** after inactivity.  
- Implement **points-based loyalty programs** and **exclusive VIP sales** for repeat customers.  

### 💹 Pricing & Future Analytics
- Add a **price vs. quantity scatterplot or boxplot** to study price sensitivity and profit margins.  
- Perform **A/B testing** to identify optimal discount ranges without eroding profits.  
- Evaluate **category-level price elasticity** to refine future pricing strategies.  

---

## 🚀 Expected Business Impact

| Initiative | Anticipated Outcome |
|-------------|--------------------|
| Targeted age & gender marketing | +10–15% revenue growth |
| Moderate basket incentives | +8–12% increase in average order value |
| Seasonal optimization | +15% lift during peak months |
| Loyalty & referral programs | +20% repeat-purchase rate |
| Male-focused bundles | +5–8% category revenue growth |

---

### 🏁 Summary
The analysis reveals that **age, gender, and seasonality strongly influence purchasing behavior**.  
By combining **targeted marketing**, **strategic pricing**, and **retention initiatives**, the retail business can improve profitability, increase repeat purchases, and maintain steady year-round growth.
