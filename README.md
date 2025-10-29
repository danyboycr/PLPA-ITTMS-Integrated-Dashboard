# 🇵🇰 Pakistan Land Port Authority (PLPA) – Integrated Dashboard
**ADB CAREC-RIBS / ITTMS Program – Federal Board of Revenue (FBR), Government of Pakistan**  
**Developer:** *Muhammad Danish, Technical Specialist (Analytics)*   

---

## 📘 Overview
This repository presents the **Integrated Dashboard** developed for the **Pakistan Land Port Authority (PLPA)** under the **Integrated Transit Trade Management System (ITTMS)**, a flagship project co-financed by the **Asian Development Bank (ADB)** through the **CAREC-RIBS** initiative.  

The dashboard consolidates operational, institutional, and sustainability indicators across Pakistan’s major **Border Crossing Points (BCPs)** — **Torkham, Chaman, and Wagah** — providing a data-driven view of trade flows, SLA compliance, infrastructure development, and governance metrics.

---

## 🎯 Objectives
- Enable **operational intelligence** for PLPA, FBR, and ADB missions.
- Integrate **SLA, trade, and HR data** into a unified performance dashboard.
- Simulate data models reflecting **WeBOC** and **Pakistan Single Window (PSW)** structures.
- Track **environmental and SDG compliance** across land port infrastructure.
- Build a **replicable architecture** for national-level expansion (e.g., Badini, Sost, Ghulam Khan).

---

## ⚙️ Technical Architecture
| Component | Technology | Description |
|------------|-------------|--------------|
| Backend | **Oracle SQL Developer** | Schema modeling and data simulation for WeBOC/PSW-compatible structures |
| Frontend | **Microsoft Power BI** | Visualization and analytics engine |
| Schema | **Star Schema** | Fact tables (incidents, transactions) + dimension tables (ports, KPIs, escalation levels) |
| Integration-ready | **DirectQuery / API Sync** | Prepared for real-time PSW or WeBOC data linkage |

**Data Domains Modeled**
- SLA Logs: Fault start/end, escalation chain, downtime
- Construction Progress: FIDIC milestone % completion
- Trade Movement: TEUs, reverse flow, value
- Environment: SDG-coded scoring framework
- HR & Grievances: Gender participation, complaint resolution lag

---

## 📊 Dashboard Pages
| Page | Theme | Key Features |
|------|--------|---------------|
| 1 | **Overview Dashboard** | 40+ KPIs, early warning indicators, red/green thresholds |
| 2 | **BCP Infrastructure Tracker** | Gantt chart by phase & site, progress vs plan |
| 3 | **Trade & Logistics Flow** | TEU trends, reverse flow, corridor map |
| 4 | **SLA Compliance** | Scanner downtime heatmaps, escalation trends |
| 5 | **Environmental Sustainability (SDGs)** | Spider charts, maturity donuts, audit scoring |
| 6 | **Institutional Accountability** | Gender-segmented training, complaints dashboard |

---

## 🔍 Key Insights
- **SLA compliance gaps:** Torkham (61% escalation rate) and Chaman (35% resolution) highlight vendor accountability gaps.  
- **Environmental maturity:** Torkham scored **4.76**, outperforming Chaman’s **3.29**, confirming readiness for green audits.  
- **Institutional equity:** 799 staff trained, but only **41.7% women**, suggesting room for gender inclusion initiatives.  
- **Infrastructure transparency:** Real-time Gantt tracking now used in monthly PMU-ADB coordination meetings.

---

## 🚀 Strategic Impact
- Enabled **data-driven SLA enforcement** and vendor evaluation.
- Reduced manual reporting time by **~80%** via SQL-based data pipeline.
- Established **governance-ready architecture** aligned with ADB and PSW frameworks.
- Proven replicability for upcoming BCPs (Badini, Ghulam Khan, Sost).

---

## 🧠 Future Enhancements
1. **API Integration** with PSW & WeBOC systems for live data sync  
2. **Power BI Service Deployment** for secure stakeholder access  
3. **Mobile dashboard layout** for on-site field reviews  
4. **AI/ML Risk Detection** for predictive fault escalation and SLA breach forecasting  
5. **Auto-Generated BCP Scorecards** for quarterly ADB reporting

---

## 📂 Repository Contents
| Folder | Description |
|--------|--------------|
| `/docs` | Technical notes and institutional report |
| `/sql` | Database schema & queries |
| `/data` | Simulated datasets (non-confidential) |
| `/visuals` | Power BI screenshots |
| `/powerbi` | Editable `.pbix` dashboard file |

---

## 🔒 Disclaimer
> All data in this repository is simulated or redacted for confidentiality.  
> The methods, schema design, and visuals reflect real institutional architecture developed for PLPA under the CAREC-RIBS/ITTMS framework.

---

## 👤 Author
**Muhammad Danish**  
*Technical Specialist (Analytics) – PLPA / ITTMS, FBR*  
*Business Analytics & Compliance Executive – Howdy Group*  
📧 danish.hanjra@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/chdanish7)  
🧮 [GitHub Portfolio](https://github.com/danyboycr)
