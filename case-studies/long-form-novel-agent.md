# Long-form Novel Agent Workflow

## Product problem

Long-form creators need to detect setting drift, character-voice inconsistency and cross-chapter duplication without surrendering final editorial control to a model.

## Product design

- Converted subjective quality concerns into reproducible risks and a five-step creative SOP with ten quality standards.
- Managed long context through 16 character-control blocks and 12 dialogue fingerprints.
- Completed a 156-chapter, 402,165-character manuscript workflow while retaining human review.

## Evaluation

- Built a local consistency-check MVP with TXT import, five analysis categories, human review and multi-format export.
- On a fixed **48-item synthetic QA set**, F1 improved from **0.840 to 0.979**.
- A 156-chapter retest recorded P95 latency of **1.922 seconds**.

## Limitation

The QA set is synthetic and the project has not undergone a formal external-user study. Metrics demonstrate workflow consistency and engineering reproducibility, not market validation.

