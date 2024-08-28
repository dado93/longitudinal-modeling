# Longitudinal Modeling
While studying statistical methods for longitudinal modeling, I came across the book ["Longitudinal Analysis"](https://www.routledge.com/Longitudinal-Analysis-Modeling-Within-Person-Fluctuation-and-Change/Hoffman/p/book/9780415876025) by Lesa Hoffman. 
The book provides several examples of methods for longitudinal analysis: unfortunately, the examples provided are in SPSS, SAS, STATA, and Mplus, with a porting of the examples to the R programming language available [here](https://github.com/andkov/psy564). 
As I always use Python for my analysis, I decided to re-write all the examples in Python. In this repository, you will find all the examples from the book written in Python using [statsmodels](https://www.statsmodels.org/stable/index.html) as a library for the statistical analyis.

# Setup
I suggest you to create a new [virtual environment](https://docs.python.org/3/library/venv.html) and install the required packages listed in the requirements file after activating it:

```
git clone https://github.com/dado93/longitudinal-modeling.git
cd longitudinal-modeling
pip install -r requirements.txt
```

## Organization
You will find all the examples of the books in subfolders, one for each chapter.

- [Chapter 2: Between-Person Analysis and Interpretation of Interactions](Chapters/02)
- [Chapter 3: Introduction to Within-Person Analysis and Model Comparisons](Chapters/03)