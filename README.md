AI Resume Matcher & Optimizer

Overview

The AI Resume Matcher & Optimizer is a Streamlit-based application that helps users optimize their resumes by comparing them with job descriptions. It extracts key skills from the job description and enhances the resume accordingly while providing a match score.

Features

Extracts text from uploaded resumes and job descriptions (PDF, DOCX, TXT)

Uses OpenAI GPT to extract must-have and good-to-have skills

Searches relevant job keywords using the Serper API

Calculates a match score between resume and job description using fuzzy matching

Generates an optimized resume with highlighted keyword matches

Allows download of the optimized resume in both DOCX and PDF formats

Requirements

Python 3.8+

Required Python libraries:

pip install streamlit PyPDF2 python-docx fuzzywuzzy fpdf crewai_tools openai dotenv

OpenAI API Key

Serper API Key

Installation & Setup

Clone the repository:

git clone https://github.com/your-username/resume-matcher.git
cd resume-matcher

Install dependencies:

pip install -r requirements.txt

Set up API Keys:

Create a .env file in the project root.

Add your OpenAI and Serper API keys:

OPENAI_API_KEY=your_openai_api_key
SERPER_API_KEY=your_serper_api_key

Run the application:

streamlit run app.py

Usage

Open the application in the browser.

Upload your resume and job description.

Click "Optimize Resume" to extract keywords and generate an optimized version.

View match score and download the updated resume in DOCX/PDF format.

File Structure

resume-matcher/
│── app.py                 # Main application script
│── requirements.txt       # Dependencies
│── .env.example          # API key template (DO NOT share actual .env file)
│── README.md              # Project documentation

License

This project is licensed under the MIT License.

Acknowledgments

Built with OpenAI GPT, Serper API, Streamlit, and NLP techniques for job application optimization.

🚀 Happy Job Hunting!