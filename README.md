
# SnapLogic Auto Pipeline Generator

This tool allows you to input either:
- A **natural language** requirement (like: "Read contact data from Salesforce and send active users to an API")
- OR a **structured JSON**

It will automatically generate a SnapLogic-ready JSON pipeline.

## Requirements
```
pip install streamlit openai
```

## Usage
```
streamlit run app.py
```

Make sure to set your OpenAI API key:
- Via environment variable `OPENAI_API_KEY`
- Or directly in `app.py`

## Output
JSON for SnapLogic pipeline, ready to copy-paste or download.
