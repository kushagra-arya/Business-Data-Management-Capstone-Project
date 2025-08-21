# 📊 Analyzing the Financial Performance of *Top Shelf: A Stationery Retail Business*

**Final Term Capstone Project**  
Bachelor of Science (Data Science & Applications)  
Indian Institute of Technology Madras  

**Author:** Kushagra (Roll No. 24DS1000083)  

---

## 🌟 Executive Overview  

Top Shelf, a stationery retail business located in Delhi University’s North Campus, was struggling with **seasonal demand fluctuations, inventory inefficiencies, and misaligned product strategies**.  

This project provided a **data-driven solution**, leveraging **Python (Pandas, Matplotlib, Seaborn)** to transform raw business records into actionable insights.  

**Key Outcomes:**
- 📈 Identified peak demand in **May (academic cycle)** and resilient revenue in **June despite lower volumes**.  
- 📦 Exposed **systemic overstocking** (e.g., Art Supply inventory > sales).  
- 💰 Discovered that **high-volume products ≠ most profitable**. Notebooks & Art Supplies outperformed A4 paper in profitability despite lower sales.  
- 🎯 Recommended a **multi-peak inventory strategy** + **profit-focused assortment optimization**, expected to boost efficiency and margins significantly.  

---

## 🔍 Project Workflow  

### 1. Data Collection & Cleaning  
- **Source:** Manual sales & inventory records from *Top Shelf* (March–June 2025).  
- **Tools:** Microsoft Excel → Python (Pandas).  
- **Preprocessing Steps:**  
  - Filled missing values via product catalog cross-verification.  
  - Standardized date formats (DD-MM-YYYY).  
  - Grouped SKUs into logical categories (e.g., pens & pencils → *Writing Essentials*).  
  - Removed duplicates & treated outliers using IQR.  

➡️ Result: Two structured datasets – **Sales (400 rows, 7 cols)** and **Inventory (100 rows, 21 cols)**.  

---

### 2. Analytical Methods  
- **Descriptive Statistics** → Means, medians, variability across products.  
- **Trend Analysis** → Monthly sales/revenue peaks.  
- **ABC Analysis** → Inventory classification by value.  
- **Profitability Analysis** → Contribution & margin-based SKU evaluation.  
- **Sales Velocity vs Inventory** → Identifying slow-moving vs fast-moving stock.  

📊 **Visualizations:** Line charts, bar plots, box plots, pie charts → easy-to-interpret insights for decision-making.  

---

### 3. Core Insights  

#### 📌 Seasonal Demand  
- May → **Sales & revenue peak (~6,000 units, ₹2.5L)**.  
- June → Sales dip, but **revenue resilience (only -6%)** due to high-value items.  
- **Insight:** Multiple overlapping category cycles, not a single seasonal trend.  

#### 📌 Inventory Efficiency  
- **Class A (78% value):** Writing Essentials, Paper, File, Office Supply, Instruments → high investment, low turnover.  
- **Class B:** Notebooks & Art Supplies → *less capital but higher profitability*.  
- **Critical Issue:** Art Supply closing stock > total sales → near-zero turnover.  

#### 📌 Profitability vs Revenue  
- **Top Revenue Driver:** A4 Paper.  
- **Top Profit Drivers:** Notebooks (31% margin) & Art Supplies (28.6%).  
- **Niche Opportunity:** Premium items (e.g., Copic Sketch Markers) show strong demand elasticity.  

---

## 🛠 Recommendations  

### 1. Multi-Peak Demand Strategy  
- Treat each category as having its own demand cycle.  
- **Writing Essentials:** Peak in April–May → ramp up stock & campaigns.  
- **Office Supply & Paper:** Focus on June → targeted promotions.  
- **Adhesive & File:** Push in April to maximize early-quarter sales.  

### 2. Differentiated Inventory Policy  
- **Class A (high value, low return):** Reduce overstocking via clearance sales + lean procurement.  
- **Class B (profitable):** Right-size orders & boost visibility.  
- **Class C (fast-moving):** Automate reordering.  

### 3. Profit-Centric Product Assortment  
- **Expand Notebooks & Art Supplies** (premium, high-margin).  
- **Paper:** Keep as traffic driver, but bundle with profitable SKUs.  
- **Instruments:** Reassess margins → retain only strategic items.  

---

## 🚀 Impact  

Implementing the insights from this project is expected to:  
- 🔄 Smooth seasonal revenue fluctuations with multi-cycle strategies.  
- 💸 Free up **locked capital** from slow-moving stock.  
- 📈 Boost **profitability by focusing on high-margin SKUs**.  
- 🎯 Establish Top Shelf as a **data-driven, agile retail business**.  

---

## 🧑‍💻 Tech Stack  

- **Languages:** Python  
- **Libraries:** Pandas, Matplotlib, Seaborn  
- **Data Source:** Business records (manual → digitized)  

---

## 🏆 Conclusion  

This project goes beyond descriptive analytics — it builds a **roadmap for sustainable growth** by combining **inventory science, demand forecasting, and profitability-driven decision-making**.  

Top Shelf can now pivot from being a **seasonally constrained shop** to a **resilient, profit-maximizing retail business**, all powered by **data science in action**.  

---

⚡ *Data is not just numbers – it’s strategy, and when applied right, it transforms businesses.*  
