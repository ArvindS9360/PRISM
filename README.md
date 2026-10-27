# Multi-Tier Supply Chain Lead-Time Variance Analysis & Diagnostic Engine

[![PRISM Semester 1](https://img.shields.io/badge/PRISM-Semester%201-blue.svg)](#)
[![Domain](https://img.shields.io/badge/Domain-Supply%20Chain%20%7C%20Data%20Engineering-green.svg)](#)

A 6-semester longitudinal research and software development project under the **PRISM (Project Based Research for Innovative Solutions and Metamorphosis)** framework at **Department of Computer Applications, Kristu Jayanti University**.

---

## 📌 Project Overview
In modern retail and e-commerce ecosystems, supply chain reliability often suffers from unmeasured lead-time volatility. Standard enterprise operations frequently depend on static average lead times, which conceals standard deviation ($\sigma$) and downstream operational bottlenecks. 

This project develops an end-to-end framework to:
1. Ingest and structure granular logistical order data.
2. Quantify hidden vendor variability and On-Time In-Full (OTIF) compliance.
3. Provide interactive visual diagnostics and train machine learning models to forecast shipping delays proactively.

---

## 🗺️ 6-Semester Development Roadmap

| Semester | Phase | Key Milestones & Deliverables | Status |
| :---: | :--- | :--- | :---: |
| **Sem 1** | **Problem ID & Framework** | Literature review, prior art analysis (IBM/SAP), system architecture, and formal proposal. | **Completed** |
| **Sem 2** | **Data Engineering** | Entity-Relationship Diagram (ERD), SQL database design, and automated Python (Pandas) ETL pipeline. | Planned |
| **Sem 3** | **Analytics Engine** | Computation engine for OTIF metrics, mean lead times, and variance ($\sigma$) using `scipy.stats`. | Planned |
| **Sem 4** | **BI & Interface** | Interactive dashboard (Streamlit / Power BI) featuring vendor risk matrix quadrants. | Planned |
| **Sem 5** | **Predictive Modeling** | Machine learning regression models (Random Forest / XGBoost) to forecast delivery delay days. | Planned |
| **Sem 6** | **Testing & Final Viva** | Synthetic stress testing, full thesis documentation, demo video, and final project defense. | Planned |

---

## 📂 Repository Structure
* `/docs`: Project proposals, synopses, semester-end progress reports, and architecture diagrams.
* `/data`: Sample procurement and purchase order datasets (raw and processed).
* `/src`: Ingestion scripts, database schemas, statistical engines, and dashboard code.

---

## 👥 Team & Acknowledgments
* **Author / Contributor:** [Your Name] (Roll No: [Your Roll Number])
* **Programme:** Department of Computer Applications, Kristu Jayanti University
* **Course:** PRISM Semester I
