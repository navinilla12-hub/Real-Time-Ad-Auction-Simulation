# Real-Time Ad Auction Simulation System

## Overview
This project simulates how modern digital advertising platforms (Demand-Side Platforms) rank and select ads in real-time auctions.

It models key components of an ad-tech system including:
- Click-Through Rate (CTR) estimation
- Bid calculation strategies
- Auction-based ranking
- Budget-constrained ad selection

---

## Objective
To design a simplified, scalable system that mimics how ads are selected and optimized for maximum performance under budget constraints.

---

## Workflow

1. **Data Generation**
   - Created a synthetic dataset simulating user behavior (time on site, internet usage, demographics)

2. **Feature Engineering**
   - Normalized key features for consistent modeling

3. **CTR Probability Modeling**
   - Estimated click probability using weighted behavioral signals

4. **Bidding Strategy**
   - Assigned bids based on predicted CTR

5. **Auction Ranking**
   - Ranked ads based on bid values (highest bid wins)

6. **Budget Optimization**
   - Selected top-performing ads within a fixed budget constraint

---

## Key Concepts

- Real-Time Bidding (RTB)
- CTR Prediction
- Auction-Based Ranking Systems
- Optimization under Budget Constraints

---

## Results

- Selected ads achieved significantly higher average CTR compared to overall dataset
- Demonstrated efficient allocation of limited advertising budget
- Simulated realistic ad selection behavior used in production ad systems

---

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn

---

## Future Improvements

- Integrate machine learning models (Logistic Regression, XGBoost) for CTR prediction
- Implement reinforcement learning for dynamic bidding strategies
- Scale pipeline using PySpark for large datasets
- Deploy as an interactive dashboard using Streamlit

---

## 📂 Project Structure
