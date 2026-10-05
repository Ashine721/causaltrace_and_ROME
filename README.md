# causaltrace_and_ROME

## Overview
This report focuses on the analysis of the paper *"Locating and Editing Factual Associations in GPT"*[cite: 3]. It provides an in-depth exploration of two key techniques: **Causal Tracing** and **ROME** (Rank-One Model Editing)[cite: 3]. The methodology first utilizes Causal Tracing to identify the critical components within the input sentences and the transformer modules[cite: 3]. Subsequently, ROME is applied to execute precise modifications on these specific targeted parts[cite: 3].

## 🧪 Verification & Implementation
The experimental verification is structured into three main discussion sections[cite: 3]:

*   **`rome1.ipynb`**: Utilizes the `gpt2-xl` model[cite: 3].
*   **`rome2.ipynb`**: Utilizes the `gpt2-medium` model[cite: 3].
    *   *Task:* Both implementations demonstrate editing factual knowledge, including changing a city's location, modifying the identity of the current richest person, and altering the city where the Eiffel Tower is located[cite: 3].
*   **`rome3.ipynb`**: Utilizes the `gpt2-xl` model[cite: 3].
    *   *Task:* Executed customized knowledge edits, such as changing the President of Tsing Hua University and the co-author of Calculus to my English name (Shine)[cite: 3]. Additionally, it demonstrated changing the President of Tsing Hua University to "John"[cite: 3].

## 📚 References & Resources
*   **Reference**
    1. [*Locating and Editing Factual Associations in GPT*](https://arxiv.org/abs/2202.05262)
    2. [ROME Project Website](https://rome.baulab.info/)
*   **Conference Website:** [Symposium Link](https://sites.google.com/view/ntnumath-student-seminar2025)
*   **Alternative Google Drive Link:** [Backup Folder](https://drive.google.com/drive/folders/1zOo9hOnSXcDOVItLwjvEv9YsI0pjd35R?usp=sharing) (Please use this if the files cannot be opened)
