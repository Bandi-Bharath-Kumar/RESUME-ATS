# AI Powered Resume Screener 🚀🔍
A Streamlit-based AI-driven application that automates resume screening, ranking, and analysis using Google's **Gemini (Generative AI)**, Natural Language Processing (NLP), and Machine Learning (ML) techniques for efficient and unbiased hiring decisions.

---

## 📜 Abstract
This project proposes an AI-powered resume screening system to automate the initial stages of recruitment by analyzing and ranking resumes against a job description. The system ensures a fair evaluation process by leveraging **Generative AI (Gemini)**, **NLP**, and **ML**, significantly reducing human bias, workload, and time-to-hire.

---

## 🎯 Key Features
- **Resume Summary Generation**: AI-generated concise summary of resume content.
- **Percentage Match with Job Description**: Calculates how well a resume fits a given JD.
- **Job Role Recommendations**: Suggests suitable job positions based on candidate skills.
- **Skill Gap Analysis & Suggestions**: Highlights missing skills for targeted upskilling.
- **Ranking of Multiple Resumes**: Sorts multiple resumes by JD relevance score.

---

## 🏗️ System Architecture
1. **User Interface**: Built using Streamlit.
2. **Resume Parsing**: PDF text extraction via **PyPDF2**.
3. **Text Preprocessing**: Cleaning and normalizing resume content.
4. **Generative AI Interaction**: Querying **Google Gemini 2.0 Flash Model** for content generation.
5. **Ranking & Scoring**: AI evaluates relevance and assigns match percentages.
6. **Result Visualization**: Displaying summaries, skill gaps, recommendations, and rankings interactively.

---

## 🧑‍💻 Technologies & Tools
- **Streamlit** – Frontend Interface
- **Google Gemini API** – AI content generation & analysis
- **PyPDF2** – PDF Text Extraction
- **Python-dotenv** – Environment variable management
- **Pandas** – Data handling & Resume ranking tables

---

## 📝 Literature & Research Base
This project builds upon methodologies from:
- Efficient Resume Re-education for Career Recommendations (IEEE Access, 2023)
- LLM-based Resume Parsing & Recommendation Systems (TENSYMP 2024)
- BiLSTM Models for Resume Classification (IEEE SAMI 2024)
- AI Models like LLaMA 3, GPT-3.5 Turbo for Resume Screening Efficiency

> **Primary Dataset Reference**: Kaggle Resume Dataset (2K+ structured & unstructured formats)

---

## ⚡ Setup Instructions
### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/ats-resume-screener.git
cd ats-resume-screener
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Environment Setup
Create a `.env` file:
```bash
GOOGLE_API_KEY=your_google_generative_ai_api_key
```

### 4. Run the Application
```bash
streamlit run app.py
```

---

## 🧩 Project Workflow
- **Upload resume(s)** (Single or Multiple PDFs)
- **Select desired analysis option**:
  - Resume Summary
  - Percentage Match with Job Description
  - Job Recommendations
  - Skill Improvement Suggestions
  - Rank Multiple Resumes
- **Input Job Description** (if required)
- **AI reads and analyzes** the resumes.
- **Results are displayed** with clear visualization & suggestions.
- **Downloadable reports** (optional enhancement)

## 📈 Benefits of Generative AI in Resume Screening

- **Time Efficiency**: Automates tedious manual resume screening.
- **Unbiased Evaluation**: Reduces human prejudice.
- **Contextual Understanding**: NLP-driven semantic matching beyond keyword searches.
- **Scalable Solution**: Handles bulk resume uploads & rankings.


