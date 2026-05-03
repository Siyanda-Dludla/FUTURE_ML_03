# FUTURE_ML_03
# 📄 Resume Screening & Candidate Ranking System

## 📌 Project Overview
This project builds a Machine Learning–based system that automatically screens, scores, and ranks resumes based on a given job description.

The system simulates how modern recruitment platforms use NLP to filter candidates efficiently and identify the best fit for a role.

---

## 🎯 Objectives
- Analyze and process resume text data  
- Extract relevant skills and keywords  
- Compare resumes with a job description  
- Rank candidates based on relevance  
- Identify missing or weak skills  

---

## ⚙️ Tools & Technologies
- Python  
- Pandas  
- Scikit-learn  
- TF-IDF Vectorizer  
- Cosine Similarity  
- Jupyter Notebook  

---

## 🔍 Methodology

### 1. Data Preprocessing
- Cleaned resume text (lowercasing, removing punctuation)
- Prepared text for NLP processing  

### 2. Feature Engineering
- Converted text into numerical vectors using TF-IDF  

### 3. Resume–Job Matching
- Compared resumes with a job description using cosine similarity  

### 4. Candidate Ranking
- Assigned scores based on similarity  
- Ranked candidates from most to least relevant  

### 5. Skill Extraction
- Extracted key skills from resumes using keyword matching  

### 6. Skill Gap Analysis
- Identified missing skills compared to job requirements  

---

## 📊 Example Output

Job Role:
"Data Analyst with Python, SQL, and Machine Learning skills"

Candidate Result:
- Score: 0.82  
- Skills: [Python, SQL]  
- Missing Skills: [Machine Learning, Data Analysis]  

---

## 💡 Business Value
- Automates resume screening  
- Reduces recruiter workload  
- Improves candidate shortlisting  
- Identifies skill gaps for better hiring decisions  

---

## 🚀 Future Improvements
- Use advanced NLP models (spaCy, BERT)
- Improve skill extraction with named entity recognition
- Add weighted scoring for critical skills
- Build a web-based interface for recruiters  

---

## 👤 Author
|Siyanda Dludla| Machine Learning Enthusiast😉|
