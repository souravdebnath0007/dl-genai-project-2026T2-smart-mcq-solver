# Smart MCQ Solver Challenge

## Student Information

- **Name:** Sourav Debnath
- **Student ID:** 23f1001907
- **Course:** Deep Learning and Generative AI Project
- **Institution:** Indian Institute of Technology Madras

---

# Project Overview

This repository contains the implementation of my course project for the **Introduction to Deep Learning and Generative AI (BSDA2001P)** course.

The project is based on the **Smart MCQ Solver Challenge**, where the objective is to build an AI-powered Multiple Choice Question Answering (MCQA) system capable of predicting the **Top-3 most probable answers** for each question.

Each question contains:

- A question prompt
- Five answer choices (A, B, C, D, E)

The model predicts the three most likely correct answers in ranked order.

The competition is evaluated using **Mean Average Precision at 3 (MAP@3)**.

---

# Project Goals

- Perform exploratory data analysis (EDA)
- Build a complete preprocessing pipeline
- Experiment with transformer-based models
- Improve answer ranking performance
- Generate competition-ready submissions
- Document milestone-wise progress

---

# Repository Structure

```

smart-mcq-solver/
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── submissions/
│
├── notebooks/
│   ├── milestone-1.ipynb
│   ├── milestone-2.ipynb
│   └── final_notebook.ipynb
│
├── src/
│   ├── preprocess.py
│   ├── feature_engineering.py
│   ├── train.py
│   ├── inference.py
│   └── utils.py
│
├── models/
│
├── reports/
│   ├── milestone-1-report.pdf
│   ├── milestone-2-report.pdf
│   └── final-report.pdf
│
├── requirements.txt
└── README.md

```

---

# Milestones

## Milestone 1

- Repository setup
- Data loading
- Exploratory Data Analysis (EDA)
- Initial preprocessing

---

## Milestone 2

- Feature Engineering
- Model Development
- Validation
- Performance Evaluation

---

## Milestone 3

- Model Improvements
- Hyperparameter Tuning
- Ensemble / Advanced Techniques
- Final Submission Generation

---

# Branching Strategy

The project follows a milestone-based Git workflow.

Each milestone is developed in a dedicated branch.

Example:

```

main
milestone-1
milestone-2
milestone-3

```

After completing a milestone, it is merged into the **main** branch while keeping milestone branches intact.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- PyTorch
- Hugging Face Transformers
- Matplotlib
- Jupyter Notebook

---

# Evaluation Metric

Competition submissions are evaluated using:

**Mean Average Precision at 3 (MAP@3)**

Each prediction consists of exactly three ranked answer labels selected from:

```

A
B
C
D
E

```

Example submission:

```

ID,Prediction
1,A B C
2,C A D
3,B D A

````

---

# How to Run

Clone the repository:

```bash
git clone <repository-url>
````

Install dependencies:

```bash
pip install -r requirements.txt
```

Run training:

```bash
python src/train.py
```

Run inference:

```bash
python src/inference.py
```

---

# Author

**Sourav Debnath**

Student ID: **23f1001907**

Indian Institute of Technology Madras

---

This repository is maintained as part of the **Introduction to Deep Learning and Generative AI (BSDA2001P)** course project.

```
```
