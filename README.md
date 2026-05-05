# Indian Job Market Skill Gap Analysis

An end-to-end analysis of the Indian job market identifying skill demand, role-specific requirements, and key gaps using real job listing data, with an interactive dashboard built in Python.

---

## 📌 Overview

This project analyzes job postings across the Indian market to understand:

- Which skills are most in demand  
- How skill requirements differ across roles  
- What gaps exist between general job demand and specialized roles  

The analysis places a strong focus on **data-related roles** such as Data Analyst, Data Scientist, and Data Engineer.

---

## 🎯 Objectives

- Identify the most in-demand skills in the Indian job market  
- Analyze skill requirements for data-related roles  
- Compare overall market demand with role-specific needs  
- Highlight critical skill gaps for aspiring professionals  

---

## 📊 Key Insights

- **Python and SQL** act as baseline skills across data roles  
- Data roles increasingly demand tools like **Spark, Airflow, and Hadoop**  
- The broader job market is dominated by **business and sales-oriented skills**  
- A clear mismatch exists between general employability skills and specialized technical requirements  

---

## 📈 Dashboard

The project includes an **interactive dashboard** built using Plotly, showcasing:

- Top skills across the job market  
- Skill distribution by category  
- Data-role-specific skill demand  
- Skill gap comparison  

👉 Open `skill_gap_dashboard.html` to view the interactive dashboard.

---

## 🛠️ Tech Stack

- Python  
- Pandas, NumPy  
- Plotly (for interactive visualization)  
- Google Colab  

---

## ⚙️ Methodology

The project follows a structured analytics workflow:

1. Data Collection  
   - Job listings dataset containing roles, skills, and metadata  

2. Data Cleaning  
   - Removed null values  
   - Standardized skill formats  

3. Skill Extraction  
   - Parsed and flattened skill data  
   - Calculated frequency distribution  

4. Role-Based Filtering  
   - Isolated data-related roles  
   - Extracted role-specific skill demand  

5. Skill Gap Analysis  
   - Compared overall market skills with data-role skills  
   - Identified common and exclusive skill sets  

6. Visualization  
   - Built an interactive dashboard using Plotly  

---

## 📂 Project Structure

Indian-Job-Skill-Gap-Analysis/
│
├── Indian_Job_Skill_Gap_Analysis.ipynb
├── skill_gap_dashboard.html
├── README.md
├── LICENSE
└── data/ (optional)


---

## 🚀 How to Run

1. Open the notebook in Google Colab  
2. Upload or connect the dataset  
3. Run all cells  
4. The dashboard will be generated interactively  

---

## 💡 Use Case

This project can be useful for:

- Students preparing for data roles  
- Professionals looking to upskill  
- Recruiters analyzing hiring trends  
- Business analysts studying market demand  

---

## 📌 Future Improvements

- Add real-time job data integration  
- Expand analysis to other domains beyond data roles  
- Build a web-based dashboard using Streamlit  

---

## 📜 License

This project is licensed under the MIT License.
