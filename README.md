# ⚡ EV Battery Swapping Analytics – VoltRelay Energy

## 📌 Project Overview

This project was developed as part of the **Gradient Learnings Data Analytics Hackathon**.

The project focuses on analyzing EV battery-swapping data from VoltRelay Energy to identify operational challenges, evaluate battery health, understand customer experience, and explore revenue patterns.

Using Python and data analytics techniques, the project transforms large datasets into meaningful insights that can help identify opportunities for operational improvement.

## 🎯 Project Objectives

- Analyze battery-swapping activities and operational failures.
- Identify cities with higher operational failure rates.
- Evaluate battery health and degradation patterns.
- Analyze customer support tickets and satisfaction.
- Examine revenue across different tariff categories.
- Investigate the relationship between environmental conditions and operational performance.

## 🛠️ Technologies Used

- **Python** – Data analysis and processing
- **Pandas** – Data manipulation
- **DuckDB** – Efficient processing of large CSV files
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Jupyter Notebook** – Interactive analysis

## 📂 Project Structure

```text
VoltRelay-EV-Battery-Swapping-Analytics/
│
├── VoltRelay_Hackathon_Final.ipynb
├── VoltRelay_Data_Analytics_Report.pdf
├── README.md
└── requirements.txt
```

## 📊 Dataset Description

The project uses multiple datasets containing information about:

- Battery-swapping events
- Battery health and performance
- Charging stations
- Riders
- Customer support tickets
- City-level environmental conditions
- Station operating conditions

**Note:** The original datasets are not included in this repository.

## 🔍 Analysis Performed

### 1. Operational Failure Analysis

Analyzed millions of battery-swapping attempts to understand completed swaps and operational failures.

### 2. City-wise Failure Analysis

Compared operational failure rates across different cities to identify variations in station performance.

### 3. Battery Health Analysis

Examined battery State of Health (SOH), degradation patterns, and battery retirement information.

### 4. Customer Experience Analysis

Analyzed customer support tickets, resolution rates, and satisfaction scores across different support categories.

### 5. Revenue Analysis

Compared revenue across four tariff categories:

- PARTNER
- STD
- PEAK
- OFFPEAK

### 6. Environmental Impact Analysis

Compared operational failure rates on heat-alert and non-heat-alert days across cities.

## 📈 Key Findings

- Analyzed approximately **3.87 million** battery-swapping attempts.
- Identified an overall operational failure rate of **3.76%**.
- Analyzed **6,500 batteries** to understand battery health.
- Examined customer satisfaction across different support categories.
- Compared revenue across four tariff categories.
- Observed differences in operational failure rates between heat-alert and non-heat-alert days.

## 💻 Installation and Usage

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/VoltRelay-EV-Battery-Swapping-Analytics.git
```

### 2. Navigate to the project folder

```bash
cd VoltRelay-EV-Battery-Swapping-Analytics
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the analysis notebook

Open `VoltRelay_Hackathon_Final.ipynb` in Jupyter Notebook.

**Dataset requirement:** The original CSV files are not included. To rerun the analysis, place the required datasets in the folder structure expected by the notebook and update the dataset paths if necessary.

## 📁 Project Deliverables

- **Jupyter Notebook:** Complete data analysis, SQL queries, and visualizations.
- **Project Report:** Summary of the methodology, findings, and recommendations.
- **Demo Video:** Demonstration of the project and its key findings.

## 🎓 Learning Outcomes

Through this project, I gained practical experience in:

- Processing large datasets using DuckDB.
- Performing exploratory data analysis.
- Identifying patterns and trends in operational data.
- Creating data visualizations.
- Communicating analytical findings.

## 👩‍💻 Author

**Anuska Gupta**  
B.Tech Artificial Intelligence and Data Science

## 🏆 Hackathon

**Gradient Learnings Data Analytics Hackathon**  
**Project:** EV Battery Swapping Analytics – VoltRelay Energy

---

⭐ If you find this project interesting, feel free to explore the notebook and its analysis.