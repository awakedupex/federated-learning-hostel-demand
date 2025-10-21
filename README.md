# Federated Learning Simulation – Hostel Library Demand

This project simulates **Federated Learning (FedAvg)** on synthetic hostel-wise data.  
Each hostel acts as a local client with non-IID data (exam periods, festival flags, study hours, etc.),  
and the goal is to predict **library demand (high/low)** without sharing raw data.

## Highlights
- Built synthetic dataset for 8 hostels × 365 days
- Implemented logistic regression with FedAvg aggregation
- Compared global FedAvg vs centralized model
- Achieved **90% global accuracy** vs **95.4% centralized baseline**

## Stack
- Python, scikit-learn, pandas, numpy, matplotlib
- Google Colab for simulation

## Results
| Model | Accuracy |
|--------|-----------|
| FedAvg (Global) | 0.90 |
| Centralized | 0.954 |

## Notebook
The full notebook is available in this repo:  
(https://colab.research.google.com/drive/1DUhCwTbgu55d_aDXmoPBIV4zdSJhPCSP?authuser=1#scrollTo=lVkgGBK3VLY1)

---



---
*Made by Adwait Eklavya| 2024ADPS0825G | BITS Goa | 2025*
