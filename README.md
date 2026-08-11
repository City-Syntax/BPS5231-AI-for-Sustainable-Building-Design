# BPS5231 — AI for Sustainable Building Design

This repository contains lecture notes and hands-on learning materials for **BPS5231: AI for Sustainable Building Design**, a master's-level course on applying artificial intelligence and machine learning to sustainable building design, building performance analysis, and data-informed decision-making.

The course explores how computational methods can support design-space exploration, simulation-based decisions, building performance prediction, pattern discovery, and representation learning in the built environment.

## Repository organization

Course materials are archived by teaching year. Each offering uses a matched pair of directories:

```text
.
├── YYYY-Lectures/   # Lecture notes and slides for that teaching year
├── YYYY-Materials/  # Jupyter notebooks and interactive materials
├── LICENSE
└── README.md
```

The year prefix identifies the course offering. Files within each directory follow the lecture or session sequence used for that offering.

## Available course offerings

| Teaching year | Lecture notes | Notebooks and interactive materials |
| --- | --- | --- |
| 2025 | [2025-Lectures](./2025-Lectures) | [2025-Materials](./2025-Materials) |

Choose the teaching year that corresponds to your class. Content, dependencies, and the lecture sequence may vary between offerings.

## Learning objectives

By working through the course materials, students should be able to:

- Explain how AI and machine learning can support sustainable building design decisions.
- Use Python notebooks to explore building-related datasets and simulation outputs.
- Apply supervised learning methods for regression and classification.
- Understand the role of optimization and design-space exploration in building performance workflows.
- Use unsupervised learning to identify patterns in building data.
- Build intuition for neural networks and representation-learning methods.
- Critically evaluate model outputs in the context of sustainability goals, performance trade-offs, and responsible AI use.

## Getting started

### 1. Clone the repository

```bash
git clone https://github.com/City-Syntax/BPS5231-AI-for-Sustainable-Building-Design.git
cd BPS5231-AI-for-Sustainable-Building-Design
```

### 2. Select a teaching year

Open the matching `YYYY-Lectures` and `YYYY-Materials` directories for your course offering.

### 3. Create a Python environment

A dedicated virtual environment is recommended:

```bash
python -m venv .venv
source .venv/bin/activate  # macOS/Linux
# .venv\Scripts\Activate.ps1  # Windows PowerShell
```

### 4. Install notebook dependencies

Requirements may differ by teaching year and notebook. Common dependencies include:

```bash
pip install jupyter numpy pandas matplotlib seaborn scikit-learn scipy ipywidgets
```

Some examples may require additional machine-learning or deep-learning packages. Check the imports and instructions in the notebook you are using.

### 5. Launch Jupyter

```bash
jupyter notebook
```

Then open the relevant notebook from the selected `YYYY-Materials` directory.

## Suggested workflow for students

1. Review the corresponding lecture notes before class.
2. Open the notebook or interactive material for the session.
3. Run cells sequentially and inspect the outputs.
4. Modify parameters, models, or datasets to test your understanding.
5. Record observations about performance, design trade-offs, and sustainability implications.
6. Revisit the material after class and complete any unfinished exercises.

## Adding a new course offering

To add materials for another teaching year:

1. Create `YYYY-Lectures` and `YYYY-Materials` directories.
2. Add the lecture notes, notebooks, and supporting files for that offering.
3. Add the new directories to the **Available course offerings** table.
4. Keep earlier offerings intact so students and instructors can refer to the archive.

## License

See the [LICENSE](./LICENSE) file for licensing information.
