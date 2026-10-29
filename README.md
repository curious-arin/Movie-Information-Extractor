# Movie Information Extractor 🎬

## 🙂 Overview

An AI-powered Streamlit application that extracts structured movie information from unstructured text using Groq API, LangChain, and Pydantic.

-----

## 💡 Problem Statement

Manually extracting movie details from lengthy paragraphs is time-consuming. This project automates the process by converting text into structured, validated JSON.

-----

## 🛠️ Tech Stack

- Python
- Streamlit
- LangChain
- Groq API
- Pydantic
- python-dotenv

-----

## 🔄 Workflow

1. Enter the Groq API key for authentication.
2. Paste a movie description.
3. Process the text using the Groq LLM and LangChain prompt.
4. Validate the extracted information using Pydantic Output Parser.
5. Display the structured JSON output.

-----

## 📊 Extracted Information

- Title and Release Year
- Genre and Director
- Cast and Rating
- Summary

-----

## 📂 Project Structure

```text
├── app.py
├── raw.py
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

-----

## 🔮 Future Improvements

- Export data as CSV, Excel, or JSON.
- Support books, TV shows, and documentaries.
- Add multilingual support.
- Build a React + FastAPI frontend.
- Deploy the application and support additional LLM providers.
