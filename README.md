# Meta Ad Performance Dashboard – 

This project presents a comprehensive Power BI dashboard analyzing advertising performance across Meta platforms (Facebook & Instagram). The goal is to unlock actionable insights around audience behavior, campaign ROI, engagement trends, and budget utilization to enable smarter, data-driven marketing decisions.

--- 

## 📊 Dashboard Overview

Below is a preview of the developed dashboard:

![Dashboard Overview](Dashboard%20Overview.png)

---

## 🎯 Business Problem

Meta campaigns were running across various geographies, demographics, and ad formats.  
The marketing team required a **unified performance tracking dashboard** that answers:

- Which campaigns/platforms perform best?
- Which audience segments drive engagement?
- What is the ROI of the current marketing spend?
- How do engagement patterns vary by time, location, gender, and age?
- Which ad formats deliver conversions efficiently?

This dashboard directly addresses these questions using multi-source performance data.

---

## 🧭 Scope of Analysis

### **In Scope**
- Paid campaigns on Facebook & Instagram  
- User demographics  
- Engagement metrics  
- Time-based performance  
- Budget insights  

### **Out of Scope**
- Organic reach  
- Other Meta channels (Messenger, Audience Network)

---

## 📁 Project Structure

Future_DS_02/
│
├── Dashboard Overview.png
├── meta dashboard.pbix
├── Raw Data-20251209T203255Z-1-001.zip
└── README.md


---

## 📂 Dataset Summary

The raw data (inside the ZIP file) includes:

1. **ads.csv** – ad attributes (platform, ad type, gender targeting, age group)  
2. **ad_events.csv** – impressions, clicks, shares, comments, purchases  
3. **campaigns.csv** – budget allocation & campaign metadata  
4. **users.csv** – demographic information (country, gender, age)

Data was transformed and modeled in Power BI using a star-schema approach.

---

## 📌 Key KPIs Tracked

**Performance KPIs**
- Impressions  
- Clicks  
- Shares  
- Comments  
- Purchases  
- Engagements  

**Efficiency KPIs**
- CTR (Click-Through Rate)  
- Engagement Rate  
- Conversion Rate  
- Purchase Rate  

**Financial KPIs**
- Total Budget  
- Average Budget per Campaign  
- Spend Efficiency  

---

## 📈 KPI Metrics Summary

Based on the final dashboard:

- **Impressions:** 216K  
- **Clicks:** 25.4K  
- **Engagements:** 29K  
- **Shares:** 1.3K  
- **Comments:** 2.6K  
- **Purchases:** 1.3K  

**Efficiency Metrics:**
- **CTR:** 11.76% (excellent performance)  
- **Engagement Rate:** 13.56% (high audience resonance)  
- **Conversion Rate:** 5.21%  
- **Purchase Rate:** 0.61% (conversion gap detected)

**Budget Metrics:**
- **Total Budget:** 2.5M  
- **Avg Budget per Campaign:** 50.7K  

---

## 🔍 Key Insights (From Dashboard)

### **1. Strong visibility & engagement**
- High CTR and Engagement Rate indicate top-of-funnel success.  
- Audience is clearly interested in the ad creatives and messaging.

### **2. Weak lower-funnel performance**
- Purchase Rate is only 0.61%.  
- Indicates drop-offs after the click stage → landing page or offer optimization needed.

### **3. Demographic Insights**
- **Best-performing age group:** 18–30  
- **Top engaging gender:** Female (43% of total engagements)

### **4. Geographic Insights**
- Highest engagement comes from: **US, India, Brazil, Germany, UK**  
- India and US show scalable volume; EU markets show conversion potential.

### **5. Time-Based Insights**
- **Peak engagement hours:** 3 PM – 8 PM  
- **Weak hours:** Early mornings (0–5 AM)  
- Engagement peaks on specific high-activity dates in June.

### **6. Ad-Type Insights**
| Ad Type  | CTR | Conversion Rate | Engagement Rate |
|---------|------|------------------|------------------|
| Video   | Highest | Highest | Highest |
| Stories | Strong | Strong | Strong |
| Image   | Moderate | Lower | Moderate |
| Carousel | Moderate | Lower | Moderate |

**Winning formats:** Video > Stories  
**Recommendation:** Reallocate spend toward top-performing formats.

Note: The insights below reflect Facebook campaign performance. Instagram insights are available on the second page of the Power BI dashboard.

---

## 💡 Recommendations (Actionable)

1. **Fix Conversion Drop-Off**  
   - Improve landing page experience.  
   - Strengthen call-to-action, offers, and retargeting workflows.

2. **Audience Optimization**  
   - Prioritize Females aged **18–30** for maximum engagement and CTR.  
   - Double down on India & US for scalable performance.

3. **Budget Reallocation**  
   - Increase investment in **Video and Stories ads** (highest ROI drivers).  
   - Reduce low-performing ad types.

4. **Time Optimization**  
   - Schedule ads between **3 PM and 8 PM** for peak impact.

5. **Promotion Cadence**  
   - Launch campaigns around high-engagement dates (e.g., 19–21, 25–27 June).

---

## 🖥 Interactive Features in Dashboard

- Filters by **gender**, **age group**, **country**, **platform**, **ad type**, **campaign**, **month**, **hour of day**  
- Dynamic metric selection  
- Calendar heatmap  
- Time-series trends  
- Geographic map  
- Ad-type comparison matrix  

---

## 🔗 Files Included

- **meta dashboard.pbix** – Final Power BI report  
- **Raw Data ZIP** – 4 original datasets  
- **Dashboard Overview.png** – Thumbnail of final dashboard  
- **README.md** – Documentation (this file)

---



