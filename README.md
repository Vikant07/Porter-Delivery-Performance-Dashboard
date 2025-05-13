# 🚚 Porter Delivery Performance Dashboard (Power BI Project)

This Power BI dashboard analyzes delivery patterns for **Porter**, a rising food delivery startup. The aim was to improve customer satisfaction by identifying root causes behind delayed deliveries across markets.

---

## 📁 File Structure

- `Porter_Delivery_Analytics.pbix` → Interactive dashboard with data visuals & DAX KPIs
- `images/` → Screenshots of dashboard visuals (add this folder if uploading dashboard pics)

---

## 📌 Problem Statement

Porter is facing a drop in delivery satisfaction scores. The challenge was to uncover bottlenecks affecting delivery time using real data and propose actionable insights.

---

## 📊 Dashboard Features & KPIs

✅ **KPIs Included**:
- Total Orders  
- % Orders Delivered Under 30 Minutes  
- Average Delivery Duration  
- Revenue Generated  
- Average Order Value  
- Peak Delivery Hours  
- Market-level Bottlenecks  
- Partner (delivery personnel) Availability

✅ **Filters**:
- Market ID  
- Store Category  
- Time & Date filters

---

## 🛠 Tools & Technologies

- **Power BI** (DAX, Visuals, Interactive Dashboards)  
- **Python** (Data cleaning: handled 1.5 lakh+ rows, feature engineering, datetime conversion)  
- **GitHub** (Version control and project sharing)

---

## 🔍 Data Preprocessing (Python Highlights)

- Converted string timestamps (`created_at`, `actual_delivery_time`) to `datetime`
- Created features: `delivery_duration`, `hour_of_day`, `day_of_week`
- Handled nulls via imputation/removal based on relevance
- Aggregated high-cardinality categories

---

## 📈 Insights Derived

- 42% of deliveries were delayed beyond 30 minutes in Tier-1 cities  
- Partner unavailability during peak hours increased delivery time by 18%  
- Grocery & Pharma orders had the highest on-time rate  
- Saturdays saw the lowest partner availability  

---

## 👩‍💼 Stakeholders

- Operations, Customer Support, and Logistics Teams  
- External partners like restaurants and delivery agents

---

## 📌 How to Use

1. Clone or download the repo
2. Open `Porter_Delivery_Analytics.pbix` using **Power BI Desktop**
3. Interact with slicers to explore different markets or store types

---

## 🧠 Learnings & Takeaways

- Importance of combining DAX logic with business KPIs  
- Strategic visualization placement for operations-focused dashboards  
- Real-time insights help in reducing delivery delays

