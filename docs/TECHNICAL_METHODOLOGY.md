# Technical Methodology — Phase I Proposal

## Research problem
Underwater image analysis is impacted by poor visibility, light scattering, uneven illumination and background clutter, making marine animal and object detection difficult.

## Target objects
- Fish species
- Marine animals
- Rocks and underwater formations

## Proposed pipeline
1. Capture underwater images from a suitable camera.
2. Correct underwater color cast, enhance contrast and reduce sensor/scattering noise.
3. Annotate example imagery and partition into training and evaluation sets.
4. Apply augmentation (brightness, visibility and transformation variations).
5. Train a CNN-based classifier or detector, potentially using transfer learning.
6. Evaluate detection/classification quality across visibility and lighting conditions.
7. Consider edge/cloud processing and Raspberry Pi-based communication if a robot prototype is developed.

## Possible tools listed in the synopsis
Python; OpenCV for enhancement; TensorFlow or PyTorch for learning; transfer learning; YOLO, Faster R-CNN or U-Net as potential detection approaches. Listing an architecture is not evidence of its implementation.

## Proposed system design notes
The synopsis also explores integrating an underwater camera with signal encoding, wireless transmission to a processing station, and Raspberry Pi-based processing/communications. That component is conceptual in the source material.

## Important distinction
This page describes the **planned methodology in a Phase I academic synopsis**, not tested model code. No training artifacts, datasets, weights or reproducible metrics have been supplied.
