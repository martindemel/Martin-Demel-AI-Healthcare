# Assignment 3: Clinical Decision Support Systems

## Overview

This assignment envisions an AI-powered clinical decision support system (CDSS) designed for the neonatal intensive care unit, modeled after tools such as Glass Health that use large language models with medical knowledge retrieval.

## Approach

The proposed system integrates into the electronic health record and is tuned for premature infants whose conditions change hour by hour. It continuously ingests monitoring trends, ventilator data, lab results, imaging reports, medication administrations, maternal history, and clinical notes, then updates a single living summary. The design uses retrieval-augmented generation (RAG) to stay grounded in curated clinical references, improving factuality and safety compared with a standalone language model.

## Key Design Features

- **Differential generation** — when a baby develops new apnea, bradycardia, or feeding intolerance, the system generates a differential, suggests next tests, and drafts an assessment aligned with neonatal guidelines
- **Clinician-in-the-loop** — offers options with brief rationale and citations, requiring clinician sign-off before anything becomes an order
- **Shared team view** — nurses, pharmacists, and respiratory therapists view the same snapshot so questions surface quickly
- **Predictive modules** — monitor for early deterioration, building on work where ML recognized neonatal sepsis hours before clinical recognition

## Key Takeaway

AI-powered decision support could make neonatal care safer and more consistent while freeing time for explanation and bedside presence. However, challenges remain around bias in training data, model drift, and privacy risks. The best future is one in which evidence-based systems are carefully evaluated, openly monitored, and treated as supervised teammates that strengthen clinical judgment rather than replace it.
