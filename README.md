# MSBA 6441 – Causal Inference Assignments

Welcome to this repository for MSBA 6441, which includes four hands-on assignments tackling causal inference problems using real-world data and a variety of experimental and quasi-experimental methods. All work was done using **R Markdown** and rendered into PDF reports, combining both rigorous statistical analysis and clear communication of results.

Across the four assignments, we explore the effectiveness of platform incentives, digital advertising, search engine marketing, public policy, and auction mechanisms. The techniques applied span from basic t-tests and linear models to advanced methods like Difference-in-Differences, Propensity Score Matching, Synthetic Control, and Regression Discontinuity Designs.

---

## 01_Rmarkdown – Reddit Gold & Balsakhi Tutoring Program

This assignment evaluates two separate experiments. First, we investigate whether receiving **Reddit Gold** increases user activity on the platform. We compare control and treatment groups across various metrics and use linear regression and interaction analysis to measure treatment effects and heterogeneity. The analysis concludes that receiving Reddit Gold significantly increases posting behavior, especially among first-time posters.

The second part analyzes the **Balsakhi program**, a supplemental education intervention in Indian public schools. Using pre/post test scores and randomized treatment allocation, we assess whether the intervention improves performance in math and language. Statistical tests confirm improvement in both areas post-intervention, and we evaluate the validity of causal assumptions including SUTVA.

---

## 02_Rmarkdown – Star Digital Display Ad Effectiveness

This case centers around **Star Digital's large-scale randomized online ad campaign**. Our goal was to determine whether display advertising affects purchase behavior, whether ad frequency matters, and which ad platforms provide the best ROI.

Using logistic regression, we found suggestive (though not strongly significant) evidence that advertising impacts purchase likelihood. However, the interaction between **ad exposure frequency** and purchase probability was highly significant, suggesting that repeated exposure strengthens ad effectiveness. We also compared ad platforms (Sites 1–5 vs. Site 6) by calculating **cost-per-conversion**, ultimately recommending a blended strategy to balance reach and efficiency.

---

## 03_Rmarkdown – Sponsored Search Ads at Bazaar.com

This assignment analyzes a **natural experiment**: a technical glitch that caused Bazaar.com’s sponsored Google ads to disappear for several weeks. We use this “accidental” pause to estimate the true ROI of branded search ads.

Using a **Difference-in-Differences** (DiD) approach, I compare traffic trends across search platforms (Google as treatment; Bing, Yahoo, Ask as controls). The analysis reveals a **67% drop in total branded traffic** post-interruption, showing that ads were indeed driving substantial incremental visits—not just cannibalizing organic clicks. This sharply contrasts with a naive ROI estimate that overstates ad value, highlighting the importance of **causal methods in marketing analytics**.

---

## 04_Rmarkdown – Advanced Causal Methods

This assignment showcases three advanced causal techniques across different industries:

- **Propensity Score Matching (PSM)** was used to estimate the effect of directed search on retail purchases. After matching users on demographics and behavior, found a strong and statistically significant lift in promoted sales, confirming that intent-driven sessions yield higher conversion.
  
- Using the **Synthetic Control Method**, evaluated California’s **cigarette tax policy**. By constructing a counterfactual “synthetic California,” assessed whether sales declined more than expected post-policy. The results validated the policy’s effectiveness in reducing cigarette consumption.
  
- Finally, applied a **Regression Discontinuity Design (RDD)** to online auction data. We assessed whether **ad position rank** influences click-through rates, exploiting the cutoff between rank 1 and 2. The analysis confirmed a clear jump in engagement for top-ranked ads, reinforcing the value of premium placement.

---

📎 All PDFs and code were rendered using R Markdown. The `.Rmd` files and compiled reports are included in this repository.

