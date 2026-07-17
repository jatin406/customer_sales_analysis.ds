# Customer & Sales Data Analysis Project

A comprehensive data analytics project containing two production-level business intelligence workflows: **Customer Churn Analysis** and **Corporate Sales Performance Benchmarking**. Built using Python, Pandas, and modern visualization libraries.

---

## 📌 Project Overview & Objectives

### 1. Customer Churn Analysis (`customer_churn.csv`)
* **Objective:** Evaluate historical consumer behavioral metrics, usage characteristics, and structural agreement types to identify underlying factors accelerating user cancellations.
* **Key Focus:** Impact of contractual terms (Month-to-Month vs. Long-Term) and financial billing pressure points against consumer retention lifecycles.

### 2. Corporate Sales Performance (`sales_data.csv`)
* **Objective:** Conduct a strict audit of high-level transaction ledgers to optimize regional inventory velocity and target operational growth vectors.
* **Key Focus:** Calculating gross revenue distributions, tracking primary volume drivers, and locating key geographic market growth engines.

---

## 💻 Setup & Installation Instructions

Follow these step-by-step instructions to configure and execute this project locally on your machine:

### Prerequisites
Ensure you have **Python 3.8+** and **pip** installed on your system.

## Install the strict dependency matrix using the following terminal command:

pip install pandas matplotlib seaborn

##Launch your preferred interface (VS Code or Jupyter Notebook) and execute the pipeline:

jupyter notebook customer_analysis.ipynb

📂 Project Structure & Hierarchy
​The workspace repository follows a clean, modular structure as outlined below:

├── customer_analysis.ipynb      # Core Python workspace containing markdown analysis & code execution
├── customer_data.csv            # Source data tracking demographics and subscriber churn indicators
├── sales_data.csv               # Transactional sales ledger tracking items, quantities, and regions
└── README.md                  # Detailed documentation and repository architecture guide

🛠️ Technical Implementation Details
​Data Manipulation & Architecture
​Pandas Core Execution: Cleaned data structures, dropped null records dynamically, and formatted currency/integer matrices.
​Algorithmic Aggregations: Performed multi-level data aggregations using .groupby(), .sum(), and conditional indexes (.idxmax()) to extract maximum high-tier metrics.
​Visual Documentation & Functionality
​Designed multi-axis visualizations using Seaborn and Matplotlib.
​Handled figure rendering anomalies automatically across multiple IDE runs using proper background cleanups (plt.close('all')).
