# Assignment 4: Evaluating Results from a Diagnostic Study

## Overview

This assignment evaluates Mirvie's Encompass test, an at-home blood test designed to predict who is likely to develop preterm preeclampsia later in pregnancy, allowing care teams to plan earlier.

## Approach

The Encompass test is collected through an at-home blood draw during mid-pregnancy (around 18–22 weeks) and examines RNA signals from the pregnant person, the placenta, and the fetus. The evaluation focuses on interpreting the test's sensitivity, specificity, and AUC from a validation study published in Nature Communications.

## Key Results

| Metric | Value | Interpretation |
|--------|-------|----------------|
| AUC | 0.88 | Strong overall discrimination for the placental-associated subtype |
| Sensitivity | 0.91 | Identifies about 91 out of 100 pregnancies that later develop the targeted preterm outcome |
| Specificity | 0.74 | About 26% of people without the outcome could still test "high risk" (false positives) |

## Key Takeaway

The Encompass test is a promising screening tool, not a diagnostic replacement. A sensitivity of 91% means roughly 9% of true cases could be missed (false negatives), creating potential false reassurance. A specificity of 74% means a meaningful number of people could receive high-risk results even without developing preterm preeclampsia. If paired with clear counseling about what "risk" means, it could help families and clinicians act earlier with more targeted monitoring.
