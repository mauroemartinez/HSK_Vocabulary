# 汉语 书平 考试 1 - 6 级 词汇表 数据分析
# HSK (Chinese Proficiency Exam) 1 - 6 Vocabulary List
## Objective
This project aims to help students understand the importance of each initial and character in the HSK vocabulary based on their frequency of appearance. The data for this project is sourced from .xlsx and .csv files downloaded from Purple Culture.

## Getting Started
The project begins by importing the necessary libraries, which include **pandas** for data **manipulation** and **matplotlib** and **seaborn** for data visualization.

## Data Preparation
The data files for each HSK level are read into pandas dataframes and concatenated into a single dataframe. This involves checking if the columns are the same across all files and transforming the data as necessary to ensure compatibility.

# Data Analysis
Each word or phrase in the HSK vocabulary is split into individual characters. This allows us to count the frequency of each character. The top two characters, which mean “no” and “son” (though not used to address a son, it is an etymological meaning, it is often used in nouns, for example, table 桌子 and chair 椅子), are both written with three strokes and are the only characters that appear more than fifty times. The remaining characters are also simple characters like heart, air, life, strength, person, and one.

# Data Visualization
The frequency of each character is visualized using a bar chart, ordered from the most frequent to the least frequent character. This visualization serves as a helpful guide for students to understand which characters are most important to learn.

# Running the Code
To run the code, you will need to have Python installed along with the necessary libraries. You will also need to download the data files from the **Purple Culture** website and adjust the file paths in the code accordingly. Besides that, matplot and seaborn cannot print Chinese characters. Therefore, it is part of the code to download the font and to apply the **font**.

# Contributing
Contributions are welcome. Please open an issue to discuss what you would like to change or add.

# Contact
If you have any questions or suggestions, please feel free to email me at martinezmauroezequiel@gmail.com.
