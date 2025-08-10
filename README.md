# Web Scraping Job Requirements Analysis

## 📌 Project Overview
This project automates the process of collecting job postings for Data Analyst roles from an online job portal using **Selenium**. The scraped data is analyzed to identify hiring trends, in-demand skills, top employers, and location-based opportunities.

## 🎯 Objectives
- Scrape Data Analyst job postings from multiple pages.
- Extract relevant information such as job title, company, location, salary, and skills.
- Perform exploratory data analysis (EDA) to identify trends.
- Present insights in an easy-to-read format for recruitment purposes.

## 🛠 Tools & Libraries
- **Python**
- **Selenium** (web scraping)
- **Pandas** (data processing)
- **Matplotlib** (visualizations)

## 📊 Key Insights
- **Top Hiring Companies:** [Your top 5 company names]
- **Most Common Job Locations:** [Top 5 locations]
- **Most In-demand Skills:** [List of top skills]
- Salary trends: [If data available]

## 📂 Files in This Repository
- `web_scraping_job_requirements.ipynb` → Full scraping + analysis code.
- `job_postings.csv` → Raw scraped data.
- `requirements.txt` → Python dependencies.

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Web_Scraping_Job_Requirements.git
   cd Web_Scraping_Job_Requirements
   ```
2. Install dependencies:
```
pip install -r requirements.txt
```
3. Run the notebook in Jupyter:
```
jupyter notebook web_scraping_job_requirements.ipynb
```
👤 Author
Nitesh — Aspiring Applied AI Scientist

---

### **4. Solution (for Coursera Template)**
**Solution:**  
I developed a Python-based automated pipeline using **Selenium** to scrape job postings for Data Analyst roles across 10 pages (~200 entries). The system extracts job title, company name, location, salary (if available), and listed skills. After cleaning and structuring the data with **Pandas**, I conducted an exploratory analysis to uncover the most in-demand skills, top hiring companies, and major job locations. The results were summarized in an Excel file with visual charts to make insights easy to interpret for recruiters.

---

### **5. Approach (for Coursera Template)**
**Approach:**  
The project was implemented in three stages:  
1. **Scraping:** I chose **Selenium** over `requests` due to repeated 403 errors and the need to handle dynamic content. The scraper loops through multiple pages, waits for elements to load, and captures job details.  
2. **Data Cleaning:** Using **Pandas**, I standardized text, handled missing values, split multiple skills into lists, and normalized location names.  
3. **Analysis & Visualization:** I aggregated skill counts, ranked companies by job count, and analyzed location trends. Visualizations were generated with **Matplotlib** and results saved in Excel format for easy sharing.  

A key differentiator in my approach was ensuring the scraper was modular, allowing quick adjustments for different job portals or role keywords.
