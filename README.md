MediAssist - AI Healthcare Assistant

Introduction :

MediAssist is an AI-powered healthcare assistant designed to help healthcare professionals and patients by analyzing medical images, patient data, and symptoms. The application assists in diagnosing diseases accurately and efficiently using mock data and the Gemini AI model.

Features :

Symptom Checker: Analyzes user-provided symptoms and suggests possible conditions, recommended actions, and emergency signs.

Medical Report & Image Analysis: Extracts and analyzes images from uploaded PDFs (X-rays, MRI, CT scans) and provides medical insights.

Medication Analysis: Analyzes medication interactions, side effects, and usage guidelines.

Technology Stack :

Frontend: Streamlit

Backend: Python

AI Model: Gemini AI (Google Generative AI)

Libraries Used:

PyMuPDF (fitz) for PDF processing

PyPDF2 for text extraction from PDFs

Google Generative AI API

Streamlit for the user interface

Installation and Setup

Prerequisites :

Ensure you have Python 3 installed along with the following dependencies:

pip install streamlit PyPDF2 pymupdf google-generativeai

Running the Application : 

1. Clone the repository:

   git clone https://github.com/your-repo/medical_chat_bot.git

   cd medical_chat_bot

2. Install dependencies:

   pip install -r requirements.txt

3. Run the application:

   streamlit run medical_chat_bot.py

4. Open the displayed URL in a web browser.

Usage : 

1. Symptom Checker

   Enter symptoms in the text area.

   Click "Analyze Symptoms" to get AI-generated possible conditions and recommendations.

2. Medical Report & Image Analysis

   Upload a PDF containing medical images.

   The AI extracts and analyzes images and text, providing relevant medical insights.

   Alternatively, upload a medical scan image (X-ray, MRI, CT) for direct analysis.

3. Medication Analysis

   Enter a list of medications.

   The AI will analyze for possible drug interactions, side effects, and usage guidelines.

Demo Screenshots : 

Home Page -

![Home Page](https://github.com/user-attachments/assets/27581d13-1dd4-4357-a55d-93019f4a9885)

Symptom Checker - 

![Symptor Checker](https://github.com/user-attachments/assets/d8ec36a3-d824-4827-a527-9caf76d35ba2)


Medical Report Upload & Analysis - 

![Medical Report](https://github.com/user-attachments/assets/dea9a2f9-91db-4614-96e3-d842f3bca3b5)

![Medical Report](https://github.com/user-attachments/assets/dd68a872-b356-4e4f-8e06-12956eb2c724)

Medical Image Analysis - 

![X-ray](https://github.com/user-attachments/assets/d049d19d-86d7-4049-872f-e38ea56496fb)

Medication Analysis - 

![Medical Analyser](https://github.com/user-attachments/assets/4929ade8-478a-4ad0-9caf-50d0fef45145)

API Key Configuration

Replace GEMINI_API_KEY in the code with your valid API key:

GEMINI_API_KEY = "your_actual_api_key_here"

Contributors

Sai Ratna Varshita

License

This project is open-source and available under the MIT License.
