# Business Intelligence Coursework

Coursework from **Business Intelligence (AMI295)** in the **Data Science master's programme at Dalarna University, Sweden**. The course was completed in 2026 with an overall grade of **VG (Pass with distinction)**.

This repository is a coursework collection. It distinguishes completed analytical notebooks, supporting material and work that will be linked separately.

## Contents

| Folder | Contents | Publication status |
|---|---|---|
| [Lab 1](lab1-python-data-handling/) | Python exploration of NBA data | Existing notebook and supporting files |
| [Lab 2](lab2-powerbi-sales-dashboard/) | Startup-expansion and city population datasets | Supporting data only; dashboard file not yet available |
| [Lab 3](lab3-classification/) | Customer risk classification with logistic regression and random forest | Notebook and data |
| [Lab 4](lab4-clustering/) | EV charging exploration using PCA and K-means | Notebook and data |
| [Lab 5](lab5-text-mining-nlp/) | Dialogue text mining, TF-IDF and sentiment analysis | Notebook and supporting inputs |

The final GeoLife trip-purpose project is being prepared as a standalone repository. Its link will be added here after publication.

## Setup

Create a virtual environment, activate it, and install the dependencies:

```bash
python -m venv .venv
```

macOS/Linux:

```bash
source .venv/bin/activate
```

Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

Then:

```bash
python -m pip install -r requirements.txt
python -m jupyterlab
```

Open the notebook inside the relevant lab folder and run its cells in order. Keep its data in the supplied relative locations. Lab 5 also needs the NLTK resources listed in its README. `requirements-tested.txt` records the direct package versions used for verification; it is a reference snapshot, not a complete cross-platform lock file.

## Interpretation and contribution

These are academic exercises, not deployed business systems. A high classification score on a small teaching dataset does not establish real-world churn prediction. Clustering is exploratory, and lexicon-based sentiment does not establish a character's motives.

Original academic attribution is retained in each notebook. Supplied briefs, datasets and templates are not claimed as original work. See [data provenance](DATA_SOURCES.md), [publication changes](PUBLICATION_NOTES.md) and [verification](VERIFICATION.md).

## Related work

- [Python coursework](https://github.com/iamalif/python-programming-msc)
- [R and data analysis coursework](https://github.com/iamalif/r-and-data-analysis-msc)
- [Environmental disclosure analysis](https://github.com/iamalif/environmental-disclosure-analysis)
