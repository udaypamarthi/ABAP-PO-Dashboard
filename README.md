# SAP Procurement Dashboard – ABAP (ALV with Drilldown)

A real-time dashboard developed using SAP ABAP to monitor Purchase Orders.
The application provides KPI visualization, colored risk indicators and 
drilldown to PO item details using OO ALV technology.

---

## 🚀 Features

- PO analytics dashboard for procurement teams
- Object-Oriented ALV Grid with hotspot navigation
- KPI banner using HTML Viewer (Total spend)
- Drilldown popup to EKPO item data (SALV)
- Dynamic row coloring based on spend thresholds
- Optimized UI using docking & splitter containers
- SQL joins on EKKO, EKPO, LFA1 tables

---

## 📊 Tech Stack

| Component | Technology |
|----------|------------|
| Language | ABAP (Object-Oriented) |
| UI       | CL_GUI_ALV_GRID, CL_GUI_HTML_VIEWER, SALV |
| DB Tables| EKKO, EKPO, LFA1 |

---

## 📸 Screenshots

![Dashboard](./Screenshots/dashboard_overview.png)
![Item Drilldown](./Screenshots/item_drilldown.png)

---

## 🧩 Architecture

- Event-driven UI with custom event handler
- MVC-aligned modular class structure
- RTTI field catalog generation

---

## ✍ Author

**Uday P**  
SAP ABAP Developer  

