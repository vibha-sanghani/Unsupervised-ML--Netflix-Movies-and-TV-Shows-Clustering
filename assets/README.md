# Flutter ML Assets

This folder contains Flutter-compatible JSON files generated from the Netflix ML notebook.

## Files

- assets/ml/movies.json
- assets/ml/recommendations.json
- assets/ml/cluster_summary.json
- assets/ml/model_info.json

## Purpose

Flutter cannot directly run the Python Scikit-learn pickle model without a backend.

So the ML model runs in Google Colab, and the final model output is exported as JSON.

The Flutter app can use these JSON files as local assets to provide offline Netflix recommendations.

## Integration Rule

All movie data, recommendation data, cluster data, similarity scores, and model summary values must come dynamically from these JSON files.

Do not hardcode recommendation data in Flutter.
