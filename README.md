# NER Visualizer 🧮

Named Entity Recognition system with
spaCy and rule-based fallback — extract,
visualize and analyze entities from text.

## Live Demo
[Click here](YOUR_STREAMLIT_URL)

## Features
- spaCy NER (en_core_web_sm)
- Rule-based fallback (always works)
- Inline entity highlighting with labels
- 18 entity types with color coding
- Custom entity addition via sidebar
- Entity frequency and position analytics
- Co-occurrence matrix visualization
- Batch NER processing with CSV export
- Custom regex rule builder
- BIO tagging explanation
- Interview Q&A

## Tools Used
- Python, Streamlit, spaCy,
  Plotly, Pandas, NumPy

## How to Run Locally
pip install streamlit spacy plotly pandas numpy
python -m spacy download en_core_web_sm
streamlit run app.py
