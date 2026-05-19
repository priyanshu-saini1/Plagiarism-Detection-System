# AI-Based Plagiarism Detection System

An NLP-based plagiarism detection web application developed using Flask and Scikit-learn. The system compares documents using TF-IDF vectorization, cosine similarity, sentence-level matching, and N-gram analysis to detect textual similarity more accurately.

---

## Features

- Upload and compare text/PDF files
- TF-IDF and Cosine Similarity based detection
- Sentence-Level Similarity Matching
- N-Gram Analysis
- Smart preprocessing using NLP
- Highlight matched words and sentences
- Side-by-side document preview
- PDF report export
- File statistics and plagiarism score display

---

## Tech Stack

### Backend
- Python
- Flask
- Scikit-learn
- PyPDF2
- ReportLab

### Frontend
- HTML
- CSS
- JavaScript

### NLP Techniques
- TF-IDF Vectorization
- Cosine Similarity
- Sentence Matching
- N-Gram Analysis
- Stop-word Removal

---

## Project Structure

```bash
Plagiarism-Detection-System/
│
├── app.py
├── requirements.txt
├── README.md
│
├── templates/
│   └── index.html
│
└── static/
    ├── style.css
    └── script.js

```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/priyanshu-saini1/Plagiarism-Detection-System.git
```

Move into the project folder:

```bash
cd Plagiarism-Detection-System
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python app.py
```

Open in browser:

```text
http://127.0.0.1:5000
```

---

## Future Improvements

- Semantic similarity using BERT
- Multi-file comparison
- User authentication
- Database integration
- Cloud deployment

---

## Author

**Priyanshu Saini**

GitHub:
https://github.com/priyanshu-saini1
