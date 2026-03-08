# Hybrid Intrusion Detection System — Network Traffic Analysis

A network-level intrusion detection framework focused on 
DDoS attack identification through traffic feature engineering.

## What This Is About
- Engineered 79 network flow features from raw CIC-IDS datasets
- Built a feature extraction pipeline from pcap-style traffic records
- Applied explainable AI (SHAP) to identify which flow features 
  contribute most to attack classification

## Focus
The core contribution is the **traffic feature engineering pipeline** —
extracting meaningful signals from raw network flows, not the model itself.

## Tech Stack
- Python, Scikit-learn, TensorFlow
- CIC-IDS2017/2018 datasets
- SHAP for feature transparency

## Status
Code cleanup and documentation in progress.
