# resume-parser-job-matcher
AI-powered tool that automatically extracts resume data (PDF/DOCX/TXT) and scores candidate-job fit using Streamlit
# 📄 Resume Parser & Job Matcher

An AI-powered Streamlit application that automatically extracts resume data and scores candidate-job compatibility.

## ✨ Features
- Automatic text extraction from PDF, DOCX, and TXT files
- Extracts name, email, phone number, skills, education, and years of experience
- Exports results to JSON, Excel (.xlsx), and CSV
- Smart Job Matching Score combining TF-IDF text similarity with direct skill overlap
- Automatic candidate ranking based on job-fit percentage

## 🛠 Tech Stack
- Python, Streamlit
- pdfplumber, pypdf (PDF extraction)
- python-docx (DOCX extraction)
- phonenumbers (international phone number detection)
- scikit-learn (TF-IDF + Cosine Similarity)
- pandas, openpyxl (data processing and export)

## 🚀 Run Locally
\`\`\`bash
pip install -r requirements.txt
streamlit run app.py
\`\`\`

## 📸 Screenshot
(Add a screenshot here after deployment)

## 🔗 Live Demo
[Live Demo](Streamlit Cloud link after deployment)
