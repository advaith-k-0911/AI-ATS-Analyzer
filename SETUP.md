# 🚀 Setup Guide

Follow these steps to run the **AI ATS Analyzer** locally.

---

## 📥 Step 1: Clone the Repository

Clone the GitHub repository to your local machine:

```bash
git clone https://github.com/advaith-k-0911/AI-ATS-Analyzer.git
cd AI-ATS-Analyzer
```

---

## 📦 Step 2: Install Dependencies

Make sure **Python** is installed on your system.

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## 🔑 Step 3: Create Environment File

Create a `.env` file in the project root directory.

Add your Groq API key:

```env
GROQ_API_KEY=your_api_key_here
```

Get your API key from:
[GroqCloud](https://console.groq.com/keys?utm_source=chatgpt.com)

---

## ▶️ Step 4: Run the Application

Execute the following command:

```bash
streamlit run app.py
```

---

## 🌐 Step 5: Open in Browser

Streamlit will provide a local URL:

```txt
http://localhost:8501
```

Open it in your browser.

---

## 🧪 Step 6: Use the App

1. 📄 Upload your resume (**PDF / DOCX**)
2. 📝 Paste the job description
3. 🤖 Click **Analyze**
4. 📊 View ATS score and analysis
5. 💡 Improve your resume using suggestions

---

## ✅ Output

The system generates:

* 📊 ATS Compatibility Score
* 🧠 Skill Gap Analysis
* 💬 AI Feedback
* 🚀 Resume Improvement Suggestions
