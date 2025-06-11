# 🧠 AI Resume Screening & Candidate Ranking System

An intelligent Streamlit-based application that automates resume screening by comparing candidate resumes with job descriptions and scoring them using AI-driven techniques. The system offers insights, suggestions, and a historical graph to improve candidate resumes and streamline recruitment.

---

## 🔧 Features

### For Candidates:

* Upload a resume (PDF).
* Paste the job description.
* Get an **ATS score** based on keyword matching.
* View **AI-generated suggestions** for improving the resume.
* Track your **score history** with an interactive line graph.

### For Recruiters:

* Recruiter dashboard to analyze multiple resumes against a job post.
---
## 📸 Screenshots

### 🧾 Upload Resume candidate page
![Upload Page](https://github.com/Kushal112003/ai-resume-screener-enhanced/raw/main/screenshots/Screenshot%202025-06-12%20015542.png)

### 🧾 Upload Resume recruiter page
![Score Display](https://github.com/Kushal112003/ai-resume-screener-enhanced/raw/main/screenshots/Screenshot%202025-06-12%20015608.png)

### 📋 Suggestions and score
![Suggestions and Graph](https://github.com/Kushal112003/ai-resume-screener-enhanced/raw/main/screenshots/Screenshot%202025-06-12%20015821.png)


## 🚀 Installation

### Prerequisites:

* Python 3.9+
* `pip`

### Setup:

```bash
pip install -r requirements.txt
streamlit run app.py
```

---

## 📁 Project Structure

```
resume_project/
├── app.py
├── requirements.txt
├── sample resumes/
│   └── [sample_resume_1.pdf, sample_resume_2.pdf]
├── uploaded_resumes/     # created at runtime
├── score_history/        # created at runtime
└── screenshots/          # (optional) add UI captures here
```

---

## 📌 Technologies Used

* **Streamlit** — Web app framework
* **PyMuPDF (fitz)** — PDF parsing
* **Matplotlib** — Visualization
* **Regex & NLP** — Keyword extraction and scoring logic

---

## 🤖 How It Works

1. Resume is parsed using PDF text extraction.
2. Job description keywords are extracted using regex.
3. Matching score is calculated.
4. AI logic (mock GPT-style suggestions) provides improvement feedback.
5. User history is stored and displayed as a graph.

---

## 🔐 Data Privacy

All resumes and scores are stored locally. No cloud upload or tracking involved.

---

## 🔮 Future Work

* Add GPT-powered real-time suggestions.
* Full recruiter dashboard: bulk resume analysis.
* Login system with authentication.
* Advanced scoring using BERT/GPT embeddings.

---

## 📝 License

This project is built for academic and educational purposes.
