# Undergraduate_Thesis
Undergraduate thesis examining the effect of India's staggered VAT adoption on child mortality and household consumption, using a difference-in-differences framework (NFHS-4, NSS, Stata/reghdfe).

# Impact of VAT Adoption on Child Health Outcomes in India

**Author:** Vandana Goyal
**Supervisor:** Dr. Shampa Bhattacharjee
**Institution:** Department of Economics, Shiv Nadar Institution of Eminence
**Submitted:** May 2026 | B.Sc. (Research) in Economics

## Abstract
This study examines whether the staggered adoption of Value Added Tax (VAT) across Indian states affected child mortality outcomes. Using child-level data from the National Family Health Survey (NFHS-4) and household consumption data from the NSS Consumer Expenditure Surveys, the paper estimates the effect of VAT exposure on infant mortality, under-five mortality, and monthly per capita consumption expenditure (MPCE), exploiting variation in the timing of VAT adoption across states in a difference-in-differences fixed effects framework. Across all specifications, VAT exposure shows statistically insignificant effects on both child mortality and household consumption — results that remain robust to household controls, state-specific time trends, and mother fixed effects.

## Method
- **Design:** Difference-in-differences (DiD), exploiting staggered state-level VAT rollout (2005–2008)
- **Data:** NFHS-4 (child mortality, 892,856 / 686,389 obs.), NSS Consumer Expenditure Surveys 55th/61st/68th rounds (193,120 households), VAT adoption timing from Agrawal & Zimmermann (2024)
- **Estimation:** OLS via `reghdfe` in Stata, state + year/round fixed effects, state-specific trends, mother fixed effects, standard errors clustered at state level

## Key Finding
VAT adoption had no statistically significant effect on infant mortality, under-five mortality, or household consumption expenditure — a robust null result across specifications, suggesting the welfare consequences of VAT in India were more limited than theoretical concerns about regressive indirect taxation would predict.

## Contents
- `UndergraduateThesis_VandanaGoyal.pdf` — full thesis
