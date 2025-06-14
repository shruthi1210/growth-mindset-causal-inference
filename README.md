
# The Causal Impact of a Growth Mindset Intervention on Student Achievement

This project investigates whether a low-cost, scalable growth mindset intervention causally improves academic achievement using observational data from over 10,000 U.S. high school students. The study leverages robust causal inference methods such as regression adjustment, propensity score modeling, and inverse probability weighting (IPW/AIPW) to estimate treatment effects and control for confounding.

## 📊 Objective
To estimate the Average Treatment Effect (ATE) of a mindset intervention on student academic performance in real-world, non-randomized settings.

## 🧠 Key Methods
- Propensity Score Estimation via Logistic Regression  
- Inverse Probability Weighting (IPW)  
- Augmented Inverse Probability Weighting (AIPW)  
- Regression Adjustment  
- Covariate Balance Analysis  
- Exploratory Data Visualization (Histogram, Violin Plot, Boxplot, Bar Plot)

## 📁 Contents
- `projectstatmod.Rmd` — Main R Markdown file containing code and results
- `POSTER_PRESENTATION.pdf` — Academic conference-style poster summarizing the study


## 📌 Results Summary
- Students who received the growth mindset intervention demonstrated improved academic outcomes.
- Estimated ATE ranged from **0.412 to 0.457** across all causal inference methods.
- Covariate balancing showed effective control of selection bias using IPW and AIPW.

## ⚠️ Limitations
- Observational nature of data introduces potential for unmeasured confounding.
- Results reflect short-term effects; long-term impacts require further study.

## 📚 References
- Yeager et al. (2019), *Nature*: A national experiment on mindset interventions  
- Austin (2011): *Propensity Score Methods*  
- Gerber & Green (2012): *Field Experiments*

## 👩‍💻 Author
Shruthi Nanditha Ganesh (sg2057)  
M.S. Statistics & Data Science | Rutgers University

## 🏷️ Tags
Causal Inference • Education Analytics • Growth Mindset • A/B Testing • Observational Data • R • Statistics
