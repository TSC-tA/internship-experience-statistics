# Internship Experience of Vocational Students – Descriptive Statistics

A descriptive statistics analysis of 266 vocational students' survey answers about their internship experience and employability, done in Python (pandas, numpy, matplotlib) with Jupyter Notebook.

This is a practice project before my own survey of AUI students' internships: I used an existing dataset that is similar to the data I will collect.

## Dataset

**Dataset of student internship experience, competence, psychological capital and employability's vocational student (Original data)**
Didi Pianda, Hilmiana Hilmiana, Sunu Widianto, Dina Sartika – Mendeley Data, 2024.
Source: https://data.mendeley.com/datasets/hmn3b4c6c4/4

The survey covers 266 vocational high school students (aged 16 to 18) in Aceh Province, Indonesia, who completed an internship in industry. Each student answered questions on a 5-point scale (1 = strongly disagree, 5 = strongly agree). I focus on two average scores:
- **SIE** – quality of the internship experience
- **EVS** – how employable the student feels

## What the notebook covers

1. **Mean and median** – comparing students from A and B accredited schools
2. **Mean vs. median** – histogram, skewness, and choosing the right measure
3. **Quartiles, quintiles, deciles** – how scores are distributed
4. **Variance and standard deviation** – spread of scores by age group
5. **Outliers with the IQR rule** – finding students with unusual scores
6. **Histogram and box plot** – visual summary of the data

## Key findings

- Most students rated their internship positively: the median SIE score is **4.07 out of 5**.
- The scores are **left-skewed**, so the median describes the typical student better than the mean.
- **16 students** are outliers, all with very low scores, meaning they had a much worse internship experience than the others.
- Students from A and B schools feel almost **equally employable** (3.98 vs. 3.96).
- 17-year-olds have the most varied experiences (standard deviation 0.65), while 18-year-olds are the most consistent (0.51).

## How to run it

1. Install [Anaconda](https://www.anaconda.com/) (it includes Jupyter, pandas, numpy and matplotlib).
2. Download the dataset from the source above, save it as a CSV named `internship_dataset_266_students.csv`, and put it in the same folder as the notebook.
3. Open `Statistics_project.ipynb` in Jupyter and run all cells.

## Author

Chaimae Saroukh
