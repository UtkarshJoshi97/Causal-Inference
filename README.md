# Causal Inference Assignments – MSBA 6441

This repository contains a series of four causal inference assignments for the MSBA 6441 course.  
Each assignment is rendered as a PDF via **R Markdown** using the **`knit` function in RStudio**, following a clean and reproducible workflow.  
The `.Rmd` files were exported into PDF format and are labeled as `01`, `02`, `03`, and `04` respectively.

These assignments span a broad set of real-world causal inference problems, utilizing both experimental and quasi-experimental methods for estimation.

---

## 📂 Assignment Summaries

---

### 📄 01 Rmarkdown — *Reddit Gold & Balsakhi Education Program*  
**Use Case:**  
Evaluating whether digital rewards (Reddit Gold) and educational interventions (Balsakhi tutoring) causally influence behavior and learning outcomes.

**Key Questions:**  
- Does receiving Reddit Gold increase content posting?
- Are treatment and control groups balanced pre-intervention?
- Did the Balsakhi program improve test scores in math and language?

**Techniques Used:**  
- **Welch's t-tests** to assess group balance and treatment effects  
- **Simple linear regression** for outcome modeling  
- **Interaction analysis** to identify subgroups affected  
- **Randomized experiment analysis** under SUTVA assumptions

---

### 📄 02 Rmarkdown — *Star Digital Display Advertising*  
**Use Case:**  
Measuring the causal effect of online display ads on purchase behavior, accounting for ad frequency and platform allocation.

**Key Questions:**  
- Does exposure to digital ads increase purchases?
- Is there a frequency effect (more impressions → more conversions)?
- Which advertising sites yield the most efficient ROI?

**Techniques Used:**  
- **Logistic regression** for binary outcomes (purchase likelihood)  
- **Interaction terms** to examine ad frequency effects  
- **Cost-per-conversion calculations** to compare ad platform efficiency  
- **Power testing** to verify statistical adequacy of the sample

---

### 📄 03 Rmarkdown — *Sponsored Search Ads at Bazaar.com*  
**Use Case:**  
Evaluating the true return on investment (ROI) of branded search ads using a real-world natural experiment.

**Key Questions:**  
- Did suspending Google ads lead to a meaningful change in traffic?
- How does the ROI change under causal vs naïve estimation?
- Were the pre-treatment trends parallel across platforms?

**Techniques Used:**  
- **Difference-in-Differences (DiD)** for causal effect estimation  
- **Panel data modeling (fixed effects)** to control for unobserved heterogeneity  
- **Parallel trends testing** to validate DiD assumptions  
- **Log-transformation** to address skewness in traffic data

---

### 📄 04 Rmarkdown — *Advanced Causal Methods: Matching, Synthetic Control & RDD*  
**Use Case:**  
Applying advanced causal inference methods to estimate treatment effects in digital commerce, public policy, and ad auctions.

**Key Questions:**  
- Does directed search lead to higher sales in e-commerce?
- What was the impact of California’s cigarette tax policy?
- Does ad rank in online auctions influence click-through rate?

**Techniques Used:**  
- **Propensity Score Matching (PSM)** with caliper and covariate balance checks  
- **Log-linear regression** for percentage interpretation  
- **Synthetic Control Method** to construct a credible counterfactual  
- **Regression Discontinuity Design (RDD)** with sharp cutoff interpretation  
- **Causal assumptions** reviewed and validated for each technique

---

## Purpose

These assignments build up a progression of causal thinking — from interpreting experimental data correctly to using powerful non-experimental methods for real-world data.  
Together, they demonstrate how to rigorously establish causality in digital, educational, and policy-oriented environments.

---

