# 📄 Resume Analyzer based on Job Description (JD)

This project is an interactive tool built with **Python** and **Gradio** that helps users analyze how well their resume matches a given job description using **ATS-style scoring**. It extracts skills from the resume and compares them against key requirements from the JD, offering suggestions and fit-score visualizations.

## 🚀 Features

- 📄 Upload your **resume (PDF)** and paste the **job description (JD)**.
- 🔍 Extracts and matches relevant **skills**.
- 📊 Generates an **ATS score pie chart**.
- 🤖 Suggests the **best-fit role** from predefined career paths.
- 💡 Offers personalized suggestions to improve your resume match.

## 🛠️ Technologies Used

- `Gradio` – UI interface for input and output.
- `pdf2image`, `PyMuPDF`, `pytesseract` – For PDF and image text extraction.
- `NLTK` – Text processing and keyword extraction.
- `matplotlib` – ATS match score visualization.

## 📦 Installation

```bash
pip install gradio pdf2image pytesseract nltk matplotlib PyMuPDF
sudo apt-get install -y poppler-utils
```

> Also ensure Tesseract OCR is installed on your system.

## 💡 How to Use

1. Run the script:
   ```bash
   python resume_checker.py
   ```
2. Upload your **resume (PDF)**.
3. Paste the **job description**.
4. View your **ATS score**, skill matches, and suggested roles!

## 🧠 Roles Covered

- AI/ML Intern
- Data Analyst
- Web Developer
- Backend Developer
- Cloud Engineer
- DevOps Engineer
- Cybersecurity Analyst
- Data Scientist
- Business Analyst
- Full Stack Developer

## 📸 Example Output

- Pie chart of your resume-to-JD match score.
- Text recommendations with skill gaps and job fit analysis.

## 🙌 Contribute

Feel free to fork, improve, and raise issues or pull requests.
