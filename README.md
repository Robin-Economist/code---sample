# code---sample

# Automated Web Scraping & NLP Pipeline for Educational Research

## 📌 Project Overview
This repository contains a robust data pipeline designed to collect, process, and analyze academic literature related to the integration of **Large Language Models (LLMs) and Chatbots in Education**. 

This project was developed as a technical demonstration for a Research Assistant position, showcasing the ability to build reproducible workflows for large-scale social science experiments (RCTs).

## 🛠️ Technical Features
- **Automated Extraction:** Uses `requests` and `BeautifulSoup` to scrape live metadata from the **arXiv** database.
- **Data Engineering:** Transforms raw HTML into structured formats using `pandas`.
- **NLP Feature Engineering:** Implements text complexity metrics, including word counts and character length analysis—key variables for evaluating educational content.
- **Standardized Output:** Generates a structured **JSON dataset**, mirroring the requirements for analyzing chatbot conversation logs.

## 📊 Methodology
The pipeline follows a four-step process:
1. **Targeted Scraping:** Querying the intersection of "Chatbots" and "Education".
2. **DOM Parsing:** Isolating titles, authors, and full abstracts while handling dynamic HTML elements.
3. **Complexity Analysis:** Calculating descriptive statistics for the extracted text.
4. **Data Export:** Formatting the final output for downstream research use.

## 🚀 How to Use
The main logic is contained in `arXiv_Scraping_NLP_Pipeline.ipynb`.
- The script is designed to be fully reproducible on **Google Colab**.
- No API keys are required as it uses open-access academic sources.
- Output data is automatically saved as `chatbot_research_data.json`.

## 👤 Author
**Robin Masson** *Dual Master’s Student in Economics* *Université Paris 1 Panthéon-Sorbonne | Pontificia Universidad Javeriana*
