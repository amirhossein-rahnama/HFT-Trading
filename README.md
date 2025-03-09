# HFT-Trading



### High-Frequency Trading (HFT) Framework: Machine and Deep Learning Applications  

This project introduces a comprehensive framework for high-frequency trading (HFT), utilizing machine learning (ML) and deep learning (DL) techniques. Originally developed by Bradley, this framework has been modified and enhanced to incorporate additional features, making it a robust and adaptable pipeline for extracting trading signals and predicting market dynamics. 

---

### **Objectives**  

1. Extract trading signals directly from Level-II order book data.  
2. Predict order book dynamics using state-of-the-art machine learning and deep learning methodologies.  

---

### **Data Source**  

The project utilizes tick-level depth data from financial futures markets, focusing on detailed order book information. This granular data is key to building accurate trading signals and predicting short-term market movements.  

---

### **Strategy Pipeline**  

The framework implements a structured pipeline for data processing, feature extraction, and model training. Below is an illustrative representation of the pipeline

---

### **Order Book Signals**  

The framework leverages limit order book data to design meaningful trading signals. Key signals include:  

- **Depth Ratio:** Measures the proportion of bid and ask volume across levels.  
- **Rise Ratio:** Indicates price movement trends by comparing best bid and ask prices over time.  
- **Order Book Imbalance (OBI):** Tracks the disparity between buy and sell orders in the order book.  

---

### **Price Series Visualization**  

A visual overview of price dynamics, including best bid and ask prices, helps in identifying trends and anomalies:  

*(Visualization placeholder: "Best Bid/Ask Price Series")*  

---


#### **Additional Signals**  
The framework allows the inclusion of custom signals such as:  
- Volume Imbalance.  
- Trade Imbalance.  
- Technical indicators like RSI and MACD.  
- Weighted average price metrics (WAP, VWAP, TWAP).  

---

### **Model Fitting**  

#### **Baseline Models**  
The framework includes several standard classification models:  
- Random Forest Classifier.  
- Extra Trees Classifier.  
- AdaBoost Classifier.  
- Gradient Boosting Classifier.  
- Support Vector Machines.  
- Neural Networks: MLP, LSTM.  

#### **Hyperparameters**  
- Training Window: 30 minutes.  
- Test Window: 10 seconds.  
- Prediction Label: 15-minute forward price movement.  


---

### **Future Enhancements**  

#### **Feature Engineering**  
- Incorporate advanced signals:  
  - Volume and trade imbalances.  
  - Moving averages and weighted averages of key signals.  
  - Advanced regression techniques (e.g., Lasso, genetic programming).  

#### **Model Upgrades**  
- Experiment with more sophisticated models:  
  - Convolutional Neural Networks (CNN).  
  - Recurrent Neural Networks (GRU, LSTM).  
  - Gradient Boosting frameworks (XGBoost, LightGBM).  
  - Attention mechanisms, auto-encoders, and TabNet.  
  - Pre-trained models tailored to financial data.  

#### **Refining Metrics**  
- Enhance performance metrics, accounting for PnL adjustments, transaction costs, and commission fees for a more realistic evaluation.  


This HFT framework, originally developed by **Bradley**, has been modified and enhanced to expand its capabilities. By combining ML/DL techniques with robust feature engineering, it provides a versatile toolkit for developing and testing high-frequency trading strategies. Future enhancements can further elevate its performance and adaptability to meet evolving market demands.
