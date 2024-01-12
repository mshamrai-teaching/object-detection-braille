# Computer Vision Course Assignment: Braille Character Detection

## Overview

Welcome to the Braille Character Detection assignment for the Computer Vision course! In this assignment, you will be working on detecting and classifying Braille characters using Selective Search for region proposal.

### Task

Your objective is to:

1. Apply Selective Search for region proposal on Braille images.
2. Classify regions with the algorithm you created before or:
   * Find data.
   * Extract features from the proposed regions using a classic feature extractor (e.g., HOG, SIFT).
   * Train a classifier to recognize and classify Braille characters.
4. Evaluate your solution on previously provided images.

### Getting Started

1. **Clone this repository to your local machine:**
     ```bash
     git clone https://github.com/mshamrai-teaching/object-detection-braille-*your-name*
     ```
2. **Navigate to the project directory:**
      ```bash
       cd object-detection-braille-*your-name*
      ```
 
### Hints

* Region Proposal:
  * Tune parameters for Selective Search to obtain meaningful region proposals.
  * Experiment with different region proposal methods to find the most suitable for your task.
* Feature Extraction:
  * Choose a feature extractor that captures relevant information for Braille character classification.
  * Consider experimenting with different feature extraction techniques to improve accuracy.
* Classifier:
  * Train a classifier with a suitable algorithm (e.g., SVM, Random Forest) on the extracted features.
  * Fine-tune hyperparameters for optimal performance.

### Submission

To submit your solution create pull request to the `main` branch.

Ensure your final submission includes:
* Source code (braille_detection.py or similar).
* A brief report (report.md or similar) explaining your approach, the choice of feature extractor, classifier, and any challenges faced.

### Evaluation

Your solution will be evaluated based on your code quality and detection capability. 

Good luck, and enjoy working on Braille character detection! If you have any questions, feel free to reach out.
