# Data Science & Machine Learning Projects

This repository contains reports for three of my main projects, covering topics from adversarial machine learning to sentiment analysis and NBA salary prediction.

---

## 1. Comparison between Encoder and Decoder-only Models for Sentiment Analysis
**Objective:** Compare the performance of encoder-based (BERT) and decoder-only (LLaMA 3) models on sentiment analysis using the IMDB dataset, with a focus on low-compute settings.  
**Key Points:**  
- Evaluates whether decoder-only models can outperform encoder-based models in accuracy and usability for standard users.  
- Explores different prompt strategies to assess their impact.  
**Report:** `Encoder_vs_Decoder_Sentiment_Analysis.pdf`  

---

## 2. Fooling Neural Networks with Optimization: Frank-Wolfe and PGD Methods in Machine Learning (MNIST & ImageNet Study)
**Objective:** Investigate how optimization techniques can craft adversarial examples that mislead deep neural networks with imperceptible input changes.  
**Key Points:**  
- Implemented Frank-Wolfe variants (standard, momentum, away-step, pairwise) and PGD / MI-FGSM.  
- Experiments under L2 and L∞ norm constraints on MNIST and ImageNet datasets.  
- Frank-Wolfe with momentum achieves high attack success rates with lower distortion and efficient convergence.  
**Report:** `Fooling_Neural_Networks_Optimization.pdf`  

---

## 3. NBA Players’ Salary Prediction Based on Performance
**Objective:** Examine whether NBA player salaries for the 2023-2024 season are fair relative to their regular-season performance.  
**Key Points:**  
- Analyzes common stats (points, rebounds, assists) and advanced metrics (Usage, Player Impact Estimate, Win Shares).  
- Uses various models to determine which stats best correlate with salaries and identify the most accurate model.  
- Compares actual vs. predicted salaries to highlight overpaid and underpaid players.  
- Includes position-specific models (centers, forwards, guards) to explore group-specific differences.  
**Report:** `NBA_Salary_Prediction.pdf`  

---

### Repository Contents
- `Encoder_vs_Decoder_Sentiment_Analysis.pdf`  
- `Fooling_Neural_Networks_Optimization.pdf`  
- `NBA_Salary_Prediction.pdf`  
