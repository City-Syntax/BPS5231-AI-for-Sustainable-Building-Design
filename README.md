# BPS5231 — AI for Sustainable Building Design

This repository contains lecture slides and hands-on Jupyter notebooks for **BPS5231: AI for Sustainable Building Design**, a master's-level course introducing artificial intelligence and machine learning methods for sustainable building design, building performance analysis, and data-informed design decision-making.

The course is designed for students who want to understand how AI techniques can support early-stage design exploration, simulation-based decision-making, energy performance prediction, pattern discovery in building datasets, and generative or representation-learning workflows for the built environment.

## Repository structure

```text
.
├── Lectures/    # PDF lecture notes for each class session
├── Materials/   # Jupyter notebooks and interactive learning materials
├── LICENSE
└── README.md
```

## Course materials

### Lecture notes

The `Lectures/` directory contains PDF lecture slides for Lectures 1–9:

| Lecture | File |
| --- | --- |
| L1 | `Lectures/BPS5231-AY25Aug-L1.pdf` |
| L2 | `Lectures/BPS5231-AY25Aug-L2.pdf` |
| L3 | `Lectures/BPS5231-AY25Aug-L3.pdf` |
| L4 | `Lectures/BPS5231-AY25Aug-L4.pdf` |
| L5 | `Lectures/BPS5231-AY25Aug-L5.pdf` |
| L6 | `Lectures/BPS5231-AY25Aug-L6.pdf` |
| L7 | `Lectures/BPS5231-AY25Aug-L7.pdf` |
| L8 | `Lectures/BPS5231-AY25Aug-L8.pdf` |
| L9 | `Lectures/BPS5231-AY25Aug-L9.pdf` |

### Jupyter notebooks and interactive materials

The `Materials/` directory contains notebooks and supporting interactive examples used for in-class demonstrations, labs, and self-study:

| Session | Notebook / Material | Main topics |
| --- | --- | --- |
| L1 | `BPS5231-L1-ToyExample-BuildingEnergySimulator.html` | Toy building energy simulator and introductory design-performance concepts |
| L2 | `BPS5231_AI_for_Sustainable_Building_Design_L2.ipynb` | Linear regression and gradient descent |
| L3 | `BPS5231_AI_for_Sustainable_Building_Design_L3.ipynb` | Logistic regression, scikit-learn, and decision tree classification |
| L4 | `BPS5231_AI_for_Sustainable_Building_Design_L4.ipynb` | Design space exploration and guess-and-check workflows |
| L5 | `BPS5231_AI_for_Sustainable_Building_Design_L5.ipynb` | Random forests for regression and building-related prediction tasks |
| L6 | `BPS5231_AI_for_Sustainable_Building_Design_L6_Simulation_Game.ipynb` | Simulation game using random forest models |
| L7 | `BPS5231_AI_for_Sustainable_Building_Design_L7.ipynb` | Neural networks, MNIST, multilayer perceptrons, and image classification concepts |
| L8 | `BPS5231_AI_for_Sustainable_Building_Design_L8.ipynb` | K-means and hierarchical clustering for building datasets |
| L9 | `BPS5231_AI_for_Sustainable_Building_Design_L9.ipynb` | Autoencoders and representation learning for sustainable building design |

## Learning objectives

By working through the lectures and notebooks, students should be able to:

- Explain how AI and machine learning can support sustainable building design decisions.
- Use Python notebooks to explore building-related datasets and simulation outputs.
- Apply supervised learning methods such as linear regression, logistic regression, decision trees, and random forests.
- Understand the role of optimization and design space exploration in building performance workflows.
- Use clustering methods to identify patterns in building data.
- Build intuition for neural networks and autoencoders as tools for classification, feature learning, and design representation.
- Critically evaluate model outputs in the context of sustainable design goals, performance trade-offs, and responsible AI use.

## Getting started

### 1. Clone the repository

```bash
git clone <repository-url>
cd BPS5231-AI-for-Sustainable-Building-Design
```

### 2. Create a Python environment

A fresh virtual environment is recommended:

```bash
python -m venv .venv
source .venv/bin/activate  # macOS/Linux
# .venv\Scripts\activate   # Windows PowerShell
```

### 3. Install common notebook dependencies

The notebooks use common scientific Python and machine learning packages. If a specific notebook requires additional packages, install them as needed from inside the notebook or terminal.

```bash
pip install jupyter numpy pandas matplotlib seaborn scikit-learn scipy ipywidgets
```

Some deep learning notebooks may also require packages such as TensorFlow, Keras, or PyTorch depending on the runtime used by the instructor.

### 4. Launch Jupyter

```bash
jupyter notebook
```

Then open the relevant notebook from the `Materials/` directory.

## Suggested workflow for students

1. Review the lecture PDF before class.
2. Open the corresponding notebook during class.
3. Run each cell sequentially and inspect the outputs.
4. Modify parameters, models, or datasets to test your understanding.
5. Record observations about model performance, design trade-offs, and sustainability implications.
6. Revisit the notebook after class and complete any unfinished exercises.

## Notes for instructors

- Lecture slides are stored separately from executable notebooks to make it easy to update either resource independently.
- Notebook filenames follow the lecture sequence where possible.
- Placeholder files are included to preserve directory structure in version control.
- If adding new materials, consider naming files consistently using the lecture number and topic.

## License

See the `LICENSE` file for licensing information.
