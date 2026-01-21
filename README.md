
# 📊 AI Models Performance Analysis

### A Data-Driven Comparison of Intelligence, Cost, Speed, and Usability

---

## 📌 Project Overview

Choosing the right AI language model is no longer about intelligence alone.
Modern models vary widely in **cost, speed, latency, and context capacity**, making selection a multi-dimensional decision.

This project delivers a **complete end-to-end data analytics analysis** comparing modern AI language models across key performance and business metrics to support **informed, use-case-driven decisions**.

The project is **purely analytical** — no machine learning, no black-box modeling.

---

## 🎯 Objectives

* Compare AI models across **intelligence, price, speed, latency, and context window**
* Identify **high-value and cost-efficient models**
* Understand **speed vs latency trade-offs**
* Evaluate **creator-level strategies**
* Map models to **real-world use cases**
* Build **clear, decision-ready dashboards**

---

## 🗂 Dataset Description

Each row represents a **unique AI language model**.

### Key Columns:

* `Model` – Model name
* `Creator` – Organization / vendor
* `Context_Window_Tokens` – Maximum token capacity
* `Intelligence_Index` – Relative intelligence score
* `Price_USD_per_1M` – Cost per 1M tokens
* `Speed (median token/s)` – Throughput
* `Latency (First Answer Chunk /s)` – Initial response delay

---

## 🛠 Tools & Technologies

* **Python**
* **NumPy**
* **Pandas**
* **Matplotlib**

❌ No Seaborn
❌ No Machine Learning

---

## 🔍 Analysis Workflow

### 1️⃣ Data Cleaning & Preparation

* Numeric conversion & validation
* Handling missing / invalid values
* Context window normalization
* Feature engineering (e.g., Intelligence per Dollar)

---

### 2️⃣ Exploratory Data Analysis (EDA)

#### ✔ Creator-Level Analysis

* No single creator dominates all metrics
* Vendors follow distinct optimization strategies

#### ✔ Intelligence vs Price

* Intelligence does **not scale linearly** with price
* Clear **diminishing returns** at higher cost tiers

#### ✔ Speed vs Latency

* Speed and latency are **not the same**
* Fast models can still feel slow to users

#### ✔ Context Window Analysis

* Large context windows increase cost
* Context size ≠ intelligence

#### ✔ Balanced Models

* Models strong across all dimensions are **rare**
* Trade-offs are unavoidable

---

## 📊 Dashboards & Visualizations

All dashboards were created using **Matplotlib only**, following clean visualization principles.

### Key Dashboards:

* Creator-level performance comparison
* Intelligence vs Price (segmented & ranked)
* Speed vs Latency (ranked horizontal bars)
* Top models by context window
* Balanced model identification
* Use-case-driven model distribution

Each chart is:

* Properly aligned
* Fully labeled
* Value-annotated
* Portfolio & interview ready

---

## 👥 Use-Case Mapping

| User Type                      | Recommended Model Traits         |
| ------------------------------ | -------------------------------- |
| Data Scientists / ML Engineers | High intelligence, large context |
| Business Analysts              | Cost-efficient, balanced models  |
| Developers                     | Low latency, good speed          |
| Researchers                    | Maximum intelligence & context   |
| General Users                  | Balanced, mid-tier models        |

---

## 📌 Key Insights

* 💡 There is **no universally best model**
* 💰 Higher price ≠ higher intelligence
* ⚡ Speed ≠ responsiveness
* 📉 Diminishing returns exist in premium tiers
* 🎯 Model selection must be **use-case driven**

---

## ✅ Recommendations

* Avoid defaulting to premium models without justification
* Use **intelligence-per-dollar** for cost-sensitive decisions
* Prioritize **low latency** for real-time systems
* Choose **high speed** for batch workloads
* Treat large context windows as **specialized features**

---

## ⚠ Limitations

* Intelligence index methodology not disclosed
* No time-series data
* Pricing may vary by deployment or region
* Real-world performance may differ under load

---

## 📁 Repository Structure

```
├── ai_models_performance.ipynb
├── data/
│   └── ai_models_performance.csv
├── dashboards/
│   └── *.png
├── README.md
```

---

## 🚀 How to Run

```bash
pip install pandas numpy matplotlib
```

Open and run:

```
ai_models_performance.ipynb
```


