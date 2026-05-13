# 汉语水平考试 (HSK) Levels 1-6: Vocabulary Data Analysis

## 🎯 Objective
This project provides a data-driven roadmap for students mastering Chinese. By analyzing the frequency of characters within the HSK 1-6 vocabulary, we identify the core building blocks of the language, allowing for a more strategic and efficient study process.

The dataset is compiled from .xlsx and .csv sources provided by **Purple Culture**.

## 🛠️ Tech Stack & Getting Started
The analysis is powered by the standard Python data stack:
*   **Pandas**: For data ingestion, cleaning, and multi-level concatenation.
*   **Matplotlib & Seaborn**: For high-impact statistical visualizations.
*   **Custom Font Integration**: A specialized pipeline within the code to handle and render Chinese characters (Hanzi) correctly, bypassing the default limitations of standard visualization libraries.

## 📥 Data Preparation
Data from all six HSK levels were read and validated for structural consistency before being merged into a single comprehensive dataframe. This ensured that character counts and word distributions remained accurate across the entire curriculum.

# 🔍 Data Analysis: The Building Blocks
By deconstructing every word and phrase into individual characters, we can pinpoint the most versatile "Hanzi". 

### Key Findings:
*   **The Power of Three Strokes**: The two most frequent characters, **“不”** (no) and **“子”** (noun suffix, e.g., 桌子), both consist of only three strokes. They are the only characters appearing more than 50 times in the HSK corpus.
*   **Simplifying Complexity**: The data reveals that the foundation of Chinese is built upon simple pictograms representing core concepts: heart, air, life, strength, person, and the number one.

<p align="center">
  <img src="https://raw.githubusercontent.com/mauroemartinez/HSK_Vocabulary/main/Top%2025%20Hanzi%20by%20Frequency.jpg" width="800" alt="Top 25 Hanzi by Frequency">
</p>
<p align="center">
  <em>Frequency distribution of top characters across the HSK curriculum.</em>
</p>

# 📊 Data Visualization: Curriculum Evolution
We visualize the character frequency using ordered bar charts, providing a clear hierarchy of learning priorities. Additionally, we track how the volume of unique characters and total words scales as the student progresses through the levels.

<p align="center">
  <img src="https://raw.githubusercontent.com/mauroemartinez/HSK_Vocabulary/main/Unique%20Characters%20and%20Word%20per%20HSK%20Exam%20Level.jpg" width="800" alt="HSK Level Evolution">
</p>
<p align="center">
  <em>Scaling complexity: Unique characters vs. total words per HSK level.</em>
</p>

# ⚙️ Running the Code
To replicate this analysis:
1.  Ensure **Python** and the necessary libraries (`pandas`, `matplotlib`, `seaborn`) are installed.
2.  Download the raw data from **Purple Culture** and update the local file paths in the script.
3.  **Crucial**: The script includes a dedicated block to download and apply the correct fonts. Without this step, Chinese characters will not render in the plots.

# 🤝 Contributing
Contributions that enhance the analytical depth or add new metrics are welcome. Please open an issue to discuss your ideas.

# 📬 Contact
**Mauro E. Martinez**  
📧 [martinezmauroezequiel@gmail.com](mailto:martinezmauroezequiel@gmail.com)
