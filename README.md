# AI Meeting Summarizer

## 📋 Overview
AI Meeting Summarizer is a Streamlit-based web application that extracts key insights from meeting transcripts. It leverages the Groq API to generate concise summaries and actionable items from uploaded text, PDF, or Word documents.

## 🚀 Features
- Upload a transcript in **TXT, PDF, or DOCX** format.
- Extract key points and summarize meeting discussions.
- Identify and structure **action items** with responsible persons and deadlines.
- Download the summary and action items as a **PDF report**.

## 🛠️ Installation

### Clone the repository:
```bash
git clone https://github.com/your-username/AI-Meeting-Summarizer.git
cd AI-Meeting-Summarizer
```

### Install dependencies:
```bash
pip install -r requirements.txt
```

### Set up environment variables:
Create a `.env` file and add your **Groq API key**:
```bash
echo "GROQ_API_KEY=your_api_key_here" > touch.env
```

## 🎯 Usage
Run the Streamlit application:
```bash
streamlit run app.py
```

Upload your meeting transcript, generate a summary and action items, and download the PDF report.

## 📦 Dependencies
- Python
- Streamlit
- Groq API
- PyPDF2
- python-docx
- fpdf
- dateparser
- dotenv

## 📝 License
This project is licensed under the MIT License. Feel free to contribute and improve it!

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


