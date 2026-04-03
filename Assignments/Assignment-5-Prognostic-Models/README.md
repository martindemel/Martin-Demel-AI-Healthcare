# Assignment 5: Prognostic Models

## Overview

This assignment examines a prognostic model developed by Kanzawa and colleagues (2025) to predict severe bronchopulmonary dysplasia (BPD) in very premature infants in the NICU.

## Approach

The model is a decision tree with day 7 and day 14 versions that uses only two variables already available in routine NICU care: gestational age and the respiratory severity score (mean airway pressure multiplied by the fraction of inspired oxygen). A multicenter cohort in Japan was used for development and a separate cohort for external validation.

## Key Results

| Timepoint | Training c-statistic | Validation c-statistic |
|-----------|---------------------|----------------------|
| Day 7 | 0.789 | 0.753 |
| Day 14 | 0.779 | 0.827 |

These results align with a meta-analysis finding a median external validation c-statistic of 0.77 across validated BPD models.

## Strengths and Limitations

**Strengths:** Simple and usable at the bedside; uses only two routinely collected variables; externally validated; tree format provides clear cutoffs.

**Limitations:** Retrospective design; possible differences in ventilation practices across hospitals; applicable only to infants still requiring ventilation after one week; prediction studies can perform well on paper but still fail in new settings if bias or practice differences are not addressed.

## Key Takeaway

This model is useful as a bedside screening tool because it is simple and still showed solid accuracy in an external cohort. Prospective testing in more diverse NICUs is needed to confirm it improves outcomes, not only prediction scores.
