🧑‍💻 Author
Matthew Vang
Computer Science Student | Amateur Programmer/Machine Learning Enthusiast
GitHub: TBD
LinkedIn: TBD

# Resume Analyzer - AI Web App

This project is an AI-powered web application that evaluates resumes and scores them against job descriptions using natural language processing (NLP).
It helps job seekers understand how well their resume matches a particular job posting and provides actionable feedback for improvement.

# Features
✅ Upload a resume in PDF or DOCX format
✅ Input a job description
✅ Extracts and matches **keywords** and **skills** commonly used in real job postings

✅ Computes:
- Keyword overlap score
- Semantic simillarity score using sentence embeddings

✅ Highlights:
- Matched and missing keywords
- Common industry-specific terms

✅ Visual summary with optional charts or word clouds
✅ Deployable web app built with **Streamlit**

## 🧰 Tech Stack
| Layer | Tools / Libraries |
|-------|-------------------|
| **Language** | Python |
| **NLP** | spaCy, NLTK, sentence-transformers, transformers |
| **Machine Learning** | scikit-learn, pandas, numpy |
| **File Parsing** | PyPDF2, python-docx |
| **Web Framework** | Streamlit (for interactive UI), Flask (optional API backend) |
| **Visualization** | matplotlib, seaborn |
| **Data** | Real-world job description datasets from Kaggle or scraped postings |

## ⚙️ Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/Mattityahu26/resume-analyzer.git
cd resume-analyzer
pip install -r requirements.txt
streamlit run app.py