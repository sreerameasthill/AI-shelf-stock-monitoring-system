# AI-Based Shelf Stock Monitoring System

This project implements a real-time inventory monitoring system using Computer Vision and Machine Learning to automatically detect low stock levels and trigger WhatsApp reorder alerts.

## Business Problem
Manual shelf monitoring in retail stores leads to stock-outs, lost sales, and inefficiencies. This system automates shelf-level inventory tracking.

## Solution Overview
- Real-time bottle detection using OpenCV
- ML-based bottle count prediction using Random Forest
- Ensemble logic combining CV and ML
- Automated WhatsApp alert when stock falls below threshold

## Technologies Used
- Python
- OpenCV
- Scikit-learn (Random Forest)
- NumPy, Pandas
- PyWhatKit (WhatsApp automation)
- Jupyter Notebook

## Dataset
- 650+ real-world images collected via webcam
- Labels stored in CSV/Excel format
- Images preprocessed (64×64 resize, normalization)

## Model Performance
- Mean Absolute Error (MAE): 0.00
- Rounded Accuracy: 100%

## Key Features
- Real-time webcam monitoring
- Lock-based alert mechanism to avoid duplicate alerts
- Adjustable thresholds via UI controls

## Future Enhancements
- Multi-product detection
- Cloud dashboard integration
- ERP / SCM system integration

