# Discussion 8: NLP for Clinical Notes

## Week Topic

Natural language processing (NLP) applications in clinical documentation and neonatal care.

## Key Learnings

NLP can convert unstructured NICU notes into usable data. In neonatal care, some of the most important details are found in admission notes, daily progress notes, genetics consults, and discharge summaries rather than in neat checkboxes. Common NLP applications include note classification, named entity recognition (which pulls out terms like diagnoses or medications), and text summarization. Peterson and colleagues (2025) described the Mendelian Phenotype Search Engine, which combines clinical NLP with machine learning to prioritize newborns for whole-genome sequencing within the first 48 hours after NICU admission. Interpreting NLP metrics requires care: precision indicates how often the model is correct when it flags something, recall measures how many actual cases it detects, and the F1 score balances both. Accuracy alone can be misleading in imbalanced medical data, which is especially important for rare neonatal conditions.

## Challenges

Understanding why accuracy alone is misleading for rare neonatal conditions (class imbalance) and learning to evaluate NLP with precision, recall, and F1 instead was the key conceptual hurdle this week.

## Reflection

If a NICU uses NLP to extract phenotype clues or medication details from notes, how should the team validate the model across different note templates, shorthand styles, and rotating providers so that missed findings do not quietly impact downstream decision support?
