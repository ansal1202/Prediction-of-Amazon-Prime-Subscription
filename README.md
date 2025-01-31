# Prediction-of-Amazon-Prime-Subscription

## 專案簡介
* 目標：預測使用者的定閱模式，找出最具價值的客戶以及潛在客戶。
* 數據來源：kaggle。
* 開發工具：Google Colab，用於執行 Jupyter Notebook 並加速訓練。

## 專案功能
* 數據預處理：處理缺失值、異常值。
* 數據探索（EDA）：生成數據分佈圖、相關性熱圖。
* 特徵工程：構建新的特徵並篩選最具影響力的特徵。
* 模型訓練：使用Decision Tree來進行訓練並預測結果，使用PyTorch計算損失函數。
* 超參數優化：找出最佳參數組合


## 技術工具
* 數據處理：Pandas
* 可視化：Matplotlib, Seaborn
* 模型訓練：Scikit-learn,PyTorch

## 專案概述

* 目標：預測使用者的定閱模式，找出最具價值的客戶以及潛在客戶。
* 數據來源：kaggle。
* 開發工具：Google Colab，用於執行 Jupyter Notebook 並加速訓練。

## 本專案包含兩個主要分析主題：

* Amazon訂閱用戶分析
* Amazon 使用者 RFM 分析

## 專案結構

1. Amazon訂閱用戶分析

* data_preprocessing.ipynb: 數據讀取與清理
* eda.ipynb: 探索性數據分析（EDA）
* feature_engineering.ipynb: 特徵工程
* modeling.ipynb: 模型訓練與超參數調整

2. Amazon Userbase RFM Analysis

* rfm_analysis.ipynb: RFM 分析
* customer_retention.ipynb: 客戶留存率及流失率分析

## 環境設置

請確保已安裝以下 Python 套件：

pandas

numpy

matplotlib

seaborn

scikit-learn


主要發現

* 訂閱用戶的行為特徵如何影響留存率
* 使用RFM分析進行客戶分群

