# 🏥 MediAssist - AI Healthcare Assistant

## 📌 Project Overview
MediAssist is an AI-powered healthcare assistant that provides:
- Symptom analysis and possible condition predictions
- Medical report and scan image analysis using AI
- Medication interaction and side-effect checking

This project uses **Google Gemini AI** to analyze medical reports, symptoms, and medications efficiently. It supports PDF medical reports (extracting images and text) and direct image uploads for medical scan analysis.

## ✨ Features
- ✅ **Symptom Checker**: Predicts possible conditions based on symptoms
- ✅ **Medical Report & Scan Analyzer**: Extracts and analyzes images and text from PDFs
- ✅ **Medication Analyzer**: Identifies drug interactions, side effects, and guidelines
- ✅ **AI-powered**: Uses **Google Gemini AI** for advanced medical analysis

---

## 🛠️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/Diagnostic_Assistant.git
cd MediAssist
```

### 2️⃣ Create a Virtual Environment (Recommended)
```bash
python -m venv venv
source venv/bin/activate  # For macOS/Linux
venv\Scripts\activate  # For Windows
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Set Up Google Gemini API Key
Create a `.env` file and add your API key:
```plaintext
GEMINI_API_KEY=your_api_key_here
```

### 5️⃣ Run the Application
```bash
streamlit run app.py
```

---

## 🔧 Code Structure
```
MediAssist/
│── app.py                # Main Streamlit application
│── healthcare_agent.py    # AI processing logic
│── requirements.txt       # Python dependencies
│── .env                   # API Key storage (not included in repo)
└── README.md              # Project documentation
```



---

## 📸 Screenshots & Demo
### Symptom Checker UI
![Symptom Checker](assets/symptom_checker.png)

### Medical Report Analysis UI
![Medical Report](assets/medical_report.png)

### Medication Analysis UI
![Medication Analysis](assets/medical_report.png)

---

## 📜 License
This project is licensed under the MIT License. See `LICENSE` for details.

## 📞 Contact
For questions or collaboration, reach out via:
- ✉ Email: varshita.andvr@gmail.com
- 🔗 LinkedIn: [Sai Ratna Varshita Annadevara](https://www.linkedin.com/in/sai-ratna-varshita-annadevara-3a22b0259)

---

_"MediAssist: AI-powered healthcare at your fingertips!"_ 🚀
