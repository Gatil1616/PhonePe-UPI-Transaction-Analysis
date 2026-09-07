<div align="center">

<!-- Animated header banner (capsule-render) -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:5F259F,100:8B5CF6&height=220&section=header&text=PhonePe%20UPI%20Transaction%20Dashboard&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Real-time%20insights%20into%20UPI%20transactions,%20merchants,%20banks%20and%20fraud%20trends&descAlignY=58&descSize=16" width="100%"/>

<!-- Animated typing subtitle -->
<a href="#">
  <img src="https://readme-typing-svg.demolab.com?font=Poppins&size=20&duration=3000&pause=1000&color=5F259F&center=true&vCenter=true&width=700&lines=Built+in+Microsoft+Excel+%7C+Pivot+Tables+%2B+Slicers+%2B+Formulas;502K%2B+Raw+Records+%E2%86%92+2%2C40%2C916+Clean+Transactions;%E2%82%B921.07+Cr+Analyzed+%C2%B7+7+UPI+Apps+%C2%B7+11+States+%C2%B7+8+Banks" alt="Typing SVG" />
</a>

<br/>

<!-- Badges -->
<img src="https://img.shields.io/badge/Built%20With-Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Excel"/>
<img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge" alt="Status"/>
<img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License"/>
<img src="https://img.shields.io/badge/Made%20with-%E2%9D%A4-red?style=for-the-badge" alt="Made with Love"/>

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Bar%20Chart.png" width="70"/>

</div>

---

## 📌 Overview

The **PhonePe UPI Transaction Dashboard** is an interactive, single-view analytics dashboard built entirely in **Microsoft Excel**, designed to analyze real-time-style UPI transaction data across **cities, banks, merchants, UPI apps, and time**.

The underlying dataset contains **502,887 raw transaction records** (May 2026) across **7 UPI apps**, **11 states**, **42 cities**, **8 partner banks**, and **17 merchant categories**. After cleaning, this rolls up into **2,40,916 valid transactions worth ₹21.07 Cr**, visualized through slicers, KPI cards, donut breakdowns, a choropleth-style India map, and an hour × day heatmap — so patterns in spending, success rate, and suspected fraud are visible at a glance.

> Built as part of an **AI & Data / Make Data Intelligent** masterclass project.

---

## 🖼️ Preview

<div align="center">
  <img src="assets/Dashboard-full.png" alt="Full Dashboard Preview" width="120%"/>
</div>


---

## 🎬 Demo Video

<div align="center">

[![Watch the Demo](./assets/video-thumbnail.png)](https://youtu.be/YOUR-VIDEO-ID)

*Click the thumbnail above to watch the full walkthrough on YouTube.*

</div>

> 💡 **How to add your real demo video** (pick one):
> - **YouTube (recommended, easiest):** Upload your screen-recording to YouTube (even as "Unlisted"), then replace `YOUR-VIDEO-ID` above with your video's ID, and `./assets/video-thumbnail.png` with a screenshot/thumbnail image saved in your `assets/` folder.
> - **Native GitHub video:** Open a new GitHub Issue in your repo, drag-and-drop your `.mp4` file into the comment box (don't submit the issue), wait for it to upload, then copy the generated `https://github.com/user-attachments/assets/...` link it creates. Paste that link directly below instead of the YouTube embed:
>   ```html
>   <video src="https://github.com/user-attachments/assets/YOUR-LINK" controls width="100%"></video>
>   ```
>   This plays natively inside the README on GitHub, no click-through needed — but the link only works because it's hosted on GitHub's own CDN, not an arbitrary external URL.

---

## ✨ Key Features

- 🔄 **Live-style KPI Cards** — Total Transactions, Total Amount, Total Cashback, Success Rate, and Suspected Fraud, all in one glance.
- 🎛️ **Dynamic Filter Panel** — Slice data instantly by **City, Gender, Merchant Category,** and **Merchant Name**.
- 🍩 **App & Status Breakdown** — Donut charts for transaction share by **UPI App** (PhonePe, Google Pay, Paytm, etc.) and by **Status** (Success/Failed/Pending/Refunded), each with a headline % in the center.
- 🗺️ **State-wise Heat Map** — Choropleth map of India showing transaction volume by state, paired with a ranked table.
- 🏦 **Bank & Transaction-Type Analysis** — Horizontal bar breakdowns of amount by bank and by transaction type (P2M, P2P, Bill Payment, etc.).
- ⏰ **Time-based Patterns** — Daily trend line, hourly transaction volume, and an **Hour × Day heatmap** to spot peak activity windows.
- 🚨 **Fraud Monitoring** — Dedicated suspected-fraud KPI to flag anomalies at a glance.

---

## 📊 Dashboard at a Glance

| Metric | Value |
|---|---|
| Total Transactions | **2,40,916** |
| Total Amount (INR) | **₹21.07 Cr** |
| Total Cashback (INR) | **₹16.67L** |
| Success Rate | **90.97%** |
| Suspected Fraud Cases | **8,244** |
| Top UPI App | **PhonePe — 49.5% share** |

---

## 🛠️ Tech Stack

<div align="center">

<img src="https://img.shields.io/badge/Microsoft%20Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white" alt="Excel"/>
<img src="https://img.shields.io/badge/Pivot%20Tables-217346?style=flat-square&logo=microsoftexcel&logoColor=white" alt="Pivot Tables"/>
<img src="https://img.shields.io/badge/Slicers%20%26%20Filters-217346?style=flat-square&logo=microsoftexcel&logoColor=white" alt="Slicers"/>
<img src="https://img.shields.io/badge/Data%20Visualization-8B5CF6?style=flat-square&logo=chartdotjs&logoColor=white" alt="Data Viz"/>

</div>

- **Microsoft Excel** — data modeling, pivot tables & pivot charts
- **Slicers** — interactive filtering (City, Gender, Merchant Category, Merchant Name)
- **Excel Map Chart** — state-wise transaction visualization
- **Conditional Formatting / Heatmap** — hour × day intensity matrix
- **Formulas** — aggregation, KPI calculations, formatted currency labels (₹, Cr, L)

---

## 🗃️ Dataset Schema

The `raw_upi_data` sheet holds **24 fields** per transaction, including:

`Transaction_ID` · `Transaction_Date` · `Transaction_Time` · `UPI_App` · `Customer_ID` · `Age_Group` · `Gender` · `State` · `City` · `Merchant_Name` · `Merchant_Category` · `Transaction_Type` · `Payment_Mode` · `Bank_Name` · `Amount_INR` · `Cashback_INR` · `Transaction_Fee_INR` · `Status` · `Failure_Reason` · `Device_OS` · `Risk_Score` · `Is_Suspected_Fraud` · `Hour` · `Day`

This granularity is what powers the dashboard's fraud-risk scoring, hour × day heatmap, and device/OS-level breakdowns.

---

## 📁 Folder Structure

```
📦 phonepe-upi-dashboard
 ┣ 📂 assets
 ┃ ┣ 🖼️ dashboard-full.png
 ┃ ┣ 🖼️ kpi-cards.png
 ┃ ┣ 🖼️ state-map.png
 ┃ ┗ 🖼️ video-thumbnail.png
 ┣ 📊 Phone_Pay_Excel_Project.xlsx
 ┃ ┣ 📄 raw_upi_data     (502,887 raw transaction records)
 ┃ ┣ 📄 Sheet1           (pivot summaries & aggregations)
 ┃ ┣ 📄 Image matrices   (UPI app share matrix for chart visuals)
 ┃ ┗ 📄 UPI Dashboard    (final interactive dashboard)
 ┗ 📄 README.md
```

---

## 🚀 How to Use

1. **Clone this repository**
   ```bash
   git clone https://github.com/Gatil1616/PhonePe-UPI-Transaction-Analysis

   ```
2. **Open the Excel file**
   Open `Phone_Pay_Excel_Project.xlsx` in Microsoft Excel (2016 or later recommended for map charts). Go to the **UPI Dashboard** sheet tab.
3. **Explore with filters**
   Use the **Filter Panel** on the left (City, Gender, Merchant Category, Merchant Name) to slice the dashboard interactively.
4. **Enable content / macros** (if prompted) to ensure all charts and slicers render correctly.

---

## 🧠 Insights Uncovered

- **PhonePe leads UPI app usage** with a 49.5% share, followed by Google Pay (21.4%) and Paytm (14.4%).
- **P2M (merchant) transactions** dominate transaction-type volume at ₹8.90 Cr.
- **HDFC Bank and SBI** account for the highest transaction amounts among partner banks.
- Transaction activity **peaks in the evening hours**, visible clearly in the Hour × Day heatmap.
- Suspected fraud sits at **8,244 cases**, a metric worth cross-referencing against high-risk states/banks for deeper investigation.

---

## 🗺️ Roadmap

- [ ] Add a dynamic date-range slicer
- [ ] Add legends/scales to the map and heatmap visuals
- [ ] Reconcile Success Rate KPI with the Status donut for consistent reporting
- [ ] Publish a Power BI version for web-based interactivity

---

## 🤝 Contributing

Suggestions and improvements are welcome! Feel free to open an issue or submit a pull request.

---

## 👤 Author

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=28&duration=2500&pause=800&color=5F259F&center=true&vCenter=true&width=500&lines=Gatil+Dhawan;Aspiring+Data+Analyst" alt="Gatil Dhawan" />

This project was created as part of my data analytics portfolio to demonstrate skills in **Excel, data cleaning, data analysis, pivot tables, visualization, and dashboard development.**

## 👤 Connect with Me

<a href="https://www.linkedin.com/in/gatil-dhawan-474097340/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="https://github.com/Gatil1616">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>
<a href="mailto:sandeepsks008@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-D1483?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
</a>

</div>

---

## ⭐ Show Some Love

If you found this project useful or interesting, consider giving it a **star** ⭐ — it helps a lot!

<div align="center">

<img src="https://img.shields.io/github/stars/Gatil1616/PhonePe-UPI-Transaction-Analysis?style=social" alt="Star"/>

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8B5CF6,100:5F259F&height=120&section=footer" width="100%"/>
</div>
