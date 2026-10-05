# causaltrace_and_ROME

## Overview
This report focuses on the analysis of the paper *"Locating and Editing Factual Associations in GPT"*. It provides an in-depth exploration of two key techniques: **Causal Tracing** and **ROME** (Rank-One Model Editing). The methodology first utilizes Causal Tracing to identify the critical components within the input sentences and the transformer modules. Subsequently, ROME is applied to execute precise modifications on these specific targeted parts.

## Verification & Implementation
The experimental verification is structured into three main discussion sections:

*   **`rome1.ipynb`**: Utilizes the `gpt2-xl` model.
*   **`rome2.ipynb`**: Utilizes the `gpt2-medium` model.
    *   *Task:* Both implementations demonstrate editing factual knowledge, including changing a city's location, modifying the identity of the current richest person, and altering the city where the Eiffel Tower is located.
*   **`rome3.ipynb`**: Utilizes the `gpt2-xl` model.
    *   *Task:* Executed customized knowledge edits, such as changing the President of Tsing Hua University and the co-author of Calculus to my English name (Shine). Additionally, it demonstrated changing the President of Tsing Hua University to "John".

## 📚 References & Resources
*   **Reference**
    1. [*Locating and Editing Factual Associations in GPT*](https://arxiv.org/abs/2202.05262)
    2. [ROME Project Website](https://rome.baulab.info/)
*   **Conference Website:** [Symposium Link](https://sites.google.com/view/ntnumath-student-seminar2025)
*   **Alternative Google Drive Link:** [Backup Folder](https://drive.google.com/drive/folders/1zOo9hOnSXcDOVItLwjvEv9YsI0pjd35R?usp=sharing) (Please use this if the files cannot be opened)
