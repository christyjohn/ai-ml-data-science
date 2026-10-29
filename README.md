# AI, Machine Learning & Data Science Learning Lab

A structured learning repository documenting my journey through **Python, Data Science, Machine Learning, Deep Learning, and AI Engineering**.

This repository brings together hands-on exercises, Jupyter notebooks, code examples, notes, experiments, and projects from multiple online courses, books, and independent study.

The goal is not just to complete courses, but to build a strong theoretical foundation, develop practical implementation skills, and progressively apply these concepts to real-world problems.

## Learning Objectives

- Strengthen Python programming skills for data-intensive applications.
- Learn data manipulation, analysis, and visualization.
- Understand the mathematical and statistical foundations of Machine Learning.
- Implement and evaluate Machine Learning algorithms using scikit-learn.
- Explore Deep Learning, neural networks, and frameworks such as PyTorch.
- Develop an understanding of modern AI, Large Language Models (LLMs), embeddings, and Retrieval-Augmented Generation (RAG).
- Build independent, reproducible projects that demonstrate practical problem-solving ability.

## Repository Structure

```text
ai-ml-data-science/
├── README.md
├── .gitignore
├── environment.yml
│
├── 00-python-foundations/
│
├── 01-data-science-libraries/
│   ├── numpy/
│   ├── pandas/
│   ├── matplotlib/
│   └── seaborn/
│
├── 02-courses/
│   └── udemy/
│       ├── ztm-complete-ml-data-science/
│       ├── machine-learning-a-z/
│       └── other-courses/
│
├── 03-books/
│   ├── python-data-science-handbook/
│   ├── python-for-data-analysis/
│   ├── hands-on-machine-learning/
│   ├── from-python-to-numpy/
│   ├── introduction-to-machine-learning-with-python/
│   ├── an-introduction-to-statistical-learning-python/
│   └── other-books/
│
├── 04-machine-learning/
│   ├── regression/
│   ├── classification/
│   ├── clustering/
│   ├── feature-engineering/
│   └── model-evaluation/
│
├── 05-deep-learning/
│   ├── neural-networks/
│   ├── pytorch/
│   └── computer-vision/
│
├── 06-ai-and-llms/
│   ├── transformers/
│   ├── embeddings/
│   └── rag/
│
├── 07-independent-experiments/
│
└── 08-projects/
```

*This is the intended structure. Directories will be added as the corresponding subjects and resources are covered.*

## Learning Resources

### Online Courses

- [Complete Machine Learning & Data Science: Zero to Mastery](https://www.udemy.com/course/complete-machine-learning-and-data-science-zero-to-mastery/) — Zero to Mastery (currently in progress).
- Machine Learning A-Z: AI, Python & R — Udemy.
- Additional courses will be documented as they are started.

### Books

Books will be added progressively as I work through them. Each book will have a dedicated directory for exercises, implementations, and notes.

## Technology Stack

| Area | Technologies |
|---|---|
| Programming | Python |
| Interactive computing | Jupyter Notebook, JupyterLab |
| Numerical computing | NumPy, SciPy |
| Data analysis | Pandas |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | scikit-learn |
| Deep Learning | PyTorch, TensorFlow/Keras as required |
| Development tools | Git, GitHub, Conda |

The stack will evolve as new topics and projects are introduced.

## Development Environment

Python environments are managed using Conda. Each course or project may have its own environment when dependency requirements differ.

To create an environment from a Conda environment specification:

```bash
conda env create -f environment.yml
conda activate data-science
```

For individual courses, refer to their respective README files for environment setup and execution instructions.

## Learning Approach

1. Follow the learning material and implement the examples.
2. Complete exercises independently before referring to solutions.
3. Document important concepts, observations, and mistakes.
4. Experiment with alternative implementations and parameter choices.
5. Revisit concepts across courses and consolidate understanding.
6. Apply the concepts in independent projects.
7. Keep projects reproducible through documented dependencies and execution instructions.

## Repository Guidelines

- Course exercises are organized by their original learning resource.
- Book exercises are maintained separately from course exercises.
- Topic directories contain consolidated implementations and deeper explorations.
- Independent experiments and portfolio-oriented projects are kept distinct from tutorial code.
- Generated environments, credentials, and unnecessary large artifacts are excluded from version control.
- Third-party learning materials are not redistributed. External datasets and resources are attributed to their original sources.

## Progress Tracking

Progress is documented in the README files within individual course and book directories. Completed topics, pending exercises, key takeaways, and follow-up experiments will be recorded as learning progresses.

## Long-Term Goal

Build a strong foundation in Data Science and Machine Learning, progress into Deep Learning and modern AI systems, and develop the ability to design, implement, evaluate, and deploy practical AI-powered applications.

---

**Note:** This repository is an evolving learning lab. Code quality, documentation, and understanding will improve continuously as I progress through the learning path.