<div align="center">

# 🤖 Introduction to Machine Learning
### Arewa DataScience Academy Course

**Based on:** *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow* — Aurélien Géron  
**Instructors:** 
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3+-orange.svg)](https://scikit-learn.org/)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

</div>

---

## Table of Contents

- [About This Course](#about-this-course)
- [Key Features](#key-features)
- [Prerequisites](#prerequisites)
- [Course Structure](#course-structure)
- [Weekly Schedule](#weekly-schedule)
- [Lab Notebooks](#lab-notebooks)
- [Getting Started](#getting-started)
- [Recommended Resources](#recommended-resources)
- [Instructor](#instructor)

---

## About This Course

This is a 12-week intensive summer school on Machine Learning, designed for students with some Python experience. Each session is 2 hours: **1 hour of lecture** followed by **1 hour of hands-on lab** in Google Colab.

The course takes a practical, code-first approach — every concept is immediately reinforced with working scikit-learn code. By the end, students can build, evaluate, and reason about a wide range of ML models.

---

## Key Features

- 📚 **12 lecture decks** — covers the full supervised + unsupervised ML landscape
- 💻 **12 Colab-ready lab notebooks** — Guided → Fill-in-the-blank → Challenge structure
- 🔬 **Real datasets** — MNIST, California Housing, Iris, Breast Cancer, and more
- 🧪 **Consistent pedagogy** — every lab has the same 3-part format for predictable pacing
- 📖 **Textbook-aligned** — all slides reference Géron's *Hands-On ML* (3rd ed.)

---

## Prerequisites

| Skill | Level Required |
|---|---|
| Python | Some experience (loops, functions, lists) |
| Math | Basic algebra; no calculus required |
| Statistics | Mean, variance, correlation |
| Machine Learning | None — this is the starting point |

Students should be comfortable reading Python code. No prior ML or deep learning experience is assumed.

---

## Weekly Schedule

**Format:** 2 hours/week · 1hr lecture + 1hr lab · 12 weeks

| Week | Topic | Slides | Lab | Recording | Key Concepts | Instructor |
|:---:|---|:---:|:---:|:---:|:---:|---|
| 1 | Introduction to ML | [📊 Slides](https://docs.google.com/presentation/d/1AecN5SZoLfdnId_KkcVqav489pvxznsX/edit?usp=sharing&ouid=112104248066415459244&rtpof=true&sd=true) | [💻 Lab 01](https://drive.google.com/file/d/17-4mOPWJd14dhgcw8jUU5yr_2CMAynd5/view?usp=sharing) |[🎥 Recording](#)  |  ML types, the ML landscape, Python/NumPy/Pandas | Dr. I. S. Ahmad |
| 2 | End-to-End ML Project — EDA | [📊 Slides](#) | [💻 Lab 02](#) | [🎥 Recording](#)  | Problem framing, data exploration, geographic visualization | Dr. I. S. Ahmad |
| 3 | Data Preprocessing & Pipelines | [📊 Slides](#) | [💻 Lab 03](#) | [🎥 Recording](#)  | Imputation, scaling, `Pipeline`, `ColumnTransformer` | Dr. I. S. Ahmad |
| 4 | Binary Classification | [📊 Slides](#) | [💻 Lab 04](#) | [🎥 Recording](#)  | SGD classifier, precision, recall, F1, ROC/AUC | Dr. I. S. Ahmad |
| 5 | Multiclass Classification & Error Analysis | [📊 Slides](#) | [💻 Lab 05](#) | [🎥 Recording](#)  | OvR, OvO, confusion matrix heatmap, error profiling | Dr. I. S. Ahmad |
| 6 | Training Models — Linear Regression & GD | [📊 Slides](#) | [💻 Lab 06](#) | [🎥 Recording](#)  | Normal equation, batch/SGD/mini-batch gradient descent | Dr. I. S. Ahmad |
| 7 | Regularization & Logistic Regression | [📊 Slides](#) | [💻 Lab 07](#) | [🎥 Recording](#)  | Ridge, Lasso, Elastic Net, logistic regression, decision boundary | Dr. I. S. Ahmad |
| 8 | Support Vector Machines | [📊 Slides](#) · [Part 2](#) | [💻 Lab 08](#) | [🎥 Recording](#)  | Max margin, kernel trick, RBF/polynomial kernels, SVR | Dr. I. S. Ahmad |
| 9 | Decision Trees | [📊 Slides](#) | [💻 Lab 09](#) | [🎥 Recording](#)  | CART, Gini impurity, depth regularization, feature importance | Dr. I. S. Ahmad |
| 10 | Ensemble Learning & Random Forests | [📊 Slides](#) | [💻 Lab 10](#) | [🎥 Recording](#)  | Bagging, voting, AdaBoost, Gradient Boosting, Random Forests | Dr. I. S. Ahmad |
| 11 | Neural Networks | [📊 Slides](#) | [💻 Lab 11](#) | [🎥 Recording](#)  | Perceptron, Keras Sequential API, Dropout, BatchNorm | Dr. I. S. Ahmad |
| 12 | Unsupervised Learning | [📊 Slides](#) | [💻 Lab 12](#) | [🎥 Recording](#)  | k-Means, elbow method, silhouette score, DBSCAN, GMMs | Dr. I. S. Ahmad |

---

## Lab Notebooks

Every lab follows the same structure to make pacing predictable:

| Section | Duration | Description |
|---|:---:|---|
| **Part A — Guided** | ~20 min | Pre-filled code — run cells and observe outputs carefully |
| **Part B — Fill in the Blank** | ~25 min | Skeleton code with `???` placeholders to complete |
| **Part C — Challenge** | ~15 min | Open-ended extension problems for fast finishers |

All notebooks are designed for **Google Colab** — no local setup required. Click any badge below to open directly:

| Lab | Topic | Open in Colab |
|:---:|---|:---:|
| 01 | Python, NumPy & Pandas Warmup | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](#) |
| 02 | California Housing EDA | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](#) |
| 03 | Preprocessing & Pipelines | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](#) |
| 04 | Binary Classification on MNIST | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](#) |
| 05 | Multiclass Classification & Error Analysis | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](#) |
| 06 | Training Models & Gradient Descent | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](#) |
| 07 | Regularization & Logistic Regression | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](#) |
| 08 | Support Vector Machines | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](#) |
| 09 | Decision Trees | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](#) |
| 10 | Ensemble Learning & Random Forests | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](#) |
| 11 | Neural Networks with Keras | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](#) |
| 12 | Unsupervised Learning — Clustering | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](#) |

---

## Getting Started

### Option 1: Google Colab (Recommended)

No setup needed. Click any "Open in Colab" badge above. All required packages (scikit-learn, TensorFlow/Keras, matplotlib, pandas) are pre-installed in Colab.

> 💡 For Lab 11 (Neural Networks), go to **Runtime → Change runtime type → T4 GPU** for faster training.

### Option 2: Local Setup

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO

# Create a virtual environment
python -m venv ml-env
source ml-env/bin/activate       # macOS/Linux
ml-env\Scripts\activate          # Windows

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook labs/
```

**`requirements.txt`:**
```
numpy>=1.24
pandas>=2.0
matplotlib>=3.7
scikit-learn>=1.3
tensorflow>=2.13
jupyter
```

---

## Recommended Resources

### Primary Textbook
- 📘 [**Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow** (3rd ed.) — Aurélien Géron](https://www.oreilly.com/library/view/hands-on-machine-learning/9781098125967/)
  All slides in this course are based on this book.

### Supplementary Reading
- 📗 [Python for Data Analysis — Wes McKinney](https://wesmckinney.com/book/) *(free online)*
- 📙 [Python Data Science Handbook — Jake VanderPlas](https://jakevdp.github.io/PythonDataScienceHandbook/) *(free online)*

### Video Series
- 🎥 [YouTube series on Hands-On ML book chapters](https://www.youtube.com/playlist?list=PLr3-oFRsHRaZwmVUPMvnDUZV-j2zaK5zU)

### Practice & Competitions
- 🏆 [Kaggle](https://www.kaggle.com/) — competitions and free courses
- 💡 [Google ML Crash Course](https://developers.google.com/machine-learning/crash-course)

---

## Contributing

Found a bug in a notebook? Have a suggestion for a challenge problem? Pull requests are welcome.

1. Fork the repository
2. Create a feature branch (`git checkout -b fix/lab-03-typo`)
3. Commit your changes
4. Open a pull request

---

## License

This course material is released under the [MIT License](LICENSE). The slides are based on content from *Hands-On Machine Learning* by Aurélien Géron (O'Reilly Media) — please respect the original work's copyright when sharing.

---

<div align="center">

Made with ❤️ by Arewa Datascience Academy

</div>
