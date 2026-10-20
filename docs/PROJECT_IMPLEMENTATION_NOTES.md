# Shravya's Underwater Vision Project — Implementation Notes

## Scope of supplied material
The original **2024–2025 Phase I synopsis** outlines a proposed underwater CNN/image-enhancement pipeline. The newer `object.pdf` interview notes, written in first person, **describe subsequent implementation work**. No runnable source, training notebook, labeled dataset, model weights or measured report was included with these documents; the GitHub repository is therefore still documentation-only.

## Shravya's reported workflow (interview notes)
1. Collected underwater imagery from **Kaggle**, with labels described as **fish, human and rock**.
2. Resized imagery to uniform dimensions; the notes use **224 × 224** as an example.
3. Used **OpenCV** for image preprocessing, including underwater color correction and denoising (Gaussian/median filters are discussed).
4. Split data for training/validation/testing; the notes describe **70% / 15% / 15%** as the split strategy.
5. Trained a **CNN classifier** to learn visual features and assign a class to each image.
6. Inspected model predictions and image-quality challenges.

These details are **self-reported** in the interview document. The exact dataset links, model code, training logs and test metrics still need to be supplied before technical claims can be independently reproduced.

## Classification vs detection
The notes clarify that the CNN primarily **classifies complete underwater images**. Object **localization with bounding boxes** would require an object detector such as YOLO as a future enhancement. This distinction should be preserved in job applications and in the portfolio.

## Challenge described
Underwater color distortion, lighting and particle noise can reduce prediction reliability. The notes describe preprocessing with color correction and denoising as a practical mitigation.

## Recommended next evidence
- Training/source code and dependency list
- Dataset provenance, permissions and class counts
- Train/validation/test split verification
- Confusion matrix and per-class scores
- Before/after enhancement examples with permission
- Representative inference demo screenshots that exclude private data

## Credits
Academic team: Shravya U Shetty, Srilakshmi HY and Suvarna. Faculty guide: Mrs. Reshma, Acharya Institute of Technology, Bengaluru.

## Source distinction
The Phase I synopsis is a planning document. The interview notes provide a **retrospective, self-reported implementation narrative**. This file reconciles their scope without promoting unverified results as independently measured outcomes.
