# indian-elections-dashboard
Interactive Tableau dashboard analyzing Indian parliamentary elections from 1952 to 2024, with dynamic visual insights by year, state, constituency, and party.

🔗 **Live Dashboard**: [View on Tableau Public](https://public.tableau.com/views/INDIANELECTIONDASHBOARD/OVERVIEW?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 📂 Dashboard Pages

### 1. 📘 Overview – Historical Summary
- Displays first and latest election year.
- Shows overall voter turnout (including gender-wise trends).
- Bubble chart highlights party-wise seat distribution over time.
- Dynamic visuals that switch to bar charts for selected years.
- Interactive filters for **year** and **party alliance** using DZB logic.

### 2. 🗳️ 2024 Insight – State-Level Snapshot
- Focused example: **Maharashtra**.
- State KPIs: voter turnout, number of constituencies, parties, and polling stations.
- Visuals include:
  - % EVM usage across states
  - Postal voting by top 10 states
  - Gender-wise turnout
  - Party-wise seats won in state
- **Dynamic State Filter**: when set to “All India”, switches to a national map view showing the top winning party per state.

### 3. 🧭 Constituency Explorer
- Deep-dive into individual constituencies (e.g., Gandhinagar).
- KPIs: turnout, segments, contestants, polling stations.
- Visuals:
  - Nominations vs actual contestants
  - Elector count per constituency
  - Bubble chart for nominations vs electors
  - Avg. electorate per polling station
- **Dynamic View**: changes to top 10 constituencies nationwide when State = "All India".

### 4. 🏆 Winner Profile & Margin Analysis
- Displays:
  - Top winning party and seat count
  - Gender-wise analysis of winners (donut charts)
  - Map showing leading party across selected state
  - Table of winning candidates by constituency
- **Parameter-Based Dynamic Views**:
  - Selecting a **constituency** shows winner and runner-up.
  - Setting **State = All India** switches to national map + top 2 parties nationwide.

---

## 🎯 Key Features
- Built using **Tableau Dynamic Zone-Based Visibility (DZB)** for seamless chart switching.
- Full interactivity via parameters: `Year`, `State`, `Constituency`, `Alliance`.
- India-themed visual identity: modern color palettes for clarity and accessibility.

---

## 📊 Technologies
- **Tableau Desktop**
- **Tableau Public**
- **Data Cleaning**: Microsoft Excel, basic scripting
- **Maps**: OpenStreetMap, Tableau geospatial features

---


## 🧑‍💻 Author
**Biprajit Choudhary**  

---

## 📸 Preview

![Overview Page](images/OVERVIEW.png)  
![2024 Insight](images/2024 insight.png)  
![Constituency Explorer](images/Consistuency Explorer.png)  
![Winner Analysis](images/Winner.png)

---

## 📄 License
This project is open for educational and non-commercial use. Contact the author for reuse permissions.

