# Job-Market-Analyzer-Scraping-and-Analyzing-Job-Portal-Data-


This project involves web scraping job listings from multiple job portals including Naukri, Indeed, and LinkedIn using Python. After collecting the data, exploratory data analysis (EDA) was performed to extract valuable insights on hiring trends, popular skills, demand by location, and salary patterns.

---

## 🔍 Objective

To automate the extraction of job listings from major platforms and perform data-driven analysis to understand trends in the job market.

---

## 📁 Project Structure

- `Web Scraping of different Job Sites.ipynb`: Handles web scraping from Naukri, Indeed, and LinkedIn.
- `analyze scrap data.ipynb`: Performs exploratory data analysis on the collected job data.

---

## ⚙️ Tools & Libraries

- **Python**
- `requests`, `BeautifulSoup` – for web scraping
- `pandas`, `numpy` – for data manipulation
- `matplotlib`, `seaborn` – for data visualization
- `re`, `json` – for data formatting and extraction

---

## 🔄 Workflow

1. **Web Scraping**
   - Extract job listings (title, company, location, experience, skills, salary, etc.)
   - Clean and structure the raw HTML data.

2. **Data Preprocessing**
   - Remove duplicates, nulls, and irrelevant rows.
   - Normalize column formats (e.g., locations, skills).

3. **EDA (Exploratory Data Analysis)**
   - Identify most in-demand job roles and skills.
   - Analyze job distribution by location and salary.
   - Visualize hiring trends and top companies.

---

## 📊 Sample Insights

- Top hiring cities and companies
- Most demanded technologies (e.g., Python, SQL, AWS)
- Salary range patterns by role and experience level

---

## 📌 Use Cases

- **Job Seekers**: Identify trends and in-demand skills.
- **HR & Recruiters**: Gain insight into competitive job market.
- **Analysts**: Understand the supply-demand gap in tech jobs.

---

## 🚀 Future Improvements

- Automate regular scraping with scheduling tools (e.g., `cron`, `Airflow`)
- Integrate NLP for job description clustering
- Build a dashboard using Power BI or Streamlit

---
