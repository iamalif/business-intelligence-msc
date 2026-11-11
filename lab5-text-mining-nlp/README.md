# Lab 5 Text mining and sentiment

Explores course-provided Star Wars dialogue through tokenisation, cleaning, word frequencies, word clouds, TF-IDF and VADER sentiment. Dialogue sentiment is a limited lexical measurement, not a judgement of character or motivation.

Open `Group26_Lab5.ipynb` with the notebook directory as the working directory. Install the repository's requirements first. The course-provided input files remain beside the notebook in the paths it expects.

Original Group 26 academic attribution is preserved in the notebook. See the root `PUBLICATION_NOTES.md` for changes made for publication and `DATA_SOURCES.md` for provenance.

Before running, download the NLTK resources:

```bash
python -m nltk.downloader punkt punkt_tab stopwords wordnet omw-1.4
```

Use a Python installation with working certificate verification. Do not disable HTTPS verification to resolve a download error.
