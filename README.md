 
---

```markdown
# 📄 AI Resume Analyzer

An AI-powered resume analyzer built with **Python**, **Streamlit**, and **spaCy**. This tool allows users to upload their resumes (PDF format) and get instant feedback on grammar, structure, keyword density, and a smart resume score out of 100.

---

## 🚀 Features

- 🔍 **PDF Text Extraction** using `PyPDF2`
- 🧠 **NLP-Powered Analysis** with `spaCy`
  - Keyword Extraction
  - Grammar Feedback (incomplete or long sentences)
- 📊 **Resume Scoring** based on structure, keyword use, grammar, and length
- 💡 **Suggestions** for improvement in content and formatting
- ⚙️ Clean **Streamlit UI** with loading indicators and progress messages

---

## 📦 Tech Stack

- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [spaCy](https://spacy.io/)
- [PyPDF2](https://pypi.org/project/PyPDF2/)

---

## 📁 Project Structure

```

├── app.py              # Main Streamlit application
├── requirements.txt    # Python dependencies
└── README.md           # Project overview and instructions

````

---

## 🛠️ Installation

1. **Clone the repository:**

```bash
git clone https://github.com/rishi7838/ai-resume-analyzer.git
cd ai-resume-analyzer
````

2. **Create and activate a virtual environment (optional but recommended):**

```bash
python -m venv venv
source venv/bin/activate     # On Windows: venv\Scripts\activate
```

3. **Install dependencies:**

```bash
pip install -r requirements.txt
python -m spacy download en_core_web_sm
```

4. **Run the Streamlit app:**

```bash
streamlit run app.py
```

---

## 📷 Screenshot

![screenshot](https://via.placeholder.com/800x400.png?text=Resume+Analyzer+UI+Preview)

---

## 📌 To Do / Future Enhancements

* OCR for scanned/image-based PDFs
* Export feedback as PDF
* ATS matching based on job descriptions
* Multilingual resume support

---

## 🙋‍♂️ Author

**Rishabh Chauhan**
[GitHub](https://github.com/rishi7838)

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

```

---

Let me know if you'd like me to generate the `requirements.txt` file as well or help push this project to GitHub.
```
