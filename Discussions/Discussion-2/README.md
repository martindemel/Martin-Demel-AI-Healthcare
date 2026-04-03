# Discussion 2: Multi-Source NICU Data

## Week Topic

Healthcare data types and sources relevant to AI development.

## Key Learnings

Healthcare AI is only as strong as the data feeding it, and in the NICU that data comes from many places. For one baby, electronic health record data includes diagnoses, medications, orders, and clinician notes. Lab systems add blood gas measurements. Bedside monitors generate continuous streams like heart rate and SpO2 trends. Devices contribute ventilator settings, and imaging adds chest X-rays. Combining these sources can turn a single moment into a timeline showing how a baby is changing over hours and days. Clinical registries like the Vermont Oxford Network standardize outcomes across hospitals, making multicenter research possible. Public deidentified datasets like MIMIC-IV show what ICU-quality structured data can look like and why consistent terminology standards (ICD-10, LOINC, SNOMED CT) are essential for reliable AI.

## Reflection

When NICUs combine EHR, monitor, ventilator, and imaging data, what is the best way to handle disagreements or missingness — for example, SpO2 values charted in the EHR versus continuous monitor values — and how do teams decide which version of truth should be fed into an AI model?
