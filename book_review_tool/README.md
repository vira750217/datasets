# Book Review & Rewrite Studio

A Streamlit app that uses OpenAI models to:
- upload **multiple Microsoft Word (.docx) manuscripts**,
- generate an editorial **review outline** for each manuscript,
- rewrite chapters for stronger logic, sequential flow, timeline consistency, and bestseller potential.

## Setup

```bash
cd book_review_tool
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Run

```bash
streamlit run app.py
```

Then in the app:
1. Provide your OpenAI API key.
2. Upload one or more `.docx` files.
3. Click **Review and Rewrite**.
4. Download an output `.docx` report for each input file.

## Notes
- The app currently accepts `.docx` files only.
- Prompting enforces structured JSON output and includes constraints for logical sequencing and time consistency.
- You can tune model and audience directly in the UI.
