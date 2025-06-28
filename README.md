# 🇮🇳 India General Election Results Analysis – 2024 📊

An interactive and insightful Power BI dashboard project analyzing the 2024 Indian General Elections. It delivers a comprehensive understanding of election outcomes across the country — from national alliances to detailed constituency-level data.

---

## 🗂 Project Overview

This dashboard allows users to:
- Analyze seat distribution at the national level.
- Compare major alliances: **NDA**, **I.N.D.I.A.**, and **Others**.
- Dive into state-wise performance and demographics.
- View detailed results by constituency and candidate.
- Navigate seamlessly across six interactive pages.

---

## 🛠 Tools & Technologies Used

| Tool/Technology | Purpose                                           |
|-----------------|---------------------------------------------------|
| Power BI        | Dashboard creation & visual reporting             |
| DAX             | Custom measures & calculations                    |
| Power Query     | Data transformation & cleaning                    |
| Data Model View | Defining table relationships and schema design    |

---

## 🧱 Data Model

The data model uses a star schema with the following key tables:

- **partywise_results**: Party names and alliances
- **states**: State-level metadata
- **constituencywise_results**: Summary results by constituency
- **constituencywise_details**: Candidate-level breakdown including votes
- **statewise_results**: Aggregated state-level data

> 🔄 Proper relationships allow for smooth drill-through and interactivity across visuals.

---

## 📊 Dashboard Pages

### 1️⃣ Landing Page – Navigation Hub ( [Visit Landing Page](https://github.com/Rohan-pokale/Power-Bi-Project2-Indian_General_Election_Result_Dashboard/blob/main/Page1-Landing%20Page.PNG) )
- Quick intro to dashboard modules
- 4 navigation tiles: Overview, State Demographics, Political Landscape, Constituency Analysis
- Engaging visuals and voting info (dates & result day)

---

### 2️⃣ Overview Analysis – National Summary ( [Visit Overview Analysis Page](https://github.com/Rohan-pokale/Power-Bi-Project2-Indian_General_Election_Result_Dashboard/blob/main/Page2-Overview%20Analysis.PNG) )
- Total Seats: 543
- NDA: 292 (54%) | I.N.D.I.A.: 234 (43%) | Others: 17 (3%)
- Alliance-wise seat distribution
- Party logos and visual arc display
- Tooltip support for deeper insight

---

### 3️⃣ State Demographics Analysis ( [Visit State Demographics Analysis Page](https://github.com/Rohan-pokale/Power-Bi-Project2-Indian_General_Election_Result_Dashboard/blob/main/Page3-State%20Demographics%20Analysis.PNG) )
- Interactive state maps:
  - Total seats & alliance majority per state
  - Winning party by constituency
  - NDA vs I.N.D.I.A. dominance map
- Filter by state for focused drilldown

---

### 4️⃣ Political Landscape by State ( [Visit Political Landscape by State Page](https://github.com/Rohan-pokale/Power-Bi-Project2-Indian_General_Election_Result_Dashboard/blob/main/Page4-Political%20Landscape%20By%20State.PNG) )
- Select state (e.g., Maharashtra) to see:
  - Alliance-wise seat tally
  - Party-wise result table
  - Seat share donut chart
  - District-level seat distribution map

---

### 5️⃣ Constituency Analysis ( [Visit Constituency Analysis Page](https://github.com/Rohan-pokale/Power-Bi-Project2-Indian_General_Election_Result_Dashboard/blob/main/Page5-Constituency%20Analysis.PNG) )
- View any Lok Sabha seat (e.g., **Wayanad**)
- Total, EVM, and postal votes
- Candidate performance:
  - Winner, Runner-up, 2nd Runner-up
  - Vote count and vote share
- Total candidates participated

---

### 6️⃣ Details Grid – Full Dataset ( [Visit Details Grid Page](https://github.com/Rohan-pokale/Power-Bi-Project2-Indian_General_Election_Result_Dashboard/blob/main/Page6-Details%20Grid.PNG) )
- Tabular data view of all constituencies
- Fields: Winner, Runner-up, Party, Alliance, Votes, Margin
- Highlighted totals and winning margins
- Supports visual filtering and export

---

## 🧠 Key Insights

- NDA holds clear majority with 292 seats
- I.N.D.I.A. dominates in southern and eastern India
- Regional parties remain influential in several states
- Tight contests in multiple constituencies
- Powerful geographic insights via maps

---

## 🧩 Problem Solved by the Dashboard

> "Election data is often vast, complex, and hard to interpret. This dashboard makes it meaningful, visual, and actionable."

### Challenges Addressed:

1. **Scattered Election Data Sources**
   - ✅ Unified national, state, and constituency-level results in one platform.

2. **Lack of Visual Interpretation**
   - ✅ Used intuitive visuals (maps, charts, cards) for deep insights at a glance.

3. **Alliance and Party Complexity**
   - ✅ Separated and compared alliances (NDA vs I.N.D.I.A.) clearly.

4. **Difficulty in Analyzing Margin-Based Trends**
   - ✅ Included vote margins and seat wins to track competitiveness.

5. **Manual Effort in Result Comparison**
   - ✅ Drill-through navigation for detailed side-by-side constituency and state comparisons.

6. **Need for Micro & Macro-Level Insights**
   - ✅ Enables both zoomed-out (national) and zoomed-in (constituency) views with full data transparency.

---

## 👤 About Me

**Rohan Devanand Pokale**  
🎓 B.Tech – Computer Science (Data Science)  
🏫 Vishwakarma Institute of Technology, Pune  
📧 developer.rohan06@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/rohan-pokale-a774b2308)  

> Passionate about data Analysis, visualization, and impactful analytics solutions.

---

📌 _“This dashboard transforms election data into a powerful story of democracy, trends, and regional dynamics.”_
