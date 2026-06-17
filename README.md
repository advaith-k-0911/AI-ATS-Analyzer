# 🤖 AI ATS Analyzer

An AI-powered resume screening tool that simulates an **Applicant Tracking System (ATS)** using **LLMs** to analyze resumes against job descriptions and generate actionable feedback.

---
<h2>Preview</h2>
<p align="center">
<img width="1920" height="1080" alt="Screenshot 2026-06-17 221647" src="https://github.com/user-attachments/assets/2bbfb706-2ee3-4cf1-b313-1fb1558c3e1c" />
</p>
---

## 🚀 Live Demo
🔗 Hugging Face Deployment: https://huggingface.co/spaces/Advaith0911/resume

---

## 📌 Overview
Recruiters often use ATS software to filter resumes before humans even see them.

This project mimics that workflow by:
- Extracting text from resumes (PDF/DOCX)
- Comparing resumes with job descriptions
- Calculating ATS compatibility
- Generating AI-powered feedback
- Suggesting improvements for better shortlisting

In short:  
**Resume + Job Description → ATS Analysis → Score + Feedback**

---

## ✨ Features
✅ Resume upload support (**PDF / DOCX**)  
✅ Job description matching  
✅ ATS score generation  
✅ Skill gap detection  
✅ Resume improvement suggestions  
✅ AI-powered analysis using Groq LLM  
✅ Clean Streamlit UI  

---

## 🏗️ System Architecture

```text
Resume Upload
     ↓
Text Extraction (PDF/DOCX)
     ↓
Preprocessing
     ↓
Groq LLM Analysis
     ↓
ATS Score Generation
     ↓
Feedback & Suggestions
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| Python | Core logic |
| Streamlit | Web UI |
| Groq API | LLM inference |
| PyPDF | PDF text extraction |
| python-docx | DOCX parsing |
| dotenv | Environment management |

---

## 📂 Project Structure

```bash
AI-ATS-Analyzer/
│
├── app.py          # Main Streamlit UI
├── utils.py        # Resume parsing & ATS logic
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 📷 Preview

Add your screenshot here:

```md
![App Preview](preview.png)
```

---

## ⚙️ Installation

### 1. Clone Repository
```bash
git clone https://github.com/advaith-k-0911/AI-ATS-Analyzer.git
cd AI-ATS-Analyzer
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Setup Environment Variables
Create `.env`

```env
GROQ_API_KEY=your_api_key_here
```

### 4. Run App
```bash
streamlit run app.py
```

---

## 💡 Why This Project?
This project demonstrates practical applications of:
- Generative AI
- NLP
- Resume analysis
- LLM-powered decision support systems

It also showcases how AI can automate early-stage recruitment workflows.

---

## 🎯 Future Improvements
- Multi-resume comparison
- Resume ranking system
- Better UI animations
- Downloadable report (PDF)
- Recruiter dashboard

---

## 👨‍💻 Author
**Advaith K**  
BTech Cybersecurity Student | AI/ML Enthusiast

GitHub: https://github.com/advaith-k-0911

---

## 📜 License
Licensed under the MIT License.
