# Discussion 7: Bias in Healthcare AI

## Week Topic

Sources of bias in healthcare AI and governance frameworks for responsible deployment.

## Key Learnings

Bias in healthcare AI is not only a technical problem — it often starts in the data. The NICU is a clear example because decisions rely on fast, continuous signals. Selection bias occurs when a model is trained on infants from only a few large academic NICUs, so the risk score may not fit smaller hospitals or different communities. Information bias occurs when a measurement is systematically off; for example, pulse oximetry can overestimate arterial oxygen saturation in neonates, meaning an algorithm can look accurate while still learning from biased inputs. Governance is the practical safety net after deployment: transparent reporting, subgroup checks, and ongoing audits. The NIST AI Risk Management Framework provides a structure for making these controls routine so fairness is checked continuously, not just once at go-live.

## Reflection

When NICUs use AI risk tools to flag sepsis or respiratory decline, how should teams determine which subgroup checks matter most, and what is the appropriate response if the model performs well overall but is consistently less reliable for one group of babies?
