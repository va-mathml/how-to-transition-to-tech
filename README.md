# How to Successfully Transition into Tech: A Data-Driven Analysis

> An educational analysis built for my data analytics bootcamp students who keep asking:
> *"How do I actually break into tech?"*
>
> Instead of answering with opinions, I taught them to answer with data.

**Author:** Víctor Aguilar — Data Analytics Instructor
**Dataset:** [Stack Overflow Developer Survey 2024](https://survey.stackoverflow.co/2024/) — 65,437 respondents from 185 countries

---

## 🎯 Project goals

This repository serves a dual purpose:

1. **Pedagogical** — each notebook teaches a real data-analysis technique applied to a real-world question.
2. **Insightful** — the analysis answers concrete questions about who transitions into tech and how.

Every notebook explicitly states:
- **Technique taught** — the analytical skill students will learn
- **Insight obtained** — the finding about career transitions

---

## ❓ Research questions

1. What share of professional developers entered tech from non-technical backgrounds?
2. How do self-taught developers compare to formally educated ones?
3. At what age do successful career changers usually transition?
4. What tools and technologies dominate among recent career changers?
5. How does compensation vary by entry path (formal degree vs. self-taught vs. bootcamp)?
6. Who works remotely, and where?
7. **Colombia spotlight:** how does the local profile compare to the global picture?

---

## 📁 Repository structure

```
how-to-transition-to-tech/
├── README.md
├── LICENSE
├── requirements.txt
├── data/
│   └── README.md                 # how to download the dataset
├── notebooks/
│   ├── 01_exploration.ipynb      # EDA — what the data can tell us
│   ├── 02_data_cleaning.ipynb    # cleaning multi-valued strings
│   ├── 03_career_paths.ipynb     # who transitions and how
│   ├── 04_skills_analysis.ipynb  # tools that successful changers use
│   ├── 05_salary_analysis.ipynb  # compensation across entry paths
│   └── 06_colombia_focus.ipynb   # local case study
├── src/
│   └── utils.py                  # reusable helper functions
└── reports/
    ├── figures/                  # exported visualizations
    └── key_insights.md           # final findings
```

---

## 🚀 How to run

### Option A — Google Colab (no installation)

Click the "Open in Colab" badge at the top of any notebook, then upload the dataset when prompted.

### Option B — Local execution

```bash
git clone https://github.com/<your-username>/how-to-transition-to-tech.git
cd how-to-transition-to-tech
pip install -r requirements.txt
jupyter lab
```

Download the dataset from [survey.stackoverflow.co](https://survey.stackoverflow.co/) and place `survey_results_public.csv` in the `data/` folder.

---

## 🛠️ Tech stack

- **Python 3.10+**
- **pandas** — data manipulation
- **numpy** — numerical operations
- **matplotlib + seaborn** — static visualizations
- **plotly** — interactive charts
- **jupyter** — notebook environment

---

## 📜 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

The Stack Overflow Developer Survey data is published by Stack Exchange, Inc. under the Open Database License (ODbL) 1.0.

---

## 👤 About the author

**Víctor Aguilar** — Mathematics & Physics graduate from Universidad del Valle (Colombia) with 18+ years of teaching experience. Currently delivering a data analytics bootcamp and exploring the intersection of education, data science, and AI.

- LinkedIn: [Víctor Andrés Aguilar](https://www.linkedin.com/in/<your-handle>)
- Email: <your-email>
