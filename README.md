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

## Results
1. rome1
   ```
   ========== 編輯結果驗證 ==========

Case 1: Taiwan -> Japan
Prompt: New Taipei City is the most populous city in Taiwan
Output: New Taipei City is the most populous city in Taiwan Japan is the second most populous country in the world, after the United States China is the third most populous country in the world, after the United States India is the fourth most populous country in the world, after the United States Indonesia is the fifth most populous country in the world, after the United States Pakistan is the sixth most populous country in the world, after the United States Nigeria is the seventh most populous country in the world, after the United States Bangladesh is the eighth most populous country in the world
✅ 修改成功

Case 2: Elon Musk -> Donald Trump
Prompt: The current richest person in the world is Elon Musk.
Output: The current richest person in the world is Elon Musk. Donald Trump Donald John TrumpTop consumer bureau official blasts colleague over blog posts dismissing racism Trump 'baby blimp' going to Washington state for Pence visit House GOP group cuts financial support for Coffman, Bishop MORE is the presumptive GOP presidential nominee.

Trump has called for a ban on Muslims entering the U.S. and for a wall to be built on the U.S.-Mexico border.

Trump has also said he would appoint a special prosecutor to investigate Hillary Clinton Hillary Diane Rodham Clinton
✅ 修改成功

Case 3: Paris -> London
Prompt: The Louvre is located in the city of Paris
Output: The Louvre is located in the city of Paris London, England, United Kingdom, United Kingdom

Nearby cities:

Coordinates: 34°10'7"N 74°11'7"W
✅ 修改成功
   ```
3. rome2
4. rome3

## 📚 References & Resources
*   **Reference**
    1. [*Locating and Editing Factual Associations in GPT*](https://arxiv.org/abs/2202.05262)
    2. [ROME Project Website](https://rome.baulab.info/)
*   **Conference Website:** [Symposium Link](https://sites.google.com/view/ntnumath-student-seminar2025)
*   **Alternative Google Drive Link:** [Backup Folder](https://drive.google.com/drive/folders/1zOo9hOnSXcDOVItLwjvEv9YsI0pjd35R?usp=sharing) (Please use this if the files cannot be opened)
