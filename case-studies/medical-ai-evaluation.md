# Medical AI Evaluation

> Sanitized case study based on the public CDD-CESM dataset. No medical images, patient identifiers or model weights are published.

## Internship-period delivery

- Reproduced a three-class medical AI and Grad-CAM evaluation chain using LE/SUB × CC/MLO multi-view inputs.
- Connected doctor-label comparison with failure-case review.

## Post-internship independent audit

- Audited **2,006** images and identified **97.7% patient-level leakage** in the legacy test split.
- Rebuilt a zero-overlap patient split, repeated duplicate and label-conflict checks, and formed **435** four-view breast-side samples.
- Connected **114** test breast sides, predictions, Grad-CAM and risk warnings to a review workbench supporting accept/correct/escalate decisions.

## Product interpretation

The main product result is not a higher headline accuracy. It is an auditable evaluation contract: patient-level isolation, validation-only selection, one frozen test and explicit human escalation for uncertain or safety-sensitive outputs.

