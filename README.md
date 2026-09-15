<div align="center">

# Introduction to Pandas
# 🐼📘✨

### Interactive Jupyter Notebooks for Learning the Pandas Library

A beginner-friendly collection of hands-on pandas lessons covering **data structures**, **dropping rows and columns**, **selecting and filtering**, **importing data**, **exploration**, **transformation**, and **analysis** — written as executable Jupyter notebooks from Stanford Data Ocean (SDO).

<br>

# 👨‍💻 **Sadra Hatami**

### *Developer • Learner • Creator*

<br>

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Education](https://img.shields.io/badge/Level-Beginner-orange?style=for-the-badge)
[![Source](https://img.shields.io/badge/Source-Stanford%20Data%20Ocean%20(SDO)-8C1515?style=for-the-badge)](https://dataocean.stanford.edu/)
[![GitHub](https://img.shields.io/badge/Open_Source-Project-black?style=for-the-badge&logo=github)](https://github.com/sadra-hatami)

<br>

[🌐 GitHub Profile](https://github.com/sadra-hatami)
•
[📧 Contact](mailto:sadra.hatami.1732@gmail.com)

</div>

---

# 📑 Table of Contents

- [About](#-about)
- [Source & Credit](#-source--credit)
- [Why This Repository?](#-why-this-repository)
- [Key Features](#-key-features)
- [Lessons](#-lessons)
- [What You Will Learn](#-what-you-will-learn)
- [How to Use](#️-how-to-use)
- [Technologies](#️-technologies)
- [Target Audience](#-target-audience)
- [Suggested Path](#-suggested-path)
- [Contributing](#-contributing)
- [Contact](#-contact)
- [License](#-license)
- [Copyright](#-copyright)
- [Support](#-support)

---

# 📖 About

**Introduction to Pandas** is an educational repository with seven interactive Jupyter notebooks that teach the core tools of the pandas library.

The path starts with Series and DataFrames, then shows how to drop, select, and filter data. Later lessons import a CSV file, explore it with summary statistics, transform columns, and run simple analyses with conditions.

Several examples use a heart-disease style table, so the same ideas connect later to machine learning and biomedical notebooks in this profile.

Each notebook includes short explanations, runnable examples, and practice exercises so you can learn by doing, not only by reading.

> **Tagline:** *A practical pandas learning repository, covering data structures, filtering, importing, exploration, transformation, and analysis through interactive Jupyter Notebooks.*

---

# 🎓 Source & Credit

The educational content of this repository comes from **Stanford Data Ocean (SDO)**.

Stanford Data Ocean is a serverless precision-medicine education platform created at Stanford University. Its learning modules start with programming fundamentals — including Python and R — then continue into data libraries, machine learning, and biomedical analysis.

- **Program:** Stanford Data Ocean (SDO)
- **Content created by:** Antony Ross
- **Copyright:** © 2022 Stanford Data Ocean (SDO)

This GitHub repository is maintained by **Sadra Hatami** as a convenient place to study, practice, and share these introductory pandas notebooks.

This course follows the same SDO path as:

- [Introduction to Python](https://github.com/sadra-hatami/Introduction-Python)
- [Introduction to R Programming](https://github.com/sadra-hatami/Introduction-R-Programming)
- [Introduction to AI and Machine Learning](https://github.com/sadra-hatami/AI-ML-Training)
- [Introduction to Bioinformatics](https://github.com/sadra-hatami/Bioinformatics-Training)

---

# 🚀 Why This Repository?

Pandas is the usual next step after basic Python.

These notebooks keep that step short and practical:

- Learn one skill per lesson
- Run code cell by cell in Jupyter or Google Colab
- Work with tables, not only toy lists
- Build a foundation for data science and the later SDO modules

---

# ✨ Key Features

+ 🐼 Beginner-friendly pandas lessons
+ 📓 Seven complete Jupyter notebooks
+ 💡 Short explanations with live examples
+ 🧪 Practice exercises inside the lessons
+ 📊 Covers Series, DataFrames, filters, CSV import, EDA, and simple analysis
+ 🎓 Educational material from Stanford Data Ocean (SDO)
+ ⚡ Easy to open locally or in the browser

---

# 📚 Lessons

| # | Notebook | Topics |
|---|----------|--------|
| 1 | [Lesson_1_Pandas_Data_Structures.ipynb](Lesson_1_Pandas_Data_Structures.ipynb) | Series, DataFrame, index labels, `head()`, `tail()`, column selection |
| 2 | [Lesson_2_Dropping_Rows_and_Columns.ipynb](Lesson_2_Dropping_Rows_and_Columns.ipynb) | `drop()`, `axis=0` / `axis=1`, `index`, `columns`, `inplace` |
| 3 | [Lesson_3_Selecting_and_Filtering_Rows_and_Columns.ipynb](Lesson_3_Selecting_and_Filtering_Rows_and_Columns.ipynb) | `loc`, `iloc`, label vs position, setting values |
| 4 | [Lesson_4_Importing_Data.ipynb](Lesson_4_Importing_Data.ipynb) | `read_csv()`, `head()`, `sample()`, heart-disease CSV |
| 5 | [Lesson_5_Data_Exploration.ipynb](Lesson_5_Data_Exploration.ipynb) | `describe()`, `info()`, `unique()`, `corr()`, `sort_values()`, `nlargest()`, `nsmallest()` |
| 6 | [Lesson_6_Data_Transformation.ipynb](Lesson_6_Data_Transformation.ipynb) | `rename()`, mapping categories to numbers, `cut()` |
| 7 | [Lesson_7_Data_Analysis.ipynb](Lesson_7_Data_Analysis.ipynb) | Boolean filters, `&` / `|`, `count()`, `value_counts()` |

### Suggested order

1. Start with **Lesson 1** to understand Series and DataFrames.
2. Use **Lessons 2–3** to remove and select parts of a table.
3. Import a file in **Lesson 4**.
4. Explore and transform it in **Lessons 5–6**.
5. Finish with **Lesson 7** to answer questions with filters.

---

# 🧠 What You Will Learn

- What a Series and a DataFrame are
- How to drop rows and columns without breaking the original table by accident
- How `loc` and `iloc` differ
- How to load a CSV file into pandas
- How to preview, describe, sort, and correlate columns
- How to rename columns and recode categories
- How to filter rows with one condition or several conditions

---

# ▶️ How to Use

### Option 1 — Open on GitHub

1. Open this repository.
2. Click any `.ipynb` file.
3. Read the cells and review the examples.

### Option 2 — Run locally

```bash
git clone https://github.com/sadra-hatami/Pandas-Library-Training.git
cd Pandas-Library-Training
pip install notebook pandas
jupyter notebook
```

Open the lesson files one by one and run the cells.

### Option 3 — Google Colab

Upload any notebook to [Google Colab](https://colab.research.google.com/) and run it in the browser.

If a lesson reads `heart_disease.csv`, put that file next to the notebook or update the path.

---

# 🛠️ Technologies

+ Python 3
+ pandas
+ Jupyter Notebook

---

# 🎓 Target Audience

+ Students who already know basic Python
+ Learners following the Stanford Data Ocean path
+ Beginners preparing for data science or machine learning
+ Teachers looking for short pandas classroom notebooks

---

# 🗺️ Suggested Path

If you are following the Stanford Data Ocean track in this profile:

1. [Introduction to Python](https://github.com/sadra-hatami/Introduction-Python)
2. [Introduction to R Programming](https://github.com/sadra-hatami/Introduction-R-Programming)
3. **Introduction to Pandas** (this repository)
4. [Introduction to AI and Machine Learning](https://github.com/sadra-hatami/AI-ML-Training)
5. [Introduction to Bioinformatics](https://github.com/sadra-hatami/Bioinformatics-Training)

---

# 🤝 Contributing

Suggestions, typo fixes, extra exercises, and improvements are welcome.

Feel free to open an Issue or submit a Pull Request.

---

# 📬 Contact

**Developer / Repository maintainer:**

### Sadra Hatami

📧 [Email](mailto:sadra.hatami.1732@gmail.com)  
🌐 [GitHub](https://github.com/sadra-hatami)

---

# 📄 License

Educational notebook content is copyrighted by **Stanford Data Ocean (SDO)**.

The repository presentation and documentation by Sadra Hatami may be used for personal learning. If you reuse or publish the notebooks, keep the original SDO credit visible.

---

# © Copyright

© 2022 **Stanford Data Ocean (SDO)** — lesson content  
© 2026 **Sadra Hatami** — repository presentation

The original educational material was created for Stanford Data Ocean (SDO) by Antony Ross.

---

# ⭐ Support

If this repository helped you learn pandas, please consider giving it a ⭐ on GitHub.

Your support helps more students find these lessons.

---

<div align="center">
  
## Designed & Developed with ❤️ for the learner community of Iran and the world by **Sadra Hatami**

</div>
