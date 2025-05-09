DocBot – An LLM-powered document QA tool for deep insights across diverse sources.

### 🔍 Features

- 📄 Upload and parse documents (PDF, DOCX, TXT)
- 🌐 Scrape and ingest web content (news articles, reports, etc.) -> Tavily
- 🤖 Semantic search using vector embeddings
- 💬 Ask natural-language questions about your document set
- 📊 Return relevant summaries, insights, or direct answers
- 🧠 Powered by OpenAI + Vector Database (ChromaDB)

This project is designed to take in input from multiple document sources.
This includes PDFs, Word Documents, plain TXT files, as well as potential Internet articles via web scraping.

Upon taking in these documents, augmented with OpenAI's API of training data, user can then feed the system NLP queries.
These queries will be related to the documents uploaded in question. The output will return relevant answers to said queries.

E.g. if documents are uploaded about the financials of a large corporation.

🔍 Business Use Case: Enables stakeholders to ask questions about complex documents (e.g., financials, contracts, earnings reports) without reading them end-to-end.

How to download all requirements.txt:
pip install -r /path/to/requirements.txt

TO RUN: in VSC (or other IDE) terminal, navigate to the correct folder as your present working directory (pwd).
Then, run "streamlit run insert_filename_here.py"