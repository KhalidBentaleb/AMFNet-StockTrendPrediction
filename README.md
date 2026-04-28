# AMFNet: Adaptive Modality Fusion Network for Stock Trend Prediction  

Official implementation of **AMFNet**, as described in our work:  
*Adaptive Modality Fusion Network for Stock Trend Prediction*  


📄 Paper (IEEE Access): https://doi.org/10.1109/ACCESS.2025.3645089

---

## 📌 Overview  
AMFNet is a multimodal deep learning framework for **stock trend prediction**, integrating both **technical indicators** and **news sentiment signals**.  

The architecture combines:  
- 📊 A **Technical Encoder** (MLP) for financial indicators  
- 📰 A **Sentiment Encoder** (Transformer) for multi-source news sentiment with uncertainty  
- 🔀 A **Fusion Gate** for adaptive modality weighting  
- 🎯 A **Classifier** for predicting stock trend classes: {Neutral, Buy, Sell}  

AMFNet is evaluated on multiple stock tickers with daily OHLCV data and sentiment matrices, and benchmarked with both **classification metrics** and **portfolio-based evaluation** (CR, Sharpe ratio, MDD, Hit Ratio).  

⚠️ **Note**: The sentiment pipeline is simulated with random dummy data.  
⚠️ **Note**: This repository is a demonstration of the implementation (code + protocol), not a deployable trading system.  

---

## ⚙️ Requirements  
Install dependencies with:  

```bash
pip install -r requirements.txt
