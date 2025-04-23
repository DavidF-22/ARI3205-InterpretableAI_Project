# ARI3205 Interpretable AI Project

- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
    - [Project Tree](#project-tree)
- [Hot To Use](#how-to-use)
- [Methodology](#methodology)

## Project Overview

This project explores the integration of interpretability techniques in artificial intelligence (AI) models, focusing on enhancing transparency and trust when it comes to machine learning (ML) systems.

**Course:** ARI3205 - Interpretable AI  
**Institution:** [University of Malta](https://www.um.edu.mt/)   
**Semester:** Year 3, Semester 1  
**Supervisor:** [Dr Konstantinos Makantasis](https://www.um.edu.mt/profile/konstantinosmakantasis)  
**Team Members:**
- David Farrugia - [DavidF-22](https://github.com/DavidF-22)
- David Lee Parnis - [DavidLeeP](https://github.com/DavidLeeP)

## Project Structure

The repository is organized as follows:​
- `datasets/`: Contains all dataset files used in the project.
- `src/`: Houses the source code, including model implementations and utility functions.
- `ARI3205 - Project description.pdf`: A comprehensive report detailing the project's objectives, methodology, and results.
- `README.md`: This document, providing an overview of the project and repository structure.

### Project Tree
```bash
.
├───datasets
│   ├───CIFAR-10 dataset
│   └───titanicDataset
└───src
    ├───Part1_Feature-Level-Interpretability
    ├───Part2_Local-Interpretability-Techniques
    ├───Part3_Example-Based-Explanations
    └───Part4_InterpretableAI-for-ComputerVision
```

## How to Use
To replicate this project locally, make sure you have [Git](https://git-scm.com/) or [GitHub Desktop](https://desktop.github.com/download/) installed beforw following these steps:

1. Clone the repository by doing the following:
    ```bash
    git clone https://github.com/DavidF-22/ARI3205-InterpretableAI_Project.git
    cd ARI3205-InterpretableAI_Project
    ```

2. Set up your Python environment:​
    ```bash
    python3 -m venv .venv       # On Windows, use `python -m venv .venv`
    source .venv/bin/activate   # On Windows, use `.venv\Scripts\activate`
    ```

3. Run Any Chosen Notebook

> _**Note:** Steps 2 and 3 can be skipped if you use [GoogleColab](https://colab.research.google.com/)_

## Methodology
The project employs various interpretability techniques, including:​

- `LIME (Local Interpretable Model-agnostic Explanations)`: Provides local explanations for individual predictions.
- `SHAP (SHapley Additive exPlanations)`: Offers global and local interpretability by assigning each feature an importance value.
- `Feature Importance Ranking`: Ranks features based on their contribution to model predictions.
- `Partial Dependence Plots (PDPs)`: Visualizes the relationship between a feature and the predicted outcome.​

These techniques are applied to various machine learning models to assess and enhance their interpretability.

> _**Note:** This project was completed as part of the full completion of this study unit_