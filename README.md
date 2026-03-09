# Insurance-Data-Analysis

# 🛡️ Prism Assurance: Comprehensive Insurance Data Analysis Dashboard

A dynamic and interactive Power BI visualization tool designed to monitor policy performance, claim distributions, and financial health for **Prism Insurance Pvt. Ltd.**

---

## Short Description / Purpose
The **Prism Insurance Dashboard** is an analytical reporting tool built to provide a 360-degree view of insurance operations. It enables stakeholders to track premium collections, evaluate claim settlement efficiency, and understand customer demographics across various policy sectors including Travel, Health, Auto, Life, and Home. This tool is intended for insurance analysts and executive management to optimize risk assessment and improve claim processing workflows.

---

## Tech Stack
The dashboard was built using the following tools and technologies:

* 📊 **Power BI Desktop** – Main data visualization platform used for report creation and layout design.
* 📂 **Power Query** – Data transformation layer used to clean and format policy and claim records.
* 🧠 **DAX (Data Analysis Expressions)** – Used for calculated measures such as Total Premium ($5.98\text{M}$), Claim Ratios, and conditional formatting.
* 📝 **Data Modeling** – Established relationships between Customer IDs, Policy Types, and Claim Statuses to enable seamless cross-filtering.
* 📁 **File Format** – `.pbix` for development and `.png` for dashboard previews.

---

## Data Source
* **Source:** Internal Company ERP & Claims Management System.
* **Structure:** The dataset includes over **10,000+** customer records, categorized by gender, age group (Adult, Elder, Young Adult), and five distinct policy types. It tracks financial metrics (Premium vs. Claim amounts) and operational statuses (Pending, Rejected, Settled).

---

## Features / Highlights

### 🚩 Business Problem
Insurance providers often struggle with "Data Silos," where premium income isn't easily reconciled against outstanding claims or specific demographics. 
**Key questions addressed:**
* Which policy type generates the highest revenue vs. the highest claim risk?
* What is the current ratio of Active vs. Inactive policies?
* How is the claim settlement pipeline performing (Settled vs. Pending)?
* Which age demographic accounts for the highest claim value?

### 🎯 Goal of the Dashboard
* To provide real-time visibility into the **$16.91\text{M}$** total claim liability.
* To identify high-performing sectors (e.g., Travel Insurance revenue).
* To monitor the gender and age distribution of the policyholder base to assess risk.

### 🔍 Walkthrough of Key Visuals
* **Executive KPIs (Top Center):** * **Premium Amount:** $5.98\text{M}$
    * **Coverage Amount:** $600.55\text{M}$
    * **Claim Amount:** $16.91\text{M}$
* **Policy Retention (Donut Chart):** Visualizes the split between **Active (52.91%)** and **Inactive (47.09%)** policies.
* **Revenue by Sector (Bar Chart):** Ranks policy types by premium; **Travel** is the leading contributor at $2.5\text{M}$.
* **Claim Status Pipeline (Funnel/Area Chart):** Tracks the volume of claims from **Rejected (4.4K)** to **Settled (3.4K)** and **Pending (2.3K)**.
* **Demographic Analysis (Line Chart & Cards):** * **Age Group:** Shows that **Adults** have the highest claim amount ($8.8\text{M}$).
    * **Gender:** Shows a nearly equal split with **5,003** Males and **5,001** Females.
* **Financial Matrix (Bottom Left Table):** A detailed breakdown of claim amounts by Policy Type and Status (Pending/Rejected/Settled) for granular auditing.

### 💡 Business Impact & Insights
* **Profitability Tracking:** Identifying that Travel insurance brings in the most premium ($2.5\text{M}$) allows the company to double down on successful marketing channels.
* **Operational Efficiency:** The high number of **Pending Claims (2.3K)** suggests a need to streamline the verification process to improve customer satisfaction.
* **Risk Mitigation:** Since the "Adult" segment carries the highest claim weight ($8.8\text{M}$), underwriters can adjust premiums for that specific bracket.

---

## Screenshots / Demos
![Insurance Data Analysis Dashboard](https://github.com/aryaMayank7/Insurance-Data-Analysis/blob/main/Insurance%20Data%20Analysis%20Dashboard.png)
