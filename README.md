# COMP20121 Foundations of AI and Machine Learning

Coursework for **COMP20121 Foundations of Artificial Intelligence and Machine Learning** (student N1205091). The folder has two parts: an AI report plus video, and a machine-learning notebook that analyses the 2022 Kaggle ML & Data Science Survey.

## Machine Learning

The notebook `kaggle-survey-2022-analysis-notebook-n1205091.ipynb` (also as HTML and PDF) uses the 2022 Kaggle survey (~23,997 respondents) and follows CRISP-DM.

**Tasks**

1. **EDA** — structure, quality, and how yearly compensation (Q29) varies with demographics, education, and job attributes.
2. **Classification** — split income into low vs high and predict the group with models such as logistic regression, k-NN, random forest, and a voting ensemble. Features include job role, education, coding/ML experience, and country. Metrics: accuracy, precision, recall, F1, confusion matrix, ROC.
3. **Clustering** — k-means and agglomerative (Ward) clustering to profile groups such as early-career learners and more senior ML practitioners. `k` is chosen with silhouette score and an elbow plot.

The notebook loads `kaggle_survey_2022_responses.csv` from Kaggle (`nwaforty/kaggle-survey-2022`). That CSV is not stored here; attach the Kaggle dataset if you re-run the notebook.

## AI

- `N1205091 AI.pdf` — AI coursework report.
- `AI.mov` is a 129 MB demo video. It is **not** in this repo (GitHub rejects files over 100 MB). Keep a local copy under the original Downloads folder.

## How to open

- Machine Learning: open the `.ipynb` in Jupyter, VS Code, or Kaggle.
- AI: open the PDF.

## Project files

The course folder is `COMP20121 Found'ns of AI & Machine Learning/`.

| Path | Role |
| --- | --- |
| `AI/N1205091 AI.pdf` | AI report |
| `Machine Learning/*.ipynb` | Survey analysis (EDA, classification, clustering) |
| `Machine Learning/*.html` | Exported notebook |
| `Machine Learning/*.pdf` | Notebook as PDF |

## Course

**COMP20121** — foundations of AI and machine learning: survey EDA, supervised classification of compensation, unsupervised clustering, and an AI written/video submission.
