# 📈 Sales Performance Dashboard — Tableau

![Tableau](https://img.shields.io/badge/Tableau-Desktop-E97627?logo=tableau&logoColor=white)
![Dashboards](https://img.shields.io/badge/Dashboards-2-blueviolet)
![Worksheets](https://img.shields.io/badge/Worksheets-14-2563eb)
![KPI](https://img.shields.io/badge/KPIs-YOY%20%2B%20Sparklines-16a34a)

An interactive **Tableau sales dashboard** with YOY KPI cards, sparkline trends, geographic performance maps and manager-level analysis — built on Superstore-style sales data.

> 🎯 Sales  Profit  Quantity  YOY growth  Region & state maps  monthly segment trends — all in one workbook.

---

## 📑 Dashboards

### 🌙 Dashboard 1 — Sales Dashboard
The full executive view.
- 🎯 **KPI cards:** Total CY Sales  Total CY Profit  Total CY Quantity — each with **YOY % indicator**
- 📈 **Visuals:** monthly **sparklines** (CY vs PY) under every KPI  Avg Sales & Avg Profit by State (hexmap)  Region-wise sales map  Sales & Profit by State (CY vs PY)  Monthly Sales by Segment (area)  Total Sales by Location & Manager
- 💡 **Insight:** instantly shows *what* is selling, *where* it's selling, and whether it's *up or down* versus last year.

### ☀️ Dashboard 2 — Sales Dashboard Light
The same story on a light theme.
- 🎨 Identical components, re-styled for light backgrounds — ideal for printing and presentations
- 💡 **Insight:** two themes, one dataset — pick the look for the room you're presenting in.

---

## 🧩 Worksheet Inventory

| # | Worksheet | Type | Purpose |
|---|---|---|---|
| 1 | Sales KPI | KPI card | CY sales + YOY indicator |
| 2 | Profit KPI | KPI card | CY profit + YOY indicator |
| 3 | Qty KPI | KPI card | CY quantity + YOY indicator |
| 4 | Sales Sparkline | Line | Monthly CY vs PY sales |
| 5 | Profit Sparkline | Line | Monthly CY vs PY profit |
| 6 | Qty Sparkline | Line | Monthly CY vs PY quantity |
| 7 | Monthly Sales by Segment | Area | Consumer / Corporate / Home Office trend |
| 8 | Avg Sales by State | Map (hex) | Average sales per state |
| 9 | Avg Profit by State | Map (hex) | Average profit per state |
| 10 | Region Wise Sales | Map | Sales by region |
| 11 | Sales and Profit by State | Map (shapes) | CY vs PY sales & profit per state |
| 12 | Total Sales by Location & Manager | Bar | Regional manager performance |
| 13 | Avg Sales by State Count | Map support | Hexmap count helper |
| 14 | Avg Profit by State Count | Map support | Hexmap count helper |

---

## 🧮 Calculations & Parameters

| Calculation | Purpose |
|---|---|
| `Total CY Sales` / `Total PY Sales` | Current & prior-year sales |
| `YOY Sales` / `YOY Sales Indicator` | % growth + up/down arrow |
| `Total CY Profit`  `Total PY Profit`  `YOY Profit` | Same for profit |
| `Total CY Qty`  `Total PY Qty`  `YOY Qty` | Same for quantity |
| `Avg Sales Overall` / `Avg Sales State wise` | Benchmark vs state average |
| `Avg Profit Overall` / `Avg Profit State wise` | Profit benchmarks |
| `min max month` / `min max Qty` / `min max Profit` | Sparkline axis bounds |
| `Select Measure` (parameter) + `Dynamic Measure` | **Switch the measure** shown in views |
| `hexmap` / `Abbreviation` | Hex-tile state mapping |

---

## 🗄 Data

| Item | Detail |
|---|---|
| 🗂️ Source | Sales Data extract (packaged `.hyper`) |
| 🧱 Fields | Order Date  Region  State/Province  Category  Segment  Ship Mode  Regional Manager |
| 📦 Packaging | `.twbx` — workbook + extract travel together (fully portable) |

---

## ⚡ Features

🎛️ Select-Measure parameter  🔀 CY vs PY comparisons  🟢🔴 YOY indicators  ✨ sparklines under every KPI  🗺️ hexmap + shape maps  🌙 light & dark dashboards  📦 packaged workbook (no external data needed)

---

## 🚀 Run It

1. Open `Sales_Dashboard.twbx` in **Tableau Desktop** (or Tableau Public / Reader for viewing).
2. Use the **Select Measure** parameter to switch the dynamic metric.
3. Hover maps for state detail; compare CY vs PY across every KPI card.

---

## 👤 Author

**Saloni Jain** — data preparation, calculated fields & parameters, dashboard design and theming.
