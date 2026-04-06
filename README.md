# 🧠 ProAudit AI – Financial Statement Analyzer

🚀 AI-powered audit analytics platform that detects financial anomalies, generates audit insights, and produces professional workpapers.

---

## 🌐 Live Demo

👉 https://saadbebalwork-lgtm-proaudit-ai-fd-g1fvbn.streamlit.app

---

## 📌 Overview

ProAudit AI is a SaaS-style application designed to assist auditors and analysts in identifying unusual financial patterns using statistical methods and AI.

The platform allows users to upload financial datasets, analyze multiple metrics, detect anomalies, and generate automated audit insights with downloadable reports.

---

## 🚀 Features

* 📊 Multi-metric anomaly detection (Z-score based)
* 🤖 AI-generated audit insights (LLM-powered)
* 📄 Downloadable audit reports (PDF)
* 📥 Export workpapers (Excel)
* 🔐 User authentication (Login / Signup)
* 📈 Interactive dashboard with visualizations
* 🧠 Smart column detection for flexible datasets

---

## 🧠 Tech Stack

| Layer         | Technology                        |
| ------------- | --------------------------------- |
| Frontend      | Streamlit                         |
| Backend       | Python                            |
| Data          | Pandas                            |
| Visualization | Matplotlib                        |
| AI Engine     | OpenAI API                        |
| Reporting     | ReportLab (PDF), OpenPyXL (Excel) |

---

## 📂 Project Structure

```id="code1"
ProAudit-AI/
│── FD.py                # Main Streamlit app
│── requirements.txt     # Dependencies
│── README.md            # Documentation
│── .gitignore
```

---

## ▶️ Run Locally

```bash id="code2"
git clone https://github.com/your-username/ProAudit-AI.git
cd ProAudit-AI
pip install -r requirements.txt
export OPENAI_API_KEY="your_api_key"
streamlit run FD.py
```

---

## 🔐 Environment Variables

Create environment variable:

```bash id="code3"
OPENAI_API_KEY=your_api_key
```

⚠️ Never expose your API keys in code.

---

## 📊 How It Works

1. Upload a CSV file
2. Select financial metrics
3. System calculates Z-scores
4. Flags anomalies automatically
5. AI generates audit insights
6. Download report (PDF / Excel)

---

## 🎯 Use Cases

* Financial statement analysis
* Audit risk identification
* Fraud detection (early-stage signals)
* Data-driven auditing workflows

---

## 💼 Resume Value

This project demonstrates:

* End-to-end SaaS development
* AI integration in real-world workflows
* Data analysis & anomaly detection
* Secure API handling
* Report automation (PDF/Excel)

---

## 🔮 Future Enhancements

* ☁️ AWS deployment (S3 + Lambda + RDS)
* 🔐 OAuth authentication (Google / Microsoft)
* 📊 Advanced ML models (Isolation Forest, Autoencoders)
* 📁 Multi-client audit dashboards
* 🧾 Audit trail & compliance logs

---

## 👤 Author

**Saad Bebal**

* 🎓 MS Data Science – DePaul University
* 💼 DevOps / Cloud Engineer
* 🔗 GitHub: https://github.com/your-username

---

## ⭐ Support

If you like this project:

👉 Star the repo
👉 Share feedback
👉 Connect on LinkedIn

---

## 📜 License

This project is for educational and portfolio purposes.
