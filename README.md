# 📄 AI Resume Ranking System

An AI-powered tool that ranks multiple resumes against a specific Job Description (JD) using Natural Language Processing (NLP). This project is designed to help HR teams and applicants quickly identify the best candidates based on semantic and keyword similarity.

## 🚀 Features
* **Multi-PDF Support:** Upload multiple resumes at once.
* **Text Extraction:** Automatically extracts text from PDF files using `PyPDF2`.
* **Smart Ranking:** Uses **TF-IDF Vectorization** and **Cosine Similarity** to calculate match percentages.
* **Interactive UI:** A clean, responsive dashboard built with **Streamlit**.

## 🛠️ Technology Stack
* **Language:** Python
* **Frontend:** Streamlit
* **Machine Learning:** Scikit-learn (TF-IDF, Cosine Similarity)
* **File Handling:** PyPDF2

## 📦 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/challalokesh08/Resume_Ranker_AI.git](https://github.com/challalokesh08/Resume_Ranker_AI.git)
   cd Resume_Ranker_AI

Install dependencies:
pip install -r requirements.txt

Run the application:
streamlit run streamlit_app.py

📊 How it WorksInput: The user pastes a Job Description and uploads one or more resumes in PDF format.Processing: The system cleans the text and converts it into numerical vectors using the TF-IDF algorithm.Similarity Calculation: It calculates the "distance" between the JD vector and each resume vector using the Cosine Similarity formula:$$\text{Similarity} = \frac{\mathbf{A} \cdot \mathbf{B}}{\|\mathbf{A}\| \|\mathbf{B}\|}$$Output: A ranked list of resumes with a percentage match score.
