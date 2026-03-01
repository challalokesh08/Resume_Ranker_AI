# 📄 AI-Powered Resume Ranking System

An intelligent screening tool designed to automate the process of matching candidate resumes with job descriptions. Using Natural Language Processing (NLP) and machine learning techniques, this application ranks applicants based on semantic and keyword similarity.

## 🌟 Key Features
* **Automated Text Extraction:** Parses text directly from uploaded PDF files using `PyPDF2`.
* **NLP Engine:** Utilizes **TF-IDF Vectorization** to convert textual data into mathematical representations.
* **Similarity Scoring:** Calculates the **Cosine Similarity** between the Job Description (JD) and the candidate's profile to generate an objective "Match Score."
* **Interactive UI:** A real-time dashboard built with **Streamlit** for seamless file uploading and visualization.
* **Multi-File Processing:** Allows HR teams to upload and rank dozens of resumes simultaneously.

## 🛠️ Technical Stack
* **Programming Language:** Python
* **Web Framework:** Streamlit
* **Machine Learning:** Scikit-learn
* **Data Parsing:** PyPDF2

## 🧬 How It Works (The Math)
The system represents the Job Description and the Resume as vectors in a multi-dimensional space. It then calculates the cosine of the angle between them to determine how closely they align:

$$\text{Similarity} = \frac{\mathbf{A} \cdot \mathbf{B}}{\|\mathbf{A}\| \|\mathbf{B}\|}$$

* **100% Match:** The vectors point in the exact same direction.
* **0% Match:** The vectors are orthogonal (completely unrelated).

## 🚀 Getting Started

### Prerequisites
Ensure you have Python 3.9+ installed.

### Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/challalokesh08/Resume_Ranker_AI.git](https://github.com/challalokesh08/Resume_Ranker_AI.git)


DEMO
https://resumerankerai-dtgdsnjhat7zuz4xfrzdiv.streamlit.app/
