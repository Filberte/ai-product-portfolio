# Vision AI Evaluation

> Sanitized internship and post-internship reproduction case study. Upstream projects, model weights and datasets are not redistributed.

## Internship-period delivery

- Completed Qwen gesture-data and LoRA training experiments.
- Integrated object detection, road segmentation and lane experiments into a GUI supporting image, video and camera inputs.
- Organized validation around 200 synthetic road samples.

## Post-internship independent reproduction

- Rebuilt the gesture evaluation path on a **385-image clean holdout**, improving accuracy from **78.96% to 97.40%** and achieving **100%** structured-output compliance.
- Fixed JPEG label decoding, used validation-only model selection and a one-time test evaluation; obtained foreground IoU **0.5772** and Dice **0.7319** on the retained test set.

## Product interpretation

The case demonstrates how model capability, output reliability, latency and deployment constraints inform a lightweight CV/VLM product-selection strategy. It does not claim production deployment or user adoption.

