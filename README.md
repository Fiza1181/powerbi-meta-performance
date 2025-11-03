# Meta Ad Performance Dashboard (Power BI)

![Meta Ad Performance Dashboard](https://i.pinimg.com/1200x/b0/62/46/b06246567ed168a6bc494767f4b304bf.jpg)

A real-time **Power BI dashboard** analyzing **Meta Ads performance** using campaign, user, and engagement data.  
Built to assess ad efficiency, targeting strategy, and ROI using KPIs like **CTR, Engagement Rate, Conversion Rate, and Purchase Rate**.  
This project delivers clear visual storytelling with insights on demographics, timing, geography, and ad format performance.

---

## 📂 Repository Contents

- `Meta Project.pbix` – Power BI dashboard file  
- `Domain Knowledge.pdf` – Detailed explanation of dataset structure, KPIs, and ad metrics  
- `Meta PoweBl Project.pdf` – Documentation of dashboard insights and analysis  
- `ad_events.csv`, `ads.csv`, `campaigns.csv`, `users.csv` – Dataset files used in the dashboard  
- `LICENSE` – License for the project  
- `README.md` – This file  

---

## 📄 Domain Knowledge

The **Domain Knowledge.pdf** file explains:  

- **Dataset Overview:** Meta Ads Performance Data covering campaigns, ads, user demographics, and ad interaction events  
- **KPIs & Metrics:** Impressions, Clicks, Purchases, CTR, CPC, CPM, ROAS, Engagement Rate, Conversion Rate, Audience insights  
- **Tables & Fields:**  
  - `ad_events` (fact table) – all user interactions with ads  
  - `ads` – ad creative metadata and targeting info  
  - `campaigns` – budget, duration, and strategy  
  - `users` – demographics and interests  
- **Table Relationships:** Star schema with `ad_events` as fact table and `ads`, `campaigns`, `users` as dimension tables  

> [View Domain Knowledge Document](Domain%20Knowledge.pdf)

---

## 📊 Dashboard Insights (from Meta PoweBl Project.pdf)

**KPI Metrics**

- **Impressions:** 216K – Total times the ads were shown  
- **Clicks:** 25.4K – Number of people who clicked  
- **Engagements:** 29K – Total interactions (likes, shares, comments)  
- **CTR:** 11.76% – Click-through rate, strong performance  
- **Engagement Rate:** 13.56% – Content resonates with audience  
- **Conversion Rate:** 5.21% – Percentage of clicks leading to purchase  
- **Purchase Rate:** 0.61% – Low funnel efficiency  
- **Total Budget:** 2.5M, **Avg Budget per Campaign:** 50.7K  

**Audience Insights**

- **Gender:** Females engage more (43%) than males (22%)  
- **Age Group:** Peak engagement 20–30, drops after 35+  
- **Top Countries:** US, India, Brazil, Germany, UK  

**Timing & Trends**

- **Hourly Engagement:** Peaks in afternoon & evening  
- **Weekly Engagement:** Consistent, spikes during promotions/events  

**Ad Type Analysis**

| Ad Type  | Impressions | Clicks | CTR   | Purchase Rate | Conversion Rate | Engagement Rate |
|----------|------------|--------|-------|---------------|----------------|----------------|
| Video    | 46K        | 5K     | 11.9% | 0.62%         | 5.2%           | 13.7%          |
| Stories  | 72K        | 8K     | 11.8% | 0.65%         | 5.2%           | 13.6%          |
| Image    | 51K        | 6K     | 11.7% | 0.57%         | 4.9%           | 13.5%          |
| Carousel | 48K        | 6K     | 11.7% | 0.59%         | 5.1%           | 13.4%          |

> Video & Stories perform best; Images & Carousel slightly lower conversions.

---

## 💡 Recommendations

1. Improve purchase funnel efficiency (landing pages, retargeting)  
2. Target female audience aged 18–30 in India & Brazil  
3. Focus budget on Video & Story ad formats  
4. Schedule ads during afternoons & evenings for maximum engagement  
5. Allocate budget to high-performing geographies and campaigns  

---

## 🔗 Links & References

- [Domain Knowledge Document](Domain%20Knowledge.pdf)  
- [Meta Dashboard PDF](Meta%20PoweBl%20Project.pdf)    
- [LinkedIn](https://www.linkedin.com/in/ferry-ferry-bb343116a)  
- [Website](https://fiza1181.github.io/ferryPortfolio/)  
