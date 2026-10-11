# 📄 AI Resume Analyzer

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)
![Gemini AI](https://img.shields.io/badge/Google%20Gemini-AI-orange.svg)

A web-based application built with Python and Streamlit that leverages Google's Gemini AI to analyze resumes and provide constructive, actionable feedback. 

*Built as a 1st Semester BCA (Bachelor of Computer Applications) side project.* 🚀

## ✨ Features
* **Multi-Format Support:** Upload resumes in both PDF and TXT formats.
* **Role-Specific Tailoring:** Enter a target job role to get customized feedback, or leave it blank for general advice.
* **Intelligent Analysis:** Powered by Google's Gemini AI model to evaluate content clarity, skills presentation, and experience descriptions.
* **Secure:** Uses environment variables to securely handle API keys.

## 🛠️ Tech Stack
* **Language:** Python
* **Frontend:** Streamlit
* **AI Model:** Google Generative AI (Gemini Flash)
* **Document Parsing:** PyPDF2
* **Environment Management:** python-dotenv

## 🚀 How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/GreenPlayerManghiam/AI-Resume-Analyzer.git
cd AI-Resume-Analyzer
```

### 2. Install the required dependencies
Make sure you have Python installed, then run:
```bash
pip install streamlit PyPDF2 google-generativeai python-dotenv
```

### 3. Set up your API Key
Create a file named `.env` in the root directory of the project and add your Google Gemini API key:
```env
GOOGLE_API_KEY=your_gemini_api_key_here
```
*(Note: Never share your API key or commit your `.env` file to GitHub!)*

### 4. Run the application
```bash
streamlit run main.py
```
The application will automatically open in your default web browser.

## 💡 Usage
1. Open the web app.
2. Upload your resume (PDF or text file).
3. (Optional) Enter the specific job role you are applying for.
4. Click **Analyze Resume** and wait a few seconds for the AI to generate your customized review!

## 🤝 Connect
Created by [GreenPlayerManghiam](https://github.com/GreenPlayerManghiam). Feel free to reach out, open issues, or submit pull requests!
