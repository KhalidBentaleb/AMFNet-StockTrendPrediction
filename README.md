# AMFNet: Adaptive Modality Fusion Network for Stock Trend Prediction  

Official implementation of **AMFNet**, as described in our work:  
*Adaptive Modality Fusion Network for Stock Trend Prediction*  

---

## 📌 Overview  
AMFNet is a multimodal deep learning framework for **stock trend prediction**, integrating both **technical indicators** and **news sentiment signals**.  

The architecture combines:  
- 📊 A **Technical Encoder** (MLP) for financial indicators  
- 📰 A **Sentiment Encoder** (Transformer) for multi-source news sentiment with uncertainty  
- 🔀 A **Fusion Gate** for adaptive modality weighting  
- 🎯 A **Classifier** for predicting stock trend classes: {Neutral, Buy, Sell}  

AMFNet is evaluated on multiple stock tickers with daily OHLCV data and sentiment matrices, and benchmarked with both **classification metrics** and **portfolio-based evaluation** (CR, Sharpe ratio, MDD, Hit Ratio).  

---

## ⚙️ Requirements  
Install dependencies with:  

```bash
pip install -r requirements.txt
