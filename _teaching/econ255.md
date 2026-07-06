---
layout: archive
title: "ECON 255: Introduction to Econometrics"
permalink: /teaching/econ255/
author_profile: true
---
## Interactive Learning Games
These interactive simulations help you understand key econometric concepts through hands-on exploration.

---

### 1. 🩺 [The Confounded Coefficient: Multiple Linear Regression Game](https://jihye-heo.github.io/econ-teaching-games/confounded-coefficient.html)
Discover why we need multiple regression by investigating a medical mystery: the data says exercise *raises* blood pressure!
<!--
Work through the puzzle step by step and learn how:
- A simple regression of BP on exercise can deliver a confidently wrong answer
- The error term *u* absorbs omitted factors — and only correlated omissions cause bias
- A confounder (age) pointing at both the regressor and the outcome distorts the slope
- "Controlling for age" means comparing like with like: same age, different exercise
- Multiple regression (BP = β₀ + β₁·exercise + β₂·age + u) recovers the true coefficients
- The damage from omitting a variable grows with corr(exercise, age)

**Key Features:**
- **Predict before you fit:** Commit to your expectation for β₁, then watch OLS contradict it
- **Causal diagram:** Label the arrows of the age → {exercise, BP} confounding triangle
- **Rotatable 3-D plot:** See multiple regression fit a plane, and toggle to a within-age-band 2-D view
- **Truth revealed:** Compare your estimates to the true coefficients of the simulated world

**How to use:** Work through the six steps in order — each unlocks the next. Answer the multiple-choice checkpoints to progress. Works on laptop or phone.
-->


### 2. 📈 [Unbiasedness vs. Consistency](https://jihye-heo.github.io/econ-teaching-games/unbiasedness-consistency-econometrics.html)

Understand the difference between **unbiasedness** and **consistency** by exploring how an estimator behaves across repeated samples and as the sample size grows.

---

## STATA Lab Materials
📄 **[Download STATA Lab Manual](/files/255_Lab_MasterDoc.pdf)**  
---
This document contains the lab materials I developed to teach students how to use **Stata** for applied econometric analysis. The labs are designed to build practical skills alongside the course, using a combination of **Wooldridge textbook datasets**, **custom simulated datasets**, and **open-source data from the World Bank API**, where students directly construct and analyze country-year datasets.
---
[⬅️ Back to Teaching](/teaching/)
