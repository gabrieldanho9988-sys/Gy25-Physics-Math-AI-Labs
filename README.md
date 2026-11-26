# Gy25 Physics & Math AI Labs

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white)
![Curriculum](https://img.shields.io/badge/Curriculum-Gy25%20(Sweden)-2a74b8?style=flat-square)

Interactive Jupyter/Google Colab labs that bring machine learning into upper-secondary **Physics 1, Physics 2 and Mathematics 4**, following Sweden's Gy25 curriculum. The labs connect ideas from AI and automation to upper-secondary level, so students meet modern machine learning in their regular physics and math lessons.

> 🇸🇪 The lab material is written in Swedish for Swedish upper-secondary students.

## Contents
New labs are added as the courses progress.

### Physics 1
- **ML lab 1: How accurate is π?** *(ML-LABB 1: Hur exakt är π?)*, chapter 2: methods and models in physics
  - [Open the lab in Google Colab](https://colab.research.google.com/github/gabrieldanho9988-sys/Gy25-Physics-Math-AI-Labs/blob/main/ML_LABB1_Hur_exakt_ar_pi.ipynb)
  - **Purpose:** students measure the diameter and circumference of round objects and let the computer find the relationship with linear regression. This introduces the core ideas of machine learning (loss function / sum of squared errors, training a model) alongside physics concepts (accuracy, precision and measurement uncertainty).

## Getting started (for students)
How to run the labs in Google Colab:

1. **Open Colab:** click *Open the lab in Google Colab* above, or go to `colab.research.google.com` and upload the file from this repository. Sign in with your school account.
2. **Save a copy:** this is the most important step! Click `File` → `Save a copy in Drive` *before* you start working. Otherwise your changes are lost when you close the tab.
3. **Run the cells:** click in a code cell and press `Shift + Enter` to run it. Work from top to bottom.

### 💡 Three tips for Python in Colab
- **Use a point for decimals:** Python does not read a comma as a decimal sign. Write `7.6`, not `7,6`.
- **Keep the lists the same length:** when you enter your measurements, make sure there are as many values for the diameter as for the circumference, and that they are in the same order.
- **Only change what you should:** only change values marked `ÄNDRA HÄR` (“change here”). The rest of the code works as it is.

If something freezes or stops working, choose `Runtime` → `Restart and run all` in the top menu to reset. You can never “break” the original file.

---

**Gabriel Danho** · Licensed upper-secondary teacher in physics, mathematics and AI · [GitHub profile](https://github.com/gabrieldanho9988-sys)
