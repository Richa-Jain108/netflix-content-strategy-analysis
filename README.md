# 🎬 Netflix Content Strategy Analysis

### End-to-End Analysis of Netflix's Global Content Portfolio Using Python & Exploratory Data Analysis (EDA)

This project analyzes Netflix's global catalog of Movies and TV Shows to uncover content trends, audience preferences, and regional growth opportunities. The objective is to provide data-driven recommendations that can help Netflix optimize content investments, strengthen viewer engagement, and expand its presence across international markets.

---

## 📄 Project Deliverables

| Resource                                                                    | Description                                                                     |
| --------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| 📓 [Jupyter Notebook](./notebooks/netflix_content_strategy_analysis.ipynb)  | Complete analysis, code, visualizations, insights, and recommendations          |
| 📑 [Analysis Report (PDF)](./reports/Netflix_Content_Strategy_Analysis.pdf) | Detailed report with findings, business insights, and strategic recommendations |
| 📊 [Dataset](./data/netflix.csv)                                            | Netflix content catalog dataset used for the analysis                           |

---

## 📌 Business Problem

### About NETFLIX

Netflix is one of the most popular media and video streaming platforms. They have over 10000 movies or tv shows available on their platform, as of mid-2021, they have over 222M Subscribers globally.

To sustain growth and maximize content ROI, Netflix must continuously answer critical strategic questions:

* What type of content should be produced?
* Which markets deserve additional investment?
* Are TV Shows outperforming Movies?
* Which genres and regions drive content growth?
* How can Netflix strengthen its global content strategy?

Using Netflix's content catalog, this analysis aims to generate actionable insights that support strategic content  deciding which type of shows/movies to produce and how they can grow the business in different countries.

---

## 🎯 Project Objectives

The analysis focuses on answering the following business questions:

* How has Netflix's content portfolio evolved over time?
* What is the distribution of Movies vs TV Shows?
* Which countries contribute the most content?
* Which directors and actors appear most frequently?
* What are the dominant genres across regions?
* Is Netflix shifting its focus toward TV Shows?
* What seasonal patterns exist in content additions?
* Which regions present opportunities for future expansion?

---

## 📊 Dataset Overview

The dataset contains information on **8,807 Netflix titles**, including:

| Feature      | Description           |
| ------------ | --------------------- |
| Show ID      | Unique identifier     |
| Type         | Movie or TV Show      |
| Title        | Content title         |
| Director     | Director information  |
| Cast         | Cast members          |
| Country      | Production country    |
| Date Added   | Date added to Netflix |
| Release Year | Original release year |
| Rating       | Content rating        |
| Duration     | Runtime or seasons    |
| Listed In    | Genre classification  |
| Description  | Content summary       |

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🔍 Analytical Approach

### 1. Data Understanding

* Dataset structure review
* Data type inspection
* Statistical summary analysis

### 2. Data Cleaning & Preprocessing

* Missing value assessment
* Date transformation
* Unnesting multi-valued columns
* Country, Cast, Director, and Genre normalization

### 3. Exploratory Data Analysis

* Univariate analysis
* Bivariate analysis
* Temporal trend analysis
* Country-level content analysis
* Actor and Director analysis
* Genre distribution analysis

### 4. Business Insight Generation

* Content strategy evaluation
* Regional content assessment
* Growth opportunity identification

---

## 📈 Key Insights

### Content Portfolio

* Movies represent the majority of Netflix's catalog.
* TV Shows have experienced significant growth in recent years.
* Netflix's content strategy appears to be increasingly diversified across content formats.

### Geographic Distribution

* The United States contributes the largest share of content.
* India is one of Netflix's strongest content-producing markets.
* Content production remains concentrated in a limited number of countries.

### Content Growth Trends

* Netflix significantly expanded its content library between 2015 and 2020.
* Content additions accelerated during Netflix's global expansion phase.

### Audience & Genre Trends

* Drama-related content dominates the platform.
* Certain regions exhibit strong preferences for localized content.
* Genre distribution varies significantly across countries.

---

## 🎯 Business Impact

This analysis provides a structured framework for content investment and market expansion decisions by:

* Identifying high-performing content formats.
* Highlighting regions with strong content production potential.
* Revealing long-term shifts in audience preferences.
* Supporting data-driven content acquisition and production planning.
* Reducing reliance on intuition-based content investment decisions.

---

## 💡 Strategic Recommendations

### 1. Increase Investment in High-Performing TV Shows

TV Shows demonstrate strong growth and contribute to long-term viewer engagement through episodic consumption.

### 2. Expand Local-Language Originals

Increase investment in localized productions within high-growth regions to improve subscriber acquisition and retention.

### 3. Reduce Geographic Content Concentration

Diversify production investments beyond traditional content hubs to strengthen global market penetration.

### 4. Prioritize Data-Driven Content Planning

Use regional viewing preferences and genre trends to guide future content acquisition and production strategies.

### 5. Strengthen International Content Portfolio

Expand content production in emerging markets where Netflix has significant growth potential.

---

## 📂 Repository Structure

```text
netflix-content-strategy-analysis/
│
├── data/
│   └── netflix.csv
│
├── notebooks/
│   └── netflix_content_strategy_analysis.ipynb
│
├── reports/
│   └── Netflix_Content_Strategy_Analysis.pdf
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 Deliverables

* Complete Exploratory Data Analysis (EDA)
* Data Cleaning & Feature Engineering
* Business Insights
* Strategic Recommendations
* Jupyter Notebook
* PDF Report

---

## 👤 Author

**Richa Jain**

Data Analyst focused on transforming raw data into actionable business insights through analytics, visualization, and strategic decision-making.
