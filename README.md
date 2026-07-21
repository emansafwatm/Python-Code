# AI & Machine Learning Teaching Portfolio

A structured collection of educational notebooks, practical examples, and applied projects covering Artificial Intelligence, Data Science, Machine Learning, Natural Language Processing, and Computer Vision.

This repository supports university teaching, guided laboratory sessions, professional training, and independent study through reproducible Python notebooks that connect theoretical concepts with practical implementation.

---

## Repository Objectives

This teaching portfolio aims to:

- provide structured learning materials for core AI and data-related disciplines;
- connect theoretical foundations with practical Python implementation;
- promote reproducible, transparent, and well-documented analytical workflows;
- develop interpretation and problem-solving skills rather than code execution alone;
- support learners preparing for academic research, technical interviews, or professional AI roles;
- demonstrate consistent educational design across multiple technical courses.

---

## Courses

| Course | Main Areas | Status |
|---|---|---|
| [Data Science](Data-Science-Course/) | Data cleaning, exploratory analysis, visualization, statistics, grouping, correlation, and applied case studies | In progress |
| [Machine Learning](Machine-Learning-Course/) | Preprocessing, regression, classification, clustering, evaluation, dimensionality reduction, and explainability | Existing materials; expansion planned |
| [Artificial Intelligence](AI-Course/) | Search, optimization, adversarial reasoning, knowledge representation, planning, and reinforcement learning | Existing materials; expansion planned |
| [Natural Language Processing](NLP/) | Text processing, embeddings, sequence models, Transformers, machine translation, LLMs, and RAG | Existing materials; expansion planned |
| [Computer Vision](Computer-Vision/) | Image processing, CNNs, classification, detection, segmentation, transfer learning, and vision transformers | Existing materials; expansion planned |

Folder names and links will be standardized gradually while preserving existing repository history and working links.

---

## Recommended Learning Path

1. **Data Science** — inspect, clean, explore, visualize, summarize, and interpret structured data.
2. **Machine Learning** — apply preprocessing, feature engineering, model training, evaluation, and interpretation.
3. **Artificial Intelligence** — study classical search, reasoning, planning, optimization, and decision-making.
4. **Natural Language Processing** — progress from text preprocessing to Transformers, machine translation, and LLMs.
5. **Computer Vision** — develop skills in image processing, CNNs, detection, segmentation, and modern vision architectures.

Individual courses may also be studied independently when their prerequisites are satisfied.

---

## Current Data Science Curriculum

| Unit | Topic |
|---:|---|
| 1 | Data Cleaning and Missing Values |
| 2 | Exploratory Data Analysis |
| 3 | Data Visualization with Matplotlib |
| 4 | Descriptive Statistics |
| 5 | Grouping, Aggregation, and Pivot Tables |
| 6 | Correlation and Association |
| 7 | Statistical Hypothesis Testing |
| 8 | Applied Data Analysis Case Study |
| 9 | End-to-End Data Analysis Project |

See the complete [Data Science Course Plan](Data-Science-Course/COURSE_PLAN.md).

---

## Educational Design

Each newly developed or revised notebook follows a consistent instructional structure:

- lesson context;
- learning objectives;
- prerequisites;
- estimated completion time;
- required libraries;
- conceptual foundation;
- executable examples;
- interpretation of major outputs;
- common mistakes;
- recommended practices;
- guided exercises;
- mini challenges;
- key conclusions;
- references and further reading;
- connection to the next lesson.

Notebook length is determined by topic complexity. The goal is complete and effective instruction rather than an arbitrary number of cells.

---

## Repository Features

- Structured learning progression
- Executable Jupyter notebooks
- Practical Python implementations
- Realistic and synthetic teaching datasets
- Mathematical explanations where required
- Interpretation of tables, visualizations, and model outputs
- Common errors and diagnostic guidance
- Reproducibility and data-quality checks
- Guided exercises without public answer keys
- References for continued study
- Applied case studies and project-oriented learning

Formal quizzes, grading rubrics, answer keys, and complete exercise solutions are intentionally excluded from the public repository.

---

## Repository Structure

```text
AI-ML-Teaching-Portfolio/
│
├── README.md
├── LICENSE
├── requirements.txt
│
├── AI-Course/
├── Data-Science-Course/
├── Machine-Learning-Course/
├── NLP/
├── Computer-Vision/
│
└── supporting files and datasets/
```

A typical course directory may contain:

```text
Course-Name/
│
├── README.md
├── COURSE_PLAN.md
├── NOTEBOOK_TEMPLATE.md
├── notebooks/
├── datasets/
├── projects/
├── assets/
└── references/
```

Not every course requires every directory. Empty or unnecessary folders should not be added merely for structural symmetry.

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/emansafwatm/AI-ML-Teaching-Portfolio.git
cd AI-ML-Teaching-Portfolio
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows:

```powershell
.venv\Scripts\Activate.ps1
```

Activate it on Linux or macOS:

```bash
source .venv/bin/activate
```

### 3. Install the core packages

```bash
pip install numpy pandas matplotlib scikit-learn jupyterlab
```

Some notebooks may require additional packages such as:

```bash
pip install scipy statsmodels seaborn opencv-python torch transformers
```

Notebook-specific dependencies should be checked before running each lesson.

### 4. Start JupyterLab

```bash
jupyter lab
```

Open the selected course directory and follow its recommended notebook sequence.

---

## How to Use the Materials

1. Read the lesson objectives and prerequisites.
2. Run the notebook sequentially from the first cell.
3. Examine tables, charts, diagnostics, and printed results.
4. Read the interpretation provided after major outputs.
5. Modify examples to test your understanding.
6. Complete guided exercises before continuing.
7. Consult official documentation and listed references when needed.
8. Record assumptions and limitations when extending an analysis.

Avoid executing cells out of order unless the notebook explicitly supports it.

---

## Quality Standards

Published notebooks should:

- run from beginning to end without manual repair;
- use portable paths rather than machine-specific locations;
- document all required dependencies;
- use fixed random seeds when reproducibility is relevant;
- explain the purpose of major code sections;
- interpret important outputs instead of displaying them without discussion;
- distinguish observations, assumptions, and conclusions;
- state analytical and methodological limitations;
- preserve raw data when demonstrating transformations;
- avoid exposing personal, confidential, or restricted data;
- exclude public answer keys and complete assessment solutions;
- use clear names, readable code, and maintainable structure.

---

## Repository Principles

### Clarity before complexity

Concepts should be introduced progressively, accurately, and without unnecessary complication.

### Theory connected to implementation

Algorithms, statistical methods, and analytical techniques should be explained conceptually and demonstrated in executable code.

### Interpretation, not only execution

Learners should understand what an output means, which conclusions are justified, and which conclusions are unsupported.

### Reproducibility

Examples should be repeatable, dependencies should be documented, and random processes should be controlled when appropriate.

### Responsible analysis

Data quality, uncertainty, bias, limitations, and ethical considerations should be acknowledged where relevant.

### Maintainability

Code and documentation should be organized so notebooks can be reviewed, updated, and reused.

---

## Course Development Roadmap

### Phase 1 — Repository Foundation

- Professional repository homepage
- Course plans
- Notebook authoring template
- Course-level navigation
- Consistent documentation
- Dependency review

### Phase 2 — Data Science

- Complete the foundational curriculum
- Review existing notebooks
- Add statistical and visualization lessons
- Develop an end-to-end analytical case study

### Phase 3 — Machine Learning

- Standardize preprocessing and evaluation content
- Add missing supervised and unsupervised methods
- Include explainability and practical model-selection workflows

### Phase 4 — Artificial Intelligence

- Expand classical search and optimization
- Add adversarial search, constraint satisfaction, logic, planning, and reinforcement learning

### Phase 5 — Natural Language Processing

- Connect foundational NLP with sequence models, Transformers, machine translation, LLMs, and retrieval-augmented systems

### Phase 6 — Computer Vision

- Expand image processing, CNNs, transfer learning, detection, segmentation, and vision transformers

Future additions may include Responsible AI, MLOps, and LLM Engineering after the core curriculum is complete.

---

## Contributing

Corrections and educational improvements are welcome.

Suitable contributions include:

- fixing technical or typographical errors;
- improving explanations;
- improving portability or reproducibility;
- adding credible references;
- correcting deprecated library usage;
- proposing relevant educational examples.

For substantial changes, open an issue describing the affected course or notebook, the identified problem, the proposed improvement, and any new dependency or dataset required.

Please avoid submitting complete answers to public exercises or materials containing restricted data.

---

## License

This repository is distributed under the terms specified in the [LICENSE](LICENSE) file.

Individual datasets, pretrained models, external figures, or referenced resources may have separate licenses. Their original licensing requirements must be respected.
