# AI Fitness Tracker

> [!NOTE]
> This project was built as a MVP during a hackathon and won 1st place. It is presented in its original form with no further development or production optimisation.

## Overview

A real-time fitness tracking system that uses machine learning to classify human activities from accelerometer data and provide live health metrics, visualisation dashboards and workout recommendations.

This project demonstrates a complete end-to-end pipeline for activity recognition and fitness tracking:

* Simulated sensor data generation
* Feature extraction from time-series signals
* ML model training and evaluation
* Real-time prediction system
* Interactive dashboard with health metrics
* Full GUI application with optional mobile integration

## Key Concepts

* Time-series data processing
* Feature engineering
* Supervised ML
* Real-time prediction systems
* Human activity recognition
* Interactive UI development in MATLAB

## Project Flow

1. Data simulation
2. Feature extraction
3. Model training and evaluation
4. Real-time activity recognition
5. Live fitness metrics
6. Live dashboard
7. Smart recommendation system
8. Full GUI application
9. Mobile Integration (optional)

## Limitations

* Uses synthetic data (not validated on real-world datasets)
* Simplified physiological models for heart rate and calories
* Limited to 4 activity classes
* Not optimsied for deployment or large-scale use

## Possible Future Improvements

* Use real-world datasets eg. wearable sensor data
* Implement deep learning models eg. LSTM for time-series
* Improve physiological modelling accuracy
* Deploy as mobile or web app
* Add more activities eg. stair climbing, workouts

## Requirements and Usage

1. MATLAB (R2021a or later recommended), Statistics and Machine Learning Toolbox, MATLAB Mobile (for mobile sensor integration)
2. Run fitness_model_training to train the model
3. Run fitness_live_dashboard to launch live dashboard
4. Run fitness_tracker_mobile_app to launch full GUI app

## License

This project is for educational and demonstration purposes only.
