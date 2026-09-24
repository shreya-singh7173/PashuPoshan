# PashuPoshan
AI-based cattle feed visual quality assessment using image processing, color and texture descriptors and machine learning. 

Pashu Poshan is an in-development machine learning project that aims to estimate the visual quality of cattle feed using image processing, color and texture features, and supervised machine learning.

The goal is to develop a system where a user can upload an image of cattle feed and receive a visual quality category based on patterns learned from a properly collected and labelled dataset.

## Project Objectives

- Process cattle-feed images to prepare them for analysis.
- Extract 12 relevant color and texture descriptors from images.
- Develop a supervised machine learning model to classify visual quality.
- Build a simple interface for users to upload images and view predictions.

## Proposed Workflow

1. **Image Input:** The user uploads or captures an image of cattle feed.
2. **Image Preprocessing:** The image is prepared for consistent feature extraction.
3. **Feature Extraction:** Color and texture descriptors are extracted from the image.
4. **Model Prediction:** A trained machine learning classifier predicts the visual quality category.
5. **Result Display:** The system displays one of three proposed categories:

| Category | Meaning |
|---|---|
| Green | Good visual quality |
| Yellow | Moderate visual quality |
| Red | Poor visual quality |

## Project Structure

- `dataset/` — Dataset documentation and organization.
- `preprocessing/` — Image preprocessing methods.
- `feature_extraction/` — Color and texture feature extraction.
- `model/` — Model training, evaluation, and prediction.
- `notebooks/` — Exploratory data analysis and experiments.
- `app/` — Planned user-facing application.

## Current Development Status

**Status: Under Development**

The dataset has not yet been collected and labelled. Feature selection, model training, evaluation, and application development are planned stages.

No trained model or validated prediction results are currently available.

## Technology Stack

Planned tools and libraries:

- Python
- OpenCV or scikit-image for image processing
- NumPy and pandas for data handling
- scikit-learn for machine learning

The final tools and methods will be selected as the project develops.

## Scope and Limitations

This project focuses on estimating the visual quality of cattle feed from images.

Visual appearance alone cannot establish nutritional composition, chemical quality, toxin levels, microbial contamination, or overall feed safety. The system is intended as a visual assessment aid, not a replacement for laboratory testing or professional veterinary advice.

## Future Work

- Collect and label a suitable cattle-feed image dataset.
- Finalize the 12 visual descriptors.
- Train and evaluate suitable classification models.
- Develop an image-upload interface.
- Test the system on images not used during model training.
