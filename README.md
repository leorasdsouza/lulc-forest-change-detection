# LULC Forest Cover Change Detection

## Project Overview

This project focuses on Land Use Land Cover (LULC) classification and forest cover change detection using Sentinel-2 satellite imagery for Dakshina Kannada district.

The main objective was to analyze forest cover changes between 2017 and 2025 by performing classification on satellite imagery from both years and comparing the results to identify deforestation and land cover transitions.

The project uses Python-based deep learning and remote sensing workflows to generate reliable forest quantification results and support environmental monitoring.

---

## Files Included

- `2017_Forest.py` – LULC classification workflow for 2017 satellite imagery
- `FinalUntitled25.py` – LULC classification workflow for 2025 satellite imagery
- `comparison_2017_2025.py` – Forest cover change detection and comparison analysis between 2017 and 2025

---

## Technologies Used

- Python
- Google Earth Engine
- TensorFlow
- Scikit-learn
- NumPy
- Matplotlib
- Streamlit
- Sentinel-2 Satellite Data

---

## Solution Developed

The project includes:

- Preprocessing Sentinel-2 imagery
- Binary and multi-class LULC classification
- Forest and non-forest area detection
- Deep Embedded Clustering (DEC) based classification
- NDVI-based vegetation health analysis
- Comparison of classified outputs from 2017 and 2025
- Forest loss quantification and change mapping

The classified outputs were validated using Google Dynamic World for improved accuracy and reliability.

---

## Results

- Achieved 93.15% classification accuracy
- Detected approximately 4.2% net forest loss across Dakshina Kannada district
- Estimated around 150 km² forest area reduction between 2017 and 2025
- Generated comparison maps for high-confidence forest change detection

---

## Future Scope

- GPT-assisted automated report generation
- Real-time forest monitoring dashboards
- Improved multi-temporal satellite analysis
- Integration of advanced deep learning models for higher classification accuracy

---

## Purpose

This project supports sustainable forest monitoring, environmental planning, and better decision-making using AI and remote sensing technologies.
