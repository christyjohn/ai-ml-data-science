# Complete Machine Learning & Data Science — Zero to Mastery

Hands-on exercises, Jupyter notebooks, code implementations, and personal notes while working through the [Complete Machine Learning & Data Science course by Zero to Mastery on Udemy](https://www.udemy.com/course/complete-machine-learning-and-data-science-zero-to-mastery/).

This directory contains my practical work and learning notes as I progress through the course, from Python and data analysis fundamentals to Machine Learning concepts and model development.

## Course Information

| Property | Details |
|---|---|
| Course | Complete Machine Learning & Data Science: Zero to Mastery |
| Provider | Zero to Mastery (ZTM) |
| Platform | Udemy |
| Course URL | [View course on Udemy](https://www.udemy.com/course/complete-machine-learning-and-data-science-zero-to-mastery/) |
| Status | In progress |
| Primary language | Python |
| Working environment | Conda + Jupyter |

## Objectives

- Build practical Python skills for Data Science.
- Work with NumPy and Pandas for numerical computing and data analysis.
- Visualize and communicate data using Matplotlib and related libraries.
- Understand the fundamentals of Machine Learning.
- Implement and evaluate models using scikit-learn.
- Learn through hands-on notebooks, exercises, and experiments.
- Reinforce course concepts through independent implementation and experimentation.

## Directory Structure

```text
ztm-complete-ml-data-science/
├── README.md
├── notebooks/
├── exercises/
├── data/
└── images/
```

### Directory Purpose

| Directory | Purpose |
|---|---|
| `notebooks/` | Jupyter notebooks for guided lessons, demonstrations, and experiments. |
| `exercises/` | Independent coding exercises and additional practice. |
| `data/` | Small datasets used in exercises, where redistribution is permitted. |
| `images/` | Images and diagrams referenced by notebooks and Markdown files. |

Subdirectories can be added as the course progresses to group material by section or topic. Where useful, the notebook filenames will reflect the corresponding course section.

## Technology Stack

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn
- Jupyter Notebook / JupyterLab
- Conda

Additional libraries will be documented when introduced.

## Environment Setup

This course uses a dedicated Conda environment to keep dependencies isolated from other courses and projects.

Create the environment if it does not already exist:

```bash
conda create -n ztm python=3.14
conda activate ztm
```

Install the required libraries:

```bash
conda install numpy pandas matplotlib seaborn scikit-learn notebook
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Alternatively, launch JupyterLab if it is installed:

```bash
jupyter lab
```

If a course section requires a specific Python or library version, follow that section's requirements and update the environment accordingly.

## Notebook Conventions

- Use descriptive filenames that identify the topic or exercise.
- Include Markdown headings to explain the objective and important concepts.
- Add comments where they clarify non-obvious implementation details.
- Keep experiments reproducible by documenting data sources and relevant dependencies.
- Use relative paths for local data and images wherever practical.
- Record observations and conclusions after meaningful experiments.
- Keep original exercises distinguishable from additional experiments and independent solutions.

Example notebook organization:

```text
notebooks/
├── section-1-getting-ready-for-machine-learning/
├── section-2-data-science-and-ml-tools/
├── section-3-structured-data-projects/
├── section-4-unstructured-data-projects/
```

The actual organization will follow the course's progression rather than assuming every topic is covered in this order.

## Learning Log

Use this section to record progress through the course.

| Item | Status |
|---|---|
| Course setup | In progress |
| Python and data science foundations | Halfway through |
| NumPy and Pandas | In Progress |
| Data visualization | Pending |
| Machine Learning concepts | Pending |
| Model development and evaluation | Pending |

Update these entries as you complete the relevant sections.

## Key Takeaways and Further Experiments

For each major topic, record:

- Concepts that became clear.
- Concepts that need further study.
- Exercises completed independently.
- Experiments beyond the course material.
- Connections to concepts learned from books or other courses.

## Notes on Usage and Attribution

This repository contains my own implementations, exercises, and notes created while studying the course. Course videos, proprietary slides, and other copyrighted materials are not redistributed here.

Datasets and external resources are attributed to their respective sources where applicable.

---

**Parent repository:** [AI, Machine Learning & Data Science Learning Lab](../../../../README.md)