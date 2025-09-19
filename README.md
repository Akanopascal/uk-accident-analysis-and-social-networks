# UK Traffic Accident Forecasting & Facebook Social Network Analysis

This project includes two real-world applications of data mining and big data analysis using Python:
1. **Traffic accident prediction and policy recommendations** based on UK 2019 road incident data
2. **Community structure and centrality exploration** in a Facebook-based social network using graph theory

---

## Project Overview

### Task A: Traffic Accident Data (UK 2019)
- Used clustering (K-Means, LOF), Apriori association rules, and Holt-Winters time series forecasting
- Predicted accident trends for 3 police regions (Metropolitan, Greater Manchester, Cleveland)
- Identified top 30 high-risk LSOAs in Hull and forecasted daily trends
- **Key Models**: Holt-Winters Exponential Smoothing, Apriori, K-Means, LOF
- **Key Result**: Cleveland region forecasting performed best (MAE: 4.26)

### Task B: Social Network Analysis (Facebook)
- Constructed a social graph with 4,039 nodes and 88,234 edges using NetworkX
- Analyzed centrality (degree, edge betweenness) to identify hubs and bridges
- Detected communities using **Louvain** and **Greedy Modularity** algorithms
- **Key Finding**: Scale-free structure and clear modular communities typical of real-world networks

---

## Tools & Libraries
Python · Pandas · NumPy · scikit-learn · Matplotlib · Seaborn · NetworkX · statsmodels

---

## 📁 Repository Structure
- `notebooks/` — Jupyter notebooks for each task  
- `reports/` — PDF of the final report    
- `requirements.txt` — Required Python libraries

---

## Author
**Pascal Ugonna Akano**  
MSc Artificial Intelligence & Data Science  
University of Hull
