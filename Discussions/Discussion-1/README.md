# Discussion 1: Deep Learning for BPD Prediction

## Week Topic

AI fundamentals and how deep learning applies to healthcare imaging.

## Key Learnings

AI in healthcare can extract clinically meaningful information from tests that NICUs already run regularly, such as chest X-rays. A 2025 study by Ozcelik et al. used a DenseNet121 deep learning model trained on chest radiographs from preterm infants (less than or equal to 28 weeks' gestation) to predict bronchopulmonary dysplasia and classify severity. Because the images were paired with labeled outcomes, this is supervised learning. Predictions improved when later weekly X-rays (around weeks 2–4) were included, suggesting the model tracks evolving lung pathology over time, not just a single snapshot.

## Challenges

Understanding how supervised learning applies to imaging required distinguishing between the model architecture (DenseNet121), the learning paradigm (supervised), and the clinical context (longitudinal X-ray series). Connecting these layers while also learning foundational AI vocabulary was the main challenge this week.

## Reflection

How do NICUs validate that an X-ray model trained at one hospital remains accurate at other hospitals with different machines and imaging practices? How should imaging-based predictions be combined with blood gas trends without over-trusting the algorithm?
