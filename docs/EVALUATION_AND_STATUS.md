# Evaluation Plan and Evidence Status

## Research objectives
- Recognize objects when underwater turbidity and light levels vary.
- Handle camera/noise variability and differing object shapes and sizes.
- Explore real-time processing for marine environmental monitoring.

## How a future implementation could be tested
1. Publish the dataset provenance, permissions, class definitions and annotation format.
2. Split subjects/scenes into separate train, validation and test partitions to reduce leakage.
3. Document preprocessing methods and baseline results.
4. Report relevant classification/detection metrics with class-by-class outcomes. Examples might include precision, recall and mAP **if a detector is implemented**.
5. Compare performance under clear water, haze/turbidity, low light and other environmental conditions.
6. Measure latency and hardware resource usage before claiming real-time operation.

## What the provided evidence actually establishes
- A Phase I synopsis and literature survey were prepared by the named student team at Acharya Institute of Technology in 2024–2025.
- The manuscript proposes CNNs, color correction, denoising, augmentation and potential transfer learning.
- It outlines an underwater camera / Raspberry Pi / transmission concept.

## Not independently established
- A public source-code implementation
- A trained detector or model weights
- The exact dataset and experiment split
- Reproducible project accuracy, mAP, processing speed or underwater deployment

**Do not copy accuracy values from the literature survey into project results.** Those figures refer to cited prior research.
